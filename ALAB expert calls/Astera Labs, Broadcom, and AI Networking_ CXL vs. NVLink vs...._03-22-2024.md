Astera Labs, Broadcom, and AI Networking: CXL vs. NVLink vs. PCIe ¡ª How Is the
Market Evolving?

Primary:

  ALAB

  AVGO

  NVDA

  MRVL

Associated:

  ANET

  CSCO

  CRDO

Viewpoint:

Industry Consultant

Moderator: Kirang Gohil (KG)

| Mar 22, 2024 | 45 Min Read

Timothy Prickett-Morgan (TP), Co-Editor - The Next Platform

  SU MMARY

Overview

The discussion, led by Timothy Prickett-Morgan, co-editor of The Next Platform, and moderated by Kirang Gohil from Guidepoint,
delves into the evolving landscape of AI server interconnects, focusing on PCIe, CXL, and NVLink. The conversation highlights the
roles of Astera Labs and Broadcom in the PCIe Re-Timer market and explores the use of CXL memory controllers. The discussion
provides insights into the technical challenges and market dynamics shaping high-performance computing and AI infrastructure.

Key Insights

Timothy Prickett-Morgan emphasizes the critical role of PCIe Re-Timers in AI servers, noting their necessity due to increased
bandwidth demands and signal integrity issues. He highlights how Re-Timers have become essential as bandwidth increases,
reducing the effective length of copper wires.
Prickett-Morgan points out that Nvidia's proprietary NVLink offers significantly higher bandwidth compared to PCIe, which has
driven Nvidia to develop its own interconnect solutions to meet AI demands.
He suggests that CXL, though currently less advanced than NVLink, could become a viable alternative for enterprises not
requiring the highest performance levels, potentially reducing costs and complexity.

Competitive Landscape

Company

Strengths

Weaknesses/Challenges

Astera Labs

Strong engineering in PCIe Re-Timers;
partnerships with Amazon and Nvidia

Faces competition from larger players like Broadcom

Broadcom

Comprehensive networking stack; re-entering
PCIe Re-Timers market

Previously considered exiting Re-Timers, indicating
past challenges

Nvidia

Marvell

High-performance NVLink interconnects;
leadership in AI hardware

Proprietary solutions may limit broader market
adoption

Offers Re-Timers and other interconnect
solutions

Less visibility in the PCIe Re-Timer market compared
to Astera

Applications & Use Cases

1

Confidential

02/18/2026 at 18:56 PM UTC

PCIe Re-Timers: Used to extend signal range and improve signal integrity in AI servers, crucial as bandwidth demands increase.
CXL Memory Controllers: Offer potential for memory expansion and shared memory pools, particularly beneficial for enterprise
AI applications with moderate performance requirements.

Quantitative Insights

Metric

Value/Insight

PCIe Bandwidth (Gen 5)

128GB/s per 16 lanes

NVLink Bandwidth (Latest)

1.8TB/s

Re-Timer Cost (Estimate)

Under $500 per unit

Potential Re-Timer Content

$4,000 per DGX server (8 Re-Timers)

Market Strategy

Astera Labs is positioning itself as a leader in the Re-Timer market by leveraging strong engineering and strategic partnerships.
Broadcom is re-entering the Re-Timer market to provide a comprehensive networking solution, responding to customer
demand for integrated solutions.

Stage & Timing

PCIe Evolution: PCIe 6 expected to be supported in servers by the next generation of processors, with PCIe 7 and 8 on the
horizon.
CXL Adoption: Still in early stages, with potential for broader adoption as enterprises seek cost-effective AI solutions.

The transcript highlights the dynamic nature of the AI server interconnect market, with companies like Astera Labs and Broadcom
navigating technical challenges and competitive pressures to meet evolving industry demands.

KG: Good morning everyone, welcome. My name is Kirang Gohil and I'm with Guidepoint. Thanks for joining our call
on Astera Labs, Broadcom and AI Networking: CXL versus NVLink versus PCIe - how is the market evolving. The call
today we will discuss the interconnects in an AI server and do a deep dive on the PCIe Re-Timer market and the use of
CXL memory controllers.

To discuss all this, I'm very pleased to welcome Timothy Prickett-Morgan to the call. Timothy is currently the co-editor
of The Next Platform, which as many of you might know, is a well regarded publication covering high performance
computing and hyperscale data center hardware infrastructure. He has followed the industry for a number of years,
and has also written on this topic that we are going to discuss today.

As for logistics, I'd like to remind listeners that if you have a question for Timothy, please email them to
Ask@Guidepoint.com and I'll include those questions anonymously into our discussion. With that, Timothy, let me turn
the call over to you. If you could please introduce yourself and give us your background as would be relevant to our
discussion today.

TP: You just told everybody who I was. I've been watching the data center for now, 35 years. It's hard for me to believe
this, but I'm a fan of large scale computing and the compute engines and storage and interconnects that make it all
possible. That's been my day job in various guises over the many decades. I still find all this stuff interesting,

2

Confidential

02/18/2026 at 18:56 PM UTC

fascinating, and sometimes scary. That's the way it is. That's it.

KG: Let's dive into it. Timothy, for those that might not be as familiar. Lay out for us what is PCIe? Where are PCIe
interconnects used in a traditional and in an AI server?

TP: For as long as I can remember, since the 1992, in fact, was when the first PCI peripheral bus interconnect spec
came out. Before then, when you wanted to attach a CPU and there was only one with one core in a server or a PC out
to the various devices, you might have a network card, a printer card, when you had those things, other kinds of
peripherals like a joystick or whatever.

If it was a PC, if it was a server, it might be various devices to hook up all kinds of different peripherals onto things. You
had to have a bus to do that, so PCIe was the bus to do it. That evolved eventually into PCI Express. The bandwidth
keeps going up, and the number of lanes of peripherals that you can support off of a processor keeps going up or off
of a controller keeps going up.
We're now at a stage with PCI Express 5, where the bandwidth is up to 32GB per signal lane, and for a server that has
what's called a 16 by 16 slot, which is what a GPU would plug into, that is running at 128GB per second of bandwidth
in and out of that device across that bus. Over the last couple of years, since the PCI Express 3 generation, they're
developed not just a need to hook things directly to the CPU over the bus, but to have them shared and pooled, and
you needed more connectivity than you could get coming out of the process or the processor might have 40 lanes of
PCI or 32 lanes of PCI, but you had hundreds of lanes of PCI Express peripherals that you wanted to connect.
To do that, you need a switch. You need a switch in the center because it has to allocate some of the bandwidth
coming off of the CPU into the devices, and they time share it over the switch. With the advent of AI servers really, you
wanted to cram more GPUs against the CPUs and the server, and that meant you needed a switch. In some cases,
there are six of them glued together in a hierarchy just to attach the CPUs to the GPU complexes. That's why they're
really used today.

Now, to connect the GPUs, some people want to use a PCI Express switch infrastructure. Meta platforms formerly
known as Facebook used to do this before they embraced NVSwitch, which is Nvidia's own switch infrastructure for
gluing together the GPUs. Most of the designs today, you've got a PCI Express complex hooking the GPUs into the
CPUs and to the other peripherals, network controllers sometimes, flash storage, other storage drivers, whatever. To
connect the GPUs to each other very tightly, there's this fabric called NVLink Switch when they externalize it, but it's
NVSwitch when it's inside of a node. That's the layout of an AI server.

KG: Help us understand what went wrong, if I can say that with PCIe especially the delay from the Gen 3 to Gen 4, and
why did Nvidia had to come out with its own proprietary NVLink interconnect?

TP: What went wrong is that and it happened with both network fabrics outside of the server node and the PCI
Express controllers and switches inside the node. It wasn't just something that happened to PCI Express. We had all
kinds of problems with signaling the materials science and the way you would do error correction and the way you
would encode things. All of it was way too heavy and way too lossy for us to make the jump in two years or three years
for PCI Express.

With InfiniBand and Ethernet, we didn't go from 10GB per second to 100GB per second. We had to step in the
middle and do 40, and we did 40 for a long time. It's only because material science and different kind of encoding
and signaling and error correction were invented that we could then get back to a normal cadence, a two year
cadence, a three year cadence, depending on how you want to be generous or not. It's really three-Ish. It was two for
a while and we got caught up.
In that gap, that gap is exactly when AI happened, when AI went commercial on GPUs was 2010 and we didn't get PCI

3

Confidential

02/18/2026 at 18:56 PM UTC

Express 4, which was running at 64GB per second, until 2017 is when the spec came out. It was really late 2018, early
2019 before we could see peripherals that actually could talk to that protocol. That's a big gap. What Nvidia did is
they had this NVSwitch, memory logic, load store, logic coherent interconnect that was in the labs. They said, well, we
need that, so bring it out now. They were like, wait, what? No, we're not ready for that.

They did it anyway and they turned this thing into a switch to connect the GPUs together. Not only did it connect it
faster. The first ones came out at 300GB per second, and PCI Express 3 was 32GB per second, so it's almost 10 times
what was available at the time. They doubled it to 600GB. Last time it was 900 with the generation of machines that
were launched today it's 1.8TB per second, not bits, bytes. You got to divide that by eight to get the bits part to
compare it to a network like Ethernet or InfiniBand.
The gap is still there. Today they're at 1.8TB per second. PCI Express with 16 lanes is at 128GB per second with PCI
Express 5, that's 14.4 times the bandwidth out of a port. It's not magic. They have a lot of lanes. Their lanes run at the
same speed as everybody else. Way back when they were 25 gig signaling, and they were 50. Then there were 50
with 10 for encoding, and then they were 100 with PAM4 encoding, and now we're at 200 with PAM4 encoding.
There's nothing magical about it. It's just they decided to do it that way. Nvidia is very good at making high speed
surges. They're on the front end of aggregating those lines in the lanes of IO and the surges to put huge fat pipes
together, coming in and out of the GPUs so that those GPUs can share their memory like a NUMA server does with
CPUs and has for decades. NUMA, a non-uniform memory access means take a bunch of CPUs, put a high speed
interconnect between them, tell the operating system that it's one giant CPU, and then work it out in the details so that
all that memory is shared. It makes it look like one big CPU. They're doing the same thing with the GPUs over NVLink.

KG: In a DGX box, where does Nvidia use NVLink connections and where does it use PCIe?

TP: It uses both. For the DGX class servers, not the new one that's got just NVLink only and not the ones that.

KG: The new one, meaning Blackwell?

TP: The Grace Hopper and Grace Blackwell is the new stuff. Meaning for those that use an x86 or ARM server as the
host for the node, you need PCI Express fabric to connect the processor to the complex of GPUs. The GPUs are
connected by NVLink. They don't use PCI Express switching there. There's many in the industry that say, well, that's
great, but not everybody is going to need to do that. I'll make that argument in a little bit that there's the jury's out.
If you want to build the highest performance, scalable machine for training 2 trillion, 5 trillion parameter AI models,
you need something like what Nvidia has invented, for sure. If you're an enterprise that is going to be training or
retraining or tuning a preexisting model on tens of billions to hundreds of billions of parameters worth of data and a
model only in that scope. You don't need that. How do we know that? Because you didn't have it before and Nvidia
was doing it just fine, Meta was using PCI Express switching to connect all their GPUs together for many years. It
worked just fine at that scale.
It's like the difference between a Ferrari and an F50 pickup truck. A lot of people are going to need an F-150 pickup
truck in the enterprise. There are going to be hundreds to thousands of organizations that want this high-end Ferrari
version of things that can, or maybe it's better to call it a cat, earth mover or something instead but my metaphor
broke down there. You get the idea that this is this is something that's for very, very high scale, high performance, and
not everyone's going to need that. If they do, they might rent it on the cloud.

They might just say AWS has these things, Google Cloud Platform and Microsoft Azure has these things. I'll just train
my model out there. When they're inferring their models use running inference and generating tokens, they probably
are not going to use these devices if they can get away with it because their godawful expensive. They're just terribly
expensive. That's in the current design. The current DGX with eight GPUs, there's this collection of PCI Express
switches. There's free timers coming off of the GPUs that talk into that switching infrastructure. Let me explain why the

4

Confidential

02/18/2026 at 18:56 PM UTC

Re-Timers are important or I'm going to lose my mind.

KG: Before we go to retimer, I'm just trying to lay out the interconnects first. We talked about NVLink. Before we go to
retimer, let's talk about CXL. Talk about CXL-
TP: CXL is not an interconnect, it's a protocol. There were many, many different memory coherent protocols once
acceleration once not just having CPUs but offloading to a GPU or a GPU like device, usually a GPU, but sometimes an
FPGA. There were many protocols that were under development. IBM had OpenCAPI, which I would argue was the
best one. It was very good at what it did. IBM also embraced NVLink and put it into their processor so they could win
some supercomputing contracts with earlier generation V100 GPUs with Nvidia. Those were the pre-exascale systems
at Oak Ridge and Lawrence Livermore National Labs that was based on that.

There were C6 coming out of AMD and the ARM collective. I'm probably forgetting Infinity Fabric at AMD. They also
embraced C6. These are all protocols that run over a transport. The transport is PCI Express. Sometimes it can be
Ethernet or InfiniBand, that's a transport as well. The switching infrastructure is the transport. It's just the way the bits
are carried, but the way they're carried and whether or not there's a memory protocol and that's the key here.

If you want to be able to share the memory of the devices that are connected to the CPU or that are connected to
each other, you need a memory atomic protocol or a cache coherent protocol. That means that the CPU, when it talks
out over the PCI Express complex to the GPUs, has a software layer that says, just make all the memory in the GPUs
look like it's the memory on the CPU, just make it work. That's what CXL is doing. There's other things it can do.
When you do CXL memory extension off of the CPU, that's what you're doing. Astera Labs has controllers they've
created, Samsung has controllers they've created that you can put on memory modules that you can plug into the
system. It looks like it's memory plugging into the memory bus of the computer, but it's really not. It's plugging into
the PCI bus and it looks and feels and smells like regular DRAM. It runs a little bit slower. It has higher latency, but it's a
pool of memory that's much larger than you would otherwise have.
CXL is a protocol. PCI Express is a transport and an IO protocol, but it doesn't have any memory coherency in it. CXL
currently overlays on top of PCI Express transports to give it this capability. It is what I call poor man's NVLink. CXL on
top of PCI does what NVLink does. It does all those kinds of things. You can glue your GPUs together and you can also
glue the CPU to it. That's many of us think, and I think there's going to be a big part of the market and particularly at
enterprises as they implement AI, that will say, well, no, that's good enough for me.

Maybe not for the most aggressive training of models, not for the most aggressive of inference. No, but for a lot of
their workloads where they're dealing with tens to hundreds of billions of parameters on pick a number, dozens to
hundreds to possibly a 1,000 GPUs, that's it. That's going to be a lot of the enterprise. For them, they can and they're
at the beginning of their wave of building out stuff.

Frankly, they haven't been able to get GPUs anyway. As PCI Express evolves and CXL evolves by the time they need
bigger clusters with that memory coherency, I think that PCI Express 7, PCI Express 6, will be in the field and it will
help absorb some of that, and it's going to be a lot less costly than NVLink plus whatever. That's my take on it.

KG: Let's talk about PCI Re-Timers. What are Re-Timers? Why do we need them in a server? Why they are used in AI or
a traditional server?

TP: Here's the concept you have to get in your head. Every time you double the bandwidth on a piece of copper, you
have on a copper interconnection. Every time you double the bandwidth, you basically half the length of the copper
that it can drive a signal through and be clean on the other end. As you drive up bandwidth, it gets noisier and noisier
and noisier and you can't drive it as far. It's to the point now where the PCI controllers on a GPU can't get out the
back-end of the server. That's how short the wire is.

5

Confidential

02/18/2026 at 18:56 PM UTC

It's so bad on a lot of Ethernet switch infrastructure at the 51.2T generation that they have to have Re-Timers coming
out of the other end or they're starting to do co-packaged optics. Bring the optics to the transceivers right down in the
lasers, right down next to the ASIC on the switch. That's very expensive. There's a lot of things going on. It's very
exciting, much lower power, costly. We're worried about reliability of that. It's all new.
Every time you double the bandwidth you shrink the wire. If you shrink the wire, you got to put something in there to
boost the signal so you can make the wire longer. In some cases, as we double the bandwidth again and again, you
won't just have one retimer between the ASIC and the port. You'll have two or three or four. There are $500 a pop, a
little under that, roughly. In an eight GPU system right now there are eight of them.
The Astera Labs are in the latest ones and the DGX B100. Not with all the NVLink interconnect for everything, but just
for the eight local CPUs there but connecting out to everything else. There are Re-Timers that go out after they come
off the PCI Express controllers off of the GPUs, and then those hook into the PCI Express switch complex, and that lets
them hook out into all the different devices out there as well as the CPUs.
There's some content in all of these devices going forward. Re-Timers have been used in switching for a long time for
that very reason, because you got to get from the ASIC in the center of the box out to the port. Now, it's you could
stretch things before, there's no way to stretch it. The other way to do it, instead of using the Re-Timers is to do what
Nvidia did with the NVLink interconnects in that 72 GPU rack scale system. They said, well, wait a minute, rather than
put all these Re-Timers out there, why don't we just drive the copper wire directly off of the switch, and just use a big
old fat copper wire?

There are over 5,000 copper wires in that rack, and that those 5,000 wires allow a direct link between every GPU and
every other GPU, so they can all talk to each other at the same time. If you look at it, it's a total rat's nest in the back.
Out of the 3,000 pounds of the rack, I would guess about half of it is just those cables. It's not cheap to do that. As I
said earlier, it's very, very expensive to use optical interconnects all throughout this layer of the network.

It would be a factor of 610 somewhere on that order. There are many supercomputers that use a mix. They use and
technically I suppose the Nvidia is too, because if you go outside of the 72 and that one rack, you got to use
InfiniBand. You use copper interconnects within a rack, or cabinet sometimes it's like a two rack deep thing with the
Cray supercomputers. Then anything outside of that is an optical interconnect, and that's where it gets pricey.

When you start going up to hundreds of cabinets, dozens of cabinets. You've got to go with optical transceivers. Fiber
optics it's not cheap, but that's not what's getting you. It's the optical transceivers that are very expensive. They're
expensive in heat. They generate a lot of heat, and the copper doesn't generate anywhere near as much heat. You
save in thermals and you save in money by doing as much copper as you can. That's going to run out. This is the other
thing you have to remember eventually.
Frankly, I was told by people that know something five years ago that 100 gig signaling was going to be all, end all,
and that was it. After that, they'd have to go to optics. Here we are at 200 gig. Engineers are clever. You never know if
they're going to be able to do the next thing. I'm hesitant to say that 200 gig is the last stop on the copper train, but
it's beginning to look like it. Then after that, if you need to go, if you need to double the bandwidth again, you're
going to have to either figure out a new trick to make copper work, or use a hell of a lot of timers to make those
distances work. If you do that adds latency and that's got its own complications. It's going to be tricky.

KG: Is there a way to think about how many PCIe timers might be used in one of the DGX boxes?

TP: If it's the old school ones there's at least eight, and there's probably more. I don't know every one of them, but
there's at least eight.

KG: When you say old school, these are not the ones that have the Grace CP?.

6

Confidential

02/18/2026 at 18:56 PM UTC

TP: If it's got an x86 CPU in it, let's say it that way. It's got a bunch and there may be others. I haven't got a breakdown
of all the different chips inside this thing yet. If you've got Grace, you don't need it because Nvidia said, well, let's put
NVLink ports on our ARM server and we'll hook it all together with NVLink ports directly. They just go direct. They got
a 600GB port coming out of Grace that goes into the NVSwitch complex inside the node.
With Hopper that was a 1:1 interconnection. With Blackwell there are two GPUs with a much faster set of NVLink ports
coming out of it that connect to Grace. The reason is, is because you don't need that much of a host and Grace ain't
cheap is my guess. I would guess it's somewhere around $10. It's a total guess, but it's not $2. You just don't need
that, it's got 72 cores.

That's plenty enough to run a Linux operating system and act as a memory controller that provides nearly a half
terabyte of memory in addition to the memory that's on the GPUs. Personally, I think they should have even fatter
memory than that. They're trying to use low power DDR5 that's cheap and not get the thermals up. They're balancing
out the next version of their ARM CPU will certainly have more than a terabyte of memory. They might even have two.
When you have that, there's no need for Re-Timer in there because they're all directly connected. They're all talking
over NVLink and they're all coherent. It's not just that they're connected. They can see each other's memory.
Programmers don't have to do load. They don't have to move data. They can just do a load store, go get it. That's ok.
Your program just like the memory on a CPU.

KG: Going back to the question, so if it's just a CPU - the H100s, H200, Blackwell B100s, B200 - if it's without the Grace
CPU then the attached rate for a PCI Re-Timer would be 1:1 with the GPU?

TP: There may need to be Re-Timers between the PCI Express switch complex and their peripherals too. I don't know
that. There could be even more. There's at least eight, or there's at least as many as there are GPUs in the system, and
there could be more. I don't know about prior generations. I don't know about Hopper. I never thought about Re-
Timers until recently, to be honest with you. I'm starting to think about them. There may or may not have been in prior
generations. There certainly are in this one.

KG: Now, one thing you mentioned very briefly, and I think we should expand on that a little bit. If it's an NVLink
connection, not PCI, but NVLink, then you do not need a Re-Timer because the NVLink is driven from the switch.
There's no need for a Re-Timer, right?

TP: They may need them at some point. To my knowledge, there isn't one in there. If there was, it'd have to be a pretty
beefy one. There's another important thing about the Re-Timers that I need to mention. It's not just amplifying the
signal. It's not just extending the range. It actually cleans up the signal. It helps make the whole thing more reliable. At
least the ones that Astaire is talking about. They actually show you the eyewall diagrams that show you the cleanliness
of the signals coming out of the devices.
The PCI Express, signal comes in and it looks fuzzy. When it comes out, it's not fuzzy, they do a lot of witchcraft on the
silicon to not only make it a cleaner signal, but allow you to monitor the cleanliness of the signal with their own
firmware. That lets you do a lot of different things. They're doing the same thing with Ethernet. In pluggable modules,
they have torus. I forgot the name for it but it does the same thing.

It's a signal cleaner for long-range Ethernet links as well. Then they've got the CXL memory controllers they're doing
as well. I think that equating Astaire success with PCI Express Re-Timers. It's more than that. They're going to find uses
inside of many different parts of these kinds of systems. It's not just the Re-Timers. They're excited because they went
public this week so you know.

KG: Now, how about just the use of Re-Timers in traditional servers? The crux there is if the traditional servers go
down, then does the use of PCIe Re-Timers also go down as well, or are there any offsets where there's content

7

Confidential

02/18/2026 at 18:56 PM UTC

growth. So even if the units go down for traditional servers overall, can PCIe Re-Timers can actually grow?
TP: The use of Re-Timers is going to go up over time because any electrical signal, if you double the bandwidth you
have the length you're going to need a Re-Timer. If we could get away without having Re-Timers for generic servers in
the past, except for very specific situations, that's not going to be the case going forward. There's absolutely going to
be more Re-Timer content in servers increasingly so as bandwidths go up.

We've got PCI Express 7 specs should come out next year. We're going to be up to 512GB per second. PCI Express 8
spec comes out in 2028. Should see things in 2029. Doubles again one terabyte per second. PCI Express 9 in 2031.
That's the two terabytes per second for 16 lanes. That's where NVLink is today. 2032 is where NVLink is today. It was
such a challenge that Broadcom was seriously thinking about not doing PCI Express 7 and just going straight to eight.
Who's going to make the peripherals? With the switches that they were making, they were like, why don't we just go
straight? Can we do it? That spec isn't even close to being done. It hasn't even started. Everybody sees the pressure
and the market as much as everybody loves the phenomenal engineering that Nvidia is doing, people want a
standard way to do things, which is why you see AMD working with Broadcom to take xGMI and Infinity Fabric
Protocol and run it on top of PCI Express switches.

It's not clear to me which one it is. I talked to Broadcom and they said it was PCI Express 7. Then I talked to some other
people who claim to know more and I find it hard to believe they do. They said no, no, it's going to actually happen
with the PCI Express 6. I said I don't think so, but maybe it will. Maybe there's like an early version that will allow parts
of Infinity Fabric to run on PCI Express 6, but even still that's only a 256 gig per second x16 link.

For a lot of uses, that might be good enough. Not every large language model is going to be GPT-5 and GenAI, and
it's a lot of them are going to be like Llama 70 billion or even Llama 250 billion if shouldn't exist. For those situations
where the model is going to be smaller and the data sets are going to be smaller, as will be the case with most
corporations who are trying to add generative AI capabilities into their applications based on their data, which is no,
obviously much smaller than the corpus of all English language or any other language for that matter. They're going
to be able to get by on a smaller, less capacious, cheaper system. That's the idea. We'll see if it happens.
KG: In practicality, from a customer perspective, if they're not buying the DGX systems from Nvidia directly, then the
other option for them is to buy the HGH, i.e. buy the GPUs and then build their own system around it. \`In that
configuration, there is an option for them to use PCIe and not NVLink. Your point is that's when PCI comes in?

TP: Has the same architecture. You can get your architecture from HP or whatever, but that server board is going to
have to have a PCI Express switch complex in it. It very likely is going to have to have Re-Timers too, there's no way out
of that. That's not but it's the other side of the GPU I'm talking about. It's the side of the GPU where the GPUs talk to
each other, not the side that talks to the server, but the side where they talk to each other.

I'm talking about there being a possibility to use PCI Express on that side, with the CXL protocol running on that side.
Not use much at all. That would mean that there would have to be some sort of agreement by Nvidia to support the
CXL protocol on the PCI Express versions of the GPUs. I don't know if that's going to happen or not, but I can tell you
what's going to happen, AMD is going to do that.

Intel is going to do it with Gaudi, and it's going to do it with Falcon Shores. If it gets to Falcon Shores, which I believe it
will try and any other accelerator is absolutely going to try to do this. There'll be a day when Nvidia has to decide
whether or not they want to participate in that emerging market. I will tell you that there's already some precedent for
that. For the last three years, it's been InfiniBand, InfiniBand, InfiniBand, InfiniBand, and now they're saying InfiniBand
and Ethernet.

Why? Because the Ultra Ethernet consortium which has Microsoft, Meta platforms, Broadcom, I forgot the other one,

8

Confidential

02/18/2026 at 18:56 PM UTC

cisco. They're trying to figure out how to build InfiniBand like networks for AI that do not involve paying the premium
for InfiniBand. The same kind of thing will happen with this PCI Express interconnect. There might be a day when
having PCI Express for everything is good enough with CXL protocol running on top of it. They're all cache coherent
and everything can work.
There might even be memory extension inside of that, for both the CPUs and the GPUs. There might be a shared
memory pool based on CXL at the center, and then a bunch of GPUs hanging off that on one side. They don't just
have to rely on their memory. They can have a fairly close but somewhat quite a bit slower DRAM memory block that
they share, which is what Grace is.

Grace is just an L4 memory with a controller that can also happen to be the host of the computer because it has some
ARM cores on it, but its function most of the time is to provide a giant scratch space for those GPUs so they can hold
something local that's quick to get in there, some data sets local or some [INAUDIBLE 35:27-35:28] or small results,
intermediate results as they're running locally that the CPU can then pass over the network if it needs to. That's the
idea.

KG: I want to make sure one more thing here. When you're talking about connecting the GPUs together. Many people
refer to that as the back-end network. Your point is that in future CXL could be used, maybe, we don't know it
depends-
TP: Because remember or node scale for sure because we got PCI Express switch complexes at node scale right now
connecting the CPUs to the GPUs. We're already doing that. I'm just saying you can put it on the other side for eight
GPUs in a node or four GPUs in a node, it will work just fine. Once we get the bandwidth up there a little bit, it's not up
there, it's not enough yet.
We could get there and then once you might be able to do rack scale, you might be able to do. We have the same
problem. It was much easier to do three racks of PCI Express 4, but at PCI Express 5 because without Re-Timers you
can only do a rack because the wires can only be so long. Now you say, ok, well, if I want to do three racks of
infrastructure, all interconnected without any InfiniBand, without any Ethernet, it's just PCI Express. Now I need Re-
Timers. Yay a Astera Labs. Yay Marvell. Yay Broadcom.

We'll see how it all goes. These are architectural choices that people haven't made yet. First of all the PCI Express
switches aren't here yet. It really gets interesting at PCI Express 6 and 7 because that's when the memory protocols for
CXL are mature supported. All of that coherency across that PCI Express domain for both the CPUs and the GPUs can
be done, and then memory pooling can also be done.
Who knows how it's going to play out? I don't know yet. I got guys talking out of both sides. Marvell is like we think the
future of AI is optical, for sure. In the meantime, the future of memory is CXL, so that's how they see it. Everyone is
trying to figure out and I got other people saying CXL memory is dead, it's stupid. It's never going to work.

KG: Let's just stay on the Re-Timers. Talk to us about the ASPs for Re-Timers chips. I'm trying to understand how much
ASP would someone like Astera Labs get for PCI Re-Timers. How does it vary when you go from PCIe Gen4 to Gen5 to
Gen6?

TP: I have no idea. I only see the Gen4 stuff. I don't know, I did some poking around and it was under $500 in a couple
of places I could find pricing, but I don't think the price comes down over time.

KG: $500 for one, and so on the total content -
TP: Yes.

KG: If there are eight GPUs, you need eight Re-Timers so that's at least $4,000 worth of content in a DGX server for
Re-Timers?

9

Confidential

02/18/2026 at 18:56 PM UTC

TP: Against the machine that's going to cost a half a million dollars. That's what I think of Blackwell version of a DGX
B100 will cost. It's nominal compared to that. It's nominal because without it don't work. You can't get the signal out of
the GPU into the CPU. There's not enough cleanliness for the signal. You have to have the Re-Timers. It's $4 against a
half a million dollar. You can see noise in the data, unless you're Astaire and you're like, yay, it's great. Astaire is going
to do ok. Is it worth $10 billion already? Yes. Why?
KG: We don't want to talk about the stock, so we'll focus on the-
TP: My point is only that people are suddenly exuberant in a way that doesn't make economic sense to me. Their
company-
KG: Let's not talk about stocks. We'll focus on the company and the fundamentals in the market. On the retimer
supplier landscape, how has that changed? Where's Astera Labs and how has that market evolved as we've gone
from Gen3, 4 to 5?

TP: I'll be honest with you, everybody's radar except people on the inside for the longest time, because you could
drive the signals at PCI Express 3 and earlier. With four, you could get away with it by placement. Even at four you
started to have to add these things in certain kinds of components. Network switch devices have had Re-Timers for a
long time. If you have an eight-
KG: Who are the suppliers?

TP: I only know about three. Marvell does it, Broadcom does it, and now Astera and there could be others I don't
know. Those are the three I care about.

KG: Parade and Montage as well.

TP: I don't know them. I only know the ones I've written about, but I suspect that they're going to see a lot more
business for sure. He who makes the best Re-Timer is going to get some business.
KG: No, I was going to ask, why do you think Astera Labs has done so well in the Re-Timer market when there are
much larger companies that historically were always focused on PCI Re-Timers. Astera Labs seems to have done really
well. Do you have any thoughts on what they've done right?

TP: The engineering is apparently very good. Maybe some of these other Re-Timers don't clean up the signal as well. I
don't know but I suspect that they have a very good product. It's not just that, again, they're doing Ethernet stuff too.
They're doing CXL memory. To partner with them is to prepare yourself for how you might enhance signaling for CXL
memory and Ethernet, as well as for the PCI Express switch complex or just point to point in PCI Express links.
If you got a PCI Express controller in the CPU and it's driving a 5.0 or 6.0 signal out of the CPU just to try to get to the
slots in the server might require a Re-Timer, I'd say almost certainly will. Again, every time you have a double length
on the wire, you cut it in half the length. Every time you double the bandwidth, you cut the length of the wire in half. At
some point, the wire doesn't barely get out of the ASIC. You need Re-Timers at that point, so there could be a lot
more of this stuff inside of a server.

KG: It's been written that Astera has good relationships with Amazon and with Nvidia. They are one of the largest
customers. Why do you think Astera was so successful that Amazon and with Nvidia. Why did these two customers
prefer to work with Astera and not with others?

TP: Well, you always want a different answer. If they have good product, you want to put some leverage on the other
ones. If Marvell and Broadcom already have a lot of business with the hyperscalers which they do, why wouldn't you
pick the third horse option to put some pressure on them. The Re-Timers are not free. They do add heat to the
system. If there's a wattage difference you're going to go for that. There's every what matters now.

10

Confidential

02/18/2026 at 18:56 PM UTC

I don't know all the differences in the feeds and speeds of the Re-Timers. I could go study that, but I haven't. You
would always want to have three suppliers anyway, in this world, the supply chains all messed up. Why not bring in the
third supplier? It benefits everybody. These are being probably etched in relatively established yet not too large
processes. Probably 5 nm chips, which means you can get them and it's ok, but they're not trying to do them in 3 nm,
which apparently doesn't work.

KG: In terms of the generation, would the current DGX or Nvidia servers support Gen5 or Gen6?

TP: There is no Gen6 yet. It's not out there. It's not yet. I don't think so. I have not seen. Well, let me be honest, the
specs have not been published, so we don't know. I strongly suspect it's PCI Express 5. I'd have to go look that up.
Again, they haven't published them. I don't think six is there yet. I wish it were. I have yet to see a server that supports
PCI Express 6. That doesn't mean it hasn't happened behind my back.

KG: When do you think we would see servers that support six?

TP: Next generation of processors. Later this year we'll see the first ones.

KG: How much of ASP bump might you expect when you go from Gen5 to Gen6 for Re-Timers.

TP: Controllers or switches?

KG: Re-Timers.

TP: Re-Timers. I haven't the slightest idea. I would assume that there's going to be a bump for performance every
time. I would expect it to be somewhere on the order of well, with switch ASICs, traditionally has been 35%-40%
increase in price for double the performance. If you look at the GPUs lately from Nvidia, it's sorted doing the same
thing at list Ish price, it's in that same zone. A lot of things that are in aggressively demanded for the reasons of being
able to do a lot more work with the new device. That's the pattern. 1.4X the price 1.3X the price for 2X the
performance. I have no reason to believe that PCI Express devices in general wouldn't follow that same pattern.

KG: Let's talk about Broadcom and their re-entry into the PCI Re-Timers market. It seems like they were going to get
out of the Re-Timers business. What happened and what drove that?

TP: I don't have the full story, but they said that their customers came to them and said, hey help. Whatever was going
on out there it wasn't making them happy. I don't know, maybe there's been delays in the Re-Timer designs. There
have been delays with the PCI Express switching to five is not out anywhere near a timely fashion. I've complained
about that, it's a crime that the servers support PCI Express 5. Then it's two years before we get the switch. It can't
work. That's not system architecture.

The switch has to be available at the same time as the ports are on the server. The peripherals have to be available at
the same time too. Meaning the GPU has to support it too, and storage controllers and everything else. There's a lot
of pressure to get this stuff in lockstep and moving along regularly and all pieces of it. What happened is that the Re-
Timer became important. I'm only writing it out now because it became important before it was like it was hidden,
now it's not hidden.

It's like it's a significant part of the heat, it's a significant part of the cost, and it's a significant part of the architecture of
the machine because of the limitations of when you drive bandwidth, you have shorter wires. It sounds so silly, but it
didn't matter before. Now it matters. They're going to say Broadcom. We're not going to trust some startup over here
or whatever to do this thing.

11

Confidential

02/18/2026 at 18:56 PM UTC

We need you to do it. We're getting our switches from you. You're building our custom, xPUs in the case of three
hyperscalers. We want you, you want your Re-Timers too while we're at it. I don't want to have a Re-Timer signaling
problem that makes the machine useless. There's too much at stake now maybe I think, but that's conjecture on my
part. It became important enough to have that.

I also have said that I want more than two suppliers of PCI Express switches. That's a point of failure. If one company's
delayed, that's half of the units or whatever, however the units break down. It means that everyone will be scrambling
for the what limited supply of the one vendor who can ship. That makes the price go up, and it makes systems
delayed too. We don't want that. I've asked Rambo's personally to go out and do this. They haven't listened to me so
far.

KG: Do you think from a customer perspective if they buy the full networking stack end to end from a company like
Broadcom - switch silicon, DSP, optics, Re-Time - would that ultimately result in a better performance because
everything is done by Broadcom, everything's tuned or does that not really matter when you're talking about such
large clusters?

TP: I think you want a throat to choke, a single one when you can get it, but you also want alternative suppliers. These
big machines have so many components that you really want to mitigate some risk of supplier stuff, and not having
things come in on time or things not working together. Even if it's not the cause, let's say the Re-Timer is working fine
and some other part of the system isn't. Everyone's going to point their fingers and not in their own direction.
If you buy everything from Broadcom, you say, hey hock something's going on here, you need to fix it. Then it's one
phone call. You know there's the value to that. You can pay a premium for that, in fact. That's why it's valuable is that
and by the way, the same holds true for Marvell. It's not like you can't make that same phone call, and you can't get
the stack of components from them too. I'm not aware of them doing PCI Express switching, but they obviously do
other kinds of interconnects. They do Re-Timers for sure.

KG: We've done calls on Astera Labs and people who've had a positive view say that Astera is like a Switzerland,
because if you are a PCI Re-Timer company, you have to work with the processor guys, you have to talk with the end
customers, you have to talk with Nvidia. Everyone needs to trust you to open up their roadmaps. Switzerland status is
why people like to work with Astera. The question is, would Nvidia or some of the hyperscalers, want to work with
Broadcom even though they are sort of a competitor as well. How do you think about that aspect especially when it
comes to Nvidia?

TP: They have two suppliers of HBM3 memory right now. They love it before they had one. That's better. It's better to
have strong partnerships with two vendors. They may decide to like they do with HBM memory to just split the
capacity across different runs of the GPUs. Or they might decide, as they've done in the past, well, this memory is used
with that device or this fab is actually fab. Samsung is going to make these GeForce versions of it and TSMC is going
to make the GPU data center versions of it or whatever. They'll figure out how they want to mitigate that risk or mix
and match. I don't think there's any appetite at all for having just one vendor for a key component. It doesn't happen
anywhere at the hyperscalers, it doesn't. They make-
KG: How much of a risk is the entry of Broadcom into PCI Re-Timers to market share for Astera Labs?

TP: It's a huge risk because there was the 800 pound gorilla in the room wasn't playing. They had the whole thing too.
They could eat the whole thing if they were the best. Now, there's no foregone conclusion that they will be the best.
Broadcom will absolutely bring it and they will bring some heat. There's no question about that. They are going to
bring to bear their cities, their circuitry, their stuff. I wrote a story about that recently there.

I wanted to talk about PCI Express switching. They wanted to talk about Re-Timer. I'm like, I don't care about Re-Timer.

12

Confidential

02/18/2026 at 18:56 PM UTC

They're like, you need to, here's why. This is a fairly new education for me. The point is that this means there's
probably going to be a good, healthy set of competition here. That's good for the industry. That's good for
everybody.
KG: They just introduce the Re-Timers. How long are the design and cycles and qualification cycles?

TP: I don't really know that. It's generally less than four. For Broadcom switching, generally they get the thing
announced and in nine months you see the first devices using it. This might be depending on how mothballed it's
vantage is the line depending on how mothballed the Re-Timer products were. For all I know they were already
working on one and they dusted it. I would expect it to be fairly quick.

KG: Less than nine months, so it's like three to six months?

TP: Less than a year. Typically Broadcom used to be a year. Then they've been trying to get it. If I talk about a switch is
like now we can get them in the field in nine months not a year. I think nine months is a lot, that's pretty fast. When is
Nvidia going to ship the NVLink only version of this machine. We don't know. We don't know. We know that some of
them are later this year.

H200, which is the old version with the fatter HBM3 memory is only June. We talked about that in November, so even
Nvidia is talking nine months ahead of when they can ship something for realsies, so it's hard to beat nine months. It's
hard to be faster than nine months. This development might have been going on for a while and then they're only
now talking about it.

KG: In the last few minutes, let's talk about CXL memory controllers. One of the debate is if there is going to be a big
enough market for CXL, especially given that Nvidia is using NVLik and AMD has its Infinity Fabric. Is there going to be
a big market for-
TP: CXL memory is different from CXL interconnect for accelerators. Let's separate that. It's hard, it depends on the
performance and the cost. In general CPU-based computing is bandwidth limited in many cases and capacity limited
in some cases. To the extent that we can increase the bandwidth and the memory capacity using the PCI Express bus
in the server and switches, that's interesting.

If you could create a memory server that use CXL protocol and radically reduce the memory inside each physical
server and have a shared set of data on this memory server, and then the servers connect that over CXL, you might
save a lot of money in memory. When memory was a third of the cost of a server a couple of years ago, for about two
years there, the price of DRAM doubled in servers. It did so because people decided, I'm going to make memory for
smartphones and the heck with servers, because even though it's sold in little bits, I can sell it for a lot more money
and that was never the case before.

Server memory was always the juiciest piece, but it wasn't there. Then suddenly, it was an outrageous amount of
money for memory. It's come down quite a bit because there's a glut in the market, and now we'll see what happens
when it bounces back. It's in the process of doing that now. It depends on the software. It depends on the use case.
The jury's out on that. There will be CXL memory cards for memory expansion in servers for sure. Because it increases
the bandwidth some.
It's only on bandwidth limited stuff and on CPUs. There going to be a CXL extended memory on a GPU? No, I don't
think so. There might be a memory pool that is connected by CXL to the GPUs that lets it have 10TB of all the model
data is right here, ready to go, and they can all just go and see it. That has its own bottlenecks. You'd have to have a
switching infrastructure to make sure that you could have lots of GPUs connecting into that memory and we'll see.

I love these additional things that can be added to the architecture. Smarter people than me are going to try to figure

13

Confidential

02/18/2026 at 18:56 PM UTC

out how to actually make use of them. I'm just glad it's there. There's going to be CXL memory and they're going to
sell CXL memory controllers, that's for sure. How much? I don't know. We have to find a use case running SAP for
instance. It's a great use case.

That's a memory machine and if you want to pay IBM an outrageous amount of money for a power systems machine
that can support 16TB, or you want to buy a cheaper x86 box and put half of the PCI Express slots, or most of them in
CXL memory as well as that and in this SAP HANA will run on that. Then it's a much cheaper way to run HANA. That
might be something that 50,000 companies do and they might sell, I don't know how many units, but millions of units,
hundreds of thousands of units. It's suddenly a business just in that small.

KG: Timothy, I think we can spend another couple of hours just talking about CXL. For right now we are at the end of
our allotted time here. Let's wrap up the call. Thank you so much for taking the time and sharing your insights with us.
We really appreciate it.

TP: Very happy to do so, and I thank you for the opportunity.

KG: Thank you. Bye-bye.

DISCLAIMER: The statements or opinions expressed today are those of the Advisor and not Guidepoint, who disclaims all liability
for the content provided. The Advisor may not disclose material nonpublic or confidential information or any information that would
cause the Advisor to breach any duty or obligations. Guidepoint is not a registered investment advisor and the information
provided is not intended to constitute investment advice.

14

Confidential

02/18/2026 at 18:56 PM UTC



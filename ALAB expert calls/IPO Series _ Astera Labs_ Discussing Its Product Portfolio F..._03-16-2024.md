IPO Series | Astera Labs: Discussing Its Product Portfolio Fit, Growth, and
Competitive Positioning With a Former Open Compute Project Sub-Project
Leader

Primary:

  Astera Labs, Inc.

Associated:

  AVGO

  MRVL

  MCHP

  CRDO

  RMBS

INTC

  NVDA

  AMD

Viewpoint:

  Former Executive

Moderator: Tony Scott (TS)

| Mar 15, 2024 | 36 Min Read

Allan Cantle (AC), Former Chief System and Solution Architect - Untether AI

  SU MMARY

Overview

The discussion, led by Tony Scott from Guidepoint, features Allan Cantle, a Sub-Project Lead at the Open Compute Project and
former Chief System and Solution Architect at Untether AI. The focus is on Astera Labs' upcoming IPO and its role in the CXL
(Compute Express Link) memory system opportunity. The conversation delves into Astera Labs' product lines, including PCIe
retimers, active cables, and CXL memory controllers, and their positioning within the connectivity market.

Key Insights

Allan Cantle highlights the critical role of retimers in maintaining signal integrity across computing architectures. Despite their
drawbacks, such as added cost and latency, retimers are deemed necessary due to increasing signal speeds.
Cantle emphasizes Astera Labs' strategic entry into the retimer market, noting their timing as demand for such products grows.
The COSMOS software suite by Astera Labs is noted for its diagnostic capabilities, which aid engineers in troubleshooting
interoperability issues, potentially setting Astera apart from competitors.
CXL is portrayed as a promising open standard for coherent memory sharing, with Intel spearheading its adoption. However,
proprietary solutions like NVIDIA's NVLink present significant competition.

Competitive Landscape

Company/Product

Strengths

Weaknesses/Challenges

Astera Labs

First mover advantage in CXL memory
buffers; COSMOS software for diagnostics

Retimers add cost and latency; market competition

NVIDIA (NVLink)

Established proprietary coherent bus; fast
development

Proprietary nature limits openness

Intel (CXL)

Open standard with broad industry
support

Slower adoption compared to proprietary solutions

Broadcom

Established in PCI switches

Slower to market with new technologies

1

Confidential

02/18/2026 at 18:56 PM UTC

Applications & Use Cases

Retimers: Used to regenerate signals in high-speed data paths, crucial for maintaining signal integrity in modern computing
architectures.
Active Cables: Incorporate retimers to extend signal reach in data centers, offering flexibility between passive and active
solutions.
CXL Memory Controllers: Facilitate coherent memory sharing across processors, crucial for heterogeneous computing
environments.

Quantitative Insights

Metric/Aspect

Details

Signal Speeds

PCIe Gen 5 at 32 GT/s, moving to 64 and 128 GT/s with Gen 6 and 7

CXL Latency

Approximately 100 nanoseconds, compared to PCIe's microsecond range

Market Strategy

Astera Labs leverages its first-mover advantage in the CXL market, particularly with its memory buffer solutions.
The company's diagnostic software, COSMOS, is positioned as a differentiator, aiding in troubleshooting and enhancing
product appeal to engineers.

Stage & Timing

The CXL market is in its early stages, with products like CXL 2.0 expected to gain traction soon. Full ecosystem development is
anticipated to take longer, with CXL 3.1 products likely emerging in the next few years.

The discussion underscores the evolving landscape of connectivity solutions, with Astera Labs positioned as a key player in the
burgeoning CXL market. The company's strategic moves and product innovations are highlighted as potential drivers of its success
in the upcoming IPO.

Tony Scott:
Hello, everybody. My name is Tony Scott. I'm here with Guidepoint. I just want to welcome everybody to the call
today. We're talking with Allan Cantle. Currently, he works as a Sub-Project Lead at the Open Compute Project and
was formerly a Chief System and Solution Architect at Untether AI. But I'm going to let him get into a little bit more of
his bio and explain it to you in a little bit.

But on the call today, we're going to be going through the Astera Labs story for their upcoming IPO. In particular, I
think we'll try and dig in a little bit on the CXL memory system opportunity and where they basically just fit in general
with the connectivity story.

I just want to add, if anyone has any questions, just please email in at ask@guidepoint.com. I'll get to those questions
and weave them anonymously into the conversation.

Allan, welcome to the call. Thanks for doing this with us. Maybe, as I said, you could just start give a little bit more of a
detail there on your bio and how you fit in with all the Astera story a little bit in the sense of your background and bio
there, especially with the OCP connection. Thanks.

AC: Hi, everybody. Just a little bit about me. I'm an electrical engineer and self-taught through experience computing

2

Confidential

02/18/2026 at 18:56 PM UTC

architecture in real-time high performance heterogeneous computing systems back in the ｀80s and early ｀90s. In a
sense, what goes around comes around. All of what I learned back then is now relevant today with all the parallel
heterogeneous big computing systems we're beginning to build now.

I've had 30 years of experience. I'm known as a pioneer in the FPGA compute acceleration world. Back here 30 years
ago, I started out on that. I guess you guys are familiar with FPGA acceleration. Through that work, I've been heavily
involved in these coherent busses which have happened over the years. That's typically when you're sharing memory
between multiple processors like Intel, I've had their QPI and their UPI.

The NVIDIA's NVLink is effectively a coherent bus today. But there's been several over the years. But they've
culminated into this industry effort led by Intel for CXL. I've got a long history of that.

TS: Hopefully, we had to pull all this together for us and what is this company, Astera. Just to start off, they have these
three product lines. Maybe it makes sense to just go in and a little bit they started out with these PCIe Retimers. I think
maybe a little bit of a perspective on what a retimer is and how they fit with the rest of the connectivity path, if you will.
Then we'll lay out the groundwork for their product portfolio and then we can start digging a little deeper after that.
Thanks.

AC: Chips in a computing architecture are connected together typically and historically with a PCIe bus internally, but
externally people will be familiar with Ethernet or maybe InfiniBand, etc. These interconnects have been getting faster
and faster. They're called transceivers. We've been eclipsing 100 gig in 200 gig with Ethernet and the PCIe one. It is a
little more robust. Is it 32 today with PCIe Gen 5 going to 64 and 128 with 6 and 7?

Long story short is it's extremely challenging to get these signals from A to B over any reasonable distance. It's
reduced. For example, when I was working with Molex in collaboration with various OCP companies, we were trying
to get signals just across between two of the modules, like an H100 module or an OAM module. We could barely
keep the signal integrity to get a good connection across between two modules in the two corners of an eight-
module board.

What happened was, is I saw that we were beginning to sprinkle, as I call it, retimers everywhere in the board to make
these signals. What the retimer does is it takes the halfway through the channel. It just regenerates the signal cleanly
again so that you can make the extra distance. Retimers have been around for a while. They're not the only company
to do them. They're actually zero utility from a technical perspective because they cost money, add power, take up
real estate, add latency, so hit performance. But they've become a necessary evil to get the signals from A to B.

Astera started with that. When I heard about them, I really didn't like them as an engineer, as a company. Because the
devices are, you'd rather not use them. But that's the retimer area. They got into that sector at the right time as
demand for it has been growing. That's the retimer area.

TS: That covers the retimer series. Then it looks like they took that expertise a little bit and moved into this other new
area, the active cables, doing the active cable modules. Maybe you could just run into that a little bit and describe that
product?

AC: It's effectively the same thing. It's retimers, but just buried into the cables themselves. Any given channel, again,
you've got a challenge. Signals going through printed circuit boards, it's a fairly poor channel, a printed circuit board.
When you go to a cable, you can actually travel further distance with a clean signal.

But still, as these speeds get higher and higher, everything, the distance reach shortens. When you go to a cable, you

3

Confidential

02/18/2026 at 18:56 PM UTC

typically want to stay in copper inside the rack. They talk about three meters, two to three meters is the distance you
really want to be able to do before you decide to go optical out of the rack.

Again, so in reality, where you used to be able to drive a signal from your switch chip through the cable connectors up
and down the rack and back into another processor or switch, then you could do that just from the driving the signal
from the first chip. But now you can't make it. The decision is, do you put a retimer on the boards, in the boxes
somewhere? Or a good place to put it is in a cable?

Because if you've got a short cable, like half a meter, then you might be able to do it with a passive and make it reach
with a good signal quality. But if you have a three-meter cable, you might say, actually, I need to buy an active cable
because it won't make it without a retimer in there. That gives you the option of using low-cost short cables that are
passive or paying more money for active, longer cables when you need them.

TS: Then let's move on to this new emerging standard or I don't know how the best way to describe it, the CXL
memory controller market. Maybe just a quick explanation of what that is exactly and where Astera plays in that area?

AC: CXL, as I mentioned on the intro, is a next sort of an open version of these coherent buses where you want to
share a memory and you want processors to communicate efficiently with each other in the same memory space.
We've had this technology forever, but it's always been under the hood of the processor companies. If you buy a two
socket Xeon server from Intel, the two Xeons will be connected together with their UPI interconnect or QPI
interconnect historically.

That allows those Xeon processors to share each other's memory in a coherent way. What that means is whenever you
access memory, the coherency makes sure that you get the latest copy of what's in that memory. You don't get old
data. They had their UPI. AMD had their HyperTransport. More recently, NVIDIA have obviously had their NVLink that
I'm sure you're all aware of. But there's been a long effort to try and open that up.

There was forerunners to CXL were OpenCAPI from IBM, Gen-Z from the likes of HP, and CCIX from Arm and Xilinx
back at the time. These were all standardization efforts trying to get this lower latency and coherent buses across an
open fabric. Anyway, long story short is Intel, as they do, they came along with CXL and everybody's rallied around
CXL and the others have disappeared or been subsumed by CXL.

This is trying to allow us to ！ with this massive explosion of accelerators and heterogeneous processors, we want to be
able to connect these together in a very low latency and efficient way where we can share each other's memory. That's
the reason for these efforts. CXL is the one for everybody.

There's lots of small companies and obviously Intel is pushing this extremely hard. But their competition is the
proprietary buses that are only available to the companies that own them, i.e., NVLink for NVIDIA. UPI is Intel's one.
Today, Infinity Fabric is AMD's one, and IBM has one called SMP.

TS: Now everyone's got a level set here in terms of the products and where they have their strength or where they've
come from into this industry through these retimers. The competition, maybe we can talk a little bit about each of
these different product lines has a very similar, but not everybody does retimers, not everybody does CXL memory
controllers, but a lot of these guys do compete with multiple product lines against Astera.

I'm interested, from your perspective, these guys have done pretty well at getting themselves locked in with some of
the hyperscalers. But when you think about using a retimer or using somebody for your AECs, then what are some of
the strengths you think that Astera potentially has here? Or what's the ability to hold position in terms of some of

4

Confidential

02/18/2026 at 18:56 PM UTC

these product lines?

AC: Specifically, on the retimer side, so yes, retimers are often redrivers, which are analog versions of retimers, have
been around for a long time. Effectively, a retimer is like a two ported switch. It's very similar. It regenerates the signal.
They have been available from the various bigger vendors, etc. I think it's just that they haven't necessarily been in big
demand, because the demand is grown with the speed of these signals.

Everyone has hit a wall at 32 gig, like in a server, any PCI Gen 5 server, there is an alternative, which you could use just
cables instead of PCBs. Retimers, the timing is right for a volume increase. On that front, a rising tide floats all boats,
so you've got that aspect anyway.

I don't personally have direct experience with using Astera Labs, so I don't know if there's ！ I've read the marketing
material. They say they've got the best, but doesn't everybody? But one thing is these signals are so fast that you
cannot debug them with traditional test equipment like oscilloscopes or logic analyzers. You build test functionality
into the actual chips themselves.

Astera have done a good job of marketing their ability for you to debug when you have an interoperability issue of
their retimer talking to your device at the other end or vice versa. My experience with using transceivers over the
years, just in general, is it is an absolute nightmare, especially when you're trying to make two different vendors of two
pieces of silicon talk to each other. You're trying to diagnose when something doesn't work, or you're seeing more
errors.

Is there something wrong with your board? Is there something wrong with vendor A chip, or something wrong with
vendor B chip? Invariably, they all blame each other, and nobody wants to look at the problem. They say ours is great.
Once you've got some diagnostic tools that really allow you to amplify, easily amplify where the error is coming from,
and diagnose a fault, that is worth its weight in gold.

As an engineer, selecting these devices, you want ones that are, one, they're good quality, and two, when you come
across the issues, they make your life easy in diagnosing where those issues are and correcting them.

TS: You bring up one point there, like the one throat to choke sort of scenario, like Broadcom?

AC: You actually don't get the one throat to choke. We never have really. Because a PCIe bus, you're connecting
many different vendors' devices together. As a system integrator, a system designer, you try to choke each of the
throats of the suppliers to you, and they each blame each other, or they blame you for building a bad product. It's a
big challenge.

TS: But as I was saying, it seems like this internal test, presuming that's accurate, the software, that internal test
capability is a big differentiating factor on some of these products?

AC: It's a way to say, we're not placing blame here, we're just trying to find out where the fault is, and this is
highlighting where the fault is. Typically, when it's obvious to a vendor that the problem is at their end, they will tuck
into it, but nobody wants to waste their time tucking in diagnosing somebody else's problem. This will help to actually
point the finger at where the issue is.

TS: I guess Astera makes quite a big or highlights this COSMOS software suite that they talk a lot about. Do you see
that the enablement of interoperability and how do you think about a company producing some piece of software like
this? Is that actually more of a custom piece of software in some respects, in like you're working with these different
hyperscalers to be able to incorporate your products or just the ability for them to have something like this, the

5

Confidential

02/18/2026 at 18:56 PM UTC

software suite that they talk about?

AC: While I'm familiar with it from their marketing material, I don't have direct experience of using it. But essentially, if
you think about this, it is a system design houses, the box builders, the Supermicros of this world, or if it's NVIDIA
building the VGX box, it's the box builders, they typically don't make anywhere near as much money as the silicon
device vendors do.

But they're the ones that are making the decision that these devices are too far apart, and they need to use a retimer.
They're the ones that put it all together and then it doesn't work, and they've got to find out why it doesn't work.
They've got to get the help of the vendors, if they believe there's something wrong at the vendors end. This tool is
extremely valuable to those system developers.

Certainly, the engineers putting them in, I guess the costing people, how much it costs, if the devices are 10 times the
price, the cost people in the business are going to say, we want you to put the cheapest one in between engineering
and the business side. But yes, it's engineers that decide these devices first. Provided that the costs of the devices
aren't astronomically different to the competition, then it will be a big difference. It would be for me. I would hands
down choose somebody that made it easy for me to track down technical issues with these very, very complicated
high-speed transceivers.

TS: Then you think about what some of the competition have to offer in terms of is it that they ！ again, if you're putting
together one of these systems, say you are working with a Broadcom switch or you're working with a Marvell switch,
other than the absolute performance of the retimer or what have you, this testability thing is a major factor if you're the
engineer there?

AC: To be clear, everybody has the hooks in place to diagnose what's going on. It's been for many years, I'd say well
over a decade. These transceivers have been pretty tough for a long time to work with. They do have circuitry inside
them. It allows you to work out a link and try and get it going. But they typically are like low level tools, a bit like an
oscilloscope or a logic analyzer where you've got to be pretty expert to actually dive into the problem and see what's
going on.

The more layers of software that you can put in of intelligence into your software stack to tell the engineer straight
away of, oh, you have an impedance problem halfway down your link. It looks like you've designed your board wrong.
If it can literally and it might even say five inches along this trait is where the problem is. An engineer can quickly
pinpoint the PCB area and go, oh, look what we've done. We've gone and drilled a veer like that. Oh, it's killed the
signal.

If it can pinpoint, if the software can pinpoint the problem in seconds, which where with the other tools, although the
other chips have these diagnostic capabilities, an engineer has to sit with it for a week to work out that that's what the
problem was. Then that's where the value comes.

TS: I'm with you. It seems that this is what's enabled them to make these big inroads with these hyperscalers in terms
of！

AC: I don't know necessarily. I don't know enough users of their technology. They're saying this COSMOS thing is the
bee's knees. There are certainly that ！ like I said, working in OCP, when I was at Molex, we were architecting these
open designs that you can freely see. When you were designing these boxes, the engineers would suddenly say, oh
my God, we've run out of a signal integrity budget. They would just start to sprinkle these retimers everywhere on the
board because it was like an easy get out to get it to work.

6

Confidential

02/18/2026 at 18:56 PM UTC

It's the fact that the signal integrity challenges are happening so much more frequently now. It's like the easy button of
your get out of jail free card is drop one of these retimers into your design. I think that as much as anything, they've
got a rise in tide floats or boats sort of thing going on here. All of the smaller players have been absorbed by the likes
of Broadcom, etc., and they tend to be a bit slower out of the gate. They're nimble, right place, right time sort of thing.
I think that's as much as anything.

TS: Then just talking about just designs in general and with retimers, and presumably, tell me if I'm wrong, but these
designs, once you're designed in, you're not getting designed out, basically. It will be a next level design or a version
two design?

AC: There's a saying in all industries, I guess, the devil you know, and let me assure you that there's always devils in
everything you choose, something that looks beautiful on the sheet when you get it in the product you realize, but
then you work out its idiosyncrasies and your engineers become a little bit skilled with it. There is often a reluctance in
engineering to better the devil you know. But equally, if something is absolutely disastrous in implementation, then
you will change.

The other thing to bear in mind here is these things like, I believe the footprint that these guys use for their retimers
for the PCI ones at least are predefined by PCI-SIG that Intel have driven. They actually say they're working to these ！
so these are standard footprints. All of their competitors will also use the same footprint. Therefore, as an engineer,
you could say, well, it's cheaper for somebody else's. We've got the channel working. Let's throw in the cheaper
device.

It goes on the same footprint. Obviously, competitors will be trying to get in the door, especially at volume ramps.
Then it becomes a pricing game. If they are the best, and again, that's possibly when the engineer is more out of the ！
or you've got the cost engineers that are trying to cost engineer the price down as the volume ramps. They will try
different ！ if they can drop in a replacement, they will just drop it in and see if it works, if they can save a buck.

Maybe once you've got the channel working and you've got over all the stupid mistakes with the superior technology,
the other technology could work. When you get to significant volumes, that obviously makes sense, but it doesn't
make sense in lower volumes.

TS: We talk about the move on to the cable market and just in the sense there, is there anything they're doing the
actual complete module? It seems like they're making the modules as opposed to just the chips. How do you think
about modules versus chips?

AC: I'm not too sure how their go-to market is, but these guys are not typically ！ they would typically partner with one
of the interconnect companies. They would make the cables and sell the cables. They're like a Molex, a TE, Amphenol
or whatever.
They would partner with them and work with them to get the design all up and running and working.

But their specialization obviously isn't making these cables. Whether they would sell them as their own product at the
end of the day or they would just let them be sold by the cable manufacturers is there's the cable manufacturer
products. I don't know how they're going to market, but there's various options there.

In the cable world, the cables they're making, the QSFP, QSFP-DD cables, they can either be a passive copper, active
copper, like with their retimers in or they can be optical. Now, obviously, passive copper is the cheapest. When you
start putting active circuitry in these cables get pretty damned expensive and then obviously you begin to compete
with the optical world. An optical can go much longer distances.

7

Confidential

02/18/2026 at 18:56 PM UTC

If you want to go 100 meters, you can definitely use an optical. With these copper retimers, if you've got to go to
them, depending on the cost differentials, that's where there's another argument. Now, I think today, this would be a
far cheaper solution in today's optical. But with silicon photonics coming down the road, it's in a few other
technologies, who knows? That could be a more competed area, but I think they're probably ok at the moment.

TS: Just in the sense of covering everything in the time here, let's talk a little bit about the CXL market. Number one,
as you see it developing and Astera, I think, has been one of the leading or seems to be one of the ！ they talk a lot
about the CXL market. What's your sense in terms of the development of that? I know you talked quite a bit about it at
the beginning, but Intel is pushing the standard.

There are the other, as you were pointing out, those proprietary solutions like with NVLink, with the pace of the GPU-
based AI servers, and maybe it's some of the experience you have from working with OCP. How do you see this
market will develop here in terms of the pace of that CXL market and with all the different competitors that are all the
private companies that are in there and some of the other public companies? What do you think about that CXL
market now? Before AI exploded！

AC: It's a very good question and a very complex answer. The best way to put it is, obviously, all of these processor
companies have their own proprietary variants of these coherent buses and arguably, this is the crown jewels of their
incumbency over those years as well. I've done presentations on this on my YouTube channel. You'll be able to see
strategies for CXL success with proprietary bus architecture, so that people can reference stuff I've done in the past to
see a little bit more detail.

The other thing is the likes of NVIDIA with NVLink and the others, they are going, busting forward so fast, yet CXL and
the likes is ！ I think if you want to go fast, go alone. If you want to go far, go together.

TS: I was just going to say, it's like, if you're a group, it's that whole thing of being an open standard and there's a
whole lot of you, but you've all got to come up with some agreement, right?

AC: Exactly. If you think about it, NVIDIA, well, in reality, NVIDIA was enabled by, on a supercomputer in 2018 with
IBM, called the Summit machine, where NVLink was really got going, and NVIDIA managed to say that they were
going to make that proprietary in their own. That was back in like 2018 and they've been going fast and alone with
that since 2018, and there was a bunch of other competing things like OpenCAPI at the time, but Intel was slow at the
gates and then they eventually got there with CXL.

They're very good at ecosystems, historically, obviously. We've got to go together, go far, but we're starting like six
years after or five years after they were in production with NVLink. We've got a lot of catch-up to do and I think CXL
isn't going away, but there are some significant challenges on it, from a latency, from a performance perspective, a
bandwidth perspective, relative to the competition.

But there's lots of startups that are bringing technology and I think that Astera pulled a rabbit out of the hat with their
memory, CXL memory buffer, that really got them on the map with everybody, I think, was, whoa, these guys have got
this working faster than anyone else, so that they've got that first mover advantage in the CXL world, although the CXL
world still has a long way to go before we see a full product ecosystem out of it.

TS: When you think just in general about the Open Compute and if you think like a lot of the customers for Astera
Labs in their retimer markets and such just working in that because everybody, we all know, NVIDIA's like 80%+
market share of this AI market right now and it's like the open world almost versus NVIDIA maybe and then you got
AMD in there as well. But when you think of the customers, the hyperscalers, how do you think that plays into this

8

Confidential

02/18/2026 at 18:56 PM UTC

whole CXL play right now? Is there a lot of impetus for them to make something out of CXL right now or trying to
accelerate adoption?

AC: You've nailed on the head. Arguably, everybody is chasing NVIDIA, including AMD and Intel. When you are
behind, bringing an open standard that everyone can play in does give you that ability to try and compete. There is a
lot of desire, but there are a lot of technical challenges with CXL, which I don't want to bore you with, but there are a
lot of technical challenges to overcome and we've gone from CXL 1 to CXL 2, and now CXL 3, and now CXL 3.1. Some
of us that can see the problems up front, they're gradually addressing these issues.

In essence, I believe this is possibly the only way to eventually tackle that dominance and bring it more to a
democratized world and I think that that's the reason why CXL isn't going away anytime soon. But some of the bigger
players, if you hear, just general stuff, they're not convinced. But the way CXL is implemented right now, it doesn't
make sense, some of the earlier versions.

They're not investing too heavily in it. But equally on the flip side, they know they have to have ！ they're fed up with
paying a massive amount of money to NVIDIA. Either they go with their own proprietary stuff to compete more
quickly, which there is a fair bit of that that goes on, and they'll jump on the CXL bandwagon if and when it shows a bit
more maturity.

TS: As you said up front, again, it's like Intel has been driving this from the beginning here. The other players in the
chip ecosystem, if you will, and when we think about high-speed memory in general and connectivity, maybe if you're
familiar with some of these other startups and other companies that you consider a big players in the CXL market or
you think more like ！ as you were describing, CXL seemed like it had a quite a bit of wind behind it, this AI, and
NVLink just picked up a supercharger or something and went ！ it's like exploding, it feels like it's leaving CXL in the
dust a little bit.

But who are some of these players and where do you think they are pushing hard on CXL or backburners a little bit?
What's your sense there?

AC: Fundamentally, CXL, it still runs over the physical pins of your PCIe bus, so that gives it some level of
compatibility. But essentially, what it's adding is it cuts into the PCI where it improves latency, like PCI connections are
around about a microsecond latency to get off their knees. Whereas CXL is in the 100-nanosecond territory. But when
it comes to things like using the CXL bus, using it for expanding memory, which is big for AI as well, and improving
memory bandwidth are the low-hanging fruit use cases of CXL that people are chasing right now.

You can get to that even beyond the switch with CXL 2.0. To get to more of the advanced coherency features, etc.,
sharing features, then you need CXL 3.1. People are still just digesting the spec of that before getting products. That
is the area is where you need more memory, more bandwidth. Obviously, HBM on package is covered for
tremendous bandwidth, low latency and power. But you're very much capacity limited when it comes to these large
language models, etc.

Therefore, reaching out to more memory over these PCIe CXL lanes gives you access to more capacity. Obviously,
your traditional local DRAM is available up to multi terabytes. But that tends to be relatively low bandwidth per
beachfront of the die or the area. CXL does bring some advantages there. That's where some of the opportunity lies.
But the challenges are even that latency improvement over PCIe, it's still a lot longer latency than local memory.

There's technical challenges. Some people believe that's not an issue. Some people believe it is an issue, depending
on the application. It's complex, I guess, is the best way to put it.

9

Confidential

02/18/2026 at 18:56 PM UTC

TS: I guess what this all drives at the end of the day is the pace of CXL. When would you see some adoption of CXL?
What would you think? That's what we really like. When does somebody like, hey, look, I'm going to stop putting up
some CXL！

AC: I guess the memory buffer works with CXL 1.1 directly attaching these. You see devices from like the Samsung
and Micron, etc. Astera making their own memory expansion PCI cards as well with their own buffer. You've got that
early stuff, and that can work today with Intel's latest processors and AMD's latest processors.

There are nascent market beginnings there. The big pooling memory is a big opportunity in terms of reusing old
memory in a pool, which the hyperscalers quite like the idea of, rather than buying more memory. That's a possible
early market, but you need the CXL switches for that. There's a company called XConn Tech is a startup that does a
256-lane CXL 2.0 switch. Broadcom are obviously working on their own switches. Their PCI switches are adopting
CXL, but I'm not sure where they're at. But I think they're working on CXL 3 and the latest one.

Obviously, the latest retimers from Astera are claiming compatibility. Their PCI retimers are touting compatibility with
the CXL, I believe, 3.0. But they're certainly touting higher level CXL compatibility. The pieces are slowly coming into
place. I think we'll see CXL 2.0 products certainly coming to market this year. CXL 3.1, I would suspect, wouldn't really
be deployed till next year or maybe even later, 3.1. It's happening, but it's relatively slow.

For a company like Astera, I don't know whether that translates to a huge growth or not for a company like Astera.
Like I say, they were out of the gates first, first mover advantage. A small amount of business, even at CXL 1.1 could be
huge for them, but I don't know.

TS: It seems as you were saying that it's almost like with the CXL market to really get going, there's a lot of pieces to
really all come together. People would like to see the switches as well. It's not just some of these more ！ the memory
controllers and such, but there's a lot of pieces to all lock together for the market to really have an opportunity to
really get, explode or if that could happen.

Maybe what's your thought? Does it really take somebody like a Broadcom to lay down the pathway here, when
there's something like this, which is a standard? Would you look first to a Astera, just because they are a first mover?
Or would you look to more！

AC: Good question. At the end of the day, nothing really started to move until Intel released one of their processors
with CXL 1.1 on it and AMD released their EPYC. I think their Genoa was the first to have some CXL Gen 2 functionality
and CXL 2 functionality, should I say.

With processors being available, then suddenly people can attach devices to it. Samsung has been a really big fan of
CXL, and they've been pushing their memory media devices, CXL.mem devices, and they've even been making
hybrid SSDs in memory in CXL format as well. They've been leveraging people's devices, like Montage¨s CXL buffer,
which is a competitor to Astera.

The big players do actually need to be in place. To your point, Intel and AMD are the ones that have to fire out the
gates to get everybody started. Then you need fast followers with the likes of the media companies, Samsung, Micron,
etc. Micron are building more products with CXL as well. Obviously, in the middle, there is the switch companies,
being Broadcom.

Now, there are startup switch companies. I don't know any startup media companies that are doing this. Because if
that's media, SSDs in memory is a tough business. Samsung, the Micron, the Hynix are doing all this. It makes sense

10

Confidential

02/18/2026 at 18:56 PM UTC

that the big Broadcom on the switch side is doing this.

Once you see these guys moving with engineering silicon, then it becomes much more obvious that this is happening.
I think that's really and the little players, so Astera is like a little bit of the glue in the middle. It doesn't seem like that
big a deal, but it actually is in certain circumstances. That's a good way for a small company to vacuum up. But on the
switch side, there are a number of startups.

I said XConn Tech, there's Enfabrica is another one that's doing a CXL and Ethernet switch. There are a few switch
players with different plays on how to do these switches and how they will compete when Broadcom comes stomping
along. But it's a slow elephant versus a fast mover little company.

We'll see how that goes. But really the PCI switch world has been pretty sad, really. It's been really just Microchip and
Broadcom or PLX. Broadcom bought PLX for many years ago now. I think there's room for a few switch players to
come into the game. Then processor startups starting to add CXL, I guess the likes of Ampere with their ARM
processors, I guess these guys will suddenly say, oh, now we can see this formulating. It's good timing for us to add
CXL to our products as well.

TS: You're painting the picture there, like the pieces are ！ we're talking more about this. The pieces are slowly coming
into place. But with the speed of what's going on with AI, it's a bit of a contrast right now, I guess.

AC: What you've got to remember that from an idea of, yes, we're going to do this from a business commitment of a
Broadcom or whoever to actually setting the gun off, to actually having a chip in production is typically three years
with this silicon ！ this silicon stuff is tough. It takes a while to get to production from commitment. That's what we're
going through. The sausage machine can only go so fast. You can only produce a baby in nine months.

TS: Just maybe your thoughts here, just because this market and these new developments in tech with so much is
changing here in terms of new architectures and such and a lot of it being driven by these hyperscalers, which all have
somewhat different architectures in a way. They're building their own custom servers in a lot of instances, the different
capabilities in the servers.

How does that all play in with a market, a new market like this, if you will? Do you see that making it an easier play for
some of these new standards like CXL? Or is the pendulum, you think, more moving towards this ！ we'll do our own
custom version of this memory, shared memory architecture, put it together ourselves, etc.?

AC: Good question. Essentially, from an incumbent perspective, they've already been there for many decades of
having their own proprietary. As much as anything, are they happy to let go of their proprietary architecture into this
open standard and how much do they feel of their crown jewels? Are they letting go by supporting this versus keep
running with their own?

I'm sure they got more sexy features embedded in their own proprietary ones that they're not in any hurry to let CXL
know about. You won't see those dying. But equally, whilst they're losing hand over fist to NVIDIA, there's more drive
to make these open standards work.

From other companies' perspectives, you certainly do see like the AI players, when you want to tile lots of your own
devices together, then it makes a lot of sense to actually just build your own proprietary interconnect with exactly the
features you want to get the lowest latency, lowest cost, highest performance implementation.

I don't think we've seen the last of a proliferation of proprietary buses when you're talking between your own devices.

11

Confidential

02/18/2026 at 18:56 PM UTC

Because you need thousands of these things in a data center connected together. But the CXL will gradually consume
more of that as it advances as a standard and people will make decisions as to whether to drop their own propriety
piece. It's a bit like PCI has been here forever. It's done tremendously well, but haven't stopped those proprietary
buses historically, and the same will go with going forward, I believe.

TS: That's an interesting point there you make with the PCI. Is this world of AI compute, accelerated compute any
different when compute came out of on-prem to cloud and the development of cloud? Is it just an extension of that?
But now we have AI compute in the cloud, it's a different form of compute. But it's pushed toward those somewhat
more proprietary architectures.

AC: The biggest problem is it's not only a different form, something they call bisection bandwidth. It's the amount of
bandwidth that you need to get out of a device off of the package to talk to other devices, other packages, be they
the same type of processor or a different type of heterogeneous processor accelerator. Typically, historically, it's the
same equation.

You have a very high memory bandwidth, and your I/O bandwidth tends to lag behind your memory bandwidth by
maybe a factor of 5 to 10. But now we've got these HBM bandwidths of 5 to 10 terabytes per second, we need 1 to 2
terabytes per second of I/O bandwidth or more coming off of these packages. In fact, we often need more with the
demands of AI for huge amounts of memory, huge bandwidths at low latency.

The AI is putting a massive stress on the need to escape with these ever-higher bandwidths. By the way, that's where
co-packaged optics will come in as a potential challenger here as well. You're coming in from the high end. You can
potentially get many terabytes per second off of a chip through silicon photonics, if it lives to its promise. But you've
got to be also aware that silicon photonics has been 10 years away for the last 40 years.

TS: Since we do have a few minutes left, you and I were talking here about the company like Astera Labs. You
described a little bit like they're providing the glue and this kind of thing. But the whole notion here is a company like
Astera and especially the way if we think of chiplet architecture, I'm going to move to chiplet architectures, etc.

Is something like an Astera would be a key company that you think could potentially evolve into this marketplace,
especially with the software capability they have and the interoperability they're working towards? Isn't this what the
chiplet market in a Holy Grail way thinks about?

AC: If you think about what they're doing with their memory buffer, they're bridging this PCI CXL interconnect into
memory. That's what that CXL buffer they provide does. But you need a lot of energy to move I/O on and off of
packages. A lot of these ！ now we're moving toward chiplets. Obviously, at the moment, industry is just the big
companies do all the chiplets themselves. They build all their own chiplets or they partner with memory companies or
whatever. But it's a very tight vertical collaboration.

Whereas in OCP, we're trying to standardize make an industry standard of chipletization for those smaller players to
bring chiplets to market and for us all to benefit from them. The reason for chiplets is you literally crush the entire
server into a package. You're minimizing the distances used to be like 18 inches up and down your server or more to
a couple of millimeters between chiplets. You can save a tremendous amount of energy and moving the data
between the various components.

I/O components are a key area for chiplets. It would make logical sense at some point that Astera could go down that
chiplet avenue. I don't know that they are. But one of the problems is these retimers, etc., you have a lot of energy on
the input port and the output port and that makes them pretty power-hungry devices. There could be some clever

12

Confidential

02/18/2026 at 18:56 PM UTC

system ways as I pushed again in some of my presentations. I've given it. It would be good to think about channels a
bit more from an energy efficiency perspective.

I think that would be an opportunity for somebody like Astera to branch into I/O type chiplets, which are effectively
tiny with just variations on their current retimer products, basically.

TS: On that note, I think I'm going to wrap up the call in fascinating conversation with you and just where Astera sits
and what some of the challenges might be ahead and where the opportunities that they have right now seem to be.
Thanks very much for the time today and the chat and all your insights, Allan.

Thanks, everybody, for listening in. If anybody has any extra one-on-one follow-ups, don't hesitate to reach out to your
Guidepoint representative. We¨ll gladly hook you up with Allan for a little bit of extra one-on-one meeting time.
Thanks again. Say goodbye. Have a good weekend, everybody. Speak to you next time. Thanks very much.
Goodbye now.

AC: Thanks. Bye-bye.

DISCLAIMER: The statements or opinions expressed today are those of the Advisor and not Guidepoint, who disclaims all liability
for the content provided. The Advisor may not disclose material nonpublic or confidential information or any information that would
cause the Advisor to breach any duty or obligations. Guidepoint is not a registered investment advisor and the information
provided is not intended to constitute investment advice.

13

Confidential

02/18/2026 at 18:56 PM UTC



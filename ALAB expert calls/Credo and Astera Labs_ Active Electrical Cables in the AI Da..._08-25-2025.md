Credo and Astera Labs: Active Electrical Cables in the AI Data Center Stack ¡ª
Technical Differentiation and Vendor Positioning

Primary:

  Credo Technology Group Holding Ltd

  ALAB

Associated:

  MRVL

  AVGO

  NVDA

Viewpoint:

Industry Consultant

Moderator: Sheetal Duggal (SD)

| Aug 25, 2025 | 38 Min Read

Chuck Byers (CB), Chief Technical Officer - Industry IoT Consortium

  SU MMARY

Overview

The discussion, led by Sheetal Duggal of Guidepoint Insights with expert Chuck Byers, focuses on the role of Active Electrical
Cables (AECs) within the data center stack, particularly highlighting the companies Credo and Astera Labs. Byers, with extensive
experience in electrical engineering and data center infrastructure, provides insights into the technical differentiation, vendor
positioning, and future landscape of AECs. The conversation delves into the adoption of AECs in hyperscaler infrastructure, their
technical specifications, and competitive positioning.

Key Insights

Technical Niche: AECs serve a specific niche, transmitting hundreds of gigabits over short distances (1 to 5 meters), crucial for
interconnecting GPUs in data centers.
Power and Latency Concerns: Hyperscalers prioritize power efficiency and low latency to maximize GPU performance and
reduce energy consumption.
Market Dynamics: While NVIDIA currently dominates the AI accelerator market, diversification with players like AMD, Google,
and Amazon is anticipated, potentially impacting vendor preferences for AECs.
Vendor Comparison: Credo and Astera Labs are direct competitors, each with unique strengths. Credo offers a higher loss
budget and supports PCI Express version 7, while Astera benefits from a strong partnership with NVIDIA and superior software
adaptability.

Competitive Landscape

Aspect

Credo

Astera Labs

Market Position

Competes with PCI Express version 7

Strong partnership with NVIDIA

Technical Strengths

Higher loss budget (40 dB)

Superior software adaptability (COSMOS)

Adoption

Suitable for longer cable lengths

Preferred in NVIDIA ecosystem

Future Outlook

Positioned for diverse AI accelerator market

May face challenges with market diversification

Applications & Use Cases

AECs are essential for scaling data centers, enabling efficient interconnection of GPUs within racks and across multiple racks. They

1

Confidential

02/18/2026 at 18:56 PM UTC

are particularly relevant in environments where low latency and power efficiency are critical, such as AI model training and
inference.

Quantitative Insights

Metric

Loss Budget

Credo

40 dB

Astera Labs

36 dB

Power Consumption

Lower power usage compared to optics

Similar power efficiency

Cost

~$1,000 for 800-gigabit AEC (5 meters)

Higher cost for equivalent optics

Market Strategy

Both companies are engaged with hyperscalers early in the design cycle, aiming to align their product roadmaps with emerging
data center needs. The discussion highlights the importance of standardization and interoperability in future market strategies,
particularly as the ecosystem diversifies beyond NVIDIA's dominance.

Stage & Timing

The market for AECs is in a growth phase, driven by the increasing complexity and scale of data centers. As AI workloads diversify,
the demand for efficient interconnect solutions is expected to rise, with both Credo and Astera poised to capitalize on these trends.

SD: Good afternoon ¡ª good morning, Sheetal Duggal with Guidepoint Insights. Thanks for dialing into our call today.
We're going to be talking about Credo and Astera Labs, really just kind of thinking about AECs within the data center
stack and really kind of just walk kind of technical differentiation, vendor positioning, and kind of how to think about
the landscape going forward.

With that, we have Chuck Byers here, who's a long-time contributor and can provide his insights on the matter. If you
have any questions, you can always email me at ask@guidepoint.com or can [INAUDIBLE 1:01] as they come in,
people just come to ask@guidepoint.com. Today's call should be about 45 minutes. And with that, Chuck, great to
have you here again. It's ¡ª background¡ª

CB: Thank you, Sheetal. It's always a pleasure to join you on these calls. You want me to say a few words about my
background, master's degree in electrical engineering. I worked for 22 years at Bell Labs as a Bell Labs fellow there,
mostly on switching and various kinds of interconnect and fiber optic architectures as well as wireless infrastructure. I
worked for 10 years at Cisco, where I worked on media processing, analytics, edge computing, Internet of Things, and
quite a bit of work in data center infrastructure.

I currently serve as the chief technical officer of the Industry IoT Consortium. We're around 100 member companies.
We were associated with the Object Management Group and now the Digital Twin Consortium. And we're really
interested in trustworthy Internet of Things, digital transformation, and that brought us to this question of how do we
build a data center to manage hundreds of billions of sensors that we expect to be peppered across the planet.

And the answer is we need lots of clusters of GPUs with lots of very fancy cabling to interconnect the members of
those clusters into large-scale systems that can train and run inference on those AI models. So that's what sort of
brought me to this whole question of what's going on in terms of the hierarchy of interconnect, different rates,
different reaches, the length of the cables, different topologies between the GPUs and the cables that connect them
together.

2

Confidential

02/18/2026 at 18:56 PM UTC

And that leads me to companies like Credo and Astera who make products like retimers, active electrical cables and
other things that we'll get into when we talk about the technology that are absolutely essential to the scaling up,
meaning putting lots of different GPUs in the same cabinet and make them all work as one and scaling out, meaning
hooking together many cabinets full of GPUs into large super clusters or what NVIDIA calls a SuperPod. All of these
things potentially use active electrical cables and the kinds of chips that Credo and Astera build, and I'm happy to be
here to talk about those. Thanks.

SD: Fantastic, Chuck. So, you know, maybe just kind of going to the topic list. When you look at AECs, you know, and
we think about kind of where the most adoption is kind of happening in the hyperscaler infrastructure, whether it's
kind of GPU to switch, CPU to DPU, SmartNICs, CXL, how do you think about, you know, where the leadership is kind
of coming from right now and how we should kind of continue to expect it to trend from here?

CB: Yes. The thing that's interesting about active electrical cables is they fit a fairly narrow niche in the market. That
niche is where you need to send hundreds of gigabits, maybe 400, 800 gigabits up to 1.6 terabits per second across a
relatively short distance. And the sweet spot in terms of distance, the length of those cables, the distance between the
GPUs you're connecting together with those cables is between about 1 meter and about 5 meters, although I think
that Credo can go about 7 meters on certain circumstances.

So it's very ¡ª it's probably overkilled, something like an active electrical cable is overkill. If you need to go from one
die to another die inside of the same chip, you would just do that with an electrical connection without paying all of
the penalties associated with building all these retimers and gearboxes and other things or even multiple chips on the
same circuit board, you probably aren't going to go more than a few tens of centimeters and you wouldn't need
anything like an active cable for that.

When you start to go off of a circuit board and through like a backplane or interconnecting bunches of circuit boards
up a large-scale infrastructure, like, for example, the NVL72 servers or the upcoming Kyber racks from NVIDIA, then
there's equivalent racks that are being built by AMD and others. Then you start to think about, well, I'm not able to
push those electrons down that cable fast enough because the cable has real physical characteristics.

It's got inductance and capacitance and loss and crosstalk and it creates all kinds of inter symbol interferences among
the various signals that you're trying to jam down that cable. So what you have to do is have something fancy on both
ends of the cable if the cable is too long or too lossy in order to compensate for the problems that potentially occur
inside of that cable. They're inevitable. You can't do anything about it. That's just the nature of electrons. And those
things are typically called retimers. We'll go into that in a minute.

Once you get over, I don't know, a handful of meters, say, 5 or 7 meters, maybe 15 feet of cabling, then you get to the
point where you simply run out of steam with electrons. Electrons simply can't be pushed through that much copper
wire and expect to have a usable signal on the other end. Under those circumstances, call it, 5 meters, you probably
have to think about going from electrons to photons, which means you change from a copper cable to a fiber optic
cable.

And that will get you using a fairly inexpensive type of fiber optic cable called an AOC or active optical cable, kind of
the big brother of the active electrical cables. You can go 30¨C100 meters with that. And then once you get beyond
that, then you start using these fiber optic transceivers, the traditional little things that you plug into the quad small
form-factor pluggable boxes that exist on all of these servers. And then you can run whatever kind of transceiver you
want, 2 kilometers up to 120 kilometers to go very long distances.

You might be sort of concerned about distance. And distance turns out to be one of the reasons why AECs fit the

3

Confidential

02/18/2026 at 18:56 PM UTC

sweet spot that they're in. And 5 meters or so is kind of an interesting distance because the racks that these things in
are about three quarters of a meter wide more or less. And if you stack a rack a bunch of them next to each other,
what we call a lineup in the data center, maybe five or seven of those racks together, what you're going to do then is
try to find a cable technology that will span the entire length of that lineup of racks that you want to assemble together
into your cluster of GPUs.

And that's the sweet spot that both Credo and Astera are chasing is this rack-to-rack interconnection. If you need to
scale out beyond what you can fit in a single rack of GPUs, then it starts to make sense to use active electrical cables to
get you those 3, 4, 5 meters to go to a half a dozen other racks near you. That's the sweet spot right now in the place
where I think they're used.

They're probably not going to be used very much on the GPU to network interface connections. Those are typically
only 50 centimeters long or something like that, and you probably don't need these internal connections to have the
active electrical cable capabilities. I think under those circumstances, you would just use direct attached copper
connections and let the chips on both ends sort out the signal integrity, which they should be capable of doing.

SD: Got it. And when you think about the typical factors about when like the hyperscalers picking AECs over DACs or
optics, you know, when we're trying to weigh power latency cost, how do you think about those? And how do you
think the hyperscalers think about those?

CB: Well, hyperscalers are really worried about power and latency. They're really worried about power because if you
invest a lot of power in running these GPUs, and remember, some of these GPU chips can be 1,200 watts per chip. It
turns out that the difference between a fiber optic transceiver it may be 20 or 25 watts and an active electrical cable
endpoint, it may be 10 watts. If you multiply that by the hundreds of transceivers that you may find associated with a
rack of equipment, it adds up fast.

And over the span of, say, 100-megawatt data center, which is about the size we tend to be building these days, that is
going to cause you some really serious problems. It might be several percent of the total energy use of your data
center could be involved in running those optical transceivers. You'd prefer to take those megawatts and use them to
run more racks or GPUs. So power efficiency is really one of the names of the game in order to get the most out of the
energy available to go in your data center, which is constrained.

The cooling capabilities of your data center, which is constrained because every watt in turns into heat and it has to be
removed by the air conditioning systems. And really, you're really trying to understand how all this goes together at a
systemic level and you want to put most of the energy investment into the things that are making you money, which
are the GPU processing chips. In terms of how many gigabits per second per what we call lane, an individual pair of
wires is called a lane, and they're differential.

So when one wire drives high, the other wire drives low in most circumstances, and that helps you get rid of certain
types of noise on the far end of that wire. So those couple of wires in each direction, those lanes run at different
speeds, 56 gigabits per second, 105 gigabits per second, 112 gigabits per second. And lately, we've been talking
about doubling it again to 224 gigabits per second. Notice, please, that these numbers are all a little higher than the
even 100 that you might have expected. And that's the overhead associated with various kinds of encoding and error
control that happen on these links.

So for example, 112 gigabit per second link is actually carrying 100 gigabits even worth of traffic. And then the
remaining 12 gigabits is the various overheads and encoding stuff that happens in order to get that efficiently across
the cable. So I would say that the data centers obviously want to go as fast as they can on those cables. But they don't

4

Confidential

02/18/2026 at 18:56 PM UTC

want to go so fast that they start having errors in the signal transmission across those cables at the length of cable that
they need to get to the far side of the cluster of GPUs.

So I suspect that what they try to do is use the cheapest, lowest power technology they can get away with for a given
cable channel speed mix. And for active electrical cables, that tends to be either 112 gigabits per second or 224
gigabits per second per lane, 224 is just an emerging technology this year, by the way, 112 is the mainstream. Then if
you need to go like a 400-gigabit channel, you might use four times 112 gig SerDes with parallel wires going down
that fat cable.

If you need to go to 1.6 terabits per second, four times higher, then all of a sudden you start looking at pretty big fat
cables with 16 pairs of wire in each direction. It gets to be unmanageable faster. So the reason that they want to go to
double data rates like 224 as opposed to 112 gigabits per second is it halves the number of cables in each ¡ª or the
number of wires in each cable, and that makes the cables cheaper, more reliable. And it turns out that a big fat cable,
the size of your pinky or maybe even the size of your thumb is really hard to manage.

I mean, you can't run it around the backside of all these GPUs and get into the cable trays and run 3 meters to the next
rack and down. It's just too stiff to run around that place efficiently. And if the cable is too big in diameter, it also tends
to be in the place where you'd love to have cooling flow, especially if you're an air-cooled system, many of them are
moving to liquid cooling. But in any event, the physical volume occupied by big bunches of fat cables tends to be
better utilized by things like improved cooling systems.

So there's a lot of trade-offs, thermal, electrical, optical performance that these folks care about. Finally, let me talk a
minute about latency. So these ¡ª the types of traffic that you'll see on these inter-unit cables inside of a cluster in a
scale-out scenario, they tend to be related to inter-GPU traffic. So for example, if I'm running a big training run, might
last a month, I'm pulling in sort of everything I can scrape off the internet, and I'm running it through my training
algorithms and trying to build a model for the AI inference that I'm going to be doing for the rest of the year on that
model.

What I care about is maximizing the efficiency of the traffic between the many GPUs, maybe thousands of GPUs in the
cluster doing that training. And when one GPU's processor core thinks that it needs a piece of data that's stored in the
memory of some other GPU, it launches a request over that cable. And that request rattles through the cable and
comes to the remote GPU and the remote GPU catches it real fast, fetches the data that it needs out of memory and
sends it back.

The round-trip delay for that is directly in series with the performance of the processor who made that request
because that processor is sitting there waiting, it's idled. It's sort of queued up waiting for that return of that data. And
the longer it takes for that data to make the round trip request out, fetch from the remote memory and then return
that data back, the more processor cycles that individual requesting CPU core is wasting.

So if I can shave a few nanoseconds, that's billions of seconds, off of the round trip delay time, the latency of that
channel, then instead of that GPU core sitting there idling for a couple of hundred instructions wasted, it might only
waste 50 instructions or something. Low latency cables are really important in terms of improving the overall capacity
of these GPUs because there may be 20,000 or 30,000 cores in each GPU chip. There may be thousands of GPU chips
in a cluster.

And when you add all up the amount of time, the amount of useful cycles that are being wasted waiting for those
latencies to come across those cables, it adds up to an appreciable performance impact on these very expensive
systems. And the data centers don't like that. So when they're out shopping for cables, they ask about latency.

5

Confidential

02/18/2026 at 18:56 PM UTC

And if a particular cable technology because they were a little fancier or a little more clever on the design of the
retimers internal circuitry, if that saves a nanosecond or two, they're going to pay a large premium for that cable
because over the life of that cable, it's going to yield a lot better efficiency on the very expensive GPU clusters that,
that cable supports. So all of these things go into the decision process of the particular cable technologies and the
suppliers of those cable technologies and low latency is most definitely one of the important things on my shopping
list.

SD: Super helpful, Chuck. Maybe we can kind of dive into kind of Astera and Credo for a second, kind of how they
compare in terms of kind of AEC ¡ª retimer architecture in terms of kind of architecture, power efficiency, integration
complexity. We could start with that, and then I have a follow-up.

CB: Sure. So both of them make retimer chips that at the highest level, functional level are probably interchangeable.
So I would consider them direct competitors. And I would say that if I was in the market for an active electrical cable or
retimer to serve other purposes in my system, I would consider them both on an equal footing. There are some subtle
differences, some of them technical, some of them commercial, but they are certainly going to weigh on you as you
make that decision.

So let's just talk for a second about the Aries PCI Express retimers that are made by ¡ª that's one of the chip families
that are made by Astera. They have quite a bit of market traction because NVIDIA has a strong partnership with
Astera. And as a result, they tend to find their way into the various kinds of reference designs that are influenced by
NVIDIA. And if you take a look at what Jensen Huang had said during his remarks in March at the NVIDIA conference,
there was a slide behind him that showed NVL72 racks.

That's the big rack, size of a refrigerator, costs about $3 million, and it's got 72 Blackwell-class GPUs in it. It turns out
that there were about 16 images on the video wall behind him of different implementations of that exact same rack.
There were some that were made by Lenovo and Supermicro and Dell and all kinds of different recognizable
companies as well as, you know, bunches of other companies that are more captive to, for example, the large-scale
cloud suppliers.

The point is that if NVIDIA says we really like a retimer from Astera, which I think they have said, then all those other
manufacturers who are building NVIDIA reference designs in order to be software compatible with NVIDIA's-driven
software, they're going to preferentially like Astera. So if you think that the ecosystem is wrenched around significantly
by the 800-pound gorilla that is NVIDIA, then Astera has probably got a bit of a leg up from a geopolitical
perspective. Other things that are interesting about Astera is that they have some products that tend to stop at PCI
Express version 6.

At least I'm not aware of an announced PCI Express version 7 from Astera yet. Credo has a PCI Express version 7
retimer. And that's sort of the difference between the ¡ª well, we talked about the difference between 112 gigabits and
224 gigabits. It turns out that for PCI Express retimers, the difference is between 64 giga transfers per second and 128
giga transfers per second. Those are the kinds of PCI Express runs on a slightly different clock rate, but it's all the
same stuff. And so I think that in terms of embracing quickly the most recent standards, I think Credo may have a leg
up there.

One other thing that's interesting, it's a little bit of a high-technology question. It's got to do with what's called the loss
budget, and it's measured in decibels. So every inch of cable has a certain fraction of a decibel of loss. And over the
length of, say, 3- to 5-meter cable, that adds up fast. It turns out that Astera can manage a loss of 36 decibels.

And that just basically means that when you get to the end of a certain length of a certain type of cable with a certain

6

Confidential

02/18/2026 at 18:56 PM UTC

kind of conductors and insulation on it, if the loss in that cable adds up to more than 36 decibels and Astera retimer
can't pull that information back out and build a perfect error-free channel anymore. The difference is that Credo has a
40-decibel loss budget. So they can get 3 more decibels, 16% or something additional cable length because they
figured out how to make their receivers a little more sensitive and their filter algorithms, which we'll talk about in a
minute, a little more adaptive.

And therefore, they can handle a slightly lousier cable or a slightly longer cable or a cable that may have some kinks
or moisture in it or something that causes it to have a little bit more loss. Under those circumstances, I'd say
advantage, Credo. Other things that I think are pretty important is the fact ¡ª an advantage of Astera in this case, is
Astera has a technology they call COSMOS, which turns out to be software. You may say that software feels awful far
away from all these analog and digital filters and synchronization circuits that exist in a retimer chip.

But it turns out that those retimer chips are themselves intelligent. And you have to have some kind of a thing that
monitors the performance of the signals flowing through the channels of these active electrical cables. And then you
have to have a thing that adapts as you think the signal on the far side is a little too low or a little too much high-
frequency energy in it or whatever it is. You go in and you program the retimers on both ends of that connection to try
to adjust their parameters. The COSMOS software from Astera is superior to the equivalent software from Credo.

And therefore, Astera might be a little bit more rapidly adaptable to changing environments in these scenarios. So I
would say that if you ¡ª you're going to try to pin me down for which one is better. And the answer is neither of them
are better for the entire market. If you have a particular application that wants to stretch a cable from, say, 5 to 7
meters, you might be better with the extra 4 decibels of loss capabilities in Credo. If on the other hand, you know that
your stuff's got to interoperate intimately with everything from the NVIDIA ecosystem, then advantage Astera.

And what you have to basically do is take a look at all those requirements technical requirements of which many of
them we've talked about, power, bit error rate, length, adaptability and so on. And then you also have to look at the
commercial criteria. Where do they fit in an ecosystem? How is their supply chain? Can you trust those suppliers with
your architectures and your future visions for how the world is going to work.

Certain semiconductor suppliers would not be trustworthy under those circumstances. I think that Astera and Credo
both are. So maybe that's a non-issue. But you got to ask yourself all those technical and all those commercial
questions. And then you got to negotiate your best price. And all of that together will lead you to an engineering and
business decision associated with which of those suppliers might be the best for your particular work.

SD: Well said, Chuck. I guess my follow-up just would be, you know, when you just said, look, neither is better. One is
more is ¡ª the loss factors are just ¡ª offer Credo an advantage and then it seems like the integration or ¡ª really the
integration with NVIDIA and things that puts us there in a better place. I guess, is that ¡ª did I characterize that
correctly? Please rephrase ¡ª let me rephrase it. So if that's the key¡ª

CB: Yes.

SD: Got it. So I guess my follow-up there is, look, if we're going to a more heterogeneous AI accelerator environment,
so, you know, say that the training environment has been incredibly NVIDIA dominant, just given the sheer prowess
and technological innovations that they've been able to provide through Hopper and Blackwell and soon Rubin, I
guess, at some point. I guess if we think about just where we are in the kind of AI workload trajectory.

And we're sitting now in a world where there's a very good chance that NVIDIA's ecosystem, while incredibly powerful
and will always remain a big ¡ª you know, probably the dominant player here is likely to see more players enter,

7

Confidential

02/18/2026 at 18:56 PM UTC

whether they're custom AI accelerators, you know, from more ¡ª sorry, specialized AI accelerators from like the
Cerebras or the Groqs of the world or custom ASICs from the Amazons, you know, the Googles, the TPUs of the world
or some other combination of other GPU players in ¡ª AMD is the one that comes to mind here.

I guess, wouldn't ¡ª I can understand you saying, look, neither is better they're both ¡ª they both kind of have set of
rules. But if I told you that, look, we're going to a world where it's going to be less NVIDIA dominant just because
there's going to be more diversification. Would you then say that, well, that probably gives the distance and how
Credo thinks about it an advantage, at least currently and how kind of ¡ª because the distance might be prioritized
more than maybe the NVIDIA integration advantages that Astera offers?

CB: Yes, that's entirely possible. And you're correct to notice that NVIDIA, although they have something like 80% of
the market share on large-scale AI clusters right now, I don't think that they're going to sustain that forever because,
well, for one thing, there might be antitrust if they get much higher than that. Second thing is that AMD is building a
fairly sophisticated ecosystem to counter NVIDIA's already very sophisticated ecosystem. And in particular, the thing
that AMD is working on is called the Ultra Accelerator Link Consortium.

AMD was a founding member, and it turns out that pretty much every semiconductor company, except for NVIDIA, is
sitting on, you know, the high levels of governance in that organization. And you're also seeing the big data center
players, the hyperscale and the neo cloud players sitting at that table. Everybody's mission is to try to blunt the force
of NVIDIA somehow. So, you know, if it was just AMD against NVIDIA, I would probably bet on NVIDIA.

But if you're starting to look at companies like Broadcom and Microsoft and Intel and, you know, you might also see
Google and Amazon and CoreWeave and DigitalOcean and Lambda Labs and all those neo clouds in there, they're
all asking for an alternative to NVIDIA. And as a result, the standards sort of de facto standard dominance that
NVIDIA's NVLink and InfiniBand connectivity have is going to likely be blunted by UALink and its derivative of Ethernet
that it uses, which, of course, is a 30-year-old technology plus.

All those things are all, you know, going to get refreshed and generate this sort of connectivity battle. Might feel like
VHS versus BetaMax for those of you who remember what that felt like. People had to place their bets and buy their
equipment and hope that they bet it correctly. And of course, I had BetaMax, so I didn't. But the question then
becomes, will both Astera and Credo build products that can be used in either the sort of the NVIDIA NVLink world
and the AMD and partners UALink world? I think the answer is inevitably yes. That's going to happen.

And as a result, I think that the impact of being joined at the hip with NVIDIA as we believe Astera is today, is going to
be blunted. And as a result, I think that, that might be less weighted on your criteria matrix, the big spreadsheet that
you should do if you're making these decisions than it might have been last year when NVIDIA was apparently
unstoppable.

SD: Yes. That makes sense. I wanted to ask like, you know, just thinking about that, we're talking about the difference
between Astera and Credo, you know, retimer design, service performance, and signaling continuing technologies.
What role do those play in kind of differentiating these different vendors, if any?

CB: Yes. Well, the signal conditioning is really what the retimer does. And it does it sort of for two important criteria in
the signal. So what's on these wires is a volt or two of pulses. And those pulses tend to be pulse amplitude modulated
PAM4, which means the pulses can be four different heights. They can be sort of 0 volts or 0.3 volts or 0.6 volts or 0.9
volts, something like that. And that means that every time you send a pulse down the cable, you can actually encode 2
bits of information across that channel.

8

Confidential

02/18/2026 at 18:56 PM UTC

And you can hypothetically go to more voltage levels, but the problem is that if you go more voltage levels, the
distance between a 01 and a 10 start to become undistinguishable, especially at the far end of a long cable or in the
presence of various kinds of interferences. So what you basically have to do in order to pull that data out of the far end
of the cable and restore it to 100% integrity reliable data connections is you have to worry about what the voltage is
and where the timing of the edges when you transition from one pulse to another is.

And that's basically what retimers do is they launch a signal into the cable that has a large voltage swing and is very
precisely timed so that those symbols as they're called, the bits that are encoded as voltage levels, they propagate
down that cable at nearly the speed of light, about seven tenths of the speed of light down the copper cables. And
you basically go ¡ª you have a whole bunch of cables in the pipeline. It's kind of like if you imagine shoving a bunch of
ping pong balls into a hose, right? There's a whole bunch of bits in flight in the cable.

And then at the far end, what ¡ª at the near end, you try to launch them in with enough speed and power and with an
abrupt enough edge so that you've done the best that you can to drive that cable with a signal that can be recovered
on the far end. And at the far end, you look at the little small signals that remain after all the losses of the cable and
then you try to adjust their voltage so that you can get good decisions about which of those four levels, the output
voltages.

And then you try to adjust the timing because the position of the front and back edges of those pulses mushes around
a little bit because of the various losses and capacitances and inductances of that cable. And as a result, the edges
that used to be clean when you launch them in, you know, a nice vertical edge on where that pulse goes up and back
down, it turns into more of a trapezoid on the far end. And if it mushes out too far, you get what's called intersymbol
interference, which means that the previous symbol is actually pouring voltage into the symbol that you're trying to
decode right now.

And as a result, you have trouble making a decision about whether or not that little electron that you measured was
associated with the previous symbol or the one that you're trying to measure right now. That's called inter symbol
interference. It's the big problem that retimers are trying to fix. And they use several different fairly sophisticated
signal processing technologies to do that. The first thing that they do is a simple equalization. It's kind of like turning
the base knob up on your stereo. So you turn the base knob up and it gets stumpier. Well, there's an analogy to that
at 224 gigabits per second.

You adjust the analog launch power at certain frequency bands into that channel, and you can actually compensate
for some of the problems that could have occurred in that channel so that you get a more usable signal out of the far
end. That's pre-equalization. You can do various kinds of what is called finite impulse response filtering. And that
basically is just a fancy word for using some digital techniques to try to figure out what the signal was on the far end.
There are three particular kinds of filtering that are common in these retimers. One is called FFE, that means feed-
forward equalization.

And basically, what you do is you take the signal that you received at some point in time and then you delay it by one
bit interval and then you sort of add and subtract it using various kinds of programmable gain engines with the five
symbols that happen next. And if you adjust the gains on those engines correctly, this is all done inside the retimer
chips, you can actually compensate for some of those inter symbol interferences. There's a related technique called
decision feedback equalization. It tends to be one that has pretty low noise.

It tends to use more taps, meaning more of these delayed elements about 40 of them. And it only looks sort of
backward in time where there's a kind of a hack that the feed-forward equalization also uses to look sort of forward in
time, what symbols are coming next. It turns out that, that adds some latency. So there's trade-offs there, but it's good

9

Confidential

02/18/2026 at 18:56 PM UTC

at reducing certain types of interference. And the final thing that I think is probably really interesting is continuous
linear ¡ª Continuous Time Linear Equalization, CTLE. And that's an analog technique that those software engines like
the COSMOS stuff from Astera.

Basically, it goes in and it adjusts the analog things. If you think about a graphic equalizer back when you were, you
know, disc jockeying some days, there's all those little sliders that go up and down. Well, they have the exact analogy
of that. Different frequency bands can be applied with different gains and continuously adjusted using this thing
called the Continuous Time Linear Equalizer.

The final thing that tends to help with these channels, especially channels that you have ¡ª the cable is just a little too
long or the wire is just a little too nasty is to use various kinds of forward error correction. So one of the things that you
can do with that extra 12-gigabits of overhead in the 112-gigabit channel beyond the 100 that you actually need to
get the signal across is you can encode some stuff in there about whether or not there's an error. It's kind of like a
fancy version of the parity that you may have been familiar with in memories.

And that stuff that Reed-Solomon coding, as it's often called, will enable you to live with a slightly noisy channel where
maybe 1 out of 1 million bits is incorrectly decoded. If you have some kind of forward error control, meaning that you
put some information into the overhead of that signal, that will let you get that error control ¡ª you can sort of recreate
what the erroneous bit was and correct it. So you might be able to, for example, discover any 2 bits of error and
correct any single bits of error in a frame of thousands of bits.

That would potentially let you live with a little bit of loss and a once in a great while erroneous decision on the receive
end of that cable because the forward error correction will eliminate those errors. Of course, forward error correction
adds latency because you have to wait for the whole frame to come in before you can decide whether or not it had
any errors in it. So all of this stuff is all traded off with the performance.

The more sophisticated these digital filtering algorithms like CTLE and DFE and FFE, they're going to add extra
complexity to the chip, chip area, which means chip cost. They're also going to add to power dissipation. So a simple
retimer might be 6 or 8 watts, a complex retimer might be 12 or 15 watts. And as I said before, those differences add
up fast. That might have been a little more technology than you needed, but I used¡ª

SD: No, that's good.

CB: That's the amount of sophistication that Credo and Astera are putting into their chips.

SD: No, that makes sense. How early do you think these vendors are engaged in hyperscaler design cycles? And I
know you mentioned NVIDIA and Astera are in that relationship. But I'm curious how quickly you think it is and
whether, you know ¡ª yes, I'll start with that and I have a follow-up.

CB: Well, they certainly have a significant amount of relationships with every potential user in this space. And it's not
just NVIDIA or chip companies like NVIDIA and AMD and Cerebras, and there's a whole bunch of other chip
companies that are building various kinds of acceleration chips, including the ASICs that are coming out of Microsoft
and Amazon and Google as well as companies like SambaNova and FuriosaAI and Groq and Tenstorrent. These
companies make tensor processing units. They're generally used just for AI inference, but they can be much more
power efficient.

So I suspect that these ¡ª that Astera and Credo are having sort of weekly or monthly meetings with everybody who's
looking like they're going places in the chip space for AI acceleration. And having those meetings probably under

10

Confidential

02/18/2026 at 18:56 PM UTC

NDA means that you can get a bit of a viewpoint into the crystal ball. You know what's coming in the future. You know
when they're going to be able to support 800 gigabits or 1.6 terabit per second connectivity. You know what the radix
of a chip is, how many fan-outs, how many signals come out of the chip.

So in the case of NVIDIA Blackwell, there's 18 NVLink ports that come out of each Blackwell chip. And I suspect that
Rubin, I don't think they've announced its ratings yet, but I'm thinking it might be higher because more output ports at
those fast rates means that you can get to more places simultaneously and have higher bandwidth chip to chip. So
these companies who are building retimer chips, they're out there trying to understand the topology of the active
cables. They're trying to understand the topology of the scale up versus scale out.

They're trying to understand where co-packaged optics is going to come in and maybe change the game again. And
then they're trying to figure out how they can use the technology that they have and extrapolate it to products that will
manage those spaces. So I think that their planning horizon is between one and two years would be my guess. They're
trying to understand what's happening two years out in the chip world.

They're trying to understand what's happening maybe 18 months out in the server world. And then they're trying to
understand what's happening maybe a year out in terms of the data center deployments of those servers. And all
those different planning horizons have to kind of come together in a time line that will generate a product road map
that will generate a profitable product portfolio for that company. It is a really hard problem. And some will get it right
better than others will.

And those are the ones that we're going to be talking about on whatever version of this call we have in 2027. I suspect
that there may be other players and some of the ones that we thought were going to be really sophisticated and
successful in this marketplace. If they didn't pivot to co-packaged optics when they should have or whatever, didn't
figure out a good 1.6 terabit solution when they should have, now those companies could be failing. I would say that
you might also need to think a little bit about standardization here.

Optics has always been kind of ¡ª optical transceivers have always been kind of standardized. There's this master
purchasing agreement that's basically a standard for what octal small form-factor pluggable optical transceiver
module should be. And there's a dozen different suppliers of that companies like Coherent, Lumentum, and nLight
and so forth. They're all making transceivers that fit into the same exact socket, and there's hundreds of those sockets
potentially on a rack full of this equipment.

And you can expect that, for example, a Coherent transceiver, you should be able to plug some fibers from that and
plug it into an nLight transceiver on the other end and expect it to work exactly as the standards would allow. There
really isn't that kind of standard right now in active electrical cables because the same company owns the retimers on
both ends of that cable, and it doesn't really matter too much what the formats inside of that cable are.

But what we might want to do is to see various kinds of second sourcing agreements for the chips that go into the
endpoints of those cables. So I wouldn't be surprised if some of the big suppliers in this space, the Ciscos of the
world, Juniper-HPE, those kind of companies, they're going to start asking for standardization around active cables.
And that standardization kind of means that you got to sit at the same table in a standards body with your arch
competitor and figure out how to build a common denominator so that your retimer transmitter will speak properly to
their retimer receiver.

That sort of thing, I think, is going to happen. I think that the large-scale consumers of these retimer chips are going to
insist upon that sort of second sourcing universal interoperability stuff. And it's not as important in active electrical
cables, but if you start looking at things like backplanes where you may have, you know, a storage engine that plugs in

11

Confidential

02/18/2026 at 18:56 PM UTC

to a rack of GPUs above it. That storage engine might not be made by the GPU company, and you might want to open
the standard of what that backplane interface looks like.

And there might be retimers connecting up and down that 3- or 4-foot long backplane. It might be 6-foot long. Under
those circumstances, you probably need retimers and you would like the retimers to be interoperable among a few
suppliers. So I would expect that, that's going to be another thing that's likely beyond the minds of Credo and Astera
is should we think about some kind of universal standardization of at least a subset of our retimer chip offers.

If they manage to do that, I think that's a big advantage to the overall ecosystem because it lets us sort of choose the
best company for each individual socket, not just a company who's compatible with all the rest of my stuff in my rack.
That's going to be a big deal if it happens.

SD: Totally makes sense. I know we're a little out of time, but I wanted to touch on one last question, if that's ok,
Chuck. Just the economic profile of AECs versus optical. Any thoughts on that, if you could share? Even high level
would be wonderful.

CB: Yes. I think that AECs cost about half the price of active optical cables. So if you only have to go 3 meters, you're
almost certainly going to use an AEC because you save half the price of an active optical cable, which would have
gone 30 meters perhaps, but at twice the price. So I think ¡ª you know, that that's kind of the differential between
electronics and optics. It turns out that it also uses somewhat less power. So active electrical cables typically between
a quarter and a half power savings compared to an equivalent speed of optical cable.

That's a big deal in this marketplace because I obviously don't want to pay for power that I could have saved some
other way. The 800-gigabit, I just looked one up on a sort of a random website. 800-gigabit cables, active electrical
cables in a 5-meter length cost just over $1,000 each. So that means, you know, by that analogy that a similar job done
by an active optical cable would be closer to $2,000 each.

You wouldn't spend the extra $1,000 unless you needed to go some distance between the 5 meters that the $1,000
cable can go and the 30¨C100 meters that the active optical cable could go. So you choose the cable technology that
fits the engineering drawings of the particular connectivity that you're trying to do. That's how it's done. And don't
spend any more money you need to. Don't spend any more power than you need to.

SD: Perfect. Chuck, that's a great place to leave it. Thank you so much, as always for all the time, all the insights. I really
appreciate it.

CB: My pleasure. Thank you for inviting me, Sheetal, and thanks to the listeners for sticking with us on this what ended
up to be a bit of a lesson on electrical engineering of high-speed signals. And a bit of a lesson on the two most
important companies in this particular space. Thanks again, and good luck on your adventures.

SD: That's great. Thanks again, Chuck. Take care.

DISCLAIMER: The statements or opinions expressed today are those of the Advisor and not Guidepoint, who disclaims all liability
for the content provided. The Advisor may not disclose material nonpublic or confidential information or any information that would
cause the Advisor to breach any duty or obligations. Guidepoint is not a registered investment advisor and the information
provided is not intended to constitute investment advice.

12

Confidential

02/18/2026 at 18:56 PM UTC

13

Confidential

02/18/2026 at 18:56 PM UTC



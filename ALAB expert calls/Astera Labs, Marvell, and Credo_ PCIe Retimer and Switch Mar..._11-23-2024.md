Astera Labs, Marvell, and Credo: PCIe Retimer and Switch Market Update

Primary:

  ALAB

  CRDO

Associated:

  MRVL

  AVGO

  NVDA

Viewpoint:

Industry Consultant

Moderator: Kirang Gohil (KG)

| Nov 22, 2024 | 31 Min Read

Bob Wheeler (BW), Principal Analyst - Wheeler's Network

  SU MMARY

Overview

The call, hosted by Kirang Gohil from Guidepoint, features Bob Wheeler, a principal analyst at Wheeler's Network. The discussion
focuses on the PCIe retimer, PCIe switch, and Active Electrical Cable (AEC) markets, with particular emphasis on companies like
Astera Labs, Marvell, and Credo. Bob Wheeler shares insights from recent industry events like the OCP Summit and
Supercomputing conference, highlighting trends in GPU clusters and networking.

Key Insights

Meta's Platform Choices: Meta disclosed that their Llama 3 inference workloads primarily run on AMD platforms, not NVIDIA,
using their Grand Teton platform which integrates PCIe switch chips.
Diverse System Designs: Not all systems replicate NVIDIA's NVL72 design; there are various configurations across companies
like Microsoft and Google.
Networking Competition: Meta and ByteDance are using Broadcom's Jericho fabric in their AI networks, indicating a shift from
traditional Tomahawk series switches and increasing competition for NVIDIA's InfiniBand.
Future of UALink: UALink's initial specifications will be based on PCIe physical layers, but future iterations may shift to an
Ethernet physical layer, potentially disadvantaging companies like Astera Labs.

Competitive Landscape

Company

Product Focus

Competitive Positioning

Astera Labs

PCIe Retimers & Switches

First-mover advantage in PCIe retimers with COSMOS software integration.
Faces growing competition from Marvell and Broadcom.

Marvell

Custom ASICs & NICs

Strong presence in custom ASICs with companies like Amazon. Potential to
leverage existing relationships for PCIe switch opportunities.

Broadcom

Switches & Networking

Utilizes Jericho fabric in AI networks. Competes with NVIDIA's InfiniBand
and Astera in PCIe switches.

Applications & Use Cases

PCIe Retimers: Used to maintain signal integrity in complex GPU systems with multiple connectors and long distances. Essential
in modular designs but less so in NVIDIA's simplified NVL72 configurations.
PCIe Switches: Facilitate logical connections between CPUs, GPUs, NICs, and storage devices. Necessary in systems using non-
NVIDIA NICs to manage bandwidth and connectivity.

1

Confidential

02/18/2026 at 18:56 PM UTC

Quantitative Insights

Metric

Value/Insight

PCIe Gen 6

First PAM4 generation at 64 Gbps, not leading-edge compared to Ethernet PAM4 at 112 Gbps.

SerDes Technology

Marvell leads in 200 Gbps per lane PAM4 DSPs, with Broadcom close behind.

Market Strategy

Astera Labs: Leverages first-mover advantage and COSMOS software for customer retention. Faces challenges as competitors
like Marvell and Broadcom enter the PCIe retimer market with integrated solutions.
Broadcom & Marvell: Utilize existing relationships and technology expertise to capture market share in PCIe switches and high-
speed interconnects.

Stage & Timing

Astera Labs: Currently strong in PCIe Gen 5 designs, but faces potential challenges with the transition to PCIe Gen 6 and
beyond, especially with the shift to Ethernet-based physical layers in UALink.

The discussion highlights the dynamic nature of the PCIe retimer and switch markets, with significant implications for companies like
Astera Labs as they navigate increasing competition and technological advancements.

KG: Good afternoon, everyone. Welcome. Kirang Gohil with Guidepoint. Thanks for joining our call on Astera Labs,
Marvell, and Credo, where we will discuss the PCIe retimer, PCIe switch, and AEC market with our advisor, Bob
Wheeler. Bob is the principal analyst at Wheeler's Network. A market analyst firm he founded after spending 22 years
at Linley Group.

He has covered semiconductors and networking for more than two decades with recent focus on DPUs, CPUs,
chiplets, and other leading-edge data center technologies. In terms of logistics for this call, and as usual, if you have
any questions for Bob, please email them to Ask@Guidepoint.com and I'll include the questions anonymously into our
discussion. With that, Bob, let me turn the call over to you. If you could please introduce yourself and give us your
background as would be relevant to our discussion today.

BW: Welcome, everybody. As Kirang said, I've been a chip analyst for about 20 years. My particular focus is in
networking and communications. At the Linley Group, we published technology analysis as opposed to quantitative
research. Really my focus is on technology more than numbers. A little different than some market research folks.

In the AI space, I've been looking very specifically at both the scale-out networks, traditional ethernet, InfiniBand as
well as scale-up like NVLink and competing interconnects in that space. In this context, PCIe is an underlying
technology that's used in essentially all platforms.

There's the basic PCIe flavor for connecting hosts and GPUs. Then there are other protocols being built on top of the
PCIe physical layer, including CXL, and now UAlink, and then other proprietary protocols being built on top of the
PCIe physical layer.

KG: Bob, thanks for that intro. Before we get into retimers and PCIe in particular, I know you were at the OCP earlier
and at Supercomputing this week. What did you take away from these two events? What was the discussion there on
the floors as it relates to GPU clusters and networking these GPU clusters? What stood out to you?

2

Confidential

02/18/2026 at 18:56 PM UTC

BW: Just to back up to last month's OCP summit, for starters a few takeaways. Meta has always been the most open
about their platforms. Meta's disclosures are very interesting, first of all, because they disclose the fact that they're
running the vast majority of their Llama 3 inference workloads on AMD platforms rather than NVIDIA platforms.

It's a version of their Grand Teton platform that they had disclosed a year ago, basically. That's relevant to the
discussion today in terms of Grand Teton integrates PCIe switch chips. Then they also disclosed Catalina, which is
their NVL rack. Unlike the NVL72, it's actually two racks with 36 GPUs per rack.

That's interesting because those two racks have to be interconnected. Meta's Catalina does not look the same from an
interconnect standpoint as NVIDIA's NVL72, which everybody looks at as being replicated everywhere. The first point
is that not all systems look like an NVL72, and I know investors would love it if there were a simple model for
everything. The reality is there are many different flavors of these platforms.

Microsoft showed a version. Google, although the tiny little photo, it showed a version of their NVL rack, and it's
clearly not the same as NVL72. I think the first thing to understand is not everything looks like an NVL72. When we talk
about attach rates on Blackwell and things like that, there is no one answer here because not everything looks like an
NVIDIA standard platform. I think those are the key points from the Meta presentations.

Then the other big piece from a networking perspective is both Meta and ByteDance talked about their use of the
Jericho fabric. Instead of using you know what, we typically see the Tomahawk series, Broadcom switches and data
center switching, Meta and ByteDance both talked about how they're actually using the Jericho product line from
Broadcom in their back-end AI networks.

In the case of Meta, they're using Arista-sourced systems. That's interesting, especially within the context of NVIDIA's
recent ethernet design win at X AI with their spectrum X platform. We're seeing, I would say, increasing competition
for InfiniBand and even from NVIDIA itself. Now NIDIA has to figure out how to reposition InfiniBand going forward.

Then from this week at Super Comm, I think one of the important pieces was to get a little more insight on what's
happening with UALink. Unfortunately, the specifications are still under wraps within the consortium.

At least we have some visibility now on where that's going. I think that's important because the initial spec will be
based on PCIe physical layer, and that's something that stereo, for example, can support quite easily. Looking
forward, it looks like UALink will be based on an ethernet physical layer in the future. That may disadvantage Astera in
the longer term. Those are some of the key takeaways.

KG: Let's start with some basics on PCIe and PCIe retimers in particular. We'll divide the discussion into two parts.
PCIe retimers and then switches. On the retimers, why are they needed? Under what system architecture are PCIe
retimers used in GPU clusters?

BW: The basics here are on PCIe is that what's called the channel, the electrical channel for PCIe Express is very
specifically designed around server motherboards because that is essentially the baseline application for each
generation of PCIe Express. The channel is essentially a chip connected to a PC board. The signal goes across traces
on a PC board, and then there's an edge connector for your PCIe Express slots where you can plug in a card.

The fundamental design of PCIe Express is to handle a certain number of inches of PCB trace plus one well-defined
connector, and then a short trace on the add-in card. That defines the loss of that channel and what the signal integrity
implications are of the channel. The physical layer for PCIe is very much designed around that.

Then as soon as you try to go either a longer distance or more often across multiple connectors, then you start to run

3

Confidential

02/18/2026 at 18:56 PM UTC

into signal integrity problems. You need either redrivers or retimers. Redrivers you can think of as just a simple analog
boost of the signal, and they can work in some circumstances, whereas retimers completely terminate the signal and
regenerate a clean signal at the retimer.

For example, in these GPU systems or a GPU server, these are typically modular designs where you have multiple PC
boards connecting across multiple connectors. You may have variable distances from a GPU on one end of a PCB to
the connectors versus one that's closer to that end of the PCB. Same thing on any intermediate cards. Catalina, there's
actually three different chassis that connect over cabling. The channels can get quite complex. I think I said Catalina, I
meant the Grand Teton Platform, actually.

The channels can get quite complex. In order to ensure basically a low bit error rate in the connection between the
GPU and the CPU, typically you put a retimer in there to essentially clean up the signal at these transitions. Usually,
adjacent to one of the connectors between the PC boards. That's fundamentally why retimers are needed is because
the PCIe was never designed to drive a very long, high-loss electrical channel.

KG: There are different ways to connect GPUs, NVIDIA does it through NVLink. Help us understand where does PCIe
come into picture? If you think about a H100 or a Blackwell system, where is PCIe and NVLink used?

BW: NVIDIA actually uses both NVLink and PCIe. NVLink is the connection for GPU to GPU connectivity. It's also used
in the Superchip configuration where you're connecting the arm CPU and the GPU. Although it's a little different flavor
of NVLink in that case. In the more traditional servers where you have a discrete CPU and discrete GPUs, NVLink is
used on the scale-up to connect the GPUs to each other.

PCIe Express is used to connect the GPUs to the host CPU. Going back to a DGX platform, for example, you have the
GPUs connecting to a PCIe Express switch, and that PCIe Express switch connects into the Intel or AMD host CPU.
Even where you have NVLink, you still need PCIe Express to get data in and out of the GPU from the host side, and
also just as the control channel from the host.

KG: Retimers are required for PCIe, but it seems like they are not for NVLink. Why is that?

BW: It fundamentally goes back to the discussion about the design target. PCIe Express has a very specific design
target in this server motherboard use case. NVIDIA has their own design targets for NVLink because they control the
complete system design. They can design their DSP however, they're driving the actual signal levels. They can add
forward error correction where needed. They can use bespoke connector systems.

In the Hopper generation of NVLink, they were able to drive things without any retimers because the GPUs were
connecting to a switch chip. There was a relatively straightforward channel between the GPU and the switch chip.
Then the switch chip would connect outside from there, usually to another NVLink switch chip.

It's a fairly simple channel. Now going to the Blackwell generation and NVLink 5, what you'll see if you look at these
systems is that now the NVLink switch chassis is using what are called flyover cables internally. Because for signal
integrity, running the signals across a PCB is no longer adequate.

They're having to use these 20 axial flyover cables for all of the connections inside of the NVLink switch. It's a higher
cost, but it has better signal integrity. Then if you look at the backbone of the NVL72 that Jensen showed at
COMPUTEX, this is quite a heavy lift design of twinaxial cabling with some very high-end Amphenol connectors on the
back of each of these compute trays. Again, with all flyover cables being used for internal connections. This is a highly
engineered system where they know everything in advance about the complete channel from end to end.

4

Confidential

02/18/2026 at 18:56 PM UTC

KG: How would PCIe retimers content change between a Hopper-based system, where eight GPUs were connected
to each other versus a Blackwell NVL 36 or 72 rack?

BW: In the worst case where you have just the ConnectX mezzanine card connecting to a GB200 superchip there
wouldn't be a retimer required in that configuration. Because VIDIA are actually, Mellanox originally actually included
a PCIe switch with just essentially one additional port in their NIC controller so that they could connect a CPU and a
GPU to the NIC.

That switch functionality is very simple. Switch functionality is already built into ConnectX. If you're not using
ConnectX, then that switch doesn't exist in the other third-party NICs, whether it's a custom hyperscalers, custom NIC
chip, or whether it's a third-party NIC chip like a Broadcom Thor 2, for example.

In that case, you would need a low port count switch to connect the CPU and the GPU to the NIC. Then in some cases,
some of the data center operators want a redundant NIC connection. Particularly for AI training, having a link go down
is a huge event that can cause a disruption in the training cycle and basically a huge loss in GPU utilization.

Some of the operators are using redundant connections in one way or another to make sure that the GPU doesn't go
down when you have a single link failure. Fundamentally, in order to connect a NIC to both the host CPU and the
GPU, you need a switch. In the case of Meta's Grand Teton platform, that's been the Broadcom PCIe switch which
connects a couple of GPUs or accelerator modules. We'll call it to the host side, as well as to the NICs.

KG: I appreciate how you introduced PCIe switch but going to just the retimer content, are there no retimers if you go
from a Hopper HGX board to the Blackwell racks now?

BW: That's correct. In the simplest case with the GB200 and the ConnectX mezzanines, my understanding is there are
no retimers.

KG: That is if it's using ConnectX. Now what about having to connect external storage systems say for example, or
other external peripherals to this cluster? Is there a need for PCIe retimers in these external storage systems, for
example?

BW: Typically in the AI clusters, the storage systems are in separate racks and are a whole other design.
Fundamentally, just about any modular system design is going to use PCIe retimer. As soon as you're building
something that's a large chassis with multiple PCBs and connectors and potentially cabling, then you're going to
require retimers. The only reason the Blackwell DGX configuration doesn't is because NVIDIA went with these simple
compute trays where it's just a one you compute tray.

Everything is essentially contained on essentially two PCBs. It's a pretty simple, pretty clean design, and the way they
scale is to add this one new chassis. A lot of designs don't look like that. A lot of designs look more like a traditional
GPU server where you have more GPUs per chassis. Again, it comes back to just about every customer has a different
configuration. There aren't going to be very many clusters that actually look exactly like NVIDIA's NVL72 rack the way
it's shown starting at GTC.

KG: It sounds like the bottom line is you think that the retimer content specifically going from the Hopper generation
to Blackwell drops significantly. Is that a fair statement?

BW: Yes, I think that's a fair statement.

KG: This is on the Blackwell. Now, again, staying on the retimers here for a minute, there are AI clusters not based on

5

Confidential

02/18/2026 at 18:56 PM UTC

NVIDIA. AMD has their GPU. Some of the hyperscalers are using their own internally developed ASICs. Google TPU,
Amazon Inferentia, Trainium and all that. How about retimer PCIe retimer content on these non-NVIDIA accelerator
clusters?

BW: Unfortunately, when it comes to Amazon, for example, they are extremely tight on information about exactly what
their systems look like. I can't really comment on Amazon. In the case of Google, their TPU servers look actually quite
similar to what the Blackwell design looks like. They're relatively simple on the base level of compute tray.

I think again, the best example you can point to where there's an obviously a lot of PCIe content is in Meta's platforms
where it's a more modular system design, where you have actually three chassis connected to form a GPU server, and
there's lots of PCIe content and that style of platform. Unfortunately, not all the hyperscalers are that open about their
system design.

KG: Is there a difference if you are using the PCIe retimers from Astera versus from Marvell or Broadcom? Ultimately,
I'm trying to understand the competitive landscape for PCIe retimers.

BW: Obviously, Astera's had a first mover advantage. I think they recognized the market opportunity. It took a while
for their larger competitors to wake up and realize there was an opportunity there. By having first mover advantage,
they were able to get designed in. They make a big deal out of their COSMOS software.

Now, I don't think it's particularly unique, but the important thing is that the customers have already adopted it for the
instrumentation of their system designs. Although competitors can provide the same features in terms of visibility and
instrumentation of the PCIe channels, and basically doing system validation and that thing.

The fact of the matter is that they've already invested somewhat in Astera's cosmos. It's just a matter of a set of APIs
that are available that have been integrated into software and firmware. It's non-trivial to, to replicate that for the
customer. I hesitate to call it lock-in. There's some momentum behind Astera based on the fact that customers have
already worked with the COSMOS software.

I think Marvell and Broadcom could very easily duplicate that functionality, but the APIs will be different. It won't be
plug-and-play from a customer standpoint. I think that's where the first-mover advantage plays to Astera. On the other
hand, Broadcom already has switch designs. I think it's likely that customers pulled them into adding PCIe retimers
because they were already buying their switch chips.

In the case of Marvell, it's well known that they're doing the Amazon Trainium ASIC, for example. They have other
designs on the custom side of the business what some of these customers. That gives them access to these designs as
well. I think the competitive landscape is going to get significantly more challenging for Astera going forward.

KG: Let's rewind back and help us understand why Astera has been so successful in PCIe retimers. What helped them
to be successful so far? How sticky are those customer relationships? How sticky are those sockets that they have won?

BW: I think the way to look at it is that traditionally the PCIe Express market moved quite slowly. It was driven by these
server upgrade cycles or processor generations. It moved quite slowly. The vendors in the space moved quite slowly.
They weren't particularly aggressive in bringing out products for each generation.

Astera came in as a startup and was much more aggressive in pushing technology. Even on Gen 4 they pushed out
products that not only had high functionality, including, these features we talked about with COSMOS on
instrumentation, but also, low power. They were moving an aggressive startup and so then moved very rapidly to Gen
5 and essentially got all of the first generation Gen 5 designs.

6

Confidential

02/18/2026 at 18:56 PM UTC

Because the only competitor was one Chinese company Montage. They had very little competition. In terms of
stickiness, I think it comes back to this COSMOS where customers have worked with it. They've included those APIs in
some of their system designs. As the incumbent, I think Astera gets first shot at the designs.

If a competitor comes in and can show that they have lower power or some other advantage that would motivate the
customer to then do the software work to adopt something different, then there's a limit to how much lock in there's
going to be for Astera.

KG: When we were talking about PCIe retimer architecture, is it possible technically, to integrate the retimer
functionality within the switch silicon, or even on the processor, for that matter?

BW: Not in the endpoint, like the GPU or the ASIC. The reason you would need a retimer is because of the long
distance or multiple connectors between the ASIC and something else, typically the host CPU. The switch chip, a PCIe
switch chip that is would incorporate the same functionality as a retimer. Looking at the use case for the Scorpio P
product in particular.

It would go essentially in the same place that a retimer would have gone in previous platforms, but then it adds
functionality in addition to retiming the signals. The switch chip is similar to a retimer except with additional
functionality.

KG: Let's talk about the PCIe switch now and start with the basics. We talked about the retimer and how it's used to
extend the length of the signal. What is a PCIe switch? Why do you need a switch?

The PCIe switch, essentially you can think of as starting off with multiple ports of the PCIe retimer functionality, which
is the physical layer of PCIe. Then it adds a logical level where you're actually logically connecting these multiple ports
on the chip, and you're able to switch packets, in this case, in PCIe express packets between these different ports.

That could be a CPU talking to a GPU. It could be a GPU talking to a NIC. It could be a CPU talking to the same NIC, or
you could also connect an NVMe SSD to the switch. If you look at again, going back to Meta Grand Teton Platform,
you'll see that there's a tray that has PCIe switch chips. That tray connects the accelerators, the host CPUs to NICs and
SSDs. That's the baseline use case for these low port count PCI express switches.

KG: You mentioned earlier about ConnectX. Maybe spend some time on ConnectX itself and its PCIe switch
capabilities. Then as you go to NICs from other companies like Broadcom, from the hyperscalers who have their own
NICs, where would the PCI switch opportunity be for Astera?

BW: Logically, you can think of ConnectX as incorporating a three-port PCIe switch. There's the PCIe slot that
connects to the host. There's the internal connection to the ethernet controller, and then there's an additional PCIe
port that can connect to storage or can connect to a CPU or a host.

By incorporating the equivalent of a three-port switch in ConnectX, the platforms can very easily connect both the
GPU and a single GPU and a single host to the NIC, the Ethernet controller functionality. That eliminates the need to
have a discrete switch chip. None of the other NIC designs out there incorporate that functionality.

Whether it's Broadcom's Thor 2 or the ASIC designs to the extent that they've been disclosed or the IPU Google
designed with Intel. If you want to connect the NIC to both the host and the GPU, you need to have the switch
functionality in between. That's where a low port count switch like the Scorpio P comes into play.

Then additional capabilities you could, for example, connect two GPUs to two NICs for failover capability so that if one

7

Confidential

02/18/2026 at 18:56 PM UTC

of your links goes down, your failover to the other connection. There's additional capabilities you could take
advantage of once you've added a switch into the architecture.

KG: From our discussion so far, it sounds like in a GPU cluster, in a GB200 NVL72 if there is a ConnectX NIC card from
NVIDIA, then the customer doesn't need an external or a discrete PCIe switch from Astera. Astera doesn't participate
in a cluster that is using ConnectX.

Help us understand what other options customers have realistically today in terms of NIC card? Have you seen
Broadcom's Thor 2 being widely used? What is the attach rate of ConnectX in GPU clusters that are not NVL72 from
NVIDIA branded, but the MGX design.

BW: Yes. I think the main thing is that there are now a lot of internal NIC designs. Amazon has been doing Nitro for
many years now. In Amazon's case, it's Nitro. Microsoft actually just announced their Azure Boost DPU. Unfortunately,
there's not much information on that yet. They just announced it this week at Ignite.

Meta at OCP actually showed their own internal NIC design that they did with Marvell. Meta has a bespoke NIC
design. Google has the IPU that they designed with Intel. More than Broadcom Thor 2, which is a basic NIC. You have
a lot of these internal designs. Then I would expect to see Broadcom Thor 2, and a lot of the Chinese data centers
actually where they don't have an internal ASIC design.

KG: Let's build on this. If you are one of these hyperscaler, the Meta, Google, Amazon, Microsoft you likely have your
own NVL72 design. Now, if you have your own NIC, chances are you would use those NICs in the GPU systems. First of
all, is that true? Then second of all, if hyperscalers are using their own NICs and not ConnectX from NVIDIA then in
that case, do they need an external PCIe switch, such as the P series from Astera? Or is the PCI capabilities integrated
in all these ASICs? What about the discrete PCI switch opportunity for all these NICs?

BW: It's definitely true that they're not using ConnectX. In some examples, I think when Amazon and NVIDIA talked
about their Hopper generation racks, it was pretty clear that Amazon was using Nitro to connect into the data center
network. Then similarly, the Google rack looks nothing like NVL72. There's what appears to be a second rack full of
networking gear. It seems pretty obvious that they're not using ConnectX and they're probably using the Intel IPU.

In the case of Microsoft, it's a little more complicated because there's multiple platforms going in parallel.
Fundamentally, if the NIC is just a straightforward NIC design, like what Meta showed that they designed with Marvell,
where it's just a one PCIe channel going to network ports with some basic multi-host capability.

Then in a traditional compute environment, you might not need a switch because you can actually break up that PCIe
connection and connect it to multiple hosts. In AI, you need all of the bandwidth for a single GPU. It's basically a 1:1
relationship between the GPU and the high-speed NIC port 400 gig today, going to 800 gig in the next generation.

In that case, if you're trying to connect multiple devices to this NIC at full speed. Then you need to introduce the
switch chip so that you're not compromising your bandwidth by splitting up the PCI Express interface. These NICs are
now pushing the limits of how much you can push across PCI Express by 16 interface, which is the limiting factor here.

KG: I'm now trying to understand where does Astera have an opportunity at each of these hyperscalers. Let's start
with the first one. Meta you said recently announced a NIC with Marvell. The question is does Astera have a PCIe
switch opportunity at Meta, or will the switch be supplied by Marvell because the whole NIC is made by Marvell?

BW: Meta today is using Broadcom actually in the Grand Teton platform. If you look at the Grand Teton inference
platform as a-.

8

Confidential

02/18/2026 at 18:56 PM UTC

KG: Is Grand Teton the GB200 NVL? That's the Catalina?

BW: No. That's Catalina. That's correct. Grand Teton is their production inference platform, which is AMD-based. It
uses MI300x. That's what they're using for their production Llama 3 workloads. They're not actually using NVIDIA for
their production workloads for Llama 3. If you look at that platform, it already uses a Broadcom PCIe switch.

It actually connects two accelerators through one switch, which although it reduces the number of switch chips can
potentially lead to contention within that switch between the two GPUs, trying to access resources that are connected
through that switch. What Astera has done, which is actually quite smart once you actually look at the use case, it really
just designed a switch on a scale where you can connect one GPU, one CPU, and a couple of other devices like the
NIC or SSD.

That switch is dedicated to a single GPU, you don't have any contention between adjacent GPUs. You can imagine a
Grand Teton design taking essentially replacing one Broadcom switch chip with two Astera switch chips because they
are lower port count devices. That would lead to actually more predictable performance would be the upside to that
design.

There are also the performance of these switches is stunning. I saw a demo at supercomputing, and the engineer on
the boat told me the latency to the switch and my jaw dropped. I'd never heard of latency at the level that they're
talking about for Scorpio in any prior PCIe switch chip. They're extremely low-latency devices.

KG: Do you believe that Astera is designed into or has the opportunity to be designed into the Grand Teton platform?

BW: I don't know if it's a design win. It's definitely an opportunity in the next generation. The current generation,
Meaning going to PCIe Gen 6. The current generation is Gen 5, and so this would be for a Gen 6 design.

KG: Grand Teton, can that architecture be used for Blackwell-based GPUs, or is it only for Hoppers?

BW: It could be used for Blackwell GPUs. What meta has done is they've had one platform for frontier model training,
or I'm not sure if frontier is the right terminology in this case. Basically, pre-training their latest generations of models,
next generation Llama. They've used NVIDIA and they've used platforms that look more like standard NVIDIA
superpods in some cases with InfiniBand, in some cases with Ethernet. Their training clusters have looked very
different from their production clusters that are used for inference as well as post-training, fine-tuning of existing
models. That kind of thing.

KG: So sounds like, Grand Teton is more inferencing, but Catalina, which is the NVL72 rack version is used more for
training. And it sounds like Astera could have an opportunity on the Grand Teton platform, but Catalina, which is the
NVL72 rack version, is all Marvell NIC, and Astra would not be there. Correct, or am I missing something?

BW: It appears to be standard GB200 compute tray. There's no switch there. They haven't actually said what NIC
they're using in that platform. It is more than likely ConnectX, but I don't think they actually disclose that detail.

KG: I understand. But then where is that Marvell NIC being used?

BW: It hasn't actually been deployed yet. They just disclosed it, and I would expect it to show up in all of their
production platforms. These would be more like the Grand Teton, and then they're standard compute platforms.

KG: Going to Amazon. Many analysts have written about Astera's opportunity, especially the switch opportunity at
Amazon. First of all, do you agree that Astera is designed into Amazon for the switch, number one? Number two,

9

Confidential

02/18/2026 at 18:56 PM UTC

what's so specific about Amazon and why they would use Astera's switch?

BW: Again the problem with Amazon is they're quite opaque. They don't disclose much about their design. It's a little
difficult to speculate on the why, but for the same reason that you would see a switch required in other NIC platforms.
Assuming that Amazon has not included switch functionality in their Nitro ASIC and they've never talked about switch
functionality in their Nitro ASIC.

Then you would be using the switch to connect the Nitro card with typically multiple hosts and multiple GPUs and
exactly what that fan out looks like it's difficult to say. Nitro in the standard compute platforms, one card supports
three servers. You do have this fan-out requirement where you're connecting one physical NIC card to multiple hosts.

If you extrapolate that to GPU-based platforms again, I think you've got this fan-out situation where you're needing to
connect multiple devices to a single Nitro ASIC. You can't do fan out with a retimer. Retimers are good for just
covering distance and connectors. When you're starting to connect multiple devices into one NIC ASIC, that's where
the switch functionality becomes required. Certainly, that fits the mold of the Nitro system design.

KG: I'm trying to understand the attach rate or the content opportunity for Astera at Amazon. Should we think about
one PCIe switch per Nitro NIC?

BW: That would be my expectation, yes. It could be more than one switch depending on the number of GPUs being
aggregated into a Nitro card. Because again, the Scorpio P is the low port count device. Then you end up needing
more devices depending on how many devices you're trying to connect.

Now this is different from the X series. The Scorpio X is a different animal, and unfortunately, Astera has said very little
in terms of the details there. I think the key with the Scorpio X is that what they're really talking about is supporting
other protocols on top of PCIe Express physical layer.

That's where you would get into things like AMD Infinity Fabric, which is actually based on the PCIe physical layer.
Then the first generation of UALink should look quite similar to Infinity Fabric. There are people building an NVLink
alternative on top of a PCIe physical layer. That's where I see the Scorpio X product fitting.

KG: Let me just make sure I understand. Scorpio X is meant for back-end GPU-to-GPU connectivity. Your point is that
this is not for NVIDIA GPUs but for AMD-based GPUs. At least that's where the opportunity primarily is from Astera's
perspective. Did I understand that right?

BW: Yes. In addition to AMD, there could be other-

KG: Hyperscaler ASICs?

BW: That are also using a proprietary accelerator to accelerator interconnect. Those are potentially. Also, if you look at
UALink now you have all of the hyperscalers basically in the consortium. You can imagine all of those bespoke ASIC
designs potentially using UALink. Now eventually the physical layer will not be PCIe, and so the near-term opportunity
is really, I would say in the AMD-based platforms.

KG: Then going back to the Amazon discussion, how many Nitro NICs or whatever they call it but let's just assume it's
Nitro. How many Nitro NICs would be there per GPU if we think of a cluster or a rack?

BW: I can't really do the math again, because Amazon hasn't disclosed enough about the rack-level architecture at
this stage. I would say in every other case we pretty much see a 1:1 ratio between 400 gig ethernet ports and GPUs. If

10

Confidential

02/18/2026 at 18:56 PM UTC

you look at it from that perspective, it's likely to be pretty close to a 1:1 ratio. There may be, in some cases, two GPUs
connected to a NIC. For the most part, it's a 1:1 ratio across all of the platforms we've seen.

KG: Let's talk about Microsoft. They introduced or showed their own NIC the Boost which from what I read, seems like
is based on the Fungible acquisition they made a year or two years ago. First of all, do you agree? Then two, what is
the opportunity for Astera at Microsoft?

BW: First of all, I do believe that it's Fungible architecture. Unfortunately, they didn't disclose enough detail to know
whether it's really a next-generation design or what exactly this the Azure Boost GPU looks like relative to the existing
fungible design. Fundamentally, fungible, had a highly programable DPU which would essentially serve in the same
role where Microsoft traditionally used FPGAs.

Microsoft has done SmartNICs for many years now, but they've been based on ConnectX controller chip with an FPGA
as the accelerator. The expectation is that this Azure Boost DPU would replace the FPGA. It's not clear if that's going
to be used in every platform or not, I would say at this stage.

As far as the opportunity, I think the opportunity would be very much the same as the opportunity in other
hyperscalers where they have an existing internal ASIC because none of those incorporate a switch. Again, if you need
to connect a host and a GPU to a DPU, then that's where you would introduce the Scorpio P type of product.

KG: What's your best guess? Would the boost DPU need an external PCI switch?

BW: In the use case where it's connecting to GPUs, yes. Because you would want to have a connection to both a GPU
and a host CPU.

KG: We have a couple of minutes left, and I want to discuss the competitive landscape for Astera from Broadcom and
Marvell from a SerDes angle. Talk to us about the importance of SerDES and having that capability in-house? How big
of a differentiator is it? Astera has said or is understood that they use SerDES from Synopsys. Broadcom, and Marvell
have very, very SerDes expertise. Is Astera at a disadvantage if they don't have their own SerDES IP?

BW: I'd say that to date it hasn't been a big disadvantage, and again, for the reason that PCIe generations move
relatively slowly and it's not leading-edge technology. PCIe Gen 6 is the first PAM4 generation. It's only 64 gigabits
per second. There's been lots of PAM4 products operating at 112 gigabits per second in the ethernet world. It's not at
all leading edge.

They've been able to use off-the-shelf SerDes IP, and that's been fine. Where I think it becomes a big problem is if
UALink is decoupled from the PCIe physical layer, and they're throwing away these issues of backwards compatibility
with prior generations. Now they are poised to move very quickly to 200 gigabits per second, per lane SerDes, which
is the rate that NVIDIA already has in NVLink 5.

That's the whole reason why UALink wants to move quickly to 200 gig per lane SerDes is to catch up essentially with
NVIDIA. In that case, if it's an ethernet-based physical layer design at 200 gig PAM4, that is a far more challenging
piece of IP. Marvell, anybody that has followed the optical space knows that Marvell has been the leader in PAM4
DSPs. They definitely have first mover advantage at 200 gig per lane on DSPs.

Broadcom is not far behind. I'd say roughly six months behind in terms of the optical DSPs. They will both have proven
200 gig per lane. Technology, Marvell I think has already demoed 200 gig in three nanometer. They'll be pushing the
leading edge on process technology. This is where I think it becomes much more challenging for Astera is moving
quickly to these advanced speeds for UALink.

11

Confidential

02/18/2026 at 18:56 PM UTC

KG: Bob, I think we could spend another couple of hours on this topic, but we'll wrap it up. We are almost out of time.
Thank you so much for taking the time and sharing your insights with us. This was really helpful.

DISCLAIMER: The statements or opinions expressed today are those of the Advisor and not Guidepoint, who disclaims all liability
for the content provided. The Advisor may not disclose material nonpublic or confidential information or any information that would
cause the Advisor to breach any duty or obligations. Guidepoint is not a registered investment advisor and the information
provided is not intended to constitute investment advice.

12

Confidential

02/18/2026 at 18:56 PM UTC



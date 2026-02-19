COMMUNITY

65d0d6538a8911da05d11de9b49cc840996c80c0

Data Centre & GPU Industry 每 Nvidia, Astera,
AMD & Broadcom 每 Senior Architect at
Microsoft Corp

Consultant | 31 March 2025

Specialist Background

> Extensive experience in the data centre and GPU (graphics processing unit) industry, focusing on

interconnects such as Ethernet, UALink, PCIe (peripheral component interconnect express) and
CXL (compute express link)

> Well-placed to discuss FPGAs' (field-programmable gate arrays') use case in data centres and
how it compares to data centre products such as server CPUs (central processing units), GPUs
and ASICs (application-specific integrated circuits)

> Comprehensive understanding of TCO's (total cost of ownership's) broader maximisation, bigger

systems that Nvidia is trying to push on hyperscalers and AMD's (Advanced Micro Devices') ZT
Systems acquisition

Contents

Relating to TCO's [total cost of ownership's] broader maximisation, we're heading into a rack
structures' shift where in the past, it's been the two CPU [central processing unit]-, eight GPU
[graphics processing unit]-card type deployments. Nvidia is trying to get some scale-up
efficiency from these system scale racks with 72 or 144 GPUs. A lot of integration challenges
and installation issues come with that. Thinking about the industry working fast and furious
towards scaling up clusters and scaling up these GB200- and GB300-type system scale
configurations, is there a world in which perhaps we need to slow down, stick with these eight
card configurations, you can then tap into some system efficiencies more expediently, and
some of the system scale stuff is going to get pushed out? How have you been thinking about
these bigger systems that Nvidia is trying to push on hyperscalers? Are they as good as what
Jensen would want us to think?

6

Data Centre & GPU Industry 每 Nvidia, Astera, AMD & Broadcom 每 Senior Architect at Microsoft Corp 每 31
March 2025

AMD [Advanced Micro Devices] has acquired ZT Systems, and Nvidia is trying to pitch to both
industry players and investors that they're not just a semiconductor chip company, but do a lot
of the systems and software work as well. You can take a full reference design, which includes
thousands of components from Nvidia, would their argument be that it works the best, and that
your performance on an absolute measure would be most optimal? Presumably, there are some
cost considerations in going with just a pure reference design. Certain workloads that are a bit
more cost sensitive would end up going with something a bit customised and lower cost at the
end of the day.

How would you be thinking about which way things will shift over the next two or three years,
as Nvidia and presumably AMD, over time, with the new ZT Systems acquisition, start trying to
deliver these big system solutions? Is it going to be taking 50/50 standard vs custom type
solutions? Is it going to be 75/25? On workloads' proliferation and diversity that these
accelerators are going to be playing into, is there a good way for me to frame how much
customisation is still going to be required over the medium term?

Would you say that the internal vs external workloads' split for any given hyperscaler is more
static and stable and that the volatility of trying to make a prediction is around trying to figure
out how much of that internal workload can go to custom silicon, and the extent to which
maybe some external workloads could go as well? But by and large, a 70/30 external vs internal
workload split for a typical hyperscaler is reasonably static? Does that shift pretty fluidly as
well?

Outside of the accelerator, another thing that comes up is Amazon using their neuron link, NIC
[network interface card] as an example vs going with ConnectX-7 or eight, in terms of what
Nvidia provides. How broad reaching do you think some of the custom capability ends up being?
As I think about the CX7 or eight, NIC or NVLink for back-end interconnect or scale up or out,
are there certain aspects that Nvidia is always going to have a dominant grasp on? Do you
reckon I should be thinking that the hyperscalers are looking across different components,
whether it be the NICs, interconnect, GPU or accelerator itself, and that there might be a need
for first in customisation for internal workloads across the board?

Relating to scale out, my understanding is that Ethernet lacks memory-semantic capabilities,
but for Ultra Ethernet, it would seem that Broadcom is maybe trying to look at it a little bit more
closely. Is that one of the areas that you're talking about where Ethernet might have some
shortcomings as it relates to being a perfect NVLink replacement? But if they were able to
incorporate better memory semantics on top of the network semantics at present, it could drive
the value proposition up for something such as UEC [ultra ethernet consortium], not just for
top rack, but also for back-end scale out opportunities?

On the UALink side of things, you brought the point where they're all going to be operating on a
similar SerDes, which I think you're referring to they're all going to be 224 gig, which is more
Ethernet like than PCIe [peripheral component interconnect express]. I wonder, for UALink,
Broadcom was on the board, then they got off of it. It seems Broadcom just in general is focused
more on full sheets and that either way in. That leaves Astera Labs as maybe the UALink switch
chip vendor likelihood. I guess my question for you would be how big of a jump would that be
going from this low-end 64-lane chip, not a lot of memory semantics, probably lower SerDes
into something that's going to be UALink compatible, so to speak? Do you have a lot of
confidence behind Astera Labs from a development standpoint to be able to make that happen?

Private and confidential

7

7

8

8

9

2

Data Centre & GPU Industry 每 Nvidia, Astera, AMD & Broadcom 每 Senior Architect at Microsoft Corp 每 31
March 2025

Would I be right in thinking that UALink's deployment, assuming that test chips actually work,
would be something that's not until next or the year after?

You mentioned around NUMA [non-uniform memory access] hop, and it seems like we never
really got to more latency than the NUMA hop standard. The Granite Rapids and Turin refresh
cycle just got pushed out a little bit with the whole AI thing, and those are ones that are going to
be 2.0 compatible. Maybe the goalpost just got pushed a little bit, and we're still going to be
seeing some nice CXL [compute Eexpress link]-related adoption for some general purpose
servers. We would have thought that refresh cycle would have been '25, and it's more going to
or would have been in '24, but it's now going to be '25 and '26.

The capacity that expansion controllers are providing is a drop in the water. You get as much as
1Tbit or 2Tbits of extra data, which is not that big of a needle mover. How should I be thinking
about CXL adoption moving forward? Had I asked this about three years ago, the aspirations
would have been a lot higher and now they've come back to reality, so to speak. How are you
thinking about CXL's role in data centres moving forward? What are the big things that you're
excited about now that the standards have matured a little bit?

Relating to controller side of things where memory expansion is going to be the use case until
we get 3.0, and to isolate to expansion, Astera has got the CXL controller. Marvell acquired
Tanzanite, but I'm pretty sure that entire design team has been assembled to a large extent.
Microchip did a little bit there. Rambus at one point thought about it, but now it seems maybe
less so. Can you set the level? It seems like Astera Labs is the most focused on it, and has silicon
that is sampling with investors. I'd expect them to see a lot of the early adoption for their
controller chips. I'm aware that Samsung, Micron, Hynix, etc do it, but they might be white-
labelling what Astera is using. Is there anyone I'm missing in the space that might also be
competing against Astera for the early expansion opportunity?

On Marvell, they have the Structera product, which is a little bit more compute-intensive than
what that Leo [sic] product is. I'd imagine that's more expensive. From your perspective, is
there a need to have those compute levels for what the CXL is trying to solve, from a memory
expansion standpoint?

Software is part of the ecosystem, for CXL still needs to be built out around host biasing and
similar stuff. How has that come along? I know there are a handful of start-ups such as
MemVerge and Liqid who are trying to do something in between the BIOS [basic input/output
system] and API [application programming interface] layer to make the management of the ins
and outs of that off-chip memory work a little bit better and cut down latency. I heard that host
biasing was one of the areas that presented challenges for CXL performing on a system level.
Has that improved much?

Relating to tracking CXL, it would seem that a lot of these R&D sampling will occur as
hyperscalers start acquiring Granite Rapids and turn CPUs that are compatible with the
standard. Then, tere will be some testing and validation, and if things go well, CXL might see a
healthier ramp as we look into next year, that would be the way to pace it a little bit, right?

Private and confidential

10

10

11

11

11

11

3

Data Centre & GPU Industry 每 Nvidia, Astera, AMD & Broadcom 每 Senior Architect at Microsoft Corp 每 31
March 2025

You mentioned that the PCIe standard process is moving a little bit more quickly than in the
past. I've been trying to explore and I'm sure you're well aware that with Blackwell GPUs for
Nvidia, they're eliminating the retimer through either having NV switch on the compute node
or the CX7 or eight NICs on the base board. There's just not going to be a need for those
reference designs to have retimers in them. For a lot of these general purpose servers that are
predominantly on Gen 4-5, that there's not really a need for retimers as of yet, but thinking
about it as we move into 2026-27, there's going to be a pretty big move over to Gen 6 for non-
AI servers, whether it be the NICs, storage drives or CPUs. At that point, given that we're
looking at 64-gig data rates, there's going to be a broader need for retimers in general purpose
servers which hasn't existed ever in the past. Is that a reasonable way to think about the way
that the general server topology might evolve? Is it overly ambitious either in terms of large
attach rate or speed at which general purpose moves to Gen 6?

Programmability around each specific project that the retimer is being configured for is non-
trivial. Nvidia is saying that there are not going to be any more retimers. Why are Marvell,
Broadcom and Credo moving into this market that might be going away, which then introduced
the whole topic around general purpose needs for it once we get to Gen 6? It seems like Astera
Labs has the dominant position in retimers simply because it was the only one in town for the
GPU cycle that occurred for Hopper. But as we have other companies come into the mix, I don't
see any reason to believe that they keep dominant share. I'd imagine that Marvell and
Broadcom are as good, if not better at enabling the programmability around the feature sets
that are diverse by workload. Would I be right in thinking that this market is going to get
divvied up pretty quickly across a handful of 4-6 players as it moves towards general purpose
servers in a couple of years?

Did you hear Arm's Infrastructure Division head say that they're going to have 50% data centre
CPU market share by the end of this year? Do you probably some differing views, given the
points you made around Intel making good internal changes to shore up some of their share?
To me, Arm saying that would suggest that Nvidia's Grace Blackwell combination is going to
take off. I just feel like 50% is a really big number for them to try in such a short timeframe.

On the head node and PCIe switches that do some of the scale out interconnect, Broadcom has
had pretty much a lion's share of this market because they got it through their PLX Technology
acquisition. I think Microchip's Microsemi was the only other one that was really offering this,
and their product is not that strong. This is an area where Astera is trying to move into. The
feedback is it's only 64 lanes. They did that so they could get out to sample with customers
quickly, but the memory semantics are pretty poor as a result. Whereas for Broadcom, 144
lanes, pretty solid memory semantics, which means that Broadcom is going to always win when
it comes to external workloads. You just can't use a 64-lane switch from Astera that has bad
memory semantics because it will be really poor performance when you have multiple
customers running on the server rack. Should I expect Astera to do anything big for this head-
node type PCIe switch anytime soon? Would you say that Broadcom has still got the market on
lock?

12

12

13

13

Private and confidential

4

Data Centre & GPU Industry 每 Nvidia, Astera, AMD & Broadcom 每 Senior Architect at Microsoft Corp 每 31
March 2025

The big debate going into Nvidia GTC was that everyone had heightened expectations around
optics in the data centre. Most of that got diffused where Jensen talked about the co-packaged
optic switch, but that it's mostly going to be for the back end and not for the intra-rack
interconnect and that he feels very strongly about keeping copper for intra-rack stuff. Do you
think that copper has a lot more staying power than some of the outsiders, who aren't fully
entrenched with some of the systems work, and that copper is going to continue to be the most
cost-efficient and good enough solution for stuff within the data centre that don't really
require interconnects' long reach?

Besides Nvidia, which companies do you think are exposed to the right product cycles, are
doing the right things around solving challenges that exist for the hyperscalers, and the ones
that meet the needs that have come with AI over the last couple of years? Are there companies
that you think are both visionary and strong executors that I should continue to watch because
they know what they're doing?

Everyone were overly worried about spending slowing down and that maybe there's an air gap
between training, peaking and inference reaching a scale that can fill in the pockets.
Presumably, you see this as overblown, but is there anything that you think distils it well in
terms of why people shouldn't be so worried that AI spend is already saturated?

14

14

15

Private and confidential

5

Data Centre & GPU Industry 每 Nvidia, Astera, AMD & Broadcom 每 Senior Architect at Microsoft Corp 每 31
March 2025

Data Centre & GPU Industry 每 Nvidia, Astera,
AMD & Broadcom 每 Senior Architect at
Microsoft Corp

Transcription begins

Analyst:
Can you give an overview of your background?

Specialist:
I'm part of an advanced technology group and my job charter is look at the architecture in our data
centre and try to figure out the optimal architecture, both for the GPU-centric as well as CPU-centric
platforms. My domain expertise comes primarily from systems, memory, storage. We are a broader
team where we also look at a lot of interconnects, whether it's Ethernet, UALink, PCIe, CXL. We look into
how we can build these systems in our data centres, which can give us the best TCO. TCO is reduce the
cost, but maximum whatever the return on those COGS. AI and non-AI, both are pretty much hot right
now.

Analyst:
Relating to TCO's [total cost of ownership's] broader maximisation, we're heading into a rack
structures' shift where in the past, it's been the two CPU [central processing unit]-, eight GPU
[graphics processing unit]-card type deployments. Nvidia is trying to get some scale-up efficiency
from these system scale racks with 72 or 144 GPUs. A lot of integration challenges and installation
issues come with that. Thinking about the industry working fast and furious towards scaling up
clusters and scaling up these GB200- and GB300-type system scale configurations, is there a world in
which perhaps we need to slow down, stick with these eight card configurations, you can then tap into
some system efficiencies more expediently, and some of the system scale stuff is going to get pushed
out? How have you been thinking about these bigger systems that Nvidia is trying to push on
hyperscalers? Are they as good as what Jensen would want us to think?

Specialist:
The rate of innovation coming out of Nvidia is incredible. They have increased the pace. You all know
that. Deployment of these bigger systems is not just how much tokens you can get, that's the metric he
uses, but the power, the reliability of these systems. Then there is a lot of non-GPU part of the data
centre where you have to get these things out of internet in terms of whether it's storage traffic or some
remote memory traffic. Then power. Power is a big problem. What I mean by power is even if, let's say,
you are able to procure all the power, how do you deliver it at the rack level? These humongous Nvidia
systems, they need a lot of rack-level power delivery innovation. Those challenges are there. Of course,
optics is one area where they're going, where you can scale out. These things are coming at a very rapid
pace.

Of course, there is Nvidia roadmap. It's not that everything is going to switch to the latest and greatest
immediately. At the same time, what I'm seeing is we are finding ways to monetise even the older
generation GPUs. For example, some of the traditional workloads that were done on typically CPU-
centric platforms, they can see better returns. Again, the software needs to be readied for all those

Private and confidential

6

Data Centre & GPU Industry 每 Nvidia, Astera, AMD & Broadcom 每 Senior Architect at Microsoft Corp 每 31
March 2025

existing software applications. I think the rate of changes on every front, whether it's models, whether
it's data centre, power delivery, and then the GPU racks, it's my personal opinion, I would say. It's all
over in the media. I don't think there is any slowdown. You just need to make sure that you have to pace
these innovations properly.

Analyst:
AMD [Advanced Micro Devices] has acquired ZT Systems, and Nvidia is trying to pitch to both industry
players and investors that they're not just a semiconductor chip company, but do a lot of the systems
and software work as well. You can take a full reference design, which includes thousands of
components from Nvidia, would their argument be that it works the best, and that your performance
on an absolute measure would be most optimal? Presumably, there are some cost considerations in
going with just a pure reference design. Certain workloads that are a bit more cost sensitive would end
up going with something a bit customised and lower cost at the end of the day.

How would you be thinking about which way things will shift over the next two or three years, as
Nvidia and presumably AMD, over time, with the new ZT Systems acquisition, start trying to deliver
these big system solutions? Is it going to be taking 50/50 standard vs custom type solutions? Is it
going to be 75/25? On workloads' proliferation and diversity that these accelerators are going to be
playing into, is there a good way for me to frame how much customisation is still going to be required
over the medium term?

Specialist:
I think overall, there are two types of use cases. One is the traditional cloud-centric where customers
come on the cloud, they want to use APIs, and then they want to quickly go＃ Time to market is very
important. Nvidia's moat with the CUDA is extremely important in that context. Many of these type of
customers will stay there. There is other moat, other similar lane (ph), which is internal workloads. It's
all in the public domain, whether it's Microsoft or other big hyperscalers. The focus is on getting the
internal models, internal workloads on internal, customised systems in silicon. To put an exact number,
whether it's 50/50, 70/30, I think it's very difficult. First of all, things are changing so rapidly. At the
same time, even Jensen made a comment, just getting a design does not mean you have a design win. For
some of the custom ASICs that Broadcom is going ahead with, yes, they have design, but it does not
mean they will be deployed.

Again AMD has no alternative. You cannot just sell GPUs. You have to build humongous system on your
own. There is a huge integration, and it has to work seamlessly. You cannot just expect them, take our
GPU and you figure out rest of the things. That doesn't work anymore. They are on the right path with
the ZT acquisition, but yes, I think Nvidia has much bigger lead. Nvidia's NVLink is very important to
them, and they have a huge lead on NVLink. AMD is trying to come up with UALink, but they're behind.
They have challenges on multiple fronts. Systems, there is no CUDA. They are putting their energy in all
the right areas, but yes, it will take some time. Then custom ASICs have a play. Nvidia, things are
expensive, everybody knows that. Custom ASICs have their own role, and they can be customised for a
specific model or specific internal use case. That's the trend. Again, putting a specific number is very
risky at this point. Things can change.

Analyst:
Would you say that the internal vs external workloads' split for any given hyperscaler is more static
and stable and that the volatility of trying to make a prediction is around trying to figure out how much
of that internal workload can go to custom silicon, and the extent to which maybe some external
workloads could go as well? But by and large, a 70/30 external vs internal workload split for a typical
hyperscaler is reasonably static? Does that shift pretty fluidly as well?

Private and confidential

7

Data Centre & GPU Industry 每 Nvidia, Astera, AMD & Broadcom 每 Senior Architect at Microsoft Corp 每 31
March 2025

Specialist:
I would say, initially to start with, the focus is on internal because that is something hyperscalers
control. They have control over models, they have control over use cases. They have control over the
design of these internal systems. That's the easier use case vs external, you are competing with Nvidia.
They have changed their rate of innovation from every, what, two years to now one year. That challenge
is always there. CUDA-X, they are increasing the breadth of CUDA. Having a mix always gives the
hyperscalers flexibility. Having both options in their hand, I think it's a good strategic play. If they can
realise that there's one external workload, but that is quickly growing in huge volume, in order to get the
cost down, they can think about getting that external workload also on internal. It all depends on how
much infra is getting used for that external workload.

Analyst:
Outside of the accelerator, another thing that comes up is Amazon using their neuron link, NIC
[network interface card] as an example vs going with ConnectX-7 or eight, in terms of what Nvidia
provides. How broad reaching do you think some of the custom capability ends up being? As I think
about the CX7 or eight, NIC or NVLink for back-end interconnect or scale up or out, are there certain
aspects that Nvidia is always going to have a dominant grasp on? Do you reckon I should be thinking
that the hyperscalers are looking across different components, whether it be the NICs, interconnect,
GPU or accelerator itself, and that there might be a need for first in customisation for internal
workloads across the board?

Specialist:
As I was saying earlier, NVLink for scale up, they have a huge advantage there. Industry is also making
the right calls. For example, UALink, Ethernet because if you really look at NVLink at the lowest level,
they use the same SerDes technology that some of these other options such as Ethernet or UALink plan
to use. The advantage that they have will not be there forever. The good thing about these standard-
based silicon is there is ecosystem, there will be multiple players. As a hyperscaler, the preference will
always be going for an industry standard where we don't get locked into a specific vendor. I think that
has played out very well right from X86 in the last 15 years of cloud. I think that advantage will always be
in favour of going with industry standard. Ethernet has a huge potential there. There are some efforts of
figuring out what is lacking in Ethernet and trying to rectify those and get the same performance with
respect to NVLink. Again, these things will take time, but the efforts are headed in the right direction.

Analyst:
Relating to scale out, my understanding is that Ethernet lacks memory-semantic capabilities, but for
Ultra Ethernet, it would seem that Broadcom is maybe trying to look at it a little bit more closely. Is
that one of the areas that you're talking about where Ethernet might have some shortcomings as it
relates to being a perfect NVLink replacement? But if they were able to incorporate better memory
semantics on top of the network semantics at present, it could drive the value proposition up for
something such as UEC [ultra ethernet consortium], not just for top rack, but also for back-end scale
out opportunities?

Specialist:
I think whether it's through UEC or some other Ethernet. I think they're trying to address those. I think
Ethernet lacks the memory semantics and they're trying to address those. It's possible. I don't see any
big technical roadblock. It's just that Ethernet was never used in the memory semantic space. Yes, it's
possible.

Analyst:
I'd be thinking about NVLink replacements with UALink being one and Ethernet being the other, it
seems you're leaning towards Ethernet as the more likely candidate. Is that your current thinking? Why

Private and confidential

8

Data Centre & GPU Industry 每 Nvidia, Astera, AMD & Broadcom 每 Senior Architect at Microsoft Corp 每 31
March 2025

do you think Ethernet would be better placed than what UALink is trying to do from an approach
standpoint?

Specialist:
I think both will have a play because if you see who is driving UALink, the number two GPU vendor is
driving UALink at this point. There can be another GPU vendor and multiple of those going beyond
UALink. The hyperscale looks like Ethernet. There is a camp for that. There's a camp for UALink. Both
will coexist. The market overall will be segmented into three buckets, as we have seen. There will be
Nvidia, there will be non-Nvidia GPU market, and there will be custom ASICs. The ecosystem is going to
develop for all three. Now the question is which one will be number two and which one will be number
three, because number one is assumed to be Nvidia for some more time. I think that needs to be seen. I
think just this looking at AMD, I think the world was very optimistic about them last year. Now just
trying to put, what, 60,000 components in (inaudible) in one rack, building those systems, working on
their ROCm, which is a CUDA-equivalent AMDs, the whole thing takes time. Even if you buy companies,
it takes time.

Nvidia has huge time advantage here. They started many years ago. They will command. Of course, their
margins are huge and having these alternatives will help the cloud because this is the game that started.
If you look at X86 CPUs, it used to be predominantly Intel, then came AMD, they started eating Intel's
market share slowly. The mistake in it was they never had CUDA. They're purely a silicon provider. The
good thing here at Nvidia is they own CUDA. It will not be easy, but nothing is impossible. It just needs
more time. There will be a mix of all three in the data centre, custom ASIC, non-Nvidia, and Nvidia.

Analyst:
On the UALink side of things, you brought the point where they're all going to be operating on a
similar SerDes, which I think you're referring to they're all going to be 224 gig, which is more Ethernet
like than PCIe [peripheral component interconnect express]. I wonder, for UALink, Broadcom was on
the board, then they got off of it. It seems Broadcom just in general is focused more on full sheets and
that either way in. That leaves Astera Labs as maybe the UALink switch chip vendor likelihood. I guess
my question for you would be how big of a jump would that be going from this low-end 64-lane chip,
not a lot of memory semantics, probably lower SerDes into something that's going to be UALink
compatible, so to speak? Do you have a lot of confidence behind Astera Labs from a development
standpoint to be able to make that happen?

Specialist:
I have been following the CXL, which is a memory semantic fabric. Of course, the SerDes speeds are
lower, but if you look at overall the ecosystem and how these chips are built, it always starts with IP
vendors such as Synopsys and Cadence. They come up with IP. Of course, Synopsys and Cadence are
working on the IP at this point. They will build their test chips. Once the test chips are working, those IPs
will be sold to the silicon providers, whether it's Astera or some other company. Building a switch at that
higher data rate, once you have the right IP and the right process from TSMC, I don't think that's
difficult because world has seen very high SerDes switches in the Ethernet space already. The difference
here is that these are very low latency memory semantic. If you take currently, there is a CXL switch in
the market. There is a company who built it.

Xconn. One can take similar architecture, replace those IPs from PCIe Gen 5, Gen 6 to the Ethernet
SerDes. Of course, you need to have the internal architecture to be modified because the pipes are going
to be much fatter, and they have to be shallow. Again, the latency requirements on UALink is not as
stringent as CXL. CXL, the latency was one NUMA hop. UALink latencies are much liberal compared to
that. Technically, for all the AI traffic, these are all DMAs internally, the GPUs. There are two types of
architectures, but these are larger transfers and there are DMAs. It's tolerable to live within that latency

Private and confidential

9

Data Centre & GPU Industry 每 Nvidia, Astera, AMD & Broadcom 每 Senior Architect at Microsoft Corp 每 31
March 2025

requirement of UALink. I don't think building UALink chips is a much difficult task. I think there won't
be many players in that space.

Analyst:
That specs in the hands of the members, and probably gets more public in the next couple of months.

Would I be right in thinking that UALink's deployment, assuming that test chips actually work, would
be something that's not until next or the year after?

Specialist:
Yes. Of course, even the GPUs need to have UALink. The whole ecosystem has to work together. If you
look at (talking over each other). The ecosystem, just having one component, it does not help. You need
to have GPUs also with UALink. These things have to interoperate with each other reliably, and all this
testing and validation takes time. Hopefully, AMD can push that fast.

Analyst:
You mentioned around NUMA [non-uniform memory access] hop, and it seems like we never really
got to more latency than the NUMA hop standard. The Granite Rapids and Turin refresh cycle just got
pushed out a little bit with the whole AI thing, and those are ones that are going to be 2.0 compatible.
Maybe the goalpost just got pushed a little bit, and we're still going to be seeing some nice CXL
[compute Eexpress link]-related adoption for some general purpose servers. We would have thought
that refresh cycle would have been '25, and it's more going to or would have been in '24, but it's now
going to be '25 and '26.

The capacity that expansion controllers are providing is a drop in the water. You get as much as 1Tbit
or 2Tbits of extra data, which is not that big of a needle mover. How should I be thinking about CXL
adoption moving forward? Had I asked this about three years ago, the aspirations would have been a
lot higher and now they've come back to reality, so to speak. How are you thinking about CXL's role in
data centres moving forward? What are the big things that you're excited about now that the standards
have matured a little bit?

Specialist:
I think your commentary is 100% correct. Things got pushed out because of all these AI spent. I firmly
believe that CXL has a role to play. If you look at AI, it's not just GPUs. There is vector database. There is a
lot of querying, there is a lot of caching. CXL helps you on the memory hierarchy. To be honest, the spec
was started in a way where they expected NUMA latency, but for certain applications, it's okay. Even if
you're not reaching NUMA, that's okay. What really matters is what performance drop you see at the
application level. There are a lot of benefits even if we don't hit the NUMA latency with CXL. I think in a
nutshell, what I would say is CXL will be there. It just got pushed out. There are a lot of interesting things
that can be done even with CXL.

PCIe is moving to Gen 6, Gen 7 will happen. The PCIe used to be a very slow innovation because it was
driven by CPUs, but the GPUs can move that much faster. GPUs can go to PCIe Gen 7 before the CPUs, and
there can be some solutions where one can take advantage of. PCIe is another interconnect coming out
of a GPU. You have your scale up, scale out, and PCIe is the third one. A lot of interesting things can be
done over there. Memory is still always more than 40% of the cost. As the memory prices are going up
through HBM, DRAM is important at the end of the day. CXL helps in that space. There is a lot of
innovation happening at the Flash and DRAM, that layer. Can there be another fast storage? CXL can be
viewed as a fast storage. I think there are a lot of cool things that can be done with CXL.

Analyst:

Private and confidential

10

Data Centre & GPU Industry 每 Nvidia, Astera, AMD & Broadcom 每 Senior Architect at Microsoft Corp 每 31
March 2025

Relating to controller side of things where memory expansion is going to be the use case until we get
3.0, and to isolate to expansion, Astera has got the CXL controller. Marvell acquired Tanzanite, but I'm
pretty sure that entire design team has been assembled to a large extent. Microchip did a little bit
there. Rambus at one point thought about it, but now it seems maybe less so. Can you set the level? It
seems like Astera Labs is the most focused on it, and has silicon that is sampling with investors. I'd
expect them to see a lot of the early adoption for their controller chips. I'm aware that Samsung,
Micron, Hynix, etc do it, but they might be white-labelling what Astera is using. Is there anyone I'm
missing in the space that might also be competing against Astera for the early expansion opportunity?

Specialist:
I think there are a couple of start-ups mostly coming out of Asia and one or two even in the US side. They
are late into this party. I don't think you have seen their public announcement yet. Yes, I think you're
right, Astera is a leader right now, but there are others who have the designs that are taped out. They are
in their labs and getting tested. There will be a few more players, which is a good thing. I'm not saying
it's a bad thing because we need more. Some of these are really innovative solutions. Those who
abandoned, they are thinking about getting in again with the CXL 3.0, but to be seen.

Analyst:
On Marvell, they have the Structera product, which is a little bit more compute-intensive than what
that Leo [sic] product is. I'd imagine that's more expensive. From your perspective, is there a need to
have those compute levels for what the CXL is trying to solve, from a memory expansion standpoint?

Specialist:
See, one particular aspect of the Marvell product that I like is about the compression technology. Again,
this is me talking as a pathfinding person. I think it increases the capacity of these DIMM significantly if
you hit the right compression ratios. The other aspect is all about the near memory compute that you
mentioned. I think near memory compute has some challenges. It's mostly around software. If you just
think even AMD, thousands of engineers on ROCm, hyperscalers building their own non-CUDA like
solution, it needs huge investments and justifiable reasons. Near memory compute, I think, is a little bit
of challenging for huge adoption at this point.

Analyst:
Software is part of the ecosystem, for CXL still needs to be built out around host biasing and similar
stuff. How has that come along? I know there are a handful of start-ups such as MemVerge and Liqid
who are trying to do something in between the BIOS [basic input/output system] and API [application
programming interface] layer to make the management of the ins and outs of that off-chip memory
work a little bit better and cut down latency. I heard that host biasing was one of the areas that
presented challenges for CXL performing on a system level. Has that improved much?

Specialist:
Yes, yes. That is getting addressed. Thankfully, a lot of things have been pushed into Linux. If you look at
Linux ecosystem, there is a lot of good stuff already and all other operating systems will get there. Yes,
it's getting addressed.

Analyst:
Relating to tracking CXL, it would seem that a lot of these R&D sampling will occur as hyperscalers
start acquiring Granite Rapids and turn CPUs that are compatible with the standard. Then, tere will be
some testing and validation, and if things go well, CXL might see a healthier ramp as we look into next
year, that would be the way to pace it a little bit, right?

Specialist:

Private and confidential

11

Data Centre & GPU Industry 每 Nvidia, Astera, AMD & Broadcom 每 Senior Architect at Microsoft Corp 每 31
March 2025

Yes, you can say that CXL will see some good adoption next year.

Analyst:
You mentioned that the PCIe standard process is moving a little bit more quickly than in the past. I've
been trying to explore and I'm sure you're well aware that with Blackwell GPUs for Nvidia, they're
eliminating the retimer through either having NV switch on the compute node or the CX7 or eight NICs
on the base board. There's just not going to be a need for those reference designs to have retimers in
them. For a lot of these general purpose servers that are predominantly on Gen 4-5, that there's not
really a need for retimers as of yet, but thinking about it as we move into 2026-27, there's going to be a
pretty big move over to Gen 6 for non-AI servers, whether it be the NICs, storage drives or CPUs. At
that point, given that we're looking at 64-gig data rates, there's going to be a broader need for
retimers in general purpose servers which hasn't existed ever in the past. Is that a reasonable way to
think about the way that the general server topology might evolve? Is it overly ambitious either in
terms of large attach rate or speed at which general purpose moves to Gen 6?

Specialist:
Let's talk about the non-GPU servers. I think even at PCIe Gen 5 right now, there are challenges around
signal integrity. The moment you try to do something at that data rate where the device is external to the
server, just looking at the distance from the CPU on the server all the way to the back side of the server
where you either connect something, a device or you take the cable out, even at Gen 5, there are
challenges. The adoption is not that much huge on Gen 5. That's why you are not seeing that issue being
amplified a lot. At Gen 6, of course, it will become even bigger issue. At the end of the day, lower latency
is very, very important, at least for memory semantic. Maybe for storage, it's okay. People will stay with
higher latency retimers, and these are low cost. The low-latency retimers, I think people have been
saying we have those, but they need to be fine-tuned. You have to work very closely with the CPU
platform vendor. There are a lot of knobs that need to be programmed on these retimers. It's not pure
just plug-and-play kind of thing. I think that is one space where low latency retimers, which are highly
reliable, is pretty much needed right now. That will become more dominant when you go to Gen 6-7.

Analyst:
Programmability around each specific project that the retimer is being configured for is non-trivial.
Nvidia is saying that there are not going to be any more retimers. Why are Marvell, Broadcom and
Credo moving into this market that might be going away, which then introduced the whole topic
around general purpose needs for it once we get to Gen 6? It seems like Astera Labs has the dominant
position in retimers simply because it was the only one in town for the GPU cycle that occurred for
Hopper. But as we have other companies come into the mix, I don't see any reason to believe that they
keep dominant share. I'd imagine that Marvell and Broadcom are as good, if not better at enabling the
programmability around the feature sets that are diverse by workload. Would I be right in thinking
that this market is going to get divvied up pretty quickly across a handful of 4-6 players as it moves
towards general purpose servers in a couple of years?

Specialist:
Yes. I think that's possible. The issue around retimers is there was only one or two vendors focused on
the low latency aspect of it. Others had neglected that. As now that has become a main pain point, other
players are moving in. It is not something like optics, which is very technically challenging. These
retimers, it's all about designing and then working with a CPU platform, and then customise those
parameters to make it work. Once you have a good partnership, I think others can also get into this
space.

Analyst:
My understanding is that Astera had a really good relationship with Intel, but maybe less so with AMD.

Private and confidential

12

Data Centre & GPU Industry 每 Nvidia, Astera, AMD & Broadcom 每 Senior Architect at Microsoft Corp 每 31
March 2025

I'd be worried a little bit to the extent that Intel is probably continuing to lose server CPU share, and it's
not helpful that Astera is maybe not as well entrenched with someone such as AMD.

Specialist:
Yes. I think Intel is also making some good changes in their CPU side. I don't think Intel is going to lose a
lot of market share in the CPU space. Of course, AMD is equally important. If others are focused on AMD,
they can also have a play there.

Analyst:
Did you hear Arm's Infrastructure Division head say that they're going to have 50% data centre CPU
market share by the end of this year? Do you probably some differing views, given the points you made
around Intel making good internal changes to shore up some of their share? To me, Arm saying that
would suggest that Nvidia's Grace Blackwell combination is going to take off. I just feel like 50% is a
really big number for them to try in such a short timeframe.

Specialist:
I will not go with a specific number. What I would say is designing a CPU is something that is their
strength, but who is going to port all those X86-based applications to Arm? You have a lot of legacy
applications that have been written on X86. Of course, it's all in the public domain. Most of the
hyperscalers have Arm-based CPUs. Again, software lift should not be underestimated. I agree with you.
50% is their wishful thinking, I think.

Analyst:
I think they have 10% or 15% share as of 2024, so that would be some significant growth.

On the head node and PCIe switches that do some of the scale out interconnect, Broadcom has had
pretty much a lion's share of this market because they got it through their PLX Technology acquisition.
I think Microchip's Microsemi was the only other one that was really offering this, and their product is
not that strong. This is an area where Astera is trying to move into. The feedback is it's only 64 lanes.
They did that so they could get out to sample with customers quickly, but the memory semantics are
pretty poor as a result. Whereas for Broadcom, 144 lanes, pretty solid memory semantics, which
means that Broadcom is going to always win when it comes to external workloads. You just can't use a
64-lane switch from Astera that has bad memory semantics because it will be really poor performance
when you have multiple customers running on the server rack. Should I expect Astera to do anything
big for this head-node type PCIe switch anytime soon? Would you say that Broadcom has still got the
market on lock?

Specialist:
First of all, there is no memory semantics on any of the PCIe switches. It's all PCIe. There is no CXL.
There is no UALink. There is no NVLink, of course. It is not memory semantic. I think based on what I
know, they designed the switch for a specific customisation that somebody requested. You need to get
more of those. It's more of a cost play, I would say. Maybe some design optimisation they have done
internally to streamline the data pipe from the storage to the GPU. I think others with the same focus can
also do it. Again, what we have seen in the history is sometimes what is very obvious often gets
neglected. We have seen that with retimers. I don't know where all Broadcom can focus their energy.
They have PCIe switches. They have these huge, custom ASICs. They are into optics. They are going into
Ultra Ethernet. They are everywhere. I don't know whether they can put focus on this low-hanging
family.

Analyst:
Maybe that's the strategy. You're focusing on these smaller scale opportunities where there's one player

Private and confidential

13

Data Centre & GPU Industry 每 Nvidia, Astera, AMD & Broadcom 每 Senior Architect at Microsoft Corp 每 31
March 2025

in town that maybe isn't putting enough focus on it because they've got some bigger opportunities
internally.

Specialist:
It can be a bigger opportunity for a smaller player, but smaller opportunity for a big player. They may
not execute on it.

Analyst:
The big debate going into Nvidia GTC was that everyone had heightened expectations around optics in
the data centre. Most of that got diffused where Jensen talked about the co-packaged optic switch, but
that it's mostly going to be for the back end and not for the intra-rack interconnect and that he feels
very strongly about keeping copper for intra-rack stuff. Do you think that copper has a lot more
staying power than some of the outsiders, who aren't fully entrenched with some of the systems work,
and that copper is going to continue to be the most cost-efficient and good enough solution for stuff
within the data centre that don't really require interconnects' long reach?

Specialist:
Yes, because if you look at Nvidia's roadmap based on GTC, they are able to go with, what, NVL 288, their
Rubin Ultra, and it's all within copper. They are able to achieve a scale of up to 288 with copper. I think if
you are able to do it with copper, why not? I think copper will be there. Optics, it's all a matter of time.
The one area where optics can be useful is, let's say, you're power limited at a rack level and you want to
scale up within two racks or multiple racks because you're power limited, then you have no choice but go
to optical. Again, if you want to put a dollar amount, if I put the right investment in my power delivery
on a rack and still able to achieve 288, I would because that will be less expensive vs building the optics
for scale up, at least for now, I'm looking at next 2-3 years.

There are a lot of very cool innovations happening in the optics. I think Jensen made that point. Anytime
when you're going to a SerDes, pluggable optics. I think this is where most of the power of the data
centre goes. If you can solve that, by not going through the SerDes technology, but using some other
optical technology, I think that will be the huge innovation on scale up. Again, these things need to go
through the product cycles, reliability, cost, and all those things will help to do it out.

Analyst:
Besides Nvidia, which companies do you think are exposed to the right product cycles, are doing the
right things around solving challenges that exist for the hyperscalers, and the ones that meet the
needs that have come with AI over the last couple of years? Are there companies that you think are both
visionary and strong executors that I should continue to watch because they know what they're doing?

Specialist:
Of course, Broadcom will be huge. I think they execute very well, and they have a track record.
Broadcom, Marvell has a lot of good assets, whether it's in the optics space, on the ASIC execution, the
IPs. Recently, MediaTek is doing a lot of good designs for both Google and Nvidia, Jensen mentioned
that. They have a good relationship with Nvidia. That's all in the ASIC business. On the other side, I think
the connectivity is another big area. Astera Lab has a place in the retimers and the PCIe CXL. I don't
know what other players＃ If you can mention me some names, I can say yes or no what you have in
mind.

Analyst:
On the cabling side of things, some people are trying to figure out why active electrical cables win the
day and why Credo is really well-placed? Would it be more active copper cables and that players such as
Macom or Semtech might be more important over the longer term? Maybe both of those arguments are

Private and confidential

14

Data Centre & GPU Industry 每 Nvidia, Astera, AMD & Broadcom 每 Senior Architect at Microsoft Corp 每 31
March 2025

wrong and it's actually going to be active optical cables.

Specialist:
I have a limited exposure to Credo, but what I've seen in the various conferences is they have good
connectivity solutions. Active copper has a place. Active optical also has a place. Both are important.

Analyst:
Everyone were overly worried about spending slowing down and that maybe there's an air gap between
training, peaking and inference reaching a scale that can fill in the pockets. Presumably, you see this as
overblown, but is there anything that you think distils it well in terms of why people shouldn't be so
worried that AI spend is already saturated?

Specialist:
If you look at some of the most recent tweet from Sam Altman, he tweeted, "Our GPUs are melting with
all these new image generation models that they released." Inference time compute is huge. I think the
need for compute for AI in inference is actually better than what we initially thought, and it will get
better. I think it's a broader question on economy. If the economy stays well, at least my personal
opinion is there will not be any slowdown. This is very typical of any type of cloud build-out. If you look
at X86 cloud build-out, it went through these phases. They have to invest early. The gain is seen only
after a few years. Physical AI was mentioned at GTC, that's another good frontier, meaning some kind of
standard chat things will go to the low-cost influence, anywhere. I think what I heard is DeepSeek has
some hallucinations so some people are not trusting those models. The good quality models are
important. My personal opinion is, no, I don't think these things are overblown right now.

Transcription ends

Disclaimer

Third Bridge Group Limited and its affiliates (together ※Third Bridge§) make no representation and accept no liability for the contents of this
transcript or for any errors, omissions or inaccuracies in respect of it. The views of the specialist expressed in this transcript are those of the
specialist and they are not endorsed by, nor do they represent the opinion of, Third Bridge. This transcript has been produced at a request of
a Client of Third Bridge and is in respect of a consultation that took place between a Client of Third Bridge and the specialist (and to which
Third Bridge was not party). You must not forward this transcript to third parties other than those to employees of the Client (or its affiliates)
or its professional advisors to the extent necessary.

Please note that all rights, including copyright, in the transcript are owned by Third Bridge, and any transcripts are provided solely for your
own use. You are not permitted to copy, broadcast, transmit, show in public, adapt or change the content in any way for any other purpose.

Private and confidential

15



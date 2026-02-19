COMMUNITY

65d0d6538a8911da05d11de9b49cc840996c80c0

AI Data Centre Industry & Astera Labs 每
Chief Architect at a US-based Technology
Firm

Consultant | 29 July 2025

Specialist Background

> Over 10 years' experience in the IT industry, focusing on AI and data centre strategy

> Well-placed to discuss technology debates around scale-up networking, as well as upcoming

ASIC (application-specific integrated circuit) efforts and how they might look a little bit different
from typical third-party merchant GPU architecture

> Knowledgeable on changes in the power distribution, as well as Astera Labs' retimer positioning

and execution risk to get to the eventual 1,000-plus accelerators per pod

Contents

I haven't heard a ton of pickup on the scale-up Ethernet Broadcom version of things. You're
RFP [request for proposal]-ing for 2027-28 demand, and you're looking at UALink, which
doesn't have silicon out the gate yet, but has the X-Series from Astera Labs that you can spec
against, and you're comparing it to NV Fusion and whatever is being offered there. I heard that
specs are pretty sparse still. What would your main considerations as you weigh the choice
between NV Fusion-based scalp-up networking and UALink-based scalp-up networking if you
wanted to diversify away from NVLink in certain parts of your AI clusters?

On the dynamic around being able to scale up to more accelerators per pod, how much
execution risk is there for Astera Labs to get to that eventual 1,000-plus accelerators per pod?
My understanding is that the initial foray into the market will be at a much lower lane count-
type switch, maybe in the 130-150 range. You're not going to get that full 1,000 accelerator
scale-up until you start marching up towards closer to 500 lanes plus. How much execution risk
do you think there happens to be or maybe not as it relates to being able to continue to build
higher-rated switches, more lanes within the switch, given that they don't have a lot of switch
know-how historically, and this is their big push into it? Are there any challenges that you're
keeping your eyes on as it relates to their ability to actually move up to that full potential?

6

7

AI Data Centre Industry & Astera Labs 每 Chief Architect at a US-based Technology Firm 每 29 July 2025

As you think about the need for UALink, you brought up the point that, from a strategic
perspective, the way they maintain their dominance is. Would I be right to think that any type of
UALink deployment is likely to be geared towards these non-Nvidia GPU-based clusters?
Mainly ASIC [application-specific integrated circuit]-type deployments because Nvidia is
probably going to close off any Nvidia-related opportunities. As you think about that ramping
in the 2027-28 timeframe, that has something to do with the fact that that's when a lot of these
custom ASICs are going to start ramping in, in more meaningful volumes?

When the UALink spec first came out, I feel like there's a lot of industry debate that there wasn't
a high-rated switch that was UALink compatible, and so that was going to have to get developed
and people are saying that as a potential question mark because when you think about typical
high-rated switches, there's only a handful of companies that do that such as Broadcom,
Marvell and Cisco. It sounds like Astera Labs is taking more of the PCIe [peripheral component
interconnect express]-native approach, where they've got a lot of know-how on the PCIe
specification, and so that really lowers the execution bar for them because they're just going to
make a pretty PCIe-like switch and don't need to focus too much on building a ground-up
UALink one. Are there any shortfalls to taking that approach without looking at a UALink
switch, from a ground-up perspective and taking a lot of what's already been developed on the
PCIe switch side of things, using that and tweaking it a little feature set-wise to make sure that
it's fully compatible with the UALink spec?

How would you be thinking about your appetite to pay per lane for an X-Series or UALink
switch? It sounds like people are resonating in the USD 5-7 per lane type of neighbourhood,
which the 150 [sic] lane first version of the chip would suggest it's like USD 800-1,000 plus. Is
that reasonable for you or is there a basis to think about what would drive appetite for dollar-
per-lane type of ASPs for these types of products?

When I think about how this fits into the rack ecosystem, the way that I understand it is
typically, you'll have two raw GPU die per package, and then there'll probably be two ports
sitting on the package, and you'll use one of those links for an X-Series or any sort of scale-up
chip. You're looking at one switch chip per four GPU die is a reasonable way to think about how
that might scale up in a typical AI data centre. I'm sure there's some nuance to that. Is that
relatively reasonable?

UAL spec number one came out, and then spec number two is going to come out later this year.
I've been hearing that a big debate is that a lot of customers want optics to be included in the
spec, maybe that's like PCIe over optics. I've heard that the main driver of that is that we've had
the shift from passive DAC [direct attach copper] to active electrical, and there is a thought that
the transition is going to continue to occur towards linear pluggable optics. There's going to be
some sort of need for PCIe over optics compatibility for UALink as well. Is that something that
you would expect to hear a lot more from over the next 6-12 months, that UALink becomes
more PCIe over optics supportive and a lot of that is driven by that exact transition, AECs [active
electrical cables] waning a little as optics reliability and costs improve over time?

8

8

9

9

10

Private and confidential

2

AI Data Centre Industry & Astera Labs 每 Chief Architect at a US-based Technology Firm 每 29 July 2025

I would think that Astera's retimer position is going to get attacked because of this. Thinking
about retimers today, they're integrated right into the motherboard. The switch cost is a little
higher because of that. That's already starting to come down a little because they do the smart
cable modules without the retimers and DSPs, and the paddle chips that are in the actual cord.
That's already pluggable in nature and more switch effective, and that will only increase as LPO
[linear pluggable optics] starts to replace some of the interconnect dynamics. You mentioned
it's probably more like USD 7-11 per lane, but that incremental dollar-per-lane content
opportunity outside of the USD 5-7 that I mentioned for switch chips probably becomes more
competitive for Astera because it's much more plug-and-play oriented and so you can attack
the installed base a little more effectively that Astera has had so far on the retimer side of things
as the signal integrity solutions, you become less integrated with the motherboard. Is that
relatively reasonable as well?

On the LPO front, are Broadcom and Marvell, the main players to pay attention to that are doing
the best work there? Are there any smaller-scale companies that you think I should keep my
eyes on that might benefit a little from the shift to LPO?

On the CPO [co-packaged optics] front, you mentioned that it's going to be this corner case for
ultra-dense switch deployments. I know there are still some challenges around high-loss
radius in the instance of failure. If the laser goes down, then the entire switch might go down,
and perhaps the entire GPU cluster goes down, gets solved by things such as 3D packaging or
liquid cooling for the actual switch itself to eliminate some of the heat dissipation issues or do
you think some of those high-loss radius failure issues are more sticky in nature?

Astera's competitors, Credo is one in particular that likes to knock Astera for their Cosmos, like
saying that's not all that differentiated. I'm of the impression that it very much is, and it sounds
like you are, too. From your perspective, what would be the key areas of differentiation that
come from Cosmos that are super beneficial to you vs what you get offered from other vendors
that are trying to take some socket share?

To the extent that you're pointing to the fact that Astera is very focused on diversifying its
portfolio. The one area that I feel like they are behind in is the Ethernet AEC product. They've
got the Taurus-branded AEC; it is mostly 400G today. They're talking about getting to 800G
sometime this year. 800G has already been ramping, and there are paths to 1.6T and even
conversations around 3.2T. When I think about the levels of priority for Astera, is Taurus
something that they can succeed in as well or do they have enough goodness going on
elsewhere that I shouldn't expect them to start to gain market share in Ethernet-based AECs?

11

11

11

12

12

Private and confidential

3

AI Data Centre Industry & Astera Labs 每 Chief Architect at a US-based Technology Firm 每 29 July 2025

If I think back to three years ago, I feel like the expectations were just as robust for CXL
[compute express link]. The AI watershed moment came and everyone started focusing on
training. To your point, CXL can become a lot more interesting for inferencing because
inference workloads are more memory bottlenecks than compute or even networking
bottlenecks. I see it as an emerging value proposition that's finally going to come into the
forefront a little more because it seems like we're knocking on the door of inference CAPEX
playing a larger role than training CAPEX, and the cost dynamics make plenty of sense to get
2TB of extra memory at maybe slightly lower latency for way cheaper. It's like USD 100-150 for
some of these CXL controllers vs thousands of dollars for an incremental DIMM [dual in-line
memory module]. The latency issue seems like the biggest bottleneck for CXL natively for the
memory fabric. How do you see that being a problem? In certain inference use cases, latency
sensitivity is of the utmost importance. Does that create some problems for CXL's value
proposition?

When I think about insertion, originally, it was like talking about Granite Rapids and Turin; it
seems like those are the 2.0 compatible CPUs. Should I wait until the 3.0 compatible CPUs come
out, that that's when the CXL rise really starts to occur?

Let's think about any other issues with CXL. I know thinking about host biasing and some of the
software layer elements of it are going to be important because of the composability and
disaggregation of it. How are ecosystem efforts at the software layer one or two layers up from
the actual controller chip itself, going? Are there still some challenges that need to be
addressed?

From a SerDes front, 224G is the workhorse right now. I feel like there are debates around
whether or not we see a jump to 400G-type SerDes or optics as we think about next-gen
devices. What are the puts and takes as you think about the likelihood of whether or not 400G
becomes the next workhorse SerDes or if SerDes starts getting attacked by optics over time?

For Astera Labs on the optical gearbox side of things, can you explain that? It's relatively new. I
think it's a corner case for the time being. Can you explain where the optical gearbox comes
into play? Is Astera doing anything overly differentiated on that front?

On the power distribution side of things, Nvidia is moving to this 800V HVDC architecture. It's
going to be a separate power rack. To what extent are we going to see a pretty decent increase in
wide bandgap products such as SiC [silicon carbide] and GaN [gallium nitride] vs pre-Rubin
power distributions? Is it going to be meaningfully more non-silicon vs silicon-type power
components or a gradual transition? Do players such as Navitas or on the SiC side of things such
as Onsemi or Infineon, have the opportunity to take some incremental share from more silicon
pure plays such as TI [Texas Instruments] or Monolithic Power, within the AI data centre?

13

14

14

15

15

16

Private and confidential

4

AI Data Centre Industry & Astera Labs 每 Chief Architect at a US-based Technology Firm 每 29 July 2025

Power stages are super important, especially because we've got hundreds of different power
stages in Blackwell, and that's only going to continue to increase with Rubin. I've also heard,
though, that the ability to be able to sell both the controllers and the power stage is becoming
increasingly important because at a point of failure, there are a lot of fingers at Monolithic
Power, TI is going to point fingers at someone else and say that it's not the power-stage
controller. There's a desire to have a single throat to choke. Is that true? If so, are any vendors
missing one piece of the two-piece puzzle? For example, Onsemi's power stage is pretty decent,
but they're still in the process of developing more quality controllers and maybe that will come.
Maybe it will not be in time. Is that a dynamic that I should be aware of in your mind, that you'd
want the ability for the vendor to be able to do both? Is there anyone on or otherwise that
doesn't have that just now?

17

Private and confidential

5

AI Data Centre Industry & Astera Labs 每 Chief Architect at a US-based Technology Firm 每 29 July 2025

AI Data Centre Industry & Astera Labs 每
Chief Architect at a US-based Technology
Firm

Transcription begins

Analyst:
We've been talking a little bit about the scale-up networking dynamics, where NVLink has been very
dominant, but it's a closed architecture. There's a handful of efforts to provide a quasi more open
alternative to that, whether it's NV Fusion at the least open alternative, where you still have to take
either an Nvidia CPU or GPU, but you can have the opportunity to introduce your own proprietary CPU or
GPU alongside that and get the chip-to-chip interconnect. You've got UALink and then, as one-third,
you've got scale-up Ethernet from Broadcom based on their Ultra Ethernet, Tomahawk switches. It
sounds to me Amazon might be leaning in over the next 12-18 months or so more heavily into the X-
Series Astera Labs PCA scale-up switch, which to me has always been the precursor to what eventually
will be UALink. It seems like for the time being, because UALink isn't out yet, there's likely to be a decent
ramp on this X-Series switch, but that there will be a continued debate around as UALink silicon comes
into the market, whether or not you go with that long term or if you maybe opt for something like NV
Fusion.

I haven't heard a ton of pickup on the scale-up Ethernet Broadcom version of things. You're RFP
[request for proposal]-ing for 2027-28 demand, and you're looking at UALink, which doesn't have
silicon out the gate yet, but has the X-Series from Astera Labs that you can spec against, and you're
comparing it to NV Fusion and whatever is being offered there. I heard that specs are pretty sparse still.
What would your main considerations as you weigh the choice between NV Fusion-based scalp-up
networking and UALink-based scalp-up networking if you wanted to diversify away from NVLink in
certain parts of your AI clusters?

Specialist:
That's a great question. I'd say, first of all, would be the bandwidth per GPU. I'd want to see exactly how
much bandwidth I would get at the GPU level. I'd want to look at latency, making sure that it's definitely
sub-microsecond. I'd want to look at the overall topology. Is it going to be something where it's like
point-to-point where NV Fusion is that switch fabric or is it going to be UALink, which is mesh, can
handle ring, can handle daisy chain, can handle switch fabric, things like that. I'd want to look at the
memory semantics. Is it cash coherent like NV Fusion is or is it something like UALink is where it's
memory load store semantics across a bunch of different heterogeneous accelerators, so I could not get
locked in any one ecosystem. I'd want to look at the interconnect type. Is it something where like NVLink
uses NVLink over proprietary SerDes vs UALink, which is really, frankly, modified Ethernet and uses
custom transaction layers. I'd also want to look at what the maximum scale is because NV Fusion tops
out at, what is it, 570 GPU, something like that, whereas UALink is 1,024 accelerators per pod.

With NV Fusion, you get better bandwidth, but you can have more accelerators in a pod with UALink.
Other things I would look at too would be integration, looking at compatibility, what CPUs does it
support, which GPUs does it support. With NV Fusion, it's only Nvidia GPUs vs UALink can use AMD, can
use custom ASICs, can use Intel Gaudis, things like that and can use Nvidia ones. I want to look at the

Private and confidential

6

AI Data Centre Industry & Astera Labs 每 Chief Architect at a US-based Technology Firm 每 29 July 2025

software stack because, honestly, ROCm vs CUDA, it's kind of a no concept there. ROCm has been getting
much better. With UALink, you can also use SYCL and you can use custom drivers and things like that,
too. With UALink though, I think Astera is a promoting founder of UALink as well. With UALink, you get
buy-in from Azure, you get buy-in from Google, you get buy-in from Meta, things like that. NV Fusion is
really tied to just the Nvidia ecosystem so you've got great software systems and DGX. I also want to look
at what the, how to say this, strategic implications would be, when it comes down to Nvidia, and don't
get me wrong, we're huge customers and partners with Nvidia. NVLink and NV Fusion really help Nvidia
to maintain their dominance, whereas UALink, the idea is to democratise interconnects and make it so
that it's easier to interconnect different hardware within your broader ecosystem.

UALink also is more about full openness across different vendors, whereas Nvidia is really about, you got
to use Nvidia's hardware. You got to play in their CPU and GPU landscape. UALink is more about being
consortium-driven and being collaborative vs something like NV Fusion where if Nvidia has issues
because they are so proprietary, then you're tied to that, too. You've got NV Fusion out there now. Going
forward, I think in 2027, probably 2028 is where you're going to see more commercial deployments of
UALink and C-silicon out there. Honestly, UALink, I would say, is a pretty broad sell though to try to
break Nvidia's monopoly on scale-up fabrics. It's not necessarily a bad thing, but Nvidia, they frankly
dominated the market is what it comes down to. Whatever they say you're going to pay, you're going to
pay. I think it's a good thing from a competition standpoint because it frankly forces them to innovate
and be less proprietary.

Analyst:
On the dynamic around being able to scale up to more accelerators per pod, how much execution risk is
there for Astera Labs to get to that eventual 1,000-plus accelerators per pod? My understanding is that
the initial foray into the market will be at a much lower lane count-type switch, maybe in the 130-150
range. You're not going to get that full 1,000 accelerator scale-up until you start marching up towards
closer to 500 lanes plus. How much execution risk do you think there happens to be or maybe not as it
relates to being able to continue to build higher-rated switches, more lanes within the switch, given
that they don't have a lot of switch know-how historically, and this is their big push into it? Are there
any challenges that you're keeping your eyes on as it relates to their ability to actually move up to that
full potential?

Specialist:
They've actually done a really good job of mitigating the risk. I would say interoperability, making sure
that they've got seamless PCIe 6 and CXL 3 UALink compatibility across their GPUs, across their CPUs,
across their switches. They've done that a lot with their Interop Lab. With the Scorpio switches, with the,
what are they, Aries is the retimers and then the Leo controllers, they've done a really good job of
making sure that interoperability between them that you'll be able to leverage different technologies
from Nvidia, from AMD, from Intel, from Micron. I'd say signal integrity, that's always a challenge when
it comes to those bigger pods, and you want to make sure that you've got better link stability, especially
if you've got a long-reach topology or it's a very dense pod. With the Aries retimers and their gearboxes
with optical modules that they've got, they really are built from a signal integrity where they're laser-
focused on making sure that you've got as much stability as possible.

The other issue you typically have with those very dense pods is thermal management, power
constraints and things like that. With the Cosmos software, they release a new version of Cosmos every
other day. They keep optimising and optimising it for better routing, better for telemetry. They've got
power aware diagnostics in there. With Cosmos and with the Scorpio switches, they've done a really
good job of helping to manage any thermal dynamics or power constraints that you've got in there. I'd
say that's the other thing, too, is Astera work very well with Nvidia, but at the same time, they are one of
the founding members of UALink. When it comes down to it, they're the ones who help ratify the spec

Private and confidential

7

AI Data Centre Industry & Astera Labs 每 Chief Architect at a US-based Technology Firm 每 29 July 2025

for 200G. They're the ones that actually set forth what the dynamics should be for having a 1,024
accelerator. They set the spec, they're setting their own bar. Then the other thing, too, is they're already
shipping PCIe 6 components. They've got reference designs with Nvidia NGX. When it comes down to it,
they're already at the foray of it. If anyone is probably poised to deliver on that amount of density, it
would probably be Astera rather than some of the competition.

Analyst:
As you think about the need for UALink, you brought up the point that, from a strategic perspective,
the way they maintain their dominance is. Would I be right to think that any type of UALink
deployment is likely to be geared towards these non-Nvidia GPU-based clusters? Mainly ASIC
[application-specific integrated circuit]-type deployments because Nvidia is probably going to close
off any Nvidia-related opportunities. As you think about that ramping in the 2027-28 timeframe, that
has something to do with the fact that that's when a lot of these custom ASICs are going to start
ramping in, in more meaningful volumes?

Specialist:
Honestly, that's up to Nvidia and Jensen to decide that. It's not just his decision. If they're strategically
going to try to lock you into their ecosystem, frankly, I think it'd be a bad move on their part because it's
like when Intel had the dominance in the CPU market and they try to do some stuff like that, too. That
gave rise to AMD and that gave rise to a lot of their competitors out there. UALink supports GPUs. It
supports AMD. It supports Intel Gaudis. It supports other non-Nvidia GPUs and of course, supports
ASICs, so if you want to do a Google GPU or an AWS Trainium, but you can also get chips from like
Broadcom and Marvell and things like it, too. Also does support FPGAs, and it's not really a primary
focus of it, but it does fully support that. It doesn't directly support Nvidia GPUs. You typically have to
use NV Fusion. If anything, NV Fusion is going to be the outsider and if they want to continue to be
proprietary and have you＃ That's the thing is they are the dominant GPU right now.

At the same time, interoperability. Look at what Linux did for cloud acceleration. We used to have with
Windows. Windows was the dominant operating system. Then with Linux being open-source, the fact
that you could actually just use it and it costs next to nothing, that's what made Linux the dominating
operating system for the cloud, too. When it comes down to it, that whole walled-garden approach
doesn't always work unless you've got such a big moat that you can crush your competitors. If anything,
history has proven that that just doesn't work.

Analyst:
When the UALink spec first came out, I feel like there's a lot of industry debate that there wasn't a
high-rated switch that was UALink compatible, and so that was going to have to get developed and
people are saying that as a potential question mark because when you think about typical high-rated
switches, there's only a handful of companies that do that such as Broadcom, Marvell and Cisco. It
sounds like Astera Labs is taking more of the PCIe [peripheral component interconnect express]-
native approach, where they've got a lot of know-how on the PCIe specification, and so that really
lowers the execution bar for them because they're just going to make a pretty PCIe-like switch and
don't need to focus too much on building a ground-up UALink one. Are there any shortfalls to taking
that approach without looking at a UALink switch, from a ground-up perspective and taking a lot of
what's already been developed on the PCIe switch side of things, using that and tweaking it a little
feature set-wise to make sure that it's fully compatible with the UALink spec?

Specialist:
If anything, I think they're going to have a progression path. In terms of shortfalls, I don't know, it's a
little nuanced is what it comes down to. If you're going to go to an all-in UALink-native fabric, then
what it comes down to right now is that until hardware is going to be manufactured at scale, it's not

Private and confidential

8

AI Data Centre Industry & Astera Labs 每 Chief Architect at a US-based Technology Firm 每 29 July 2025

going to make much of a difference. With PCIe-based switches, there's definitely higher latency vs
UALink, which are sub-microsecond. I would say with UALink, you definitely have full-load store,
you've got atomic ops and things like that from a memory semantic standpoint, but PCIe is limited. With
PCIe, you can only get to 64 accelerators vs UALink, you get the whole 1,024, and that's an ambitious
goal, too. UALink is optimised for AI workloads and PCIe is general purpose. What it comes down to is
they're basically setting their trajectory of making sure that the other thing too would be power and die
where UALink has a leaner protocol stack vs PCIe, which has higher overhead. At the same time, PCIe is a
little bit of a vendor lock-in is what it comes down to, whereas with UALink, they're able to basically say
that it works with anything.

I would say the reason that they still build PCIe switches is that it's just ubiquitous among CPUs, GPUs,
storage, things like that. It's really good for front-end connectivity. You get CXL memory expansion,
too, which is great for inference workloads. I wouldn't expect them to go all in on UALink. I think that
they'll probably still build PCIe switches in the future. Where the market is right now is it's PCIe,
Generation 5, Generation 6 that they're already deployed. They're basically biding their time until
UALink is more ubiquitous. Then I think that they're going to really switch over into that. Frankly, it's a
dual strategy is what it comes down to is they want their Scorpio, their P-Series to help target like PCIe
and CXL and then they're going to have Scorpio X, which will be more for UALink. It's really coming
down to if you want to buy the switches, buy them for whichever technology is best in market. The
problem with PCIe is that they're just not ultra-low latency. Right now, they're great but in two years,
you're going to definitely want those X-Series switches.

Analyst:
How would you be thinking about your appetite to pay per lane for an X-Series or UALink switch? It
sounds like people are resonating in the USD 5-7 per lane type of neighbourhood, which the 150 [sic]
lane first version of the chip would suggest it's like USD 800-1,000 plus. Is that reasonable for you or is
there a basis to think about what would drive appetite for dollar-per-lane type of ASPs for these types
of products?

Specialist:
When it comes down to it, I would say you're in the right ballpark for any lane level silicon, I'd say it's a
reasonable target, USD 5-7 per lane. If you're doing 200GB per second PHY and controller IP when it
finally hits production, I think that really what it comes down to is＃ What Synopsys had like projections
that it would probably be USD 5-7 per range. You also have to look at the switchboard overhead. You
have to look at packaging, you have to look at retimers, which adds another USD 2-4 there. Your total
bill of materials is going to be, before any level integrations can be anywhere from USD 7-11. That being
said, because UALink has a much better protocol stack, it's going to reduce the die area, going to reduce
the power and 31% of the cost of operating a data centre is power. It's a broader ecosystem, and it's an
open ecosystem. You could use Broadcom, you could use Astera, you could use Synopsys, things like that.
It's all interoperable IT. The pricing, just like supply and demand, is going to be more competitive.

I think you're also going to see just better scale-up efficiency. What is it the goal for UALink is to have
93% effective bandwidth at a much lower cost. From an economic standpoint, it's different trade-offs,
too. It's the cost per accelerator, the radix trade-offs, the rack-level interconnects and things like that.
USD 7-11 for a total bill of materials is probably more realistic.

Analyst:
When I think about how this fits into the rack ecosystem, the way that I understand it is typically,
you'll have two raw GPU die per package, and then there'll probably be two ports sitting on the
package, and you'll use one of those links for an X-Series or any sort of scale-up chip. You're looking
at one switch chip per four GPU die is a reasonable way to think about how that might scale up in a

Private and confidential

9

AI Data Centre Industry & Astera Labs 每 Chief Architect at a US-based Technology Firm 每 29 July 2025

typical AI data centre. I'm sure there's some nuance to that. Is that relatively reasonable?

Specialist:
Two raw dies per package is one of the most common configurations, especially if you're using multi-
chip modules and advanced packaging. I've seen single-die configurations where you've just got the
monolithic chip. I've seen dual dies where you got two raw dies side by side or they can be stacked. I see
multi-die where they've got several dies in just a single package with chiplets and stacked DRAM and
HBM, which HBM is super hot right now. Stacked die where you get dies that are layered vertically
completely. Then you get chiplet-based where there's modular dies with die-to-die interconnects, too.
That's what AMD does with EPYC and Intel does with Ponte Vecchio and AI pods and things like that.
There's a lot of different configurations in a package, frankly, two dies. The nice part about that, as
you're alluding to, is that you can split the logic and split the I/O into separate dies, which ultimately
gives you better wafer yield. From a process standpoint, you might have one die that's usually using
advanced logic like 3nm and then the other more mature I/O, anywhere upwards of 28nm for process
mixing.

The other benefit that gives you, frankly, is just thermal isolation. If you got a high-power compute
from something that's very sensitive from an analogue standpoint, two dies does tend to be the better
way to go. The other part that if you got one of those dies that fails or if you need to upgrade one of the
dies, you can do so from a modularity standpoint without having to redesign the whole chip. That's why
you see such a proliferation of the dual-die approach.

Analyst:
UAL spec number one came out, and then spec number two is going to come out later this year. I've
been hearing that a big debate is that a lot of customers want optics to be included in the spec, maybe
that's like PCIe over optics. I've heard that the main driver of that is that we've had the shift from
passive DAC [direct attach copper] to active electrical, and there is a thought that the transition is
going to continue to occur towards linear pluggable optics. There's going to be some sort of need for
PCIe over optics compatibility for UALink as well. Is that something that you would expect to hear a lot
more from over the next 6-12 months, that UALink becomes more PCIe over optics supportive and a
lot of that is driven by that exact transition, AECs [active electrical cables] waning a little as optics
reliability and costs improve over time?

Specialist:
All the talk and the chatter that I've heard about getting linear pluggable optics, LPOs in UALink 3, it
really comes down to is the desire to scale AI clusters across racks. While at the same time, having low
latency, having high bandwidth and then also being super energy efficient. Copper is limited to about
four metres is what it comes down to, whereas optics are going to allow you to extend UALink beyond a
single rack from a power standpoint, optical links are, frankly, a heck of a lot. They consume very little
power is what it comes down to vs having to retime any electrical links. From a thermal standpoint,
optics, they just don't have the heat density that a high radix switch environment is going to have. From
a bandwidth scaling standpoint, any 200G lane optics that you have, they would actually do a really good
job matching UALinks like PHY spec for future-proofing it. You'd be able to just go forward from a
bandwidth standpoint and continue to scale it up. I'd also say just some of the pods that we're building, a
lot of the pods that we used to build were 50-100 accelerators. Yes, as you're getting into the 1,000
accelerator range, any optics would enable that scale going beyond the four-metre rack-to-rack
distance.

As we grow the size of the clusters, optics definitely play a bigger role in them, and that's because of the
power, it's because of lower latency. Nice part about LPOs is they're hot swappable and they're super
modular. Then from short reach standpoint, they are super cost-effective vs any of the other fabrics that

Private and confidential

10

AI Data Centre Industry & Astera Labs 每 Chief Architect at a US-based Technology Firm 每 29 July 2025

you've got out there, too. CPOs at the same time, co-packaged optics, I would say they're looking to be
more dominant from ultra-dense switch designs, but LPOs are frankly more flexible, you get a pluggable
path for UALink too. The UALink consortium, they're more aligning with OIS and LPO MSA efforts,
frankly, for ecosystem readiness. I would say, yes, you hit the nail on the head, LPOs are definitely going
to play a role in probably 3.0.

Analyst:
I would think that Astera's retimer position is going to get attacked because of this. Thinking about
retimers today, they're integrated right into the motherboard. The switch cost is a little higher because
of that. That's already starting to come down a little because they do the smart cable modules without
the retimers and DSPs, and the paddle chips that are in the actual cord. That's already pluggable in
nature and more switch effective, and that will only increase as LPO [linear pluggable optics] starts to
replace some of the interconnect dynamics. You mentioned it's probably more like USD 7-11 per lane,
but that incremental dollar-per-lane content opportunity outside of the USD 5-7 that I mentioned for
switch chips probably becomes more competitive for Astera because it's much more plug-and-play
oriented and so you can attack the installed base a little more effectively that Astera has had so far on
the retimer side of things as the signal integrity solutions, you become less integrated with the
motherboard. Is that relatively reasonable as well?

Specialist:
Yes, definitely. I got to say that Astera has really done a really good job of diversifying their product
portfolio. They've got smart retimers, they've got smart gearboxes. They've got fabric switches, what
smart cable modules. They've got optical modules. They've got Ethernet modules. If anything, and they
do CXL controllers, they do NVLink, they've done a really good job of instead of going all in on one
technology, diversifying their product portfolio so that, yes, in the event that, let's say, retimers that
you no longer need them integrated with LPOs, then you could still sell them, but because they've got
optical modules and things like that that they'd be still well-positioned to take advantage of that
progress where the industry is going.

Analyst:
On the LPO front, are Broadcom and Marvell, the main players to pay attention to that are doing the
best work there? Are there any smaller-scale companies that you think I should keep my eyes on that
might benefit a little from the shift to LPO?

Specialist:
I would say, yes, Broadcom have been pretty impressive. I would say Dell, they're looking at some end-
to-end LPO deployments. Macom is another one. There's a company DustPhotonics. They do silicon
photonics. Then there's an architectural firm called Latitude Design Systems. They're doing some pretty
impressive stuff out there in terms of being thought leaders on LPO vs CPOs and deployment risk and
how to consider them. Broadcom and Macom and then Dell would probably be the biggest ones.

Analyst:
On the CPO [co-packaged optics] front, you mentioned that it's going to be this corner case for ultra-
dense switch deployments. I know there are still some challenges around high-loss radius in the
instance of failure. If the laser goes down, then the entire switch might go down, and perhaps the
entire GPU cluster goes down, gets solved by things such as 3D packaging or liquid cooling for the
actual switch itself to eliminate some of the heat dissipation issues or do you think some of those
high-loss radius failure issues are more sticky in nature?

Specialist:
Latitude. Just when it comes down to it, you want to make sure that you've got no single point of failure.

Private and confidential

11

AI Data Centre Industry & Astera Labs 每 Chief Architect at a US-based Technology Firm 每 29 July 2025

All of clusters and pods are designed to be doubly redundant. When you design it out like that, you can
have single points of failure. As long as you've got layer dependencies, you've got the telemetry in there
to help predict it. That way, you're able to really anticipate a failure before it occurs and then be more
proactive about it. I think with liquid cooling, I think with single lasers as well, as long as you're
designing for redundancy, then you can do a really good job. Each one of those clusters, every time we
build one of those, those are USD 300m-400m per cluster.

Analyst:
Astera's competitors, Credo is one in particular that likes to knock Astera for their Cosmos, like saying
that's not all that differentiated. I'm of the impression that it very much is, and it sounds like you are,
too. From your perspective, what would be the key areas of differentiation that come from Cosmos that
are super beneficial to you vs what you get offered from other vendors that are trying to take some
socket share?

Specialist:
I don't know, Credo and I have a love-hate relationship.

Analyst:
You're probably talking to the same guy.

Specialist:
Yes I would say, Credo has always been more Ethernet-centric vs Astera. Credo has been around since
2008, whereas Astera, they were founded, what, 2016-17. They've really been geared towards more of
the AI market and more being cloud-native. They don't think with that legacy mindset. Credo does
optical DSPs, but they've been an Ethernet-based company. They do AECs and things like that vs Astera
where they're really focused on AI fabrics, UALink, CXL, PCIe. They're both targeted towards
hyperscalers, but where Astera leans heavily into the future with ASICs and with GPUs, Credo is more
about enterprises and OEMs and the legacy data centre model. I would say that when it comes down to it,
both of them are AI aligned, but I would say Astera does tend to have deeper integration with GPUs and
with ASICs, whereas Credo is still strong in Ethernet, and they do PCIe Gen 6, but that's what they do
with AECs, too. I would say Credo is still focused on the system-level design stack, whereas Astera with
Cosmos, it's got excellent debugging.

There's a lot of different tools out there that come in the Cosmos stack as well. Credo, because they're so
Ethernet heavy, it's weighing them down vs where Astera they're willing to be more＃ I don't know,
Credo just tends to be more risk averse. How many companies would you see that build competing
products within their four walls? You look at HP with the best jet and the laser jet printers. It's like, why
would you create two products that compete against one another? It's like, there's two different
markets. One is the home user and one is the office user. It's bold to find a company that's willing to do
that and basically cannibalise itself. At the same time, that positions you better for the future so that if
the market goes one direction, if it zig, you can zag and you're not caught off guard vs someone like
Credo, which because it's so Ethernet-based and they lived in that Ethernet world that if the world does
decide to go do away with Ethernet, then they're going to be left holding the bag there. Yes, we might be
talking to the same people. Honestly, I don't know, Credo, they've got some challenges.

Analyst:
To the extent that you're pointing to the fact that Astera is very focused on diversifying its portfolio.
The one area that I feel like they are behind in is the Ethernet AEC product. They've got the Taurus-
branded AEC; it is mostly 400G today. They're talking about getting to 800G sometime this year. 800G
has already been ramping, and there are paths to 1.6T and even conversations around 3.2T. When I
think about the levels of priority for Astera, is Taurus something that they can succeed in as well or do

Private and confidential

12

AI Data Centre Industry & Astera Labs 每 Chief Architect at a US-based Technology Firm 每 29 July 2025

they have enough goodness going on elsewhere that I shouldn't expect them to start to gain market
share in Ethernet-based AECs?

Specialist:
I would say, Credo is very good with Ethernet and with AECs. They dominate pretty much the market for
any AECs or Ethernet retimers. They're optical DSPs, They've got a 3nm 200G lane DSP. They are really
leading the forefront of getting out 1.6T optics. The challenge you also have with Credo though, is that
they own the full stack. It's the SerDes IP, the retimers, the DSPs and the system design, which is a good
thing because you do have fast innovation cycles, you don't have to worry about interoperability. When
it comes down to it, I would say if you're looking towards building more AI training pods, scale-up
fabrics and whatnot, Astera is just more aligned where things are going. If you're just looking to do
retimer-heavy Ethernet fabrics, the sheer number of retimers we buy is insane. You know what a retimer
is, the reason you have to have retimers is just none of the hardware is all patches where it's just
basically like, this one is fast, this one is slow. Hey, we have to buy additional hardware to just retime it
all to make sure that lane deployments are proper and that you've got that.

You can get down to not having to buy retimers, that's the ideal state where you don't need additional
hardware to account for existing hardware. Do I think that Astera is going to get there? Yes, I'm actually
a fan. I think that again, they lean into the future vs going, "We've got revenue coming from retimers so
why would we want to do away with it?" They're basically like, "Look, if we can get rid of our retimer
business and lean heavily into more interoperability, that's going to help us to sell many of our other
products as well."

Analyst:
If I think back to three years ago, I feel like the expectations were just as robust for CXL [compute
express link]. The AI watershed moment came and everyone started focusing on training. To your
point, CXL can become a lot more interesting for inferencing because inference workloads are more
memory bottlenecks than compute or even networking bottlenecks. I see it as an emerging value
proposition that's finally going to come into the forefront a little more because it seems like we're
knocking on the door of inference CAPEX playing a larger role than training CAPEX, and the cost
dynamics make plenty of sense to get 2TB of extra memory at maybe slightly lower latency for way
cheaper. It's like USD 100-150 for some of these CXL controllers vs thousands of dollars for an
incremental DIMM [dual in-line memory module]. The latency issue seems like the biggest bottleneck
for CXL natively for the memory fabric. How do you see that being a problem? In certain inference use
cases, latency sensitivity is of the utmost importance. Does that create some problems for CXL's value
proposition?

Specialist:
I honestly think with CXL Type 3 devices, they add DDR5 over PCIe. That you're basically getting around
any of the CPU channel limits. I think CXL, frankly, from a latency standpoint, it really is designed to
avoid traditional memory translation delays, which is actually really well positioned for inferencing. CXL
also has that disaggregated architecture, too. You're able to do composable AI fabrics where memory and
compute scale independently, which is really well aligned for inferencing. Then with CXL, you can do
multiple accelerators. You can do GPUs and ASICs and they can share a unified memory pool. That way,
you really reduce the fragmentation and you ultimately reduce latency too. If anything, CXL, from an
ecosystem standpoint, it's definitely been emerging.

I think Astera and MemVerge and Supermicro, Micron too, and Samsung. They're all shipping CXL
memory modules. From a performance standpoint, though, what is it, like 35-40% bandwidth boost and
24% speed up if you are using it for AI and HPC workloads. The software stack around it with Linux too,
the Linux kernel 6.9 now supports doing what's called weighted interleaving, so you can do it across

Private and confidential

13

AI Data Centre Industry & Astera Labs 每 Chief Architect at a US-based Technology Firm 每 29 July 2025

DRAM and do it across CXL memory. If anything, CXL, to your point, is very well-positioned for
inferencing, but also vector searching, LLM caching, RAG pipelines, things like that, where you don't
need the speed that you would for a training workload, but inferencing because of memory
disaggregation is perfect for that.

Analyst:
Thinking about the pooling opportunity, I've seen demonstrations where it's just like 8-16 Leo
controller chips integrated onto a single PCB trace board. Is that how you'd think about the opportunity
or is someone going to come out with a higher power box or integrated box that is more geared towards
the pooling opportunity where you don't just get the 2TB of expanded capacity, you get much more on
that?

Specialist:
I'm going to refrain from answering on that. I'm unable to answer that one.

Analyst:
When I think about insertion, originally, it was like talking about Granite Rapids and Turin; it seems
like those are the 2.0 compatible CPUs. Should I wait until the 3.0 compatible CPUs come out, that
that's when the CXL rise really starts to occur?

Specialist:
I don't know. I've seen some impressive stuff nowadays, too. I would say that 3.0 is definitely going to
give it some benefit. I would say just when it comes to insertion hints and things like that, they are,
frankly, the best way to optimise latency for that high-speed data transmission. When it comes down to
it, I don't know, I think, frankly, you can always wait and wait and then lose the market opportunity, too.
I would say, just to give it a couple more months, and you're going to see definitely some progress being
made there.

Analyst:
They've mentioned that they've got some projects in flight that might have the opportunity to ramp
towards the end of this year, so that aligns with how they've been talking about it, too. I think pooling is
way more exciting than expansion. I wasn't sure to the extent that some of those early deployments
might be more light volumes.

Let's think about any other issues with CXL. I know thinking about host biasing and some of the
software layer elements of it are going to be important because of the composability and
disaggregation of it. How are ecosystem efforts at the software layer one or two layers up from the
actual controller chip itself, going? Are there still some challenges that need to be addressed?

Specialist:
I would definitely say, latency sensitivity is always an issue, and you get that with CRC and FEC fallback
and things like that. You can mitigate that using different software with any NOP insertion complexity. It
just comes down to how well you schedule it to maintain low latency flitting and things like that. If you
do verification and debugging, then you can help to remedy that with CXL. Any memory coherency
issues with CXL 2, if you've got like CXL.cache or CXL.mem interactions that can sometimes cause stale
data or race conditions and things like that. Again, it comes down to your software stack and how well
you control that too. With memory coherency, for example, so if you've got strict cache flushing policies
and weighted interleaving and the Linux kernel, then it will take care of that. With latency tuning, you
can use 256B latency optimised flip mode with NOP insertion hints, and it will address any of the CRC
and the FEC transitions, some of the other issues you get.

Private and confidential

14

AI Data Centre Industry & Astera Labs 每 Chief Architect at a US-based Technology Firm 每 29 July 2025

The software stack with CXL in the past has been typically with the kernel, with the bias, with
orchestration tools have been traditionally immature, but the software is honestly, as long as you
validate that a CXL 3.0 compliant and use orchestration tools like MemMverge and things like that, then
it's actually pretty good with handling it, too. From a security standpoint, that's always, you worry about
shared memory pools. If any one of the operators in there poisons the pool or anything like that, then
you can have an attack vector. With the security stuff, you can isolate the memory pools or you can
enforce ACLs and monitor for any anomalous access patterns and stuff. The tools have been getting
better out there. Then interoperability standpoint, not all CXL devices really identify the same. If you've
got any consortium-certified devices and you run compliance tests across your different PCIe Gen 6
lanes, then you're pretty much guaranteed to be working. CXL's biggest strength is its flexible memory
sharing is what it comes down to. You can use it for CPUs, GPUs, ASICs, anything, FPGAs, stuff like that.
You just need to coordinate between the hardware, firmware, and the orchestration layers really well.
The promise of CXL is playing out, but I would say that from an inferencing standpoint, it's really going
to benefit.

Analyst:
From a SerDes front, 224G is the workhorse right now. I feel like there are debates around whether or
not we see a jump to 400G-type SerDes or optics as we think about next-gen devices. What are the puts
and takes as you think about the likelihood of whether or not 400G becomes the next workhorse
SerDes or if SerDes starts getting attacked by optics over time?

Specialist:
These are great questions. You clearly have done your homework. This is one of the more technical
interviews that I've ever had in quite some time. The coffee is still sitting in. With SerDes, if you want to
move from 112G PAM4 to 224G PAM and things like that, that is what's going to give you 800G and 1.6T
Ethernet with fewer lanes, smaller die, lower power, things like that. I've seen a lot of progress being
made with LPOs. The big benefit of that is you're bypassing the SerDes bottleneck whatsoever. Frankly,
you don't really have to worry about power or you don't have to worry about latency at scale, too. SerDes
is like copper is what it comes down to it. SerDes over copper will definitely hit reach and power walls
beyond anything four metres vs with LPOs. DSP-free optics is what it comes down to. They're 40% less
power than a retime SerDes. There you have to power the retimer, too. I will say latency optics
completely avoid retimer delays. They are definitely better for retiming and better for inferencing, sorry,
and for memory coherence.

SerDes, honestly, its sweet spot is I'd say it's even less than four metres. It's more like two metres or
less. AECs with SerDes are very cost-effective, very mature. Anything from a PCIe compatibility
standpoint and with CXL compatibility, SerDes, it's very tightly coupled, but that's why it shines really
well. If you look at going forward, I think you're going to see a hybrid approach where you can do PCIe
Gen 6 over optics and you can combine SerDes PHYs with optical DSPs. UALink, though, is very optics
friendly and using any Ethernet PHYs that support LPO or CPO modules out there. AI pods will still
probably use SerDes going in the future, but only for intra-rack within that kind of two-metre stuff. Two
metres, man, I can outstretch my arm and that's two metres right there, too. When it comes down to,
that's not really far, especially within a rack. If you're going to top of the rack, the bottom of rack, that's
five metres right there, four metres. That's why it just doesn't scale is what it comes down to.

Analyst:
For Astera Labs on the optical gearbox side of things, can you explain that? It's relatively new. I think
it's a corner case for the time being. Can you explain where the optical gearbox comes into play? Is
Astera doing anything overly differentiated on that front?

Specialist:

Private and confidential

15

AI Data Centre Industry & Astera Labs 每 Chief Architect at a US-based Technology Firm 每 29 July 2025

How to explain this? You seem pretty technical. I won't boil it down too much. If I had to explain it to my
15-year-old, then I'm sure she'd be like, "Dad, this is way over my head." It's basically a purpose-built
silicon bridge that lets you do seamless connectivity between a PCIe 6 and a PCIe 5 device. The reason
that's important is that some of our older PCIe 5 stuff, which isn't actually that old. It's like 1.5 years old.
If you need to use it for AI and things like that, if you've got next-generation infrastructure, that way
you don't have to rebuild the whole pod or rebuild the whole cluster, you can use next-generation
infrastructure together. Doing protocol bridging between flip mode and between non-flip mode, but
also having full bandwidth is really the benefit of that optical gearbox. The nice part there, too, is like I
said, you're not doing a whole USD 350m investment. You can basically say, "Hey, we've got some older
1.5 years equipment. If you do PCIe over optics and things like that, you can have rack-to-rack and road-
to-road GPU clustering." That's the big benefit of it. It avoids bottlenecks. It maximises your lane
utilisation. You get disaggregated GPU technologies, you get even lower latency with optical
interconnects.

Frankly, from a telemetry standpoint, you just get better uptime and fault isolation, because in the past,
you had to go all PCIe 5 or all PCIe 6. Really, what's special about there is it's the first PCIe gearbox that's
optimised for AI workloads, optical media and Cosmos, it's all software defined, too. You can do protocol
state transition, you can do field upgrades, things like that. It actually has its own built-in analyser, too.
You can do transmission lane margining, you can do error reporting, and it works across a whole bunch
of different PCIe devices, too, so you're not really locked into their ecosystem. You can do it with open
standards, too. Getting back, I described it as a bridge. It's not just a bridge. It's a smart optical aware
interconnect fabric.

Analyst:
On the power distribution side of things, Nvidia is moving to this 800V HVDC architecture. It's going to
be a separate power rack. To what extent are we going to see a pretty decent increase in wide bandgap
products such as SiC [silicon carbide] and GaN [gallium nitride] vs pre-Rubin power distributions? Is it
going to be meaningfully more non-silicon vs silicon-type power components or a gradual transition?
Do players such as Navitas or on the SiC side of things such as Onsemi or Infineon, have the
opportunity to take some incremental share from more silicon pure plays such as TI [Texas
Instruments] or Monolithic Power, within the AI data centre?

Specialist:
It really is, honestly, HVDC, it is a radical rethinking of the way that you do, do architectures within the
data centre, too. It's like a traditional 54V DC. Honestly, what it comes down to is you've got 200kW at
the rack level. I've seen some of the specs of the 800V HVDC, they want to bring up to a full megawatt
down to the rack level, which to me＃ I don't know, I've seen people lean on racks before and I'm like,
"What are you doing? Don't lean on that." 1MW of power going through one rack, that would scare me.
The big benefit of HVDC, though, is when it comes down to it, you're reducing the amount of copper you
have for power distribution by up to 45%. From a 45% standpoint, you look at just the sheer amount of
power that goes to racks, that is a huge cost savings there. From an efficiency standpoint, you don't have
to have a whole bunch of transformers doing AC to DC conversion. That's the way that we traditionally
do upgrades and whatnot are pretty incremental. This is more of a direct rid-to-rack conversion and
then not having to do it.

Then from a cooling standpoint, any of those PSUs that you've got on a rack, those generate a lot of heat,
and we've got to cool those down using localised cooling or liquid cooling and things like that. If you
have centralised conversion, you're already inherently going to reduce the heat. If anything, frankly,
from a semi standpoint, with GaN and with silicon carbide, the big benefit of those two is that GaN
supports up to 650V and then silicon carbide honestly supports up to, I think it's like 6,500kV and things
like that. You're going to see grid to 800V DC conversion, high-power rectifiers, things like that. With

Private and confidential

16

AI Data Centre Industry & Astera Labs 每 Chief Architect at a US-based Technology Firm 每 29 July 2025

GaN, you basically have secondary DC to DC conversion inside of the rack. That gives you higher
switching speeds. It's going to give you definitely smaller, more efficient PSUs. You're going to have a lot
lower conduction losses. We lose a lot of power and a lot of heat with conduction. Then frankly, from a
longevity and a durability standpoint, you're going to have a longer lifespan, which means reduced
maintenance because a lot of those AI clusters and things like that, we're rebuilding them every 1.5-2
years just to have to do upgrades and things like that.

If I can be guaranteed from a power standpoint that I won't have to rebuild and the equipment is much
more durable, then yes, it's going to last longer, and we can see more ROI from it, too. Strategically,
you're looking at scalability, you're looking at sustainability from a copper standpoint because copper is
pretty expensive right now. Then from a scalability stuff with Rubin and the Rubin Ultra GPUs, you're
going to have the ability to support full Kyber racks and things like that, too. A lot of what silicon carbide
and GaN, they are designed for future-proofing, too, that once you get to 1MW and beyond racks, which
scare me even more, that's where 2027-28, you're going to see 1GW-scale AI factories. That's what
we're really trying to build towards, but still 1GW-scale building, that's a lot of power. Right now, the
biggest bottleneck is still energy and the ability to get energy. You can design out megawatt scale racks
and whatnot. If you don't have enough power going into the data centre, then that's still going to be the
choking point.

Analyst:
Power stages are super important, especially because we've got hundreds of different power stages in
Blackwell, and that's only going to continue to increase with Rubin. I've also heard, though, that the
ability to be able to sell both the controllers and the power stage is becoming increasingly important
because at a point of failure, there are a lot of fingers at Monolithic Power, TI is going to point fingers
at someone else and say that it's not the power-stage controller. There's a desire to have a single
throat to choke. Is that true? If so, are any vendors missing one piece of the two-piece puzzle? For
example, Onsemi's power stage is pretty decent, but they're still in the process of developing more
quality controllers and maybe that will come. Maybe it will not be in time. Is that a dynamic that I
should be aware of in your mind, that you'd want the ability for the vendor to be able to do both? Is
there anyone on or otherwise that doesn't have that just now?

Specialist:
I can't comment on individual vendors. You've got Flex, you've got Rohm, you've got Navitas. They're
doing rack-integrated power shells and stuff like that and converters. Power stagers in general, they
give you wide-bandgap semiconductors, which will help you with switch losses and have more high-
efficiency converters, vertical power delivery, set systems, capacitive energy storage systems, things
like that. When it comes down to, at all the different stages, going from the grid down to the individual
chip, you've got the grid input, you've got substation conversion, you've got rack-level distribution,
you've got any of the intermediate bus conversion point of load. As you are going from the grid directly
to the chip, there's a lot of different power stages there. I think vendors, if they had more singular
solutions, that's easy. Of course, they're more than happy to sell as many different transformers and all
kinds of like boards and voltage regulators and things like that, too.

When it comes down to it, every time you go from one stage to another, you're going to have a loss is
what it comes down to. With less loss, you would have less heat and less cooling costs. The energy we use
is just obscene as it is. If you had, I would say, more modular stages that would allow you to have better,
more flexible rack design and would support those 1MW densities, those would be ideal. Frankly, I
haven't seen anyone that's really doing it. I've seen plans for it, but I haven't seen anyone that's doing it
just now.

Analyst:

Private and confidential

17

AI Data Centre Industry & Astera Labs 每 Chief Architect at a US-based Technology Firm 每 29 July 2025

There's been a lot of fast-moving developments, and I'm sure it's not going to slow down too much.

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

18



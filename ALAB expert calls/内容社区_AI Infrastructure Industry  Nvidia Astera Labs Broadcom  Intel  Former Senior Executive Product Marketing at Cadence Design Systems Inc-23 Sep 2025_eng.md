CLIENT-LED

65d0d6538a8911da05d11de9b49cc840996c80c0

AI Infrastructure Industry 每 Nvidia, Astera
Labs, Broadcom & Intel 每 Former Senior
Executive, Product Marketing at Cadence
Design Systems Inc

Consultant | 23 September 2025

Specialist Background

> Over 20 years' experience in the AI infrastructure industry, with strong knowledge of key players

such as Nvidia, Astera Labs, Broadcom and Intel

> Well-placed to discuss the AI infrastructure industry's update, the AI Infra Summit, as well as

OpenAI's announcement and what it means to the custom ASIC (application-specific integrated
circuit) TAM

> Well-versed in Nvidia's dominance in the GPU space and Rubin CPX, a dedicated inference

GPU, as well as the Nvidia-Intel partnership

Contents

On the Intel-Nvidia collaboration, as I think about it from the server side of things, it's the first
foray into enabling x86 with NVLink via NV Fusion. Previously, there was some cynicism
around the likelihood that hyperscalers really would care too much about NV Fusion, largely to
do with the fact that to have their own custom ASIC [application-specific integrated circuit],
whether it's Trainium, TPU [tensor processing unit] or MTIA [Meta Training and Inference
Accelerator] or Maia and all those kinds of things that might be working behind the scenes,
you'd still need the Arm-based CPU. Does anything change in your mind as it relates to
hyperscalers as opposed to enterprise customers looking to adopt this future flavour of rack-
scale solution that would come with a custom Intel x86 CPU, and then presumably it would be
an Nvidia GPU with NV Fusion?

5

AI Infrastructure Industry 每 Nvidia, Astera Labs, Broadcom & Intel 每 Former Senior Executive, Product
Marketing at Cadence Design Systems Inc 每 23 September 2025

Let's say Amazon were to go to Intel and look for a custom 86 CPU that would be integrated
with their Trainium accelerator, I don't think that NVLink enablement would be possible in that
instance because it would have to be an Nvidia GPU. Is Intel doing a customised CPU enough to
make Amazon, for example, shift its roadmap, or is the main goal to ultimately use their own
accelerators? If there's no NVLink enablement in that case, how does that change how they
think about when we get to '27 and '28, whether or not they go with something more akin to
Graviton plus Trainium plus a non-Nvidia fabric vs now they've got the option to do their CPU
with their accelerator and NVLink or an x86 custom CPU with an Nvidia GPU and NVLink? Is
NVLink the main thing that is important here, and so I should think that it will be something
that goes the NVLink route from a scale-up networking standpoint, or do you still think there's
room for things like scale-up Ethernet with Tomahawk Ultra or UALink eventually? How does
that impact those initiatives on the networking side of things?

Do you think that the main thing we need right now is actual UALink switch silicon, whether it
comes from Astera Labs or I saw Auradine spun out the Upscale AI? A couple of companies are
working on the actual switch silicon element of it. I imagine you can't really have a product out
in the market until you have the actual switch chip itself. Is that the main bottleneck present-
day, as you think about momentum around UALink?

Astera has just the higher-lane PCIe switch, the X-Series scale fabric switch, it has the PCIe
[peripheral component interconnect express] elements of it, but is lacking the UALink
dynamics that will make it more NVLink in nature. Is there a big lift to go, in your mind, from
an X-Series to a UALink switch chip? Are you worried that Astera won't be able to actually keep
something out of quality?

Amazon is adopting the X-Series for Trainium3, which is the first programme, which is more
like PCIe. I feel like that is well-understood as a Band-Aid solution until you get to the second
programme, where you get the full benefits of the Ethernet dynamics within the UALink
standard itself. Now that we've got scale-up Ethernet with the ecosystem built around it for
Tomahawk Ultra, you could still just go with Nvidia GPUs and NVLink or you could wait around
to see what this Intel plus NV Fusion situation will be. Do you think that the X-Series chip has
much potential to get any other uptake outside of just Amazon or are most of the broader
hyperscalers going to take the wait-and-see approach, and when they get to '27, maybe they'll
experiment with NVLink and scale-up Ethernet, but not X-Series PCIe? That will put Astera
behind a little from a learning perspective. How do you think about how some of the
hyperscalers outside of Amazon might be setting themselves up in preparation for 2027, which
I think opens up the optionality of how you can go about constructing your AI clusters?

ByteDance, for example, are partnered with Broadcom from an ASIC perspective. Do you think
taking ByteDance, but also some of the other ASIC partners that already have been established
from a front-end design perspective, does that become an issue for Astera Labs where if you're
working with someone from a front-end silicon design standpoint that they're going to try to
push what they'd prefer you to use from a scale-up networking perspective and that would
dampen the opportunity for Astera if, say, ByteDance is working with Broadcom, or Google is
working with Broadcom or just extending that exact dynamic, does that limit the likelihood
that they'll have any interest in Astera's product?

Private and confidential

6

7

7

8

8

2

AI Infrastructure Industry 每 Nvidia, Astera Labs, Broadcom & Intel 每 Former Senior Executive, Product
Marketing at Cadence Design Systems Inc 每 23 September 2025

I think it was late last week that everyone knew that Auradine had been working on that, and
then they formalised it around this Upscale AI spin-out. They got some funding. There's no
strategic funding, which I thought was. Qualcomm Ventures, you could quasi-count as strategic
funding, but not any big players backing them. On Upscale AI, is this a distraction or should I
continue to pay attention to them in this landscape?

If I'm potentially getting the chance to chat with Rajiv, probably not for a handful of weeks,
because they've been busy with launching Upscale AI formally. If you had a couple of key
questions, what would you be asking?

For legacy Innovium, I feel like with all these start-ups, there's usually a couple of hyperscalers
that really back some of these companies. Is there a hyperscaler that stands out that legacy
Innovium had a pretty close relationship with that Rajiv could maybe carry over?

How are you thinking about what Nvidia might be liking that they saw from Enfabrica? They
didn't take the chip. It wasn't the chip, but there are some interesting things they're doing
around. They were both Ethernet and PCIe. That plays well for all the reasons we talked about.
There are also some elements around CXL [compute express link], but I don't know if it will be
that. Right now, it seems like it's mostly from a scale-out perspective, but I don't know. How
are you thinking about what likely drove Nvidia to be interested enough to bring Rochan and his
team on board?

On the memory fabric for CPU, I know Enfabrica was exploring CXL. Is that what you're
expecting that fabric to be based on? I feel like we've been in the CXL hype cycle for probably
going on 10 years now, or do you think it will be something different?

Rubin CPX got announced at the AI Infra Summit. It's an interesting take on first token
inferencing and eliminating the KV [key-value] cache bottleneck that has existed. I feel like a
lot of the hyperscalers' efforts around custom ASICs have been tuned specifically to their own
inferencing workloads. Do you think that Rubin CPX answers some of those challenges?

We've got the OpenAI announcement with Nvidia, 10GW of capacity, probably [billions of
dollars] worth of accelerator and system revenues that might be associated with that. I feel like
the industry outside looking in has been hotly debating which ASIC provider OpenAI might go
with. I do think that there are still opportunities for OpenAI to take a bit of a heterogeneous
approach because, if you believe Sam Altman, [billions of dollars] is leaving plenty of room for
the trillions of dollars he plans to spend. All of it taken together, how do you think about this
OpenAI announcement and what it means to the custom ASIC TAM?

I feel like people are most concerned about probably two main things. One is that the custom
ASIC TAM shrink is based on all the stuff that we heard over the last month or so, primarily
from Nvidia. I think the other one is that NVLink has increased its chances of becoming a de
facto standard for the connectivity piece of the AI cluster. As a result, the PCIe ecosystem might
be facing some significant pressures moving forward. On those two fronts, is there anything
that you feel like I might be missing that would help debunk those concerns, or do you think
they're reasonable concerns?

Private and confidential

9

9

10

10

11

11

11

12

3

AI Infrastructure Industry 每 Nvidia, Astera Labs, Broadcom & Intel 每 Former Senior Executive, Product
Marketing at Cadence Design Systems Inc 每 23 September 2025

Do you think that there is a level of diversity of HPC [high-performance computing] and AI
accelerator design work that is pushing to the most leading-edge nodes, or is 10 maybe a
misdirection, that not all the 10 are really going to matter? How are you thinking about the
diversity of demand for AI accelerators?

We're at 224G SerDes [serializer/deserializer] right now. I feel like there's a lot of debate
around whether or not optical can overtake things at 448G or 448G SerDes adoption will even
exist because of all the work done around optical. How do you feel about where we're at from a
pricing and cost, but also a reliability standpoint, on the optical side of things? Is it something
beyond 448G that optical really starts to matter?

Hock Tan commented that Ethernet-based active electrical cables are only in existence because
customers still use lower-quality SerDes. If you use high-quality SerDes that AECs [active
electrical cables] are not necessary. How do you think about the durability of the AEC market,
considering that dynamic?

I feel like Astera has had a tough go from a content story perspective with anything Nvidia-
related, and it feels like this Intel custom CPU with an Nvidia GPU is further deflationary for
both their retimer content as well as that head node switch chip that they have for P-Series,
because customers might just customise less. Do you think that the Intel-Nvidia partnership is
a further negative for Astera and beyond just the X-Series part of it?

What do you think about their trajectory, Astera Labs, from here? It seems like it got a lot more
challenging.

Do you think the optics and DSP [digital signal processing] market is just much more
competitive? Do you think it's likely that they replicate their success they saw in retimers in any
product category in the future?

Talking about the end of last year, everyone thought 2025 would be the peak growth year of AI.
Towards the end of this year, I feel like people are thinking '26 is going to be the growth peak of
AI. How are you thinking about the durability of AI demand, especially considering some of the
big announcements we've seen across a lot of the hyperscalers lately?

If you think about a specific technology where the industry is still debating on what the right
approach is going to be, it's CPO [co-packaged optics], scaled networking. Thinking about
liquid cooling introduction, just if you picked a technology that you think is most debated that's
going to have the biggest impact on what the trajectory of the landscape ends up being, what
would you say I should isolate down to one or two of those to really dig in to try to understand
the moving pieces and try to formulate a view on where the industry actually goes?

12

13

14

14

14

15

15

16

Private and confidential

4

AI Infrastructure Industry 每 Nvidia, Astera Labs, Broadcom & Intel 每 Former Senior Executive, Product
Marketing at Cadence Design Systems Inc 每 23 September 2025

AI Infrastructure Industry 每 Nvidia, Astera
Labs, Broadcom & Intel 每 Former Senior
Executive, Product Marketing at Cadence
Design Systems Inc

Transcription begins

Analyst:
I focus on a lot of the AI plays. I think since the last time we chatted, we've had Hot Chips, we've had AI
Infra Summit, and then there's been a series of announcements by Nvidia and a few others. Really just
hoping to get your updated thought process around some of the dynamics that we've been digging into
in the past as it relates to custom vs third-party merchant GPUs and what the scale of networking
dynamic might look like and all of the peripheral componentry around there.

On the Intel-Nvidia collaboration, as I think about it from the server side of things, it's the first foray
into enabling x86 with NVLink via NV Fusion. Previously, there was some cynicism around the
likelihood that hyperscalers really would care too much about NV Fusion, largely to do with the fact
that to have their own custom ASIC [application-specific integrated circuit], whether it's Trainium,
TPU [tensor processing unit] or MTIA [Meta Training and Inference Accelerator] or Maia and all those
kinds of things that might be working behind the scenes, you'd still need the Arm-based CPU. Does
anything change in your mind as it relates to hyperscalers as opposed to enterprise customers looking
to adopt this future flavour of rack-scale solution that would come with a custom Intel x86 CPU, and
then presumably it would be an Nvidia GPU with NV Fusion?

I don't think much has changed from my perspective as it relates to hyperscaler incentives to go this
route. Based on initial industry reactions, whether or not the status holds true that NV Fusion is maybe
not something that hyperscalers are considering or if this development might make it more worthwhile
to dig into and potentially deploy at the time that those products would become available.

Specialist:
This whole integration of Intel with Nvidia is a game-changer for Intel and even for Nvidia as such
because whatever said and done, there is still Intel servers being deployed in the industry. By having this
collaboration and putting the RTX GPUs inside the Intel desktops and Intel CPUs, it basically gives a path
for Intel CPUs to talk to the Nvidia fabric or the Nvidia mesh through the NVLink. If I'm not mistaken,
the RTX GPU does support NVLink to connect both these GPUs together to get a better performance. This
also creates a doubt of Intel's plans to make their own GPU. Intel has a programme called as Jaguar
Shores which is in public domain. It puts us in a puzzle that if this is the case that they are going with
Nvidia today for the CPUs [sic], then what happens to the future of Jaguar Shores? Are they completely
giving up on implementing Intel-based GPUs? Intel has been struggling in the GPU space for a couple of
few years, if you noticed. They haven't really come up with a very strong message on the GPU side of the
story. That is one aspect of it, but this is just the beginning of engagement where Nvidia's dominance in
the GPU space is now going beyond the Nvidia domain.

It's proliferating into the x86 domain as well with Intel as the beginning. Then what happens to AMD as

Private and confidential

5

AI Infrastructure Industry 每 Nvidia, Astera Labs, Broadcom & Intel 每 Former Senior Executive, Product
Marketing at Cadence Design Systems Inc 每 23 September 2025

a GPU vendor because AMD is talking about UALink, is talking about their MI400 and the future 500.
That also puts in a doubt because ultimately, AMD is also on an x86 architecture. It'll be putting an
immense pressure on AMD that should they be also collaborating with Nvidia and Nvidia being the
dominant player in the industry for GPUs taking over both of these players, Intel and AMD. It's a very
strategic move on part of AMD. Intel being Intel and it's struggling financially, it gives them a boost that
now with the collaboration with the strongest GPU vendor, they have a path to play in a better or a bigger
space where they were not being considered previously. Also, it puts a doubt in the space of hyperscalers
that if Intel is flexible of putting Nvidia GPUs inside their CPUs, is Intel open to do custom hyperscaler
accelerator inside their CPU? As an example, tomorrow, the likes of Amazon or Google can go to Intel
and tell them, "Okay, guys, this is my part of accelerator, which is unique to my workload, which my
architects have designed. I'm willing to buy thousands of your CPUs per year, but I want this accelerator
to be integrated inside your CPU."

What is the reason why these customers today, the hyperscalers are making their own CPUs? They are
making their own CPUs not because they are saving any money out of it, but they're making the CPUs
because it's optimised to their workload. It gives them superior performance. Plus, they are optimising it
for the power and performance. They don't need some generic CPUs to run over there, which is not
optimal for their workload. Either it's underutilised or over-utilised. Adding their accelerator in an Intel
CPU gives them the path that they don't have to take the heavy-lifting of manufacturing, designing and
doing all the stuff with ARM. If Intel meets their requirements and puts their accelerator inside their
CPU, they should be open to it. It's a complete different domain. I think so the Intel management has
realised that they cannot keep the doors locked to Intel Inside and they have to open up to the new
paradigm in the industry where the CPU is governed by the hyperscalers and the workloads what they
are using.

Analyst:
Let's say Amazon were to go to Intel and look for a custom 86 CPU that would be integrated with their
Trainium accelerator, I don't think that NVLink enablement would be possible in that instance because
it would have to be an Nvidia GPU. Is Intel doing a customised CPU enough to make Amazon, for
example, shift its roadmap, or is the main goal to ultimately use their own accelerators? If there's no
NVLink enablement in that case, how does that change how they think about when we get to '27 and
'28, whether or not they go with something more akin to Graviton plus Trainium plus a non-Nvidia
fabric vs now they've got the option to do their CPU with their accelerator and NVLink or an x86
custom CPU with an Nvidia GPU and NVLink? Is NVLink the main thing that is important here, and so I
should think that it will be something that goes the NVLink route from a scale-up networking
standpoint, or do you still think there's room for things like scale-up Ethernet with Tomahawk Ultra
or UALink eventually? How does that impact those initiatives on the networking side of things?

Specialist:
A good question again. The NVLink dominance will be restricted to only the Nvidia side of the GPUs,
irrespective to whether it's Amazon or Google or any organisation. How much ever they try, they want to
basically limit their dependency on Nvidia GPUs to the NVLink to the bare minimum. They have a whole
back-end network, which is the non-Nvidia GPUs because Nvidia GPUs are extremely expensive for
these organisations. When they're building their own XPUs, they are exploring today two parts. One is
the UALink, and other one is the Ethernet scale-up. Ethernet scale-up has got more legs to run. In the
coming few months and I would say one year or so, the Ethernet scale-up will be one of the dominant
factors for two reasons. Number one is because already the Ethernet deployment is already existing in
this infrastructure. Number two, the dominance of players like Broadcom who are really pushing the
envelope to adopt to Ethernet scale-up and not to look at the UALink. UALink by construction is an
accurate protocol much better than Ethernet scale-up. It's in line with NVLink. I think so we discussed
this before also. It basically truly is on the memory semantics what you need, but the problem with

Private and confidential

6

AI Infrastructure Industry 每 Nvidia, Astera Labs, Broadcom & Intel 每 Former Senior Executive, Product
Marketing at Cadence Design Systems Inc 每 23 September 2025

UALink is the ecosystem. For some reason, AMD lost the focus or they did not put the full attention on
the whole stack enablement of UALink.

Today, the UALink ecosystem is extremely weak. The spec is there, but there is no solution outside.
There is no GPUs on UALink. There is no switches on UALink. If these two combinations are not there,
it's just a paper tiger, however good it is. Because of the lack of ecosystem and Broadcom dominating the
Ethernet side and coming up with products today and also the hyperscalers who are building their own
XPUs, they are more comfortable on the Ethernet side of the stuff because they have the domain
expertise and the investments already on the Ethernet side. If you ask my opinion, the scale is a little bit
more heavier on the Ethernet side unless and until AMD comes quickly and hits back and says, "Here is a
full solution, here is the whole rack," which AMD positions it only to happening in 2027. In the AMD AI
Day [sic], the Helios rack and the other aspects of what they showed, today, as an example, it's really
abnormality in the industry, the Helios rack is actually running UALink over Ethernet. It is over
Ethernet.

That's a little bit of a shame that you position UALink, but you're still deploying it commercially over
Ethernet. That gives Ethernet over scale-up a testimony that, "Hey, guys, I'm still there. What are you
talking about? The UALink protocol, what you're talking about, today is running on Ethernet." It's
basically fabricated on Ethernet fabric. That is something where I think so AMD has lost the shine and
they have really not outlasted the Ethernet side of stuff in spite of having such a good solid protocol for
UALink. Plus there are hyperscalers who endorse UALink, but they have not come forward with the
product line with UALink. There's Meta, there is Amazon who are part of the Consortium. As a matter of
fact, even Apple is a member of the UALink Consortium, but nothing has come out of these members.

Analyst:
Do you think that the main thing we need right now is actual UALink switch silicon, whether it comes
from Astera Labs or I saw Auradine spun out the Upscale AI? A couple of companies are working on the
actual switch silicon element of it. I imagine you can't really have a product out in the market until you
have the actual switch chip itself. Is that the main bottleneck present-day, as you think about
momentum around UALink?

Specialist:
Yes, I strongly believe that that is the requirement, yes.

Analyst:
Astera has just the higher-lane PCIe switch, the X-Series scale fabric switch, it has the PCIe [peripheral
component interconnect express] elements of it, but is lacking the UALink dynamics that will make it
more NVLink in nature. Is there a big lift to go, in your mind, from an X-Series to a UALink switch
chip? Are you worried that Astera won't be able to actually keep something out of quality?

Specialist:
There are two things. Fundamentally, what Astera has is a Gen 0 of UALink, which is based out of 128G.
There are two programmes which Astera Labs is trying to target right now. First one of them, I think so
they doing it for one of the hyperscalers, which is the Gen 0 of the UALink. It is basically based out of
PCIe flip-based design, and that is a 256-byte FLIT, and it operates at 128G speed of the I/Os, which is
PCIe Gen 7 speed. That's number one product line. That will be used only for hyperscalers. It cannot be
used as a UALink switch. The second product line, what they're doing is a dedicated UALink switch for
the likes of industry, AMD and other customers. That is basically a 64-byte FLIT design. It uses 200G I/
Os, and it's basically a complex design. This will be the first time where Astera Labs is jumping from
their comfort zone of PCIe to Ethernet because 200G is in the Ethernet domain, and this is the UALink 1.0
spec.

Private and confidential

7

AI Infrastructure Industry 每 Nvidia, Astera Labs, Broadcom & Intel 每 Former Senior Executive, Product
Marketing at Cadence Design Systems Inc 每 23 September 2025

I'm not discounting them, but it is not going to be a smooth ride because whenever you have a leap of
200G or in that domain, there is a lot of learning associated with the design, with the I/O technology
associated with it. It will be something to watch out for, but again, Astera Labs and their management
are pretty strong enough. They have a good dedicated team of engineering talent. They should be able to
pull it off, but as I said, it's not a piece of cake that they will take it because they don't have an actual
switch expertise. They were good in the PCIe domain, but now they are moving their domain from PCIe
switching to Ethernet switching, which is something unique and new to them. They are entering into the
territory of the Broadcoms, the Marvells, the Ciscos who are dominant into the switching space.

Analyst:
Amazon is adopting the X-Series for Trainium3, which is the first programme, which is more like
PCIe. I feel like that is well-understood as a Band-Aid solution until you get to the second programme,
where you get the full benefits of the Ethernet dynamics within the UALink standard itself. Now that
we've got scale-up Ethernet with the ecosystem built around it for Tomahawk Ultra, you could still just
go with Nvidia GPUs and NVLink or you could wait around to see what this Intel plus NV Fusion
situation will be. Do you think that the X-Series chip has much potential to get any other uptake
outside of just Amazon or are most of the broader hyperscalers going to take the wait-and-see
approach, and when they get to '27, maybe they'll experiment with NVLink and scale-up Ethernet, but
not X-Series PCIe? That will put Astera behind a little from a learning perspective. How do you think
about how some of the hyperscalers outside of Amazon might be setting themselves up in preparation
for 2027, which I think opens up the optionality of how you can go about constructing your AI clusters?

Specialist:
I think so that X-Series initially will be for Amazon. They have a dominant engagement with Amazon, to
be honest. Then leveraging that success, they'll try to penetrate more into the APAC territory with the
customers like ByteDance, Alibaba, who are looking into the scale-up using PCIe class of interface
because China doesn't have a full access to the 200G technology, to be very honest. They are restricted
and limited with the current geopolitical situation. Astera can take advantage of that particular
limitation and proliferate their solution with the 128G or the PCIe-based scale-up solution in that
market. I think so in the recent call also, they mentioned that they have about 10 customers or
something like that who are pipeline for their scale-up technology. I do believe at least seven or eight of
them are APAC customers, whereas the bigger hyperscalers will not adopt to that. Because it's very
custom and limited, they will directly go to the scale-up Ethernet at 200G or the UALink at 200G.

Analyst:
ByteDance, for example, are partnered with Broadcom from an ASIC perspective. Do you think taking
ByteDance, but also some of the other ASIC partners that already have been established from a front-
end design perspective, does that become an issue for Astera Labs where if you're working with
someone from a front-end silicon design standpoint that they're going to try to push what they'd
prefer you to use from a scale-up networking perspective and that would dampen the opportunity for
Astera if, say, ByteDance is working with Broadcom, or Google is working with Broadcom or just
extending that exact dynamic, does that limit the likelihood that they'll have any interest in Astera's
product?

Specialist:
The good part of the Astera product line is if that particular custom ASIC has a PCIe port, a PCIe Gen 7
port, then the Astera solution just is a plug-and-play and they can get the leverage of the scale-up using
that architecture. It doesn't require any special ingredients coming from Astera to enable that interface.
They just need a standard PCIe Gen 7 port on that design. Irrespective to whether the ASIC is being done
by Broadcom or any other ASIC vendor, if the ASIC vendor is smart enough and incorporates a PCIe port

Private and confidential

8

AI Infrastructure Industry 每 Nvidia, Astera Labs, Broadcom & Intel 每 Former Senior Executive, Product
Marketing at Cadence Design Systems Inc 每 23 September 2025

without telling all the details to Broadcom, why and all the stuff, he should be able to comfortably design
and use Astera Labs, but on the other side of the spectrum, then he is currently locked and tied to Astera.
That gives Astera a lot of leverage that there's no other alternative solutions today, and Astera, it'll be
completely a semi-proprietary type of interface because it was the Gen 0 of UALink which nobody
adopted, and Astera took it because they had this lead customer who wanted them to build it.

Again, coming back to my previous point, since the UALink ecosystem is so weak, there aren't many
players who have shown a commitment to come up with a solution today, except Astera and Auradine
and some other vendors. Astera, being the first, gets the advantage of the first-mover advantage. They
can lock those accounts and accelerate their path to a very healthy revenue coming from a scale-up
solution. Plus they don't have the Ethernet expertise. They will be in a spectrum where there is Ethernet
scale-up through Broadcom and others like Marvell and Cisco. Then there will be a PCIe-based scale-up,
which is coming from Astera Labs. The Ethernet-based scale-up is not going to dominate in China
because of the I/O limitations, which I mentioned to you before. They just do not have the access to that
I/O. For them, Astera solution is the most viable solution at a very economical price.

Analyst:
I think it was late last week that everyone knew that Auradine had been working on that, and then they
formalised it around this Upscale AI spin-out. They got some funding. There's no strategic funding,
which I thought was. Qualcomm Ventures, you could quasi-count as strategic funding, but not any big
players backing them. On Upscale AI, is this a distraction or should I continue to pay attention to them
in this landscape?

Specialist:
I really don't know, but don't they have funding from Mayfield and all those stuff? I thought they had
funding even from Mayfield.

Analyst:
Yes, they do. I meant more like there weren't really any strategic companies that put up some money
alongside or at least that wasn't part of the press release.

Specialist:
Honestly, I am puzzled as well because there's too many stuff in that Auradine, then there was
AuraLinks, and then now there is Upscale AI, and then within Upscale AI, there are different ventures. I
think so Rajiv is the one who is the president of all these companies and orchestrating it. He was the
previous CEO of Innovium as well. I wouldn't discount him. He does have the switching expertise and he
has taken a successful switch company and incubated it. I don't have much to say. There aren't many
players in scale-up, and he is the only one start-up which is showing up. Astera is not a start-up. It's a
well-established company. For Upscale to start doing things from scratch, doing the system, doing the
software, it's not easy for start-up companies to do switching as a matter of fact. If you notice, there
hasn't been a successful start-up which has gone IPO with just a switching technology. You can look at
the examples of Barefoot. It was acquired by Intel. Innovium was acquired by Marvell. Overall, anything
with the switching start-up stuff, it's a very daunting and a very big task to undertake for a start-up to
get switching done and get everything in the stable zone.

Analyst:
If I'm potentially getting the chance to chat with Rajiv, probably not for a handful of weeks, because
they've been busy with launching Upscale AI formally. If you had a couple of key questions, what would
you be asking?

Specialist:

Private and confidential

9

AI Infrastructure Industry 每 Nvidia, Astera Labs, Broadcom & Intel 每 Former Senior Executive, Product
Marketing at Cadence Design Systems Inc 每 23 September 2025

Key question for them is basically the main part of the switch is the I/O technology. Where are you
getting this I/O technology from? Who's enabling you for your I/O technology to be successful? The
number two is basically you're dealing with 200G I/Os and you will be having hundreds of them on your
design. In terms of the ASIC capability, do you have the right expertise to do such a complex ASIC and get
it out? That's number two. Number three is the whole issue of scale-up is memory semantics. It is very
intensive in terms of latency and software. How do you manage that challenge that you will be able to
succeed and you will be able to get it?

Number four is a very important question that you're putting entire bets on UALink, whereas the market
is balanced between Ethernet and UALink. What gives you that confidence that you have gone ahead and
invested so much on the UALink camp? Do you have an existing customer or a line of sight where
somebody has signed up with you that they're going to deploy your technology? Because UALink is not
there in the market today. There is no endpoint. There are no hosts. There are no GPUs. There are no
XPUs. It's a big commitment for a start-up to do this without having a handhold or a blessing from
somebody who has given you the path that, "Okay, do it and I will buy it from you." Where is that? Can
you spot some light on that business aspect of it that who is the lead customer for whom you are driving
this for?

Analyst:
For legacy Innovium, I feel like with all these start-ups, there's usually a couple of hyperscalers that
really back some of these companies. Is there a hyperscaler that stands out that legacy Innovium had a
pretty close relationship with that Rajiv could maybe carry over?

Specialist:
I think so Innovium had a strong relationship with Amazon, but right now, Amazon is in the Astera Labs
camp because they've already signed up with them. I really don't know, to be honest.

Analyst:
I was wondering if there was going to be a non-Amazon hyperscaler.

Specialist:
I don't see any non-Amazon guy who signed up with UALink, to be honest. Microsoft is not on the
wagon of doing UALink for sure. Google is on OCS, so they don't need UALink. Those two have gone off
the back. Meta is basically more on the Ethernet side of scale-up because they are completely a
Broadcom house.

Analyst:
How are you thinking about what Nvidia might be liking that they saw from Enfabrica? They didn't
take the chip. It wasn't the chip, but there are some interesting things they're doing around. They were
both Ethernet and PCIe. That plays well for all the reasons we talked about. There are also some
elements around CXL [compute express link], but I don't know if it will be that. Right now, it seems
like it's mostly from a scale-out perspective, but I don't know. How are you thinking about what likely
drove Nvidia to be interested enough to bring Rochan and his team on board?

Specialist:
The problem with Enfabrica was it was basically a SuperNIC, like a Swiss army. Rochan was trying to do
too many things at one time. It came to a point that at the end of the day, they were not having any
customer success and it became a huge problem to solve, given the start-up bench strength what they
had, but they definitely have a good concept. Nvidia was already an investor in that particular
organisation. I'm happy for Rochan that he got the right evaluation and a great exit for him, but on the
Nvidia side, what they're trying to do is they have done the memory fabric for the scale-up with the

Private and confidential

10

AI Infrastructure Industry 每 Nvidia, Astera Labs, Broadcom & Intel 每 Former Senior Executive, Product
Marketing at Cadence Design Systems Inc 每 23 September 2025

GPUs, but they want a similar type of environment for the CPUs. Enfabrica brings that kind of a flavour
where now they can have a memory fabric for the CPUs and then they have a memory fabric for the
GPUs. The GPU memory fabric is through the NVLink. The fabric for the CPUs could be through the
SuperNIC, what Enfabrica is designing. This is very intensive software kind of a project where it requires
a lot of software building up on the system side, and that's where the Enfabrica lacked the gas to get it
done to the final touch-up on their silicon.

With the combination of Enfabrica, Nvidia will be able to explore more on the CPU side with the memory
semantics and memory fabric engagement. That will go very well with the combination of ConnectX,
which they have it through Mellanox, and Enfabrica's domain expertise. Plus Rochan has a good
expertise even on the Ethernet side of switching, having done switching at Broadcom for a long period of
time. That combination will help Nvidia to fuel their stuff. Plus there is a lot of FUT coming from
Broadcom on the Ethernet scale-up side of stuff. Rochan will be able to handle the Broadcom FUT well
enough because he's been seasonal [sic]. He's worked at Broadcom for a good period of time. He knows
how the Broadcom think tank works, and he'll be able to complement that at Nvidia to handle all the, I
would say, positioning what Broadcom has been putting against Nvidia and in the industry as well.

Analyst:
On the memory fabric for CPU, I know Enfabrica was exploring CXL. Is that what you're expecting that
fabric to be based on? I feel like we've been in the CXL hype cycle for probably going on 10 years now,
or do you think it will be something different?

Specialist:
It has to be something different because that CXL thing did not fly, to be honest. It was there for a very
long period of time, and it really did not take off because CXL did not scale to that level. It was limited to
a certain amount of nodes, and there was no software stack. I think so the main problem which lies over
here is the software stack where Nvidia can supplement Rochan to get his dreams and get him to the
finish line because Nvidia has a super-set of software engineers who have been working on this. They
have done Cuda and all those stuff. They will be able to take him to the finish line and get him that vision
what he has on the memory fabric for CPUs.

Analyst:
I'll be curious to see what we might see. It won't be Enfabrica-branded, but I feel like we'll see an
announcement and know that Rochan and his team might have played a role in it.

Rubin CPX got announced at the AI Infra Summit. It's an interesting take on first token inferencing
and eliminating the KV [key-value] cache bottleneck that has existed. I feel like a lot of the
hyperscalers' efforts around custom ASICs have been tuned specifically to their own inferencing
workloads. Do you think that Rubin CPX answers some of those challenges?

Specialist:
Definitely, the Rubin CPX does address those challenges, especially the HBM capacity has increased
significantly in Rubin. Plus Rubin has got more GPU cores inside it. It is taking to the next generation of
their current generation GPUs what they have. I would also add one more element to the Rubin thing
which a little bit surprises me that it is still in the 3nm technology node. In that way, I think so Jensen
and the Nvidia team are still able to extract value from the TSMC 3nm and they didn't have to go to 2nm.
That means they will still have a very healthy margin on their business from the Rubin SoC.

Analyst:
We've got the OpenAI announcement with Nvidia, 10GW of capacity, probably [billions of dollars]
worth of accelerator and system revenues that might be associated with that. I feel like the industry

Private and confidential

11

AI Infrastructure Industry 每 Nvidia, Astera Labs, Broadcom & Intel 每 Former Senior Executive, Product
Marketing at Cadence Design Systems Inc 每 23 September 2025

outside looking in has been hotly debating which ASIC provider OpenAI might go with. I do think that
there are still opportunities for OpenAI to take a bit of a heterogeneous approach because, if you
believe Sam Altman, [billions of dollars] is leaving plenty of room for the trillions of dollars he plans to
spend. All of it taken together, how do you think about this OpenAI announcement and what it means
to the custom ASIC TAM?

Specialist:
If you remember, Broadcom's Hock Tan's update in the recent post. His biggest win is at OpenAI right
now. OpenAI ASIC has been awarded to Broadcom, which they awarded last. I would say, later part of last
year in Q3, they got that design win. They are doing an accelerator at large scale and Broadcom is their
ASIC partner. Addressing your question about ASIC with OpenAI, it's a Broadcom account right now. It's
a pretty huge design win for Broadcom, and that's why Hock was claiming the engagement. Of course, a
majority of the share is OpenAI. There are a few other design wins he has like the Google TPU and all
those stuff, but the biggest mover and shaker is the OpenAI win what they had.

With this engagement of Nvidia, what Nvidia has done is basically taken away some more share of
Broadcom format because instead of them investing more on doing custom ASIC and doing all the stuff,
Jensen basically has given them a sweet deal and forced their GPUs and given them the priority that,
"Don't look outside, don't do anything funky and investing in other things. Just take my stuff, and I will
give it to you and solve your problem." He has taken also some more share from OpenAI. Instead of
OpenAI going to Broadcom and doing more custom stuff, now they are going to even do Nvidia stuff. I
think so going to Nvidia was primarily because of the readiness what Nvidia had to serve them and also
they didn't have to put their bets on custom ASIC to such a high level where their deployments get
delayed.

Analyst:
I feel like people are most concerned about probably two main things. One is that the custom ASIC TAM
shrink is based on all the stuff that we heard over the last month or so, primarily from Nvidia. I think
the other one is that NVLink has increased its chances of becoming a de facto standard for the
connectivity piece of the AI cluster. As a result, the PCIe ecosystem might be facing some significant
pressures moving forward. On those two fronts, is there anything that you feel like I might be missing
that would help debunk those concerns, or do you think they're reasonable concerns?

Specialist:
No, those are reasonable concerns, to be honest. This market is so dynamic, right now, I would say the
silicon semiconductor segment by itself is on steroids. There are so many things happening in terms of
the connectivity, the data centre, the compute segment and the XPU segments, and everybody wants to
differentiate themselves from each other. Of course, there's a full dominance of players like Broadcom
and Nvidia, but there is still a lot of growth for companies to do custom silicon who want to differentiate
themselves from others and the innovation at the pace what is happening, especially on the AI, edge AI
side of stuff that I would say we still have a good 2-3 years of healthy run rate on the silicon side of the
business. I wouldn't say that the custom silicon TAM is shrinking. It's a little bit of a reactive stuff when
people in the market see that the (inaudible) of the AI is still not finalised. People do see sometimes
jitters and when they see their earnings not being aligned, they cut back their investments, but then they
again come back to track after a few months or after a few quarters. Those things are still there, a little
bit of a swing in the pendulum, but the momentum is still there towards semiconductor investment
overall, which is fuelling the industry.

Analyst:
Do you think that there is a level of diversity of HPC [high-performance computing] and AI accelerator
design work that is pushing to the most leading-edge nodes, or is 10 maybe a misdirection, that not all

Private and confidential

12

AI Infrastructure Industry 每 Nvidia, Astera Labs, Broadcom & Intel 每 Former Senior Executive, Product
Marketing at Cadence Design Systems Inc 每 23 September 2025

the 10 are really going to matter? How are you thinking about the diversity of demand for AI
accelerators?

Specialist:
I think so people have not yet still fully gone into the 2nm mode. TSMC themselves are struggling in 2nm
in terms of their overall yield and performance, and they are guiding more folks on what they call it as
the A14 process node what they have. I haven't seen so much of a success in 2nm, except for the guys like
the Apples and the high consumer items which people are buying. Even on the compute side of the
segment, a lot of designs today are being executed in 3nm as well. As you said, the Rubin itself is in 3nm
because it's not just the process aspect of it, but also the scaling that can these devices being. Can they
scale to a commercial deployment range and can you produce them in mass volumes and at proper cost
points? I'm a little bit sceptical on 2nm. I haven't smelled success on 2nm in the industry where people
are boasting about it and saying that, "Yes, I'll be able to do it." That's something which I wouldn't like
to do it. I would say we have to take care of it.

Analyst:
I think ASM International cut its H2 outlook, which I imagine is largely gate-all-around driven, which is
a 2nm downtick on demand. I agree with you that it feels like maybe things aren't as great as a comment
such as customers moving to 2nm would suggest.

Specialist:
As I said, in terms of the infrastructure, even, for example, high-end switching, when you look at the
Tomahawk 6 and all, everything has been done in 3nm, but when it goes to 200Tbit of switching, that
2nm becomes pervasive. When we go to 448G SerDes and high optical connection of 1.6T, you will look
at 2nm. I think so 2nm and beyond or lower will be only. You will see some traction of them in 2027. I
don't see it in '25. I will not see it in '26. You will see 2027 where 2nm product lines will have some kind
of gas in them or steam in them, but other than that, I don't see it.

Analyst:
We're at 224G SerDes [serializer/deserializer] right now. I feel like there's a lot of debate around
whether or not optical can overtake things at 448G or 448G SerDes adoption will even exist because of
all the work done around optical. How do you feel about where we're at from a pricing and cost, but
also a reliability standpoint, on the optical side of things? Is it something beyond 448G that optical
really starts to matter?

Specialist:
Beyond 448G, people will start looking at co-packaged optics because at that point, you lose the gas on
the electrical side for high speed. Your electrical links will not be able to have that much of crosstalk and
noise that it will not be able to sustain the distance. At that point, you'll have to basically go for co-
packaged optics. That's what companies like Nvidia, Marvell, Broadcom are gearing up for the future for
their CPU technologies. That's why you see a lot of photonics companies and photonic start-ups in that
space because we are reaching to the end of the tunnel where you cannot scale beyond. That's happening
on the 448G. 224G will have a very long life. I would say it'll sustain until 2028 and beyond. It'll have a
good 4-5 years of runway. Right now, the designs are being implemented in 224G. Tomahawk 6 is a
224G switching device. Once you have the switching device in 224G, then you will see other peripherals
like the SmartNIC cards and the host interface which will support 224G as well. That's what is
happening.

448G per se, it is a different beast compared to the 112G and 200G because it has a different PAM
technology for electrical and a different PAM technology for optics. In all other cases like 112G and 224G,
the PAM technology was common between electrical and optical. You had the same PAM. They would

Private and confidential

13

AI Infrastructure Industry 每 Nvidia, Astera Labs, Broadcom & Intel 每 Former Senior Executive, Product
Marketing at Cadence Design Systems Inc 每 23 September 2025

talk to each other, but in 448G, the PAM technology is different for optics and it's different for electrical.
That creates a barrier between electrical and optical interconnects and you need a gearbox or a matching
DSP to do it. Companies have demonstrated 448G today. I would expect that 448G devices would be there
in the market by 2028 timeframe, where you look at the 200T or the 400T switch, but beyond 448G, it's
going to be CPU.

Analyst:
Hock Tan commented that Ethernet-based active electrical cables are only in existence because
customers still use lower-quality SerDes. If you use high-quality SerDes that AECs [active electrical
cables] are not necessary. How do you think about the durability of the AEC market, considering that
dynamic?

Specialist:
I think so I don't fully bind to that argument of his because his SerDes might be good because he makes
the switch, but people who are doing GPUs and doing NIC cards and all, they don't need to put such a
strong SerDes inside and everybody is not going to put a strong SerDes. He's talking only for himself. He
should be looking at everybody is not coming from Broadcom, everybody is not using Broadcom devices.
From an economies of scale, you look at the whole ecosystem, AECs will exist because there will be
Broadcom and there will be non-Broadcom. When non-Broadcom wants to talk to Broadcom, you will
use AEC. Everybody cannot be using Broadcom. He's just trying to brute force that if you use me, then
you don't need AECs, but then you're paying the cost of going through Broadcom and paying them a
heavy amount of dollars. In that sense, I would say the AEC market will still exist. There are companies
like Credo, Marvell, Astera Labs who are using it. There are hyperscalers who are doing the custom
silicon like the Amazons and the Googles, and they will use AECs. From an ecosystem point of view, AECs
do exist today, and it will exist in the future as well. It's not going to die tomorrow, to be honest.

Analyst:
I feel like Astera has had a tough go from a content story perspective with anything Nvidia-related, and
it feels like this Intel custom CPU with an Nvidia GPU is further deflationary for both their retimer
content as well as that head node switch chip that they have for P-Series, because customers might
just customise less. Do you think that the Intel-Nvidia partnership is a further negative for Astera and
beyond just the X-Series part of it?

Specialist:
Definitely. By the way, Nvidia removed them. After PCIe Gen 5, they didn't need them for Gen 6. The
Grace Hopper stuff, first generation used Astera as a retimer for Gen 5, but in Gen 6, they completely
eliminated them, exactly the same theory like Hock Tan. If my SerDes are good, I don't need you. They
also eliminated the PCIe switch because the ConnectX series now has integrated PCIe switch inside.
Nvidia actually eliminated Astera. After their first generation, they never used Astera. They took them
off because they realised that they're paying a lot of money to them, so they don't need it and their
designs were completely off. With this Intel stuff and infusion of Nvidia inside Intel, they will also
remove the PCIe stuff from Intel because everything will be based on the GPU and the NVLink stuff. PCIe
dominance will go away from the Intel camp. If the PCIe dominance goes away, then Astera will struggle
to have their stuff in Intel Inside.

Analyst:
What do you think about their trajectory, Astera Labs, from here? It seems like it got a lot more
challenging.

Specialist:
I think so they will proliferate into the switching business of Ethernet and the retimers. They have a lot

Private and confidential

14

AI Infrastructure Industry 每 Nvidia, Astera Labs, Broadcom & Intel 每 Former Senior Executive, Product
Marketing at Cadence Design Systems Inc 每 23 September 2025

of capital in terms of stock value. If I was in their case, I would do some strong M&A with some
companies and grow their footprint in different areas. They just cannot be vertically integrated with the
limited stuff what they're doing in the PCIe and the UALink space. They should spread their wings right
now, given their bench strength what they have, and leverage their stock values to buy some companies
or buy some start-ups so that they can grow their footprint. They should start proliferating into optics,
DSP in those type of spaces.

Analyst:
Do you think the optics and DSP [digital signal processing] market is just much more competitive? Do
you think it's likely that they replicate their success they saw in retimers in any product category in the
future?

Specialist:
I think so that the DSP market is pretty healthy and strong because it is being deployed on the optics
side. It is a market which is quite evolving from 800G, 1.6T, 3.2T. There is still a lot of fuel in that market
to grow. If you have the right technology, you can do wonders. You look at MaxLinear. They used to be a
USD 9 stock just six months back. Today, they are USD 17 stock. It's given you 100% returns in six
months. Astera should buy a company like MaxLinear as an example. They can easily acquire that
company and leverage it and do something much better than what MaxLinear is doing today.

Analyst:
I feel like that will be reacted to pretty negatively because I think everyone has a legacy interpretation of
what kind of company MaxLinear is.

Specialist:
I understand. I get it, what type of a company it is, but they can restructure it because they can infuse
their thinking, and they buy for talent and their technology and then benefit from that price.

Analyst:
Talking about the end of last year, everyone thought 2025 would be the peak growth year of AI.
Towards the end of this year, I feel like people are thinking '26 is going to be the growth peak of AI.
How are you thinking about the durability of AI demand, especially considering some of the big
announcements we've seen across a lot of the hyperscalers lately?

Specialist:
I think so the AI still has a lot of legs to run, especially it is proliferating in the edge side of the
component side, on the inference side of things. People are basically trying to look at more optimised
way of doing the AI models right now. A lot of, I would say, R&D and research is going on in doing
parallelism on these models which are there and especially on the things called as the physical AI, which
is coming into play, a third dimension to AI, I would say. A lot of emphasis today has been put on the
physical AI side of stuff, which will make it much more accurate and much more human. With that, the
compute power is still going to scale further ahead to get that reality into the AI. It is still going to get
fuelled.

Companies might say whatever they want, but ultimately, the industry will drive towards that, and they
will be forced to do that investment to get to the next stage. Otherwise, they'll be out of the race. How
much ever Microsoft tells about cutting down the investments and all the stuff, but you look at Meta,
you look at Amazon, they are going double down on AI right now. Especially Meta is investing like crazy
in terms of their talent pool, in terms of their infrastructure. They are just going all out on the AI side of
stuff. They will reap the benefit, if not today, then tomorrow. If they are not investing, then they will be
out of the race.

Private and confidential

15

AI Infrastructure Industry 每 Nvidia, Astera Labs, Broadcom & Intel 每 Former Senior Executive, Product
Marketing at Cadence Design Systems Inc 每 23 September 2025

Analyst:
If you think about a specific technology where the industry is still debating on what the right approach
is going to be, it's CPO [co-packaged optics], scaled networking. Thinking about liquid cooling
introduction, just if you picked a technology that you think is most debated that's going to have the
biggest impact on what the trajectory of the landscape ends up being, what would you say I should
isolate down to one or two of those to really dig in to try to understand the moving pieces and try to
formulate a view on where the industry actually goes?

Specialist:
I would say two things. One is the co-packaged optics. A lot of things are happening there. Just as a
reference, the main challenge in co-packaged optics today is that it's not being manufactured in
mainstream fab. It's basically being done in gallium arsenide. That is the main stuff what is there. That
makes a difference to where we are on the co-package optics because when you're doing in gallium
arsenide, you're not in the mainstream TSMC and then you don't get the economies of scale, those fabs
are not manufacturing in thousands and millions of those ports. That is a bottleneck. The second aspect
of it is different technologies are existing in CPU by itself in terms of MGM, EMI [sic] and all those type
of things or EMR or ring-based photonics. Those are the elements which the industry has to converge.
Then there is another aspect of serviceability and manageability of these co-packaged optics, the fibre
and all the stuff, the ecosystem. A lot of stuff has happened in the past few years and a lot of stuff is
going to happen in the coming few years to get this technology stable because this is the only technology
which will scale going forward, and you cannot have the pluggable optics in the future. For example,
how we went from the cassette player to the CD and then to the MP3 digital audio, similarly, this optic
revolution is going to happen.

We had huge optical connectors before like a cigarette pack. Then we went to these modules which are
being used today. Then the next generation is going to be co-packaged. It's imminent, and that's where
the majority of discussions, investments are happening today. That's one part of the equation. The
second part of the equation is there will be two networks existing in the data centre. One will be for the
compute and one will be for the network. These two networks will exist. The growth today is not on the
network side. It's a myth that the network is going to grow. In reality, what is going to grow is the
compute side of the network, where you're connecting all the CPUs and the GPUs because that's where
the real horsepower is. The connectivity of network already exists today. You can still leverage what the
investments we have been doing since the past 10 years on the scale-out. You don't really need to put
your energy into that today. It's there. Where the entire industry energy is going to be right now is
networking of the CPUs and the GPUs, which didn't exist before because those are the highest OPEX of
the network. Remember that, the highest OPEX what you're spending today is on the GPU and CPU. You
want to make sure you're utilising them to the best and leveraging them to the best.

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

16



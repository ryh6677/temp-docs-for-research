COMMUNITY

65d0d6538a8911da05d11de9b49cc840996c80c0

Retimer Market 每 Astera Labs, Amazon,
Broadcom, Nvidia & AMD 每 Senior Executive,
Network Switching Group at Marvell
Technology Inc

Consultant | 28 March 2025

Specialist Background

> Over five years' experience in the semiconductor industry, with an in-depth knowledge of key
players such as Astera Labs, Amazon, Broadcom, Nvidia and AMD (Advanced Micro Devices)

> Deep insights into hyperscalers close to having a usable custom NIC (network interface card),

reasons why hyperscalers would want to have an alternative to NVLink and content opportunity
on a per-server basis

> Well-placed to discuss the retimer market, attach rate, PCIe (peripheral component interconnect

express) switches and China hyperscale opportunity

Contents

The ODM [original design manufacturer] will start including retimers when they put the
systems together on the actual CPU head node. Maybe the attach rate isn't falling that
dramatically. At the same time, if Nvidia is selling, let's say, a million chips, there's going to be
a percentage of those that are just standard reference design and not a lot of customisation
done on them. By default, I would have to imagine that there are no retimers in those systems,
and they only show up in the customised ones. Do you have a good way to think about what the
split might look like in terms of custom vs standard to try to think about how big of an air gap
there might be for some of these Nvidia GPU [graphics processing unit] shipments that
probably are going to no longer have retimers, where they did in the past?

If we knew that retimers were moving from NRZ to PAM4 at gen six and that ultimately, like
Nvidia, would be able to solve signal integrity issues because of the benefits that come from the
better modulation, then why have Broadcom, Credo and others even developing a gen six
retimer?

When you say it's needed for things like CPU, are you talking specifically to a general-purpose
server where there is no accelerator? Is that there's going to be a need for it at the CPU (talking
over each other), even in instances where it might be an AI cluster?

5

6

6

Retimer Market 每 Astera Labs, Amazon, Broadcom, Nvidia & AMD 每 Senior Executive, Network Switching
Group at Marvell Technology Inc 每 28 March 2025

Astera Labs, as an example, attach rate for general-purpose servers at gen four, gen five is 2%,
3%, 4%, 5%, something like really small, right? How should I be thinking about the attach rate?
By that attach rate, I mean that if you think about there being like 15-25 (inaudible) out there,
the attach rate in those server access (ph), like gen four, five, because you could use a re-driver.
The signal integrity issues aren't as large as they might be on the GPU side of things because
the bandwidth is faster. Is basically what happened with Nvidia moving to hopper and
bandwidth jumping high enough that all of a sudden, retimers are going to start happening for
general-purpose servers at gen six once those CPU servers start to refresh?

"We're predominantly a gen four and gen five for general-purpose servers today." Is this all
tied to Granite Rapids and Turin adoption? How should I think about the general purpose, and
how the mix to gen six will evolve?

The Scorpio switch, my understanding is that Broadcom has a reference design for that. You
talked about, like, at most, probably 20% of these GPU designs are going to be custom in
nature. I would think that their P-Series opportunity, the Scorpio switch opportunity, is within
that 20% that are customised. Is that the right way to think about it?

To your point that once you're getting into 144-lane type products, you're managing multiple
clients. I would think that 64 lanes make plenty of sense for internal workloads where you're
not having that host bias. Is that the main place where the Scorpio switches are getting adopted,
where an Amazon, Google or Meta, hypothetically, would have their internal workloads that are
not competing that much and are trying to do one thing pretty well? The memory semantics are
good enough there, and it's cheaper, so your BOM [bill of materials] goes down, and you're
saving some money on some of the internal stuff to do. Is that a good playback of the value
proposition today?

Can you remind me, the content opportunity, if I'm thinking about the rack and most of these
are probably going into those two CPU, eight GPU kind of board or trays at the end of the day? Is
it four switches for that? It's two CPUs, four switches and then eight GPUs? Is that the right way
to think about what the flow looks like?

When I think about the China hyperscale opportunity, I think about them servicing their
demand two ways. One is by renting public GPUs, which I would imagine come like reference
designs that would be Nvidia plus Broadcom in terms of the PCIe [peripheral component
interconnect express] switch. They'll also have some cases where they're going to be actively
purchasing their own GPUs. To me, it would seem that that's probably the more likely place
where Astera is going to take a little bit of share. How do you think about the AI diffusion rules
that are going to kick in in May, and what that might do to the China opportunity set? I don't
know if the industry is talking about that much.

Are there any other hyperscalers that you think are anywhere close to having a custom NIC
[network interface card] that's actually usable? It feels to me that Amazon is the main one
that's made some good progress on the NIC front. Maybe Meta. Definitely not Microsoft. How
do you think about the likelihood that there are aspirations to do something similar to
Amazon?

Private and confidential

7

7

8

9

9

10

11

2

Retimer Market 每 Astera Labs, Amazon, Broadcom, Nvidia & AMD 每 Senior Executive, Network Switching
Group at Marvell Technology Inc 每 28 March 2025

It seems like Meta is pretty actively focused on actually getting some front-end silicon. They
tried to buy Furiosa. Do you think at some point, all of these guys are going to have some
custom capability?

I want to talk about the UAL [ultra accelerator link] part of it. This is more for like the scale-up,
competing with NVLink. NVLink has been so good. Why would these hyperscalers want to have
an alternative to NVLink? Thinking about the fact that the P switches, like the 64-layer switch
from Astera, are not even close to the 144 lane from Broadcom, that's a drop in the water
compared to trying to compete with an NVLink switch. Why should I think that this could be a
big bang?

To the extent that for scale-up memory semantics matter so much more, and it sounds like
Astera is bad at that. Does the access to the consortium give them access to how to retrofit what
they're doing on the X series and the eventual UALink switch that they could get a lot better at
that more quickly? Is that a pretty big bottleneck in terms of Astera being able to be successful
for the scale-up side of things?

When you hear Astera saying that this non-Nvidia scale-up switch TAM can grow from
probably nothing today to USD 2.5bn in just three years. Is that overly ambitious from your
perspective?

Can you help me understand the content opportunity on a per-server basis? If we just keep
using this eight GPU form factor, I imagine that it's going to interconnect a handful of those
together from a back-end perspective. Is there a good way to think about how many NVLink
switches there are on＃

It would seem that Broadcom thinks that they might be able to use Ultra Ethernet for scale up as
well, where they do something in and around the latency. I don't have a lot of confidence in that
being the case, fixing the density problems that exist for Ultra Ethernet, but do you think that
that's a viable second option, as to, if you're not going to go with NVLink, then UEC [ultra
ethernet consortium] is also a choice that you can consider?

They also have the Leo CXL [compute express link] controller. I know that from a memory
expansion standpoint, it does something much different than what we're talking about here,
UALink-wise. Do you think their original goal is to have a CXL-based switch that would be the
UALink equivalent of the scale-up? Do you think that those aspirations are probably pretty dead
at this point, going back to your point around the fact that the Intel standard around CXL just
never really got its feet underneath it?

On the AEC [active electrical cable] side of things, for me, it feels like Credo has got this pretty
locked down with both Microsoft and Amazon, and then outside of Credo, I wouldn't even say
that Astera is going to be where I go next. What do you see in terms of their positioning with
this Ethernet-based retimer paddle card and the likelihood that they can either diversify the
revenues or across different customers or gain share at certain customers? How should we be
thinking about this part of the business?

What would be keeping you up the most at night if you were running the business in Astera?

Private and confidential

12

12

13

14

15

15

16

17

18

3

Retimer Market 每 Astera Labs, Amazon, Broadcom, Nvidia & AMD 每 Senior Executive, Network Switching
Group at Marvell Technology Inc 每 28 March 2025

Do you think that if we're talking again in three years that we will think Astera is a good, strong
and well-placed?

I feel like investors are concerned about Amazon because they have this little TikTok approach
to like their suppliers, where they'll let someone have a ton of share at one, and then they'll let
someone else gain some share and then switch back to play them off one another and keep
pricing intact. I feel the most positive thing for Astera would be to diversify their revenues out
of Amazon, as we think about 2025 probably being a majority Amazon business. As we look at
2026 and beyond, do you see any reasonable reason to think that someone else might become a
big account for them or is this pretty much an Amazon story, if you thought about it?

18

18

Private and confidential

4

Retimer Market 每 Astera Labs, Amazon, Broadcom, Nvidia & AMD 每 Senior Executive, Network Switching
Group at Marvell Technology Inc 每 28 March 2025

Retimer Market 每 Astera Labs, Amazon,
Broadcom, Nvidia & AMD 每 Senior Executive,
Network Switching Group at Marvell
Technology Inc

Transcription begins

Analyst:
Everything around AI has been pretty quick-moving, as it relates to like Nvidia trying to move to GB300.
It sounds like some challenges around ramping up GB200, everything around ASICs [application-
specific integrated circuits] and a lot of that stuff falling out of vogue. Maybe as a starting point, on the
retimer side of things, I want to talk around attach rate and how you'd be thinking about that. Astera
Labs, for something like Nvidia, as an example, there's no more content on the base board from a
reference design perspective. At the end of the day, the signal integrity issues will still exist in some
cases.

The ODM [original design manufacturer] will start including retimers when they put the systems
together on the actual CPU head node. Maybe the attach rate isn't falling that dramatically. At the same
time, if Nvidia is selling, let's say, a million chips, there's going to be a percentage of those that are
just standard reference design and not a lot of customisation done on them. By default, I would have to
imagine that there are no retimers in those systems, and they only show up in the customised ones. Do
you have a good way to think about what the split might look like in terms of custom vs standard to try
to think about how big of an air gap there might be for some of these Nvidia GPU [graphics processing
unit] shipments that probably are going to no longer have retimers, where they did in the past?

Specialist:
Let me address the concern one by one. Definitely, Nvidia is trying to eliminate the retimers as much as
they can because it reduces the BOM cost or in other words, they can consume that extra BOM cost into
their margin and improve their margins. From BOM architecture point of view, the first generation use
the retimers in PCIe gen five. When it goes to gen six, from their CPU, GPU type of an interface, they are
trying to eliminate the retimers and absorb that margin to GPUs because the cost of the GPU has gone up
significantly, and they don't want to give that margin away to somebody else. From a design point of
view, let me be very clear. From a design point of view, they have made sure that there shouldn't be any
SI issues and the marginality is enough to eliminate the retimer. Because PCIe gen six runs at 64 gig, it is
a PAM4 signalling and it has enough drive strength to eliminate the retimer.

Now having said that, if somebody uses a cheaper PCB material or tries to compromise on the PCB cost
from an ODM point of view, then he will land up into a situation where he would have to use a retimer.
There is no shortcuts over here. At that point, Nvidia is not going to endorse the design because they will
say, I've given you a reference design, I've told you the PCB stack, I told you the PCB material which has
to be used. If you are taking shortcuts and making changes to that, then you would have to add a retimer.
The second element of a retimer is the latency. People do not realise that and Nvidia is playing very
smart over here. If you put the retimer, you will get the SI and the marginality, but you will be penalised
on the latency aspect of it. In a GPU interface, especially for AI applications, latency is very important.

Private and confidential

5

Retimer Market 每 Astera Labs, Amazon, Broadcom, Nvidia & AMD 每 Senior Executive, Network Switching
Group at Marvell Technology Inc 每 28 March 2025

That has to be consistent across that what are you compromising and trading off. I am not discounting
that there won't be cases where the retimers would be used. There would be a small portion of these
million dollar attachments or USD 1m chips, which are being sold. A small percentage of them would be
using a retimer just as a security or an assurance that your design is very stable and you don't have to
fine-tune or design any further, but it's a small percentage. It is not a whole ocean of stuff which is
happening over there.

Analyst:
10%, 15%, 20%?

Specialist:
I would say maximum will be 20%. I don't think it will be more than 20% because it's not like Astera is
selling these retimers and chip.

Analyst:
If we knew that retimers were moving from NRZ to PAM4 at gen six and that ultimately, like Nvidia,
would be able to solve signal integrity issues because of the benefits that come from the better
modulation, then why have Broadcom, Credo and others even developing a gen six retimer?

Specialist:
Very good question. No, there is a need for it. That's a very good question, actually. Let me address that
question. For a case of a GPU, it is already very power-hungry device. We all agree. Since it's power
hungry, you can put in the IOs in it, which are power hungry IOs. You can basically put the SerDes and all
the stuff, which are very power hungry. Since you're already investing into a device which is consuming
a lot of power, and that's an industry norm, you have accepted it, so you can put SerDes, which are
extended long-reach and long-reach SerDes for PAM4 and eliminate the retimers. When you talk about
the NIC cards, when you talk about the CPUs and all the stuff for PCIe gen six, Intels and AMDs are not
putting extended long-read SerDes on the CPUs. When it comes to a CPU with a PCIe interface of gen six,
you will need a retimer.

Until that particular CPU is sitting in a laptop, then you don't need it, but if that CPU is sitting in a server
and you are constrained with the power for the CPU and the thermal dissipation and all those stuff, in a
server platform, you will need the retimer for PCIe gen six. Mind you, in servers, they use cheaper
material and the cost and the BOM cost is pretty low. If a server is not working, they just toss it and
throw it. They don't debug and all those stuff. The whole concept of server is basically you make with a
minimal cost and you make sure that it runs for 3-5 years and after that, you toss it out. In those cases,
the retimer is very much needed for PCIe gen six. That's why companies like Broadcom, Astera Labs and
many others, and even in China, there are companies like Montage, which are going behind the retimer
business.

Analyst:
When you say it's needed for things like CPU, are you talking specifically to a general-purpose server
where there is no accelerator? Is that there's going to be a need for it at the CPU (talking over each
other), even in instances where it might be an AI cluster?

Specialist:
Yes, these are general purpose servers, which are sitting in the cloud. They are not the AI class of servers
where GPUs are attached. There is a large volume of servers which are sitting for storage application,
web servers and normal general purpose servers, which are sitting in AWS front-end servers, which
don't have a GPU attached. GPUs are attached to the back-end servers. There are high volumes of front-
end servers. Let's not forget that.

Private and confidential

6

Retimer Market 每 Astera Labs, Amazon, Broadcom, Nvidia & AMD 每 Senior Executive, Network Switching
Group at Marvell Technology Inc 每 28 March 2025

Analyst:
Astera Labs, as an example, attach rate for general-purpose servers at gen four, gen five is 2%, 3%,
4%, 5%, something like really small, right? How should I be thinking about the attach rate? By that
attach rate, I mean that if you think about there being like 15-25 (inaudible) out there, the attach rate
in those server access (ph), like gen four, five, because you could use a re-driver. The signal integrity
issues aren't as large as they might be on the GPU side of things because the bandwidth is faster. Is
basically what happened with Nvidia moving to hopper and bandwidth jumping high enough that all of
a sudden, retimers are going to start happening for general-purpose servers at gen six once those CPU
servers start to refresh?

Specialist:
The gen six general purpose servers will need a retimer. The attach rate will be more than 80%, I would
say. There will be a high attach rate for a general purpose server in gen six. It can be from AMD, it can be
from Intel. Mind you, Astera Labs makes the maximum amount of revenues from the AWS because they
have a close tie-up with the Graviton team. All the Graviton servers, the ARM-based servers, which is
being designed by Amazon, all of their retimer attach rates are 100% Astera Labs. They architected in
such a way that even before Astera Labs became IPO, they had two clean customers. One was Amazon
and other one was Intel, who had signed up for them to do their next-generation server platforms with
their retimers.

In fact, Intel reference designs were all based out of Astera Labs retimers. Similarly, all Graviton
platforms, which are deployed in Amazon. Their attach rates are almost close to more than 90% on the
Graviton and on the Intel platform. Even when the Graviton goes to gen six or the Intel CPUs are going to
gen six, those retimers will be attached. Now when you do put a GPU to it, then the whole equation
changes. From a Grace class of CPUs, Nvidia has made us a very smart and a bold move that I'm going to
eliminate the retimers, I'm going to make sure that my CPUs have the enough drive strength to plug in
for my GPUs, and I don't need the retimer sitting between my CPU and my GPU.

Analyst:
"We're predominantly a gen four and gen five for general-purpose servers today." Is this all tied to
Granite Rapids and Turin adoption? How should I think about the general purpose, and how the mix to
gen six will evolve?

Specialist:
Yes, that's a good one. By the way, gen four doesn't require a retimer because gen four is running at 16
gig, you don't require a retimer there. gen five is running at 32 gig and the retimer starts appearing from
gen five onwards. The gen six is running at 64 gig, it becomes critical depending upon how the I/Os have
been structured on the CPU. If the I/Os are not a long reach I/O, then you will require a retimer. Long-
reach I/Os will increase your power consumption of your CPU. Now coming to the transition from gen
four to gen five and gen six. These transitions are predominantly driven by the network interface card or
for the GPU cards. Because when you have a gen five kind of an interface and you can go all the way up to
maximum up to 16 lanes of gen five and each lane is basically running at 32 gig, you'll get a maximum
bandwidth of 400 gig. If you have a 400-gig NIC card, then you can use gen five.

The moment you start having more than 400 gig, like 800 gig or two ports of 400 gig on your NIC cards,
then you will have to transition into a gen six type of a platform. This also translates to the number of
drives. If there is a storage server for database storage, how many storage drives are you attaching to
your server? If you're attaching basically 16 drives into one server, then you will require a gen six. If
you're attaching eight drives to a server, then you require for gen five. Remember, when you attach the
storage drives for database like Oracle and SAP and all those type of applications or very intense data
storage applications, at that stage, you have to keep a balance of your CPU capability and the number of

Private and confidential

7

Retimer Market 每 Astera Labs, Amazon, Broadcom, Nvidia & AMD 每 Senior Executive, Network Switching
Group at Marvell Technology Inc 每 28 March 2025

drives you are attaching so that your hit rate with the drives are pretty much normalised and you don't
have an extreme latency in terms of drive response time. Gen six is quite there. If you have a gen six type
of interface, your connectivity and your scaling of your drives becomes much more better.

Analyst:
It's driven by the SSDs [solid-state drives] and the NICs [network interface cards]. There's not a lot of
gen six products being talked about right now.

Specialist:
Gen six deployment will start happening, I would say, from early part of next year to mid next year. They
are right now in the field trials. You're right, gen six deployment has really not kicked in at the levels
what we would like to see it. You're right on that.

Analyst:
That leaves an air pocket for Astera's retimer business in 2025.

Specialist:
Exactly. We are still selling the gen five. They have expanded their portfolio by having the Scorpio, which
is a PCIe switch. It's a 64-lane switch. That does the gen five and gen six. They are also expanding into
UALink, trying to do a UALink switch. I wouldn't be surprised if they're doing it for the like of Amazon or
somebody for a UALink switch, but they are definitely heavily investing into the UALink switch. I
wouldn't be surprised if they come up with a UALink switch product by end of this year or early part of
next year.

Analyst:
The Scorpio switch, my understanding is that Broadcom has a reference design for that. You talked
about, like, at most, probably 20% of these GPU designs are going to be custom in nature. I would
think that their P-Series opportunity, the Scorpio switch opportunity, is within that 20% that are
customised. Is that the right way to think about it?

Specialist:
That's right. Actually, Broadcom's PCIe switch is far superior. Broadcom switch is 144 lanes and Astera
Labs is 64 lanes. Astera did a very quick job of getting the PCIe switch out because doing a 144 lanes
would have been much more complex. They did a quick and a dirty job. They have been able to make a lot
of noise of it. If you technically compare it with Broadcom's switch, Broadcom is far superior and double
the bandwidth. It's 144 compared to 64 lanes.

Analyst:
These things sell for like USD 250-300 at 64 lanes because Broadcom is 144, and I think it's north of USD
500-600, so 550 divided by 144 times 64 would tell me almost USD 250. Is that a reasonable way to
think?

Specialist:
Yes, that's a reasonable way of thinking about it. The main thing is the 144 does the memory semantics
in a much better fashion than what a 64 lanes can do. It is basically the design complexity which goes
behind the 144 lanes. It doesn't scale linearly. Once you hit beyond a certain number of lanes, your
complexity of doing memory semantics becomes more complicated because now you have multiple
clients, which you have to take care of. I think so for Astera Labs, they were lacking the expertise or
maybe the time to get to a scale of 44, so they did a bare-bone minimum feature of 64 lanes, so that at
least they can get a foot inside. It is quite possible that they might be having a driver customer who is
requesting for such type of a switch because Astera is very customer-driven.

Private and confidential

8

Retimer Market 每 Astera Labs, Amazon, Broadcom, Nvidia & AMD 每 Senior Executive, Network Switching
Group at Marvell Technology Inc 每 28 March 2025

They will not come up with a product till there is a customer and a sure assurance to their revenue to do
it. They will not experiment and keep doing something using their own instinct. They will basically go by
the market instincts and develop a product line, which is fine. The strategy is working for them. There is
no flaw in that strategy. What I'm getting at is, definitely, there is a market for 64 lanes. That's why they
have come up. For the people who need 64 lanes, Broadcom sells them 144 and charges them a lot of
money, so they would have thought, okay, why am I paying Broadcom so much money when I'm not
using so many lanes. Let me go with 64 lanes.

Analyst:
To your point that once you're getting into 144-lane type products, you're managing multiple clients. I
would think that 64 lanes make plenty of sense for internal workloads where you're not having that
host bias. Is that the main place where the Scorpio switches are getting adopted, where an Amazon,
Google or Meta, hypothetically, would have their internal workloads that are not competing that much
and are trying to do one thing pretty well? The memory semantics are good enough there, and it's
cheaper, so your BOM [bill of materials] goes down, and you're saving some money on some of the
internal stuff to do. Is that a good playback of the value proposition today?

Specialist:
Yes, that's a good value proposition. I think so in case of the PCIe switch, we have a very strong hold in
APAC. Astera Labs is pushing heavily in APAC, their PCIe switches. This is basically the folks like Alibaba,
Baidu, ByteDance. They are heavily pushing their business over there, where predominantly previously,
Broadcom used to dominate, but now they are trying to basically get some traction in these segments.

Analyst:
Can you remind me, the content opportunity, if I'm thinking about the rack and most of these are
probably going into those two CPU, eight GPU kind of board or trays at the end of the day? Is it four
switches for that? It's two CPUs, four switches and then eight GPUs? Is that the right way to think
about what the flow looks like?

Specialist:
Yes, that's the right way. Basically, you will see anywhere between 4-6 switches in a rack. Four is the
bare minimum. Six switches will be a redundant switch in case if there is overprovisioning needed, but
four is the right number for rack for the switches for PCIe.

Analyst:
Their switch is going to be 10% of their revenues this year, which last time that shook out to somewhere
around 60 million, maybe it will be 65 million. That implies 1.2-1.3 million GPUs, roughly speaking.
When you think about Amazon's internal workloads and some Chinese share, is that too big a number?
Is that reasonable when you think about what the opportunity set is that they're attacking?

Specialist:
I think so the number is reasonable in that range, yes. I would say that's the right number because there
aren't many players in the PCIe switch space, very limited number of players. Customers, they are put in
a hostile situation with Broadcom, so they are looking for some alternatives where they can at least let
Broadcom know that you're not the only dominant player and Astera is filling that gap and executing
and delivering them the stuff. It's an advantageous situation for Astera. Especially in PCIe, there was
nobody in switching. Marvell was not there.

Analyst:
Microsemi, right?

Private and confidential

9

Retimer Market 每 Astera Labs, Amazon, Broadcom, Nvidia & AMD 每 Senior Executive, Network Switching
Group at Marvell Technology Inc 每 28 March 2025

Specialist:
Yes. Broadcom acquired this stuff from PLX Technology. I think Microsemi is there in PCIe switching,
but not to that level, but they are there. I do know that they have a PCIe switch, but for some reason, they
are not so dominant in that area. I don't know the details, but I can look into it and get back to you.
Definitely, Astera is giving Broadcom a run for the money and telling them that don't be just compliance
and you have to be very vigilant. I think so Broadcom's PCIe division has woken up, and I see a lot of
blogs recently coming out from them. Basically, it has definitely taken them internally that Astera Labs
is coming very strong at them, so they need to take care of their business.

Analyst:
When I think about the China hyperscale opportunity, I think about them servicing their demand two
ways. One is by renting public GPUs, which I would imagine come like reference designs that would be
Nvidia plus Broadcom in terms of the PCIe [peripheral component interconnect express] switch.
They'll also have some cases where they're going to be actively purchasing their own GPUs. To me, it
would seem that that's probably the more likely place where Astera is going to take a little bit of share.
How do you think about the AI diffusion rules that are going to kick in in May, and what that might do
to the China opportunity set? I don't know if the industry is talking about that much.

Specialist:
The problem with China is they don't have direct access to the emerging technology because of the
restrictions, which are being imposed by the government in the Fed. First of all, they are basically
fragmenting their AI deployment. They are not going for the high-end GPUs because they just cannot
deploy those GPUs. Either they can rent those resources through some services, and those services
might be outside China, but then they have access to these machines and they can run their workloads
on these machines, which is exactly what you said, and that's happening, by the way. The likes of the
Amazon and OVH, which is basically a French cloud company. They are leasing their AI data centre to
Chinese firms. The other side of the spectrum is, which is very strange, these Chinese companies like the
Tencent and the Baidu, they also have offices in US. I don't know why people ignore that fact.

They have a decent amount of presence in US, where they have resources and people working in US. They
might be US citizens, but the company is Baidu and Tencent. They have access to that technology locally
from here, and they can basically hire the GPUs from the providers like Amazon locally. They can run
that workload in US, though they are Chinese companies. I fail to understand why people forget, you
cannot isolate a company which is sitting in US, on US network and tell them, "I'm going to ban you
from accessing Amazon data centre." That is not happening. I have not seen that happening. What are
we talking about? The guy sitting in China can completely offload his entire workload and machines in
US and tell the US guy to run those trainings and algorithms using the infrastructure which is installed
in US. He may not have direct access. He may not invest in their infrastructure, but he can lease it and get
it done. It's not been fully bulletproofed. It's partially there. It's a scare factor, but it's not like you're
completely preventing them from doing or touching it at all.

Analyst:
It's like China is able to continue to get access to some of the leading-edge stuff by renting it from like
an OVH, Amazon or Microsoft or what have you. I'd have to imagine that for the external workload type
server clusters, that Amazon, OVH or Microsoft is using a 144-layer switch because there are multiple
clients that they're renting those instances to and need the proper memory semantics. Where and how
Astera can win with some of those Chinese hyperscalers, if increasingly, they're going to have to rent
GPUs locally to avoid falling behind?

Specialist:
Yes. By the way, I don't know, there are about 20 GPU companies in China, start-up GPU companies. Out

Private and confidential

10

Retimer Market 每 Astera Labs, Amazon, Broadcom, Nvidia & AMD 每 Senior Executive, Network Switching
Group at Marvell Technology Inc 每 28 March 2025

of these 20 companies, 4-5 of them have direct investment from their hyperscalers. ByteDance, Baidu,
Tencent, (inaudible). These four or five companies have direct investment in these companies. In that
way, Astera is enabling them in their technology.

Analyst:
I wonder if that will get shut down eventually. Just as I think about the Donald Trump administration, it
doesn't seem like they have a lot of limitations on where things will stop for them.

Specialist:
I know for sure that they are selling in China to these hyperscalers, their parts. The 144 has an
advantage. Let's be very clear. Broadcom is squeezing a lot of margins from China. Now it's come to a
situation that you are taking a lot of money from me, your product is good, but every year, you keep
raising the price and you keep squeezing me and put me in a hostile situation. I'd rather go to some other
vendor who may not have the perfect product, but at least I'm not squeezed by them, I'm respected by
them, and I'm not paying an exuberant amount of money, and I'm not threatened every year that you're
going to raise my price. Astera Labs in terms of customer relationship has that advantage compared to
Broadcom. Broadcom have shot themselves by not taking care of their customer and constantly
threatening them of price increase and increasing their own product margins.

Analyst:
When I think about some of the front-end, we talk about like, you don't want to pay for a CX8 NIC is one
example of where you're gaming the system a little. The CX8 NIC from Nvidia is probably getting you to
a point where you don't have the signal integrity issues. If you're Amazon, you want to use your neuron
like V3 (ph) or whatever, you'll go with the Astera Labs instance.

Are there any other hyperscalers that you think are anywhere close to having a custom NIC [network
interface card] that's actually usable? It feels to me that Amazon is the main one that's made some
good progress on the NIC front. Maybe Meta. Definitely not Microsoft. How do you think about the
likelihood that there are aspirations to do something similar to Amazon?

Specialist:
By the way, Microsoft bought a company called Fungible. I don't know whether you recollect this or not.

Analyst:
Yes, the DPU [data processing unit], right?

Specialist:
Yes, DPU. That's a NIC only. It's a class of a NIC what they develop. It's bump in the wire. Every
hyperscaler has some or the other form of an internal NIC. Amazon got it through Annapurna Labs,
which they had acquired a few years back, same group, which is developing the Graviton and the Nitrox
security card. Then Microsoft, they got Fungible. Meta develops their own custom NIC. Some of them
have been designed by Marvell called the VNIC, which is in the public domain today. Google actually uses
the Intel NIC. It's public information. Intel and Google collaborate a lot and a lot of Intel product lines
are basically being used in Google as the NIC and they design their own TPUs, which is a class of an
accelerator for their own network.

In some form or the other, all of these companies have some form or the other accelerator or a NIC card,
which they are designing in hardware for their cloud network. Google and Meta don't design their own
servers today. Actually, Google is designing their own servers, which is being done under Uri Frank in
Israel. Predominantly, they have not come to a mass deployment like Amazon, but they do have ARM
servers, which are being deployed internally in their cloud, which is being designed by them. I don't

Private and confidential

11

Retimer Market 每 Astera Labs, Amazon, Broadcom, Nvidia & AMD 每 Senior Executive, Network Switching
Group at Marvell Technology Inc 每 28 March 2025

know which retimer Google is using in their servers, but I can tell you that they might be using a retimer
from somebody. It might be Broadcom, it might be Marvell, it might be Astera, but somebody's retimers
have been used in Google. Graviton, we know the retimers are coming from Aster Labs. Meta is using a
generic server coming from Intel and AMD. They don't design their own DPUs (ph).

Analyst:
The fact that they're using a generic server, does that change the gen six opportunity for them on the
general-purpose side of things? Would Meta be a less likely big retimer candidate?

Specialist:
Meta can be a big retimer candidate because since they're using generic purpose servers, they will be
more vulnerable to use the retimers because they don't control their CPU design. It is coming as a
generic CPU from AMD and Intel. Both of these AMD, Intel general purpose servers are endorsed to use
retimers. They have not been retimer free from a server point of view. Both of these companies have
taken the retimer part for the general purpose servers.

Analyst:
It seems like Meta is pretty actively focused on actually getting some front-end silicon. They tried to
buy Furiosa. Do you think at some point, all of these guys are going to have some custom capability?

Specialist:
100%, yes. By the way, Meta has a whole team of silicon architects and design right here in the Bay Area
in the Sunnyvale office. They do a lot of custom designs. I'm very well aware about they're doing stuff on
the memory accelerator and all those stuff. They also do a lot of ASICs for their AR/VR type of devices,
what they sell. Yes, they do have slowly over a period of time, they have built in the silicon design
capabilities. Now whether they want to stretch it further and do a CPU class of SoCs, it's only time will
say. I don't know the details or insights as to what the Meta's long-term plan is for their silicon
development. Yes, they are there. It's not that they are ignoring that fact.

Analyst:
I want to talk about the UAL [ultra accelerator link] part of it. This is more for like the scale-up,
competing with NVLink. NVLink has been so good. Why would these hyperscalers want to have an
alternative to NVLink? Thinking about the fact that the P switches, like the 64-layer switch from
Astera, are not even close to the 144 lane from Broadcom, that's a drop in the water compared to trying
to compete with an NVLink switch. Why should I think that this could be a big bang?

Specialist:
I'll give you my views. Some people might not like it, but I'll share it with you. By the way, UALink was
started by AMD. It was not started by any of the hyperscalers. AMD started the UALink consortium
because they are the second source GPUs after Nvidia. Nvidia spent a lot of money on their GPUs and the
software infrastructure. NVLink did not arrive today. NVLink was there since 2011. It just became
prominent now. You can imagine the vision and the investment Nvidia had for this so many years ago,
when we go back. Intel came up with an equivalent called CXL, but CXL did not scale to the level of
NVLink. CXL had good flavours in it, but for somehow, Intel being so distracted and too much into their
foundry and other stuff, they completely missed the AI train, and CXL fell through the cracks. Now
coming back to UALink, AMD, I don't know why, but I think so AMD is a bit in a weird situation. You do
the GPUs, you come up with a UALink consortium. You acknowledge that you need a UALink for your
GPUs, why don't you build it yourself?

Why do you just put it in a consortium and say, oh, other people, now you start building it? Nvidia did
not do that. Nvidia built their own NVLink switch. When the GPU sell, they sell their NVLink switch also.

Private and confidential

12

Retimer Market 每 Astera Labs, Amazon, Broadcom, Nvidia & AMD 每 Senior Executive, Network Switching
Group at Marvell Technology Inc 每 28 March 2025

It goes in tandem and everything handshakes and you give a full solution. Honestly, I feel AMD, I don't
know what their management is thinking. You think the GPUs will be successful, but they will be
successful only when you have a UALink switch. If you don't have the switch, you are completely off the
market because now why do you need a UALink switch? The reason you need a UALink switch is because
when you connect so many clusters of GPUs, the customers or the consumers of the GPU want to make
sure that after spending so much of money, I'm utilising these GPUs to the full extent. I'm not leaving
them idle. What you do is you create a cluster and you link all the GPUs to the switch so that you get the
maximum efficiency in terms of memory semantics.

Most of the GPUs, they lose their performance because they are short of memory. Here, you are
assimilating the memory across multiple GPUs and doing node balancing with them and making sure
that all of them are always actively working and performing. That is the purpose of a UALink switch. It's
different from the Ethernet switch. It is a switch, which has low latency and does memory semantics. A
normal switch or a scale-out switch does network semantics. It takes care of the network part of it and
make sure that the network is not getting clogged and there is a proper flow control and load balancing
between the network. UALink switch takes care that the GPUs are effective and the memory semantics
and efficiencies are basically through all the GPUs.

If AMD wants the GPUs to be there in the market, they want to be a second source compared to Nvidia,
but you leave the field open for UALink switch and tell others to design it. That is a big problem. Now
that's number one. The number two is the UALink switch, people now are designing own GPUs. Amazon
is designing their own accelerator GPU card. There are so many companies in China which are designing.
They may or may not use AMD. What they are doing is they are taking the UALink, which AMD come up
with and will try to modify it or make it more proprietary, add some more frills to it based on their GPU
design, so UALink will become a baseline, but on top of it, they will do some customisation on it because
that is meeting their GPU requirements, which is a non-AMD GPU, and they will get a solution. I
personally feel this UALink may or may not be successful because it doesn't have a unified force coming
from AMD themselves. It should have been done by AMD from start to finish rather than just coming up
with a spec and leaving it to others to accomplish and build it. That's a wrong strategy.

Analyst:
I've heard a few people tell me that the fact that (inaudible) is on the board means that Amazon is very,
very seriously considering using UALink. If he joins a consortium, that means he's not just joking
around; he's not someone who joins every consortium that exists.

Specialist:
I'm on a similar view of yours, but with a slight twist on it. He's on the board. He will extract all the
information from UALink, then he'll tell Astera Labs to build a UALink switch for him or his GPU is what
he's designing inside Amazon. He may not use AMD, but he will extract all the goodies from what the
UALink spec has got, what an AMD GPU has got and then build custom accelerator GPU or whatever you
call it, and which will run on the UALink. I think so that is his plan.

Analyst:
To the extent that for scale-up memory semantics matter so much more, and it sounds like Astera is
bad at that. Does the access to the consortium give them access to how to retrofit what they're doing
on the X series and the eventual UALink switch that they could get a lot better at that more quickly? Is
that a pretty big bottleneck in terms of Astera being able to be successful for the scale-up side of
things?

Specialist:
No, it's a bottleneck. It's by joining the consortium, they just get access to the draft, which everybody

Private and confidential

13

Retimer Market 每 Astera Labs, Amazon, Broadcom, Nvidia & AMD 每 Senior Executive, Network Switching
Group at Marvell Technology Inc 每 28 March 2025

has got. That doesn't move the needle. Ultimately, it will be their internal architectural talent. They are
in a situation where they can hire people. They can use the stock money to hire people and get that
talent. They are strong enough now to get the good talent in their camp.

Analyst:
Yes, you should check out their stock price actually. It's down 50% in the last three months.

Specialist:
Yes. All the stocks have gone. Same thing with my company. That's the case. You look at Nvidia also,
instead of doing all such good things, it's getting less than USD 110. You look at Broadcom, it's less than
USD 170 today.

Analyst:
Apple is on the UALink consortium. They don't really do anything, custom that's pretty well known
about. I think even recently, there's been a little bit of rumours around the fact that they're putting on
bigger orders for AI clusters. Some of that has to do with the fact that DeepSeek made training or
inference costs, like the post-training costs, a lot more pushing. Maybe that makes Tim Cook think that
he can actually do something from an AI device standpoint for the cell phone. I just thought it was
interesting that Apple is on the board of UALink. I would have thought them as (audio distorts).

Specialist:
Yes, to be honest, Apple being on the UALink little bit baffles me also. I get confused as to what they
exactly are doing. I can't exactly pinpoint why they are there in the UALink stuff because they don't build
their own data centre, they lease it from Amazon. They don't do any data centre hardware, everything.
They being in the UALink is a little bit of a puzzle to me also. I'll be very frank about it. I can't point out
the thoughts as to why they are there and what's in there for them.

Analyst:
At re:Invent, Apple is on stage. It seems they're maybe going to be one of the bigger Trainium initial
external customers. Maybe the whole point is not to look at the state that Apple wants to be very close in
coordination with what they're going to end up doing, and if it's good enough for what they're hoping
for, maybe that's＃

Specialist:
Yes. The other thing is basically, they do build the GPUs for their Mac and all the stuff. I don't know what
their long-term plan is. They want to do a multi-GPU stuff on some graphic machine or something. I
don't know. I'm just speculating. I'm still not being able to pinpoint as to what exactly is happening.

Analyst:
Is Cisco doing anything this far down the silicon stack in terms of＃

Specialist:
No, they are not. They are not. Actually, they are struggling with the Silicon One right now because let's
not forget the whole Silicon One team is based out of Israel because that was the Leaba acquisition.
Hopefully, they'll do something.

Analyst:
When you hear Astera saying that this non-Nvidia scale-up switch TAM can grow from probably
nothing today to USD 2.5bn in just three years. Is that overly ambitious from your perspective?

Private and confidential

14

Retimer Market 每 Astera Labs, Amazon, Broadcom, Nvidia & AMD 每 Senior Executive, Network Switching
Group at Marvell Technology Inc 每 28 March 2025

Specialist:
It's overly ambitious. It's over ambitious because, as I said, the UALink switch, AMD has to put skin in
the game, unless they don't put it, there's a lot and a lot of heavy lifting. It's just not doing silicon. The
whole software stack has to be developed. I think so people are heavily underestimating what Nvidia has
done and given them. It is just not the hardware and you come up with a switch. It's the whole
ecosystem, which has to be orchestrated and has to work with it. What about the software stack and
who's enabling that?

Analyst:
Can you help me understand the content opportunity on a per-server basis? If we just keep using this
eight GPU form factor, I imagine that it's going to interconnect a handful of those together from a
back-end perspective. Is there a good way to think about how many NVLink switches there are on＃

Specialist:
Right now, most of the UALink's spec and the people who are considering doing a GPU, they are looking
at a scale of 72 GPUs being connected, 72, up to 72 GPUs on one single UALink switch. You can basically
structure your rack based on that, how many GPUs are there on one particular cluster on a pod. The
UALink de facto, the benchmark is you should be able to connect 72 GPUs on one single UALink switch.

Analyst:
That's pretty bad vs NVLink, right?

Specialist:
It is bad compared to the NVLink, but it's a stepping stone. It's the first entry point where you're looking
at. You cannot just directly go and floor it from the first go because people are discovering,
implementing. There's a huge cost of investment in doing this complex silicon. It's not easy. When I say
about 72, you're talking about 244 lanes. It's not some small device.

Analyst:
The ASP vs that 250 for the 64-lane is going to be pretty significant. When I was doing the USD 250
divided by 64 times 244, I think it's more than that, maybe, so should I be thinking it's over USD 1,500?
Do you think USD 1,000? How should I think about it?

Specialist:
Yes, it will be north of USD 1,000 easily. It won't be cheaper than that. I would anticipate north of USD
1,000 easily.

Analyst:
It would seem that Broadcom thinks that they might be able to use Ultra Ethernet for scale up as well,
where they do something in and around the latency. I don't have a lot of confidence in that being the
case, fixing the density problems that exist for Ultra Ethernet, but do you think that that's a viable
second option, as to, if you're not going to go with NVLink, then UEC [ultra ethernet consortium] is
also a choice that you can consider?

Specialist:
Broadcom is making every effort to cannibalise the efforts of UALink. The way they are doing it is
basically they have rejoined the UALink team about two months back. They are back in UALink camp.
They can extract all the information from UALink, and they are influencing the UEC, which is for scale
out to have memory semantics. On the network side, you don't care about memory, by the way. The
switches don't care about memory. They care about network semantics, not memory semantics. They
are trying to influence the UEC spec to have memory semantics. By doing so, then they will have one

Private and confidential

15

Retimer Market 每 Astera Labs, Amazon, Broadcom, Nvidia & AMD 每 Senior Executive, Network Switching
Group at Marvell Technology Inc 每 28 March 2025

common switch, which can do scale up and scale out and they don't have to do two classes of switches,
which is a very smart move actually. This is my perception when I look at it, why they are doing this and
what they are doing. I don't see any other reason why a network switch should have memory semantics.

Analyst:
Then, I guess, it would come down to is PCIe Ethernet is better for scale up? If, at the end of the day,
using that network switch for the scale-up because you added memory semantics, I think that then the
decision would come down to whether or not PCIe or Ethernet would be better equipped for everything
else that's included in the scale-up needs outside of memory semantics itself, which maybe get a level
playing field between the two. Do you think that the Ethernet base would be better?

Specialist:
It could be better. In fact, the UALink spec itself is going towards Ethernet. The first generation was
PCIe, then they changed it. The current spec of UALink is basically Ethernet speeds, so it is 224. That
decision is already made that it will be towards the Ethernet side of the world.

Analyst:
Astera have no Ethernet IP at this point.

Specialist:
If you look at the career post and all the stuff, they are hiring a lot of people on the Ethernet side of
space. They are working towards that.

Analyst:
You mentioned that maybe at the end of this year, early next year, they'd be able to come out with the
product. None of that changes, even though they're going to have to actually come up with something
that's Ethernet-based instead of PCIe-based, which they're pretty well entrenched in?

Specialist:
Yes.

Analyst:
On the UAL part of it, to the extent that it's their first foray into something that's Ethernet-based,
releasing a product with sampling is all good, well, but when might you think about the ability to get to
volume production? Do you think that the first product will be volume production-ready? Do you think
that something iterative would have to occur and that I shouldn't expect this UALink revenue trajectory
to really be something we're talking about that much until maybe later in ＊26 or into ＊27?

Specialist:
I think so the first product will go through a little bit of turns. I anticipate the Rev B silicon or Rev B (ph)
product will be the better one for them. It is very difficult to do everything in the first pass. I think so.

Analyst:
They also have the Leo CXL [compute express link] controller. I know that from a memory expansion
standpoint, it does something much different than what we're talking about here, UALink-wise. Do
you think their original goal is to have a CXL-based switch that would be the UALink equivalent of the
scale-up? Do you think that those aspirations are probably pretty dead at this point, going back to your
point around the fact that the Intel standard around CXL just never really got its feet underneath it?

Specialist:

Private and confidential

16

Retimer Market 每 Astera Labs, Amazon, Broadcom, Nvidia & AMD 每 Senior Executive, Network Switching
Group at Marvell Technology Inc 每 28 March 2025

I think so there will be a lot of work involved in getting it done. It's not going to be a first step success.
They will have to work very closely with their system vendor, which in this case, I think it's going to be
Amazon, which they're going to work with. It's going to basically take them at least a year or more to get
all of their software stack and everything cleaned up before they do anything.

Analyst:
for the actual Leo CXL controller itself, where you're adding a couple of terabits of memory for probably
internal workloads, where you're trying to avoid adding a DIMM [dual in-line memory module] at the
end of the day. I heard the big alternative there would be near memory compute because it's a little
smarter than what the CXL controller is. Do you think that the CXL product that Astera has is going to
see much traction?

Specialist:
I think what eventually CXL is going to be just for a point-to-point between the server. With the memory
semantics coming in UALink, CXL is going to die down. That is going to take at least, I would say, next
three years to four years. It's not going to happen immediately. CXL will eventually be taken over by
UALink in terms of memory semantics. CXL will lose its ground or its value, I would say.

Analyst:
On the AEC [active electrical cable] side of things, for me, it feels like Credo has got this pretty locked
down with both Microsoft and Amazon, and then outside of Credo, I wouldn't even say that Astera is
going to be where I go next. What do you see in terms of their positioning with this Ethernet-based
retimer paddle card and the likelihood that they can either diversify the revenues or across different
customers or gain share at certain customers? How should we be thinking about this part of the
business?

Specialist:
The AEC business is very lucrative because it's the cabling stuff. It will still be there. As we go to the 224
interfaces, which will start deploying from 2026 onwards. In 2025, as the first 200-lane switches will be
deployed, I'm pretty sure in the OFC, there will be a few announcements of the 200-gig switch. Jensen
already mentioned about his 100T switch. Most of the 100T switches are based out of 200 gig links. Once
200-gig links become more pervasive in the market in 2026, the AEC will be back in the market. Let me
remind you that 200-gig insertion losses and the attack rates go only up to 1 metre and 1.5 metre. 112
DAC was going up to 4 metres. To compensate for the 4 metres with the 1.5 metres, there will be more
active AEC cables, which will be needed for 200-gig ports. Also, as we see from Nvidia's demonstration,
now you are going into multi-rack interfaces for a complete pod. You are scaling up to more from 72
GPUs to 500 GPUs to 200,000 GPUs to 500,000 GPUs. Now you need a whole orchestration of multiple
racks, which are connected together in a very cohesive manner. AEC cables, either you go to AEC or you
do CPC or CPU. CPC and CPU are expensive and it will still take time to be proven in commercial large-
scale deployment. AEC will be prominent in terms of the deployment for these networks, at least for the
short term.

Analyst:
Does Astera have any differentiation on this side of things?

Specialist:
No, they don't. Actually, it's the same stuff. Everybody has the same thing. It's just the cost and the
lower power, but it's not a big difference right now. It's the pricing, the relationships. Yes, Credo has it,
Marvell has it and even Astera has it. The market is quite huge. I would say all of these organisations are
doing a good job over there.

Private and confidential

17

Retimer Market 每 Astera Labs, Amazon, Broadcom, Nvidia & AMD 每 Senior Executive, Network Switching
Group at Marvell Technology Inc 每 28 March 2025

Analyst:
Am I right that if I looked back at 2024 that Credo probably had north of 50% share at 400-800 gig
already? If that's correct, then as you think about 800-gig proliferation, do you see that turning into
something that's like one-third, one-third, one-third between those three big guys?

Specialist:
Quite possible, yes.

Analyst:
I'm right that Credo have the majority share. If we were looking back, not talking about moving forward,
they did have a majority share because there are only a couple of customers doing it. Once we broaden
that out, that's when it's going to step up a lot.

Specialist:
Yes.

Analyst:
It feels like a handful of green shoots for the business. The core retimer portion of it is tied specifically to
GPUs that are Nvidia's are not going to be that positive, but there's probably some staying power for the
retimer franchise. All these Trainium clusters are going to use retimers, and all of them, which is nice for
them as well.

What would be keeping you up the most at night if you were running the business in Astera?

Specialist:
What will be keeping me up at night if I'm running the business in Astera is because they have been so
far riding the wave of the PCIe retimers, and that business can be cannibalised by the likes of Broadcom,
Marvell and all because there's nothing unique in that business from a talent point of view, from a
technology point of view. It's a smart thing to do, but it just requires execution, to be honest, and getting
the things done. There is no innovation in terms of the technology part of it. That would be keeping it
busy that ultimately, you have to have something unique in terms of innovation, which is unique in your
brand name to get it done. Their brand name today is they are good in executing and getting it on time.
They are not distracted by anything. They focus on a problem and they get it done. In the long term,
when people know that these are easily achievable things, people will go after them very strongly. They
don't have the breadth. Vertically, they have one solution. Now it's up to them how do they leverage this
top dollars they have to grow and expand and do something which is a unique value, which will take
them for the next 10 years.

Analyst:
Do you think that if we're talking again in three years that we will think Astera is a good, strong and
well-placed?

Specialist:
I would say, yes. For the next 2-3 years, they will skim it because they have the product, they have
already entered the market and they are executing. There's no issues with that. They will skim it and
they are locked down those accounts, so they will keep getting it. After three years, how do they sustain?
I think so they should do more acquisition, hire more talent and start developing something which is
quite unique in the market. They have that leverage, and they should start leveraging that fact.

Analyst:
I feel like investors are concerned about Amazon because they have this little TikTok approach to like

Private and confidential

18

Retimer Market 每 Astera Labs, Amazon, Broadcom, Nvidia & AMD 每 Senior Executive, Network Switching
Group at Marvell Technology Inc 每 28 March 2025

their suppliers, where they'll let someone have a ton of share at one, and then they'll let someone else
gain some share and then switch back to play them off one another and keep pricing intact. I feel the
most positive thing for Astera would be to diversify their revenues out of Amazon, as we think about
2025 probably being a majority Amazon business. As we look at 2026 and beyond, do you see any
reasonable reason to think that someone else might become a big account for them or is this pretty
much an Amazon story, if you thought about it?

Specialist:
I think they have a very locked-in relationship with Amazon. As long as they execute, I think that they
should be fine.

Analyst:
Ability to get other customers way less the case?

Specialist:
They have a very deep relationship with (inaudible) was an investor in Astera Labs. They have executed
and they have given them at a very compelling price points. Amazon will be doing the servers by
themselves. Graviton will be using it. They have a good story line over here for the next 3-4 years.
Amazon is not going to use servers from outside. They're going to design their own servers. They will
need the retimer for their cloud servers. Astera has to just keep executing to their demand. That's all.

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

19



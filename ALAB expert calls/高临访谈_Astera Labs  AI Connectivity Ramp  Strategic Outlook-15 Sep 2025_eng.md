Astera Labs 每 AI Connectivity Ramp &
Strategic Outlook

FORUM

65d0d6538a8911da05d11de9b49cc840996c80c0

15 September 2025

Key Insights

> Astera Labs maintains 90% market

share in retimers through exceptional
customer support and fast issue
resolution, prioritising reliability over
performance

> Astera's product portfolio is highly
aligned with AI infrastructure, with
Gen6 retimers, Scorpio switches and
UALink products directly addressing
high-speed and high-sensitivity signal
integrity needs

> UALink 每 an open standard 每 is
poised to challenge Nvidia's
proprietary NVLink by 2027, offering
seamless memory sharing across
GPUs for AI infrastructure

> Scorpio switches will be a significant
growth driver, with a realistic path to
contributing over 20% of revenue by
2026 due to its necessity for Gen6
adoption

> Beyond AI, Astera is well-positioned
for growth in storage clusters and
streaming services, where high-speed
connectivity is increasingly crucial

Specialist Gil Tal (GT), Former Director, System &

Validation at Astera Labs Inc

Moderator William McGonigle (WM), Third Bridge

Sector Analyst

Agenda

> PCIe (Peripheral Component Interconnect

Express) 6 and Scorpio Fabric Switch adoption for
Astera Labs (NASDAQ: ALAB) across AI system
customers

> Ecosystem partnerships with Nvidia (NASDAQ:
NVDA), AMD (NASDAQ: AMD) and UALink
Consortium

> Margin sustainability and near-term revenue

growth outlook

> Supply chain resilience and tariff and geopolitical

risk management

Astera Labs 每 AI Connectivity Ramp & Strategic Outlook 每 15 September 2025

Contents

Q: How did Astera Labs evolve during your tenure? Could you provide an overview of the
company's products, such as Aries, Taurus, Leo and Scorpio switches, and their evolution?

Q: Which factors enable Astera to maintain and secure its 90% market share, specifically in the
retimers? How does the broader AI story tie into the company's defensible moat of market
share?

Q: How defensible will the moat be moving forwards as we see the move to Gen7, which, as you
mentioned, order shipping will start in late 2026?

Q: What would the current or past GPUs [graphics processing units]-to-retimers ratio look
like? Where has that ratio moved now? Where do you expect that to move as hyperscalers
qualify and ramp Gen6?

Q: Nvidia's GB200 NVL racks rely on NVLink, which bypasses the PCIe [Peripheral Component
Interconnect Express] retimers. How material is this to Astera's TAM? Do you see x86 or ASIC
[application-specific integrated circuit]-based systems, such as the ones we're speaking about
with hyperscalers, sustaining this demand for the retimers as an offset?

Q: In its Q2 2025 earnings report, Astera stated that the intelligent connectivity platform
addresses a large and growing TAM of around USD 17.2bn currently, and the company expects it
to grow to USD 27.4bn by 2027. Does that increased TAM in 2027 make sense to you? Does the
scale at which we're seeing build-outs that will demand the products plateau after training?

Q: What are the biggest barriers to design wins for Scorpio switches against Broadcom's
entrenched position? Is it qualification cycles or the stickiness of software integration at
hyperscalers?

Q: Street estimates that Scorpio could reach around 10%-plus of total revenue in 2025 and grow
to 20% by 2026. Do you see that same growth path for Scorpio here, assuming Astera executes
and maintains relationships? What are some conditions that need to materialise or continue
with the momentum to achieve that ramp?

Q: Could you expand on the significance of UALink, particularly as a long-term driver for
Astera? Do you realistically see its open-standard approach meaningfully eroding Nvidia's
NVLink dominance by 2027?

Q: What role do the 800G active electrical cables play in AI cluster build-outs? How should we
think about the attach rates, either intra- vs inter-rack connectivity?

Q: What realistic adoption curve do you see across hyperscalers or CPU vendors, looking at CXL
[Compute Express Link] controllers, such as Leo? Is 2026 a true inflection point, or do you
expect that later in the future?

Private and confidential

4

5

6

6

7

7

7

8

9

9

10

2

Astera Labs 每 AI Connectivity Ramp & Strategic Outlook 每 15 September 2025

Q: What would you point out as the KPIs, metrics, events or announcements to watch out for to
gauge the adoption and traction across Astera's product line?

Q: Given Astera engages with large customers on the pricing side, how resistant are the
relationships to pricing changes? Gen5 retimers sell at around USD 30-40 or Gen6 could launch
around 30-50% higher. Do you see any resistance or pushback from hyperscalers on that
increase, or is performance and design critical enough to sustain the higher ASPs?

Q: Where are the other emerging applications 每 beyond the AI clusters 每 in enterprise servers
or storage, where PCIe Gen6 retimers could drive some incremental demand? What are the
other underappreciated demands or market opportunities for Astera?

10

11

12

Private and confidential

3

Astera Labs 每 AI Connectivity Ramp & Strategic Outlook 每 15 September 2025

Astera Labs 每 AI Connectivity Ramp &
Strategic Outlook

Transcription begins at 00:00:02 of the recorded material

WM: Welcome to Third Bridge Forum's Interview entitled Astera Labs 每 AI Connectivity Ramp &
Strategic Outlook. I'm Will McGonigle, and I'll be facilitating today's Interview with Mr Gil Tal, former
Director of System and Validation at Astera.

Gil, before we start today's Interview, would you please state either I agree or I disagree to the following
statement: You understand the definition of material non-public information and agree not to disclose
any such information, or any other information which is confidential, during this Interview.

GT: I agree.

[00:00:36]

Q: How did Astera Labs evolve during your tenure? Could you provide an overview of the company's
products, such as Aries, Taurus, Leo and Scorpio switches, and their evolution?

GT: I started Astera Labs when they, I think, were two years old or something. They decided to found a
branch in Israel, so I was assigned engineering manager of the Israeli site and aside from that, System
and Validation Director. Personally in Israel, we were in charge of the cables, fast Ethernet cables,
utilising Taurus. Since I brought with me lots of experience from the industry, I was highly involved with
the engineering manager of Astera Labs. We had lots of technical discussions also with the CTO, and I
was very close to the two leaders, Sanjay and Jitendra. I'm highly familiar with the product. The Taurus
is the product line which serves as connectivity for very high-speed Ethernet connection serving in big
servers and clusters. Aries is highly needed because of the PCIe Gen5 and Gen6, very high speed and high
sensitivity to signal integrity. This is why you need a retimer, which is a booster for the signal strength
along the way of the routing.

Also, there is the product line of the CXL, which is a memory extension throughout the CXL, which
enables you to expand the memory of a server, a big server seamlessly without the drivers. It also gives
you the benefits to utilise all DDR4 modules that are usually being removed from old servers, not that
old but old enough in order for the company to dispose them. You don't need, you can buy a CXL bridge
from Astera and then utilise this DDR4 memory modules almost for free. Now they have the Scorpio,
which is a gearbox for PCIe. It's a smart fabric switch that gives you the capability to have devices with
different PCIe speeds. It's also the first PCIe Gen6 fabric switch. This way, you can have Gen5, Gen4 and
devices connected to a Gen6. In this way, for example, you can have a GPU that has Gen5, so two GPUs at
Gen5 connected to a CPU, which has a Gen6 interface. This way, you can have 2x16 GPUs connected to
one CPU which has only 1x16 connection to the fabric. This way you can utilise the system in a much
better way.

Also, there is the new product line that Astera Labs＃ it's public. They announced about the UALink
product line. They are about to release switch and other product lines for the UALink, which is a huge,

Private and confidential

4

Astera Labs 每 AI Connectivity Ramp & Strategic Outlook 每 15 September 2025

huge and smart decision toward AI infrastructures. PCIe also started moving to Gen7, just started. It's
just beginning and product should be arriving only late next year. The adoption for PCIe Gen6 is ramping
fast. This is exactly where Astera Labs is targeting all those Gen6 devices, high speed. If you want me to
expand a bit about AI and the complexity of AI compute, then you might be able to understand why it is
so highly needed, both UALink, Gen6. Wherever Astera is at, it is highly needed for AI compute and
infrastructure.

[00:05:52]

Q: Which factors enable Astera to maintain and secure its 90% market share, specifically in the
retimers? How does the broader AI story tie into the company's defensible moat of market share?

GT: I'll tell you what, the strategy of Astera Labs is first and most customer support. They put most of
their effort on having the best and highest skilled engineers supporting their customers. This way, they
are able to solve issues very fast and highly professional. This way, customers＃ Everyone has issues, no
matter whatever state in the product life, you can have issues at the beginning, ramping up the product.
You can have issues later on. You can have issues in production, you can have issue later on during the
product life cycle. Astera Labs understand that issues can happen and can occur and they are doing, I
think, extraordinary effort to solve issues for the customers. I personally was involved serving Amazon
when they were using the Taurus. We were a second supplier for Amazon. Since the customer support
that we gave them was so great and so fast and with the highest quality, they switched to Astera as their
main supplier. Although they had a fight that was underperforming compared to the competitor, but I
tell you what, customers appreciate much more than performance, customer support and the ability to
solve their issues.

Let's say you're going to buy a Toyota. When you buy a Toyota, you know one thing. It's a reliable car.
You have less headache. Although it's not the best car in the market, you know that you're going to sleep
well. If you're going to buy, I don't know, an exotic car, let's say, a very expensive Mercedes, so what? I
don't think you're going to have the same feeling of self-confidence in the product. Although it
performs much better and, I don't know, maybe the experience is, for sure, a better experience than
driving a Toyota, but the mindset that you have when you have a Toyota is a completely different
mindset. Imagine yourself when you're managing a fleet of servers, you have, I don't know, almost one
million servers. Just imagine yourself a situation in which the cable starts giving you issues in the fleet.
You're going to have＃ You're starting having, I don't know, failures in the field. It means that, for
example, if you are serving Amazon and they have the TV services or whatever, and only 5% of the cables
are starting to fail in the field. You're going to have, I don't know, 5% or 10% of America disconnected.
That's the outcome.

You as a manager that needs to run a fleet, you say, okay, so the competitor gives me, I don't know,
10-15% better performance, but the customer service or the way they solve issues when they arise is on a
completely different level. I prefer having a bit less performance if it's the situation, not always this is
the situation. I think the Aries product is top notch. In any case, you prefer to have a supplier that gives
you a bit less performance, less shiny, but the best customer service, the best solutions whenever you
have issues, the fastest way to solve them. This is the way things are working now because Astera Labs
plays in fleets and fleets are huge. You can imagine yourself today data centres are enormous, especially
and they are growing and growing faster and faster and bigger and bigger. Whomever is in charge of
these fleets, he needs to sleep well and needs to make sure that nothing fails and if something starts to
rise and issue starts to rise, expect the product supplier to be the first and solve the issue as fast as
possible. This is exactly what Astera Labs are doing. Again, this is, I think, the biggest advantage of
Astera Labs aside from others, but I think at most, this is the one.

Private and confidential

5

Astera Labs 每 AI Connectivity Ramp & Strategic Outlook 每 15 September 2025

[00:11:29]

Q: How defensible will the moat be moving forwards as we see the move to Gen7, which, as you
mentioned, order shipping will start in late 2026?

GT: I think that the strategy stays the same. Technology-wise, I think the supplier of the PHY is
probably Synopsys or Cadence, not too much options out there in the market. There were Wayfair (ph
12.04) and they were bought by Broadcom, probably not going to sell any more PHYs to the open market.
I think same strategy will hold, meaning when you have＃ Say you are a customer for Aries products for
Gen6, and you are highly satisfied because of the customer support and the way Astera Labs solves your
issues and then moving on to Gen7, why would you switch to a different supplier? Let's say, they give
you a bit better price, let's say. As I say, the mindset that you must have as managing huge fleets is
always, always will be first, who gives you the best and fastest solution when you have an issue. I think
Astera Labs are not giving up on their strategy as giving the best and fastest service whenever you have
issues with the customers. Currently, my current job is at Intel, and we are buying retimers from Astera
Labs, and there was an issue with one of the systems＃ It wasn't Astera Labs issue, but it was a system
issue. Astera Labs worked very fast in order to give us a solution. I think that this is something that really
matters. I think in most cases, most matters.

[00:13:46]

Q: What would the current or past GPUs [graphics processing units]-to-retimers ratio look like?
Where has that ratio moved now? Where do you expect that to move as hyperscalers qualify and ramp
Gen6?

GT: I'll tell you what, it really depends on the system architecture because, for example, if you are using
Scorpio as your fabric, then Scorpio sells also since it's a switch and the CPU is connected to the switch
and then the GPU is also connected to switch. In some situations, you might not need a retimer because
you have the fabric, the switch, the PCIe Gen6 switch, the P-Series. If you have a big cluster, like, for
example, we do at Intel, we have the AI GPUs that we are constructing, the traces from the GPU to the
either switch or CPU are very long, and they must have a retimer. I haven't been into calculation for
Gen7. I don't know if you need two of them per GPU or only one. Could be that you only need one because
you have the switch and then you have a retimer from the GPU to the retimer and then from the retimer
to the switch.

I think that the market share for Astera Labs is going to go in combination of using of customers using
both Scorpio and the retimers. I'm not familiar with the pricing of Scorpio. I think this combination of
having both retimers and switch is going to be highly beneficial for both customers and also for Astera
and keep the numbers at a good pace going up. Also since AI is growing very fast, very fast and the need
for CPU blades is rising very fast. I think that retimers are going to grow in the same ratio. Again, I think
that＃ I don't think customers, for sure, will need smart fabric switches. Scorpio is going to be part of the
system as well.

WM: Would that be one Scorpio and one retimer per compute node or GPU?

GT: I think it's going to be＃ Let's take, for example, a blade having four GPUs. You're probably going to
have one Scorpio and four retimers on such a blade.

Private and confidential

6

Astera Labs 每 AI Connectivity Ramp & Strategic Outlook 每 15 September 2025

[00:17:38]

Q: Nvidia's GB200 NVL racks rely on NVLink, which bypasses the PCIe [Peripheral Component
Interconnect Express] retimers. How material is this to Astera's TAM? Do you see x86 or ASIC
[application-specific integrated circuit]-based systems, such as the ones we're speaking about with
hyperscalers, sustaining this demand for the retimers as an offset?

GT: I'll tell you what. Nvidia will not be able to sustain the market share for long. Other competitors are
closing the gaps in terms of software, which is the most, I think, dominant part of Nvidia's ability to
control the market. Also, I think there are new solutions coming next year, which might offset the
market a bit. Since NVLink is only a proprietary of Nvidia, then let's assume two scenarios. One,
customers they don't have NVLink, so they need a NIC. If they need a NIC, they need a retimer. The other
scenario is customers are moving to the new UALink interface, which might bypass the retimer, but also
gives you, again, a path to Astera Labs because Astera is one of the first to adopt the UALink interface.
UALink is the competitor for the NVLink from Nvidia. I think that NVLink is not going to survive because
you cannot have a proprietary and that is not shared with others, they need a solution as well.

While the market is moving to UALink, probably, I think at the end, Nvidia will have to switch to UALink
as well. Then they will come to Astera Labs. I don't think they will be able to develop their own solution
fast enough. Since Astera are going to be probably the first out there in the market with UALink, then the
offset is probably going to be in such a way that either Astera Labs keeps using＃ Their customers keep
using the retimers or using NIC or when moving to UALink, then Astera Labs will compensate them by
using the UALink solutions. This is how I see it.

[00:21:08]

Q: In its Q2 2025 earnings report, Astera stated that the intelligent connectivity platform addresses a
large and growing TAM of around USD 17.2bn currently, and the company expects it to grow to USD
27.4bn by 2027. Does that increased TAM in 2027 make sense to you? Does the scale at which we're
seeing build-outs that will demand the products plateau after training?

GT: I think it's on the edge, but it's not that far because currently, customers are designing to have their
first power on early on 2026 with UALink products. Again, it's a public information. I'm not saying
something that is not out there in the market, so you can take a look at it. Intel and AMD and others are
targeting the new AI GPUs using UALink and other infrastructure that is supposed to be probably more
or less power on at the end of 2026, meaning it's on the edge for them to be able to reach PRQ, meaning
going out to the market by the end of 2027. This is highly optimistic. Let's say, if it won't be the end of
2027, it will be at the beginning of 2028, maybe Q1, Q2 of 2028, where big numbers will come for this AI
connectivity products. That's for sure.

[00:23:29]

Q: What are the biggest barriers to design wins for Scorpio switches against Broadcom's entrenched
position? Is it qualification cycles or the stickiness of software integration at hyperscalers?

GT: Scorpio doesn't need a software, almost doesn't need a software. Fabric can be easily be
programmed, have a firmware and software is not a big issue. Why are you using a fast fabric switch? I
think the biggest difference between Broadcom and Astera Labs is there are two main differences. First,

Private and confidential

7

Astera Labs 每 AI Connectivity Ramp & Strategic Outlook 每 15 September 2025

Astera Labs is still in start-up mode. Although they gone public and they are not exactly a start-up, but
they are still fast and they act fast, they design fast and they move very fast. This is something that it's a
bit tough for Broadcom. Validation cycles at Astera Labs are fast. They have very good validation
infrastructures. They have the highly skilled engineers. Something I didn't say, but it is quite unique to
Astera Labs. They insist on hiring very, very, very professional engineers. Sometimes you're going to
have to go through seven interviews. In most cases, you're going to have an interview that the
engineering manager or one of the CTOs or Jitendra or Sanjay, they are insisting on having the best of
the best. This shows, as you can see, Astera Labs are performing very good. Take a look at the stock.

As for Broadcom, remember what I said about Astera Labs, how the customer support and the
engagement with you when you have an issue is remarkable, this is not the case for Broadcom.
Customers, when you have an issue, when you have a product from Broadcom, that's what customers
are stating. It's a nightmare for them. They hate working with Broadcom when you have an issue. This is
probably one of the best, I think, advantages for Astera Labs vs Broadcom. Astera are aiming very high,
and they will get there. They are rising star and they're not dreaming, they are performing. I know that
Jitendra and Sanjay personally, I had lots of discussions with them, both friendly and technical, and they
are really unique, and also the third guy, which is serving as a CTO, all three of them are highly humble
and fully determined.

They are determined to success, and they're not just talking, they are acting. They are hiring the best of
the best. They personally talk to the customers when needed, and they make sure that Astera Labs keeps
performing at the best way towards serving their customers and also building the best product for the
market. They know how to identify exactly what the market needs. Again, they are highly familiar with
Broadcom. They know exactly who are Broadcom and what are their weaknesses and what are＃ The
biggest advantage currently for Astera Labs is they are acting very fast and the customer service, which
Broadcom cannot compete with them.

[00:27:56]

Q: Street estimates that Scorpio could reach around 10%-plus of total revenue in 2025 and grow to
20% by 2026. Do you see that same growth path for Scorpio here, assuming Astera executes and
maintains relationships? What are some conditions that need to materialise or continue with the
momentum to achieve that ramp?

GT: I think it makes lots of sense because the market currently needs this product, the Scorpio product,
as I said, because there are lots of Gen5 GPUs and memory controllers and SSD controllers. Currently,
the latest call from Intel and AMD are having Gen6 CPUs and fabrics. It is a must. If you want to utilise
and not give up on highly expensive in terms of importance for the system architecture, PCIe lanes, then
you must have the Scorpio product on the systems. It's a must. Again, since the products are highly＃ The
basis for the Scorpio, again, is the Aries, and the Aries is in a very good condition product. Imagine
yourself building something with basic blocks, building blocks, which are with the highest quality and
they are fully proved and working and just on the new＃ Create a new device utilising these highly
advanced products. On a Scorpio, you have a Gen5, just as an allegory, Gen5 retimers within the switch
and then a Gen6 retimer on the other side. Then they just know how to communicate with these devices
from side to side. The Scorpio is a very high product. Customers don't like to mess with PCIe, they really
don't like to mess with it. It's a very sensitive interface.

If it doesn't function well, then you're going to have really big issues on the system. Customer doesn't
like to take risks. Since they know that the basic building blocks of Scorpio are actually the Gen6 Aries
and Gen5 Aries, then they know that Scorpio is a high-quality product and especially on the sensitive

Private and confidential

8

Astera Labs 每 AI Connectivity Ramp & Strategic Outlook 每 15 September 2025

parts, which are the PHYs, the high-speed PHYs. This is why I think success is guaranteed for the
Scorpio.

[00:31:29]

Q: Could you expand on the significance of UALink, particularly as a long-term driver for Astera? Do
you realistically see its open-standard approach meaningfully eroding Nvidia's NVLink dominance by
2027?

GT: Yes, for sure. Let me give you a very short introduction to AI. AI, once you have a model, a very large
model, then when you try to do an inference, inference means that you need the model to give you an
answer for a specific question, for example, it's a very high-level description. A basic model, large model
is composed of almost 100 billion-150 billion parameters. When you have a GPU blade and you need in
order to exercise this large model, which is being uploaded to many GPUs in concurrent fashion because
one GPU cannot handle it. In most cases, you need many GPUs, I don't know, tens of them in order to
maintain a very large AI model. The communication between the GPUs, while doing the computation to
give you the answer, it's a token. You give a token to LLM machine, and it gives you the probability. You
must have a very simple and fast way to do upscaling, meaning generating a virtual one huge GPU. This
can be done very easily with the UALink because of the memory semantic technology, which is
integrated into this interface, which gives you the ability to generate a very huge memory space, which
is shared between all of the GPUs seamlessly.

Just remember what happened to flash. You remember, most of the sites were composed of flash, Adobe
Flash. Then Steve Jobs decided one day that no more flash, we are moving to HTML. If you're＃ You don't
have to be, but I'll just give you a very brief description. Flash was very complex. It was very high. It
required lots of compute power from the CPU running the browser. HTML is a completely different story.
It was a huge revolution moving from flash to HTML. I think it's the same allegory. Moving from NVLink
to UALink. I think that UALink is going to be the way that AI infrastructure needs to be able to share
memory between different GPUs and give you the capability to do upscaling with the best performance. I
don't think Nvidia has a chance to withstand the competition using UALink. They won't be able to
sustain the NVLink because, first, you cannot buy the IP only maybe if they are selling the NICs and I
don't think it has the capabilities of the UALink because UALink is coming from the need of AI.

The whole architecture is being designed with bias for AI infrastructures. This is something that I think
where UALink is superior to NVLink. Again, since Astera Labs, Intel, AMD, Apple and many more are
jumping on the wagon of the UALink, then I don't think Nvidia will be able to withstand the market
moving to UALink. This is where Astera Labs is going to be hitting very hard. It's going to be a very, very,
very big market and Astera Labs is going to be there. For sure, they're going to be there.

[00:36:41]

Q: What role do the 800G active electrical cables play in AI cluster build-outs? How should we think
about the attach rates, either intra- vs inter-rack connectivity?

GT: Currently, the 800-gig NICs are being used for scale out and not scale in, meaning the different＃
When you have a rack, for example, then all the communication within the same rack, usually, they
don't need this＃ Sorry, they need these 800-gig cables in order to communicate between the different
blades. Sometimes they are using, I don't know, info. For example, Gaudi 3 from Intel, they have their
own solution for＃ They have their own NIC integrated into the GPU itself, the Gaudi, for example, and

Private and confidential

9

Astera Labs 每 AI Connectivity Ramp & Strategic Outlook 每 15 September 2025

they have communication between the blades. If you need to communicate between blades, in most
cases, you need the 800-gig cables because the first, they are able to＃ You can use them for long range,
two metres. They also have versions for three metres. You can imagine yourself these racks are really
big. Physically, you need cables and the NICs that Intel are using, they are not able to withstand such a
long range cable. Mostly these cables are big players in upscaling in terms of AI. In terms of
communication that, for example, while Amazon are serving Netflix and give them lots of servers for
streaming, then the purpose of the 800-gig cables is a completely different story.

They are being used for communication, streaming the data to the customers and bringing the data from
the hard disc, the big hard disc that containing whatever content they are streaming. In terms of
upscaling between racks, then these cables are highly needed. It could be that in terms of AI, the number
of cables serving AI is probably going to be reduced while once UALink is going to kick in. Since UALink
is also capable for 1.6 gig on an eight-lane cable, it's 200 gig per lane. If you have only four lane, then
you have 800 gig and you have eight lanes and you can have 1.6 gig. It really depends on the＃ I'm not
sure with regards to the PHY capabilities driving more than, I don't know, 20, 30, 50 centimetres of
copper, but I haven't heard about UALink retimers. I do know that we're going to use switches and how
the different switches are going to be connected between each other. I must tell you, I don't have the
answer for it now. It could be that they are going to use, I don't know, this 800 or maybe a few 800-gig
cables to connect between the different UALink switches, but I'm not sure. This is something that I'm
missing.

[00:41:07]

Q: What realistic adoption curve do you see across hyperscalers or CPU vendors, looking at CXL
[Compute Express Link] controllers, such as Leo? Is 2026 a true inflection point, or do you expect that
later in the future?

GT: Tell you the truth, it's hard to tell. I tell you what because CPU vendors and GPU, GPU has its own
memory. Usually, GPU cannot utilise＃ It doesn't make sense for a GPU to utilise memory over Leo. In
most cases, the one that can utilise memory over Leo are CPUs. Customers like I don't know＃
Manufacturers like Intel, AMD, they know how to expand the memory slots. Currently, I don't think they
have lack for memory slots for the servers because in most＃ Although it is true that AI needs a huge
amount of memory when handling big modem, but most of the memory resides within the GPUs
themselves because they are doing the calculations. The CPU only host the data and then drive it toward
the GPUs. It's very hard to tell, except the fact that, again, since there are millions, I don't know how
many hundreds of millions of servers going out of service, and they have DDR4 memories. These
memory slots are very＃ They used to be very expensive. They're still expensive. Those are sometimes
255GB per DIMM, so there's huge memory slots, and you're going to dispose them.

If you have a Leo, then you can utilise them. Give you a test case for that, I don't know because I tell you
what, PCIe lanes are highly expensive assets in terms of designing a system, meaning if you have three
PCIe lanes, then you will connect to GPU serving AI. That is why in terms of AI, I think it's less common
to use Leo. As far as I see it, it could be. I might be wrong, but as far as I see it, I don't see Leo, and I'm
also highly involved in the new AI systems coming from Intel. I cannot elaborate on them. Again, Leo is
not going to be the＃ It's hard to tell. It's really hard to tell.

[00:44:29]

Q: What would you point out as the KPIs, metrics, events or announcements to watch out for to gauge

Private and confidential

10

Astera Labs 每 AI Connectivity Ramp & Strategic Outlook 每 15 September 2025

the adoption and traction across Astera's product line?

GT: Let me see that I understood your question. You're asking customer looking at Astera, how they will
adopt the products and how they look at Astera moving forward?

WM: For an investor trying to gauge where adoption and traction sit across Astera's product portfolio,
are there any metrics or KPIs that they should monitor to gauge the health of the company's business
lines?

GT: I think Astera currently performed very well in terms of, as you said, market share for the Aries. I
think the best indication is looking at Aries in terms of electrical performance or comparing the power
consumption to competitors, then you might see that the difference is not that big. You can ask yourself,
so why Astera Labs are maintaining such a high market share. The reason again is the way Astera are
engaged with their customers. I think if you want to have an indication, then you should be highly
tentative to the customers. What are the experience engaged when engaging with Astera. Are they
satisfied or not? Once they are not satisfied, then I think the advantage of Aries over other competitors'
products is not that significant. What is significant is the way Astera serve their customers. I don't think
this is going to change because this is the main in their core business, customer service and having the
best of the best engineers serving their customers. It is very difficult to monitor because you don't start
asking their customers, tell me how is the experience working with Astera. They give you good service.
How fast are they respond to issues that are rising. It's very tough.

I think that what we should monitor is the overall behaviour of Astera Labs because they keep
innovating. They keep moving forward. They keep expanding their customer highly selectively. They
don't have many customers, but they have big and very important customers like Nvidia, Amazon and
other big and highly quality, and they are targeting more. Are you familiar with Napoleon's strategy
when he was going out to a war? Napoleon didn't have a big army. It was small compared to other
armies, but the strategy was very interesting. He would take all of his army against a specific, I don't
know, combat that he had. His enemies always had the illusion that he has a huge army because always
he's coming with big numbers compared to the specific combat he had. I think that's the way Astera are
acting. They are not big. They are going. They are going very carefully because they are＃ Again, for
example, I work at Intel, I can tell you that Intel had issues to recruiting highly qualified engineers
during the years because of the big numbers, so we had to compromise, but Astera doesn't compromise.

As long as they do it, when＃ Let's say, now they are going to target Apple, for example, as a customer.
Then they will do the Napoleon strategy. They will put all of their efforts on Apple making them get into
production in the best way there is, fastest and with the highest quality, and then they will move on to
the other customer. I think that's the way Astera are doing and working. That's why they are choosing
the customers which has big numbers. I think it makes sense. They are not big enough to have, I don't
know, thousands of customers, each one buying, I don't know, small numbers. They prefer to have less
customers but with big numbers. This is working for them. It's working very well. I don't know if you are
familiar with Sanjay and Jitendra, since they are highly humble and highly technical, super technical,
customers like them very much. They have very good relationships with the leaders of whatever
company they are engaged with. They're highly social with our leaders. I think this gives them a very
good advantage moving forward.

[00:51:08]

Q: Given Astera engages with large customers on the pricing side, how resistant are the relationships
to pricing changes? Gen5 retimers sell at around USD 30-40 or Gen6 could launch around 30-50%

Private and confidential

11

Astera Labs 每 AI Connectivity Ramp & Strategic Outlook 每 15 September 2025

higher. Do you see any resistance or pushback from hyperscalers on that increase, or is performance
and design critical enough to sustain the higher ASPs?

GT: It depends on the market that you are targeting. Since the AI market is highly big numbers market,
as you know, try to buy a blade from Nvidia, you will understand how expensive they are. I don't think it
matters for them too much, I don't know, USD 5 less or more. They are trying, but I tell you what, when I
used to work for Astera, there was one guy from Amazon that was pushing very hard on Astera to reduce
prices, and they didn't. They refused to reduce the price. Amazon kept buying from them. Again, because
why? Again, it's like you're going to buy a Toyota and you tell the seller, give me a discount. I tell you
why should I give you a discount. This is the best reliable car you can buy. It will give you a peace of
mind. You will sell it at a very good price when you decide to sell it later on. If you don't buy me, someone
else will buy it. Astera have a strategy telling the customers, I know you're paying, but you're getting
all＃ How would I say it? You are fully compensated for the price. In terms of customer service,
engagement, in case that you will call them, I don't know, midnight, he will answer your phone and tell
you what you have in mind. What is bothering you? Let me help you. That's the way Astera Labs.

I think they tell customers, okay, you are paying, but you have the benefit for what you are paying for. I
think that customers highly appreciate the customer service. If one day this will stop being an advantage
for Astera Labs, they probably will push the prices lower because they tell them what is the difference
between you and Broadcom? Both of you give me headache, both of you doesn't give me the support
when I need. Why should I pay more? I don't think it's going to be the case with Astera Labs. As I told
you, I personally know Sanjay and Jitendra and Casey, and they are all highly humble and fully
determined to come to a full success, again, maintaining the core basics for Astera Labs, which says best
performance, they can, but before anything else, customer support.

[00:55:09]

Q: Where are the other emerging applications 每 beyond the AI clusters 每 in enterprise servers or
storage, where PCIe Gen6 retimers could drive some incremental demand? What are the other
underappreciated demands or market opportunities for Astera?

GT: I think you said it well. First, storage clusters. They are very big. They are moving to high-speed
SSDs. They need retimers. On the same＃ Imagine yourself how a storage cluster looks like. You have lots
of SSDs. New SSDs are connected using Gen5 PCIe. It really makes sense for them to start using Scorpio
and having the CPU utilising Gen6 and then you have few sometimes. Let's just say the CPU has i16 (ph
56.39) interface, a Gen6 and then you have four, i4 Gen5 SSDs connected using a Scorpio. I think it's
going to grow very fast talking about storage. Then moving on to utilising streaming services, then you
need the high-speed cables that Astera makes maybe not the best performer, but the most reliable
cables in the market. I think they have a very good price point. I think looking at the future, the future is
moving to bigger and more and more big fleets for either streaming, storage and compute, not just AI
compute, general compute. They are everywhere. I think they're located in exactly where the market is
growing up, exactly both storage and streaming services, compute services coming from Amazon, from
Microsoft.

Most of them doesn't have the time to handle developing such a product. They rely on Astera Labs or the
competitors to create all the infrastructure supporting devices. They are both Amazon and Google and
Microsoft, they are developing their own ASICs, but without the infrastructure, they need the
infrastructure coming from either Astera or whomever. As I told you, if I was about to decide with whom
I would like to go with, and if I would know Sanjay, Jitendra and Casey, I would go with Astera Labs. I'll
tell you what, I think it's public, so it's not something I can tell. Intel are highly engaged with Astera

Private and confidential

12

Astera Labs 每 AI Connectivity Ramp & Strategic Outlook 每 15 September 2025

Labs using retimers and on the next product line of UALink.

WM: I want to say thank you for your time and input. This Interview has been fantastic, and thank you to
our Third Bridge clients as always.

GT: You're welcome.

Transcription ends at 00:59:33 of the recorded material

If you＊d like to speak to Gil Tal in a private call or meeting, please let your relationship manager know.

Disclaimer

The information, material and content contained in this transcript (※Content§) is for information purposes only and does not constitute advice
or an offer or inducement of any type or a trade recommendation and should not form the basis of any investment decision. This transcript
has been edited by Third Bridge and may differ from the audio recording of the Interview. Third Bridge Group Limited and its affiliates
(together ※Third Bridge§) make no representation and accept no liability for the Content or for any errors, omissions or inaccuracies in
respect of it. The views of the specialist expressed in the Content are those of the specialist and they are not endorsed by, nor do they
represent the opinion of, Third Bridge. Third Bridge reserves all copyright, intellectual and other property rights in the Content. Any
modification, reformatting, copying, displaying, distributing, transmitting, publishing, licensing, creating derivative works from, transferring or
selling any Content is strictly prohibited.

Private and confidential

13



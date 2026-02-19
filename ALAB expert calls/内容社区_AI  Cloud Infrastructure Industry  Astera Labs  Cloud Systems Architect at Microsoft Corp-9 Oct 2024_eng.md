COMMUNITY

65d0d6538a8911da05d11de9b49cc840996c80c0

AI & Cloud Infrastructure Industry & Astera
Labs 每 Cloud Systems Architect at Microsoft
Corp

Competitor, Customer | 9 October 2024

Specialist Background

> Over 10 years' experience in the IT industry, focusing on cloud infrastructure

> Knowledgeable on MSPs (managed service providers) and IT service providers' evaluation and

selection criteria, as well as contract negotiations

> Well-placed to discuss next-gen AI systems, the competitive landscape and key players such as

Astera Labs, Broadcom and Marvell

Contents

The main focus of the call is on Astera Labs, that just carried out their PCIe [peripheral
component interconnect express] fabric switch, so that could be a good place to start out. Was
this something that you were expecting? Any early reaction to the new product coming from
Astera Labs, if you expect it to get any decent uptake?

What would you think about the likelihood that Astera starts to take some share? Obviously, the
retimer much less complex silicon, but at the same time, they're claiming that they are Gen 6. I
don't think Broadcom's Gen 6 PCIe switch chips have even started to ship in volume. To some
extent, they're jumping ahead of Broadcom, at least from a PCIe standard standpoint. What do
you expect? Do you think that they're going to gain any decent amount of share on the scale
side of things?

Is that the situation is at Gen 5 is in already? Broadcom is probably only selling a PCIe switch in
those specific instances where Amazon, Microsoft and Meta are looking at their custom ASIC
[application-specific integrated circuit] opportunity and are not going either the Ethernet or
Nvidia proprietary link route. Is that already the case?

Astera Labs is trying to claim that it's a USD 5bn market. I've been trying to run some quick
numbers, and it feels like it's more an USD 800m-1bn market. What does the PCIe fabric switch
TAM happens to be. Is USD 1bn a little too high, when you're thinking about people spending
across the board, not just like a single customer opportunity?

5

5

6

6

AI & Cloud Infrastructure Industry & Astera Labs 每 Cloud Systems Architect at Microsoft Corp 每 9 October
2024

I see the opportunity being very isolated to head node connectivity between the CPU [central
processing unit] and maybe some NICs [network interface cards], maybe some storage, but not
really going to be this scale-up cluster type of switch chip by any means. It's very much just like
a head node connectivity scale-out option in a single rack, not doing rack-to-rack. That's how
I've been thinking about what Astera can target.

Do you think for the target set that we're talking about, Broadcom still has 95% share of the
market? I'm sure they're not just going to roll over and give Astera one-third or half of the
market.

The pie in the sky story is that if, CXL [compute express link], and by default PCIe, because CXL
is a PCIe-based standard becomes the memory fabric, but if that doesn't happen, then this
market doesn't get anywhere much larger than USD 1bn, right?

I feel like it's more of the pooling one. Now that we're at 1 DIMM [dual in-line memory module]
per channel core count going through the roof, eventually, you're going to need large enough
memory pools that have compute capability to do all the host biassing (ph) and stuff. That's
when I think that CXL matters a little bit more, but I don't think we get there until 2028-29.

On the retimer side of things, the big thing that everyone is debating about is, you used to have
an eight GPU [graphics processing unit] tray for an H100 and depending upon what types of
NICs or SSDs [solid-state drives] that was attached to, you could probably have 8-24 retimers,
because every GPU needed one. If you were trying to connect to the storage, you needed to add
another eight if you wanted to connect all the NICs, you could even add another eight. Moving
forward for GB200, the NIC is right on the tray, so there's no need for GPU to NIC connections.
It's up for debate whether or not the GPU to CPU is even necessary because of the form factor of
the two CPU to two GPU. It feels like the only retimer need left is storage.

There's 72 GPUs, but it's a two CPU and two GPU form factor. There's technically 36 of those
things. You probably still need 36 retimers for the storage, but maybe you don't connect to
every single (talking over each other).

How much pull does the Grace Blackwell one have? Do you think the mix of Nvidia GPUs that are
sold next year and the year after that, are Grace-based from a processor standpoint? Is it 10%,
20% or 60% of the mix? It feels like no hyperscaler wants to pay the Grace penalty.

You have a lot of chatter from Broadcom and Marvell saying they're selling retimers too. When
you think about the fact that you're probably paying USD 500,000 or maybe USD 1m or north of
USD 1m depending on how densely clustered your server is and a retimer is, USD 30, USD 40 or
USD 50. Okay, sure you have eight of them, so you're still talking a couple hundred bucks. In the
grand scheme of things, does it make sense to switch off of them and use Broadcom and
Marvell?

7

7

7

8

8

9

9

10

Private and confidential

2

AI & Cloud Infrastructure Industry & Astera Labs 每 Cloud Systems Architect at Microsoft Corp 每 9 October
2024

Trying to think about what the retimer TAM could turn into over the longer term, maybe by '27
or '28. When you think about what Nvidia is selling right now, there's a lot of component fluff
in there. They're able to do that because they're getting 70-80% margin on everything that
they add in. If you inflate the overall system cost and stick to getting like 75-80% margin, that
benefits them. Eventually, the purchasers are going to look at this thing and be like there's a lot
of stuff that's in there that isn't that necessary. I can do without 30-40%. It feels like there's a
chance that retimers get included there. When you think about the server architecture and how
it's going to evolve over the next 3-4 years, is there a world in which you can see these racks set
up in a way that doesn't need any retimers? How do you see things evolving? Once we do slow
down the spend, which probably does happen somewhere in the '26-'28 time frame, what
happens to the retimer need? Where are they always going to be necessary? How should I think
about what that means for the amount of retimers that are needed in steady state?

If servers are going up, isn't GPU per server likely going up too? Some of that can counteract
that maybe retimer per server when you think about, retimer per GPU that goes down a little bit.
GPU per server is going up over the time, and so Retimer per server, is there a world where
maybe it actually doesn't fall or do you still think it falls?

Let's say, for the Ethernet-based switches, do you expect those to have retimer capability
integrated into them? In the sense that they're going to take some share from MV switch [sic]
on the front end over the longer term? Do you think that increases (talking over each other)?

What does all this mean for A Lab? Do they need to come out with a co-packaged optics product
in the grand scheme of things to remain relevant? How do you think about it?

Taking a quick look at my model, for this past year, it feels like retimer units grew by a bunch,
but then when you think about 2025, is that still growing at a really nice clip because the Grace
mix is not that＃ If I'm trying to draw the slope of the curve for retimer units, eventually,
they're going to decline. When do we get there? How many more years of retimer demand
remaining strong and the units can continue to grow?

It's probably not worth spending too much time on the CXL controller then because I feel like
that's all like database warehousing and (talking over each other).

How would you compare the DGX or HGX ports? If it's H100-based vs B100-based, 8 GPU tray?
Is the retimer opportunity falling, when you think about just buying that particular form
factor?

Why would you have wanted to manage the individual GPUs at Hopper and not do it anymore at
Blackwell if you're not using a Grace CPU?

Why would Astera say that historically, there was a one-to-one attach for every GPU at Hopper?

At Hopper, if they did X dollar content at Hopper, they think their content at Blackwell is going
up, no matter what the configuration. For hyperscaler deployments that don't use Nvidia, but
rather use home-grown AI accelerators, they think that their content opportunity is going to go
up by 5x, right?

What about AWS [Amazon Web Services]?

Private and confidential

10

11

11

11

12

12

13

13

14

14

15

3

AI & Cloud Infrastructure Industry & Astera Labs 每 Cloud Systems Architect at Microsoft Corp 每 9 October
2024

None of this contemplates the back-end scale up clustering side of it? There's four per board
two CPU, but they're still clustering a bunch of those together. I've heard that there's a need for
a retimer on the back-end of them because they're so spread out, less dense than what Nvidia
packs together, no NVSwitch that's capable＃

15

Private and confidential

4

AI & Cloud Infrastructure Industry & Astera Labs 每 Cloud Systems Architect at Microsoft Corp 每 9 October
2024

AI & Cloud Infrastructure Industry & Astera
Labs 每 Cloud Systems Architect at Microsoft
Corp

Transcription begins

Analyst:
The main focus of the call is on Astera Labs, that just carried out their PCIe [peripheral component
interconnect express] fabric switch, so that could be a good place to start out. Was this something that
you were expecting? Any early reaction to the new product coming from Astera Labs, if you expect it to
get any decent uptake?

Specialist:
Yes. I just saw the news today that they have debuted the Scorpio. Actually, Scorpio is actually the name
of a Broadcom. It's not a data centre part, but it's actually an automotive switch, but yes. I see it's also
PCIe Gen 6, yes.

Analyst:
To my knowledge, Broadcom has 95% share of PCIe scale-out switches (talking over each other).

Specialist:
Correct. From my understanding (ph), it is a very minor player.

Analyst:
What would you think about the likelihood that Astera starts to take some share? Obviously, the
retimer much less complex silicon, but at the same time, they're claiming that they are Gen 6. I don't
think Broadcom's Gen 6 PCIe switch chips have even started to ship in volume. To some extent, they're
jumping ahead of Broadcom, at least from a PCIe standard standpoint. What do you expect? Do you
think that they're going to gain any decent amount of share on the scale side of things?

Specialist:
PCIe Gen 6 is where the market is actually not clear. If you're talking about connecting＃ What are we
connecting to the switches? I think that's where we need to focus. You have the Ultra Ethernet
Consortium, they're focused on the whole side, CPU side, fanout, as well as the GPU to GPU interconnect,
not within the same coherency domain, but outside that domain, or AI, the accelerator domain.
Someone is going to do an Ultra Ethernet bridge. They're changing the UET, they're changing the
transport layer for Ethernet congestion. Someone is going to have to do a UET and an Ethernet switch.
The UAL side, it's not really mature yet, that's like AMD is pushing that Broadcom with the Drew (ph)
because they were unsure like, "Hey, do we want to give away our proprietary?" (ph) This is like
basically they compete with NVLink, NVSwitch. This is the top side of the fanout. The CPU managing
four GPUs or connecting a CPU to an NVSwitch that fans out to multiple GPUs in the same coherency
domain. I think that's what you're trying to replace here. The traditional CPU, big data cloud storage
market, they may be happy with PCIe Gen 5. If you want PCIe Gen 6, the question is, do you want UEC or
do you want UAL or NVLink, NVSwitch? How big is the market? I think that's the question because AMD
is throwing their weight behind UAL to compete with NVLink, NVSwitch.

Private and confidential

5

AI & Cloud Infrastructure Industry & Astera Labs 每 Cloud Systems Architect at Microsoft Corp 每 9 October
2024

Then there's no PCIe Gen 6 SSD today. There's only PCIe Gen 5 SSDs. The highest, I think it's the
Samsung, I forget, it's the PM-something. I forget the exact part number, but it's in that family. They
have 16 lanes of Gen 5. That's the highest individual SSD. The DPU market is not really ramping. The
DPU, for data centre, it's not really that interesting any more. There's the SmartNIC market, but that's
again, it's going to be more like they have Ethernet UEC going forward. How big is the market for PCIe
Gen 6 switch? The only thing I think you can connect to it is going to be＃ People will use it for generic AI
accelerators if they're not doing UALink. I'm pretty sure everyone else is going to, for the back-end
fanout, they're going to use the Ultra Ethernet because that's pretty far along. There's a lot of
consortium members. There's a lot of weight behind that. UAL is undecided. You could potentially see
PCIe Gen 6 used for next-generation GPU for non-AMD, non-Nvidia solutions, or you can (talking over
each other) switches, like someone is doing (talking over each other) network.

Analyst:
Is that the situation is at Gen 5 is in already? Broadcom is probably only selling a PCIe switch in those
specific instances where Amazon, Microsoft and Meta are looking at their custom ASIC [application-
specific integrated circuit] opportunity and are not going either the Ethernet or Nvidia proprietary link
route. Is that already the case?

Specialist:
No. I think that you have＃ There are PCIe Gen 5 SSDs.

Analyst:
Okay, so an add storage.

Specialist:
Yes, so you have storage, you have storage area networking. You have, in general, CPUs connected to
multiple peripherals. Actually, let me think about that one. Again, CPUs for expansion connects, CPUs
that are not the main host, but like outside host managing storage or the enterprise market that may be
doing hyper-converged infrastructure. There's some demand for PCIe Gen 5 switches there.

Analyst:
Astera Labs is trying to claim that it's a USD 5bn market. I've been trying to run some quick numbers,
and it feels like it's more an USD 800m-1bn market. What does the PCIe fabric switch TAM happens to
be. Is USD 1bn a little too high, when you're thinking about people spending across the board, not just
like a single customer opportunity?

Specialist:
No, I understand. I think it's in the ballpark of USD 1bn, maybe USD 1.2bn. I don't see the USD 5bn simply
because you have the AMD throwing their way behind UAL, you have NVLink, NVSwitch and then you
have the Ultra Ethernet.

Analyst:
On UAL [Ultra Accelerator Link] and Ultra Ethernet, I would think that if Astera is going to come out and
say, "It's going to be a USD 5bn TAM", they're taking the view that they're going to be the fabric of
choice over Ultra Ethernet and Ultra accelerator link, which fees like (talking over each other).

Specialist:
No, no. That's not＃

Analyst:

Private and confidential

6

AI & Cloud Infrastructure Industry & Astera Labs 每 Cloud Systems Architect at Microsoft Corp 每 9 October
2024

Highly unlikely?

Specialist:
Yes, if you include all those, then the TAM can be that high, but they won't get that share. The Ethernet
has lower latency than PCIe, and it is generally seen as a better connectivity. PCIe can have higher
bandwidth, but the UAL has some specific adaptations done, or you can scale up to, say, 1,000 nodes. You
can't do that with PCIe. Their PCIe switch, you can't connect 1,000 GPUs to that.

Analyst:
You probably can't even connect 100?

Specialist:
Yes, I think it may be like 100-200 lanes, something like this. It's basically their switch is going to
replace the direct NVSwitch part that is the older generation NVSwitch likely. The one for the Blackwell, I
think, connects 256 GPUs. This is still a much smaller scale than Ethernet. You can think Ethernet
switch, I may be able to switch between thousands of endpoints. The UAL is supposed to do 1000 nodes.
AMD said initially, they're going to try 256 NVLink, NVSwitch does. The Blackwell, 256. The one today is
18 or something like that or 36, excuse me. Maybe they can connect 20 GPUs, but I don't see why anyone
would use their part.

Analyst:
I see the opportunity being very isolated to head node connectivity between the CPU [central
processing unit] and maybe some NICs [network interface cards], maybe some storage, but not really
going to be this scale-up cluster type of switch chip by any means. It's very much just like a head node
connectivity scale-out option in a single rack, not doing rack-to-rack. That's how I've been thinking
about what Astera can target.

Specialist:
Correct.

Analyst:
It sounds like you generally agree.

Specialist:
Yes.

Analyst:
Do you think for the target set that we're talking about, Broadcom still has 95% share of the market?
I'm sure they're not just going to roll over and give Astera one-third or half of the market.

Specialist:
They bought Elastic Cloud that was doing a CXL 3.0, 3.1 switch. Some of the people weren't happy after
that acquisition. Then they went to Astera and then Marvell bought Tanzanite. I think if the market
really takes off, I think Broadcom will say, "We're going to take it more seriously." They've been hitting
pause on that. They've been diverting resources from that to focus on their custom ASIC products group.

Analyst:
The pie in the sky story is that if, CXL [compute express link], and by default PCIe, because CXL is a
PCIe-based standard becomes the memory fabric, but if that doesn't happen, then this market doesn't
get anywhere much larger than USD 1bn, right?

Private and confidential

7

AI & Cloud Infrastructure Industry & Astera Labs 每 Cloud Systems Architect at Microsoft Corp 每 9 October
2024

Specialist:
If you want to do CXL.mem, you're trying to do attached memory for sharing, maybe there's some
people have looked at doing this over UCIe for expanding host coherency and other things. Is it attached
to a switch though? There's the Marvell Structera that's near memory computing that's doing the same
thing, this memory expansion capability, so a pure memory expander without compute capability, I
don't think there's a market for.

Analyst:
I feel like it's more of the pooling one. Now that we're at 1 DIMM [dual in-line memory module] per
channel core count going through the roof, eventually, you're going to need large enough memory
pools that have compute capability to do all the host biassing (ph) and stuff. That's when I think that
CXL matters a little bit more, but I don't think we get there until 2028-29.

Specialist:
I think that you're right. CXL 3.1 with the back-end validation and unordered I/O is attempting to do, I
think what you described, if you do that and you do memory pooling across that, where you have
multiple accelerator devices to perhaps multiple hosts, that are pooling memory. I think this is where
people have looked beyond this, that works well, but I think they would use CXL only for the memory
expansion, but they would use the actual protocol layers of UAL or UEC.

Analyst:
I totally agree with that. I appreciate the fact that it seems like industry pull is moving more in the
direction of UAL and UEC [Ultra Ethernet Consortium] and maybe less in the direction of CXL. That
makes plenty of sense.

On the retimer side of things, the big thing that everyone is debating about is, you used to have an
eight GPU [graphics processing unit] tray for an H100 and depending upon what types of NICs or SSDs
[solid-state drives] that was attached to, you could probably have 8-24 retimers, because every GPU
needed one. If you were trying to connect to the storage, you needed to add another eight if you wanted
to connect all the NICs, you could even add another eight. Moving forward for GB200, the NIC is right
on the tray, so there's no need for GPU to NIC connections. It's up for debate whether or not the GPU to
CPU is even necessary because of the form factor of the two CPU to two GPU. It feels like the only
retimer need left is storage.

Specialist:
To be clear, the NVSwitch has built-in retimer capability for connecting to the GPU side, to the NVLink
side of those things. You still need the retimer to connect to the CPU host if it's not the Grace, if it's not
the GB200, but an Intel CPU, let's just say, but yes, in general, the need is lesser.

Analyst:
For an NVL72, those are Grace or are they selling NVL72s?

Specialist:
You can buy the B200 GPU and have them managed by Intel CPUs or AMD CPUs. I'm saying in the
configuration that Nvidia had at the GTC and what they want＃ You're a GPU as a service provider, we
just want to buy stock hardware from them. You buy a rack that has the NVL, like it has the NVSwitch
that's going to connect to＃ That has a DAC cable. It's a copper, active copper. That's going to connect to
the NVSwitch, that's the Quantum-2 InfiniBand switch. It's going to connect to the boards that have the
NVSwitch on them. That NVSwitch has a built-in retimer that is for the GPU with NVLink. The Grace
Hopper CPU is on the same board. I don't see in the NVL36, actually, they killed the NVL36. There's now
only NVL72. On the complete Nvidia ecosystem, if it's that, I don't see where the retimer is, unless

Private and confidential

8

AI & Cloud Infrastructure Industry & Astera Labs 每 Cloud Systems Architect at Microsoft Corp 每 9 October
2024

you're connecting to external storage. Yes. Okay. If you're connecting to external storage, maybe then
you have the retimer there.

Analyst:
There's 72 GPUs, but it's a two CPU and two GPU form factor. There's technically 36 of those things.
You probably still need 36 retimers for the storage, but maybe you don't connect to every single
(talking over each other).

Specialist:
No, the storage doesn't connect to each server. The storage is going to be connected through a BlueField
DPU or it should be＃ There may be some central piece like network, there's going to be a storage area
network controller that may connect to a bank of SSD. You only need the retimer for that, and you have
16 lanes. You may need 96 lanes, so you need maybe six retimers for the whole rack. That storage is for
the whole rack. It's not just for one server. Per rack, you may need six retimers. That's what I'm
thinking. Now if you go to the world where it's the Intel managing it, then yes, you need to connect to
each NVSwitch, you need 64 lanes, you need four retimers per 64 lanes. You need almost one retimer per
GPU to be managed by the CPU to connect to the NVSwitch.

Analyst:
How much pull does the Grace Blackwell one have? Do you think the mix of Nvidia GPUs that are sold
next year and the year after that, are Grace-based from a processor standpoint? Is it 10%, 20% or 60%
of the mix? It feels like no hyperscaler wants to pay the Grace penalty.

Specialist:
Correct. Yes. You're right. The AWS, they want to ramp their own chip. I think they bought some.
Microsoft has the Nvidia DGX Cloud partnership with access to Nvidia proprietary models for BioNeMo
drug discovery.

Analyst:
When you say a rack, you're talking about NVL72?

Specialist:
Yes, like 72 GPUs, a rack's worth. I don't think Google is really interested to buy any so I understand.
They're active in the UXL Consortium. They're really pushing their TPU v6. Meta is, they are also
probably going to buy a rack's worth. They would prefer not to use their CPU because you get better
performance with AMD and Nvidia＃ Sorry, the Intel CPU and then you can avoid lock-in into the Nvidia
ecosystem forever. You may have to rewrite the PCIe coherency driver to manage those GPUs for doing
GPU direct RDMA and some other things. The NVSHMEM, you have to make some modification to that. I
think those companies do have the resource to do this. I think Oracle will probably not do that. Oracle
will just buy the NVL72.

Analyst:
With the Grace?

Specialist:
Yes, with the Grace. For all of their demand. all the GPU-as-a-Service vendors for all their demand. If I
look at for the Blackwell demand, what percent is with the Grace, what percent is without the Grace, I
think it should be 60% without the Grace, yes.

Analyst:
It's 40% just because, I guess the way that I think about it is, these guys are probably doing their last leg

Private and confidential

9

AI & Cloud Infrastructure Industry & Astera Labs 每 Cloud Systems Architect at Microsoft Corp 每 9 October
2024

of training deployment and 40% of their needs are training. Moving forward, they're probably going to
be able to just continue to use some＃ I don't see much need for that many more net incremental training
clusters deployed. A lot of it's now going to be shifting to thinking about what you need from an
inferencing standpoint and that's a completely different story. Do you disagree with that? Let's say, next
year's Blackwell demand, 40% of it has Grace alongside it. That's not going to become 60%, 70% or
80% if we talk about 2-4 years out. That's a ceiling or do you disagree?

Specialist:
I think that there will still be continued use of Nvidia for training, but the inference is going to take over
in 2025 as the dominant. Right now, it's probably 65% training, 35% inference. It should be the other
way around at the end of '25.

Analyst:
You have a lot of chatter from Broadcom and Marvell saying they're selling retimers too. When you
think about the fact that you're probably paying USD 500,000 or maybe USD 1m or north of USD 1m
depending on how densely clustered your server is and a retimer is, USD 30, USD 40 or USD 50. Okay,
sure you have eight of them, so you're still talking a couple hundred bucks. In the grand scheme of
things, does it make sense to switch off of them and use Broadcom and Marvell?

Specialist:
I don't think Nvidia will buy any Broadcom parts. They may buy Marvell. Maybe the Taiwanese ODM may
say, "Hey, Astera, drop your price. I have some competitors." Let me just use it to make them believe.

Analyst:
You're of the opinion, they probably keep market share, but pricing is going to be a little bit under
pressure.

Specialist:
Yes.

Analyst:
That's what I'm thinking too. I feel like when Broadcom first announced this back in like February or
March, it was like, "Astera's market share is going to fall to 50-60%." I'm coming around to the idea
that maybe their market share stays at 70-80% at just a lower ASP or maybe ASP stays flat because they
can't raise prices at each next generation that they come out with.

Specialist:
Correct.

Analyst:
Trying to think about what the retimer TAM could turn into over the longer term, maybe by '27 or '28.
When you think about what Nvidia is selling right now, there's a lot of component fluff in there.
They're able to do that because they're getting 70-80% margin on everything that they add in. If you
inflate the overall system cost and stick to getting like 75-80% margin, that benefits them. Eventually,
the purchasers are going to look at this thing and be like there's a lot of stuff that's in there that isn't
that necessary. I can do without 30-40%. It feels like there's a chance that retimers get included there.
When you think about the server architecture and how it's going to evolve over the next 3-4 years, is
there a world in which you can see these racks set up in a way that doesn't need any retimers? How do
you see things evolving? Once we do slow down the spend, which probably does happen somewhere in
the '26-'28 time frame, what happens to the retimer need? Where are they always going to be
necessary? How should I think about what that means for the amount of retimers that are needed in

Private and confidential

10

AI & Cloud Infrastructure Industry & Astera Labs 每 Cloud Systems Architect at Microsoft Corp 每 9 October
2024

steady state?

Specialist:
Yes, absolutely. I think that the retimer volume will go down for sure. I think their volumes will go down.
The server volumes overall are going up, but the number of retimer per server will go down. Volumes
will either stay flat or go down, likely go down by '27. For sure, you'll see the impact in '26. I think that
you're correct that the volumes may decline 10-15%.

Analyst:
If servers are going up, isn't GPU per server likely going up too? Some of that can counteract that
maybe retimer per server when you think about, retimer per GPU that goes down a little bit. GPU per
server is going up over the time, and so Retimer per server, is there a world where maybe it actually
doesn't fall or do you still think it falls?

Specialist:
Yes, but I think you're going to find that see, NVSwitch has the retimer capability built in.

Analyst:
Yes, that's the back-end.

Specialist:
You're talking about the front-end CPU connection to NVSwitch. Is that right?

Analyst:
Yes, I guess it could be connection to NVSwitch, direct connection to the GPU.

Specialist:
You won't have direct connection to GPU, but the architecture will change.

Analyst:
Let's say, for the Ethernet-based switches, do you expect those to have retimer capability integrated
into them? In the sense that they're going to take some share from MV switch [sic] on the front end
over the longer term? Do you think that increases (talking over each other)?

Specialist:
Ethernet-based switch is going to use Ultra Ethernet, and that is going to have DSP. There's an optical
DSP. Inphi does the DSP and then there's Credo, that's the linear drive, so that market is also＃ There's
no discrete retimer there. That retimer capability is part of what the DSP does and even that's getting
eliminated and integrated into the switch.

Analyst:
What does all this mean for A Lab? Do they need to come out with a co-packaged optics product in the
grand scheme of things to remain relevant? How do you think about it?

Specialist:
Co-packaged optics for what. You have to have co-packaged optics where you do the main switch ASIC
or you want to do the Ultra Ethernet or whatever other switch ASIC or the UAL, I don't believe they're
part of that consortium. You need to either do that a product and do that with CPO or you want to do it
over copper and then you integrate the retimer capability into that part. CPUs are not going to have
retimers in them, but the CPU side, maybe there's the retimer connecting to the NVSwitch or whatever

Private and confidential

11

AI & Cloud Infrastructure Industry & Astera Labs 每 Cloud Systems Architect at Microsoft Corp 每 9 October
2024

other parts. You do have those parts. I think the CPU quantity is not going up that much. It does go up
like the server volume goes up, but if you're not participating in the back-end of the more GPUs and you
cut out that volume, it's going to more than offset because now the CPU is not directly going to talk to
the GPU anymore going forward. That's the problem, so you don't need the retimer in there.

Analyst:
Taking a quick look at my model, for this past year, it feels like retimer units grew by a bunch, but then
when you think about 2025, is that still growing at a really nice clip because the Grace mix is not that＃
If I'm trying to draw the slope of the curve for retimer units, eventually, they're going to decline. When
do we get there? How many more years of retimer demand remaining strong and the units can
continue to grow?

Specialist:
I saw their IPO prospectus, but I haven't been following like what their recent forecasts are from
revenue. I would say, though, that I expect that there should be＃ The PCIe Gen 5 retimers are not used
on the Blackwell. Blackwell, whatever retimer there is, is going to be Gen 6. You agree, right?

Analyst:
Yes, agreed.

Specialist:
AMD MI325X is going to have the next version of XGMI, and they're working on UALink, so for the
MI375 and the MI400. I'm not seeing who's buying the PCIe Gen 6 retimers, it must be only CPUs to
manage or connect to NVSwitch or connect to a UAL bridge or an Ultra Ethernet, UAL to UEC bridge. The
host does some management. The GPU may share that host memory. Maybe there's some CXL memory
pooling there to that UAL, UEC bridge as well. Maybe there's the retimer there. That's the only retimer
usage I'm seeing. Maybe some storage, okay, you have connection to storage, yes.

Analyst:
Could 2025 be a down year units-wise?

Specialist:
I'm expecting it to be a down year units wise, yes. There may still be good H200 demand. I think 2026,
for sure, will be a down year, '25 past July will be down because it will take some time for everyone to get
Blackwell. Not everyone gets today, it's ready, right?

Analyst:
It's probably not worth spending too much time on the CXL controller then because I feel like that's all
like database warehousing and (talking over each other).

Specialist:
You have Marvell Structera X that does near memory compute that has expansion capabilities. You have
to look and track how is the sale of that part because that's doing near memory compute. It's not just
doing dummy memory expansion, which there was almost like no demand for. There was initial AWS
demand and then people started adding more cores. As you're adding more cores that have better
performance NoC, and then you have＃ DDR6 is still delayed. There's an LPDDR6, but DDR6 itself is
delayed because the market has not had a need for this. People are happy with DDR5 8500 or 7200. The
8500 is DDR6. If you're not even seeing a new DDR5, then why are you going to want more memory?
Everyone runs the kernels compute bound, it's not memory bound (talking over each other) DDR5 8600
now, but yes.

Private and confidential

12

AI & Cloud Infrastructure Industry & Astera Labs 每 Cloud Systems Architect at Microsoft Corp 每 9 October
2024

Analyst:
That was really just my main question, it's been something that had a lot of hype probably 2-3 years ago
(talking over each other).

Specialist:
There was some other Korean start-up that like SK Hynix guys raised some money to do that, too. Yes,
these people will have to pivot. They'll have to do near memory computing or some other thing. There's
always been hype around that. The only use case I see is that if you have a UAL UEC bridge that needs
memory expansion to that, then you have the use case there. This memory expansion has to be to a
switch. It's not going to be just to a bunch of compute nodes. Otherwise, you're better off doing a
Structera X. You're going to have to have some compute in that chip as well.

Analyst:
How would you compare the DGX or HGX ports? If it's H100-based vs B100-based, 8 GPU tray? Is the
retimer opportunity falling, when you think about just buying that particular form factor?

Specialist:
The B100 got killed. They're going to only sell the B200. Everyone buying the H200 now, I don't know
how many people are still buying H100. Maybe I misunderstood your question.

Analyst:
I was just generalising. I was mostly focused on like Hopper vs Blackwell, but I totally appreciate that
nuance.

When you're thinking about Hopper vs Blackwell in those eight GPU tray configurations, do you see a
need for the retimers still, such as the Gen 6 ones that are going to be sold? I just wanted to make sure
that I'm understanding correctly that it's not just the Grace.

Specialist:
If you're doing a non-Grace CPU, you may need that to connect to the NVSwitch or you may still want to
manage individual GPUs, in which case you need that to connect to the individual GPUs.

Analyst:
Why would you have wanted to manage the individual GPUs at Hopper and not do it anymore at
Blackwell if you're not using a Grace CPU?

Specialist:
No. The H100 GPU, the CPU is individually managing. There is an NVLink and NVSwitch. The NVSwitch is
connecting on the back-end the GPUs together, but you still have to have the CPU talking to each GPU to
manage it. I'm saying with the Blackwell, not the Grace CPU. You do an Intel CPU, the NVSwitch, so
there's a Quantum-2 InfiniBand switch that connects to two NVSwitch ICs, and those are going to
connect to the GPUs with the DAC cable, right?

Analyst:
Yes.

Specialist:
The CPU should be talking to the NVSwitch. It's not going to be talking to the GPU directly. That's the
ideal case if you want to replace the Grace. You might need the retimer there.

Private and confidential

13

AI & Cloud Infrastructure Industry & Astera Labs 每 Cloud Systems Architect at Microsoft Corp 每 9 October
2024

Analyst:
There's two CPUs, so it's just two retimers or because there's eight GPUs (talking over each other).

Specialist:
No. It's for 16 lanes though. You need 64 lanes, so you'll need four retimers.

Analyst:
Why would Astera say that historically, there was a one-to-one attach for every GPU at Hopper?

Specialist:
Hold on. That's the case for the Hopper GPU. There's a Grace Hopper CPU that they just reuse the name.
There's a Hopper GPU. For the case of the Hopper GPU, which is the H100, H200 series, there is one-to-
one CPU management, which is not the case for the Blackwell GPU that is managed by a Hopper CPU,
which is not the same thing as the Hopper GPU.

Analyst:
I'm just gathering my notes here because you talk to a different person and they say something
differently, even Astera management team will say something different.

Specialist:
A lot of people saying they're expert, but you need to talk to someone who has actually worked on like＃
See, there's a lot of people who are server architect who say that, and they just manage the vendor. You
need someone who has actually designed the GPU fabric and I/O connectivity, who has actually designed
PCIe controller and familiar with the protocol, ethernet controller, understands GPU, CPU coherency and
how this has to impact. They would be the people like that means someone who does that level of
architecture. Just the general like someone who's the server architect does not know all these details.
(Talking over each other) Nvidia gives them, that's all they do.

Analyst:
At Hopper, if they did X dollar content at Hopper, they think their content at Blackwell is going up, no
matter what the configuration. For hyperscaler deployments that don't use Nvidia, but rather use
home-grown AI accelerators, they think that their content opportunity is going to go up by 5x, right?

Specialist:
You're saying that for the non-Nvidia and non-AMD, they're going to get 90% of the share to connect
those with retimers. Is that right, for a CPU to manage those?

Analyst:
Yes.

Specialist:
The [MTIA] chip has a CPU inside. It's a systolic array that has a RISC-V CPU that does scalar and vector
extension. They have their own floating point and matrix multiplication in those for the rest of the AI
element. The data chip has LPDDR5X. I don't think there's an external CPU managing＃ The Google TPU
is managed by CPUs. Those CPUs, I believe they do the same four-to-two, like they do four TPUs per
board, something like that, and they have two CPUs managing them. They don't do a base board.

Why is there a retimer? If you want to do eight, you have a separate base board that has the GPUs
mounted vertically. There's a retimer and the CPUs are mounted separately. There's a longer distance.
You need a retimer to cover the distance. In the Google TPU case, the servers are smaller. They're trying
to do them with air cooling. They're trying to pack four TPUs for two CPUs. I don't see the retimer there.

Private and confidential

14

AI & Cloud Infrastructure Industry & Astera Labs 每 Cloud Systems Architect at Microsoft Corp 每 9 October
2024

Now the Project Maia, there is an external CPU to manage, and they do use retimer, sorry, I take it back,
it's also four＃ They do air cooling and they do four Maias with two CPUs. There's no retimer. I think they
may have provisioned to use the retimer in case, but I think the production configuration is they don't
ship with retimer.

Analyst:
What about AWS [Amazon Web Services]?

Specialist:
AWS Inferentia has a CPU doing management, but I believe they're also doing the same 2-4 [sic].

Analyst:
What about on the back-end clustering＃

Specialist:
They do their own CPU, too. AWS has their own Graviton CPUs.

Analyst:
Unlikely to use NVSwitch.

Specialist:
No, you cannot use NVSwitch to talk to a non-Nvidia GPU. You don't get the NVLink protocol. You can
buy NVSwitch if you want to do your own server with an Nvidia GPU if you're a big enough customer.

Analyst:
None of this contemplates the back-end scale up clustering side of it? There's four per board two CPU,
but they're still clustering a bunch of those together. I've heard that there's a need for a retimer on the
back-end of them because they're so spread out, less dense than what Nvidia packs together, no
NVSwitch that's capable＃

Specialist:
You're saying they have to connect to a SOP (ph). Yes, you're correct for connecting the GPUs to the＃ We
said that Microsoft does have the retimer, actually, they will probably populate to connect to a switch,
yes. They have both ethernet and PCIe connectivity. They may be populating four retimers, but one
retimer per chip, but I don't know like their configuration is not high-volume deployment. Let me think
here. In terms of AWS, how do they connect? What's their answer to NVSwitch? I think they're focused
on getting the individual chip performance very high, and they may take the penalty in the short term.
That is, they will say, we'll do a 2-4 [sic] for that reason, and we'll connect over ethernet for inference
(audio cuts out).

Analyst:
I was trying to get a quick understanding the back-end scale-up side of it and for the custom and AI
processor side of things. Do you see that retimer needs sticking around for a little while longer? We could
probably just wrap up once we walk through that part.

Specialist:
I do think that it will stick around a little bit longer for the demand from maybe Microsoft perhaps, and
maybe AWS, yes. I don't think Google Meta for sure, no.

Analyst:

Private and confidential

15

AI & Cloud Infrastructure Industry & Astera Labs 每 Cloud Systems Architect at Microsoft Corp 每 9 October
2024

Yes, that makes sense because Google is doing its own thing and Meta's processor [is poor]. Everything
that we've talked about for Astera Labs so far has been front end because of this NVLink, NVSwitch
capability that defeats the purpose of needing a retimer. It's just not necessary for Nvidia configuration
back-end. Do you think that the back-end opportunity for Microsoft and AWS is bigger than what we've
talked about for Nvidia in the past? I'm trying to get a feel for when Astera tries to tell me that because
the back-end is included for these homegrown ASIC deployments that the opportunity for retimer goes
up by 5x vs Hopper.

Specialist:
AWS, I don't believe, is a member of the Ultra Ethernet Consortium and they're certainly not part of UAL.
They're not even part of UXL. I think you're right that they're trying to work on getting a better
performance GPU.

Analyst:
All right. That's helpful because I feel like I was about to walk away feeling worried about Astera, but it
feels like there might be enough with the back-end stuff from at least two customers that it offsets some
of the headwind that they're going to face with the Grace Blackwell dynamic.

Specialist:
Yes.

Disclaimer

Transcription ends

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



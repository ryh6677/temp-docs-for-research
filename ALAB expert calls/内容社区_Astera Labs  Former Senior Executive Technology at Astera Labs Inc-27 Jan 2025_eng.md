COMMUNITY

65d0d6538a8911da05d11de9b49cc840996c80c0

Astera Labs 每 Former Senior Executive,
Technology at Astera Labs Inc

Former Employee | 27 January 2025

Specialist Background

> Over 30 years' experience in the IT industry, with deep insights into the AI landscape, cloud

infrastructure and

> Knowledgeable on Astera Labs' chips and next-gen products, long-term strategy and market

positioning

> Well-placed to discuss retimers and CXL (compute express link) controllers, as well as market

risks and growth opportunities

Contents

Maybe just as a starting point, when you think about the business environment, Astera Labs is
competing in across its various product sets. Thinking about where it might be trying to go,
what do you think has changed most maybe to both the positive and the negative over the last
6-12 months? Can we discuss how they look at the competitive landscape and the market
opportunity late last year, early this year vs maybe how thinking might have changed over that
timeframe?

Would I be right to be thinking that 80-90% of revenues for Astera Labs is non-China in
nature, and so that market share impact would be pretty minimal at the end of the day?

Credo sounded incrementally bullish on their cable opportunity. I think they guided their Q4
revenues up by 67% sequentially, and they're talking about 50% growth into the next year.
When you think about the fact that they're obviously ramping up with AWS [Amazon Web
Services] more recently, does that concern you in terms of the market share that Astera Labs
can get in PCIe [peripheral component interconnect express] cables with AWS?

Do you think it will be bad for Astera Labs's Taurus product trajectory at the very least? Do you
think that it's more of like an all tides rising where the opportunity set has just gotten much
larger?

3

4

4

4

Astera Labs 每 Former Senior Executive, Technology at Astera Labs Inc 每 27 January 2025

Maybe to talk a little bit about the Scorpio switch product 每 you've got the P-Series PCIe switch
that's for head node interconnectivity. Am I right to think that where that gets adopted, it'll be
a 1:1 attach rate on a per GPU [graphics processing unit] basis? Is there any opportunity that it's
higher or lower just as you think about where the P-Series chips will make sense in terms of
installing into the systems that decide to go there?

Does that remove the need for a retimer in those instances because the PCIe switch is actually
doing the interconnect?

If I use AWS as the use case, it sounds like they're doing two different form factors. One is like a
16-accelerator rack and the other is a 64-accelerator rack. I heard that most customers are
probably going to prefer the 64 one. When I think about the content-per-cluster opportunity.
Am I right to think I can conservatively just say there are probably 64 retimers and 64 switches
in that? Is there any optimisation at a system level that I should lower my estimates in terms of
thinking about what content might exist in a per-cluster basis?

Are those bigger PCIe switch chips on the front end? Is that X-Series flavour of the Scorpio
where it's a bigger switch chip on the back end maybe something to do with the fact that the
interconnect fabric is just a wider area, and so you need a bigger chip at the end of the day? Are
you seeing those bigger PCIe chips on the front end of the rack or only on the back end?

When the Scorpio product got announced initially, the big pitch around P-Series was that it was
only 64 lanes. Because of that, when you compare it on a price point vs the Broadcom 144-lane
chip, it's orders of magnitude cheaper with the argument being that hyperscalers are under-
utilising their PCIe switch ports. You brought up the point of maybe 144 gives you nine ports,
but I've heard that those aren't really being utilised fully at the end of the day. It sounds to me,
at the end of the day, the customers still want the optionality. Do you think that the P-Series,
which started as a 64-lane chip, needs to expand in terms of flavours to be higher lane count to
be competitive in this market just based on the cloud customer desires?

I'm starting to get more people asking me about co-packaged optics. My sense is that we're at
least two years away from that being actually inserted in AI data centres. I guess just when you
think about what co-packaged optics provides, how does that remove the need for retimers in
the server? Do you have thoughts on, given the challenges around optics reliability, how far
away we probably are still from co-packaged optics? Am I right to think that we're at least two
years away?

As I think about competitive moats for Astera Labs, how proprietary do you feel the Cosmos
firmware is at the end of the day? Is that a key part of the moat, or does their competitive
advantage come in different forms?

How would you be thinking about where Astera Labs's roadmap can go? They've got four key
product families at this point across retimers, cables, CXL [Compute Express Link] controllers
and a switch now. What do you think the right way to be thinking about? What else they can
bring to the portfolio? What are some easy low-hanging fruit that you think make the most
sense as I think about how this business might evolve over time?

Private and confidential

5

6

6

7

8

10

11

11

2

Astera Labs 每 Former Senior Executive, Technology at Astera Labs Inc 每 27 January 2025

Astera Labs 每 Former Senior Executive,
Technology at Astera Labs Inc

Transcription begins

Analyst:
I wanted to touch base with you to talk through how I'm seeing Astera Labs' business model evolve.
Obviously, we've had a lot of changes in the AI backdrop, and so I figured it would be good to see your
thoughts on a handful of things just given that you spent a little bit of time there, probably thinking
about their longer-term roadmap and that sort of stuff.

Maybe just as a starting point, when you think about the business environment, Astera Labs is
competing in across its various product sets. Thinking about where it might be trying to go, what do
you think has changed most maybe to both the positive and the negative over the last 6-12 months?
Can we discuss how they look at the competitive landscape and the market opportunity late last year,
early this year vs maybe how thinking might have changed over that timeframe?

Specialist:
The competitive landscape, obviously, we (audio distorts) has a retimer business＃ Some retimer
business from AWS. That's what we all know. I don't think I heard anything from Broadcom, even
though they are pushing hard. There is some noise about Montage retimer working, and they are
announcing it, so don't know what's their implication on the US data centre guys. Mostly, there's
nothing. The other one, Credo, tried to do it, but I don't think that's going to matter anyway. Then as you
all know, and I've been telling some time, that Nvidia's B200 system, rack system, had their own issues.
They may go with active cables at some point on what are their system architecture is going to change.
The effect on the PCI retimer business is probably negligible going to B200, at least in my opinion,
because most of the data centre guys, as far as I know, they want to take the blade and then connect to
their own CPU tray and then their own Nic trays. I don't think the retimer business changes that much in
that angle. Of course, initial shipments is probably still the B200 racks and everybody shows some
number of B200 racks, both Microsoft, everybody. I don't think Microsoft will change, but AWS and
Meta mostly buy the GPU trays and then connect to their CPUs and Nics. I'm very confident Meta has
their own Nics with their own RDMA stuff, so they don't want to pay money to Nvidia on that front.

That's where the retimer business still survive. I also know their gen 6 production retimers came back.
Astera, I don't know how they are working on it, but I think they are ready to ship once they test it and
everything is working. That's a good news from Astera's side. My guess is they probably do the gen 7,
PCIe gen 7, even though they're not talking about it, and Nvidia is not talking about it, but there is
certain big data centre guy who wants to go to gen 7, and he's pushing hard. That's the future one, but
it's not far. Last few months, that has no effect, but there is a roadmap to do gen 7. When, how, I don't
know, but that's one thing. I don't see any big impact on the retimer business. The cables are interesting.
Again, they are confident they have a good order for PCIe cable. It's not disaggregated system that much,
but putting eight GPUs in one system vs two GPU, four GPU, they can play the system architecture once
you have PCIe cables. It seems that big customer is ordering too many PCIe cables, it looks like.

The revenue front looks okay because even Marvell has the chip, they don't have a cable at this point.
They can do it, but the qualification time and everything will take quite long while the Astera already
went through that process, so they have a leg up. Once Marvell come with their cables and then these

Private and confidential

3

Astera Labs 每 Former Senior Executive, Technology at Astera Labs Inc 每 27 January 2025

validated, then it's much easy because it's just a replace one cable with other. The trade-off is not that
big at that point. Right now, they still have a moat on that area. Those two what I see is they still can
protect the gen 5 and gen 6 as they start picking up. I think one thing that probably moved to the gen 6 a
little faster is, if my information is right, AWS has a gen 6 Nics also, so their Nitro Nics. If they have gen
6 and they want to move their training to systems with gen 6 Nics, definitely, they need gen 6 retimers
or they need that Scorpio switch. One of those two things they needed. That will be either a growth for
retimers or extra Scorpio switch basically. That's what I see. Competition, I don't see much competition.
Retimer, yes, Marvell playing a little bit, but that I don't see any much news from their side that
something is happening.

Analyst:
When you think about the Montage product maybe improving a little bit, do you see them gaining much
share outside of China hyperscalers at the end of the day just given where they're based?

Specialist:
No. I don't think.

Analyst:
Would I be right to be thinking that 80-90% of revenues for Astera Labs is non-China in nature, and
so that market share impact would be pretty minimal at the end of the day?

Specialist:
I think even China, anybody building AI systems, most of them still Astera customers. Montage may
offer a little bit cheaper. I don't see any impact on that front because a lot of those guys burn their
fingers with Montage because Montage and Astera, they both initially, we announced the same time. Of
course, they have a lot of issues. Someday, they said they gave up and then they came back kind of thing.
Also, customers burn going to Montage. Hopefully, it's working now. You will lose some, but I don't
think it's a lot of revenue from China from this.

Analyst:
Credo sounded incrementally bullish on their cable opportunity. I think they guided their Q4 revenues
up by 67% sequentially, and they're talking about 50% growth into the next year. When you think
about the fact that they're obviously ramping up with AWS [Amazon Web Services] more recently, does
that concern you in terms of the market share that Astera Labs can get in PCIe [peripheral component
interconnect express] cables with AWS?

Specialist:
No, I don't think Credo is a PCIe. Most of their upside is in Ethernet. They have Ethernet retimers and
Ethernet cables. That's because they have 800-gig retimers or AEC cables, active electrical cables. That's
where the growth is, not PCIe. Astera is coming on the lower end. They have a 200-gig cable, Ethernet
cables with their Taurus product line. They have 400 gig, but I don't think it hasn't started making
money. Credo has 800 gig, which is what most of the AI system is going to need. That's where the
market goes, and then Credo is there already. They see a huge upside in that area, not PCIe. All their
upside is coming from Ethernet or active electrical cables.

Analyst:
Do you think it will be bad for Astera Labs's Taurus product trajectory at the very least? Do you think
that it's more of like an all tides rising where the opportunity set has just gotten much larger?

Specialist:
Yes and no because what happened is most of the new installed systems, systems like Trainium2 or

Private and confidential

4

Astera Labs 每 Former Senior Executive, Technology at Astera Labs Inc 每 27 January 2025

whatever it is, they are going to need 800 gig/1.6T. I don't think 1.6T now, but 800 gig even more. We did
a chip for four years back, but for some reason, they had issues with the Synopsys, and then they
couldn't make the 800 gig ready. I think they will be ready in this year, hopefully. What happened is this
change, 800-gig AEC cable need went up quite high recently, and that's why not there. This market is
new. New means it's all new AI systems anyway, not like nobody predicted previously. All this goes to
Credo for now. Low end is where Astera is trying to get in. Now the question is either low end will grow
or it will be stagnated. The interesting thing is all x86 systems, they don't need 800 gig or anything, but
they still want to go to 200 gig. I think that's plenty. They don't need that much network bandwidth
because they can't process anyway. I think those racks will still go to 200Gbit to maybe, whatever, 3.2 or
12.8, whatever the thoughts and everything because they don't want to upgrade those systems or racks
because they will be cheaper node, the (inaudible), the Taurus and everything.

In those instalments, even though they are new instalments, you can call them as a legacy x86 system.
Now that area, I think Astera will get some market share. They have some, but I think they'll increase
their market share, while Credo is getting most of the new generation, 800 gig and up. Astera will get it
in the low end, but it's a good business. It will make money and the business, I think the way they do sell
the (inaudible) part is the best way of making money for Astera as well as for other customers also
because they can get much leverage from the cable guys. That's where the revenue will grow, how x86
Arm installations will go. That area, probably my guess is Astera will get a lot more share there
compared to Credo.

Marvell probably is already there, but Credo is the main guy. Again, you asked the risk, that's where the
risk is. Astera has to do a better job in delivering their Taurus platform. They have a chip. I don't know
what's the problem really is. Is it the (inaudible) or whatever it is? They have this 800-gig chip. Then
once they figure out any issues. Third is they can get it to the production quickly because all the software
stacks, everything is pretty identical. We don't need to change anything there. It's just a validation at
Astera and AWS to get 800 gig going. Will it happen in a few months? I don't know. Hopefully, by end of
this year, they will be at some competitive level with Credo, my guess.

Analyst:
Maybe to talk a little bit about the Scorpio switch product 每 you've got the P-Series PCIe switch that's
for head node interconnectivity. Am I right to think that where that gets adopted, it'll be a 1:1 attach
rate on a per GPU [graphics processing unit] basis? Is there any opportunity that it's higher or lower
just as you think about where the P-Series chips will make sense in terms of installing into the
systems that decide to go there?

Specialist:
Yes. It seems they only have four PCIe port. There is not many other areas you can look at it, put the
switch because at most, you can connect four and then the CPU, GPU and then there are only other
things you can connect, the Nic and the storage. That's the use case now. Previously, what AWS is saying
is, "Okay, I have a gen 5 Nic. I have two of them," and Nvidia goes to gen 6, CPU, gen 5. Somehow I put
two Nics and one GPU, CPU, and I need a switch because they need a full 800-gig bandwidth to the GPU.
Once they have a gen 6 Nic, you really don't need a switch in the middle because you can connect Nic
directly to the GPU if they want. If Nic has two ports, one port can connect to GPU, one port can connect
to CPU. Nvidia anyway has a PCIe port connect to the storage side by four PCIe is good enough for
storage. With that four ports, you have this limitation, what else you can connect with? You can probably
think of I can take it and then connect to three other (audio distorts) drives, blah, blah, blah. Again, all
those things will come in our configuration. I don't see any real case there, but we have to see. I don't see
any other places where they can put the switch on.

It's mostly connect all four together because that's easy way to manage the system. Nic can go all three

Private and confidential

5

Astera Labs 每 Former Senior Executive, Technology at Astera Labs Inc 每 27 January 2025

places as well as GPU and CPU. Is there a big sharing you can do? That's the biggest problem what you
see if you do this 1:1 mapping. The Nic bandwidth, you cannot share with other GPUs. Is that a big deal?
Probably not because you can do that thing at the top of the rack. Different guys have a different opinion.
If you go to Meta, Meta say, "No, I want my Nic bandwidth shared across all GPUs, so I need a bigger PCI
switch." If you look at Nvidia, they said, "Okay, I don't need it. I'll connect one Nic to one GPU and my
trays." That's good enough. It's the two camps. AWS probably followed Nvidia, and they say, "Connect
one Nic to one GPU and one CPU," which is fine. I think that's the only use case I can see now. If they
have more ports, we can look at SSD sharing or whatever it is. Right now, they don't have. That's a
limited use case I can think of, not mainly the case.

Analyst:
Does that remove the need for a retimer in those instances because the PCIe switch is actually doing
the interconnect?

Specialist:
Yes. People think that way. Yes and no, depending on where the switch is because if you put the switch
on the GPU board, which you should not because of the power and other stuff, so if you put one at the
GPU, then the CPU side and the Nic side, depending on where they put it, you may need a retimer to
reach the switch also. 1-2, they may remove it, but you are adding other side. There may be one, but right
now, GPU to CPU is one retimer, and GPU to Nic is another retimer. Let's say there are two retimers
you're using. You may remove one. Say, I'll place the switch closer to my CPU. Nic, so then I don't think
I'll place closer to the Nic. If at all, I'll place closer to the GPU and then replace one retimer. You swap one
retimer for a switch. If I'm a very intelligent system designer, maybe replace two retimers with the
switch, but switch cost is quite high compared to the retimers. At the end, I still don't understand that
architecture because if you don't remove retimers and you're adding extra latency from the switch and
management power, everything, what is that they're gaining? From the system architecture point of
view, they have a flexibility.

They prefer that way, so they isolate everything, and then they can manage the system easily or swap
the components easily. That I understand, but pure power functionality point of view, I don't know how
much benefit they have. I think the one benefit is if GPU gen 6 and CPUs are gen 5 forever, you need a
switch to get to the CPU anyway. It could be the same for Nic also. I think there is a benefit because what
happened previously, Nic has two ports, one connected to GPU, one connect to CPU. You need retimers
on both sides, mostly. Now what happened is Nic is connected to switch only. Even if you remove one
retimer there, and then my switch is the one that is connecting to both CPU and GPU. There is some
advantage, but we have to see how it goes.

Analyst:
If I use AWS as the use case, it sounds like they're doing two different form factors. One is like a 16-
accelerator rack and the other is a 64-accelerator rack. I heard that most customers are probably going
to prefer the 64 one. When I think about the content-per-cluster opportunity. Am I right to think I can
conservatively just say there are probably 64 retimers and 64 switches in that? Is there any
optimisation at a system level that I should lower my estimates in terms of thinking about what
content might exist in a per-cluster basis?

Specialist:
I think in that area, actually, there are a lot more PCIe cables. I don't think they can use that to connect
it. I believe they'll probably use PCIe cables. They have both sides retimers or one side, we have to see
based on the distance. I believe probably they'll put some with one-side retimer and some with both
sides, depending on how far are the GPUs. I saw some of those clusters, but I still don't get it. In one of
the cluster, they showed a bigger PCIe switch rather than a smaller one. I'm confused why they have to

Private and confidential

6

Astera Labs 每 Former Senior Executive, Technology at Astera Labs Inc 每 27 January 2025

do it. The only reason they can do that is to share the Nic bandwidth because do we need that much
network bandwidth for these clusters, I don't know. If they go with it, then yes, you still have to have a
switch, 1:1 switching, but you also need a lot of PCIe cables because if it's a cluster, I don't think it will be
connected directly through the back end. You still have to go through the cable.

Analyst:
Are those bigger PCIe switch chips on the front end? Is that X-Series flavour of the Scorpio where it's a
bigger switch chip on the back end maybe something to do with the fact that the interconnect fabric is
just a wider area, and so you need a bigger chip at the end of the day? Are you seeing those bigger PCIe
chips on the front end of the rack or only on the back end?

Specialist:
I don't know what the front end means, but the front end means you're connecting Nics to the CPUs and
GPUs. That's what you call front end or between the GPUs.

Analyst:
Then the back end would be more like GPU-to-GPU interconnect?

Specialist:
Yes. The GPU-to-GPU interconnect, PCIe is actually slow, but AWS right now has a PCIe, so they will use
it until PCIe jumps on or UALink comes. Mainly, they said that is what the use case is, but the bigger use
cases, even not only for AWS, Meta and other customers, Microsoft, everybody will use is the front end
where multiple Nics and multiple GPUs and CPUs are connected to the bigger PCIe switches. They are
currently in the Meta systems and other systems, and they are using, of course, gen 5 PCIes, gen 5
switches from Broadcom, 144-lane switches. The Scorpio X, which＃ Of course, most of the customers
need more than 144 lanes, which is if you use it by 16, it will be seven ports or something＃ Nine ports,
which is weird, but that's what they have. They want more than nine ports because, previously, nine
ports is okay with one CPU and four GPUs, four Nics or something like that, and then they can cross-
connect. Some ports, they will use for cross-connect to build a bigger＃ Four big switches to connect
everything kind of thing. Now storage came into the picture and everything. They need more lanes in
their switch. Whatever Astera is doing, I don't know, they are still doing 256 or they came down to 196 or
something like that, still more than 144 that Broadcom offered.

What happened is those systems are already proven with the bigger Broadcom switches at the front end.
That market is also big. We can think between accelerators, but the front-end market is also big. What
are Astera's X-Series, they will fit in both areas, but I believe they will give a good fight if they target the
front-end switches. The second thing is between the accelerator, which you're calling back-end
switching, whatever it is, there are certain things you need it because of the latency and the smaller
packet switching and other stuff, which they will do. PCIe gen 6 has a 64-byte Flits＃ 256-byte Flits, so
they can do the smaller packets, but latency is also important. Front end, previously, it is not that big
because it's mostly control traffic or initial data load kind of thing. We have to see how optimised they
will do for back end so it can be used for both front end and back end. What we know from AWS and
others is that PCIe is not going to be sufficient bandwidth for back-end interconnect. They came up with
this UALink and others, and Astera said they are also part of UALink Consortium. Those chips are a
couple of years away. Maybe in the middle, AWS is also pushing for gen 7, PCIe gen 7. There's a lot of
variations happening there. They will do the X-Series. If X-Series works, you get what you get. Then
AWS said, no choice because they're still betting on them.

They probably use whatever Astera provided because they may not go with Broadcom anyway. Right
now, they're all directly connected. If you look at their systems, they are all directly connected. Directly
connected means each accelerator connected to 4-6 of their (inaudible) kind of thing, which strike PCIe

Private and confidential

7

Astera Labs 每 Former Senior Executive, Technology at Astera Labs Inc 每 27 January 2025

cables. It is okay for certain applications, but if you compare head-to-head with Nvidia, Nvidia did that
NVLink direct connect previously, but they went to NVLink switches and telling the world that's how it
should go. Maybe there is something lacking, that AWS also think we need a switch there. The other way
to say, their system architecture, though I need to connect four of them or six of them, I don't need to
connect directly. Let's go through the switch. Instead of one PCIe link, I'll connect two PCIe links so I'll
get a little bit better bandwidth. Maybe that's how they will justify putting a bigger PCIe switch by
adding extra latency, but they get the flexibility and maybe a little bit better bandwidth utilisation.
Eventually, switch is better because that's what everybody is doing. They get some flexibility in that way.
The gen 6 is the right number, gen 7 or UALink, whatever it is. Definitely, gen 6 is lower speed compared
to Nvidia. The X-Series eventually can go there, but I think there will be some changes.

Astera will do the X-Series. Most probably, that will be the front-end switch is fighting with Broadcom
and other because there are a lot of customers there for X-Series as a front-end switch because Meta,
Microsoft, everybody, they only have one source PCIe switch source is Broadcom at the higher end.
There is a start-up that is trying to get in, Xconn, but I doubt if they can produce reliable switching. I
know most of the people there also. They think they have some Chinese data centre guys, their customer.
We'll see how it goes. My guess is if Astera delivers it, bigger switch, they will give a good competition to
Broadcom, and they will get multiple customers for that product. The front-end switch is no-brainer.
You use Broadcom or Astera, the protocols and everything is same.

Now for the back end, AWS is still confusing because they want to promote UALink, but it will take at
least a couple of years to just stabilise the protocol, product or whatever it is. Is Astera going to do
UALink switch just for AWS, and will AWS change all their accelerators to put UALink? I doubt it. When I
talk to somebody in AWS, they say it's the same SerDes, we can run it in a PCIe gen 6, but gen 6 is too
slow. Maybe I can run gen 7 or I can run 100-gig, 200-gig, 224-gig Ethernet, the SerDes can run all the
speeds. I don't know when Trainium 3 is coming, but this is like next-year accelerator. If they can put
some SerDes with all these speeds (ph) can work and some protocol logic that can handle everything,
which is fine, then it's＃ If you get a UALink switch, then they'll use UALink switch. If you get the PCIe
switch and UALink is not there, they can just go to gen 6. Then when gen 7 comes, they can upgrade to
gen 7.

I think that area, everybody is confused what AWS is really trying to get. Right now, they are
handicapped with gen 6 PCIe whenever that comes in. I don't bet on that one for Astera for now because
it's still unknown, unknown basically how the things going to evolve at AWS. As a front-end switch,
there is a market already, defined market needs the PCIe switch. (audio cuts out) themselves in their gen
6 switches, and I can guarantee they're not going to deliver a good product even if they fix their SerDes
issue and something because I know they screwed up the data path. Because they have software, they
have all the customer things, they may still maintain some market share. If somebody comes really good
architecture, low latency and everything, definitely, there is a good market for those switches. I hope
Astera will execute like that. If Astera didn't give the good latency and other things, but still, it's a
second source. You will get 20-30% of the USD 1bn market, so you will get even USD 200m-300m extra
revenue. I think that's where the X-Series will fit no matter what. There will be multiple customers there
and will give good competition to Broadcom.

Analyst:
When the Scorpio product got announced initially, the big pitch around P-Series was that it was only
64 lanes. Because of that, when you compare it on a price point vs the Broadcom 144-lane chip, it's
orders of magnitude cheaper with the argument being that hyperscalers are under-utilising their PCIe
switch ports. You brought up the point of maybe 144 gives you nine ports, but I've heard that those
aren't really being utilised fully at the end of the day. It sounds to me, at the end of the day, the
customers still want the optionality. Do you think that the P-Series, which started as a 64-lane chip,

Private and confidential

8

Astera Labs 每 Former Senior Executive, Technology at Astera Labs Inc 每 27 January 2025

needs to expand in terms of flavours to be higher lane count to be competitive in this market just based
on the cloud customer desires?

Specialist:
The X-Series is basically a bigger PC, more PCIe port. Functionality, it is same. The only thing they'd say
is, "Okay, it's GPU-to-GPU connectivity, but what is it? It's just still a PCIe port, and you'll switch it.
There's nothing different." Gen 6 protocol is same, everything is same. Again, people start under-
estimating it. I did 64 lanes, I can do 256 lanes. Once you go to bigger port count, you will have all kinds
of other issues that's going to creep in. Broadcom is not stupid to restrict to 144 lanes. They can do
bigger (inaudible). If they are doing the 51.2T features, they could do bigger PCIe features, but they
didn't see bigger need, and then they basically stuck to 144. They have smaller PCIe features. They have
72-lane PCIe features if we want in gen 5. If Astera analysts say that, "Okay, you have only one choice
from Broadcom, that's 144 lane," that's not true. 72 lane is just a package, and then you'll get it. It's not
a big deal. Even though the die is same, the cost is not going to be that much different. I believe they
have smaller port switches that Broadcom sells in gen 5.

Now in gen 6, four ports are ideal for that purpose. Again, if you ask customers, some customers say,
"Four ports are too small because now if I want to connect something else, how do I do it? If I want to
connect two GPUs to share the same CPU, I have to put two switches. Why should I do it? I'd rather
connect two GPUs, two CPUs, one Nic and one storage, maybe seven ports are better, maybe eight
ports." Everybody will ask different, different things because what are they seeing. I think what I really
heard is Astera also went through this pain after P-Series and X-Series. Is there any intermediate? What
number of ports is better? Maybe they settle that instead of 256 lanes, they probably settle somewhere
around 160 or 180, 196 or something like that, so you get a little bit more flexibility.

Now whoever said that of the bigger feature, they're not using all the ports, I don't think that is true
because in the bigger eight GPU systems, just the eight GPUs, eight Nics and the two CPUs and 1-2
storage, it's a lot of ports you need it and you don't get it. When I looked at Meta system, I think they use
three 144 PCIe switches. Somehow they connected them to all their GPUs, Nics and maybe storage also.
They use the ports to cross-connect to other PCIe switches, and I think ByteDance does the same thing.
If Astera say that, I think it's just a marketing thing, but many places, they are not stupid. The big
customers are not stupid. They try to use the PCIe ports if they are available. They're not going to let it
go. They will use smaller switches, 72 lane or whatever it is, Broadcom will offer, they will use that one.
Either gen 5 to gen 6 is not there. Astera is the first one. That's an advantage for them.

When Broadcom comes, the bigger problem for Broadcom is they started with the bigger switch instead
of doing the smaller switch. From their side, it is the right decision because most of their customers are
buying bigger switches so they can do bigger switch first to satisfy their customer demand in this. I think
at the end, there is a way you can create the system with four-port P-Series and say, "I'm not going to
share anything to anybody, just 1:1 kind of thing," great. Now it's a bigger thing. You have a lot more
flexibility in the system side, like a front-end switch you have a lot more flexibility, and the GPU can be
controlled by two CPUs, or one Nic can go to all GPUs, all kinds of flexibilities you can create it. Each
system guy, each data centre wants to architect things. One way is better than the other way. The
flexibility is there.

I believe doing an X-Series PCIe switch with a higher port count is a good competition and good
alternative for these other data centre guys. Of course, AWS eventually come, they can also say, "Okay,
let me put bigger switches to share also." That's up to them because that's what they did before the
smaller one because the previous system, they used the Broadcom switch. That's where they said,
"Okay, I need an alternative cheaper solution, whatever it is." They may come back and say, "Okay, my
older system, that architecture still holds good. I need a bigger switch. Can you do it," which is what the

Private and confidential

9

Astera Labs 每 Former Senior Executive, Technology at Astera Labs Inc 每 27 January 2025

X-Series can fit it in and which is my belief is they're doing it. Once that bigger switch comes, you can
fight head-to-head on the front-end switching with Broadcom, you get your share, whatever, 20% or
whatever it is, but across all the customers.

You can go to Meta, you can go to Microsoft, you can go to ByteDance, anybody, and say, "Okay, you are
my retimer customers, and this is my PCIe switches, exactly what you want and you're getting it."
Broadcom, maybe cheaper, maybe whatever it is, and I'm going to bend backwards to work with you
guys to make you happy. I think that's a better play for the revenue and the quicker way to go to revenue
because GPU to GPU, there are 100 other things these guys are asking, some in order some (inaudible)
kind of things. By the time all those things resolved, it may take some time.

Analyst:
I'm starting to get more people asking me about co-packaged optics. My sense is that we're at least
two years away from that being actually inserted in AI data centres. I guess just when you think about
what co-packaged optics provides, how does that remove the need for retimers in the server? Do you
have thoughts on, given the challenges around optics reliability, how far away we probably are still
from co-packaged optics? Am I right to think that we're at least two years away?

Specialist:
Yes, my guess is even longer, unless you are necessary to go long distance and you don't have any choice.
Even between the racks, if you can get it through PCIe cables or Ethernet cables, you don't need to go
optical. The alternative that people say is if the cost is low, which what I read recently is Broadcom is
going＃ Sorry, not Broadcom, (inaudible) some Chinese guys, and then they can get optics cheaper. I
don't know what are they saying. The power is more, first thing, and then I heard a lot of errors
happening. Then to get from the chip and out, even co-packaged optics, how close they can put it. If they
get the signals out of the package and then now you have to drive the optical outside, which is another
chip, (audio distorts) sometimes optical conversion chip and others. People showing all these things.
They say they're locked, and other, they're showing it for a long time, but nobody is adopting it. I don't
think that is the main thing.

Maybe networking top-of-the-rack switches or some switches, maybe they want to put it. GPU-to-GPU
connectivity within the box, co-packaged optics, but I don't know. That's too far to think of. It's not
there. It's not that they (audio distorts). I saw some of these packages that looks so big. Imagine if you
do a B200 or whatever it is and then you need 18 lanes off it, how do they connect to the optics unless
they put multiple lanes and other stuff and try to put 1-2 cables out, which looks fine. 1-2 cables out, and
you reduce all the cable cost, AECs and everything, optical and that's what it is. The problem with that is
that optical cable has to go to one connection on the other side. If I have 18 cables coming out of the
B200, it can go to four NVLink switches or another eight GPUs, whatever it is I can connect to. If I put an
optical 1-2 optical cables and use multi-mode or whatever it is, it has to go only one place on the other
side. It cannot go to eight places.

I think that limitation is there. Now between the two accelerators, if I want to do a direct connection.
Like today, I'm using eight cables to get there. Can I use one cable, one optical module? That's great
because instead of eight cables and whatever number of electrical modules, you can reduce all the cost,
collapse to one. Error rate is high. Then I read some paper that the errors are so high that unless you
need it, don't put it kind of thing. Even cost is somehow maybe is justified (ph). If errors and because of
errors, you do retransmissions, and it's the latest increase, everything. It doesn't make sense at this
point. Somebody has to do something. If you start now, maybe 2-3 years down the road, maybe there's a
new＃ That's what we are seeing for the last 5-6 years, and we have been looking at those for almost 5-6
years, but I don't see that much change, but we'll see.

Private and confidential

10

Astera Labs 每 Former Senior Executive, Technology at Astera Labs Inc 每 27 January 2025

Analyst:
As I think about competitive moats for Astera Labs, how proprietary do you feel the Cosmos firmware
is at the end of the day? Is that a key part of the moat, or does their competitive advantage come in
different forms?

Specialist:
Cosmos has some advantage, but eventually, everybody will have the same features in their own way.
Initially, it will be because you have these features that they have, but people will copy. Marvell will
provide because even if they don't provide, the customer will lost their money. They need these (ph)
features, and then they will put it. Otherwise, all the Marvell (audio distorts) get into the AWS. There will
be all the requirements. They won't see how Astera is providing it and make sure that Marvell will
provide the similar features. The advantage in that way is not that great. What it is, is basically every
product line, you will get the same features. Now you get one from Credo, one from Marvell, they have to
provide the features. Basically, the customer has to get the same features from multiple vendors vs
Astera where they provide all the features. People will provide. If the AWS asked for features, who is not
going to provide? They'll bent backward and get the things done. Until the other guys get it done, Astera
has the advantage. The only provider that may not do all these things is Broadcom because they have
multiple customers and they say, "We will pick and choose. We know what to do." For some customers,
they may do it, but some customers, they really cater (ph) them. That's the only difference.

All the features Astera has or Astera offers, diagnostics (ph). As long as the chip has some way to do all
those things, Marvell and everybody will provide those features. There is some advantage, but I'm not
going to make a decision just because they have that one because if the chip has all the features that I
want, my software will actually deliver what customer wants. I may postpone the purchase decision until
the vendors deliver those features, but it's an advantage until the (inaudible) delivery.

Analyst:
How would you be thinking about where Astera Labs's roadmap can go? They've got four key product
families at this point across retimers, cables, CXL [Compute Express Link] controllers and a switch
now. What do you think the right way to be thinking about? What else they can bring to the portfolio?
What are some easy low-hanging fruit that you think make the most sense as I think about how this
business might evolve over time?

Specialist:
For them, the easiest is the PCIe over (ph) optical, which they announced it, they are testing it for a long
distance PCIe. I still don't understand the reason you want to go that long on the PCIe because at certain
place, PCIe, the latency is too much, the protocol will break at certain levels. They understand it and
their customers understand who is asking PCIe over (ph) optical. If that worked, there is very little that
Astera is going to do it because they have a retimer, they'll plug it in front of some optical components,
which are already industry standard, and then plug it as a fibre. If that worked and at least they
demonstrated, so they had to make it production-ready and what our customers will give customers. It's
a high-margin product, I assume, and what are the volume, you'll get some money. On the CXL side, it
didn't pick it up because the whole world is now on this other (inaudible). They announced something
that the SAP kind of market is there that＃ Revenue-wise, I don't know how big is this. It's not that big.
They cannot do too much on that area until they get some revenue and then get some feedback from
customers. They're doing some call-on (ph) products, but to me, it may not be that great money
product. It may make some money, but I don't think that's a great money product.

PCIe switching, I think this is the tool, and not much going to happen on the PCIe world. They're trying
to optimise＃ PCIe trying to come up with some switch that can work in the back end, are adaptable,
much better for the back end. I don't think they will do it in gen 7, but they can adapt something into gen

Private and confidential

11

Astera Labs 每 Former Senior Executive, Technology at Astera Labs Inc 每 27 January 2025

7. The CXL also want to do something for this back-end switching because they already have a memory,
the semantics in the PCIe, CXL protocol. They want to put a couple of more things that is suitable for the
back-end accelerator-to-accelerator (inaudible). Again, you are throwing too many protocols to that
back end, and you don't need that many. UALink is interesting. If they do that right and if a bunch of
accelerators go with UALink, that's actually much better area because if Meta and Microsoft today, they
are putting Ultra Ethernet as a back end or some kind of Ultra Ethernet as a back end, so they can talk
Ethernet among the accelerators within the box.

There is these two camps. AWS, and a couple of other guys say Ultra Ethernet is good, not good, UALink
is better. Obviously, Broadcom is picking Ultra Ethernet and then AWS and Astera (inaudible) UALink. If
they do UALink switch, and if the AWS, Meta and Microsoft go with UALink, that's a huge market, let's
assume, at least between eight accelerators or some level of accelerators and give a good competition to
NVLink, if at all that picks up and then Astera deliver a switch, that is it, because once you have PCIe
switch, you know the data part is already there, you just need to do some protocol stuff and you can
quickly get it done if they do the right architecture. That's another thing. It's still within their area.

Beyond that, can they do a new product segment? Within the infrastructure, it is tough because if you
look at the PCIe system or any server system or any EIA (ph) system, you don't see any other
components. Infrastructure is a retimer or some switching. Other things are Nics and CPUs and GPUs or
SSDs. Everything is owned by big guys. These are the only things they can play. Pretty much, that is it.
Maybe some small PCIe switches for storage devices, connecting multiple storage devices, but those are
all USD 30-40 components. You may get revenue, but the profits and everything is pretty small. Long
term, you only can play this game, but unless AWS see some new market and then they ask Astera to do
it, deliver a product, then that's a different story.

Analyst:
It's harder to predict, though.

Specialist:
Yes, exactly. If I'm there, I would have done something different. Like CXL, we experimented something.
It should have been panned out, it didn't, but at least we tried a market to find a product, and we went
there. I still believe there is a chance for CXL to pick up just for the memory expansion and others. There
is something, but Astera is not going to do it. They don't have any idea. I cannot tell anyway exactly
because that's probably what I'm looking at, but Astera is not going to do it. There is something they
could have done it, but they didn't do it. Right now, I think they're still going to struggle. Not struggle,
but they still try to find a different flavour on the retimer, or maybe the Taurus line, they will do 1.6T and
then maybe they will do optical there also, Ethernet optical transceivers, whatever it is, to give a fight to
Marvell or Broadcom. I think that's where eventually they will settle down. Even the other way, they will
do their own SerDes to save some money and show some differentiation. Beyond that, I doubt.

Transcription ends

Private and confidential

12

Astera Labs 每 Former Senior Executive, Technology at Astera Labs Inc 每 27 January 2025

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

13



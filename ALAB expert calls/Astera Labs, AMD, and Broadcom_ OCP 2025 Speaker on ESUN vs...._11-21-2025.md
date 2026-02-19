Astera Labs, AMD, and Broadcom: OCP 2025 Speaker on ESUN vs. UALink
Implications

Primary:

  ALAB

  AVGO

Associated:

  NVDA

  ANET

  CRDO

  MRVL

  AMD

Viewpoint:

  Former Executive

Moderator: Kirang Gohil (KG)

| Nov 20, 2025 | 26 Min Read

Rohit Mittal (RM), Former Systems and Silicon Architect for AI/ML Infrastructure - Google

  SU MMARY

Overview

The discussion focused on the emerging debate between ESUN (Ethernet for Scale-Up Networking) and UALink, following recent
announcements at the OCP conference. The expert, a former systems and silicon architect, shared insights on the motivations
behind Broadcom's introduction of ESUN, the challenges faced by previous standards like SUE, and the potential impact on the
networking landscape. The conversation also touched on the roles of major companies like AMD, Broadcom, and hyperscalers such
as Meta and Microsoft in shaping the future of scale-up networking.

Key Insights

The expert highlighted that ESUN aims to extend Ethernet semantics into rack scale, providing a vendor-neutral option that
aligns with hyperscalers' preferences. This move is seen as a strategic effort to maintain Ethernet's relevance against competing
standards like NVLink and UALink.
The expert noted that hyperscalers such as Meta and Microsoft are interested in ESUN due to its vendor-neutral nature and
compatibility with their internal ASICs, despite UALink's performance advantages.
The discussion emphasized the importance of interoperability and the potential for ESUN to become a long-term standard if it
adopts best practices from UALink.

Competitive Landscape

Company/Product

Positive Aspects

Negative Aspects

Broadcom (ESUN)

Vendor-neutral, aligns with hyperscalers,
extends Ethernet semantics

Faces competition from established standards
like NVLink

AMD (UALink)

Built for scale-up, performance advantages

May face challenges if hyperscalers prefer
ESUN

NVIDIA (NVLink)

Technically superior, widely deployed

Potential isolation if hyperscalers adopt ESUN

Astera Labs

Positioned in PCIe to CXL transition

May face reduced TAM if UALink weakens

Applications & Use Cases

ESUN is designed to provide a vendor-neutral, Ethernet-based fabric that can be integrated with various internal ASICs, offering

1

Confidential

02/18/2026 at 18:56 PM UTC

hyperscalers flexibility and interoperability. This is particularly relevant for companies like Meta and Microsoft, which have custom
accelerators and seek a coherent fabric across their systems.

Quantitative Insights

Metric

Insight

ESUN Adoption

Expected to see early testing and interoperability by late 2026, with potential deployment by 2027

UALink Adoption

Similar timeline to ESUN, with potential operational status by 2027

Market Strategy

The discussion highlighted the strategic importance of aligning with hyperscalers' preferences for vendor-neutral solutions.
Broadcom's introduction of ESUN is seen as a move to maintain Ethernet's relevance, while AMD's UALink offers performance
advantages but may need to adapt if hyperscalers favor ESUN.

Stage & Timing

The ESUN and UALink standards are in the early stages of adoption, with significant developments expected around 2027. The
timeline for interoperability and testing is anticipated to begin in late 2026, with full deployment potentially occurring the following
year.

KG: Good afternoon, everyone. Welcome. This is Kirang Gohil with Guidepoint. Thanks for joining our call on Astera
Labs, AMD, and Broadcom, where today, we will get views from an expert on scale-up networking, in particular, we'll
talk about the recent ESUN versus UALink debate that has emerged following the OCP conference that was held last
month.

To discuss this, I'm very pleased to welcome, Rohit Mittal, to this call. Rohit is a former systems and silicon architect for
AI and ML infrastructure at Google. He was with Google from 2020 to earlier this year. Before that, he spent almost 20
years at Intel in various roles. And currently, Rohit is at Upscale AI as a founding member and head of product and
technology.

All right. Before we begin, just quickly in terms of logistics. If you have any questions for Rohit on this call, please send
them to ask@guidepoint.com and I'll include your questions anonymously into our discussion. So with that, Rohit,
welcome. Let me turn the call over to you. If you can spend a minute on your background, tell us a little bit about your
role at Google and what you are currently doing, and then we'll get right in.

RM: Cool. Yes. Thanks for the invite, Kirang. Before we start, just to make sure everybody is aligned. So these are my
personal views looking at the industry trends and what is happening in the ecosystem. It's a reflection of my present or
previous employers' official statements. Having said that, my background has been in AI, silicon and systems for more
than or close to a decade.

I started in Intel, where I was leading a lot of the Xeon servers and then transitioned into silicon photonics, where I was
a founding member of the silicon photonics business unit. After that, I was at Google, where I was leading the TPU
inter-chip interconnect protocols, and architecture, and end-to-end systems, which has been pretty successful. People
know it as ICI.

And recently, I've been at a startup called Upscale AI, which is building open-source products for scale-up from silicon
all the way to systems. So that's my background. And I have a lot of expertise in scale-ups and all the protocols and

2

Confidential

02/18/2026 at 18:56 PM UTC

everything that is going around in this space now. So when Kirang asked me to join, I was happy to share my
thoughts.

KG: Great. Thanks for that intro. So let's start with some of the announcements that came out of OCP. One big debate
or announcement was around ESUN or Ethernet for scale-up networking. Give us your thoughts on what is it? Why did
Broadcom do this? What was the motivation behind this? What was the issue with scale-up Ethernet or SUE? And your
thoughts on the traction that you think ESUN is going to get.

RM: Got it. So let's start from historically. So basically, what was wrong with SUE, as Kirang mentioned. So SUE was
basically a scale-up Ethernet, which Broadcom had shared in OCP in Dublin, which was last summer. But the
challenge with SUE was that it was too vendor-specific and it was too narrow. So there was no broad traction with it.

It basically lacked hyperscale commitment and didn't provide a real road map for rack scale compute, semantics. The
motivation what Broadcom had was they wanted to protect Ethernet relevance as a scale of fabric compared to
NVLink, compared to TPU, ICI, and also UALink. So that's why they brought this out.

But because there was a lack of commitment and all, there was some challenges of making SUE broad-based enough
for Broadcom. So what happens is ESUN basically lets Broadcom extend Ethernet semantics into rack scale, ok,
instead of letting PCIe or GPU-centric standards become the future.

And the strategic goal, in my view, is that you want to keep hyperscales aligned with Ethernet and keep the switch
silicon attach. So that's where Broadcom really wants Ethernet in some way or shape to continue to be relevant. And if
you look at the keynote, Ram, their SVP of Switching talked about at OCP in Dublin was, "Hey, Ethernet is going to
take over and it's going to even surpass NVLink," which is a broad flame at that point.

Now - so in my view, the hyperscalers do want ESUN, ok? They do not want proprietary standard or maybe even
UALink becomes a default. So ESUN gives them Ethernet-based vendor neutral and then they can integrate any of
their internal ASICs, be it MTIA or Maia without being tied to some GPU-specific semantics.

And if you look at the people who were big proponents, you saw Meta and Microsoft up there. So that's the reason
why they are there. You know, you can make a case that, "Hey, does the industry need another scale-up fabric?
There's already quite a few of them, right, out there with a proprietary like ICI or NVLink or even open standard like
UALink.

So maybe not technically because UALink after all was built from ground up to be a scale-up fabric. But I think what
the industry needed was a neutral governance and multi-vendor interoperability, and that's where ESUN basically
comes in. So ESUN is basically much more gives optionality and it's vendor-neutral, Ethernet-based, which everybody
knows in the hyperscale community, and it's really driven by hyperscalers.

KG: What is the issue with UALink? Why do the hyperscalers want ESUN? Why not just go with UALink?

RM: Yes, that's a great question. So you see the present hyperscale fabrics are much more Ethernet-based. UALink is a
new kid on the block. Building a protocol from scratch is not just based on performance and TCO. Those are big
parts. Don't get me wrong. That's very critical. But, you know, there's also reliability. There's also maturity. There's also
interoperability.

There's a lot of host of other factors which go in to make a protocol adapted by big customers like hyperscalers. So
UALink today is basically led by AMD. It's a PCI-based coherent fabric. It was built for their GPUs, like the 350, 450
kind of thing. And then it's basically been that way. And so you know, you can also make a case that going forward,

3

Confidential

02/18/2026 at 18:56 PM UTC

how committed is AMD to UALink. And I feel that UALink does give AMD differentiation. But if all the other guys,
especially the hyperscale customers, which are the customers for AMD GPUs, all rally behind ESUN.

I think AMD will not fight that tide even though they are the ones who started this whole effort. It's like, you know,
there have always been protocol wars or challenges from before, like there was a standard called C6, which I think
Xilinx and some vendors had started a long time ago in the mid-2000s because PCIe was not making progress. But C6
ultimately died because it's a new protocol and there's a whole host of factors other than performance, which go into
this.

So that's - when I look historically, that's the mental framework I have personally speaking. And I feel that's how
UALink had some challenges, and it could become just a transactional fabric and not a long-term standard like ESUN
possibly would be.

KG: As you mentioned, Meta and Microsoft are part of the ESUN announcement. Does this mean that these two
hyperscalers are now all in on ESUN and they have moved away from UALink? Or do you think there is equal chance
of success for both UALink and ESUN at Microsoft and Meta?

RM: Yes, that's a very forward-looking question. So, you know - first, let's look at the motivation behind Meta and
Microsoft to - even ESUN for that matter, right? So both of these guys have their custom accelerators like Meta has
MTIA and Microsoft has Maia. So I think both of them would want a single, coherent fabric across their accelerators,
and maybe even the CPUs, and the DPUs. They understand Ethernet quite well. In fact, the present fabrics are all
Ethernet-based, and they've just done some kind of proprietary semantics on top of that Ethernet or proprietary
transport layer on top of Ethernet.

So ESUN basically gives both of them a non-vendor-specific fabric for their internal ASICs, ok? Now UALink is also a
standard. And UALink has the benefits of being ground up for scale-up. So it will definitely have inherent advantages
over ESUN just from a performance and protocol point of view.

I think the challenge is operationally, Ethernet is going to be easier to adopt than a new protocol. So, you know, I've
given you the pros and cons of both of them. If I was to summarize, I would say that, you know, it's very early to look
into this. I mean, ESUN just barely got started. And I think if ESUN basically adopts a lot of good practices from
UALink, then ESUN would mitigate the performance disadvantage it has compared to UALink. In which case, the in
which case, the pull toward having a UALink-based fabric would become much and much less, ok?

However, if UALink maintains a performance advantage and it continues to have a strong support from everyone, then
it still has a shot to become the de facto standard. And if you know, both Microsoft and Meta are on the board of
UALink as well. So I believe they're hedging their bets. They're seeing how this evolves, whether ESUN becomes
performant enough and whether you start getting other companies providing ESUN kind of switches, and silicon, and
interoperability aspects, then yes - then they might just stick to ESUN and not even look at UALink.

KG: In terms of timing, do you think we'll see UALink switches and the broader ecosystem develop around 2027 time
frame? And compared to that, when do you think we would see ESUN ecosystem develop and ESUN switches out and
essentially ESUN in production environments?

RM: Yes. So if I look at the time line, so 2025, 2026 is MI450 Helios racks. And that ships with "UALink over Ethernet."
So that's too late to redesign, right? So 2027, 2028 is when probably MI50, and that likely adds ESUN compatibility,
assuming the hyperscalers say, "Hey, we need ESUN at that time." So I feel that either one ESUN or UALink become
operational in 2027.

4

Confidential

02/18/2026 at 18:56 PM UTC

Operational meaning like that it is in the field, in early testing with hyperscalers. And the passive alignment and early
interoperability starts sooner, like in 2026, Q4-ish kind of time frame. But I think the thing would be that, you know, if
hyperscalers pivot to ESUN, then UALink switch dam collapses. So you might basically just have ESUN switches and
silicon out there.

And then AMD also might just say, "Ok, I'll just put ESUN in the MI500 and not have UALink." They have not said that
yet. They have not come out strongly in that space. I think it depends upon how the ESUN standardization progresses.
If it progresses very fast like UALink did, then you might see ESUN being the main one. Yes. So does that answer your
question? It's all - the short answer.

KG: No. I get it. 2027, it's sort of similar time frame for both.

RM: Yes. 2027 is when it gets deployed. And I think 2026 late is when you start to see early signs of interoperability
and testing happening.

KG: One of the other companies as part of the ESUN announcement is OpenAI. We've all heard about OpenAI's
internal ASIC efforts. If you put these two together, do you think ESUN is going to be the scale-up fabric for OpenAI's
ASIC?

RM: Most likely, yes. See, they're one of the drivers. And lot of the lineage of OpenAI came from the teams that have
worked there at Google. So the ethos of OpenAI's custom silicon is they want a standard fabric for their ASIC. I don't
think they would want it tied to NVIDIA or AMD. So I don't think they want an NVLink or UALink controlling their
destiny for this.

So I mean, there - I think if I remember correctly, Broadcom, has been pretty vocal that they are doing the OpenAI
ASIC. And so - if you look at all of these factors together and Broadcom is a big proponent of ESUN and not of UALink.
So I would say that it's more than likely that given all their alignments, they would want an interoperable scale of fabric
for future clusters based on Ethernet. And ESUN is the vehicle for that. So - yes, I would agree with you that that's
probably what's going to happen.

KG: One other interesting aspect of the ESUN consortium is that NVIDIA is also part of ESUN. Why do you think
NVIDIA is a member? What is in their interest? Because they already have NVLink, which is sort of the de facto
standard that's out there or the most widely deployed. So why do you think NVIDIA is part of ESUN?

RM: Yes. That one, I don't know fully. But you see, we all agree that NVLink is superior technically because it has been
out in the field and all that, and there is nothing close to it. Maybe it was because they cannot afford to be outside a
hyperscale-led standard. Like I mentioned before, this thing was driven a lot by Microsoft and Maia and the reason -
sorry, Microsoft and Meta.

And the reason I say that is because this was announced in OCP and the people who announced it first were basically
their director of networking, Omar. I forgot who from Microsoft. So based on the public tea leaves, that's what I feel
happened. So NVIDIA possibly joined to avoid isolation. And, you know, I guess by having a seat at the table, they
could ensure that ESUN does not become hostile "to NVLink clusters," and it could influence the direction - so they
could influence the direction also by working with other partners.

And then, you know, in the future, you could have like heterogeneous clusters, GPUs plus ASICs, all meshed together.
And if the ASICs are using one protocol and GPUs are using something else, then that could create trouble for
everybody, including NVIDIA. So - it kind of future-proofs them as well. Now I don't know the technical details how this

5

Confidential

02/18/2026 at 18:56 PM UTC

could work. That ESUN is still very new and raw. So it will be an evolving story, in my opinion. But that will be my guess
that, you know, it's a hyperscaler-led standard and every chip guy, every - like GPU provider like NVIDIA needs to
have a seat at the table.

KG: NVIDIA, as you know, a few months ago announced NVLink Fusion, where it seems like they are opening up
NVLink. There are different formats or - you apply this with its chiplets or chip-to-chip? What - first of all - what are your
views on this? Does NVIDIA really want to open up NVLink? What is the interest from the customer, from the
ecosystem on NVLink Fusion?

RM: Yes. I don't - I mean, this is just my guess because I'm not - I don't have the standard or the spec from them, right?
I just read from their public announcements. So you know - so I think the main idea is that they want to standardize the
NVLink semantics into a usable fabric. And they want to kind of enable GPU accelerated rack scale coherence across
CPU or ASIC nodes.

In fact, I just saw on LinkedIn that they announced something with Arm, which said that they want everything
connected via NVLink, whether it's CPU, DPUs, GPUs, everything. So my feeling is that NVIDIA wants to pull these
hyperscaler ASICs also into their ecosystem. And - you know, NVLink is shipping volume. So making NVLink
compatible enough that hyperscalers consider NVLink as their hub interconnect even if they build their own chips is a
smart move on their part. I don't know if I answered your question, to be honest, because this one is something which
I don't really have much information on.

KG: Yes. And to be fair, NVIDIA hasn't said much on this anyways. So I get your point. All right. Let's go back to the
UALink ESUN debate. For AMD, does this have any impact on the Helios rack? Not 450 because that's UALink or
Ethernet, but the 500 series. Does this, help them or hurt them in their effort to build the scale-up rack?

RM: Yes, yes. So I feel that the MI500 2027, you know, will likely add ESUN compatibility. And that's just because, see,
AMD has to sell to hyperscalers, right, because that's the end customer. And if the hyperscalers are full force behind
ESUN versus UALink, then probably they'll say, "Ok, we want ESUN compatibility for our operations. Like, all our ops
people need to have a good way of looking at the whole system, and we are familiar with Ethernet rather than
UALink."
So if that happens, even though AMD championed UALink and UALink gives them differentiation, if all their big
customers all rally behind ESUN, I don't think AMD will have a choice but to add compatibility of ESUN in their MI500
racks. So that's my thing. Now, you know, you have to make sure that there are switches also, ESUN switches, in the
time line and/or UALink switches. So with that - for that, they'll just have to partner with companies to make sure that,
that whole ecosystem comes together. And that would be an interesting exercise.

KG: On that switches point, Astera Labs who was just developing UALink switches, is not part of the initial set of
companies that were announced for, you know, supporting ESUN. Is there a reason why you think Astera was not?
And, is there a religious reason why they would support UALink but not ESUN? Or do you think it's just a matter of
time and we'll see Astera also support ESUN?

RM: Yes. So you know - I think Astera, if you look at it, is the king of PCIe retimers and switches, certainly as like one of
the smaller companies in that space. So they are perfectly positioned - they were perfectly positioned in the PCIe to
CXL transaction. I think UALink would have expanded their TAM and ESUN probably reduces their future TAM, ok?

So if UALink outlook weakens, I think Astera Labs loses because, you know, they could easily do - they could do a
potential UALink switch attach and retimers. But if the industry moves away from PCIe entirely, like if they did ESUN,
then there's a longer-term risk for them. So they have to figure out what they want to do. And they were not in the

6

Confidential

02/18/2026 at 18:56 PM UTC

initial list of companies on the ESUN announcement. But ESUN is like going to be an open standard. So even though
they're not on the Board, but they're on the Board of UALink, any of these open standards, they can still like build
based on the specifications that come out from OCP on ESUN.

So that's the trade-off that they have to make, you know. Where they go, if they also feel ESUN is going to be the big
thing, then they also will start working on that, even though they're not on the Board of ESUN. Yes, that's my
assessment.

KG: Right. Astera was developing UALink switches. They were on stage when MI450 or - when the Helios rack was
announced. So Astera was set to benefit as AMD gained traction for Helios racks. If AMD adopts ESUN and diminishes
reliance on UALink, do you think that would ultimately be negative for Astera, i.e., lesser opportunity for Astera
because the ecosystem and the customers move to ESUN and not UALink? Or am I missing something here?

RM: I think you're largely right. It also depends upon whether they are able to build an ESUN switch as an example, or
ESUN retimers, or all of those things. I mean, ESUN is, like I mentioned, the - it's just like a new standard, right? So
there is nothing preventing any company, whether it's Astera, or Marvell, or any other company from building an
ESUN switch, right?

So it just depends upon a company saying, "Ok, I want to do this and then having the team to build on that," right? So
I mean, if UALink had been the one, then they had a driver seat. Now UALink, as we are talking through this, UALink
may not be the one, then - and if ESUN is the one, then they don't have the driver seat. They can still continue to
execute, but they don't have like an additional advantage compared to others. That's the way to put it.

KG: Given your experience in the industry, how easy or difficult you think it would be for Astera to develop an ESUN
switch given that they don't have an Ethernet heritage?

RM: Yes, it's not that easy, in my opinion, to build an Ethernet switch. You know, there are a lot of companies have
tried. But if you think of it from a historical perspective, Broadcom has basically taken the lion's share of revenues. I
think there were like so many startups, which tried in the mid-2010s.

There was like - I don' remember, there was a MediaTek startup. There was like Innovium got acquired. So that one
was successful. But there were - I remember there were a host of startups, Barefoot. They had a different take on it, but
it was still an Ethernet switch. Yes, I forget. But there were a lot of companies trying to compete, but Broadcom
basically came out ahead and almost took 100% of the market share, just like NVIDIAs or GPUs.

So building an Ethernet switch from scratch isn't that easy based on that historical data. Otherwise, people would
have built it much before this whole market took off. There seems to be only like a couple of companies, right?
There's Broadcom, there's Marvell. Cisco is trying to get into it. NVIDIA also has something in it, although they have a
custom flavor of it. So yes, it seems like a big company game of companies who have already been doing Ethernet for
decades. And so a new company would have difficulty.

KG: Now, let's take a hyperscaler or a customer perspective. Amazon with their Trainium? What do you think is the
scale-up fabric that they've adopted?

RM: Yes. So Amazon uses PCIe today, ok? I think that's what we've seen from all the analysis that company - that other
analysts have done and what we see a little bit on the public domain. So Trainium and Inferentia were built around
PCIe-based scale-up because it's easier interoperability, lower risk.

And then you can just reuse the PCIe IP from other parts of the server for scale-up as well. So - AWS, in my view,

7

Confidential

02/18/2026 at 18:56 PM UTC

historically avoids adopting new fabrics unless they control it. So - PCIe is used in Trainium clusters all over the place.
It's in accelerator trays, storage I/O, DPU connections. So - and they're heavily dependent on PCIe retimers and the
switches. That's one of the big places where Astera has really succeeded.

So - I think the thing to look at is that moving forward, what does AWS do? Because PCIe has good loads toward
semantics, but it is much lower bandwidth than UALink, ESUN, or any Ethernet-based PHY. So I don't know how they
move forward. They could - I don't remember if AWS was on the ESUN promoter list, but they could use ESUN for
scale-up or use UALink if AMD posted it in certain MI500 pods. So those would be my take on the future and what
they do right now.

KG: Right. Amazon was not on that ESUN list, at least the initial list that came out. Do you think Amazon sticks to PCIe
or would they be forced to adopt some other standard, whether it's UALink, or ESUN, or something else? What is the
life span here for PCIe on future generations of Trainium?

RM: I don't think Amazon will continue with PCIe. I think the challenge - so the challenge with PCIe is basically it's
much lower bandwidth than Ethernet, right? So you can get to like - Ethernet is already 200 and then they'll go to 400.
PCIe is nowhere there. So it puts them at a competitive disadvantage if they continue using PCIe PHY compared to
Ethernet PHY.

And so they've done it before because they wanted to take lower risk, and they were - this is the first time they were
doing it, so they wanted interoperability. But going forward, for - they've already done multiple versions of Trainium. I
would be very surprised if they remain with PCIe. It's significant disadvantage from a workload perspective. I do feel
that they would probably go to ESUN or UALink depending upon where everybody else aligns. That will be my best
estimate.

KG: In 2026, Amazon ramps Trainium 3, that's PCIe. Do you think Trainium 4 would be PCIe as well? Or do you think
the scale-up fabric for Trainium 4 is up in the air?

RM: I would say that it's up in the air, yes. They've already done three generations with PCIe. So they've already
derisked other parts of the silicon and the system. Like, you know, if you're building a brand-new compute, you want
to kind of take the risk out of the networking piece of it. They've already done many versions of their Trainiums and
they have - presumably, they must have had a good compiler stack and the software is mature enough.

So now they can take - afford to take risks on other pieces, which would become bottleneck, be it memory or
interconnect. I have not looked at the memory road maps, but I believe in the next one, the Trainium 4, they would be
able to go and get the best interconnect fabric without worrying about the risk of it.

KG: If you had to guess or make a bet, do you think Amazon adapts UALink or do they go with ESUN or something
else for the next generation of Trainiums?

RM: It depends upon where all the other hyperscalers align. If everybody is going ESUN way - so there are a couple of
scenarios, right? If everybody goes ESUN way, then they would probably pivot to ESUN. Now if the challenge
becomes - if some of them become ESUN-based and - like maybe AMD continues with UALink, then maybe it's good
for Amazon because they get a choice and they can choose one or the other, or they can choose whichever one is the
best for them, whichever one is the lowest risk.

So just thinking out loud, I think they could go either way because they are vendor neutral and they don't have the
history behind this. Like Meta and Microsoft always had Ethernet and AWS had PCIe, which they know they need to

8

Confidential

02/18/2026 at 18:56 PM UTC

update. So they can go the ESUN way and make it Ethernet-based or they could go a ground-up protocol like UALink,
you know.

KG: If you have an ASIC such as Trainium 4 that's supposed to come out in 2027, by what time frame do you think
they need to lock in the scale-up fabric? Six months before, 12 months before or do they already need to design in
the scale-up fabric at the same time as they are designing the ASIC or Trainium 4?

RM: Yes. Yes. Let me think about that. That's a very deep question. If you think about it, ideally - ok. So ideally, you
want to kind of lock in when you're designing your silicon. Now they could put programmability, so they could switch
between one or the other. But I don't know how many companies have IPs, which are - which can do both because
there are going to be differences.

And I don't know if ESUN is going to be the same. It's too early to see if ESUN will have the same link layer as UALink,
like the data link layer. The PHY could be the same, but the data link layer could be different between the two. So it's a
tricky one. I don't have a great answer.

KG: Essentially, what I'm trying to get at here is the opportunity for Astera Labs as it relates to Trainium. If Amazon
does decide to go with ESUN and Astera doesn't have ESUN, then that could be a headwind. But if the Trainiums
continue on the PCIe path, and adopt the next-gen PCIe or if they do UALink, then obviously Astera will be in the flow.
That's what I was trying to get at here. But I understand. Ok. Maybe moving on.

Do you think TPUs remain with the proprietary ICI standard? Or could that also change in your view in a couple of
years?

RM: Yes. So by the way, I have to drop in two minutes. But on the Google front, you know, so - they announced
Ironwood recently and that had ICI. And ICI has been the strongest internal fabric in the industry. I mean it was there
even before NVLink. I feel that Google will continue on the ICI path. Maybe they adopt what hyperscalers like
Microsoft and Meta do for the long term, but probably only for heterogeneous clusters where they have their TPUs
interlinked with other accelerators, be it NVIDIA GPUs or something else.

But - I mean, I don't see that scenario happening. There's no - I haven't seen any kind of workload which benefits from
having TPUs, and GPUs, and ASICs interlinked at the scale-up level. It's hard for me to kind of picture a point unless
ICI just cannot keep up with the next-generation workloads and there is a significant deviation in performance of ICI
links versus, say, ESUN or UALink.

KG: And who does the ICI switches? Is it Google internal?

RM: Yes. So ICI is basically a very different network than ESUN or Ethernet. There's no - it's like there are no switches
in ICI. It's basically a toroid. So it's very different architecture than all of these people. Nobody builds an ICI switch
chip. For instance, like, you hear about NVLink switch, you hear about UALink switch, inference switch, but nothing
about an ICI switch. So Kirang, sorry, I have to drop. Is there any last question you would like?

KG: No. Rohit, I know we had a hard 45-minute stop. So with that, let's wrap up the call. Thank you so much for taking
the time and sharing your insights. This was helpful, and I appreciate you doing it.

RM: Thank you. Bye.

KG: Thank you. Bye-bye.

9

Confidential

02/18/2026 at 18:56 PM UTC

DISCLAIMER: The statements or opinions expressed today are those of the Advisor and not Guidepoint, who disclaims all liability
for the content provided. The Advisor may not disclose material nonpublic or confidential information or any information that would
cause the Advisor to breach any duty or obligations. Guidepoint is not a registered investment advisor and the information
provided is not intended to constitute investment advice.

10

Confidential

02/18/2026 at 18:56 PM UTC



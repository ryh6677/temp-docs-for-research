Astera Labs 每 Data Centre Connectivity &
CXL Adoption Trend Outlook

FORUM

65d0d6538a8911da05d11de9b49cc840996c80c0

21 November 2024

Key Insights

> Specialist considers 60% YoY
revenue growth optimistic but
achievable for Astera Labs in FY25,
as long as the AI and non-AI server
and data centre demand continues
throughout the short term

> Astera's revenue is split c60/40 for AI
vs general compute, respectively. It
could shift towards 70/30, heavier in
AI, within the next 1-2 years

> Astera's Scorpio product family will be
able to ramp and deliver in H2 2025.
Initial revenue opportunity could be
cUSD 20m-25m, c3-4% of overall
revenues. Specialist believes the
company could win "d10% of the
switching market within the first year
and c20% by 2027

> Specialist thinks retimer consumption
will grow c50% when the  industry
transitions from PCIe Gen-5 to Gen-6
in H2 2025. Astera's market share
could drop to 70% from 95% by 2027,
but revenues will continue to grow by
double digits in the short term

Specialist

Jennifer Elliott (JE), Former Sales
Executive, CSP (Cloud Service
Providers) at Astera Labs Inc

Moderator

Lucas Keh (LK), Third Bridge Sector
Analyst

Agenda

> Trajectory for Astera Labs' (NASDAQ: ALAB)
positioning in data centres with connectivity
solutions

> Demand environment and use of retimers within

data centres

> CXL (Compute Express Link) adoption trends and

expectations for 2025

> Astera's growth outlook across various connectivity

segments

Astera Labs 每 Data Centre Connectivity & CXL Adoption Trend Outlook 每 21 November 2024

Contents

Q: Although the semiconductor sector is down today, we're seeing an explosion in Astera Labs'
stock price, which is almost up 10% as we speak. Would you like to highlight any recent news
around the company?

Q: Would you say there's a threat to Astera and Nvidia's relationship in the future if Astera
pushes the UALink [Ultra Accelerator Link] route over NVLink [NvidiaLink]?

Q: Could you walk us through Astera's growth and progress since its IPO in March 2024?

Q: Astera's revenue growth rate is around 40% sequentially QoQ. How sustainable do you think
the company's current rate is?

Q: Given Astera could lose some market share to Broadcom and others in PCIe [Peripheral
Component Interconnect Express] Gen-5, are you expecting a slowdown in the company's
current overall revenue growth of around 40%?

Q: Overall consensus estimates indicate roughly a 60% YoY revenue growth for Astera in FY25
vs FY24. Would you say this is justifiable?

Q: How much of Astera's current revenue would you attribute to the AI lift? How would you
roughly split the company's AI vs non-server AI-related revenue for the next 1-2 years?

Q: You mentioned the launch of Astera's Scorpio switch in October 2024. What do you think this
says about the company's future direction and where it might be looking to focus within data
centres?

Q: What could be some initial challenges to production or delivery of Scorpio switches on
Astera's end?

Q: What do you see as Scorpio's potential revenue opportunity over the next 12-18 months?

Q: You said Scorpio is a good opportunity for Astera, but how much market share gain do you
see for the company in the next 2-3 years? What could be some challenges in terms of
competition?

Q: How much of the DC [direct current] switching market do you see Astera being able to take in
the next two years?

Q: What are some demand and consumption trends for retimers, especially in terms of
hyperscalers?

Q: What timeline are you seeing for the transition from Gen-5 to Gen-6?

Q: What might the TAM increase look like in relation to the 50% growth in demand and
consumption of retimers that you mentioned?

Private and confidential

4

5

5

5

6

7

7

8

8

9

9

10

11

11

12

2

Astera Labs 每 Data Centre Connectivity & CXL Adoption Trend Outlook 每 21 November 2024

Q: How might Astera benefit from the TAM explosion that you mentioned? What are you
expecting in terms of retimer revenue or growth?

Q: With the Gen-6 transition, how intense do you expect a decrease in Astera's market share
from 95%?

Q: How do you see the demand environment for CXL [Compute Express Link] evolving in 2025,
especially with a higher mix of DDR5 [double data rate 5] products ramped at least from the
memory manufacturer's end?

Q: How would you evaluate Astera's positioning within CXL?

Q: Who would you consider Astera's biggest threats within CXL?

Q: How do you see Astera pricing its switch and retimer solutions in the next 12-18 months?

Q: What do you consider to be the biggest challenges for Astera in the next 12 months?

12

12

13

13

14

14

15

Private and confidential

3

Astera Labs 每 Data Centre Connectivity & CXL Adoption Trend Outlook 每 21 November 2024

Astera Labs 每 Data Centre Connectivity &
CXL Adoption Trend Outlook

Transcription begins at 00:00:01 of the recorded material

LK: Welcome to Third Bridge Forum's Interview entitled Astera Labs 每 Data Centre Connectivity & CXL
Adoption Trend Outlook. This is Lucas Keh and today, I'm joined by Ms Jennifer Elliott, who was former
Sales Executive of CSPs [Cloud Service Providers] at Astera Labs.

Before we begin with today's Interview, could you please state either I agree or I disagree to the
following statement: You understand the definition of material non-public information and agree not to
disclose any such information, or any other information which is confidential, during this Interview.

JE: I agree.

LK: Before we get started, would you mind giving us an introduction to yourself and your background in
the space?

JE: I have been in the data centre technology space for about 25 years now. I've had various roles from
engineering to FAE, field applications engineer, marketing, product marketing, product line
management and sales. I've had a broad range of experiences. With that broad range, I'm able to look at
data with a broad perspective because I can attack it from the marketing side or the sales side or the
technical side. Yes, I have lots of things to say from all the different aspects that would go into this
conversation.

[00:01:42]

Q: Although the semiconductor sector is down today, we're seeing an explosion in Astera Labs' stock
price, which is almost up 10% as we speak. Would you like to highlight any recent news around the
company?

JE: There's a few things. Obviously, they are deep in just straight-up data centre technology, but
obviously, AI technology as well. With Nvidia's announcement yesterday, which blew away all the
numbers, it's not surprising to me that Astera would track with Nvidia. Also, when Astera went public, I
believe Jensen was on their roadshow. Clearly, the companies have a strong partnership. Yes, that's
probably one of the big ones. The other one that I found or find interesting from recent announcements
is their leadership role in UALink, which is a consortium. I'm not quite sure all of the participants in it,
but the leading people are people like Google, Intel, AMD and UALink is prepared to take on Nvidia's
NVLink. As you can see, Astera has done a really good job of staying protocol-agnostic, but they're really
focused on custom connectivity within racks and within data centres. They're staying true to a focus
area and not picking favourites on specific protocols. For anybody that doesn't know, NVLink is a
proprietary protocol from＃ Designed by＃ Developed by Nvidia and it's for GPU-to-GPU
communication. UALink, this is consortium now, is going to be taking that＃ I would imagine toe-to-toe
would be that＃ Would be taking that on. Yes, they're＃ Again, Astera is clearly driving UALink, but they
have to have＃ With their close relationship with Nvidia and AI, there's NVLink, too.

Private and confidential

4

Astera Labs 每 Data Centre Connectivity & CXL Adoption Trend Outlook 每 21 November 2024

[00:04:21]

Q: Would you say there's a threat to Astera and Nvidia's relationship in the future if Astera pushes the
UALink [Ultra Accelerator Link] route over NVLink [NvidiaLink]?

JE: I don't think so because Astera is really good about staying＃ They're like the Switzerland of
interconnects. They're staying neutral. They're very open about themselves staying neutral, but they're
also very open about being an extension of customers' engineering arms. They really＃ The thing that
stood out for me＃ One of the most things or one of the things that stood out the most to me while at
Astera is they're very, very, very customer-focused. They really build the relationships at all levels.
That's the culture of the company is teamwork. I don't see any real＃ No, I don't think there's going to be
any falling out from that. Also, Nvidia is probably going to have to adapt at some point because they're at
95% market share or whatever it is, high 90s. In general, Silicon Valley and technology don't like
proprietary things because then you're beholden to a specific company. In the short run, it's okay, but in
the long run, no one wants that. That's just a general overall tenet, if you will, of technology. Multi-
source is a way to drive down pricing. Any consortium or MSA agreement is helpful in the long run.

[00:06:22]

Q: Could you walk us through Astera's growth and progress since its IPO in March 2024?

JE: According to their latest statement, which is consistent with what I would have expected, is most of
their growth is in the retimer space, PCIe Gen-5. They were first to market. They did an excellent job
executing on PCIe Gen-5 retimers. They have＃ Their chips are very cleverly designed where there's a lot
of software, a lot of firmware in their products, so they're more flexible than others. They also offer＃
Through their CMOS software, they offer additional diagnostics features and link＃ Just health features
of the data link, which is obviously helpful. PCIe Gen-5 is really ramping this year and especially with
the addition of or the massive growth of AI, those systems are just much more complicated than the
general-purpose machines or virtual machines. They're just＃ They're killing it on the retimer side.

I would say that's pretty consistent and now, they've got the added bonus of some of these other product
lines coming online. In their announcement, they mentioned Taurus. That's going into production,
which are the AEC, the active electrical cables, copper cables. Now they've announced the switch.
Actually, I should have mentioned that in the previous call. The announcement, the switch
announcement is a huge announcement. The PCIe switch is a huge announcement because right now,
basically almost 100% of that market is Broadcom PCIe Gen-5. They're taking＃ They're going＃ They
basically sent a message to Broadcom that they're going to be taking＃ They're going to be looking at a
very lucrative market and they're going toe-to-toe with Broadcom, which is no joke. Broadcom is a very
big competitor, so yes. I think those are big things. Then next year, you'll see some growth in CXL as
well. Even though this year and since the IPO, it's been primarily retimers, all these other products that
they've announced are going to be ramping in 2025 and 2026, so there's solid growth for those guys.

[00:09:32]

Q: Astera's revenue growth rate is around 40% sequentially QoQ. How sustainable do you think the
company's current rate is?

JE: That's a tough question. I do think they're at 95% market share, PCIe Gen-5, Gen-6. There's no

Private and confidential

5

Astera Labs 每 Data Centre Connectivity & CXL Adoption Trend Outlook 每 21 November 2024

room＃ There's not much room to grow on the PCIe retimers. Gen-6 is going to get interesting because
now you have new entrants. You have Broadcom and Marvell. It doesn't take a genius to figure out at
95%, the only real way that you're going to＃ The market share for yourself is going to go is probably
down. They do have some moats around them where they can prevent others from gaining market share,
but the overall sentiment in the market and especially by the hyperscalers is they all learned tough
lessons during the semiconductor shortage and so their mantra now is they want everything second-
sourced because the semiconductor shortage was a high risk for them. The big guys are all going to want
a second source, I would assume. They're going to see some market share drop just because of＃ At 95%
market share, you're just going to see some drop. As far as the other products go, the AECs, right now, I
believe those are more like corner-case use cases or very specific use cases for the hyperscalers. I think
there's a lot of competing technologies that might not require or there's competing technologies that
could work in those same use cases. They're not only up against competitors. They're up against actual
or other technologies to fill, to accommodate that use case, I guess.

Their strategy of making the chipset and working and selling that instead of the cable itself like Credo
does is very, very wise because you can maintain the semiconductor margins and the cable guys are the
ones that have to put together the MSA piece of these cables, the multi-source agreement, whether it's
QSFP or whatever, QSFP-DD. Anything that's an MSA-driven technology, it's just a race to the bottom.
Historically, semiconductor margins are in the 60-70% range, let's say, or maybe 55-65% range. The
margin for any sort of MSA transceiver is more in the 20%, maybe 20-30% range or 15-25% range. It
was very clever what they did there. Let's see. What else? That's going to be ramping into production.
The switch market is very interesting. Like I said, Broadcom has probably 90% or more of that market.
With the overall sentiment of wanting to diversify the＃ Sorry, the hyperscalers wanting to diversify or
maintain two sources for everything, they're going to have a＃ They're going to be able to do pretty well
in that market space. What else? Then their CXL product, I've heard that's going to ramp as well. I don't
know a lot of specifics on what projects are going on. Obviously, I couldn't share.

Far memory in general, which is what CXL＃ That's the term that they use. It would be the host, the CXL
controller talking to Dimms, the DDR5 Dimms. That's just needed in general because some of these
chips＃ Some of the AMD chips, I can't recall their names, but some of these chips don't have any
memory at all really attached to them, so they need it. They just need far memory. There will be adoption
of CXL coming in the new year. Like I said, their bread and butter, they might lose some market share on
their bread-and-butter PCIe Gen-5 or Gen-6 retimer, but all the other markets and all the other
technologies are going to start ramping next year and the year after. Then who knows? Those guys are so
innovative and they execute so well, I wouldn't be surprised if they're working on something else, some
other kind of interconnect for the data centre. Because like I said, they're the Switzerland of
interconnects. They just go do anything as long as there's a market. The team at the top is just＃ They're
phenomenal. They've worked together for a long time. They all have different strengths that are
complementary to each other. Yes, they've just done an excellent job.

[00:15:37]

Q: Given Astera could lose some market share to Broadcom and others in PCIe [Peripheral Component
Interconnect Express] Gen-5, are you expecting a slowdown in the company's current overall revenue
growth of around 40%?

JE: I don't think so because retimers are a＃ Retimer's ASP is much lower than some of these other
products. Obviously, it's going to be mix and volume on these other products, but I'm trying to think.
Most of them are going to be higher ASP products. I think that will easily balance or exceed. Now 40%, I
can't get that specific. I don't know. It's not out of the realm of possibilities, I would say.

Private and confidential

6

Astera Labs 每 Data Centre Connectivity & CXL Adoption Trend Outlook 每 21 November 2024

[00:16:44]

Q: Overall consensus estimates indicate roughly a 60% YoY revenue growth for Astera in FY25 vs FY24.
Would you say this is justifiable?

JE: 60%, I would say it would make me nervous. I don't＃ That's just a lot of＃ That's huge revenue
growth, but like I said, the team is so talented and just execute so flawlessly. I wouldn't say I would bet
against them, but 60%, that's just massive growth. I think a lot of that's going to have to do with how all
this stuff plays out with Nvidia and AI market. If the AI market continues to grow as rapidly as it has
been and then more broadly, the data centre market, they will track very close to that growth because
they're essential in virtually not just AI clusters, but any cluster, they're essential. Their products are
essential. More so in AI, but if general-purpose racks are being built and they still will be, they're going
to do just as well. There's probably more content in AI, but if AI slows, they're still going to have plenty
of business in other types of machines because like I said, their products are just ubiquitous.

LK: As long as there's server demand, it should continue in the short term.

JE: Exactly, exactly.

LK: 60% is achievable.

JE: Exactly. Yes, yes.

[00:18:27]

Q: How much of Astera's current revenue would you attribute to the AI lift? How would you roughly
split the company's AI vs non-server AI-related revenue for the next 1-2 years?

JE: That's tough. I probably have to think about that a little more. I do know there's been a shift in a lot
of the big guys or at least I believe there has been of pushing all their stuff towards AI servers. That's just
the fastest-growing market for all these big guys. I would＃ It also depends on how＃ These guys all＃
They all design differently, so what would be true for one of the hyperscalers isn't necessarily true for
the other ones, you know what I mean, because they design very differently. Wait, can you repeat your
question again? I want to make sure I'm answering it correctly.

LK: How would you split up Astera's AI vs non-AI-related revenues?

JE: At this point, I'm going to say most of it is probably AI related. Let me say, let's say, 60-40, 60% AI,
maybe 40% general＃ Maybe 70%, 60-70% AI, 30-40% general purpose or non-AI-related clusters. It's
tricky because some of the stuff can be used in both.

LK: Over the next 1-2 years, how are you expecting this mix to trend? Might we see closer to a 70/30 AI-
heavy split?

JE: Yes. As long as the main guys keep on pumping out AI stuff, and I don't see that stopping, but also,
there's this pit in my stomach because I went through the dotcom bust, some of these feelings feel very
familiar. I think the general AI market overall is overcrowded, but that's on the software side, not on the
hardware side. As you can see from a lot of＃ What I've been tracking a lot of start-up companies, there's
a lot more AI start-up hardware＃ AI hardware start-up companies than I think I've ever＃ I just＃ You

Private and confidential

7

Astera Labs 每 Data Centre Connectivity & CXL Adoption Trend Outlook 每 21 November 2024

don't see hardware companies starting because they usually get acquired or snapped up pretty big. I've
been surprised at the level of hardware start-ups. I think＃ I guess what I'm trying to say is with a＃ Even
with a bust and a heavy consolidation like the dot-com era, with all these different AI software
companies coming out, that's really not going to impact Astera at all because they do the hardware stuff
and the hardware stuff is growing regardless, especially at the hyperscalers. I don't see it slowing down
from any of the hyperscalers.

[00:22:08]

Q: You mentioned the launch of Astera's Scorpio switch in October 2024. What do you think this says
about the company's future direction and where it might be looking to focus within data centres?

JE: Yes, it's going to be within racks and inter-racks and intra-racks. They're just going to be able to
help＃ Their PCIe switch is going to just enable more virtual machines. It's a pretty decent market. I
don't know specifically what size the market is, but it's a good-sized market and with only one player in
it right now, the monopoly that really is existing now. Microchip is planning＃ They are in that market,
too, but right now, at Gen-5, it's mostly Broadcom as far as I'm aware. Yes, it will be interesting to see
(talking over each other 23.19). It will be interesting to see if they come back at PCIe Gen-6, Microchip,
but it's a very lucrative market. The major player right now is Broadcom. Yes, I think＃ I'm going to go to
another room, acorns hitting the ceiling. Yes, so I think they're going to do very well and it's definitely
an interesting move in the best possible way.

I guess what I'm saying is it's a sure winner because there's basically only Broadcom. All of the
hyperscalers want to dual source everything. It's not a matter if they＃ It's not a matter of whether or not
they'll get qualified. They will. They will as a second source. It's just how much of the market share are
they going to be able to take from Broadcom right away. By the way, a lot of this stuff depends on how
sticky the technology is. By sticky, I mean, how integrated is the software into the hyperscaler software.
The stickier you are, the harder it is to get you out immediately. Yes, they've got some advantages,
particularly on the＃ I know I'm jumping back to retimers but on the retimers with their Cosmos feature
set or their software and features that they offer, they've just got really sticky products. Yes, they'll do
really well on the switch market, really well. I think they're going to have to expand that portfolio to
possibly higher port counts, but maybe not.

[00:25:20]

Q: What could be some initial challenges to production or delivery of Scorpio switches on Astera's end?

JE: Honestly, the lady that runs their production and all that stuff, whatever you call it, operations, she is
just＃ She is a pit bull. Operationally, they＃ In fact, they were one of the few companies that I know of
that wasn't impacted really by the semiconductor shortage because they did such a phenomenal job
making sure all their supply chain is robust and working well. I don't see any issues at all with their
production and yes, they did a really top-notch job doing that.

LK: No real initial hurdles there. How quickly do you see Astera being able to ramp up this product?

JE: Fast. These guys are phenomenal. That's why I said they are edge＃ They are all execution. They are
all execution, so yes.

Private and confidential

8

Astera Labs 每 Data Centre Connectivity & CXL Adoption Trend Outlook 每 21 November 2024

LK: When are you expecting volume production and delivery? H2 2025?

JE: I'm not sure, but that sounds probably about right. When PCIe 6 starts launching, they're in
preproduction now. Yes, H2 next year, I would say, yes, that sounds like a good＃ Just based on
qualification cycles and also where we are with PCIe Gen-5 and the ramp there, yes, that's probably a
safe bet, H2 next year.

[00:27:14]

Q: What do you see as Scorpio's potential revenue opportunity over the next 12-18 months?

JE: This is just a straight-up guess because there's a lot of factors that have to go into it, like what
programmes are they on? What's the design cycle?

LK: If we expect volume delivery within H2 2024, what could a potential revenue opportunity be just for
Gen-5?

JE: In the millions, for sure. This is just a wild guess, probably USD 5m, USD 10m. USD 10m, that would
be my (talking over each other 28.21). No, no, I would say that's probably average maybe. I just don't
know how widely adopted it is. From what I know, the port count sounds low, but I also＃ From
traditional use cases of the PCIe switch, the port count is low, but I also know that people are＃ The
hyperscalers are looking to maybe change the topography of the servers themselves. In traditional use
cases that I'm aware of, it needs to be a higher port count. I don't know that this is going to be a broad＃
The 64-port count, Scorpio, I'm not sure that it's going to be broad adoption across all hyperscalers. I
think it's going to be more specific to one or two hyperscalers and then they're going to grow the
portfolio to capture all the ones that have the higher port counts would be what I would guess.

LK: Roughly USD 10m in revenue would be just under the projected 2025 revenue of USD 615m. That
would be just under 2% of Astera's total sales. Would you say that's reasonable, or does that seem
slightly low?

JE: Yes, it seems a little low, to be honest. It seems a little low. Maybe 3%, 4% because their PCIe＃ Their
retimer business is going to continue to ramp and then all these other things are going to ramp. It's
when Gen-6 hits that they're going to see more of a decline in their market share on the retimer. PCIe
Gen-5 is going to continue to ship for quite some time and since they have 95% market share, yes.

LK: If the switches can be anywhere from 3% to 4% of Astera's overall 2025 revenue, maybe closer to
USD 20m-25m for the Scorpio is what you're saying?

JE: Possibly. Yes, it's really hard without knowing specifics of the programme and the programme that's
going to＃ When that use case or a couple of projects they're working on is going to ramp and exit
qualification. It's just there's so many factors. I feel like that's probably pretty decent, USD 20m-25m.

[00:31:57]

Q: You said Scorpio is a good opportunity for Astera, but how much market share gain do you see for
the company in the next 2-3 years? What could be some challenges in terms of competition?

Private and confidential

9

Astera Labs 每 Data Centre Connectivity & CXL Adoption Trend Outlook 每 21 November 2024

JE: They're not going to get more than 10% market share in the first year and that's just kind of rule of
thumb in technology. Like I mentioned before, the stickiness of the Broadcom solution is going to be not
a deterrent, but it's going to be a barrier to entry. It's the software that's already integrated＃ The
Broadcom software that's already integrated into the hyperscaler systems. I can see that growing over
time pretty quickly as long as there's no qualification issues and the software is able to＃ They're able to
integrate Astera's software into the end customer software, I expect that they will gain market share
pretty quickly. The other caveat, I would say, is that Broadcom is very powerful. They're one of two
companies that make ASICs. Broadcom and Marvell are the two that make ASICs for other customers.

There is a shift and this is all public, too. There's a shift for the big hyperscalers are starting to make
more and more of their own chips, example being TPUs. That's from Google. Then also, another example
from Google is they ousted Snapdragon from their phones and are now developing internal. Meta is
making a lot of their own chips, so there's＃ For their VRs and their headsets and the glasses and all that
stuff. There is definitely a shift of the bigger guys bringing＃ Creating more and more internal content,
semiconductor content that's more specific for their use cases rather than this general-purpose stuff
like Nvidia. There is going to be more and more adoption of internal development chips.

Broadcom is one of these ASIC guys and so they have quite a bit of leverage because Hock is very well-
known for＃ Hock, their CEO, is very well-known for using that leverage to maintain his revenue. As an
example, let's say, they're buying 100 pieces or 100 different SKUs. Let's say, whatever, Meta is buying
100 different SKUs from Broadcom. If Meta turns around and says, "I'm going to give one of these SKUs
to another company," Hock will turn around and just say, "I'm going to increase your prices on
everything else," so he continues to make the same revenue. There's that leverage feature that Astera
doesn't have as much of, but they're obviously gaining that leverage because of the retimers, because
the broader their portfolio goes and the more content they have within each of these hyperscalers, the
more leverage they're going to have. Just knowing the founders, they're going to continue to just create
more and more content and because they're so customer-friendly and Broadcom is generally known for
not being customer-friendly, they're going to do well against Broadcom. Against Marvell, Marvell also
has the ASICs. They don't have the switch, but they have the ASIC ability. I almost think of it as Marvell
makes me a little more nervous just because I think they're easier to do business with than Broadcom
and they still have the leverage of the ASICs.

[00:36:38]

Q: How much of the DC [direct current] switching market do you see Astera being able to take in the
next two years?

JE: At certain customers, they might take the whole thing.

LK: If we're looking at just within the CSP [cloud service provider] landscape?

JE: Yes, yes, yes. No, that's what I'm referring to. They're not going to get more than＃ I don't think
they'll get more than 10% in the first year because that's just generally what technology does. They're
not going to switch over everything to a new person unless they absolutely have to. Within the first year,
there will be some trials. They'll do some lower-margin stuff. Then over the years, as the software is
more integrated and the teams are more comfortable together and Astera continues to listen to their
customers and make value-added products, they're going to gain market share. I'd say maybe years two
and three, they'll go up to 20%, maybe add another 10% per year of the market.

LK: Are you saying 20% by the second year?

Private and confidential

10

Astera Labs 每 Data Centre Connectivity & CXL Adoption Trend Outlook 每 21 November 2024

JE: Yes, maybe 20%. First year, they're not going to get more than 10%. It just doesn't＃ They won't.
They won't put all their＃ They won't put a lot of their eggs in one basket. They won't switch it over. In
the coming years after that, assuming Astera is successful and the switch does what it wants, and I have
no doubt that it will, then they'll probably slowly start ramping up the market share with Astera. Then
obviously, there could be total shocks like, again, a semiconductor shortage and Broadcom falls down,
which I think is unlikely, but then a lot of stuff would shift towards Astera. In general, Astera is just very
nimble. That's how they've set up the company. They're just＃ Like I said, they didn't have any issues
shipping during the semiconductor shortage. They really, really make sure that all aspects of dealing
with customers are＃ Any risk is mitigated early upfront. That's why they've been so successful along
with the fact that they're first to market. It's their execution and the way they mitigate risks that have
been so successful and their partnerships and the fact that they're agnostic. They're working with
everybody.

LK: To confirm, are you referring to 2026 or 2027 as the second year?

JE: Probably 2027, I would say. It's probably going to start midyear, so yes, probably 10% in 2026 and
20% or more in 2027.

[00:39:42]

Q: What are some demand and consumption trends for retimers, especially in terms of hyperscalers?

JE: It's just going to continue to ramp. Gen-5, there'll be some growth. Gen-6 is going to be a massive
TAM explosion for PCIe retimers, hands down, because the data rates are doubling. I believe the
encoding scheme is going from NRZ to Pam4. There's a couple of technology leaps happening. It's going
from 32Gbit to 64Gbit per channel and then the encoding scheme, I believe, is going to change, too. Yes,
they're just going to have to＃ I just＃ At Gen-5, there's still some other knobs that you can turn like
improving PCB and dah, dah, dah, dah, but at Gen-6, the data rates are just so high. They're so much
higher that there's going to be a TAM explosion. The only other thing I can think of is people start
massively changing the topography of servers, then maybe there's one more trick, but if not, I don't see
how＃ I just think there's going to be a massive explosion in the TAM at 6, at Gen-6.

LK: What type of growth are you seeing there?

JE: I know everybody asks me this question. I would say at least 50% growth.

LK: When it comes to retimer demand or consumption?

JE: Yes, yes, overall.

[00:41:48]

Q: What timeline are you seeing for the transition from Gen-5 to Gen-6?

JE: That's a good question. I'm going to go with starting to ramp H2 next year as well, because yes,
Gen-5 is being deployed now and in full swing.

Private and confidential

11

Astera Labs 每 Data Centre Connectivity & CXL Adoption Trend Outlook 每 21 November 2024

[00:42:12]

Q: What might the TAM increase look like in relation to the 50% growth in demand and consumption
of retimers that you mentioned?

JE: The overall TAM is going to, I think, increase by 50% between Gen-5 and Gen-6. It will be 50%
higher at Gen 6. It's going to be a massive explosion because of the data rate. You're just not＃ The
retimer, I can take a step back, the retimer is used to compensate for the losses in the copper traces on
the PCB, the printed circuit board, itself. The higher the data rate, the shorter＃ We call it reach, the
shorter the reach of the signal. As long as these servers remain big, you've got to get traces from one
across the board. It's just you're going to need a retimer. At 64Gbit, you're going to need a retimer
unless you start making smaller boards. I don't know that that really makes sense because you're trying
to add more and more content. It's a trade-off between trace lengths on the board, data rate. That's
basically the trade-off. It's like these trace lengths vs the loss of the signal across those traces. If you
make the traces shorter, you don't have as much loss, but then you have to massively change the
structure of the overall server. I am hearing a lot of the dual-host servers are going down to single host,
so there could be a change in the topography of servers as well.

[00:44:17]

Q: How might Astera benefit from the TAM explosion that you mentioned? What are you expecting in
terms of retimer revenue or growth?

JE: I'm expecting high growth, not in their market share. The market share is going to go down. That's
definitive because they're already at 95%, but there's going to be a much bigger TAM, so I think the
overall revenue will still grow. It will be interesting how＃ All the hyperscalers want a second source. It's
not a matter of if they'll add a second source, it's just when they'll add a second source. Again, that
whole thing I mentioned earlier about the stickiness of their technology, so they have good software and
they've been selling that. It was called something different. When I was there, it's just telemetry. It was
more general telemetry. Once you start＃ Once the hyperscalers start bringing in telemetry and stuff and
that piece of their software into their overall data centre management, it's going to be really hard to get
them out, really hard. I don't know what Broadcom is offering as far as telemetry and link health and all
those things and diagnostics.

They were very clever. Astera was very clever to make their products sticky from a software side. It's
going to be harder to get them out. Again, I'm not sure that it will all go Broadcom. I know Broadcom's＃
I think Broadcom beat Marvell. I'm not exactly sure where Marvell is, but again, Marvell makes me a
little more nervous than Broadcom just because of the way the ease＃ They're easier to do business with
and they have that ASIC leverage. I would predict Marvell is probably going to get more of that market,
assuming＃ Then I do know of some other public companies that are going to start looking into retimers,
but I can't disclose that information. The market＃ Yes, there's going to be more competitors, but in the
end, I think it's going to be Astera＃ For the hyperscalers, it's going to be Astera, Marvell or Broadcom.

[00:46:35]

Q: With the Gen-6 transition, how intense do you expect a decrease in Astera's market share from
95%?

Private and confidential

12

Astera Labs 每 Data Centre Connectivity & CXL Adoption Trend Outlook 每 21 November 2024

JE: Not a lot, not a lot the first year because＃ Then I would say it's probably going to be similar, maybe a
10% decrease or so, maybe 20% just because if it splits 50-50 with Broadcom because they've got two
good competitors. Maybe a little bit＃ It will drop a little bit more. It's in the first year and it's just＃ It's
not＃ They're not going to be that heavily impacted within the first year, I don't think, because, again,
for that whole thing, you want to＃ You really want to make sure that the new＃ The competitor's chipset
is working and all the software is integrated before you go on a big project. You start them off in smaller
projects that aren't high volume. You get used to their tips. You get used to how they work. You integrate
the software. Then once that's been proven out for a while, a year or so, then they're more likely to get
displaced. It's going to be, I would say, a year or two before they're going to get displaced. Then you
never know what they're going to do because they're going to have more leverage in a couple of years,
too, with all the switching products. It's going to be a very interesting play-out between＃ Among those
three companies.

LK: As Astera's market share grows in switches, do you expect a similar decline in retimers?

JE: Yes.

LK: In terms of revenues, though, for retimers, that's expected to continue to grow. You're saying maybe
double digits. Is that correct?

JE: Wait, is this a Gen-5 or Gen-6?

LK: From Gen-5 to Gen-6.

JE: Yes, I would still＃ I would say probably double digits, at least in the first year, for sure.

[00:48:43]

Q: How do you see the demand environment for CXL [Compute Express Link] evolving in 2025,
especially with a higher mix of DDR5 [double data rate 5] products ramped at least from the memory
manufacturer's end?

JE: See, that's the thing. You're going to need CXL more so in an AI environment than you would in just a
general-purpose environment. That will continue to ramp. I'm still not hearing a ton about CXL. It's
obvious that＃ I know for sure, they'll deploy stuff in 2025 for CXL. I think they mentioned that in their
latest call, earnings call. I'm still unsure really about the CXL market. I just＃ You couldn't＃ You just
heard about it all the time 2-3 years ago and then it's just died, not died, but it's been very＃ I shouldn't
say it died. It's been very quiet for the last couple of years. There will be adoption, but I don't think it's
going to be crazy adoption yet because I think there's still ways to make far memory work and HBM
memory work. As you need to use more and more memory to run these AI algorithms and language
models and all that stuff, then CXL is going to be more important. I think it's going to be more '26-27
for CXL than next year. It will ramp next year, but I don't think it's going to be this massive explosion.

[00:50:53]

Q: How would you evaluate Astera's positioning within CXL?

JE: Yes, top-notch. I'm not sure. Actually, I'm not sure if I can share this information. Let's just say there

Private and confidential

13

Astera Labs 每 Data Centre Connectivity & CXL Adoption Trend Outlook 每 21 November 2024

were DDR4 opportunities that I saw for CXL. I don't know if those ever panned out, but＃ They didn't do
DDR4, so it's a little hard to know if there's any incumbents already in those places or sorry, in the
hyperscalers. If not and those DDR4 projects got cancelled, and I'm pretty sure one did, the other one,
I'm not sure, then they'll do really well at CXL because, again, they're first to market and they've got the
special software. Yes, they've just done a phenomenal job of executing.

[00:52:05]

Q: Who would you consider Astera's biggest threats within CXL?

JE: Definitely not＃ What was it called? I can't remember the name, Montage. I don't think Microchip will
be＃ That's the thing. I don't even know who＃ Yes, I don't even know anyone else doing CXL. I'm trying
to think who else. There's Montage. I don't know if Broadcom is in CXL. I would imagine Broadcom and
Marvell are probably, but I don't know that for sure. I haven't really looked that deeply into the CXL
market because it never＃ It didn't happen as fast as we all thought it was going to be. The different＃
Here's another difference and this is interesting and relevant to the UALink. Astera basically co-
developed CXL with Intel. This is another brilliant thing that the management does. They're doing the
same with the UALink. You want to be one of those founding members of any of these new consortiums
because you're going to steer the spec towards your strengths. You absolutely＃ Any multi-source
agreement or consortium, you want to be one of those founding members because obviously, you're
going to steer the specification towards what you know and what you do best. They did that with CXL, so
they're going to have advantages with that because they wrote the spec themselves.

Then similarly, with UALink that's now started, they're one of the＃ I think they're the only chip vendor
on there. No, that's not true. I'm lying. They're the only chip＃ Intel and AMD are on there, but they're
the only retimer or not retimer but a non-processor chip person there. If you see the roster of people on
UALink, Astera is notably the smallest company out of all. They're all behemoths and then it's Astera.
Once again, they're creating these partnerships, they're listening to their customers and they're co-
creating the spec with their customers. They're going to have an advantage over everybody else because
they know the details well before it's going to be released to the general public. I thought it was pretty
interesting that no other interconnect, let's say, interconnect chip vendors were part of UALink. I know I
steered the question in a different direction from CXL, but in general, you always want to write the spec
because you're going to have a wildly＃ Advantage over others.

LK: In terms of pricing for Rambus's switch products and pressures from those types of players, do you
see that impacting Astera?

JE: Not really. Rambus is like an IP house. That's their bread and butter. I found that it takes a while for
someone to go from IP vs being able to make a good-quality semiconductor. For that matter, people like
or sorry, companies like Nvidia, who is a chip＃ Predominantly a chip vendor, when they started making
boards for the H100 and stuff, there's just a big learning curve between these jumps in value-added
technologies going from IP to chip and then chip to board. There's just a big learning curve. I don't think
Rambus＃ I forgot about them, so there you go.

[00:56:28]

Q: How do you see Astera pricing its switch and retimer solutions in the next 12-18 months?

Private and confidential

14

Astera Labs 每 Data Centre Connectivity & CXL Adoption Trend Outlook 每 21 November 2024

JE: Retimer at Gen-5 will come down mildly because that's just how it goes. You have to offer some sort
of reduction in price. They're not going to＃ I don't think they're going to drop it significantly. There's
no point. PCIe Gen-6, usually, they'll get about a 10% bump in pricing, 10%, maybe 15% bump in pricing
in production for the next generation. That will probably come down faster at Gen-6 just because there's
going to be more competition. It's just there's going to be more price mobility at Gen-6. On the switch,
yes, I'm＃ I don't even know what that price would be. I assume that they're going to be very competitive
with Broadcom, if not a little more aggressive to buy that market share. Once they're established in
there＃ Broadcom is a machine. Hock is not exactly one to start dropping prices to gain market share. He
uses leverages like the ASICs and stuff. I think pricing will stay pretty solid, unless there's a third＃ I
have heard of a start-up that has a very high port count switch, but I don't know where they are with
that technology. I think they have＃ There's some start-up that allegedly has a 240-port count PCIe
switch. Again, none of the big guys are going to put their＃ They might qualify it on some test cards or
something, but they're not going to just go full steam ahead with a start-up with unproven technology
that＃ It's just not going to happen.

[00:58:42]

Q: What do you consider to be the biggest challenges for Astera in the next 12 months?

JE: That's a good question. They're just on such a tear. Probably ramping staff, I think, because they keep
on opening like design centres all over the world. I think it's just hard to hire good people and they really
want the best of the best. I think that's going to be a challenge for them. Obviously, going toe-to-toe
with Broadcom or Marvell is going to be interesting, especially with how much more leverage those two
companies have. I think that's a risk. Other than that, I feel like they're hit＃ Nailing everything and I'm
0% surprised by this. They're just a wonderfully balanced team. Like I said, they've been working with
each other for 20-30 years or whatever, 20 years together. They're a well-oiled machine. Yes, they're
going to keep on continuing to＃ They're going to continue to serve customers and making sure they're
listening to the customers. They don't have the hubris or whatever, I think that's the right word, that
Broadcom and Broadcom has where they're like, "No, I'll design the product and you'll buy it." That's
not their philosophy. Yes, I think they're going to continue to win business from all the hyperscalers
because of that.

LK: Thanks so much for joining us today and breaking down Astera and its future growth, Jennifer. I
appreciate your insights, and I hope you enjoyed the Interview as well.

JE: Yes. I loved it. Thanks, guys.

LK: Thank you. Take care.

Transcription ends at 01:00:39 of the recorded material

If you＊d like to speak to Jennifer Elliott in a private call or meeting, please let your relationship manager
know.

Private and confidential

15

Astera Labs 每 Data Centre Connectivity & CXL Adoption Trend Outlook 每 21 November 2024

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

16



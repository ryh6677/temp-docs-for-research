Astera Labs: PCIe Retimer and Switch Opportunities With a Former Executive

Primary:

  ALAB

Associated:

  MRVL

  AVGO

  CRDO

Viewpoint:

  Former Executive

Moderator: Kirang Gohil (KG)

| Feb 10, 2025 | 37 Min Read

Jennifer Elliott (JE), Former Member of the Business Team for CSP Sales - Astera Labs

  SU MMARY

Overview

The discussion, led by Kirang Gohil from Guidepoint, features insights from Jennifer Elliott, a former member of the business team
at Astera Labs. The focus is on Astera Labs' opportunities in PCIe retimers and switches, particularly their strategic positioning and
market dynamics over the next few years. Jennifer Elliott brings her extensive experience in the data center industry and
semiconductors to provide a comprehensive analysis of Astera Labs' market position and future prospects.

Key Insights

First-to-Market Strategy: Astera Labs has successfully captured 100% market share in PCIe Gen 5 retimers by being first to
market and is poised to do the same with Gen 6. Their strategy of early design integration with customers makes their products
"sticky."
Dual Sourcing Trend: Due to past semiconductor shortages, cloud service providers (CSPs) are moving towards dual sourcing
critical components, which could introduce competition for Astera from companies like Marvell and Broadcom.
Diversification and Innovation: Astera Labs is diversifying beyond PCIe, engaging in protocols like UALink and CXL, indicating
their intent to expand their product portfolio while maintaining a focus on interconnect technologies.
Engineering Excellence: Astera Labs is recognized for its robust design and simulation capabilities, often going from test chip
to production without revisions, which shortens design cycles and enhances reliability.

Competitive Landscape

Company

Strengths

Weaknesses

Market Positioning

Astera Labs

First-to-market, strong customer
integration, diversification into
new protocols

Lacks ASIC capabilities,
potential external IP
dependency

Dominant in PCIe Gen 5, poised
for Gen 6, expanding into
switches

Broadcom

Established player, ASIC
capabilities

Not well-received in the
industry, difficult to work with

Current leader in PCIe switches,
facing competition from Astera

Marvell

ASIC capabilities, potential
strong competitor

Uncertain switch market entry

Emerging as a significant
competitor to Astera in retimers

Applications & Use Cases

Astera Labs' PCIe retimers and switches are crucial for maintaining signal integrity in data centers, enabling longer signal
transmission distances and supporting high-speed data transfer. Their products are used in cloud service providers' data centers,

1

Confidential

02/18/2026 at 18:56 PM UTC

with applications in GPU clusters and interconnects between CPUs, GPUs, and memory.

Quantitative Insights

Metric

Data Rate

Encoding

Expected ASP Increase

Market Strategy

PCIe Gen 5

PCIe Gen 6

32 Gbps

64 Gbps

NRZ

-

PAM4

~15%

Astera Labs' strategy focuses on being first to market, fostering deep customer relationships, and ensuring ease of business. Their
partnerships with major players like AWS and TSMC provide them with favorable terms and robust supply chains. They emphasize
customer support, often acting as an extension of the customer's engineering team.

Stage & Timing

Astera Labs is in a growth phase, expanding its product offerings and market reach. They are currently leading in PCIe Gen 5 and
are positioned to capture significant market share in Gen 6. Their switch products are in early stages, with AWS as a primary
customer, and potential expansion to other CSPs is anticipated.

Kirang Gohil:
Good afternoon, everyone. Welcome. Kirang Gohil with Guidepoint. Thanks for joining our call on Astera Labs to
discuss their PCIe retimer and switch opportunities. To discuss this, I'm very pleased to welcome our advisor for today,
Jennifer Elliott, to the call. Jennifer is the former member of business team, CSP or cloud service provider sales at
Astera Labs.

She also recently spent time at Microchip, focused on CSP sales. Earlier in her career, has worked at Fujitsu, SiTime,
Xilinx, Altera, and Finisar. All right. In terms of logistics, and as usual, if you have any questions for Jennifer on this call,
please email them to ask@guidepoint.com, and I'll include your questions anonymously into our discussion. So with
that, Jennifer, let me turn the call over to you. If you could, please introduce yourself and tell us a little bit about your
role at Astera Labs.

JE: Sure. Hi, everyone. I have been in the data center industry for the last 25 years in various roles, from R&D engineer,
field applications engineer, marketing, sales. So I have a really broad knowledge base. I'm also very technical, so I can
kind of get into the points and read between the lines on some of these press releases and whatnot that you see from
the companies.

Specifically at Astera, I ran the Google and Meta accounts. And at Microchip, I ran Google. And yes, that's pretty much
it. And my background, specifically, are in semiconductors as well as fiber optics. So yes, I got both ！ deep
knowledge in both types of interconnects within the data center and within the rack.

KG: Great. Perfect. So let's start at a high level. I'm curious to get your thoughts on the company, Astera Labs, and
your views on their PCIe retimer and switch opportunity. Somewhat of a big question, but interested to hear what your
outlook is over the next two, three years? And how do you think they're positioned?

JE: Sure. So I'm going to ！ I'll start with the retimers and then move over to the switch. But as far as the retimers go, I

2

Confidential

02/18/2026 at 18:56 PM UTC

think many of you already know they were first to market on Gen 5. They're going to be first to market on Gen 6. And
so there's a bunch of things going on. So just talking about the broad technology, PCIe Gen 5, 32 gigabits per
second, NRZ encoding, so non-return-to-zero encoding, which means you can either have a 0 or 1.

With PCIe Gen 6, you're doubling it to 64 gigabits per second, but the encoding is going to be PAM4, so you can
have a 0, 1, 2 or 3. So it's a different kind of encoding scheme, which signals a different kind of chip to keep the signal
integrity with on a board. So Astera got ！ like basically cleaned the market. They basically had 100% market share at
Gen 5.

Again, their strategy has really been to be first to market. The earlier you get into the designs at the customer, the
easier it is to maintain your market share. The most obvious reason is they can't just ！ you can't dual source these
chips right off the bat, like you just can't. It's very difficult, I would say. So the pinouts for these chips are completely
different from vendor to vendor and as well as the software.

So if you're the first one in there by six months, nine months, whatever, you're the one who they're sampling ！ they're
sampling your chips, they're able to design their PCBs, their printed circuit boards with your pinout and software.
They can start early software. So both of those things being on the board first and the software integration will make
you very, very sticky.

Now there was a time when the CSP guys were trying to get all the retimer companies to settle on one form factor and
set of like standards for diagnostics and other software features, and they all said no because they all wanted to
maintain their margin of that 60%, 70% versus optics.

Optics went the MSA route, the multisource agreement route, and it's basically plug-and-play, you yank someone out
and you just replace with the next person. So they ！ as long as they're in first and their chip works well, they will likely
have the majority market share at PCIe 6. The things that could cause them to lose market share ！ well, there's ！ let
me start with the reason.

So during the semiconductor shortage of whatever it was, 2020, 2021, the CSP providers have decided that they can't
do single source anymore for these critical components ！ well, for any components really, right, because ！ like boards
weren't being shipped because of they couldn't get a handful of resistors or capacitors. So there's a broad industry
standard of moving away from a single source to a dual source.

So essentially, when, let's say, Amazon or Google are building these boards, they're probably going to have two
flavors of boards. One with, let's say, Astera and then one with Broadcom. And they'll just choose which one they'll
make more of based on pricing and availability and customer relationship. So that's kind of how the industry works.

So I think they'll do great on PCIe 6 with that added competition. And then they will see some competition, though,
for sure from Marvell or Broadcom. On side note, Broadcom is not really well received in the industry. Most people
have been trying to design out Broadcom for a very long time.

However, because Broadcom and Marvell, for that matter, have ASIC capabilities, they have ！ they tend to have more
leverage than like an Astera would because Hock is famous for reducing prices on certain chips so they can keep the
ASIC business. And then if you don't buy their chips, then they'll jack up your ASIC price. So you're still paying the
same amount, but for less chips.

Ok. On the switch, but ！ ok. So speaking of Broadcom, Astera going head-to-head with Broadcom on the PCIe switch
sends a very clear message that Astera is not going to back down or become like a point player in this. So they're ！

3

Confidential

02/18/2026 at 18:56 PM UTC

they've released this. We might get into this a little bit later in more detail, but as far as I know, it's specifically for AWS.
The port count is rather low. Actually, I'll save that for later.

So Astera has a great opportunity right now to start taking market share away from Broadcom. And again, right now,
at PCIe Gen 6, Broadcom is the only game in town. Microchip does offer something, but they lost all their market
share at Gen 5 or most of the market share at Gen 5. So really, it's Astera's opportunity to come in as like the second ！
the main second source player at Gen 6. I think that's pretty good.

KG: There's a lot of content in there and I have many follow-ups. But just staying at a high level, do they have the
engineering DNA in your view to become a much larger diversified networking company? Or are they going to
remain "a point product" company focused on just PCIe? How do you think about their diversification efforts and
where they ultimately want to go?

JE: No, they're going to diversify. They're going to continue to diversify. You can see that already with their founding
membership at UALink. That's the protocol that's going to rival NVLink. And you guys can all Google it, but the
founding members ！ I mean, apart from Astera, there's really ！ I think everybody else is like a big player, like Intel,
AMD, Google, Microsoft because all the CSP players and the CPU ！ the x86 CPU guys, they're kind of passed out with
NVLink. They can't use it as a proprietary protocol. It's only between GPU-to-GPU as of right now. So ！ or sorry,
NVIDIA chips.

So I think Astera, given that they're actively participating in being founding members of all these different protocols,
CXL, another example, they're going to continue to expand their product portfolio. I think they will keep it mostly to
interconnect stuff. I don't ever see them trying to compete, at least not in the short run, on any kind of x86 thing or a
Tensor chip or a TPU or any of these like AI accelerators that would be more left for other companies and like FPGAs.

KG: Beyond PCIe, you highlighted UALink.

JE: UALink, CXL, PCIe, Ethernet. And I wouldn't be surprised if they were doing something proprietary for NVIDIA. I
don't know that, don't quote me on that, but it wouldn't be surprising to me if they were doing something with
NVLink.

KG: Do you believe they have enough engineering resources to get on the optical side of interconnects? Or is it
mainly going to be tied to copper?

JE: Right now, it's going to be tied to copper. They do have Richard Ward. He's been there for a couple of years now,
and he is like a big optics guy, like he was the ！ setting standards. So I have to imagine because Richard is there, they
do have some sort of pursuit for optics at some point.

And with the onset of silicon photonics or ！ I guess, silicon photonics is kind of still in its infancy, I wouldn't be
surprised that there was growth there because there are quite a few startups that are working on silicon photonics
chips. and it's right in their wheelhouse, right? It's chips designed for interconnects. It's just silicon ！ it's light versus
copper as a medium.

KG: You've worked there and have seen the company both from inside and you also competed with them. What do
you think are some of their weaknesses? Other way to ask is when they lose a socket, why do they lose it?

JE: Ok. So I would say their biggest weakness is the fact that they don't do the ASICs, right? Like Marvell and
Broadcom both help design ASICs. And maybe you guys know or not, there's definitely been a shift from moving
away from ASSPs, application-specific standard products, which is like GPUs or like NVIDIA or Intel or one of these

4

Confidential

02/18/2026 at 18:56 PM UTC

other guys, to ASICs, the application-specific ICs, because they perform better in a very specific case.

For example, the TPUs that Google has designed. I think they're in their sixth or seventh generation. Those are
codeveloped by Google internally, but also with, probably, Marvell or Broadcom, one or the other. So they have that
depth in some of the bigger higher end of products that Astera won't have.

So I think that's their biggest threat. But I also think that these ！ the CSP guys don't want to be beholden to ！ I mean,
it's well known that no one likes to deal with Hock. So of the two, between Marvell and Broadcom, I think Marvell
would probably be a bigger competitor. Sorry, what was the second part of your question?

KG: When they lose a deal ！ or a socket, why do they lose it?

JE: Why do they lose? To be honest, it would have to be a performance issue because there's no reason other than
like a performance issue or if they're not first to market. Like if they completely fall down and their timing is completely
off, which I think is low because they're usually ahead of the game, they're nimble, they can move much faster than
others. But I don't ！ unless the other guys do some kind of crazy bundling of all their chips that go into the CSPs, I
don't see how Astera loses, to be honest.

KG: What do you think about their SerDes capabilities? The perception is that companies who have the best SerDes ！
and investors generally put Broadcom, Marvell in there ！ those are the vendors that ultimately win out. With Astera
Labs, they license from Synopsys. So what do you think about their SerDes capabilities? And do you think it's
competitive enough to Broadcom and Marvell?

JE: So that's a good point. So yes, Astera does do external SerDes as far as I know. I know when I was there several
years ago, they were talking about bringing SerDes development internally. I know there were some hiccups with the
Synopsys IP at Gen 5. I'm not sure what it's like at Gen 6, but the fact that they're releasing stuff, and I haven't heard of
any like issues with any of the Astera stuff, I think they're fine at Gen 6 using external IP.

The other big thing I want to note is that Astera does a lot of simulation. They have big, big machines that do all the
FPGA simulation machines. They really ！ their mantra is like make sure that design is so tight and so good, like a lot ！ I
think in multiple chips, they don't even have to do ！ like usually, it's like you launch the chip, the test chip, then there's
like a revision or two. They usually just go from test chip straight to production. So they shorten the design cycle for
chips.

But I could see ！ so I guess, in summary, they do a really good job of designing chips with the external IP, but there is
the potential in the future that the ！ that they could eventually have a disadvantage using external IP. But I would not
be surprised if they haven't already started the SerDes ！ like building up their SerDes team because they were talking
about that when I was there a couple of years ago.

I just want to take a second to say the founders are geniuses in each ！ like in their own area of expertise, like the three
of them work so seamlessly together, that they're a hard team to beat. You don't just have like one CEO. I mean, these
guys, really, like they tag team, and they work magic. So I have to say that. They don't rule with like an iron fist like
Hock does, right? So there's definitely much more collaboration. They are taking in all the new innovations and design
more so than I think some of the bigger companies who are more slow moving.

KG: Let's talk about some of the customers, and I want to start with Amazon. It's well understood that Amazon is a
large customer for them. What are your thoughts on the Amazon relationship? Give us some background on how it
came about? Why would Amazon work with Astera Labs, which relatively is a much, much, smaller company

5

Confidential

02/18/2026 at 18:56 PM UTC

compared to the big guys like Broadcom and Marvell.

JE: So the relationship is very tight. The investors for Astera Labs were also the investors for ！ I think it was [Annapurna
Labs]. And so the guy who ！ basically the CEO of that portion of AWS is just friends with those investors, which are the
same investors that invested in Astera Labs. So there's a very tight relationship there. I believe the gentleman's name
is Nafea. I think he's out of Israel. He has a lot of sway within AWS.

So I don't see that relationship falling apart, really, ever, because the investors are going to make sure that it doesn't.
Because obviously, the better relationship of those two, the more money they make. So I don't see that relationship
going anywhere but up and tighter. I know there were some ！ like they also made some deals with AWS.

I don't know the details or whatever ！ or not deals, but like they're ！ the other thing that Astera really likes to do is
give favorable terms in their master purchasing agreements with their customers. They're very, very easy to work with.
That's another one of their mantras, is like make it so easy to work with them that the customer will just want to
continue that relationship. Whereas, again, I'm less familiar with the style of Marvell, but with Broadcom, it's much ！
it's like it's your ！ it's my way or the highway, right?

Like Hock is very much like ！ he's made it very clear that he's going to be a difficult person to work with for these
customers, which is part of the reason why a lot of them want him out or want Broadcom out. And his ！ or not his
predecessor, his prot└g└, which is Charlie, I can't remember his last name, is like a clone of Hock.

So just as demanding and just as much telling the customer, hey, we want ！ you do it our way or we'll cut off the
supply of ASICs, right? So again, that just ties in more to Marvell, I think, being a bigger competitor than ！ to Astera
than Broadcom.

KG: Should we think about Astera's relationship with Amazon mainly being tied to Annapurna Labs since you just
mentioned the！

JE: Oh, Annapurna.

KG: So is it the Annapurna Labs that's kind of the！

JE: Yes. Sorry, Habana Labs was bought by Intel. That's why there's ！ so there's like strong connections with Intel.
Astera wrote the CXL protocol with Intel and Annapurna Labs, sorry, my bad. Habana went to Intel. I mean ！ but
here's the thing, Nafea, the gentleman that runs that part, is very influential. AWS does design in silos, which is very
different than like Google, who designs like building blocks.

But it's only a matter of time before Nafea gets ！ I mean, there's so much connection between AWS and Astera. I just
don't see that issue going. And then as well, there's a deep connection with Astera and DigiKey. So I don't know if that
makes a difference or not, probably not, but that's another like ！ they're really about deep partnerships with anyone
and everyone.

KG: You mentioned that AWS has an investment in Astera Labs, and it's well understood that, AWS has a warrant-
based investment in Astera Labs. However, recently, AWS made a similar investment in Marvell. And in that press
release, they mentioned retimer opportunity as well. What do you make of that? Do you think it ultimately means that
the dual source that you talked about is going to be between Astera and Marvell? And then ultimately, how do you
think it shakes out on who gets the primary supplier position?

JE: Yes, exactly. I mean, that's kind of what ！ I suspect that Marvell is going to be a bigger competitor to AWS ！ I

6

Confidential

02/18/2026 at 18:56 PM UTC

mean, sorry, to Astera than, I think, Broadcom will be. So that totally makes sense. The ！ they're always going to do
second sourcing. It's going to then come down to availability. Like let's say it goes the way I'm thinking it's going to
go. It's going to primarily be Marvell and Astera, depending on who gets in there first, whose chip can ！ whose chip
doesn't have as many issues in qualification, that board they will launch with.

It also depends how well they're able to deliver, right? So if you have a robust delivery system, which Astera does,
then they're going to do better, especially if there's some kind of another shortage or whatever, Astera is much more
nimble. I mean, worst case, they will never just go to a single source ever again.

That's never going to happen. But I mean, there's possibility of their market share to go down with AWS. But I don't ！ I
like ！ they're never going to be none, and they're never going to ！ I don't think they'll be taken over by Broadcom.

KG: What's the word in the industry? I mean, would AWS want to allocate like 50-50 share between Astera and Marvell
over the next two, three years? Or are they just trying to mitigate single source dependency risk and that's why they
have Marvell, but Astera will still get the majority of the share? What are your thoughts on how that share split would
look? Which factors will determine that?

JE: I mean, it's definitely going to be availability. Can ！ who's got the shorter lead time, right? Because these guys
don't want to buy the chips until they absolutely have to. So if Astera has a 2-week lead time and Marvell has an 8-
week lead time, then Astera will get more of the share. The other factors are pricing, obviously, depending on the
price of each. And again, Astera has really made it so they want to be really easy to do business with.

So they make sure that they have a ton of inventory. Actually, Astera during the ！ like the semiconductor shortage,
never actually ever had a shortage because of all the partnerships that they have with TSMC and all these other ！ and
the OSATs, right? TSMC is an investor as well to Astera. So they've got very favorable lead times, stocking and
availability through their DigiKey partners, and then they've got EDOM in Asia.

And then pricing, I mean, you can always be a price leader. I don't know what that will do to Astera's margins, but
that's always a way they can win, and relationship. And that's pretty much how they can continue to increase or
maintain their market share. And obviously, ease of being able to qualify the product within ！ on the design. Astera ！ I
don't know what the other guys offer, but Astera offers like handholding through designs, like Astera will review all
schematics, they'll do deep design views.

They'll ！ in fact, sometimes the Astera people will do a lot of the designs for the end customer or at least pieces of the
design for the end customer, and Astera touts themselves as an extension of your engineering team. So they might ！
they probably go ！ at least when I was there, they were going above and beyond to support customers and especially
during the qualification phase.

KG: How much visibility would Astera Labs get from a customer such as Amazon ！ or for that matter, any of the
hyperscale customers? How open are customers to sharing their own internal road maps with Astera? Is it really a
partnership? Or are they just taking Astera as any other vendor?

JE: So they've got pretty intense partnerships, like good partnerships. I don't think they get the visibility on the actual
like full server, full rack design because they don't play in that, where obviously, like Marvell and Broadcom, because
they have ！ they're doing the ASICs for these guys a lot of times. They all see like more system-level road map versus
Astera will only see more like design level, like ！ you know what I mean, like board-level designs, not like full system
design.

7

Confidential

02/18/2026 at 18:56 PM UTC

Although with the switch, then that's probably ！ with the switch, they're going to see more and more of those designs
because they have to know where the things are switching, you know, where ！ what's being switched. So they'll get
more of a full rack view rather than more of just like a server view.

KG: How about opportunities at other hyperscalers?

JE: You mean like outside of the US?

KG: Outside of Amazon, where else are they strong in? What's the opportunity at those hyperscalers?

JE: I mean, they've got ！ they're in all the big hyperscalers like for sure. Yes, I mean, they're in all the hyperscalers. I
think, I don't know, but as of when I was there, they weren't doing any of the colo guys. That might have changed.
They're in with all the networking guys.

I would imagine ！ I don't think they have much influence. They haven't really touched Europe as far as I know. They're
really ！ their focus has been the US and the Asia markets. So the other guys will probably have a bigger impact in
Europe and like South America stuff, which are obviously ！ well, South America is probably growing very rapidly.

KG: How would you characterize their relationship with NVIDIA? How tight are they? How much visibility do they get
from NVIDIA? And for NVIDIA, is Astera Labs a special relationship? Or is it just one of many along with Broadcom,
Marvell, etc.?

JE: No, it's a special relationship. It's been grown into a special relationship.

KG: Can you expand on that?

JE: Yes, yes, yes. For a couple ！ well, first of all, Jensen went on their IPO roadshow, so that's big. Let's just say ！ ok,
so before the H100 board, NVIDIA really hadn't done any board-level designs, right? That was kind of their first
entrance into not just selling chips, but selling a system. And NVIDIA, at that time, didn't have a lot of internal know-
how on how to do that.

And with Astera touting that they are an extension of your engineering team, you can see that there are a lot of close
relationships built on that H100 board. Now as they move forward with the next generation, the Blackwell boards, I
would imagine that there's still quite a bit of cross-pollination between those two companies.

KG: Let's now dive into the switch announcement they had a few months ago. What do you make of that? What I'm
trying to understand is ！ first of all, where do you think it's used? Who's using it? Who's the lead customer? And why
would that customer have selected Astera and not Broadcom or Marvell?

JE: Well, Marvell, I don't know how far they are in their switch because when I was talking to them a couple of years
ago, they weren't even sure they wanted to go into that market. But Broadcom certainly has been at Gen 5. They
basically had it, I'm 100% sure. The port count of this ！ from my knowledge, when I was, you know, working with
Google a lot, that port count of 64 is too low for anything that Google would use.

So this is very ！ I suspect and from what I've heard, it's very application-specific to AWS. And so they ！ again, we're
likely trying to get ！ AWS is likely trying to get Broadcom out. And so they worked with Astera, especially on the
Annapurna Labs side, to get ！ work with Astera to get to a product line that would work for them in some of their
instances. So it also signals to the market that Astera is coming for other people's business.

8

Confidential

02/18/2026 at 18:56 PM UTC

I imagine with Hock, he probably paid little attention to it. Marvell, obviously, I think did if they're starting to offer this
product. You know, they're realizing that the second source was usually Microchip. With Microchip falling down at
Gen 5, it kind of opened up a whole bunch of market share for someone else to come in and take. So this is Astera's
sort of first step into this market, and, you know, they're entering it cautiously as they should because switch
technology ！ fabric switch technology is no joke.

I mean, that's very tricky to do. And they're doing it with a tried and true partner who is going to hold their hand, the
Annapurna guys is going to hold their hand and walk them through this to make it successful at 64. And then once
you've got the 64 port one in, then you can expand upward. Now I'm not saying that there aren't going to be 64 port
opportunities at the other ones, but the main opportunities I've seen has been for higher port switching.

KG: If I'm hearing this correctly, your point is that the switch was specifically designed, or sort of custom designed for
AWS?

JE: I would suspect that. I would suspect that just given what I know about some of the other architectures, yes.

KG: Can this switch opportunity expand for Astera Labs beyond AWS?

JE: I have heard ！ I did hear rumblings that some CSPs could use a lower port switch, but it's not their primary use. It
would be some, you know, application-specific use cases. So yes, they could get in there, prove that they are a worthy
competitor on some of the lower volume stuff. I'm not talking about AWS, I'm talking about the other guys, lower
volume stuff, establish themselves, get the guys familiar with their software, and then expand from there when they're
able to have higher port count.

KG: This switch from Astera, where would it go ultimately in a GPU cluster? Is it ultimately part of the NIC or the
adapter cards that the hyperscalers use? Or where exactly is the switch used?

JE: I mean, it could be used anywhere, but where I've seen it is a separate card. It would be a separate card.

KG: The switch by itself?

JE: No, there's going to be other stuff on it, but I don't remember ever seeing it with a bunch of other ！ like main
chips on it. But it's definitely possible to have a switch chip with like a whole bunch of GPUs on it, but I don't know that
that's necessarily the best use of that space. The way I've seen it in the past ！ again, architectures are rapidly
changing. I've seen, you know ！ like the H100 board is a bunch of GPUs. It's JBoG, right?

JBoG, NIC or board, I would say, I don't know if I'd call it a NIC. And then there would be like a separate card that
does all the switching. Like think about way back in the day with, you know, a switchboard for telephone calls, right?
So this is kind of the central thing where all the data is kind of coming in and out of！

KG: We have a question that was just sent to me from one of the listeners and the person is asking, how does the
switch compare to what Amazon is buying from Celestica? I guess Astera, is mainly PCIe switch, right? With Celestica,
it's different. It's not PCIe. Do you have any thoughts?

JE: I'm not familiar with the switch chip from Celestica. Celestica is now doing switch chips?

KG: No. I mean, Amazon is doing sort of white boxing, if you will. Astera is a PCIe switch, which is a chip, not that
whole big switch. There¨s a bit of confusion with the term switch, I guess.

9

Confidential

02/18/2026 at 18:56 PM UTC

JE: Wait, hold on a second. So like Celestica is selling a white box switch board, correct? Not a switch chip.

KG: Not a switch chip, right. Well, let me ask you that. Do you have any color?

JE: I don't know anything about what Celestica is offering as a white box. I'm not ！ I didn't deal with the CMs very
often. I wouldn't be surprised, Celestica is definitely doing a lot of stuff for the AI market, for sure. All the CMs are. And
Celestica is in Thailand, right? They're out of China? They're out of China.

KG: We can move on. When Astera made the switch announcement, they said they have an X-Series and a P-Series
switch. X-Series is the one that would be used for back-end GPU-to-GPU connectivity. Can you help us understand
where exactly is this opportunity with the X-Series switch and the P-Series? At which customers?

JE: I mean, I certainly understand the difference between the two, but I don't know specifically like intimate design
knowledge of stuff. Like I mean, you can just think of it as ！ I would imagine that there would be more X-Series bought
than P-Series. Because you're trying to ！ typically, like for a CPU, you have one head node or maybe, you know, a dual
head node.

You're going to have one to two CPUs, although I'm hearing the industry is moving to one CPU. And then you're
going to have just like dozens or hundreds of these GPU clusters. So it's going to be ！ the higher volume is going to
be for the GPU-to-GPU.

KG: Right. But with NVIDIA and Mellanox, they already have the retimer in-house. First of all, is that correct or not?
And when Astera talks about GPU-to-GPU connectivity, are they mainly talking about opportunities with AMD? Or are
they also including ASICs as well?

JE: Wait, hold on. Can you say the first part of it?

KG: When they talk about GPU-to-GPU connectivity, there are two GPU guys, right? NVIDIA and AMD. Do you think
Astera would have a play at NVIDIA for this switch?

JE: No, because NVIDIA uses NVLink. There might be some ！ so NVIDIA will speak NVLink among their chips. Now if
it's all on ！ if it's going from board-to-board, like GPU board to another GPU board, then yes, they might use ！ they
could use switching. But NVIDIA typically use InfiniBand, which is another sort of ！ it used to be an MSA standard, but
it's basically another custom proprietary standard. So I guess, yes, maybe Astera could use or design a special chip for
them, but I don't think either one of these would be useful for NVIDIA.

KG: How soon might we see Astera have a second customer for the switch beyond Amazon?

JE: I mean, they might already. This could be used at any of the CSP guys, if they needed it. I mean, it's like a ！ it's kind
of like a standard product. It's an ASSP. Now I don't know specifically if like Google has a 64-port design. I don't have
visibility into ！ and that would be material information that I wouldn't be able to share anyway.

KG: Is there any reason why Astera Labs can't design a higher port count switch?

JE: No, they can. They could. I just think, you know, they were probably getting design development money from
AWS or some kind of partnership deal where if Astera designed it, then AWS would commit to buying a whole bunch,
right?

KG: Let's switch gears and talk about retimers. Give some color for those that might not be as familiar on retimers.

10

Confidential

02/18/2026 at 18:56 PM UTC

There were retimers used on the H100 boxes, but that went down with the Blackwells as NVLink cables came into
play. What happened? Is there still opportunity for Astera with their retimers on the future generations of NVIDIA
GPUs?

JE: So I think there's a little bit of confusion here. So GPU-to-GPU is NVLink. The only thing that will compete with
NVLink on the broader market really is UALink. So I encouraged everybody to go and look at that. So the PCIe ！ sorry,
the retimer is specifically for PCIe. It's not for NVLink. They don't ！ they're not even in the same like data paths.
They're completely different data paths.

So PCIe was needed ！ so then ！ so at the ！ with the H100 board, it was one-to-one because you're trying to get the
signal off of that card somewhere else, probably to a switch card or to some other card. Maybe some of them go
directly to like talk to the CPU, some of them could go to a switch chip card and talk elsewhere. So the reason why
there was such a high count, I think, at ！ on the H100 boards is because that was the first time NVIDIA ever created a
board.

I'm not talking on the Mellanox side, but this is like the first time they were doing these AI boards. And it takes a lot of
time and effort and expertise to really get the signal integrity there. So maybe I should take a step back and explain
what a retimer is. What a retimer does or what it does, it allows you to send a signal further in length. So let's say you
have one card that needs to talk to another and those two cards are, I don't know, like a foot away from each other.
You can't just use like a copper cable. There's too much loss.

So what the retimer does is it takes the signal from the GPU or anything, and it takes that PCIe signal and it retimes it
and cleans up the signal. So what happens is, is you have a square wave, right? You have a 0, 1 square wave. Well,
over distance, that square wave becomes more like a sign wave, right? It's more rounded. And eventually, it becomes
so rounded and flat, you can't decipher the difference between a 0 and a 1.

So what a retimer does, it looks at everything, it retimes everything, it cleans up the signal, so it looks closer to a
square wave again. Now at PCIe Gen 5, you can ！ you need 36dB, you can only have a maximum of 36dB of loss,
decibels of loss, from point A to point B. So with a retimer, you're able to go longer distances because you're cleaning
up that signal. Does that all make sense?

KG: It does, yes.

JE: Ok. Ok. So then at Gen 6, right, when ！ as you increase speeds, it gets harder to distinguish between a 0 and 1
because everything is going faster, faster, faster, faster. It's on, off, on, off, on, off, like think of it like a flashlight,
turning it on, off, on, off. It's harder to turn things on faster, turn things on and off faster, right, than it is ！ there's going
to be more mistakes. Complicating that even further is going from NRZ, which is on, off, on, off, on, off to PAM4, which
is Gen 6.

So Gen 5, NRZ, 0, 1. Gen 6, 0, 1, 2, 3. So now you have to actually split that on-off signal into four different signals and
you're doing it fast, right? So it gets a little tricky. The reason ！ I think the main reason why there's less is because it's
liquid cooled. So when you cool boards down with liquids and ships down with liquids, they perform better, their
signal integrity performs better. So I suspect ！ I mean, temperature makes a huge difference in that pristineness of
that signal. And the Blackwell series is liquid cooled.

There are some other tricks that you can do to make the signal like cleaner along a long trace. There's different PCB
board materials that have less loss, like how you design it, where all the copper traces are, like if you have copper
traces too close together, you're going to have crosstalk between the traces, which will impact the signal integrity.

11

Confidential

02/18/2026 at 18:56 PM UTC

There are a lot of factors that impact ！ I'm just going to keep it simple, the NRZ protocol, the 0 to 1. So liquid cooling
makes a big difference for signal integrity and your ability to transmit those signals across a longer trace so you can
get the signal from point A to point B. Does that all make sense? I know that's like a！

KG: It does. Thank you. Hyperscalers, all have plans for their internal ASICs. The hyperscalers don't have NVLink. So
what are hyperscalers doing? Are they using PCIe to connect their ASIC or something else? Ultimately trying to
understand what's the retimer opportunity for Astera at these hyperscalers?

JE: The retimer will still continue to rise. As the data rates get higher, it gets ！ you require a retimer. But there's two
different things going on. So NVLink is short traces between GPUs. So imagine all the short traces, like if there's eight
GPUs like the H100, the eight GPUs on the board, right, it depends on the architecture, they're all talking to each
other very ！ they're right next to each other. And they're talking between each other on that one card, right?

They're talking through NVLink. They're not talking to each other by PCIe. So depending on the architecture. So if you
have two H100 cards in ！ I can't remember with DGX or whatever it's called the system, right, you want each
individual GPU to be able to talk to another GPU on another card. So you're going to have some！

KG: I think that is kind of understood. How are ASICs talking with each other? With NVIDIA GPUs, it's NVLink. What
about for the ASICs, like TPUs, Inferentia, Trainiums！

JE: Sorry, I misunderstood the question. So it could be PCIe ！ it's most likely PCIe, but then now CXL was also
involved. And then certainly, UALink is going to be used somehow as well, that's ！ that new standard.

KG: With CXL, there was a lot of interest in the industry a couple of years ago, but now it seems like the momentum
might have slowed. What are your thoughts on CXL? I appreciate there are different versions of CXL. But for using it as
an interconnect, do you think the industry is going to go the CXL route? Or is it mainly going to go UALink?

JE: CXL, I am hearing deployments will happen this year in some level of volume. I think CXL is going to be relegated
primarily between memory and CPU, GPU possibly storage. I've heard a lot of things with storage and CXL. UALink
will just be between GPUs or probably TPUs and GPUs. That will be the inter ！ in between the two chips, but those are
typically close together. And anything that's going from like a board-to-board will be PCIe. I'm hearing now PCIe is
doing PCIe cabling, right?

The [PCI-SIG? 57:21] now has a work group looking to standardize PCIe cabling. And then obviously, you know,
InfiniBand is another option, but I think that's going to stay within NVIDIA. And I'm hearing rumblings maybe that
Ethernet could somehow do that, but I don't think Ethernet is as robust for these kind of data signals than that PCIe is.
So I think it's going to be primarily PCIe with chip ！ like the bigger chips to chip, and then CXL will probably stay with
memory and storage. But I am hearing deployments will be happening this year, or I believe DDR5.

KG: Do you think Astera Labs will see meaningful revenues from CXL this year?

JE: Yes. Yes. I have no idea of volume or how much. I have no idea.

KG: Is it just one particular hyperscaler or customer pushing it or is it more broad based?

JE: Well, it's certainly going to be ！ I mean, if it's going to be anyone, it's going to be AWS as the lead. But, you know,
I do know some other hyperscalers do have projects. I just don't know when those guys are launching. I would suspect
it's going to be a leading with AWS.

12

Confidential

02/18/2026 at 18:56 PM UTC

KG: Would AWS use CXL? Is it used like an interconnect for ASICs or is it for memory pooling? Where exactly or how
would AWS use CXL?

JE: I mean, like ！ yes, you nailed it, data pooling. I can't remember ！ there are different forms of CXL. There's like
three different forms. But yes, it will be between like a CPU and memory or a GPU and memory because I think, now, a
lot of the chips are ！ you know, they'll have some level of HBM within the chip, but then there's going to be like no ！
like all the far memory will be with CXL. There's only so much HBM you can like put inside a chip, right? So it will go
externally with CXL.

KG: We are almost out of time, Jennifer, but I have one more question that was sent in. What do you think is going to
be the ASP lift going from Gen 5 to Gen 6 for PCIe retimers?

JE: Normally, it's only about 10% when you go from one generation to the next generation, that's usually where it
settles at. However, because of the ！ because the signal encoding scheme is changing from NRZ to PAM4, I suspect
that they might be able to squeeze a little bit more increase in pricing for that, so maybe 15%.

But I doubt ！ certainly on early samples and like when it's starting to ramp, it could be higher, but it will quickly ！ this
is just generally in semiconductors after like a certain volume, you know, it's expected to not be much more than 10%.
Even if you're doubling the data rate, they ！ customers typically don't pay much more than 10%.

KG: Got it. So for PCIe Gen 6, maybe 15% or around there?

JE: Maybe 15%, yes.

KG: All right. Great, Jennifer. With that, we are out of time, so we'll wrap it up. Thank you so much for taking the time
and sharing your insights with us. It was really helpful. I appreciate you doing it.

JE: Thanks, guys. Have a great day.

KG: Thank you. Bye-bye.

JE: Thanks. Bye.

DISCLAIMER: The statements or opinions expressed today are those of the Advisor and not Guidepoint, who disclaims all liability
for the content provided. The Advisor may not disclose material nonpublic or confidential information or any information that would
cause the Advisor to breach any duty or obligations. Guidepoint is not a registered investment advisor and the information
provided is not intended to constitute investment advice.

13

Confidential

02/18/2026 at 18:56 PM UTC



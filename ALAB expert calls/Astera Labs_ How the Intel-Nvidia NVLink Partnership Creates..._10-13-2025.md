Astera Labs: How the Intel-Nvidia NVLink Partnership Creates Risks and
Opportunities in Rack-Scale Connectivity

Primary:

  ALAB

  Credo Technology Group Holding Ltd

Associated:

  MRVL

  AVGO

  NVDA

Viewpoint:

Industry Consultant

Moderator: Sheetal Duggal (SD)

| Oct 13, 2025 | 43 Min Read

Chuck Byers (CB), Chief Technology Officer - Industry IoT Consortium

  SU MMARY

Overview

The discussion, led by Chuck Byers, focuses on the recent partnership between Intel and NVIDIA, particularly in the context of rack-
scale connectivity and its implications for companies like Astera Labs. Byers, with extensive experience in data center infrastructure
and interconnect technologies, provides insights into how this partnership could reshape the semiconductor and data center
markets. The conversation also explores the competitive landscape, potential technological shifts, and strategic moves necessary
for companies like Astera Labs to remain relevant.

Key Insights

Intel-NVIDIA Partnership: Byers highlights the strategic nature of NVIDIA's $5 billion investment in Intel, emphasizing the mutual
benefits. Intel gains much-needed capital for advancing its semiconductor technologies, while NVIDIA diversifies its supply
chain, reducing reliance on TSMC's Taiwan-based fabs.
Market Disruption: Byers predicts significant disruption in the semiconductor industry, particularly affecting competitors like
AMD and smaller TPU companies. The partnership could lead to a competitive edge for Intel and NVIDIA in the interconnect
technology space.
Astera Labs' Challenges: The partnership poses risks for Astera Labs, especially if Intel and NVIDIA's combined technologies
diminish the relevance of Astera's PCI Express-based products.

Competitive Landscape

Company

Positioning & Strategy

Key Advantages

Key Challenges

Intel

NVIDIA

Partnering with NVIDIA to
leverage NVLink

Semiconductor innovation,
diverse fabs

Requires capital for tech
advancements

Expanding fab options,
reducing TSMC reliance

Strong market presence, NVLink
ecosystem

Proprietary tech limits broader
adoption

Astera Labs

Focused on PCI Express
products

Established in retimers and
switches

Needs to pivot to NVLink/optical
tech

AMD

Competing in GPU and TPU
markets

Established in CPUs and GPUs

Lagging behind NVIDIA's market
dominance

1

Confidential

02/18/2026 at 18:56 PM UTC

Applications & Use Cases

NVLink vs. PCIe: The discussion centers around the potential shift from PCI Express to NVLink for interconnect technologies.
NVLink offers lower latency and higher performance, crucial for large-scale GPU clusters.
Co-Packaged Optics: Byers discusses the future role of co-packaged optics in improving data center efficiency, suggesting a
shift away from traditional electrical connections.

Quantitative Insights

Metric

NVIDIA Investment in Intel

Value/Insight

$5 billion

Potential Intel-NVIDIA Chip Launch

March 2027 (projected)

Power Requirement for Future Racks

600,000 watts (Kyber system)

Market Strategy

Product-Market Fit: Byers suggests that Astera Labs must pivot from PCI Express to NVLink or UALink to maintain market
relevance. This involves developing new products that align with emerging standards and technologies.
Strategic Partnerships: The Intel-NVIDIA partnership exemplifies strategic collaboration to leverage complementary strengths
and address market challenges.

Stage & Timing

Intel-NVIDIA Partnership: Currently in early stages, with significant market impact expected by 2027.
Astera Labs' Pivot: Urgent need to adapt by 2025 to remain competitive, with a focus on developing NVLink-compatible
products and exploring co-packaged optics.

The discussion underscores the transformative potential of the Intel-NVIDIA partnership and the strategic pivots required for
companies like Astera Labs to thrive in a rapidly evolving technological landscape.

SD: Good morning, Sheetal Duggal with Guidepoint Insights. Thanks for dialing into our call today. We're going to be
talking about Astera Labs and the Intel-NVLink partnership as well as the opportunities and risks it creates and how
the Intel-NVIDIA NVLink partnership will create risks and opportunities in rack-scale connectivity. We're linking up with
Chuck Byers here to talk through his thoughts on the topic.

If you have any questions, as always, you can email me at ask@guidepoint.com. I'll work through all emails, any
questions I receive on an anonymous basis as they come in. The email just again is A-S-K@guidepoint.com. With that,
Chuck, great to have you here. Would love to have you walk through your background to the audience and then we
can dive into your thoughts on some of these topics.

CB: Sure. And thanks for inviting me. It's always a pleasure to work with Sheetal and Guidepoint and the whole team
to talk about interesting opportunities in the technology space. So my name is Chuck Byers. I have a master's degree
in electrical engineering. I worked for 22 years at Bell Laboratories on various switching, access, and wireless
networking projects.

I worked for 10 years at Cisco, where I was doing media processing, analytics, edge computing, Internet of Things and
lots and lots of work on data center infrastructure. I currently serve as the chief technical officer of the Industry IoT

2

Confidential

02/18/2026 at 18:56 PM UTC

Consortium. We're a consortium of around 100 member companies interested in digital transformation, the
trustworthy Internet of Things and sort of what we do with the data coming in from a few hundred billion sensors
across the globe.

The answer is we pull them into data centers, and we analyze and distill that information very carefully. And as a result
of that work, I've gotten very involved in data center infrastructure, especially the interconnect between various kinds
of networks and the equipment in the data center and also how to cluster the equipment inside of the data center.

That led me to lots of interesting studies and work with Astera and their competitors like Credo and MACOM as well
as work with the primary suppliers of chips in those servers, namely NVIDIA, AMD, and a few other companies. So this
recent announcement is interesting, and I look forward to talking something about that. The only other interesting
part of my credentials is I have 136 issued US patents, significant numbers of them relate to these interconnect topics.
Thanks.

SD: Thanks, Chuck. Let's start with your high-level thoughts on this announcement, what you think the implications are
and what it means. Obviously, there's a lot of implications here, but I want to at least start with how you think about
just kind of, you know, NVIDIA and Intel becoming, you know, more partners versus competitors in certain ways, they
will still be competitors in other ways. But really kind of, you know, how you think this broadly impacts the dynamic or
can impact the dynamic, you know, especially when it comes to some of the connectivity solutions that we've been
seeing and the overall market for that?

CB: Yes, there's a lot to unfold in this announcement. So my understanding is the announcement involves a potential
$5 billion investment by NVIDIA into Intel. And, you know, that seems a little strange given that Intel sort of makes
GPUs and processors and potentially is a direct competitor in some ways to what NVIDIA does. But if you dig a little
bit deeper into some of the ramifications and potential motivations, I think it starts to make sense. One thing, of
course, that NVIDIA brings to the bidirectional value of this proposal is $5 billion.

And it turns out Intel really needs that in order to capitalize their next-generation process technologies, build out their
fabs, continue to pay a competitive wage to the - avoiding laying off even more of their talent and so on. So I think that
Intel probably needs it a little bit more than NVIDIA does. But I think NVIDIA gets some interesting stuff out of it, too.

Intel has always been, and I think continues to be an innovator in semiconductor process technology. And at the end,
we can talk a little bit about exactly what that means and what Intel has done recently in that space. Some of their
recent work in semiconductor process innovation is quite impressive. And I think that NVIDIA might realize that
they've got a lot of eggs in one basket with their pretty much sole reliance on TSMC as a semiconductor fab and a few
other companies as their sort of chip assembly and packaging partners.

I think that Intel brings some really interesting options to NVIDIA in terms of fab locations. One of the biggest single
risks that I think NVIDIA faces is that TSMC's sort of 3-nanometer and better fabs are all in Taiwan. At least now, they're
talking about building out further. But right now, they're in Taiwan, where Intel has fabs that are sort of capable of that
level of process, they're not quite ready to go on the lowest level nodes yet, but they're in places like Arizona and
Oregon.

So in my opinion, having a supply chain that's far away from the East China Sea might be very useful for NVIDIA. And I
think that also helps NVIDIA with their, you know, concerns about some of the stuff with the US government, I think,
could be a little smoothed over if the deal goes as anticipated. So I think that there's something in it for both
companies.

3

Confidential

02/18/2026 at 18:56 PM UTC

And I do think it is going to be disruptive to the larger semiconductor industry, of which Astera and their competitors
are a part. So let's talk a little bit more about some other things that I think are going on. I think this could also
potentially be a significant blow to AMD and any of the other little companies like Cerebras and the various kinds of
TPU companies - companies like - there's a whole bunch of TPU companies, Groq and Tenstorrent and Furiosa.

So those kind of companies, I think, are, you know, sort of expecting that this combination of Intel and NVIDIA is going
to be significantly uphill battle for them, and I think they're probably right. I think that we could probably also see
some interesting changes in the way that interconnect technology, the technology necessary to scale, for example, a
cluster of GPUs connecting them all together will be implemented.

So we've seen significant input and significant content from companies like Astera in the large-scale DGX and NVL72
clusters that you'll find using the NVIDIA GPUs. Intel has their own philosophies about the way that those
interprocessor networks ought to be built. And some of those philosophies would be potentially very beneficial to
NVIDIA, should NVIDIA decide to grab them and run with them.

And some of them could potentially be significantly detrimental to companies like Astera because, for example, with
co-packaged optics, much of the Astera benefits associated with electrical and PCI Express interconnection are going
to be diminished or potentially completely eliminated. So we can talk later about the details of how and why that
might happen. But there are significant risks to Astera if this deal runs to its full fruition and the great benefits that Intel
brings and the great benefits that NVIDIA brings are multiplied by each other, then I think Astera is going to have
some uphill battles.

SD: So let's unpack that. I mean there's a lot to talk about here, Chuck. So I really appreciate the intro. It was fantastic.
But maybe we can kind of start with kind of PCIe versus NVLink and kind of the deeper kind of NVLink integration into
Intel CPUs and what it means kind of for PCIe and scale-up architectures, especially kind of how to think about what it
means for kind of obviously PCIe retimers. So maybe we can kind of start with that as just kind of a thought process in
terms of exploring and then kind of dive into other questions and topics here.

CB: Yes, Intel has always been a strong proponent of PCIe and PCI Express and some of the derivatives of that like
streaming fabric interface and Thunderbolt, they use some of the basic protocol functions of PCI Express. And as a
result, Intel has got quite a bit of experience in those spaces.

What this potentially means, what the announcement potentially means is that in addition to Intel's interest in those
PCI derivative standards, Intel might also start to be interested in the proprietary NVLink stuff, which is, of course,
strongly implemented in all of the NVIDIA products, both their large-scale GPUs as well as their InfiniBand switching
technology that is derived from the Mellanox acquisition.

I would suspect that all of these technologies, these interconnect and link technologies could coexist for a while. But
eventually, it's going to be a bit like a beta versus VHS sort of standoff. And eventually, the market is going to choose
a winner. There's probably around three different opportunities for choosing that winner. The first one and the one
that I think my money is on is the NVLink InfiniBand ecosystem that is [promoted? 9:58] by NVIDIA and certainly
important in all of their products.

It's got some really interesting technical performance advantages. It's energy use is pretty good. It has very low
latency. These are all things that are very important to building large-scale GPU clusters with potentially millions of
member chips. But there's a big downside to NVLink and InfiniBand is that they're viewed as very proprietary to
NVIDIA.

4

Confidential

02/18/2026 at 18:56 PM UTC

You can't, for example, run for the chairmanship of a committee to define what the next generation of NVLink is. The
way you would do that definition is be hired by NVIDIA and then be run into their Mellanox division and part of the
architecture team that's inventing the next generation of that stuff. So it's not a democracy. There's no way that a
company like AMD can play in that.

So that's a significant downside having that standard being proprietary. It's not really a standard. It's a proprietary
infrastructure. And it's very possible that NVIDIA owns a significant amount of the intellectual property, the patents
necessary to implement that stuff, which gives NVIDIA control over the marketplace, who they license it to, what kind
of royalties they could demand on companies that spend tens of millions of dollars developing chips.

In addition, you might have to pay tens of millions of dollars to NVIDIA for royalties if it turns out that there's an
NVIDIA intellectual property buried inside of that chip. So for those reasons, NVLink, you know, I think it's got
commercial momentum. I think it's going to be going places. I think it's going to be necessary for the future, at least
for the next half of a decade or so.

I think it's reasonable that Intel got in bed with it, but it's not the only solution that we could consider. The second one
would be the whole PCI Express ecosystem. And that's sort of a derivative of the buses that you find in desktop
computers in the 1980s and 1990s. And as a result, it's, you know, sort of very - its scalability is kind of limited.

You can't put millions of endpoints on a PCI Express network and expect it to perform properly. There are very
significant limitations to how far you can reach a PCI Express network. The protocol isn't capable of sending it for tens
or hundreds of meters, for example. And there's significant amounts of other problems associated, for example, with
energy efficiency, the types of connectors that it depends on and so on.

So as a result, PCI Express is, I think, probably not going to win this market space. And of course, Astera has put
significant amounts of resources and investments in their PCI Express-based products, both retimers and their - the
Scorpio switch lines. So those investments from Astera are not necessarily going to yield product line momentum and
profitability growth toward the end of the decade.

For the intermediate time, there's still a need for PCI Express and servers. I think that those products are going to sell
reasonably well, but I think that their future is limited. The third approach to this entire venture is to sort of try to
replicate some of the value of the NVLink and InfiniBand ecosystem, but in a standards-based way. And those
standards are called basically UALink or the sort of CXL standard Coherent Express Link.

Those are standard-based ecosystems, and they tend to run over Ethernet network links. So that's all standards-
based. You can run for the chairmanship of a committee defining that stuff from any company who's a member of
those standards bodies. And NVIDIA can't really squish it. There's also significant amounts of intellectual property
protection associated with those standards.

So if you're coming in with a patent that you hope will be implemented in that standard, you're required to disclose it
and you're also required to sign off that you're going to license it at reasonable and nondiscriminatory terms. So
you're not going to hold an implementer of that standard hostage because you happen to have one link level
protocol patent somewhere, you're required as part of the standards body to actually disclose and license that
reasonably.

So the three choices are the NVLink InfiniBand ecosystem, the PCI Express ecosystem, and the UALink over Ethernet
ecosystem. And I think that it's a horse race between number one and number three. Intel used to be hoping for
number two. I think they've given up on that. The PCI Express thing is not going to be a scale-out network for the

5

Confidential

02/18/2026 at 18:56 PM UTC

world.

And as a result, I think they're getting on bed with who they think is the likely front-runner, which is NVIDIA's NVLink
stuff. And by say - when I say getting in bed with, I mean that, that means that future Intel processor chips, future Intel
switch chips, future Intel co-packaged optics engines will probably embody the NVLink protocols. And that's probably
bad news for Astera because they're sort of in the PCI Express camp.

They're like Sony who bet on the Betamax and eventually had to pivot and build VHS VCRs. I think that we'll see the
same thing potentially happening to Astera. They're going to have to think about getting into chiplets. They're going
to have to think about pivoting their PCI Express switches to either NVLink switches or UALink switches or maybe
multimode switches that can do both.

But until - they've got a few years of runway in front of them with the PCI Express stuff, at which point I think they're
going to see a point of diminishing sales, and they'll have wished that they started in 2025 working on some other
approaches to switching and interconnect and all of the retimers and cable drivers and DSP stuff that goes along with
it.

So I really think that it's going to be a forcing function is probably the right way to describe it, that Astera is going to
have to pivot to recognize whichever one of those other two camps they think is going to be the winner in the
marketplace or if they can figure out how to do it for a reasonable cost, figure out how to support both alternatives in
a new family of products.

SD: So the position, you said, you know, the forcing of the repositioning and then forcing the investment, how long -
so that was a great overview, by the way, Chuck, I really appreciate that. Thinking about the time line to achieving
some of these, you know, some of these potential opportunities that are risk that may have to - Astera sorry, Astera
may have to explore to maintain relevancy and to kind of not lose share.

You're saying they start in '25, but what do you think the latest is that they can start kind of adopting or thinking about
these new technologies and incorporating that into their product road map, which I get the impression that from what
you've seen with your research, it's not really on their product road map at least of right now.

When you think about like kind of the medium term, what is their kind of time line in your view to where they have to
think about this and you said a couple of years, but if there's any way we can kind of even potentially put together a
finer point, on what that looks like? Would love any color around that.

CB: Yes, as in many situations with this whole AI GPU, big data center cluster architecture, a lot of that is really driven
by NVIDIA's decisions in their product families. So they've already announced at least the code names of two product
families of next-generation GPUs. The first one is called Rubin Vera, where Ruben is the GPU and Vera is like a
processor, a CPU with ARM computer control inside of it.

And then you use Vera's and Rubin's sort of together where the DSP - the GPUs in the Rubin chips are doing the heavy
lifting, the AI model training and inference. And then the Vera CPU chips are sort of doing the coordination control
and data wrangling piece of that. And those two chips together represent the chipset that will be in the next-
generation products. They've also announced the code name of the generation after that, which is called Feynman.

And that chip is - we don't know much about it, at least publicly, but we expect that it will have significant amounts of
innovations in one direction or other. Now I think what's likely to happen is that NVIDIA will double down on the
InfiniBand NVLink stuff and not go to anything PCI Express or UALink in those - in that generation.

6

Confidential

02/18/2026 at 18:56 PM UTC

Simultaneously over the next couple of years, say, by 2026, late or 2027, Intel is going to be announcing next-
generation server CPUs that are going to jump in and run the - the NVLink protocols, native, there'll be pins on the
CPU that maybe used to be PCI Express interface pins. Now they're going to be either multimode pins or exclusively
NVLink pins.

So that means that you can take a Vera - you don't necessarily need the Vera CPU. You can take the Rubin GPUs and
connect them to Intel multi-mode CPU that has these kinds of interfaces connected to them. So what that really means
is that you need to wait for about one more generation of chips to come out.

The Rubin Vera chips should be out in the middle of next year, 2026. I would expect that Intel is going to take about
12-18 months to demonstrate the first chips that have NVLink interfaces in them. So call that early 2027, I think, is the
first time that we can do an interoperability connection between an NVIDIA GPU and an Intel CPU. That will be a
watershed moment for the industry.

And my bet is that it's going to be in the global conference that will be hosted in March of 2027 by NVIDIA. And I think
if you want me to put, you know, estimate a real fine point, I would say March of 2027 is the place where you can start,
you know, buying large quantities of chips that do - that put this partnership into real action.

And that is perhaps the point where there will be less and less of the sort of PCI Express active electrical cable stuff
that Astera has become fairly proficient at. So if you're going to ask me when the inflection point is when Astera's
revenues associated with their current approach to data center network are going to start to fall off, that's the
watershed event, first quarter, maybe second quarter '27.

SD: Helpful. And that's about as strong a pinpoint as I can ask for. So I want to ask for more on that. I appreciate it,
Chuck.

CB: I can look at the exact date of that conference, but-

SD: Good. I think we are going to get to it buddy. You know, the one thing I want to talk about is, you know, Astera is
listed as kind of this NVLink Fusion partner. And I'd love to understand, you know, from what the research and work
you've done, what does that partnership kind of entail today?

And does this kind of - if you think about PCIe displacement risk, we just - which we spent the majority of the call
talking through, you know, do these opportunities potentially present - are these - are there potential opportunities
here that can offset that? Or are there places they can be that end up coming kind of a different path for them or
different kind of revenue opportunity for them? I'm just curious or product opportunity even for them. Any thoughts
around that?

CB: Yes, so NVLink Fusion, I think it was announced April of this year, something like that. And it really represents an
attempt for - by NVIDIA to sort of open up the NVLink ecosystem a little bit beyond their proprietary GPU to InfiniBand
switch chip link, which was generally what NVLink was up until that point. So there were, I think, about eight or nine
different companies that were announced as partners in the NVLink Fusion approach.

Certainly, Astera is prominent there, but so was MediaTek, Marvell, Alchip's, Synopsys, Cadence and then a couple of
CPU vendors, Qualcomm and Fujitsu that was as of last May. So basically, those companies say, yes, we like the
NVLink approach to interconnecting things. We would like to support chips that connect to that network. And we're,
you know, buying on licensing the NVIDIA technologies necessary to make that happen.

So I think what that basically means is that Astera needs to take a look at what their connectivity products can do, their

7

Confidential

02/18/2026 at 18:56 PM UTC

retimers and so forth. Are they adequate to run the kinds of protocols and physical links that NVLink Fusion demands?
I think the answer is yes, they're probably either can run it just as they are or easily adaptable to work under those
scenarios.

A potentially harder problem for Astera is that NVLink Fusion requires a whole bunch of higher-level software
protocols. So for example, when you first plug in somebody else's processor into an NVLink network, there's a whole
bunch of negotiation that goes on, kind of like when you first plug a USB thing into your computer, the computer
stops and thinks for a while to see if it can find the device drivers and recognize the device and validate the security
and all that stuff.

There's a whole lot of that software that Astera is going to have to write and perfect and distribute across the
marketplace. So Astera's software infrastructure is called COSMOS. And it's really about sort of tuning the parameters
of the retimers and programming the switches and memory controllers and stuff. That's what COSMOS does.

COSMOS will have to have additional modules added to it that enable it to process all the NVLink Fusion protocols,
manage the NVLink Fusion devices, do orchestration so that you, for example, know what priority order different
messages have to go in and out, that kind of stuff. Certainly, security postures are going to be important because
hackers are going to try to get into NVLink Fusion networks. They will be a very high-value target if they can penetrate
it.

And it would be a real shame if Astera's components some had a security vulnerability. So I'm sure they understand
that risk and are working hard to get the security posture of COSMOS up to the task. So I suspect that they're going to
have six months or a year worth of development before they can go to a plug fest and say, let's plug in an Astera
NVLink Fusion thing on to a bunch of NVIDIA GPU clusters and see if we can communicate.

Those, you know, theoretically, in simulations, that stuff generally works pretty quickly. But tuning it up to the point
where we can actually, you know, go in and make sure that all of the protocol layers are right and all the physical
cables are connecting appropriately, that's going to take them at least six months. But once they get that done, then
they could potentially have a leadership role in that ecosystem of those eight or 10 companies that I mentioned
because, you know, they'll be among the first to actually connect third-party devices to NVIDIA networks.

I would expect that, you know, that's sort of the potential for their ability to get into this NVLink Fusion world. I haven't
seen any products announced from Astera that specifically say this is an NVLink Fusion capable switch chip or memory
controller or a link extender. And certainly, they'll be working on that stuff, but I haven't seen any public
announcements of that.

I hope that they do make those public announcements. I hope they're able to demonstrate at least some of this stuff at
the NVIDIA conference next March. And it's a stretch, but I think it could be possible. Some other things that they
could also do is realize that their current - Astera's current product line may not be precisely matched to the needs of
the NVLink Fusion ecosystem and Astera could pivot.

They could go more toward chiplets which is a thing that their arch competitor, Credo, is already doing. A chiplet is a
little sliver of silicon that sort of gets stuck next to a major chip like a GPU or switch in order to, for example, adapt I/O
connections from one side to another. So one could think about making PCI Express to NVLink Fusion chiplet and
then offering that as a gasket, as a buffer between the NVLink universe and the older school PCI Express universe that
Astera is more involved in.

Astera could also pivot toward a significant threat to the later half of the - or the later part of the decade called co-

8

Confidential

02/18/2026 at 18:56 PM UTC

packaged optics, and we can talk about that deeper into this call. But that would be another mechanism for them to
try to address some of the new opportunities via pivots into those opportunities rather than continuing to beat on PCI
Express products that are going to be diminishing in their opportunities.

SD: Maybe we can kind of start that conversation on co-packaged optics and what that looks like. Obviously, that's a
central theme and data point, I'd say - sorry, evolution, not data point, but, you know, in terms of how we're thinking
about what happens with interconnectivity and kind of these components and how they're going to be - how
networking interacts with GPUs. So yes, Chuck, why don't we talk about that? Let's talk about what we think on
Astera's role and kind of what that looks like kind of going forward?

CB: Right. So co-packaged optics is a bit of a departure from the way that these large-scale servers and switches are
built today. Today, these are - first of all, it's very important that we understand that this isn't just about throwing a
bunch of CPU cores in a box and hoping for the best. Those cores have to be very carefully interconnected with very
high-speed trillion bit per second speeds of connections.

And that's necessary because no single GPU, even though it has over 20,000 processor cores on it, can do the whole
job of something like training a trillion parameter AI model. You need clusters of dozens, hundreds, maybe tens of
thousands of GPUs to complete those kinds of training runs at reasonable amounts of time.

You also need clusters of that size to manage the fact that sort of, you know, every user on Facebook right now in two
or three years is going to be running their connectivity through an AI inference engine and, you know, scaling millions
of simultaneous users means you might need millions of simultaneous GPU sessions.

So you've got to have connectivity between the various processor chips that's really efficient, very low latency,
meaning there's not too many nanoseconds of time that elapses as the connection goes across those inter GPU
cables. There's really two kinds of networks.

There's what's called a scale-up network, which means that all of the GPU chips in a box are connected together. In
the case of the NVL72 reference design from NVIDIA, it's a box the size of a refrigerator that has 72 GPUs and there's
like 2 miles of cabling, 5,000 different connectivities across the cables that go between those GPUs.

That - there's also a thing called a scale-out network where you take this rack of 72 GPUs, and you connect it to dozens
or hundreds of sister racks using higher speed cables that generally are fiber optic cables that go longer distances. So
what co-packaged optics does is it lets us improve the efficiency, speed, power utilization of those potentially
hundreds of thousands of interconnects that go from one GPU chip to the other GPU chips in the cluster.

And right now, we do those connections by coming out of the bottom of the GPU chip with electrical connections,
running a few centimeters across to an optical transceiver or some kind of a backplane connector or some kind of a
retimer like an exterior retimer chip. And then those connections go across various kinds of optical or electrical
cables. Electrical cables can only go about three meters, say, 10 or 12 feet.

Optical cables can go kilometers if necessary. And then they end up on the other side of the connection via these
optical or electrical facilities. What - the problem with that is jumping out of a chip electrically and then going a few
centimeters to this optical transceiver, this little matchbox size thing that turns it to optical signals or a thing called an
active electrical cable, which is where the Astera retimers tend to go, which turns it into a few meters of electrical
cabling.

That whole thing is very expensive, physically large and very power hungry. So what they're going to do is they're

9

Confidential

02/18/2026 at 18:56 PM UTC

going to take the components associated with those optical transceivers doing the electrical to optical and vice versa
conversions. And they're going to suck them inside of the package of the chip.

That's why they call it co-packaged optics because the optical interfaces are packaged inside of the same chip as the
semiconductors and memory that we already see on GPUs. The thing that, that will enable, assuming that companies
like NVIDIA and AMD do that in their GPUs is instead of having a GPU with a bunch of optical transceivers and a
bunch of cable driving connections, you just bring fibers right out of this little top hat on top of the chip.

And then those fibers can go a couple of hundred meters any place in the data center you want them to go. And then
they terminate directly on the far end chips without any need to go electrical at all. All of the electrical connections are
inside of the chips on both ends, but the connections among those chips are optical. That saves a whole lot of board
area, a whole lot of cost, those optical transceivers that run at, say, 800 billion bits per second, they cost $2,000, and
you might have a dozen or more of them on an individual GPU chip.

So it adds up really fast. They also take a lot of power. Each of those endpoints takes on the order of 10 watts. So if
there's a couple of dozen endpoints, there may be a few hundred watts of electrical power associated with those
interfaces. Pulling it into co-packaged optics, instead of $2,000, it might be a couple of hundred dollars per channel.
Instead of 10 watts per channel, it might be 1 watt per channel.

So you're looking in co-packaged optics at an order of magnitude potential savings in both power and capex. That's
huge. The thing that's interesting about co-packaged optics from an Astera perspective is there's absolutely no Astera
content in the connection from one GPU to another. It's just a couple of fiber optic connections and a bunch of fiber
optic ribbon fibers.

Astera, if they want to play in this sort of end of the decade game where instead of being connected together with a
bunch of electrical and a few optical connections, it's all optical, then they're going to have to pivot into a way that
gets them into more of the enabling technologies for co-packaged optics. I think co-packaged optics is inevitable,
and it's really a question of which companies are going to be the winners.

Certainly, retimers and PCI Express switches and various kinds of electrically based memory controllers are not the
answer to how you stay relevant at the end of the decade when co-packaged optics is upon us. The companies that
are looking the most relevant right now are companies like Corning who make the fibers, and the connectors
associated with that.

Companies like Astera Labs, who are experts on the lasers and the sources of optics and the interfaces of high-density
multichannel optics. There's a few other companies that are out there in this space that really, I think, are most
certainly going to be involved. Astera, they don't have, in my knowledge anyway, a lot of research going on in co-
packaged optics.

They think that electrical is the answer for the rest of the decade. I think that electrical is the answer for a couple,
maybe three years. But at the end of the decade, I think that the chip-to-chip connections are going to be largely
optical for the reasons I've described. And if Astera doesn't pivot to some way that they can get involved the way that
[HereLab? 35:46] and Corning and Coherent and other companies are, they're going to see a great loss in their
interconnect business.

SD: You know, Chuck I don't think we touched on - I think you briefly kind of touched on it, but I want to make sure -
just make sure we extend on this point. The power and cooling requirements that optical presents in terms of
challenges, how do you think that gets resolved or yes, change? How does that change over the next kind of couple of

10

Confidential

02/18/2026 at 18:56 PM UTC

- yes, I mean like multi years?

CB: As we scale the data centers, putting more and more GPUs into a place that used to be a few CPUs. Now we have
a few dozen or a few hundred GPUs into the same rack. As we do that, we have three fundamental challenges. The
density of these things are increasing. So we have to figure out how to get lots and lots of interconnect in and out. Co-
packaged optics does that.

It's harder to do with active electrical or active optical cables. The second challenge is how do you get enough
electrical power into this bigger rack - and there's a bunch of companies like Eaton and Vertiv and a few others that
are trying to figure that out. We'll probably go from the 208-volt AC that we use today to something like 800 volts DC.

And that's a significant benefit to companies who make UPSs, companies like Tesla, for example, 800-volt DC power
supply for a rack full of GPUs is not all that different from the battery pack inside of a Tesla cyber truck. So that's - so
getting the enough energy in to run all of the processing cores and all of the tens of thousands of optical
interconnects that could be inside of this is going to be a challenge.

And there's a bunch of companies who are potentially postured on this move from 200-ish volts AC-800 volts DC is a
much more efficient way to deliver the power into those racks. Those racks are going to take 600,000 watts in the
next-generation NVIDIA rack called Kyber. That's going to be a trick. The final challenge beyond interconnect and
power entry is cooling.

And how do we get the - every watt that we put in generates 4 BTUs, I think I did that math right, of thermal output
from that rack. And as a result, you need to have a way that you can cool these high-density racks, blowing a bunch of
air at it like the fan in the back of your laptop that makes the top of your thigh sweat is not the answer. You have to
have a coolant that's much more efficient than air, and that's generally a liquid coolant.

The NVIDIA - the next two generations of NVIDIA racks are using a technology called direct-to-chip liquid cooling.
Where a bunch of water-based coolant sort of circulates around a whole bunch of plumbing and then that circulates
through the special cold plate that's bolted to the 1,000-watt GPU chip, and it takes the power out of the silicon into
this cold plate, which is a chunk of copper with a bunch of serpentine channels in it.

And then there's fluid flowing in the serpentine channels and then that gets sucked away and rejected by the air
conditioning on the roof of the data center. That's the way that we're going to do it for the next couple of years. At the
end of the decade, there's an even more promising thermal technology that's called immersion, which we just take
the entire server, all the memory, everything in the server, and we dip it in a vat of cold oil.

And then the oil sort of removes the heat through convective processes into the oil, and then we circulate that oil
through a bunch of heat exchangers and reject the heat to the outdoors. Those technologies are all applicable to co-
packaged optics and are all, I believe, inevitable in the future of these data centers.

The data center that we're building five years from now is going to look pretty damn foreign to the data centers that
we are deploying today in companies like, say, CoreWeave and Lambda Labs and those kind of companies. We're
going to see a significant change because of these demands of this high density on power and cooling energy out
and interconnect.

And I think that Astera could be in a position to drive some of the interconnect part of that and they would have to
take their requirements into account associated with how the energy arrives in the rack of equipment and how the
thermal - how the heat is removed from that rack of equipment.

11

Confidential

02/18/2026 at 18:56 PM UTC

So Astera needs to build chips that are capable of immersion cooling, for example. I've never seen them mention that
before. But next year, all the customers are going to say, we think we're going to be immersion cooling in two years,
are your chips ready? And if the answer is no, then they'll shop for other chips.

SD: Super helpful color. You know, you look at the Intel NVIDIA partnership and it reinforces the importance of rack-
scale computing. How well do you think Astera is to benefit from the broader adoption of CXL and other rack-scale
standards even if NVLink gains traction in select architectures?

CB: Yes, there's a whole lot of opportunities for different architectures in rack scale. Certainly, for the hyperscalers, the
place where Intel is still perhaps king is you have a rack of equipment about the size of a refrigerator and you have 40
1U servers, about the size of 40 pizza boxes kind of stacked in that refrigerator and then there's a top of rack switch
that collects all the data and sends it off.

Astera doesn't have a whole lot of plays in that space right now. The connections from the 1U servers to the top of
rack switch are typically Ethernet cables, electrical connections that Astera doesn't really have a significant amount of
play in. I can see them, you know, maybe in the top of rack switch, there might be some opportunities for something
like a PCI system or whatever.

But in general, I don't think they're going to be selling a lot - as we scale up to something like the NVL72 rack, which
has 72 GPUs, there are places where things like retimers, active electrical cables, and then the PCI Express
infrastructure on the front of some of those servers could be an opportunity for them. The NVL72 reference
architecture is sort of invented by NVIDIA and it has been adopted by 16 of their partners.

So it's sort of suggested once by NVIDIA since they understand how all the chips are sort of intended by their
designers to be hooked together. And then it's - that reference design is licensed out to companies like Lenovo and
Dell and HPE in order to build the servers in volume. That's interesting and an approach that I think that they're going
to follow.

The next generation of rack level system is code named Kyber. We've seen a few mockups of what we think that Kyber
is going to look like. It is even more dense. It's 600,000 watts compared to the 120,000 or 140,000 watts that the
NVL72 is. And as a result, the equipment is even more meshed together. The power and cooling challenges are
extreme, and the interconnect challenges are extreme.

Much of the interconnect in that system is actually done by fairly short connections across a backplane. And we
believe that Amphenol is the primary technology supplier for the connectors on that backplane. And the backplane is
passive. There's no Astera chips on the backplane. It's just a bunch of hundred thousands of wires that are connecting
the boards inside of that server together.

I don't think that there's a whole lot of opportunity for Astera content. At least in the primary connections between the
many GPUs in that rack. I think that there may be some opportunities for them as part of the scale-out network where
you have a need to connect one set of these racks to a few dozen other racks in the cluster.

And under those circumstances, the retimer products might be useful as you build active electrical cables for the
reaches that you can - the cables that you can reach out to different places in that cluster. So I think that there's
potentially some opportunities there, but I don't see it as a huge growth area as we start looking at the scale up. I think
that we're also needing to take a look at whether or not technologies like CXL or UALink are going to jump in and try
to catch up with NVIDIA's interconnect dominance.

12

Confidential

02/18/2026 at 18:56 PM UTC

It's clear to me that NVIDIA has got like 80% of the interconnect world right now on the rack level scale implications.
But it's also clear to me that the market really wants a standards-based solution that isn't driven by NVIDIA and may be
partnered with their new lapdog, Intel. They're looking for, you know, different companies to jump in and show
leadership.

And it's really on AMD's shoulders right now to try to do the same kind of partnerships and ecosystem creation that
NVIDIA has been very successful at. I haven't seen strong evidence that AMD is capable of doing that. The jury is still
out on whether their MI400 and MI450 chips are going to be viable competitors in this GPU space.

My gut feeling is they're going to be about a year behind NVIDIA and remain there for a while, which means that
NVIDIA will maintain their market dominance, especially if NVIDIA is able to make use of the experiences and
expertise of Intel, then I really don't see a rack scale change away from the NVLink over InfiniBand ecosystem. And
that's probably bad news for Astera unless Astera can somehow pivot and amplify their NVLink Fusion efforts to be
more relevant in that ecosystem.

SD: Appreciate that. So I wanted to ask you something more broadly. You mentioned the NVIDIA AMD. I just wanted
to get your thoughts on a final question, not necessarily totally topic related, but related to GenAI. You know, you've
seen in the last five weeks, OpenAI announced contracts for, you know, 26 gigawatts of capacity in terms of chips, you
know, 10 from Broadcom, 10 from NVIDIA, six from AMD. It's been a flurry of announcements.

And you run that against what today is probably them operating at around 4-5 gigawatts. If you think about like the
deal they have with Oracle, they clearly, you know, they've signed deals to lift their capacity by 6x. Any thoughts on
feasibility, practicality? You know, just given that you spent a lot of time in this space, I'd love any opinions you might
have on some of these announcements, what you think it means?

CB: Well, they're obviously all in on this, right? And they have the credibility of Wall Street because everybody has
played with their products and everybody was blown away two years ago when GPT came and everybody could, you
know, start writing their term papers. And, you know, I use it to write poems for my wife's birthday cards, you know,
stuff like that. So the fact that they're looking at gigawatts, tens of gigawatts worth of investment is not surprising.

They realize that there's a first-mover advantage here. And the announcements are sort of plausible in terms of the
direction that they want to go. Now there's this question of are they practical? So a gigawatt of GPUs is, you know,
maybe it's tens of thousands of chips for sure. Probably - and it just depends upon the efficiency of the data center.

Chips are - tend to be on the order of 2,000 watts or so if you take all of the - that's what a typical large-scale GPU is if
you count all of the stuff around it. So if you take a look at that, you end up with, you know, 500,000 chips per, you
know, something like that per gigawatt. So this announcement means that you're going to be putting in lots and lots
of GPUs and racks and racks of GPUs.

The question now starts to become, where do you get the electrical energy to run them? That's the first question. And
that turns out to be a really, really hard problem, especially if you're trying to do it in an environmentally responsible
way. China is trying to grow gigawatts worth of GPUs. They don't have access to the best NVIDIA GPUs because of
embargoes, but they're trying to grow many gigawatts of GPUs, and they're doing that by burning coal.

So they're mining coal in kind of the, you know, one part of China and then they train it in and then they burn it, then
they run the power over to a different part of China, where it is funneled into data centers where DeepSeek and
they're like Huawei chips and so on are all racked up and trying to build large-scale AI.

13

Confidential

02/18/2026 at 18:56 PM UTC

In the United States, a little harder. I was actually at a city council zoning meeting last month where they were talking
about putting a 72-megawatt data center near Chicago and there was significant community pushback. They're really
worried about is the power grid up to this? Are we going to have blackouts because of that data center? Is it going to
make our utility or our power bill go way up because of scarcity? Is it going to have a carbon impact?

So, you know, are we going to end up burning a lot more coal or whatever to make this energy necessary to run those
multiple gigawatts. Are we going to use a lot of water? Sometimes cooling evaporates millions of gallons of water. So
we could be looking at tens of millions of gallons per data center per month. And how do we, you know, do we have
that water? We can't suck out of the Great Lakes because of the treaties, it's hard to do.

So my belief is that 26 gigawatts is probably unrealistic given the energy, water, and public sentiment in the United
States. There are places in the world, Russia, you could probably get away with building some of those data centers,
hydroelectric plants in China might be useful. There's - so there's significant concerns about that. Sustainability is
going to be a real problem.

The carbon footprint of that is going to be similar to the aviation industry, ok? That's a hard problem. You know,
you're going to have to figure out how to convince the greenies that blowing all that carbon into the atmosphere
using conventional electrical generation is the right answer. If this is something that we can wait toward the end of the
decade for, there is a potential technology on the horizon that could actually supply 26 gigawatts of electrical energy
to this thing.

That technology is small modular reactors, where you build a nuclear reactor about maybe, you know, one-tenth or
one-fifteenth the size of a traditional boiling water reactor you find in a power station. And you put a few of them, you
know, bury them in the ground out in the parking lot behind your data center. So your 100-megawatt, 150-megawatt
data center, of which you need a lot of them to get to those gigawatt numbers, has, say, three or four small modular
reactors buried in its parking lot.

And those reactors are making nuclear energy and they're feeding it right into the data center. There's no electrical
utility. There's no grid to expand. There's no power meters really involved. The data center owns the reactors, and the
reactors power the data center. That is a carbon-free mechanism to do that. If we can figure out how to get the
uranium into those things last for many years and how to get the waste out of them and reprocess.

There's ways you can do it without serious environmental toxicity, unproven, but the technology is theoretically
possible. That's a way that they can potentially make this work. So the energy into the data center is the first obstacle.
The second obstacle is, can we build enough GPU chips? And the answer is probably not. There's a certain amount of
fabrication facility for these sort of 2-nanometer and better chips that we're talking about in this time frame.

That exists in four buildings in Taiwan and maybe a couple of buildings in the United States and Europe. Those
buildings cost $10 billion or more to create and equip with the appropriate very expensive machines. And they take
about five years to build.

So if OpenAI and those kind of companies think they're going to need 20 gigawatts worth of GPU chips, you know,
the first question I'm going to have is where is the power plants? And the second question I was going to have is
where is the dozen 2-nanometer wafer fabs, $10 billion each that you need to build those chips? I don't think they
exist.

So, you know, you can do a few gigawatts here and there without necessarily impacting the global silicon supply. But
20 gigawatts, especially if you want to do it in the case of a couple of years, is well beyond any current or planned

14

Confidential

02/18/2026 at 18:56 PM UTC

capacity for semiconductor fabrication and chip assembly, which, in my opinion, means that is sort of unfeasible
unless something radical changes.

SD: Right, we will end it. Chuck, thank you so much for your time. Really appreciate all the color as always. Let's catch
up again real soon.

CB: Yes. Thanks, Sheetal. Good luck to everybody, and thanks to the listeners for listening in and hope that the
insights are useful and good luck on your investing. Take care.

SD: Thanks so much. Take care. Bye.

CB: Bye.

DISCLAIMER: The statements or opinions expressed today are those of the Advisor and not Guidepoint, who disclaims all liability
for the content provided. The Advisor may not disclose material nonpublic or confidential information or any information that would
cause the Advisor to breach any duty or obligations. Guidepoint is not a registered investment advisor and the information
provided is not intended to constitute investment advice.

15

Confidential

02/18/2026 at 18:56 PM UTC



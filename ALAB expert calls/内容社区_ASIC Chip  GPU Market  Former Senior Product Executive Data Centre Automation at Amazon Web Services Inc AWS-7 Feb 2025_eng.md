COMMUNITY

65d0d6538a8911da05d11de9b49cc840996c80c0

ASIC Chip & GPU Market 每 Former Senior
Product Executive, Data Centre Automation
at Amazon Web Services Inc (AWS)

Consultant | 7 February 2025

Specialist Background

> Over 25 years' experience in the IT industry, with deep insights into strategy, product

development and operations

> Well-placed to discuss AWS' (Amazon Web Services') core value proposition, internal and
external workloads, performance levels, economic model and partnership with Marvell

> Strong understanding of Nvidia's competitive positioning, dominance in the training market,
inference use cases, software capabilities and brand credibility, as well as GPU (graphics
processing unit) replacement trends

> Well-versed in custom accelerators and ASICs (application-specific integrated circuits) building

processes

Contents

As I think about the pace at which Amazon is moving, maybe compared to Trillium, I feel like
that's the greatest scale of custom ASICs [application-specific integrated circuits] out there. It
feels like somewhat fast and furious. I know on the earnings call most recently they talked
about Project Rainier is going to grow into couple hundred thousand Trainium to UltraServers
at the end of the day. When I speak to folks in the industry, it sounds like build plans are a lot
more than just a couple hundred thousand. The pace of growth here seems pretty impressive.
As you look back at the journey here, starting with Graviton at the CPU level and then moving
into custom ASICs for AI acceleration, what do you think is the main thing that's enabling AWS
[Amazon Web Services] to take some learnings maybe from the industry, but also from their
internal efforts on custom silicon at the CPU and now moving forward into acceleration, that is
likely driving a lot of the momentum that we're likely going to see over the next 12 months with
Trainium2 and then furthermore with Trainium3 and 4, which are in development.

6

ASIC Chip & GPU Market 每 Former Senior Product Executive, Data Centre Automation at Amazon Web
Services Inc (AWS) 每 7 February 2025

What do you think about the balance between the opportunity set for internal acceleration? The
bespoke foundation models that Amazon has across its cloud infrastructure and search engines
and recommendation engines as it relates to the advertising business. Comparing that to the
likelihood that more external customers look to adopt Trainium at scale, similar to what we're
seeing from Anthropic so far and potentially a few of others that have been commented as
having tested the chips. Do you think it's much more an internal opportunity where you get the
big cost savings because you have to pay the USD 30,000 tax on GPUs [graphics processing
unit]? Do you think that the external opportunity can be just as big?

How should I be thinking about the opportunity set for replacing Nvidia GPUs internally with
training at the end of the day? Will it follow a similar pace as Graviton, where small volumes,
call it, 5-7 years ago, now growing into 60% of internal now on Graviton. Is that the right
linearity to think about or could it be accelerated? Is there a good way for me to think about the
GPU requirement for Amazon at the end of the day, like thinking about the fact that they bought
somewhere around 50,000-plus H100s last year. What are their actual needs? Do you think that
their needs are closer to the 100,000-200,000 that Microsoft and Meta got and that they just
got deprioritised on allocation and that they'll probably grow into that? I would think that their
scale is similar to Microsoft and Meta, if not more. I'm just trying to get a feel for as they would
look to replace Nvidia, is that at least a 100,000-accelerator opportunity and then everything
else is gravy as they look to get external customers to adopt?

Would you say that the long pole in the tent for getting broader external adoption resides at
NeuronLink at the end of the day? My understanding is that whether it's NeuronLink, ICI [sic]
for Google, that when you compare it to the bandwidth capacity and latency of NVLink at the
end of the day, it still lags. I'd imagine that service level agreements have pretty rigid
requirements that might be benchmarked against what NVLink can already require. efforts on
the scale network for Amazon are going to be most important to gauge if they're going to be
super successful in getting external customers to adopt, right? Amazon aiming to sell this
custom acceleration to external customers. If I'm thinking about Trainium2 Ultra server
clusters and doing something similar where Anthropic is now building out this big cluster to do
their foundational model training on that. How replicable is that? As customers have
conversations with Amazon, would you expect that kind of performance and latency penalties
from NeuronLink compared to NVLink, as it relates to the scale-up GPU-to-GPU interconnect
is a main talking point around areas of improvement that would be necessary to get broader
replicability of what we're seeing with Anthropic adoption with Amazon today?

As I think about how this progresses, what do you think the largest changes might be as I think
about the overall cluster architecture as we move from Blackwell to Rubin and Trainium2 to
Trainium3 and Trillium v6 to v7. One thing that's been coming up is that we're at PCIe
[peripheral component interconnect express] gen 5. This coming year, we're going to be at PCIe
gen 6. The PCIe gen standard came out only recently and we're just getting a controller around
now, which would suggest that silicon isn't going to be out for another year or two, so there's a
bit of a mismatch with the performance jumps that are going to be coming from Trainium3 and
Rubin and TPU 7 and PCIe is not going to be able to keep up. Do you expect to shift from PCIe-
based copper to optics as we think about 2026 as a function of that dynamic and mismatch
towards insertion?

Private and confidential

7

7

8

8

2

ASIC Chip & GPU Market 每 Former Senior Product Executive, Data Centre Automation at Amazon Web
Services Inc (AWS) 每 7 February 2025

About actual co-packaged optics, what I've heard is that there's a bit of a replacement issue
where it might have 99% success rate, 1% failure rate or a certain decimal point of failure rate.
When those failures do occur, the whole system goes down because it's co-packaged. How
should I be thinking about the need for near packaged optics or pluggable optics relative to co-
packaged optics, at least in the next 12-24 months? How should I be thinking about the ability
to solve those system failure issues for CPO [co-packaged optics] over the longer term? Do you
think that co-packaged optics is going to be the standard in the long term? There might be
some staying power for these pluggable or near to the chip packages at the end of the day,
right?

What does this mean for some of the players that are over-indexed to whether it be PCIe or
ethernet at the end of the day? I think of Astera Labs where they have the retimers, which I feel
like optics dilutes the need for those. I think of even Credo where they've got a solid AEC [active
electrical cable] story, but I think that's copper-based. As I think about active optical, I think
that the competition increases pretty meaningfully at least vs their opportunity set for just
active electrical. Do you see those two players as losers, as we think about the technology shifts
over the next couple years?

I think your point around the fact that optics is going to be centred around the biggest
parameter workloads and the biggest cluster sizes is an important one. If you think about the
PCIe gen 5 to gen 6 cutover, is that going to take a lot longer than maybe you'd initially think?
Obviously, everyone's talking about this move to optics, this move to gen 6, but that's centred
around the cutting edge. There's a pretty long tail of less cutting-edge workloads at the end of
the day. Should I be thinking about durability of demand for things like PCIe gen 5 at the end of
the day, where obviously the big four will adopt a certain percentage of the newest GPUs and
accelerators out there, but they're going to keep a portion with some of the older stuff for cost
efficiency purposes to your point around lower throughput and lower cluster size. If I think
about the window of opportunity for Astera and Credo and those kind of companies that need to
be aware of these technology shifts, like it's not by the end of the year, they have a little bit
more time to make a move until we're at a point where optics is becoming the higher volume
workhorse at the end of the day. Is there any pushback on that general kind of pattern?

As you think about the back-end networking fabrics that a lot of these companies have, I think
everyone wants to figure out a way to displace NVLink to some extent. The same way that
they're doing with GPUs on the front end. There's a few technologies that get talked about,
Ultra Accelerator Link and Ultra Ethernet link. I feel like the runt of the litter CXL gets talked
about it as a fabric that has latency issues. As you think about where the most potential is to
displace NVLink over a longer-term time frame, who should I be the most focused on, whether
it's consortium or company-based to track their progress that you think are just taking a good
approach and have the best shot at actually displacing NVLink to a meaningful extent?

The Marvell Tanzanite team sounds like they might have departed the company over the last
4-5 years, which is concerning. Then that leaves you Microchip who I had never really bet on.
How are you thinking about the landscape relative to that? Is there anyone that you think is
doing the right things, CXL wise as we think about standards improving and getting established
in a broad-based form over the next 4-5 years, where should I be focusing on? Am I missing
anything as I think about the competitive landscape?

Private and confidential

9

9

10

10

11

3

ASIC Chip & GPU Market 每 Former Senior Product Executive, Data Centre Automation at Amazon Web
Services Inc (AWS) 每 7 February 2025

What do you see as the long pole in the tent? Other than the standards, because you've
mentioned that already, that's obviously got to come first. As I think about next steps, one is
you need a switch chip because that has 3.0 compatibility and opens up the doors for pooling,
which is the killer app at the end of the day and will drive memory fabric use cases. Then maybe
related to that, it sounds like with CXL not being on the tray per se, there's host biassed issues
where there's a lot of latency that gets introduced if you don't have strong software
management of the in and outs as it relates to the signals and especially when you have
multiple racks feeding into a broader fabric or pool, that's concerning. Do we need to get a
switch chip and we also need to get better software layer at the end of the day before
hyperscalers look at this seriously?

I think I saw that Marvell did a PCIe gen 7 SerDes [serializer/deserializer] demonstration at
DesignCon and a few folks that I spoke to said that the set-up of that would suggest that at gen
7, maybe they're all sing in the switch chip market a little bit. It seems like competition is going
to increase at Broadcom. At the end of the day, they're more than happy to just slice prices. I
wouldn't be surprised if they offer a similar 64-lane chip that would be priced at or below levels
that maybe some of the new entrants are coming to the market. As you think about that space,
do you think that 95% share is very much at risk for Broadcom? Do you think they've got
enough tools in the tool shed to defend their share and stay as the vast market leader?

I feel like the big long-term debate right now is, you got an accelerator TAM. Nvidia has got
80%-plus share of that. When do we get to the end of the decade? What does that evolve into? I
feel like the big moving dynamic for me within that is that workloads are fluid. They change all
the time. We saw DeepSeek really step function down in terms of efficiencies as it relates to
algorithms, which is going to just change the way that folks are doing their training and
inference, so some might argue that a general purpose approach third-party merchant GPUs,
particularly Nvidia, benefit from that fluidity because they can adopt more efficiently, whereas
some of these more custom solutions that are optimised to relatively finite workloads might
have a harder time with the fluidity. Keeping that in mind, as you think about the 80/20 or 85/15
split that exists today, when we get to 2030, do you think custom ASICs takes a much bigger
piece of the pie? How would you think about that split over time based on some of the dynamics
that we need to consider?

Of those smaller startups, who are you most excited about? I hear about Cerebras and Grok
ready to ramp this year, but probably more like a 2026 story. Clearly, some positive momentum
here. Outside of them, including them, but also anyone else that you think I should be taking a
look at who might nibble at the lower-hanging fruit from Nvidia outside of just the custom
ASIC efforts by the hyperscalers?

If you look at hyperscale CAPEX, it'll usually grow by 50% over three years and then consolidate
for a year and then do it again and then consolidate. If you just run that pattern, it would
suggest that 2026 is possibly a digestion period. I know that a lot of the public comments from
hyperscalers has been around maybe just spending at most recent run rates which would imply
that 2025 is higher because you get a full four quarters of that spend. As we move into 2026, it
brings a lot of questions. Do you think that we're getting closer to a point where AI CAPEX can
peak out a little bit and folks will digest the work they've done and let assets sweat a little bit
and are closer to supply, demand balance? Do you think it's further than 2026?

Private and confidential

11

12

13

13

13

4

ASIC Chip & GPU Market 每 Former Senior Product Executive, Data Centre Automation at Amazon Web
Services Inc (AWS) 每 7 February 2025

About DeepSeek, whatever their actual efficiencies are because obviously, USD 6m is not the
right training number. The algorithms are very interesting in the sense that they've lowered the
cost to inference by a good bit. I feel like a lot of people are trying to get a feel for whether or not
this opens up the edge AI inference opportunity a lot more. What are you thinking about the
likelihood that, based on DeepSeek as a signal that there's plenty of scaling as it relates to
getting inference costs lower? Are we going to see a lot more AI compute at the edge, whether
that's through handsets or laptops or tablets or random kind of more application-specific IoT
[Internet of Things] devices?

It's unlocking because of the lower cost. If I isolate that dynamic to someone such as Google,
Meta or Amazon, where they've got a workload that's applied to search or advertising
recommendation engines or same thing with Meta, does what DeepSeek has shown and
contemplating future improvements lower the total accelerator requirements for those internal
efforts, I guess, at the end of the day. Take Meta because we're using it on this inference
opportunity. Meta bought 150,000 GPUs last year, but that's because their parameters were
almost USD 45bn. Now as we work through algorithms, maybe they're going to get down to 300
or 200 or 100. Does that cut in proportion the total amount of accelerators that they need for
their internal stuff?

14

15

Private and confidential

5

ASIC Chip & GPU Market 每 Former Senior Product Executive, Data Centre Automation at Amazon Web
Services Inc (AWS) 每 7 February 2025

ASIC Chip & GPU Market 每 Former Senior
Product Executive, Data Centre Automation
at Amazon Web Services Inc (AWS)

Transcription begins

Analyst:
I'm basically just trying to get a little bit smarter around how to think about where a lot of these custom
ASIC [application-specific integrated circuit] developments are going because obviously, the
momentum is pretty quick. Within that a few of the components that are going to likely benefit from the
fact that you got Google, Amazon, Meta, Microsoft all kind of hyper focused on this.

As I think about the pace at which Amazon is moving, maybe compared to Trillium, I feel like that's the
greatest scale of custom ASICs [application-specific integrated circuits] out there. It feels like
somewhat fast and furious. I know on the earnings call most recently they talked about Project Rainier
is going to grow into couple hundred thousand Trainium to UltraServers at the end of the day. When I
speak to folks in the industry, it sounds like build plans are a lot more than just a couple hundred
thousand. The pace of growth here seems pretty impressive. As you look back at the journey here,
starting with Graviton at the CPU level and then moving into custom ASICs for AI acceleration, what do
you think is the main thing that's enabling AWS [Amazon Web Services] to take some learnings maybe
from the industry, but also from their internal efforts on custom silicon at the CPU and now moving
forward into acceleration, that is likely driving a lot of the momentum that we're likely going to see
over the next 12 months with Trainium2 and then furthermore with Trainium3 and 4, which are in
development.

Specialist:
AWS has the DNA and expertise for development, custom ASICs. They acquired Annapurna, a company
from Israel about 15 years ago and that's where the Graviton was born. Basically, their philosophy is if
they own the design development, they own their destiny. They can cut out the third party and those
cost savings, they can pass those cost savings to their customers. It basically is an amazing value
proposition for both sides. They are basically following their suite from, as you mentioned, from
Graviton to Trainium. They are doing the design in-house. Yes, they bring in Marvell and Alchip or
whatever, other partners for different parts and pieces, but they own the design.

The philosophy is develop these Inferentia and training chips and just like Graviton-based hardware,
start building hardware with these custom chips so that they don't have to solely depend on Nvidia of
the world or even AMD for that matter. In the long run, next 2-3 years, you'll start seeing these chips-
based servers coming out, providing competing performance than Nvidia and AMD. That's my personal
observation. That's where the industry is going. That's why you see Google and Microsoft getting into
the custom ASICs as well. They have seen AWS doing it extremely successfully. Of course, for that
matter, Meta as well, the MDI a chips, accelerator chips they develop. Apple is getting into that as well.
I've seen some reports even Tesla is trying to do, so that is becoming an industry trend to develop these
ASICs for their custom use cases and basically serve their customers.

Analyst:

Private and confidential

6

ASIC Chip & GPU Market 每 Former Senior Product Executive, Data Centre Automation at Amazon Web
Services Inc (AWS) 每 7 February 2025

What do you think about the balance between the opportunity set for internal acceleration? The
bespoke foundation models that Amazon has across its cloud infrastructure and search engines and
recommendation engines as it relates to the advertising business. Comparing that to the likelihood
that more external customers look to adopt Trainium at scale, similar to what we're seeing from
Anthropic so far and potentially a few of others that have been commented as having tested the chips.
Do you think it's much more an internal opportunity where you get the big cost savings because you
have to pay the USD 30,000 tax on GPUs [graphics processing unit]? Do you think that the external
opportunity can be just as big?

Specialist:
For AWS, the first thing is, one thing I wanted to clarify, you don't need GPUs for everything. Up to USD
7bn, you can run CPU-based hardware without a problem. It provides equal or even better performance.
Basically, what I'm saying is for a lot of work that AWS is doing right now, Graviton3 is just doing the job
right now for those web surfing and analytics that don't require millions of parameters, so having that
said, AWS is I think their main goal is serving their customers and using these chips for their own data
centres. I don't think they're going to walk away from that culture. They're not selling Graviton to
anyone. They're just using them to build their own data centres. As you may know, with the success they
have now about 60% of their data centre worldwide runs on Graviton. That's a lot, so my take would be
they would do the same thing with these Trainium and Inferentia chips. They're going to slowly and
gradually start replacing AMD, Nvidia wherever they can as they start building stronger, better chips,
better hardware and better clusters.

Analyst:
Then appreciating your point around the fact that not all workloads need GPUs at the end of the day,
smaller parameters sets are going to be just fine with CPUs.

How should I be thinking about the opportunity set for replacing Nvidia GPUs internally with training
at the end of the day? Will it follow a similar pace as Graviton, where small volumes, call it, 5-7 years
ago, now growing into 60% of internal now on Graviton. Is that the right linearity to think about or
could it be accelerated? Is there a good way for me to think about the GPU requirement for Amazon at
the end of the day, like thinking about the fact that they bought somewhere around 50,000-plus H100s
last year. What are their actual needs? Do you think that their needs are closer to the 100,000-200,000
that Microsoft and Meta got and that they just got deprioritised on allocation and that they'll probably
grow into that? I would think that their scale is similar to Microsoft and Meta, if not more. I'm just
trying to get a feel for as they would look to replace Nvidia, is that at least a 100,000-accelerator
opportunity and then everything else is gravy as they look to get external customers to adopt?

Specialist:
Dilemma that Microsoft and Google and others have is they don't have servers like Graviton, so that's
the primary reason. They're now trying to get into custom chips to have more powerful SoCs. At the
moment, they don't have any option but to buy GPUs from Nvidia, and they are buying a lot more than
Amazon is. Your observation is spot on. Amazon, on the other side, of course, they have a bigger
customer base. They are number one hyperscalers in the world. Their customers are asking for
accelerated workloads. In many cases, they are getting by using the Graviton servers, and where they
cannot, they are buying H100s and then they would also buy G200s or GB200-based clusters. They are
doing it very strategically, in my opinion, where you can get away without using GPUs, they are using
their in-house hardware and how quickly they're going to start developing the acceleration based on
these Inferentia and Trainium chips.

Just imagine the architecture at a high level would be, you have a host CPU that basically works with an
Inferentia or Trainium chip, which has HBM or LDDR5 memory, depending on how the cost of the set-

Private and confidential

7

ASIC Chip & GPU Market 每 Former Senior Product Executive, Data Centre Automation at Amazon Web
Services Inc (AWS) 每 7 February 2025

up. With that type of set-up in the middle of all this, you could offload and get performance equivalent
to H100 and 200 at a fraction of cost. I mean there are start-ups that are doing that right now. They are
trying to sell that type of hardware to other companies, so that is the evolution. Long story short, what
I'm trying to say is Amazon is very frugal. They have the edge with their Graviton. They could use it for
AI workloads wherever they can, where they don't have that option, only then they buy H100 and 200. In
the background, they're going to build up these Inferentia, have their custom acceleration going and
then start going replacing or buying less of Nvidia.

Analyst:
Would you say that the long pole in the tent for getting broader external adoption resides at
NeuronLink at the end of the day? My understanding is that whether it's NeuronLink, ICI [sic] for
Google, that when you compare it to the bandwidth capacity and latency of NVLink at the end of the
day, it still lags. I'd imagine that service level agreements have pretty rigid requirements that might be
benchmarked against what NVLink can already require. efforts on the scale network for Amazon are
going to be most important to gauge if they're going to be super successful in getting external
customers to adopt, right? Amazon aiming to sell this custom acceleration to external customers. If
I'm thinking about Trainium2 Ultra server clusters and doing something similar where Anthropic is
now building out this big cluster to do their foundational model training on that. How replicable is
that? As customers have conversations with Amazon, would you expect that kind of performance and
latency penalties from NeuronLink compared to NVLink, as it relates to the scale-up GPU-to-GPU
interconnect is a main talking point around areas of improvement that would be necessary to get
broader replicability of what we're seeing with Anthropic adoption with Amazon today?

Specialist:
The matrix, the interconnect is definitely super critical because, as you pointed out, the game is you
basically hook up multiple accelerators and CPUs and that matrix, that whole network seems to work
efficiently. The good thing is they are both using Arm based architecture, which provides inherent
matrix capabilities to grow, to scale the cluster size. Amazon would have that plus using that technology.
They are investing in Anthropic, as we all know. I think from the interconnect and I/O capacity
perspective, basically, this is I/O, connecting one node with another. I think Amazon, they already have
their internal technology that they would amp up for higher cluster size to compete with NVLink or
provide better performance. I think innovation is their DNA.

Just think of this, if they are working on the next generation of Trainium and Inferentia, they for sure,
know that without scaling, these chips are not going to do anything. They have to learn how to scale
these accelerators to the level they can provide comparable performance with Nvidia or AMD. They
haven't shared a lot of details about the interconnects and what technology they're going to use. I'm
sure they're working hard and heavy to get that developed along with the next generation of these chips.
What I would also think if they have vested interest, in a particular company, for example, Anthropic,
they may not sell this technology publicly. They haven't done that again with Graviton, but they may do
that for their business partners where they have invested, or they have bought a company that does.
Let's say, they buy another company in the future that does something special in AI. As opposed to
having them buy Nvidia or AMD hardware, they may make their hardware available for them, so that is
certainly possible.

Analyst:
As I think about how this progresses, what do you think the largest changes might be as I think about
the overall cluster architecture as we move from Blackwell to Rubin and Trainium2 to Trainium3 and
Trillium v6 to v7. One thing that's been coming up is that we're at PCIe [peripheral component
interconnect express] gen 5. This coming year, we're going to be at PCIe gen 6. The PCIe gen standard
came out only recently and we're just getting a controller around now, which would suggest that

Private and confidential

8

ASIC Chip & GPU Market 每 Former Senior Product Executive, Data Centre Automation at Amazon Web
Services Inc (AWS) 每 7 February 2025

silicon isn't going to be out for another year or two, so there's a bit of a mismatch with the
performance jumps that are going to be coming from Trainium3 and Rubin and TPU 7 and PCIe is not
going to be able to keep up. Do you expect to shift from PCIe-based copper to optics as we think about
2026 as a function of that dynamic and mismatch towards insertion?

Specialist:
Absolutely. Yes. There's a lot of optics already being developed, a lot of companies doing this. Even now,
they're being used in some of the data centres, so that shift is happening. We'll have better switching
and interconnectivity based on fibre and optics. As you know, right now, even within the data centre,
when you connect a rack with another rack, that is not an Ethernet switch. That's all optic based, so
these companies are using similar logic and now trying to figure out how they can provide way better
performance than PCI, ie, using optics. There's a lot of work being done in that space, and we'll see some
good technology coming out in the next year or two.

Analyst:
About actual co-packaged optics, what I've heard is that there's a bit of a replacement issue where it
might have 99% success rate, 1% failure rate or a certain decimal point of failure rate. When those
failures do occur, the whole system goes down because it's co-packaged. How should I be thinking
about the need for near packaged optics or pluggable optics relative to co-packaged optics, at least in
the next 12-24 months? How should I be thinking about the ability to solve those system failure issues
for CPO [co-packaged optics] over the longer term? Do you think that co-packaged optics is going to
be the standard in the long term? There might be some staying power for these pluggable or near to
the chip packages at the end of the day, right?

Specialist:
It's going to be just like any other technology, co-packaged is necessity right now for tighter
integration. As you can imagine, in an initial stage, the bigger issue is how do you get to have the
hardware and optics work together, and that requires a lot of integration. It is co-packaged to avoid the
software and hardware issues. In the longer run, as the technology progresses, it's going to turn into, in
my opinion, a pluggable module, just like what we have for ethernet switches. It's just you could use it in
different ways you can. I think it's going to evolve to that model in the long run. There will be their
standards going to be built, and if you have standard interfaces just like we have for PCIe 5, I don't see a
reason why would we not have pluggable modules down the road.

Analyst:
What does this mean for some of the players that are over-indexed to whether it be PCIe or ethernet at
the end of the day? I think of Astera Labs where they have the retimers, which I feel like optics dilutes
the need for those. I think of even Credo where they've got a solid AEC [active electrical cable] story,
but I think that's copper-based. As I think about active optical, I think that the competition increases
pretty meaningfully at least vs their opportunity set for just active electrical. Do you see those two
players as losers, as we think about the technology shifts over the next couple years?

Specialist:
No, they're going to transition. It's nature of the beast, adoption is going to happen or they're going to
lose. It's one of those things. Broadcom, for example, they are king of the ethernet switching. They're
not going to just sit silent and just stay there in that mode. They're working on optics, and we all know it.
I think all these players, they're going to have both options. Cheaper one would be ethernet and PCIe-
based solutions and then for lower throughput applications and then the optics coming into the more
niche, the more bigger cluster sizes. I think the industry is going to transition towards it. There's no
other way around in my opinion.

Private and confidential

9

ASIC Chip & GPU Market 每 Former Senior Product Executive, Data Centre Automation at Amazon Web
Services Inc (AWS) 每 7 February 2025

Analyst:
I think your point around the fact that optics is going to be centred around the biggest parameter
workloads and the biggest cluster sizes is an important one. If you think about the PCIe gen 5 to gen 6
cutover, is that going to take a lot longer than maybe you'd initially think? Obviously, everyone's
talking about this move to optics, this move to gen 6, but that's centred around the cutting edge.
There's a pretty long tail of less cutting-edge workloads at the end of the day. Should I be thinking
about durability of demand for things like PCIe gen 5 at the end of the day, where obviously the big
four will adopt a certain percentage of the newest GPUs and accelerators out there, but they're going to
keep a portion with some of the older stuff for cost efficiency purposes to your point around lower
throughput and lower cluster size. If I think about the window of opportunity for Astera and Credo and
those kind of companies that need to be aware of these technology shifts, like it's not by the end of the
year, they have a little bit more time to make a move until we're at a point where optics is becoming the
higher volume workhorse at the end of the day. Is there any pushback on that general kind of pattern?

Specialist:
No, I think you're thinking along the right lines. From taxation perspective and even overall cost saving
perspective, what I'm noticing is back in the day, the life of the hardware was about five years. Now I'm
seeing these data centres, they are even pushing to 6-7. I mean running web-based services, you don't
need anything fancy. You can extend the life and save some money. To your point, they're just gradually
going to scale over to optics wherever they can, they're going to stay. I mean even look at PCIe evolution,
going from four to five, gosh, it took us, what, 2-3 years. By the time it was everywhere. I think it's going
to be similar pattern. These companies have 2-3 years to slowly and gradually start moving depending
on cost savings and existing hardware customer demands, all these factors, they will have to balance it. I
think they have a bit of time.

Analyst:
As you think about the back-end networking fabrics that a lot of these companies have, I think
everyone wants to figure out a way to displace NVLink to some extent. The same way that they're doing
with GPUs on the front end. There's a few technologies that get talked about, Ultra Accelerator Link
and Ultra Ethernet link. I feel like the runt of the litter CXL gets talked about it as a fabric that has
latency issues. As you think about where the most potential is to displace NVLink over a longer-term
time frame, who should I be the most focused on, whether it's consortium or company-based to track
their progress that you think are just taking a good approach and have the best shot at actually
displacing NVLink to a meaningful extent?

Specialist:
A lot of people are betting on CXL. My only worry with them is the standardisation takes a little longer. I
think that's the way to go. anything that's non-standard, the scalability would become an issue. The
integration would become an issue. These small companies, they come up with good solutions. They're
very proprietary. I'm dealing with, even AMD, MR3 still is going through integration issues. That's one
of the reasons they got held back and they couldn't scale because customers are totally just ticked off. It
just can't set it up, can't make it work, and so my point is there's all start-ups with niche solutions they
may look nice and fancy. If they are not standardised, the bigger corporations are not going to go for
them and adapt their solution. CXL in any standardised solution is going to be the way to go because of
the interoperability and scalability, and so I would focus on that or even the smaller companies that are
trying to standardise stuff. I think they would have a better chance, better luck than companies with
their totally customised one-off solutions.

Analyst:
Within the CXL ecosystem, Astera Labs is the most loud about it with their controllers. I wouldn't be
surprised if they're going to work on a CXL switch over time. It seems like they're qualifying the

Private and confidential

10

ASIC Chip & GPU Market 每 Former Senior Product Executive, Data Centre Automation at Amazon Web
Services Inc (AWS) 每 7 February 2025

expansion controllers for now and just seem to be talking about it the most. You have Marvell, who
acquired Tanzanite a handful of years ago, did a big presentation on it. I haven't really heard much since
it sort of seems like they're shifting to this near memory compute approach, which is a bit different,
comes at a premium, has a little bit better performance, but I don't know that that's necessarily what
folks are looking for. You have Broadcom who, at one point was working on development of a CXL
switch. I think they acquired a company for IP a few years back. It seems like they might be shifting their
focus a little bit to Ultra Ethernet over CXL, at least from an R&D dollar perspective.

I know Microchip is doing a little bit. I know XConn is working on a CXL switch but has had a lot of issues
with the silicon. That's kind of the landscape as I know it from like at least a hardware perspective. It
seems like we've heard the least problems and most focus from Astera, there's no issues with an
execution from Broadcom, but it's a question of focus.

The Marvell Tanzanite team sounds like they might have departed the company over the last 4-5
years, which is concerning. Then that leaves you Microchip who I had never really bet on. How are you
thinking about the landscape relative to that? Is there anyone that you think is doing the right things,
CXL wise as we think about standards improving and getting established in a broad-based form over
the next 4-5 years, where should I be focusing on? Am I missing anything as I think about the
competitive landscape?

Specialist:
No, I think you got it right. Astera is probably pushing it. They are working hard and heavy. Actually,
Microsoft is now involved big time because they want standardised solution. They're pushing hard. They
have publicly announced Meta as well, they want to build acceleration solution. The bigger guys are
jumping in. They have dedicated people that are putting, pushing forward with the standardisation. Arm
has a number of folks working in that direction as well. I think of course, Broadcom is going to push
forward with the Ultra Ethernet. I think we'll have probably two choices, CXL based and Ultra Ethernet
type of solutions. I think that's how the industry is going to move forward.

Analyst:
What do you see as the long pole in the tent? Other than the standards, because you've mentioned that
already, that's obviously got to come first. As I think about next steps, one is you need a switch chip
because that has 3.0 compatibility and opens up the doors for pooling, which is the killer app at the end
of the day and will drive memory fabric use cases. Then maybe related to that, it sounds like with CXL
not being on the tray per se, there's host biassed issues where there's a lot of latency that gets
introduced if you don't have strong software management of the in and outs as it relates to the signals
and especially when you have multiple racks feeding into a broader fabric or pool, that's concerning.
Do we need to get a switch chip and we also need to get better software layer at the end of the day
before hyperscalers look at this seriously?

Specialist:
Yes, absolutely. It's about the whole stack. Basically, at the end of the day, it's like third-party IP
integration with the hardware. You may be using a software stack from, let's say, whatever company,
the hardware is being developed by whatever company. Just like in PCIe situation, you can get Synopsys
to give you the IP, but the hardware could come from whatever company, and they both of them, the
whole stack, hardware software has to work. Similar phenomena there. You have to think of this
integration from a complete stack perspective, and that's where the standardisation really forces that
that you have to build everything compliant with the standard. Even if you do, they would have some
sort of their own variant that throws things off. Basically, my point is it's a full stack integration.
Otherwise, things just don't work.

Private and confidential

11

ASIC Chip & GPU Market 每 Former Senior Product Executive, Data Centre Automation at Amazon Web
Services Inc (AWS) 每 7 February 2025

Analyst:
I think we'll hear about expansion this year because Granite Rapids in turn are ramping. They are the
first CPUs with 2.0. I'm sure Graviton probably has it as well, so there's that opportunity set. I think that
there's some decent expansion opportunity this year. As I think about standards, switch chip silicon and
software, is pooling and competing against NVLink as a fabric more of '27, '28, '29 type of dynamic as I
think about the moving pieces and the likelihood that it takes a little while to work through all those
things?

Specialist:
Yes. I think '27 is more likely than anything else at this stage, given where we are from a standardisation
perspective and everything else.

Analyst:
I didn't get the chance to look at the 3.2 spec. I don't know if you looked at it and did anything surprise
you in terms of good improvements at least compared to the prior specification for CXL that they're
moving in the right direction.

Specialist:
No, I haven't looked at the 3.2 specs as well. I've been focusing. Yes.

Analyst:
Another part of this server architecture that I feel like is starting to get competed for is Broadcom's got
the PCIe switch chips that reside on the compute tray that do multi-node heterogeneous interconnect at
the end of the day. They've had 95% share of whatever the market size is, maybe USD 1bn, mostly to do
with the fact that the only other person able to provide a product is Microsemi, and it's pretty bad. Then,
you have Astera that came out with the switch chip with only 64 lanes vs Broadcom offering up to 144.
Their pitch is that Broadcom is stuffing too many layer counts down customers' throats because they
have a monopolistic position in the market. That's leading to port underutilisation, so if you're able to
come in and cut the price by more than 50% on a per lane basis that you're offering really good TCO
[total cost of ownership] and up in the utilisation for the hyperscalers, so it makes plenty of sense.

I think I saw that Marvell did a PCIe gen 7 SerDes [serializer/deserializer] demonstration at DesignCon
and a few folks that I spoke to said that the set-up of that would suggest that at gen 7, maybe they're
all sing in the switch chip market a little bit. It seems like competition is going to increase at
Broadcom. At the end of the day, they're more than happy to just slice prices. I wouldn't be surprised if
they offer a similar 64-lane chip that would be priced at or below levels that maybe some of the new
entrants are coming to the market. As you think about that space, do you think that 95% share is very
much at risk for Broadcom? Do you think they've got enough tools in the tool shed to defend their
share and stay as the vast market leader?

Specialist:
Yes. I think Broadcom is going to continue excelling. There's two primary reasons. Switching is a very
niche business in with their market share they make it extremely difficult for the new players to come in
and do something new. Arm has tried to build in other folks as well, the open source stuff. It's making
progress, but it's like not to a point where they can start taking a huge share from Broadcom. There's a
lot of ODMs that are looking at open source options using that software and maybe even Intel's stack
their IP. There they're making small headwinds. I think in the long run, Broadcom with their market
share, they will continue to succeed in that space. The open source, I'm forgetting the name that I'm not
100% switching person. Yes, there's an open source software that Microsoft and other folks started, and
a lot of Chinese ODMs are using that. There may be a shift in other parts of the world where we would see
Broadcom share going away because they don't have to deal with paying a lot of hefty fees to Broadcom

Private and confidential

12

ASIC Chip & GPU Market 每 Former Senior Product Executive, Data Centre Automation at Amazon Web
Services Inc (AWS) 每 7 February 2025

or buy their hardware, so that transition is happening, but it's very slow, especially it is pretty much
outside the US. I know a couple of ODMs in China that are hard and heavy using open source and trying
to build switches based on that.

Analyst:
I feel like the big long-term debate right now is, you got an accelerator TAM. Nvidia has got 80%-plus
share of that. When do we get to the end of the decade? What does that evolve into? I feel like the big
moving dynamic for me within that is that workloads are fluid. They change all the time. We saw
DeepSeek really step function down in terms of efficiencies as it relates to algorithms, which is going
to just change the way that folks are doing their training and inference, so some might argue that a
general purpose approach third-party merchant GPUs, particularly Nvidia, benefit from that fluidity
because they can adopt more efficiently, whereas some of these more custom solutions that are
optimised to relatively finite workloads might have a harder time with the fluidity. Keeping that in
mind, as you think about the 80/20 or 85/15 split that exists today, when we get to 2030, do you think
custom ASICs takes a much bigger piece of the pie? How would you think about that split over time
based on some of the dynamics that we need to consider?

Specialist:
I think by end of the decade, my bet would be, it's going to be more like 70/30 split with ASICs being built
at the speed, every big organisation, Microsoft, Google, Amazon, you name it, Meta, they're all building
their acceleration ASICs. They have dedicated team, partners, so with all that work by the end of this
decade, I think they're going to easily chip away 15-20% share from Nvidia. It's just from there, it's
going to go further down. The standardisation is going to start coming along. Optics will become a bit
more prevalent, so things are going to change and that people would have definitely different options
than Nvidia by end of this decade. I mentioned, there's at least seven custom exploration companies,
small start-ups that I know today have hardware ready to go. They're able to sell it to smaller data
centres, really small ones, colos. Again, as the time progresses, their penetration is going to increase as
well. With all these factors in mind, I think conservatively speaking, Nvidia share is going to go down by
at least 15% by 2030.

Analyst:
Of those smaller startups, who are you most excited about? I hear about Cerebras and Grok ready to
ramp this year, but probably more like a 2026 story. Clearly, some positive momentum here. Outside of
them, including them, but also anyone else that you think I should be taking a look at who might
nibble at the lower-hanging fruit from Nvidia outside of just the custom ASIC efforts by the
hyperscalers?

Specialist:
Grok is one for sure. There's a few that are staying under the radar. I'll share the public ones. FuriosaAI is
another one. Rebellions and FuriosaAI, are two that are making great progress.

Analyst:
If you look at hyperscale CAPEX, it'll usually grow by 50% over three years and then consolidate for a
year and then do it again and then consolidate. If you just run that pattern, it would suggest that 2026
is possibly a digestion period. I know that a lot of the public comments from hyperscalers has been
around maybe just spending at most recent run rates which would imply that 2025 is higher because
you get a full four quarters of that spend. As we move into 2026, it brings a lot of questions. Do you
think that we're getting closer to a point where AI CAPEX can peak out a little bit and folks will digest
the work they've done and let assets sweat a little bit and are closer to supply, demand balance? Do you
think it's further than 2026?

Private and confidential

13

ASIC Chip & GPU Market 每 Former Senior Product Executive, Data Centre Automation at Amazon Web
Services Inc (AWS) 每 7 February 2025

Specialist:
Definitely further than 2026. The analyst reports I have seen by, right now, if you look at the overall
hardware, general purpose is 75-80% and 2025 is AI. By the time we get to 2030, it's going to be 60/40
split.

Analyst:
In favour of AI or in favour of general＃

Specialist:
No AI because AI right now is barely 15-20%, is going to grow to 40% by 2030.

Analyst:
Overall CAPEX dollars, we might see flatten out a bit, but when you look under the covers, there's further
growth for the AI piece.

Specialist:
Absolutely. AI is going to carry the majority of the CAPEX dollars, and also even the GP stuff is 3-5 years
cycle time. They will get replaced with better hardware. In some cases, the cost of running that piece of
hardware is more than the hardware itself. You will see companies getting rid of older stuff. Some of the
Dell Edge stuff is quite high in power. My point is there will be replacement of general purpose. Overall
spending will continue to grow in hardware and data centre space in next 10 years.

Analyst:
About DeepSeek, whatever their actual efficiencies are because obviously, USD 6m is not the right
training number. The algorithms are very interesting in the sense that they've lowered the cost to
inference by a good bit. I feel like a lot of people are trying to get a feel for whether or not this opens up
the edge AI inference opportunity a lot more. What are you thinking about the likelihood that, based on
DeepSeek as a signal that there's plenty of scaling as it relates to getting inference costs lower? Are we
going to see a lot more AI compute at the edge, whether that's through handsets or laptops or tablets
or random kind of more application-specific IoT [Internet of Things] devices?

Specialist:
The way I look at this is it's just as pick any industry. When the industry is going through initial stage,
applications are niche, hardware is niche, the cost of doing business is really high. Only X number of
companies can afford, for example, right now to buy GPUs. This is the nature of the evolution. As the
new companies come up with new ways of doing things, things start getting, technology starts getting
commoditised. That means that cheaper, more affordable technology is now available to a lot more
people, so the scale and volume goes up. Basically, even though it's cheaper to, let's say, go with
DeepSeek for a second, the growth is phenomenal in AI. Even though the cost of hardware goes down or
even we improve the software technologies. There's a lot of work being done at the software layer to
improve performance requiring less hardware, a ton of work. All the culmination point in my opinion is
it's going to become more economical to do, to run AI workloads. With that, it's going to open up that
door to a lot more companies and people to use it. With that, the scale is going to grow, and overall
spending is going to keep going. That's my way of thinking, and this is based on, you can look at any
technology.

Analyst:
I did an analysis where if you think about going from mainframes to computers to PCs to smartphones
to IoT devices, they're cost per MIPS always goes up when you get to initial adoption. It's not like the
value proposition is savings. It's more that the actual computing capabilities go way up. Then over time,
that cost per MIPS falls. As it falls, it unlocks elasticities of demand like you're speaking about that the

Private and confidential

14

ASIC Chip & GPU Market 每 Former Senior Product Executive, Data Centre Automation at Amazon Web
Services Inc (AWS) 每 7 February 2025

unit TAM just grows exponentially.

Specialist:
There you go.

Analyst:
It's unlocking because of the lower cost. If I isolate that dynamic to someone such as Google, Meta or
Amazon, where they've got a workload that's applied to search or advertising recommendation
engines or same thing with Meta, does what DeepSeek has shown and contemplating future
improvements lower the total accelerator requirements for those internal efforts, I guess, at the end of
the day. Take Meta because we're using it on this inference opportunity. Meta bought 150,000 GPUs
last year, but that's because their parameters were almost USD 45bn. Now as we work through
algorithms, maybe they're going to get down to 300 or 200 or 100. Does that cut in proportion the total
amount of accelerators that they need for their internal stuff?

Specialist:
Yes. It certainly improves and reduces the number of accelerators you need. The thing is everyone is just
thinking about just direct correlation without even thinking about the applications, meaning if you're
running a genomics workload, HPC type of workloads or weather, right? They are very, very compute
intensive. The thing is, I think we don't know enough about DeepSeek, what they're doing, how they're
doing? The results we're seeing, they're pretty much on the search type of activity, which doesn't
require a lot of compute. My take is there's a lot of compute heavy workload, niche workload that are
going to continue needing a lot more GPUs, and absolutely, wherever the software and the new
technologies and you're going to see more folks like DeepSeek coming up with new ways of doing things.
They would reduce the hardware requirements. I don't see an abrupt change right away. It's going to be
a gradual change over time, just like any other technology evolution.

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

15



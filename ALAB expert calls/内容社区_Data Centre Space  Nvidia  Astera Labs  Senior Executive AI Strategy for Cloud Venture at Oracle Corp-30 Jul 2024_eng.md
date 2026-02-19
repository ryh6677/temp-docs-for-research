COMMUNITY

65d0d6538a8911da05d11de9b49cc840996c80c0

Data Centre Space 每 Nvidia & Astera Labs 每
Senior Executive, AI Strategy for Cloud
Venture at Oracle Corp

Customer | 30 July 2024

Specialist Background

> Over 30 years' experience in the data networking space, focusing on AI strategy and business

development

> Knowledgeable on data centre operating models and providers, as well as their differentiating

factors and strengths and weaknesses

> Can speak to CPU inferencing opportunities, customer-specific strategies, hyperscalers and

retimers

Contents

This comment from Jensen saying less retimers are necessary at the end of the day in the back
end isn't overly impactful for someone like Astera Labs because that's not really the way that
they sell their products. Is that the correct understanding of the landscape or is there a negative
content story, so to speak, for Astera Labs as we do shift over to GB200 moving forward into
next year?

Another takeaway is that everything that Jensen said at GTC pushed out the AMD accelerator
opportunity, coming from the perspective of the fact that it would seem that NVIDIA is the
undisputed training leader and that that training portion of this AI investment cycle has some
more legs, and the inferencing will really start to play a bigger role, maybe a little bit later than
everyone had anticipated, at least in meaningful fashion. How are you thinking about it, where
AMD for MI300 is really going to be, by and large, more of an inferencing play than a training
play and how might they start playing a bigger role in the broader accelerator spend bucket?

Doing it via copper instead of optical is more of the issue, where doing some of that back-end
intra- and inter-data centre connection let the data travel through that pretty wide fabric of
clusters, and is where NVIDIA is thinking about shifting things a little to maybe save some
costs. I'd be right to think that will impact someone like a Marvell and a Broadcom that have
data centre.

4

5

Data Centre Space 每 Nvidia & Astera Labs 每 Senior Executive, AI Strategy for Cloud Venture at Oracle Corp
每 30 July 2024

I'm aware Oracle is pretty closely aligned with someone like an Ampere that's doing single-
threaded performance. That's going to be driving a lot of that. Are there specific workloads that
the CPU inferencing is best-equipped for, where you would want to go that route instead of GPU
inferencing? How will that opportunity play out on the inferencing side of things? Will it be
driven by workload or by what a customer-specific strategy is? How does that CPU inferencing
opportunity expand over time? What are the key drivers underneath that?

How big of an issue is asset utilisation for those smaller models to the extent that they might sit
more idle than that larger single foundation model because more prompts might go into it,
whereas specialised prompts will go to the smaller models? Is there an issue where inference
deployment is sitting more idle than a typical large foundational model? How does that get
worked through over time? Presumably, use cases will proliferate, and that will help it a little,
but I imagine it is a bit of a headache in the early days at the very least.

Do you believe we're far enough along in the training build-out? You mentioned if you have a
30,000 cluster, you're probably looking at 90,000-100,000 square feet of data centre space
that's going to be required for those things, but are we at a point yet where the actual clean
room space, that's what we call it for semiconductor fabs, the actual data centre footprint isn't
going to be as much of a bottleneck because we're starting to shift increasingly to some of these
smaller and more proliferate edge points that require less of a build-out at the end of the day?
You probably saw Elon Musk building these tiny little rack spaces in trucks, so it seems like
people are getting pretty nimble about it as it relates to finding the data centre space that they
need.

The other bottleneck is the fact that the NVL72 version of GB200 is going to be liquid-cooled
and it seems that capacity for guys like Verint and some of the other liquid cooling providers is
pretty constrained, and so there's a possibility that hyperscaler cloud customers in particular
would be willing to wait 90 days or whatever it would need, to be able to get the liquid cooling
capacity back where it needs to be, as opposed to buying air-cooled solutions, because those
types of customers want to have the leading-edge types of GPUs at the end of the day. How have
you been navigating that as liquid cooling, investing fast enough, so to speak, until I keep up
with what is going to be necessary for when we do shift over to more of these NVL72-type GPUs
that do require the liquid cooling infrastructure?

It only just started coming up. It was said by a few of the private GPU cloud guys, and I think
that they have a large deployment of GPUs and so maybe it's a little bit idiosyncratic, so to
speak, where they vs the industry might face some delivery issues vs their expectations, but
more broadly, it feels like things are chugging along and that liquid cooling isn't this broad-
based issue, so that's also good to hear. What are your thoughts?

Private and confidential

5

6

6

7

7

2

Data Centre Space 每 Nvidia & Astera Labs 每 Senior Executive, AI Strategy for Cloud Venture at Oracle Corp
每 30 July 2024

In today's world with these HGX platforms, it's just eight GPUs, and we're shifting over to a
world where NVL72 can have orders of magnitude more than that. Can you have less retimers
on a per GPU ratio? My understanding is no because it's held by the PCIe generation speeds. If
you're at 128 [sic], even if you have way more GPUs per CPU, you're still going to need the same
amount of retimers because it's mostly just an issue of, once the data travels far enough off of
the GPU, you need to put a retimer to retransmit the data and avoid signal integrity issues. It's
hard to find efficiencies even if the GPU-to-CPU ratio is improving. Does that make sense to
you where you're still going to need maybe a 1:1 retimer to GPU or slightly less than that and
that you can't use less retimers just because of that distance factor, which is a pretty rigid
limitation to keeping the data signal integrity where it needs to be?

How would you rate the progress there, because NVIDIA is innovating pretty quickly, and I'm
sure that they're going to have new announcements that move the goalposts even farther back
vs what UltraLink [sic] is trying to bridge the gap upon? How is that going because I know that
it helps being this open consortium and having a lot of different companies working on it in
tandem? I imagine that they'll bridge the gap, but how are you thinking about timing-wise?
When would you expect it to get more competitive, that the big cloud guys would start
considering using it more as an alternative?

Does the UEC success benefit everything that Broadcom is doing from a PCIe perspective over in
Astera Labs because Astera is so closely aligned with someone like NVIDIA, and so the success
of NVIDIA is something that Astera will ride the curtails, and if Broadcom and UEC can crack the
code, that would actually be the bigger thing to focus on that would be a bit more negative over
the medium-to-longer term for someone like Astera Labs?

Share shift would start to manifest probably in 2026. Is that the right way to think about it, if
things keep plugging away the way that they are?

Private and confidential

8

8

8

9

3

Data Centre Space 每 Nvidia & Astera Labs 每 Senior Executive, AI Strategy for Cloud Venture at Oracle Corp
每 30 July 2024

Data Centre Space 每 Nvidia & Astera Labs 每
Senior Executive, AI Strategy for Cloud
Venture at Oracle Corp

Transcription begins

Analyst:
This comment from Jensen saying less retimers are necessary at the end of the day in the back end
isn't overly impactful for someone like Astera Labs because that's not really the way that they sell their
products. Is that the correct understanding of the landscape or is there a negative content story, so to
speak, for Astera Labs as we do shift over to GB200 moving forward into next year?

Another takeaway is that everything that Jensen said at GTC pushed out the AMD accelerator
opportunity, coming from the perspective of the fact that it would seem that NVIDIA is the undisputed
training leader and that that training portion of this AI investment cycle has some more legs, and the
inferencing will really start to play a bigger role, maybe a little bit later than everyone had anticipated,
at least in meaningful fashion. How are you thinking about it, where AMD for MI300 is really going to
be, by and large, more of an inferencing play than a training play and how might they start playing a
bigger role in the broader accelerator spend bucket?

Specialist:
Where MI300X is, it's definitely winning more in inferencing right now. The biggest issue with AMD in
general is that their ROCm software suite, as you mentioned, is still way, way too immature for most
enterprises to be able to go to use. The only way you're going to really see enterprise adoption in the
current state of AMD MI300X is through some managed team that's going to do this on behalf of the
enterprise customers, someone that's well-skilled. There's two companies that are going to come to
mind. TensorWave, they're out there touting that they're MI300X-only and they're there to support
enterprises and managing on behalf of a customer. Another company that's going to be doing that is
Penguin Computing. Penguin is a huge provider to Meta, and they're well-known for being able to
support MI300X as well. They got Mark Papermaster on their board. Mark is the CTO over at AMD.

I don't see the ROCm software suite really coming up to maturity within the next two years. Yet, with
that said, if you're just using this for inferencing and you do have to manage the companies that can do
some managed loads for that, then inferencing is a much easier way to go. Why is that, because model
training also is going to needed for much larger clusters. To date, I have not read anything where AMD
has been able to show large, large clusters being used together. That's the only way you use training.
Training needs lots of clusters. To give you an idea here, for H100s, they have probably more H100s than
anyone on earth with 600,000 of them, but I think the cluster capacity currently on H100s is 30,000, and
this goes back to your retimer issue, is that when you start to physically get too many GPUs, and sorry,
I'm jumping between AMD back to NVIDIA, is the physical limitation of space, I mean, just distance.

Let's say, 8-16 GPUs of H100s or even, let's say, we'll go with Blackwells. If you're going to get eight
Blackwells into a rack, you can't get 32 into a rack. That's just too much, too dense. I think 25 square feet
per rack per cabin, that's typically how you'd square that out in the data centre floor. Do the math on
how do you get to 30,000 GPUs. What is the actual distance at going 25 square feet per eight GPUs? I

Private and confidential

4

Data Centre Space 每 Nvidia & Astera Labs 每 Senior Executive, AI Strategy for Cloud Venture at Oracle Corp
每 30 July 2024

can't do that math for you right here, but you can get your mindset that that really quickly gets very far
away. If we're really trying to get cluster communication to be sub-two microseconds, you start having a
problem with signal attenuation and all that stuff when it gets too far away. To your part, where do these
come in? Front of the house instead of back of the house where you need to connect in all those GPUs
that way, but the remainder of connecting that to the rest of your network, that's so important as well
because they're not going to live in a vacuum, especially if you've got workloads that need to do things
outside of just doing that large cluster for training, inferencing and/or working in part of some
connection with your ERP systems and other enterprise workloads. You now need to be communicating
back and forth between those.

Analyst:
Doing it via copper instead of optical is more of the issue, where doing some of that back-end intra-
and inter-data centre connection let the data travel through that pretty wide fabric of clusters, and is
where NVIDIA is thinking about shifting things a little to maybe save some costs. I'd be right to think
that will impact someone like a Marvell and a Broadcom that have data centre.

Specialist:
Realise that there is still a future for CPU inferencing as well as GPU inferencing. We're actually seeing
that being done today. Let's not rule out CPUs. There will be a future growth in AI inferencing with CPUs,
not just GPUs.

Analyst:
I'm aware Oracle is pretty closely aligned with someone like an Ampere that's doing single-threaded
performance. That's going to be driving a lot of that. Are there specific workloads that the CPU
inferencing is best-equipped for, where you would want to go that route instead of GPU inferencing?
How will that opportunity play out on the inferencing side of things? Will it be driven by workload or
by what a customer-specific strategy is? How does that CPU inferencing opportunity expand over
time? What are the key drivers underneath that?

Specialist:
I think the complexity of the workload. If you start getting into some really higher math, you're not
doing that on a CPU. Actually, and I don't think this has actually been architected about this way. If you
familiar with the term mixture of experts, instead of using one very large foundational model, think of
ChatGPT-4o at 1.8 trillion parameters with one big, big massive model, instead think of 64 smaller
models, there's a more specialised training in each of those 64 models and then putting a router in front
of it. Based on your prompt, we then choose between 2-4 of the 64 models that are now much smaller
instead of going after one big, big large framework, I have all these in small balls. Together, those small
balls almost add up to the same size as the one big one, but now I'm not moving them all at the same
time. That's called a mixture of experts foundational model. Databricks has a DBRX. There are others out
there like Mixtral. They have (inaudible) mixture of experts.

This is an up-and-coming theme on how we're going to start really trying to do enterprise-grade
computing. When I say enterprise-grade AI, I don't really care about jokes of the old testament. I want
very specific proprietary data for this part of my business to do this job. You have individual specialised
AI that is going to be smaller. Why is smaller important? Lower latency, less tokens, less cost. If I don't
have to run the whole big model, I can now run these smaller models. I'm going and spending a lot of
time in this for a reason. To switch over for a second back to your question, you put in your prompt, and
based on the type of queries that are being done, you then could route that to either a CPU or a GPU based
on the complexity of the workload. That's where I ultimately see where that might go, where we'll
continue to have more use of a CPU for smaller-style workloads that can handle it. If it's too big for it, of
course, you're then going into a larger GPU style because you can easily paralyse that, where, as you're

Private and confidential

5

Data Centre Space 每 Nvidia & Astera Labs 每 Senior Executive, AI Strategy for Cloud Venture at Oracle Corp
每 30 July 2024

aware, you can't with a CPU. That's going to be workload-dependent.

Analyst:
How big of an issue is asset utilisation for those smaller models to the extent that they might sit more
idle than that larger single foundation model because more prompts might go into it, whereas
specialised prompts will go to the smaller models? Is there an issue where inference deployment is
sitting more idle than a typical large foundational model? How does that get worked through over
time? Presumably, use cases will proliferate, and that will help it a little, but I imagine it is a bit of a
headache in the early days at the very least.

Specialist:
It's definitely a headache in the early days, but as you start to track data on usage trends, that's where
we start using our own business intelligence, our analytics on what are the proper way to configure this
up. Ultimately, you're going to be seeing a lot more smaller edge facilities for inferencing instead of
these large server farms just for training. The same way we've heard about edge for 5G, now you have
other reasons why you want inferencing in smaller, call it, lights-out facilities that are more modular.
Have you ever heard of a company called Vapor IO?

Analyst:
Yes.

Specialist:
That's probably the epitome of edge inferencing opportunities. Put them on cell towers everywhere
instead of putting in just regional facilities, which are more hyperscalers are doing today, but those are
larger and centralised. Then we have Azure Stack,  AWS Outposts. We have these Dedicated Region
Cloud@Customers that can be small 14-rack nodes that can go anywhere. I think that's going to be the
total future where we're seeing future builds is not just going to be in massive because we hear all of the
worries and the doom and gloom about, "We're going to run out of power with all these 500MW new
facilities or gigawatt facilities." We can talk to that now. There is some alternative power out there, go
for it, but just as much as that's going to continue to grow, we're going to see a proliferation of 2-5MW
edge facilities everywhere.

Analyst:
Do you believe we're far enough along in the training build-out? You mentioned if you have a 30,000
cluster, you're probably looking at 90,000-100,000 square feet of data centre space that's going to be
required for those things, but are we at a point yet where the actual clean room space, that's what we
call it for semiconductor fabs, the actual data centre footprint isn't going to be as much of a bottleneck
because we're starting to shift increasingly to some of these smaller and more proliferate edge points
that require less of a build-out at the end of the day? You probably saw Elon Musk building these tiny
little rack spaces in trucks, so it seems like people are getting pretty nimble about it as it relates to
finding the data centre space that they need.

Specialist:
We're still a ways out, and a big problem still even with smaller facilities is getting land leases in place.
Actually, real estate is still a big issue there. Can you roll these out, especially because they're
prefabricated modular little projects? I don't think you're going to see as much with these trucks that
Elon is doing. Elon is pushing the edge on a lot of different things, but I don't think that's going to be
very common. We have something called a roving edge, but other companies, plenty of them are out
there with just, call it, a megawatt modular that can come out, think of a mobile home factory. Right
here in Denver, there's a company, RK Mission Critical that does them for Microsoft and for Vantage.
There are plenty of companies around the country that are popping those out, and I see that as a fast way

Private and confidential

6

Data Centre Space 每 Nvidia & Astera Labs 每 Senior Executive, AI Strategy for Cloud Venture at Oracle Corp
每 30 July 2024

to go to market with small, completely enclosed, you're not worrying about your supply chain because
everything is right inside of those units and they're deployable very quickly. That is the future, but I
would say we're still a couple of years away from that.

Now all those enterprises are not looking to go build their own models. Let's say, Llama 3.1 is the last
model that drops and then there's a moratorium. For the next five years, we still have enough with the
models that are out there today to keep us moving, but that's not reality. Reality is we have flywheel
where all these other companies, which is driving me crazy, I cannot believe it, they're blowing through
so much money to build and train new models. It's not stopping. It's only continuing. From the models
that we have now, we have plenty to inference over the next five years, even though we're going to see
more and more new models in this arms race come out every week, every month, and it's starting to
blow my mind. I don't know where we're going to come up with all that power.

At one point, you're going to start to see why a lot of companies are driving these new purpose-built
massive data centres and/or their smaller data centres in places like Texas where we can start seeing
things from Crusoe.ai. There's another company, Bilateral Energy, that has three sites in San Antonio.
They're going to be good for a gigawatt each. All of which is going to be carbon neutral using abandoned
oilfields to extract just enough oil to get a generator running, so not to really pump oil, but to just run
data centres. I think you're going to see a big shift towards a lot of these behind them, either purpose-
built data centres being run by some type of carbon-neutral power in situ, not even possibly connected
back to the grid at all.

Analyst:
The other bottleneck is the fact that the NVL72 version of GB200 is going to be liquid-cooled and it
seems that capacity for guys like Verint and some of the other liquid cooling providers is pretty
constrained, and so there's a possibility that hyperscaler cloud customers in particular would be
willing to wait 90 days or whatever it would need, to be able to get the liquid cooling capacity back
where it needs to be, as opposed to buying air-cooled solutions, because those types of customers want
to have the leading-edge types of GPUs at the end of the day. How have you been navigating that as
liquid cooling, investing fast enough, so to speak, until I keep up with what is going to be necessary for
when we do shift over to more of these NVL72-type GPUs that do require the liquid cooling
infrastructure?

Specialist:
There's a good 25 companies right now in that space that are all coming into either in-rack liquid
cooling, I know where you're going to go is chip, but I just want to make sure that we're clear on the
different types of liquid cooling that's out there. You have hybrid cooling available. Everyone is shifting
over. I don't really see a real need to go out of your way to do a lot of air-cooled anything for new data
centre development anyway. I was not familiar with what you were talking about with that cooling issue
of being delayed. You look at Schneider, Vertiv, LiquidStack, they all have some plans on how they're
going to do direct-to-chip cooling. LiquidStack is probably one of the largest that people think of right
there. For that, I'm a little confused as to why people are concerned that there's going to be a delay.

Analyst:
It only just started coming up. It was said by a few of the private GPU cloud guys, and I think that they
have a large deployment of GPUs and so maybe it's a little bit idiosyncratic, so to speak, where they vs
the industry might face some delivery issues vs their expectations, but more broadly, it feels like
things are chugging along and that liquid cooling isn't this broad-based issue, so that's also good to
hear. What are your thoughts?

Specialist:

Private and confidential

7

Data Centre Space 每 Nvidia & Astera Labs 每 Senior Executive, AI Strategy for Cloud Venture at Oracle Corp
每 30 July 2024

Chilldyne is probably a huge pioneer  these days. Peter Gross is part of that company. Peter Gross is a
legend. Last thing he was in Bloom Energy. The part of that, he is an OG of data centre design, did a lot of
work with Switch in Vegas early on. Switch, by the way, is probably one of the most forward-thinking
data centre operators on Planet Earth. Rob Roy is incredible with all of his patents. For that reason, I
believe that they can architect around any of those delays that you talked about. I know you want to
shift, but really quick, remember that multi-tenant data centre operators are also digging deep into
doing their own cooling without needing to just go to big names. Flexential, Aligned Data Centers,
they're starting to really push the edge on saying how they're going to be able to handle all liquid going
forward, even though they'll still have some air cooling, but now you're seeing data centre operators
pioneering this concept. It's just part of the DNA of their company. That's going to take off.

Analyst:
In today's world with these HGX platforms, it's just eight GPUs, and we're shifting over to a world
where NVL72 can have orders of magnitude more than that. Can you have less retimers on a per GPU
ratio? My understanding is no because it's held by the PCIe generation speeds. If you're at 128 [sic],
even if you have way more GPUs per CPU, you're still going to need the same amount of retimers
because it's mostly just an issue of, once the data travels far enough off of the GPU, you need to put a
retimer to retransmit the data and avoid signal integrity issues. It's hard to find efficiencies even if the
GPU-to-CPU ratio is improving. Does that make sense to you where you're still going to need maybe a
1:1 retimer to GPU or slightly less than that and that you can't use less retimers just because of that
distance factor, which is a pretty rigid limitation to keeping the data signal integrity where it needs to
be?

Specialist:
That's about the extent of how I know that. It's just that distance issue and what you just mentioned.
They're trying to block NVIDIA with this new Ultra. UltraLink was started last summer.

Analyst:
How would you rate the progress there, because NVIDIA is innovating pretty quickly, and I'm sure that
they're going to have new announcements that move the goalposts even farther back vs what
UltraLink [sic] is trying to bridge the gap upon? How is that going because I know that it helps being
this open consortium and having a lot of different companies working on it in tandem? I imagine that
they'll bridge the gap, but how are you thinking about timing-wise? When would you expect it to get
more competitive, that the big cloud guys would start considering using it more as an alternative?

Specialist:
AWS has their own thing called Elastic Fabric Adapter or EFA. Google is going down the road of not even
using Ethernet at all with this Aquila fabric, but those are outliers. To set aside AWS and Google for a
second and realise everyone else is moving really quickly. There's eight different working groups, and
they're going to have v1 of UEC out, they say, by Q3 2024. That is really fast. I believe this could have a
huge impact on everyone to say, "Look, we're not just going to buy into InfiniBand with NVIDIA. We
really need to be able to go another way," and the reason for it is they realised this tail latency of end-
points is the critical crux that they need to solve for, and they're going to do it with UEC.

Analyst:
Does the UEC success benefit everything that Broadcom is doing from a PCIe perspective over in Astera
Labs because Astera is so closely aligned with someone like NVIDIA, and so the success of NVIDIA is
something that Astera will ride the curtails, and if Broadcom and UEC can crack the code, that would
actually be the bigger thing to focus on that would be a bit more negative over the medium-to-longer
term for someone like Astera Labs?

Private and confidential

8

Data Centre Space 每 Nvidia & Astera Labs 每 Senior Executive, AI Strategy for Cloud Venture at Oracle Corp
每 30 July 2024

Specialist:
I would say, yes, and I believe as much as I don't like Broadcom and the way they do their business
model with buying, what they did with VMware, Broadcom has got a huge opportunity right now. If that
goes away, I think it will, your point is well-taken that Astera is going to be just on NVIDIA, but there's
all this other opportunity for everyone else to say, "We're not going to buy into, that's the only way to
go." I think that's great for the entire industry. I'm not saying one or the other. NVIDIA is not going
anywhere, but the fact that these other companies are architecting an alternative Ethernet or a lower-
cost solution is actually better for the industry.

Analyst:
Share shift would start to manifest probably in 2026. Is that the right way to think about it, if things
keep plugging away the way that they are?

Specialist:
Sure, that sounds a good number, but let's call that two years from now. Yes, 2-3, because not enough
enterprises are going to jump in in the beginning. Even though we see that it's wildly popular, it's still
going to take a good 2-5 years for enterprise adoption. Look back at VMware in the beginning, everyone
now says, "Of course, you're going to use VM," but in the early days, it took a couple of years for that
thing to really catch tailwinds.

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

9



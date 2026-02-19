AI Infrastructure & Networking Space &
Nvidia 每 Senior Architect at Microsoft Corp

CLIENT-LED

65d0d6538a8911da05d11de9b49cc840996c80c0

24 October 2025

Specialist Background

> Over 10 years' experience in the semiconductor space, focusing on data centres, engineering,

networking, capacity and demand management, site planning and AI strategy

> Knowledgeable on the shifting expenditure mix of merchant GPUs vs customer ASICs
(application-specific integrated circuits) and Google's TPUs (tensor processing units)

> Well-versed in the emerging open standards challenging Nvidia's NVLink for scale-up networking

such as UALink and ESUN (Ethernet Scale-up Networking)

> Well-placed to discuss the shift in demand from training to inferencing, the development timelines
for agentic AI and inferencing at the edge, as well as the security implications of new AI API
(application programming interface) ecosystems

Contents

5

6

I know Anthropic had been using Trainium in the past, but that Trainium chip was pretty much
designed for Anthropic, so it feels a little bit different and more flexible and dynamic in nature
as it relates to TPUs [tensor processuing units] being able to tap into this. Do you think this is a
corner case? Do you think we're going to hear a lot more of this ASICs [application-specific
integration circuits] for externally served workloads over time?

An important part you mentioned was that most of your customers are going to ultimately want
general-purpose GPUs for training and inferencing. I've observed that a lot of people are
focused on this inferencing crossover. If we unpack the differences in what you expect the mix
of spend to be based on the advantages of the various processing capabilities across TPU, GPU,
ASIC and FPGA [field-programmable gate array] for both training and inference, on the
training side, it sounds that 80-90% is going to be these general-purpose third-party
merchant GPUs. Then, there's going to be another 10-20% bucket that might have a little bit of
everything in it. Training is so dominated by these large LLMs [large language models] and
Anthropic is going to go with TPU increasingly and already has Trainium. Google is doing its
entire Gemini on TPU as well. OpenAI has a deal with Avago that's going to be custom ASIC as
well. I can't tell if it's training or inference. Do you think that 80-90% realistic? Do you think it
may be a little bit lower than that because the large LLM makers are going to be driving the
lion's share of overall training workloads?

AI Infrastructure & Networking Space & Nvidia 每 Senior Architect at Microsoft Corp 每 24 October 2025

On the inferencing side, can GPUs represent 50% of the wallet share ultimately? Do you think
that there are so many different types of inferencing workloads, such as physical AI, agentic AI,
vision processing, IoT [Internet of Things], the edge that there's just a bevy of more optionality
as it relates to what type of processing capability you ultimately need? Do you think that,
because of that, GPUs will fall to something less than half of the market and the balance is made
up by all those other options that you laid out?

Has availability at the GB200 level greatly improved as of yet? Are there still some bring-up
headaches that exist? How has that driven compute capacity demand? Would you say that we've
seen some pretty healthy increases? Have there been any supply constraints limiting that?

Within that demand construct, I feel like two years ago, training to inference was probably
90/10 and more lately, it may be closer to 2:3, 1:3 or 60/40. Would you say that inferencing as a
percentage of the demand has edged up further? Would you say inference demand has been
stronger than even training and so that mix has further grown? Are we at a static point right
now until these agentic AI applications get stood up over the next couple of years? Is 60/40 the
right mix for training vs inference currently?

What is that swap driven by at the end of the day? I'm sure that it goes back to the retraining
elements, but how do you see the renaissance of training coming into form?

Would you say the industry is probably going to evolve over the longer term in a direction
where the LLM asset quality or freshness depreciates over a handful of years, so there will be
this big spike in training to get it back to modern times? Then you'll see the next wave of
inferencing on better and better data, then inferencing will come back, and you'll have to keep
doing that. Is that the cycle that I should anticipate to continue?

On the inferencing side of things, a way to break it down is inferencing at the data centre vs
inferencing at the edge. I would think that we're still pretty dominated by inferencing at the
data centre. I think it's the lion's share of overall inferencing workloads. Do you agree with
that? As you think about some of these agentic and physical and other types of edge-type
inferencing workloads that are being discussed across the industry, how do you think about
that cutting over time? Is that something that really starts coming into the fold in meaningful
mixed fashion in '27 or earlier? How would you think about that development?

On the topic of security, you've gotten the increased presence of these AI-native web browsers
from Perplexity and Atlas coming out from OpenAI. I think the ultimate goals of the LLMs is to
create an API [application programming interface] ecosystem in which they can allow
enterprises to come in and build out their own agents. Security is going to be the big factor
there. It feels like we might be going back to the Wild West of the initial internet build-out. I've
heard folks say like, "The new Norton is going to come back to town as it relates to security of
data and security of utilising those types of browsers or API ecosystems." How are you thinking
about what that eventual API ecosystem might look like? It does seem like that's the ultimate
goal of the LLM model makers.

Private and confidential

6

7

7

8

8

9

9

2

AI Infrastructure & Networking Space & Nvidia 每 Senior Architect at Microsoft Corp 每 24 October 2025

Let's shift to some of the innovations around inferencing. I believe Rubin CPX is an interesting
one for data centre inferencing as it relates to how cumbersome the prefill and how heavy the
KV cache ultimately gets. From the philosophy that Nvidia is starting to get more innovative at
the product line, releasing specific SKUs that are going to be optimised for specific workloads
or even stages within a broader workload, how does that make you feel about AMD? I think
AMD's entire pitch was to have certain advantages in inferencing, but Rubin CPX seems to have
reset the bar a little bit there. How much might that change your view on utilising AMD vs
Nvidia for inferencing prep (ph) at the very least for inferencing when it's centralising back to
the data centre?

Is there any area where you wish AMD were a little bit better at? I'm sure ROCm is one area of
that. It's made good momentum. We'll give it a B, B+. What would get it into A-, A+ territory?

How is the evolution of priorities as it relates to finding alternatives from NVLink on a scale-up
networking standpoint? What does that form factor definition look like? How has that evolved?

Based on how you described it, should I view UALink and ESUN as somewhat complementary,
where ESUN will be the protocol on which the actual switch chip runs, but then UALink will be
an interconnect protocol on top of that, so it would be UALink over ESUN? Has the market
gotten it right that silicon is no longer required? What form should I expect UALink to come
into the market when it does?

Would you expect two disparate switch fabric chips at the end of the day? Would I be right to
think that it will be IP over a chiplet? What's the backbone? Is it more UALink because that's the
highway? Is it more ESUN? Astera Labs has been working on taping out silicon. The UALink chip
that it's going to do in the first place is over PCIe [Peripheral Component Interonnect Express],
which I can't tell if that fits into this construct or if it needs to be over an Ethernet-based
protocol. I'm trying to figure out what the two different hardware roadmaps might look like
and if one is less of a hardware roadmap and more of an IP or protocol roadmap?

Do you have familiarity with aiXscale Photonics? Do you consider the team to be a savvy one?

I noticed that Ayar Labs is doing a webinar on CPO [co-packaged optics] with Alchip and Astera
Labs. I was scratching my head on why Astera was there and then they announced the
acquisition. I might have been ahead of the ball on that one. How do you see Ayar Labs and
Astera Labs' potential strategies intertwining?

Can you help me understand how Ayar Labs is competing with Nvidia and Broadcom's CPO
efforts and where they differentiate themselves?

OpenAI announced 26-27GW of capacity that it's going to put in place by the early 2030s
timeframe. That's more than 10x the size of the 2GW of existing capacity. It compares to what I
believe to be around 1GW getting deployed, whether it's Hyperion or Project Rainier, taking at
least one year. All that together, how do you think about the possibility to deploy at scale and
pace that OpenAI is saying, considering land and power constraints? Is there a more reasonable
scale that you think they could hypothetically get to by 2030?

Private and confidential

10

10

11

12

12

13

13

14

14

3

AI Infrastructure & Networking Space & Nvidia 每 Senior Architect at Microsoft Corp 每 24 October 2025

Do you think Broadcom's ASIC design momentum vs Marvell is purely related to the fact that
it'll actually do part of the front-end design for I/O [input/output] and memory guys, whereas
Marvell is doing a lot more of the back end and the front end is where some of these software
companies need help because they just don't have hardware know-how? If I boiled it down to
one thing, is that the main driver in your mind?

15

Private and confidential

4

AI Infrastructure & Networking Space & Nvidia 每 Senior Architect at Microsoft Corp 每 24 October 2025

AI Infrastructure & Networking Space &
Nvidia 每 Senior Architect at Microsoft Corp

Transcription begins

Analyst:
I work in equity research. I cover semiconductor stocks, mostly the players that are exposed to the AI
secular trends such as Nvidia, AMD, Astera Labs, Broadcom, Marvell and Arm. As a starting point, I'd be
curious how you're thinking about this ASICs [application-specific integration circuits] for external
workloads dynamic and the extent to which TPUs [tensor processuing units] maybe have tapped into
something. The Anthropic deal came out, I think, yesterday, talking about deploying one million TPUs.
It's going to be USD 10bn-plus worth of total capital deployment, a gigawatt worth of capacity.
Historically, the way I've thought about it is that it works really well for internal workloads, but that
once you get to external, it's a little bit more difficult to tune it to customer-specific and more dynamic
workloads that you don't have full sight of where those are going, but this feels like a bit of a change
statement.

I know Anthropic had been using Trainium in the past, but that Trainium chip was pretty much
designed for Anthropic, so it feels a little bit different and more flexible and dynamic in nature as it
relates to TPUs [tensor processuing units] being able to tap into this. Do you think this is a corner
case? Do you think we're going to hear a lot more of this ASICs [application-specific integration
circuits] for externally served workloads over time?

Specialist:
First of all, you did your research. I think you hit the nail on the head. When it comes down to the whole
custom ASICs for external workloads, really, what it comes down to ASICs take quite a lot of time if it's a
TPU, if it's Trainium, if it's Maia, things like that, to design, to actually mass produce, to prototype out.
You really need to design any custom ASICs or FPGAs for that matter for this specific model and then
really understand what the intent of the model is. You do also have compatibility issues, there's a tooling
gap out there in terms of developers and the ecosystems that they use and compilers and frameworks
and all that fun stuff. I will say that as a hyperscaler or any business in general, once you make an
investment in any ASICs, it is highly customised. As a result of that, you risk fragmentation. You can
only use it for a certain segment of your customers. Most of our customers want general-purpose GPUs.
They want something like that for any degree of training and referencing. The sweet spot with FPGAs is
that they allow you to use different modules as long as you know how to programme on them in a more
generic sense and reduce your cost.

Now, the whole TPU vs (audio distorts) and Google cloud stuff, that didn't surprise me, a gigawatt of
compute capacity, that's quite a lot, but those are really just geared towards Claude, is when it comes
down to Claude 3 and future generations. When it comes down to it, it could have been Google that
decided to make an investment in TPU, specifically for Claude. I think that custom ASICs are good.

Custom silicon, it does have a lot of performance value, it has energy value, but you're tied to the model,
and you're really tied to what you're doing there. Then not only that, custom ASICs can be very
expensive to update. Yes, I do think this is more of a corner case. I would say that for specific frontier
models like Claude and GPT and some of the Gemini out there, yes, custom ASICs are great.

Private and confidential

5

AI Infrastructure & Networking Space & Nvidia 每 Senior Architect at Microsoft Corp 每 24 October 2025

Analyst:
An important part you mentioned was that most of your customers are going to ultimately want
general-purpose GPUs for training and inferencing. I've observed that a lot of people are focused on
this inferencing crossover. If we unpack the differences in what you expect the mix of spend to be
based on the advantages of the various processing capabilities across TPU, GPU, ASIC and FPGA [field-
programmable gate array] for both training and inference, on the training side, it sounds that 80-90%
is going to be these general-purpose third-party merchant GPUs. Then, there's going to be another
10-20% bucket that might have a little bit of everything in it. Training is so dominated by these large
LLMs [large language models] and Anthropic is going to go with TPU increasingly and already has
Trainium. Google is doing its entire Gemini on TPU as well. OpenAI has a deal with Avago that's going
to be custom ASIC as well. I can't tell if it's training or inference. Do you think that 80-90% realistic?
Do you think it may be a little bit lower than that because the large LLM makers are going to be driving
the lion's share of overall training workloads?

Specialist:
Yes. Those frontier models, those large LLM models, they're driving most of the custom ASICs and TPUs
and things like that. When it comes down to it, GPUs still have that explosive growth because they are
more general purpose. They can be used for training, they can be used for inferencing. They are still
dominant at hyperscalers for AI. The amortisation schedule on those is 12-24 months, so it's really easy
to buy those for USD 41,000 or USD 51,000 and then write them off over a couple of years and then see
the revenue, the TCO from them. TPUs, honestly, super rapid growth, but they are very specific, and
TPUs work best with more math-driven models with financial transactions, with healthcare where
you're doing more tensor-based workloads that don't require a whole lot of vectorisation. Google
Anthropic, custom ASICs for that, they're very efficient for large models where you've already
normalised the way that you approach vectorisation from a math standpoint. ASICs, I would say, have
been growing pretty strong. They're used more so for inferencing and for networking. OpenAI, we use
them with them. AWS uses them. Meta uses them for a lot of internal workloads too. CPU growth,
honestly, has been pretty flat. I would say it's actually been plateauing, and it's funny because Intel,
everyone is looking like, "Get your stuff together, Intel, you could be doing so much more."

I know the US government made a big investment in them as well. There's a lot of growth with Arm-
based CPUs like Cobalt and Graviton, that's been gaining share, but that's where the growth in that
market has been. VPUs, a lot of the stuff was Sora, those have seen a lot of growth, especially for like
edge AI and vision processing. That's been on the uptick. Then the neural processing, the NPUs, those
really what we've been seeing a lot more edge compute, and so there's been a growth in NPUs for AI-
embedded PCs, for smartphones but for also Azure Local and for growth at the edge.

Analyst:
On the inferencing side, can GPUs represent 50% of the wallet share ultimately? Do you think that
there are so many different types of inferencing workloads, such as physical AI, agentic AI, vision
processing, IoT [Internet of Things], the edge that there's just a bevy of more optionality as it relates
to what type of processing capability you ultimately need? Do you think that, because of that, GPUs will
fall to something less than half of the market and the balance is made up by all those other options that
you laid out?

Specialist:
I think Grand View Research did a study saying that. Right now, it's 52.4% of the processing semis that
are out there are GPUs. Right now, that's what they're seeing, and it is the largest compute segment. By
2030, that's going to start to falter and where you're going to move into those more segmented semis
and move into something that are more bespoke. I'm starting to see it right now, probably about three or
four months ago with customers where they're complaining based upon cost is what it comes down to.

Private and confidential

6

AI Infrastructure & Networking Space & Nvidia 每 Senior Architect at Microsoft Corp 每 24 October 2025

You get the big benefits of CUDA, you get the benefits of ROCm for GPUs, TensorRT, PyTorch, things like
that. GPUs provide a lot of flexibility, but they come at the cost of power consumption and cost overall.

Some of them are looking at like, "Hey, let's just move this over from Nvidia GPUs," to "What can we do
to move it over to FPGA? What would that take for it to move it over to a TPU?" Yes, you're going to
spend a little money from a labour standpoint to convert it to support other hardware. That being said, if
you're going to inference for 3-4 years, you're definitely going to save money on that. I would say in the
future going forward, we're going to continue definitely using GPUs for general purpose inferencing,
especially for those dynamic huge LLMs and multi-model environments, but you're going to see a
growth in ASICs, you're going to see a growth in TPUs and share. Probably by 2030, they're going to have
the wallet share of between, I'd say, 50-60%, and edge inferencing. Honestly, a lot of the companies
that I'm working with right now that are doing that, they're really moving towards NPUs and VPUs
because it's so expensive to send. From a business cost standpoint, it's so expensive to send that data all
the way back to a cloud data centre just to do inferencing vs, "Hey, can't we just get a powerful device
with the edge and do the inferencing there?"

Analyst:
In terms of demand dynamics over the last 3-4 months, when we entered the 2025 calendar year, it was
all about GB200 delays, the fact that a lot of people can optimise their CUDA [Compute Unified Device
Architecture] coding to a Hopper and you have to make some changes to get that optimised for
Blackwell. Then, from a packaging scheme, going from CoWoS-S [Chip-on-Wafer-on-Substrate with
Silicon Interposer] to CoWoS-L [CoWoS with Local Silicon Interonnect] also had a little bit of headaches.

Has availability at the GB200 level greatly improved as of yet? Are there still some bring-up headaches
that exist? How has that driven compute capacity demand? Would you say that we've seen some pretty
healthy increases? Have there been any supply constraints limiting that?

Specialist:
I'll choose my words carefully here. I would say it's definitely improved from an availability standpoint
from mid-to-late 2025. The issues that were there, as you hit upon towards, really, supply chain issues,
design issues, I would say TSMC had some production issues as well, and then Nvidia continue to just
keep making little architectural adjustments, which required firmware updates and us to keep going
back and having to update that. I would say we've definitely normalised the demand, but when it comes
down to capacity, there's definitely a lot more capacity out there between us and Google and Meta and
some of the others.

When it comes down to liquid cooling, it's just mandatory. Liquid cooling takes some time to stand up.
The co-package optics and the fibre density, those are also super critical for GB200s. When you look at
Rubin, Rubin Ultra, Feynman, Feynman Ultra, those roadmaps, they're going to definitely require a lot
more power at the rack and definitely require liquid cooling, but now any time you deploy GB200s, you
have to plan for any power envelope modelling, rack-level thermal budgets. Yes, it's pushing and
customers are adopting them more, but it's a lot more time to stand up those, the GB200s.

Analyst:
Within that demand construct, I feel like two years ago, training to inference was probably 90/10 and
more lately, it may be closer to 2:3, 1:3 or 60/40. Would you say that inferencing as a percentage of the
demand has edged up further? Would you say inference demand has been stronger than even training
and so that mix has further grown? Are we at a static point right now until these agentic AI
applications get stood up over the next couple of years? Is 60/40 the right mix for training vs inference
currently?

Private and confidential

7

AI Infrastructure & Networking Space & Nvidia 每 Senior Architect at Microsoft Corp 每 24 October 2025

Specialist:
I would say they're always in the 40/60 is that realm between training and inferencing because with new
frameworks, with improvements with CUDA, with improvements with ROCm, with especially agentic
frameworks where that requires a lot more inferencing of having like Autogen, which is causing
different frameworks to call other frameworks and do RAG and do some antikernel in real time. That's
all inferencing workload. That really pushes the needle back towards more inferencing.

That being said, it can also cause those models to ask to retrain themselves and train on other datasets
too. It goes back and forth. I would say right now, the bulk of it is inferencing. I think over the next
couple of years, you're going to see inferencing take more of the share just because no one is right now
in this economic climate making big financial bets on training, except for the big frontier model players
like Anthropic, OpenAI and Google and stuff like that too. I think it's going to be inferencing for probably
the next 1.5 years.

Analyst:
What is that swap driven by at the end of the day? I'm sure that it goes back to the retraining elements,
but how do you see the renaissance of training coming into form?

Specialist:
Let's see how much of that I can talk about. I would say that most agentic AI systems require definitely
more inferencing, but the datasets are getting bigger and bigger. The datasets are also getting, how to
say this, very dated in terms of timestamps when they were acquired, and so as a result of that, because
of the aggregation of data getting bigger and bigger and discrepancies between the datasets, the only
way you can really resolve that is to retrain models. Inferencing, if you've got six different agents that go
out and come up with four different responses to a prompt, then it really begs the question, from a
transparency standpoint, which ones of those do I trust? How can I get them to plan and act and reason
behind the scenes to do fact-checking.

Ultimately, you get to a tipping point where the only real option is to create a separate standalone model
from different models to retrain and have that do a short-term retraining of the text, of the images, of
the audio and then have those agents basically pick it apart. You're getting to a point where AI needs to
reinvent itself because models have been trained on different datasets and just the scope of what they've
been trained on. There are disparate natures of the dataset. You're going to see in 1.5 years the need for
dynamic generation of new models and then training of them on a much shorter purpose, which is going
to cause a flush right back to GPUs.

Analyst:
Would you say the industry is probably going to evolve over the longer term in a direction where the
LLM asset quality or freshness depreciates over a handful of years, so there will be this big spike in
training to get it back to modern times? Then you'll see the next wave of inferencing on better and
better data, then inferencing will come back, and you'll have to keep doing that. Is that the cycle that I
should anticipate to continue?

Specialist:
It comes down to the endemic nature of data. Data is always timestamped and so how do you continue to
update it so that you're not ebbing and flowing back? Look at ChatGPT-3, it was September 2022, and if
you ever try to ask questions of GPT-3 nowadays, the answers are so dated and so incorrect that you lean
like, "Why did anyone ever use this? It was only 2.5 years ago." Yes, we're trying to solve that. How do
we do this in such a way that we could do continuous retraining and continuous inferencing for that? I
think, ultimately, there's going to be some type of custom semi that comes out that addresses that
because GPUs are just still too expensive to do inferencing on, but they're the only way that you can do

Private and confidential

8

AI Infrastructure & Networking Space & Nvidia 每 Senior Architect at Microsoft Corp 每 24 October 2025

training and retraining in a cost-effective manner. I don't know. We're noodling on that right now, but
yes, I would largely agree with that assertion.

Analyst:
It will be interesting to see if there's a breakthrough on that front because that would lead to probably
more durable optimisations if you didn't have to flip-flop so frequently.

On the inferencing side of things, a way to break it down is inferencing at the data centre vs
inferencing at the edge. I would think that we're still pretty dominated by inferencing at the data
centre. I think it's the lion's share of overall inferencing workloads. Do you agree with that? As you
think about some of these agentic and physical and other types of edge-type inferencing workloads
that are being discussed across the industry, how do you think about that cutting over time? Is that
something that really starts coming into the fold in meaningful mixed fashion in '27 or earlier? How
would you think about that development?

Specialist:
That's just what it comes down to is latency, privacy, local context, compliance and regulation. It's
definitely growing, and then IoT has a huge comeback, 5G, real-time analytics. IoT is finally hitting the
promise of a lot of what was pitched back in 2012 and 2014. A lot of those IoT devices have much more
complex compute on them. With 5G out there, you can do real-time analytics that provide you super-
low latency responses for retail systems, autonomous systems, industrial automation, things like that. I
would also say don't cut out compliance because data residency and autonomy and sovereignty, privacy
concerns, it just takes a little bit of data being leaked for someone to say like, "Hey, we're not sending
data across state lines anymore." Any time that you keep that data local, use smart camera, surveillance,
healthcare diagnostics local vs sending it to across the internet to cloud. It's definitely going to become a
lot more decentralised over the next 3-5 years.

Analyst:
On the topic of security, you've gotten the increased presence of these AI-native web browsers from
Perplexity and Atlas coming out from OpenAI. I think the ultimate goals of the LLMs is to create an API
[application programming interface] ecosystem in which they can allow enterprises to come in and
build out their own agents. Security is going to be the big factor there. It feels like we might be going
back to the Wild West of the initial internet build-out. I've heard folks say like, "The new Norton is
going to come back to town as it relates to security of data and security of utilising those types of
browsers or API ecosystems." How are you thinking about what that eventual API ecosystem might
look like? It does seem like that's the ultimate goal of the LLM model makers.

Specialist:
Atlas, Comet, Chrome for Gemini, they are putting an LLM directly in the browser. It's a really cool
experience and whatnot. It does make [it] a little bit tougher to code on, but the ability to summarise
pages, answer questions, use memory recall, that's the nature of the web. The web is always stateless,
but when you've got a web browser that's got LLMs embedded in it, you're actually bringing it and
making it staple so that you can use autonomous agents to do like ordering groceries or booking travel
and stuff like that. From a security standpoint, I would say I'm definitely much more bearish on that
from doing an AI-based web browser because you can directly intercept any direct injection attacks,
indirect injection prompt attacks or really limit AI agents from going out and changing the model to do
any model drift, and you can do it at the browser level.

I would also say, with an AI-based browser, you can get more granular with authenticated privileges too,
because they allow you to say like, "This is what the browser can do, this is what the user can do, this is
what an AI agent can do." You can prevent any hijacks for banking websites or work e-mail or internal

Private and confidential

9

AI Infrastructure & Networking Space & Nvidia 每 Senior Architect at Microsoft Corp 每 24 October 2025

systems at the browser level vs having to do any of those RBAC-based (ph) checks within the data centre.
Some of the things that scare me, though, are the whole sidebars and extensions that if you were to
create a fake AI sidebar and start compromising that at the browser level, as we put out browsers there,
especially with edge, make sure that we're provide extensibility for developers, but also keep security
guardrails in there to prevent exfiltration of data, backdoors, redirections, things like that, any social
engineering or phishing. They are somewhat unique risks, but at the same time, they definitely provide
you with some benefits from moving the model directly into the browser vs having to operate it in a data
centre. You definitely need some more compute power from an NPU on the host of the laptop or the
device, but at the same time, it provides a lot more autonomy for AI agents, and it lets you do a lot more
from an empowerment at the edge.

Analyst:
Let's shift to some of the innovations around inferencing. I believe Rubin CPX is an interesting one for
data centre inferencing as it relates to how cumbersome the prefill and how heavy the KV cache
ultimately gets. From the philosophy that Nvidia is starting to get more innovative at the product line,
releasing specific SKUs that are going to be optimised for specific workloads or even stages within a
broader workload, how does that make you feel about AMD? I think AMD's entire pitch was to have
certain advantages in inferencing, but Rubin CPX seems to have reset the bar a little bit there. How
much might that change your view on utilising AMD vs Nvidia for inferencing prep (ph) at the very
least for inferencing when it's centralising back to the data centre?

Specialist:
Jensen loves to get up on the stage and talk about how many workloads are inferenced on Nvidia chips,
but when it comes down to it, it's a cost thing at the end of the day. When you look at Rubin CPX, you
look at KV cache, it's really just a strategic escalation of their wanting to maintain dominance of AI
inferencing. I would say that impact is somewhat multifaceted because it does really raise the
performance bar. It does make it so that us, as hyperscalers, our attention is to ultra-long-context
workloads. It really does pressure AMD to accelerate their roadmap for more inference-optimised GPUs
and for AI accelerators. Rubin CPX is supposed to have, what, 3x faster attention processing. I think it's
8x of FLOPS per rack, which is just from a long-context inferencing, that is a new bar, that's a new
standard to do. From AMD's standpoint, the MI300X definitely has much more competitive from a
memory bandwidth standpoint for floating point operations and things like that. It's not, though,
optimised for one million token context. You're comparing Rubin CPX vs an MI300X, which if you look at
the 350X, the 450X and the specs for the 500X, they will definitely be able to compete directly with Rubin
CPX. Then if you bring in something like KV cache, it's definitely going to allow AMD to reuse those key
value pairs, accelerate token generation and whatnot.

I wouldn't count AMD out. I would say that Nvidia definitely did some good strategy. They looked at it
and said, "We're going to lose out in the long run on inferencing workloads. What can we do?" AMD is
now responding to that to make sure that they are going to have equivalent inferencing optimisations. I
would say AMD might lose wallet share in the short term, but once they come out, once the 450X really
hits it out there, just because their chips always have more high-bandwidth memory on it, that HBM4
and HBM3E that's been deployed, it's much more cost-efficient, and it's a much lower TCO for any of
those enterprise inference workloads. As long as cost is important to companies, AMD is going to
continue to thrive.

Analyst:
Is there any area where you wish AMD were a little bit better at? I'm sure ROCm is one area of that. It's
made good momentum. We'll give it a B, B+. What would get it into A-, A+ territory?

Specialist:

Private and confidential

10

AI Infrastructure & Networking Space & Nvidia 每 Senior Architect at Microsoft Corp 每 24 October 2025

You hit the nail on the head. The ROCm stack has been improving greatly. I would say a little bit better
support for PyTorch, TensorFlow and Hugging Face, that would be better in ROCm vs CUDA. I would say
it does take a little bit longer to onboard for inferencing workloads with AMD, not just for training and
then some of the debugging tools, the optimisation tools, just profiling and stuff like that for memory.
They're not as good as CUDA out there. Inferencing optimisation, too. They're training, the MI300X is
outstanding for training, outstanding from a memory standpoint. If you want to do any fine-tune
inferencing on it, you really need to do long-context inferencing, and that has higher latency. We wish
that they had better support for that, for those bigger tokens, anything that's over one million tokens is
what it comes down to. Then another technique, which is parameter-efficient tuning, LoRa and QLoRa
and stuff like that, just ROCm has not been good at supporting that.

I would say also having AMD's architecture is generally, it's general-purpose, and if they could build
capabilities that were more AI-specific, things like transformer, sparsity, KV caching, attention
acceleration, things like that. The AMD is outstanding at their ability to deliver at volume in terms of
competing with Nvidia, but it's just a little bit of what it comes down to is ROCm and just giving better
attention to some of the trends and patterns that are happening out there. Then the other thing, too, is
just we wish that they participated more in a little bit of the OpenAI infrastructure initiatives like Ultra
Ethernet. They said that they will come to the table on that. Definitely have a wish list with them, and
they take it all in stride and they say, like, "Yes, let's see what we can do to work towards that."

Analyst:
You brought up the point around AMD struggling with longer context, having a higher latency. I imagine
some of that might not just be ROCm, but also the scale networking element where NVLink is the de
facto standard. You bring up ESUN [Ethernet Scale-up Networking]. Can we talk about what the goals are
with ESUN? Historically, I felt like a lot of the memory semantics elements of Ethernet have just been
lacking, but it feels like ESUN is a little bit of a departure from that where at the end of the day you're
just looking for them to deliver a lower byte header. Then it seems they're saying like, "Don't waste your
time on anything related to memory semantics, load balancing and all that. We don't need it as long as
you can just let us use your ESUN on our existing switches. That's good enough," which is different than
what Ultra Accelerator Link has been attempting to do. It feels like they're trying to emulate some of the
memory semantics advantages that exist with NVLink. The UALink got announced around 12 months
ago, Scale-Up Ethernet a little bit after that, and now we're at ESUN.

How is the evolution of priorities as it relates to finding alternatives from NVLink on a scale-up
networking standpoint? What does that form factor definition look like? How has that evolved?

Specialist:
Now we're dabbling with a lot of different technologies now. When it comes to ESUN, it's efficient
streaming online normalisation [sic]. Really, it comes down to the attention weights that you get there,
so normalisation for normal context. If you're normalising across tokens and you're avoiding the full
sequence softmax computation, it does help you with numerical stability, it helps you with efficiency.
Anytime you're going past like 100,000 tokens, what it comes down to. You get better memory usage,
you get better compute overhead, better real-time inferencing for any of those long-form tasks like
video, understanding or document summarisation or agentic workflows and things like that. A lot of the
bigger frontier models, Claude 3.5, Gemini 3.5 [sic], GPT-4 Turbo, they use long-context inferencing
and they work well with ESUN techniques and things like that. I will say that as you go further in the
future, techniques like ESUN, they're going to be critical to scaling without having exponential cost. If
you look at some of the benchmarks out there like the, long sight, you look at streaming VLM, some of
those benchmarks are being established out there to evaluate the fidelity of long-context settings that
are going out there.

Private and confidential

11

AI Infrastructure & Networking Space & Nvidia 每 Senior Architect at Microsoft Corp 每 24 October 2025

As you bring in UALink, UALink is that interconnect glue is what it comes down to. AMD has been
leading it, Broadcom, Intel, Google, we're involved with it. What it comes down to is you're going to have
coherent memory sharing across GPUs for large-scale inferencing. In addition to having techniques like
ESUN, it will help you to better support disaggregated compute. It's also going to provide for better high
bandwidth, low latency. Those are really critical for technologies like KV cache and like Rubin CPX-style
architecture. All the little bits, they all add up, and that's what something Satya is really big about is just
like see where we can eke out efficiencies, not just from the hardware standpoint, but from software,
from technique standpoint to also just provide and lower the cost of operating these data centres as well.

Analyst:
Based on how you described it, should I view UALink and ESUN as somewhat complementary, where
ESUN will be the protocol on which the actual switch chip runs, but then UALink will be an
interconnect protocol on top of that, so it would be UALink over ESUN? Has the market gotten it right
that silicon is no longer required? What form should I expect UALink to come into the market when it
does?

Specialist:
UALink, it is the high-speed interconnect layer. Those two technologies are highly complementary,
where UALink is giving you ultra-low latency, high-bandwidth communication between GPUs in a
cluster, that allows disaggregated inferencing, so different GPUs can handle context ingestion, they can
handle token generation, they can handle coherent memory sharing. That's where you're going to use
like KV caching or distributed attention, that's why you need UALink. ESUN, on the other hand, it
optimises attention normalisation during inferencing. It tells you, basically, for those super long
sequences, "This is where I can help reduce on memory, this is where I can help reduce on overall
compute," and it maintains that numeric stability.

The way they work together from a hardware standpoint is that at the hardware interconnect layer, they
move data between GPUs efficiently, that's UALink. The model is then optimised using ESUN or KV cache
and that reduces the overall compute and memory per token. The two complement each other very, very
well. UALink, really, it's ensuring that the GPUs can share their KV caches and have their attention
weights quickly and ESUN really ensures that those weights are computed and normalised efficiency
even across these massive, massive token windows and things like that. I would say, think of UALink as
like a highway system that connects different cities and then ESUN is the fuel-efficient engine inside
each vehicle at the model layer that makes sure that the vehicle travelling between those cities is doing
so in the most efficient way possible.

Analyst:
Would you expect two disparate switch fabric chips at the end of the day? Would I be right to think that
it will be IP over a chiplet? What's the backbone? Is it more UALink because that's the highway? Is it
more ESUN? Astera Labs has been working on taping out silicon. The UALink chip that it's going to do
in the first place is over PCIe [Peripheral Component Interonnect Express], which I can't tell if that fits
into this construct or if it needs to be over an Ethernet-based protocol. I'm trying to figure out what
the two different hardware roadmaps might look like and if one is less of a hardware roadmap and
more of an IP or protocol roadmap?

Specialist:
Astera does have plans to support a couple of different distinct chip models for UALink. One optimised
for electrical signalling, another one optimised for photonic and optical interconnects. That's just
because within data centres, you have different deployment needs for rack-scale AI infrastructure. Any
of those electrical UALink chiplets that they have, their current generation, they're going to give you
good high bandwidth, low-latency GPU-to-GPU. Those are what have been being deployed right now,

Private and confidential

12

AI Infrastructure & Networking Space & Nvidia 每 Senior Architect at Microsoft Corp 每 24 October 2025

UALink, like the 200G, things like that. Astera, they do a good job at the fabric level for switch silicon,
retimers and things like that.

Photonic UALink chiplets, that's where they're moving to, though, and those use optical interconnects.
Those frankly, what was it, I know it was this month, October 2025, Astera actually acquired a company
called aiXscale Photonics, those let you do photonic chiplets and fibre coupling techniques. That really is
what gets you to better future proofing, where racks are operating as a unified compute fabric and give
you optical I/O for scale-up and scale-out operations, too. The big benefit there is you're reducing power
and thermal constraints. You have two models right now. The electrical is best for short-reach, high-
volume deployments. Photonic UALink is going to be where we get with the next-generation AI clusters.
Now that they've acquired aiXscale Photonics, it will be interesting to see where they work that into
Astera's portfolio. I would say the industry as a whole is moving that direction.

Analyst:
Do you have familiarity with aiXscale Photonics? Do you consider the team to be a savvy one?

Specialist:
I met them in February this year. I was out travelling California, West Coast. I was talking to some of
them. They're a German-based start-up, and they're some smart guys. They do some high-density
optical I/O, they do fibre-to-chip coupling. The Germans have never been bad with manufacturing or
engineering. They really have looked to what's the five-year problem that we need to solve. Bottlenecks
in optical interconnects, aligning light between chips and fibres and really dense high-bandwidth
environments. They're looking at photonic chiplets as the way to co-package with GPUs, CPUs, switches
and things like that. They've done a really good job of keeping their eye on the industry and where
UALink has been going. I would say that they also know the need for terabits-per-second of
interconnect bandwidth. What they've been keeping an eye on is you've got copper-based signalling but
there's so much, there's power constraints with that, and there's thermal constraints with copper-
based signalling. What can we do to move to photonics? When I talked to them back in February, I think
it was out in California, they've got their eye on the future, they know of where things are going. They've
got some good research and some good products that they've built towards that. It will be interesting to
see how Astera really brings them in there, but theirs is more of a disaggregated, use chiplets to co-
package with GPUs and CPUs to address optical I/O bottlenecks.

Analyst:
I noticed that Ayar Labs is doing a webinar on CPO [co-packaged optics] with Alchip and Astera Labs. I
was scratching my head on why Astera was there and then they announced the acquisition. I might
have been ahead of the ball on that one. How do you see Ayar Labs and Astera Labs' potential strategies
intertwining?

Specialist:
I don't have to think about that one. I know what you're talking about. I saw that press release, too, and I
was like, they're both intertwining around photonic interconnects. I would say, and it's at the rack level
for AI. When it comes down to like Ayar Labs, they've got a pretty strong leadership in chip-to-chip
optical. When it comes down to, UALink is going to drive that. Ayar Labs when it comes down to chip-to-
chip communication, uses just low cost from an optical modulator and detection standpoint, it is super
low power, and it provides you a high bandwidth. Really, Ayar Labs has been targeting AI accelerators,
companies that need memory pooling, anytime you want to do disaggregated compute. Astera Labs'
strategy has been, "At the rack level and for rack scale, let's do better connectivity through UALink,
through PCIe, through CXL, through Ethernet, things like that." Really, if I see their strategies
intertwining, it's at the chip-to-chip optical signalling with CPOs and doing it for silicon photonic
integration and at the UALink. They definitely have complementary strengths on chip photonics, but

Private and confidential

13

AI Infrastructure & Networking Space & Nvidia 每 Senior Architect at Microsoft Corp 每 24 October 2025

Astera is really building at the rack scale. They both have a shared vision of replacing copper with light in
AI clusters and reducing your power and latency.

Analyst:
Can you help me understand how Ayar Labs is competing with Nvidia and Broadcom's CPO efforts and
where they differentiate themselves?

Specialist:
Yes. I would say Ayar Labs vs Nvidia, Ayar Labs, their CPOs are more modular. I would say they are
definitely more power-efficient than Nvidia, and they're targeted, like I said, at more chip-to-chip
rather than Nvidia, which is more switch-level integration. Nvidia is more about massive bandwidth at
the rack level, which is where Astera is. Ayar Labs is more about like, "Let's redefine those interconnects
at the die and the package level." Because they're more photonic with their I/Os, they're going to have
better chip-to-chip integration and better chip-to-chip communication, which every little bit helps.
You're going to have much lower power per bit, you're going to have better modular integration with
CPUs and GPUs and better for more disaggregated architectures. Nvidia is really focused on more switch
ASICs with Spectrum-X and Quantum-X. For them, you're going to have really good performance at the
rack level and better port level, but you're again getting back to the switch, so you still have to travel
back to the switch in order to do high-density AI clusters with thousands of GPUs.

The difference being is just with Nvidia, at the integration level, you're at the switch ASIC and the optical
engine, Ayar Labs is at the silicon photonic level. The bandwidth focus for Nvidia is the rack scale vs Ayar
Labs at the chip level, which still gets you at terabits-per-second. The modularity for Nvidia, it's fixed
optics per switch vs Ayar Labs are more modular. I would say, though, the power efficiency from a CPO
from Nvidia is definitely like I think it's 3-3.5x better than pluggables. Ayar Labs is definitely, and you're
already consuming super-low power, it's ultra-low power. Nvidia is good. The problem, though, is that
if you've got failed optics, then you have to replace the switch and the optics vs Ayar Labs. I can just
isolate whatever the fault was and swap out the individual CPO. Really, both are targeted towards
hyperscalers. It's looking at where failure isolation happens.

Analyst:
It would be really interesting to see how all this develops. I know that we're probably a couple of years
away from CPO coming into the fold, but it's going to be super interesting to see how it plays out. It
seems like we'll get a lot more in early November, at least in terms of what the vision actually is.

OpenAI announced 26-27GW of capacity that it's going to put in place by the early 2030s timeframe.
That's more than 10x the size of the 2GW of existing capacity. It compares to what I believe to be
around 1GW getting deployed, whether it's Hyperion or Project Rainier, taking at least one year. All
that together, how do you think about the possibility to deploy at scale and pace that OpenAI is saying,
considering land and power constraints? Is there a more reasonable scale that you think they could
hypothetically get to by 2030?

Specialist:
I will say that whole 26-27GW, it's pretty ambitious because currently it's just short of 2GW now. There
are a lot of hurdles there. You've got grid access, you've got transmission build-out. Regulatory
bottlenecks is a lot more＃ I see stories in the local newspaper now, and I live out in the country about
data centres and how much power data centres are consuming and things like that. The locals have a
very Nimby and don't want to give up my land for transmission lines and things like that. That being
said, it's a very bold ambition for them. It's going to really hinge on Sam's ability to do partnerships on
also regional energy policy. If you look at like Vermont, they hate data centres, they don't want data
centres anywhere there, but also utility coordination. That's what they do, is really developing

Private and confidential

14

AI Infrastructure & Networking Space & Nvidia 每 Senior Architect at Microsoft Corp 每 24 October 2025

partnerships with utilities with IPPs to sign PPAs and things like that. I would say with Stargate right
now, the flagship facilities down in Abilene. If SoftBank is willing to keep honing up and Oracle too,
they'll definitely be able to scale that area. Also, that's to support GPT. They've also been talking about
supporting like Claude in conjunction with Anthropic to do multi-agent orchestration and real-time
personalisation.

The compute scale, though, that is millions and millions and millions of GB200s, and you need rack-
level power that definitely exceeds 140kW-per-rack. You would need a blend of different energy sources
like nuclear, solar, wind, natural gas, on-site battery storage, grid interconnects and things like that.
Also from a water standpoint, you're going to need a lot of water to do liquid cooling of that many
million GPUs. I would say that also the big things you need to look at there are the grid interconnect
delays because utilities right now are, they're pushing back and they're saying, "You're going to need to
give us 5-10 years." We're like, "We can't wait 5-10 years for high-voltage lines and things like that."
I'd also say permitting, there's multi-year regulatory hurdles being put in place for a lot of those nuclear
projects and for gas projects. FERC and a lot of the utilities out there, they're just basically pushing back
to saying, "We're limited on the number of assets we have. Then when the government shut down that
we're not getting responses on that." Also, capital allocation, too, when it comes down to demand
realisation. A lot of investors are saying, "We need to see more returns on this a lot faster, too."

What it comes down to, I would say it's very ambitious, but realistically, 27GW, it is their North Star. It's
not guaranteed. I would say it's going to take probably 5-10 years. I'd say, by 2027, you're probably
going to see 5-10GW, not 27GW, and that's just because of regulations and scaling. I would say energy is
probably the biggest moat there is what it comes down to is that just getting clean, scalable power is
what's going to determine OpenAI's competitive edge. Then infrastructure as a strategy. It's not just
about the chips, it's also about the power, the land, the fibre and the cooling. You've got to control that
whole stack and that full stack. The chain is only as strong as its weakest link. If you don't have good
land strategy, if your fibre is not up to it, if you're not able to cool that many millions of GPUs, you're not
going to be able to have that much compute power out there. It's a good ambition.

Analyst:
Do you think Broadcom's ASIC design momentum vs Marvell is purely related to the fact that it'll
actually do part of the front-end design for I/O [input/output] and memory guys, whereas Marvell is
doing a lot more of the back end and the front end is where some of these software companies need
help because they just don't have hardware know-how? If I boiled it down to one thing, is that the
main driver in your mind?

Specialist:
Broadcom is definitely more successful in ASIC design, and they've got 55% of the market share. They've
got better hyperscaler relationships and partnerships, they definitely have a more mature roadmap.
Marvell has been gaining ground. Broadcom, frankly, they're better with scale, they're better with
execution, better with revenue growth, too, that's why they've got about 60% of the market share. They
work with Meta on their MTIA, they have the 2nm. They're working with them Google on CPU V8.
They're really good at executing and they're being good at being first to market. I would say Marvell,
their market share is 15%. Amazon's Trainium 2 was Marvell. They're really good with electro-optics
and networking silicon. The problem with Marvell, though, is just they don't have the scale, they don't
have the deep co-design history. I know Marvell is trying to aggressively hire people away from
Broadcom. If they can execute on it, then yes, they can change, but Broadcom now, that's why they're
still leading. It's their ability to execute.

Private and confidential

15

AI Infrastructure & Networking Space & Nvidia 每 Senior Architect at Microsoft Corp 每 24 October 2025

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

16



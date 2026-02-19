CLIENT-LED

65d0d6538a8911da05d11de9b49cc840996c80c0

Semiconductor & Infrastructure Software
Industry 每 Arista Networks, Astera Labs &
Fabrinet 每 Senior Architect at Nvidia Corp

Consultant | 16 October 2025

Specialist Background

> Around 20 years' experience in the semiconductor industry, focusing on mobile chips, custom

accelerators, cloud systems and data centre infrastructure

> Well-versed in the semiconductor and infrastructure software industry's competitive landscape,

including power chips and subcomponents companies

> Well-placed to discuss whether Arista will lose share because of advancements being made on
the Spectrum-X, as well as Astera Labs' growth runway and where Fabrinet sits in the supply
chain

> Knowledgeable on how far we are on the Chip-on-Wafer to eliminate the substrate, as well as

cold plating and HBM (high-bandwidth memory) technology

Contents

We're looking to better understand the semiconductor and infrastructure software industry.
We're familiar with Google TPU [tensor processing unit] 7, Trainium and AMD [Advanced
Micro Devices] is coming up with the MI350, 450 in 2026. Do you believe these chips are close
to competing with Nvidia?

You mentioned the whole rack level and the networking lens as well. What are the big
architectural changes happening? Do you believe a company such as Arista will lose share
because of the advancements being made on the Spectrum-X?

When we look at component companies, there are people building power chips and other
subcomponents. Which companies do you believe have the best solution?

Who builds the UALink [Ultra Accelerator Link]? Is there another company that can benefit
from it?

Let's move to semi and component companies, such as Astera Labs, that have really amazing
technology. The company seems to be doing a little on the active cable. Which other company
comes to your mind?

3

4

4

4

5

Semiconductor & Infrastructure Software Industry 每 Arista Networks, Astera Labs & Fabrinet 每 Senior
Architect at Nvidia Corp 每 16 October 2025

Do you believe Astera Labs and Credo have a long runway? How much room do they have?

Are you familiar with SiTime? Do you know about the timing chips?

Where does Fabrinet sit in the supply chain, and if you aren't using it for the assembly, which
player does that step go to? Who are the competing vendors?

Given you don't use Fabrinet for the module assembly, what other companies accomplish that
for you?

Which companies do you believe have a lot of growth ahead of them? We know HPM [Hanwha
Precision Machinery] is getting very popular, but I'm sure there are others we don't know of.
Are there other components that are becoming more critical, as complexity is increasing?

How far are we on the Chip-on-Wafer to eliminate the substrate? Who makes that?

Power management must be quite critical. As power requirements increase, does the amount of
content Monolithic Power Systems has on a single board also increase?

You mentioned the cold plating technology. Which player does that?

You mentioned believing TPUs will probably still take a little while to compete, at least a few
more years. Do you think it can come close to inference in 2027?

5

5

6

6

6

6

7

7

8

Private and confidential

2

Semiconductor & Infrastructure Software Industry 每 Arista Networks, Astera Labs & Fabrinet 每 Senior
Architect at Nvidia Corp 每 16 October 2025

Semiconductor & Infrastructure Software
Industry 每 Arista Networks, Astera Labs &
Fabrinet 每 Senior Architect at Nvidia Corp

Transcription begins

Analyst:
We're looking to better understand the semiconductor and infrastructure software industry. We're
familiar with Google TPU [tensor processing unit] 7, Trainium and AMD [Advanced Micro Devices] is
coming up with the MI350, 450 in 2026. Do you believe these chips are close to competing with Nvidia?

Specialist:
In general, I don't think any of these companies are close. You talked about the TPU, I would probably
put it around six on a scale of 10. Then MI450, again, I would put it around six or seven. Then Trainium,
again, I would put it at six.

Analyst:
I know of Groq and Cerebras, and there are a few others that are coming up.

Specialist:
Yes. No, they are not, and they are struggling. I have friends at these companies. It's hard for them to
find customers that can meaningfully add significant revenue. Also, the way to think about this is also
like what kind of workloads you are attacking. We are talking about like inference space. Of course, in
training space, I don't think all of these competitors are much farther behind. In inference space, like
MI450 is definitely a good contender. I still don't think that they are where they need to be in terms of
software yet.

Then the TPU is also, I would say, a pretty good reasonable contender in the custom accelerator space,
but also keeping in mind that it's mostly for specific workloads like internal workloads that Google
optimises the TPU for something like YouTube recommendations or Gemini. This is not something very
surprising. GPUs are what they have been since a while. They are general purpose accelerators, still
accelerators, but not suited for any specific workload. They perform well at most of the workloads. Then
you have the specialised architectures that are basically tailored or custom-made for transformer
architecture.

You have different variants like you mentioned about Groq and Cerebras, they want to take advantage of
almost infinite amount of memory available to them, which again works well for a lot of workloads. For
a majority of the workloads, they are still not competitive, I would say, in real life. Software is one piece
that I mentioned, but also networking is the other piece. When you think of the new unit of computing,
that's the data centre as a whole. You have to think in the scale of like rack-level computing rather than
like a single chip. You have the chip, you have the connectivity part, networking, again, Nvidia is far
ahead than some of the alternatives like Ethernet for scale-out or PCIe for which most of these other
companies use.

Analyst:

Private and confidential

3

Semiconductor & Infrastructure Software Industry 每 Arista Networks, Astera Labs & Fabrinet 每 Senior
Architect at Nvidia Corp 每 16 October 2025

You mentioned the whole rack level and the networking lens as well. What are the big architectural
changes happening? Do you believe a company such as Arista will lose share because of the
advancements being made on the Spectrum-X?

Specialist:
Yes. No, it's a good point. I know that the opinion was that Arista Net is going to lose. I don't really think
so because Arista Net is a competitor to InfiniBand and Spectrum-X, but their solution is very different.
Again, along with the Broadcom, they have the 400G, 800G, which is like the vanilla out-of-the-box
network switching solutions and connectivity solution that just works. Some of the hyperscalers like
AWS don't like Nvidia connectivity because they don't want to pay licensing fees. They don't want to pay
the margins and so on and so forth. They have their own version of Ethernet, but they also use to an
extent, the Broadcom switches. They also use to an extent, Arista. At the same time, Meta also in some of
their data centres, it continues to use Arista and Broadcom. Google, of course, I don't know if they use
Arista for the network connectivity. They might have some of their own connectivity solution itself.

I think Arista also has more room to grow, like someone like Google or Amazon could also basically
adopt their switching solutions. I know that other than AI data centres or servers itself, like for HPC,
Arista is like a very, very popular name that's being used.

Analyst:
When we look at component companies, there are people building power chips and other
subcomponents. Which companies do you believe have the best solution?

Specialist:
We are still talking about the networking side? Is it like scale-up network?

Analyst:
The scale-up side, because it seems like you're trying to build bigger and bigger solutions.

Specialist:
Yes. I think one is definitely one that has established scale-up solution is Google, which is using their
own interconnect solution in their TPUs for scale-up solutions. The other one, which is, again, like I was
talking about the UALink, it's not adopted, but AMD, Intel, and Broadcom are basically trying to adopt
that and commercialise that more. I think the most promising right now is the PCIe gen 5 and gen 6 that
most of the hyperscalers, they are using some version of this, and it's also compatible with the standard
switch fabrics from Broadcom. It doesn't need a lot of cost-sensitive hardware and PCIe is basically just
open-source protocol. I think that is the most widely adopted right now. Now in terms of the future, it's
hard to say because with NVLink licensing opportunity,

Analyst:
Who builds the UALink [Ultra Accelerator Link]? Is there another company that can benefit from it?

Specialist:
Yes. No, there is no one company. It's a consortium of multiple companies like it's backed by AMD, Intel,
Broadcom, Cisco, Google, and Microsoft, Meta, all of these companies, they are backed it. It's not gotten
traction up until now.

Analyst:
You mentioned gen 5 and 6. Is that also proprietary internal, or is there an external company that offers
that?

Private and confidential

4

Semiconductor & Infrastructure Software Industry 每 Arista Networks, Astera Labs & Fabrinet 每 Senior
Architect at Nvidia Corp 每 16 October 2025

Specialist:
The PCIe gen 5, gen 6, those are open-source protocols. They are open-source protocols, but say you
want to implement that, then companies like Synopsys would provide the SerDes for that for you to
integrate as an IP. Then you need retimers for PCIe. Companies like Astera Labs are the leaders that
support those.

Analyst:
Let's move to semi and component companies, such as Astera Labs, that have really amazing
technology. The company seems to be doing a little on the active cable. Which other company comes to
your mind?

Specialist:
Yes, Astera Labs and there is another company called Credo. Again, those are the two leaders. I would say
those are the two legit companies that would come to my mind, especially for the connectivity, like AEC
connectivity. Now there are a bunch of other companies that are also doing optical connectivity and
design optical transceivers. Then there are even fewer companies which are basically working on
integrating the optical photonics on the board and on the package. It's silicon photonics and the
technology is called CPO, co-packaged optics.

Analyst:
Do you believe Astera Labs and Credo have a long runway? How much room do they have?

Specialist:
Correct. Yes. I think they should still have a pretty long runway because copper cabling is not going to go
anywhere. Say, it's at 100% today, say, five years from now, it will be probably at still 80-90% purely
because it's just cheaper and with active electrical cables also have their own signal integrity issues. For
your rack-scale connectivity, you don't need to travel several yards or several metres. They are cheaper,
they are reliable, so they should continue to work. For scale out, definitely, you need to look out for these
other alternatives because currently, they are more expensive.

Analyst:
Are you familiar with SiTime? Do you know about the timing chips?

Specialist:
I have heard about it, I have heard about SiTime, but I don't know a lot about how the performance is or
who is using them. I believe probably some hyperscalers is already using them.

Analyst:
You are not using it for doing the timing chips, right?

Specialist:
Right. Yes. No. For PCIe retimers, Astera Labs is pretty much the de facto.

Analyst:
We're also interested to learn about Fabrinet on the assembly side, and it seems Nvidia and Mellanox has
a pretty tight relationship with them.

Specialist:
Right. Yes.

Private and confidential

5

Semiconductor & Infrastructure Software Industry 每 Arista Networks, Astera Labs & Fabrinet 每 Senior
Architect at Nvidia Corp 每 16 October 2025

Analyst:
Where does Fabrinet sit in the supply chain, and if you aren't using it for the assembly, which player
does that step go to? Who are the competing vendors?

Specialist:
Fabrinet comes like pretty, I would say, like late in the design cycle, like it's more at the subsystem and
module assembly chain. It sits more in the optical transceivers and co-packaged optics assembly. It's
like the completed PCB assembly enclosure, system level burn-in. Those would be some of the last major
steps, at the PCB level itself on the assembly build line.

Analyst:
Given you don't use Fabrinet for the module assembly, what other companies accomplish that for you?

Specialist:
There is Foxconn for assembly. Then there are other alternatives. There is Coherent Corporation, there is
Jabil. There is also like AWS, we also had InnoLight. Those are some major ones.

Analyst:
Which companies do you believe have a lot of growth ahead of them? We know HPM [Hanwha
Precision Machinery] is getting very popular, but I'm sure there are others we don't know of. Are there
other components that are becoming more critical, as complexity is increasing?

Specialist:
Yes. The cold plate component is definitely something to watch out for. You have also just the
components that are involved in the high-speed interfaces, connectors. We already talked about
retimers. One component we didn't talk about is power management modules like VRM. Infineon is one
company that makes them. There is also MPS. I would look at these two companies because these are
pretty much in high demand, even though they are not like a very high-margin business, but just a
volume point of view, I would be looking at those. You mentioned about HBM memory. There are also
other memories, so memory makers itself like Micron and SK Hynix. Even though not every server would
use HBM, so you could still have LPDDR or GDDR memory like low-cost memory, NAND, NVMe
components. Then we talked about the advanced interconnects, which have a very tight integration with
HBMs, with the GPUs, AI accelerators. These are like high-density interconnect PCBs. We are talking
about Microvias, more finer wire traces, stacked designs.

There is also a technology which I believe could become big after CoWoS. It's called Chip-on-Wafer-on-
PCB. You eliminate the substrate part and you directly are basically using the PCB as your substrate layer
as a connectivity between different chiplets. That's promising. I mentioned all of these, I would say are
right.

Analyst:
How far are we on the Chip-on-Wafer to eliminate the substrate? Who makes that?

Specialist:
CoWoP, I would say it is in a pretty advanced stage. We could see production side of it like sometimes
maybe next year or the year after that. It is in a pretty advanced stage, and it's like developed as an
alternative to all the supply chain bottlenecks that we are seeing with CoWoS itself. As to who makes
that, again, TSMC has the technology, has the capability to make it. Samsung has the capability to make
true 3D packaging with interposer and PCB integration. Amkor also has that capability. Yes, I think
probably Unimicron is another company. ASE is another one. All these are like they have the technology
to make this.

Private and confidential

6

Semiconductor & Infrastructure Software Industry 每 Arista Networks, Astera Labs & Fabrinet 每 Senior
Architect at Nvidia Corp 每 16 October 2025

Analyst:
On the power management side, you mentioned MPS. Is that Monolithic Power?

Specialist:
Yes. MPS is Monolithic Power Systems.

Analyst:
Is there any alternative to them or is Monolithic the best in technology?

Specialist:
Yes. I think both Monolithic and Infineon, I would say they are both pretty good.  Monolithic is smaller.
That's why I would probably give them one extra point if I had to rate them on a scale of 10 compared to
Infineon, their support, their technology is still pretty good for a small company like that.

Analyst:
Who makes the advanced interconnects with HBM [high-bandwidth memory] and high-density
interconnects?

Specialist:
I would say pretty much the same players who are usual suspects for PCBs.

Analyst:
Power management must be quite critical. As power requirements increase, does the amount of
content Monolithic Power Systems has on a single board also increase?

Specialist:
Yes, definitely because previously, we had one or two phases that would deliver the power to the entire
package or the chip. Then we had like eight phases, then we moved to 16, 32 phases. You need pretty
sophisticated power management and VRM modules to handle that. At the same time, you also have a
new technology called backside power delivery by which traditionally, you use the same metal layers
within a chip for the power delivery, and so they have to fight with the resources on the wiring and
connectivity side within a chip. With the backside power delivery now, you can supply the power to the
chip from one side, whereas you could use the other side for all your interchip routing resources. That
technology is also pretty new. That also has additional complications. I would say the amount of content
on the PCB is increasing for someone like MPS to handle and get more share.

Analyst:
You mentioned the cold plating technology. Which player does that?

Specialist:
I think there is Vertiv, who is the leader. There is Supermicro, who has their own liquid cooling. There
are others like Schneider who also have the liquid cooling technology, but Vertiv is the leader.

Analyst:
On the component side, they make bigger systems for data centre cooling, but I was thinking about the
chip level or the board level cold plates. Are you familiar with a company called Asia Vital Components?
It does thermal cooling and makes a lot of components for liquid cooling for the chip. It used to do the
cooling for notebooks.

Specialist:

Private and confidential

7

Semiconductor & Infrastructure Software Industry 每 Arista Networks, Astera Labs & Fabrinet 每 Senior
Architect at Nvidia Corp 每 16 October 2025

Probably not. I've heard about Thermal Dynamics, and I've heard about Boyd.

Analyst:
You mentioned believing TPUs will probably still take a little while to compete, at least a few more
years. Do you think it can come close to inference in 2027?

Specialist:
Yes. If you want to do something like a public cloud service, I think it will still be longer than that
because today, they are purely optimised for the internal workloads. When you open up your
infrastructure to the outside world, you need to ensure that it works seamlessly with each and every
workload. That's the point that I was trying to allude that these are optimised for very, very specialised
workloads. It will take longer than just maybe one year or two to make them work for each and every
workload.

If, say, Google were to open up the TPU ecosystem to the outside world, which I'm sure they will sooner
or later, how much time will it take for someone like a small start-up who doesn't probably know
anything about their TPUs to get on the TPUs and start using them, something which we are seeing with
AMD. They struggle pretty much for 2-3 years to even come up with a strategy for their software, even
though their hardware is pretty competitive.

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

8



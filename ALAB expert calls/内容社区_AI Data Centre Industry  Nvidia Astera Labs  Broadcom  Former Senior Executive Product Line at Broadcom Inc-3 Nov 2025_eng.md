CLIENT-LED

65d0d6538a8911da05d11de9b49cc840996c80c0

AI Data Centre Industry 每 Nvidia, Astera
Labs & Broadcom 每 Former Senior
Executive, Product Line at Broadcom Inc

3 November 2025

Specialist Background

> Over 10 years' experience in the networking side of AI, focusing on connectivity and fabric, with a

strong understanding of the AI data centre industry

> Well-versed in how Nvidia's NVLink connects a lot of GPUs (graphics processing units) and the

PCIe (Peripheral Component Interconnect Express) is more in the back end

> Well-placed to discuss how Astera is doing a lot of PCIe, highlighting its competition in retimer

chips and technology vs Broadcom and Credo

> Knowledgeable on vendors benefiting vs losing in the technology landscape, including the

Spectrum-X switch with Nvidia and Arista's pluggable optics

Contents

We're trying to better understand the AI data centre industry, and we've seen a lot of
developments happening with Nvidia and the AI server ecosystem. Nvidia's NVLink connects a
lot of GPUs [graphics processing units], and the PCIe [Peripheral Component Interconnect
Express] is more in the back end. They bought Mellanox for InfiniBand, which they've made
more proprietary. How do you think about the connectivity and fabric in the more near-term,
so the next 6-9 months, and the more mid-term, so two years?

Is Astera doing a lot of PCIe?

Given PCIe has been around for a while, isn't there a lot of other competition? I believe Astera
does retimer chips and they were the first ones to come in for Gen 4, Gen 5, right?

In the world of technology, unless one has a big advantage, why would one not use Broadcom?
Do you think Astera will have enough competitive advantage in six or 12 months or will their
business not sustain this growth level?

Which vendors are benefiting vs losing in the technology landscape? A lot of people are
choosing Ethernet. Across all parts of the value and supply chain, which companies are going to
go through a massive growth phase?

3

4

5

5

6

AI Data Centre Industry 每 Nvidia, Astera Labs & Broadcom 每 Former Senior Executive, Product Line at
Broadcom Inc 每 3 November 2025

Broadcom is a key vendor; we get that. What about other companies? Is there any interesting
connector company? Is anyone using products and smaller companies?

Who directly competes with Credo?

Credo has better technology, right? Do they have an advantage or not?

You mentioned some of the connectors, and we know the Spectrum-X switch is coming with
Nvidia, and they're trying to integrate that. Is that a big deal? Who is that going to impact?

We understand Arista is doing the pluggable optics, and they won't be able to scale after 1.6. Are
you familiar with Celestica? What about Axon? Is Arista going to gain or lose share relative to
Spectrum-X?

Our sense was that Spectrum is more of the backplane of connecting GPUs, whereas Arista and
other networking vendors are more outside of that closet. Is that right?

Are there any PCB [printed circuit board] vendors or substrates you feel very good about for
components?

6

7

7

7

7

8

8

Private and confidential

2

AI Data Centre Industry 每 Nvidia, Astera Labs & Broadcom 每 Former Senior Executive, Product Line at
Broadcom Inc 每 3 November 2025

AI Data Centre Industry 每 Nvidia, Astera
Labs & Broadcom 每 Former Senior
Executive, Product Line at Broadcom Inc

Transcription begins

Analyst 1:
We're trying to better understand the AI data centre industry, and we've seen a lot of developments
happening with Nvidia and the AI server ecosystem. Nvidia's NVLink connects a lot of GPUs [graphics
processing units], and the PCIe [Peripheral Component Interconnect Express] is more in the back end.
They bought Mellanox for InfiniBand, which they've made more proprietary. How do you think about
the connectivity and fabric in the more near-term, so the next 6-9 months, and the more mid-term,
so two years?

Specialist:
On the fabric side, the main traction right now on the AI side is scale-up. On the scale-up side, the
domain is basically, three key aspects are playing over there. One is the NVLink. Second one is the Ultra
Accelerator Link or the UALink. The third one is Ethernet scale-up. The NVLink is far ahead of the game
and for a very simple reason because Nvidia was invested into GPUs. They have been investing into the
infrastructure and software since almost a decade. By the way, NVLink was existing even in 2014 or 2012
initially. You can imagine that the progression being made in the past 10-12 years on NVLink by itself.

They are currently the pioneers, but the drawback over there is it is a closed box environment. It's not an
open domain. Yes, they have infused the NVLink fusion for those hyperscalers or customers who are
designing their own XPUs and want to attach it to the Nvidia fabric, but it's still dominated by Nvidia
because they don't tell you the nitty-gritties of the NVLink. They just provide you with a chiplet, you
attach it on your design and that particular SoC gets hooked up to the Nvidia fabric. Plus a very rich
CUDA software environment, which supports it. This gives you the best performance. The second tool,
the other two ones have emerged recently. The reason why they have emerged is because the industry
wants an alternative route and they don't want to be fully dependent upon Nvidia or pay a heavy
premium for it.

Secondly, the very important aspect is customers are designing their own XPUs, their own interconnect
fabric as well. Not everything is related to Nvidia. Nvidia is a pioneer in training, but when it comes to
inference, the hyperscalers want to design their own XPUs. These might be the Microsoft, the Amazons,
who want to design by themselves. For them, the connectivity today is PCIe or Ethernet. The gen 0 is
PCIe and the gen 1 is Ethernet, I would say, and then comes the UALink. Now, there is a fine line between
what NVLink, UALink and Ethernet does. NVLink is purely on memory semantics. What we are trying to
achieve over here? We are trying to create a mesh of different GPUs to be connected so that they look as a
unified GPU, as one entity, and this can be in form of a pod, a pod can be six, nine, 12 GPUs or it can be of
entire rack of 72 GPUs, and it can scale from one rack to the other rack and can be a unified 144 GPUs
based on what compute load are you trying to achieve. Having said that, memory semantics basically
allows the coherency of memories, the HBMs, which are there in the GPUs so that they look unified. Why
do we do that? The reason why we do that is because GPUs are the highest OPEX on the data centre today.

Private and confidential

3

AI Data Centre Industry 每 Nvidia, Astera Labs & Broadcom 每 Former Senior Executive, Product Line at
Broadcom Inc 每 3 November 2025

You want to make sure that these GPUs are not underutilised or neither they are over utilised or burned
out. Underutilised means you have paid the money for it, but they are not being used for the optimal
performance. Over utilised means you give a particular workload to them, and it takes days and months
or weeks to converge. You don't want that to happen. You want them to operate at an optimal
performance, and that's why you want to unify them so that everybody can borrow each other's HBM
and finally, do like how you do multicore in the olden days. It's exactly a concept of multicore, but you
are at scales between different devices, not within one device.

The only protocol, and this is an important aspect. Now, the only protocol which comes closer to NVLink
is UALink. This is basically what AMD tries to do. AMD has to compete with Nvidia. Ultimately, when the
GPU performance is published in technical publications, they will publish basically what is the
convergence time, what is the power ratio and what is basically the performance ratio of these GPUs. For
that to happen, AMD came up with a UALink, which is also on memory semantics, and it gives them the
site or the scale to compete with Nvidia. However, for UALink, AMD came up with this spec one year
back, but unfortunately, they don't have a strong ecosystem like Nvidia, which they have established
over a period of 10-12 years.

In fact, even the AMD GPU today, the MI350 or the 450, which is coming up, do not support UALink as a
port. The first device which will have a UALink as a port will be MI500 coming sometime in mid-2027. In
intermediate, they have to basically live with something like a UALink over Ethernet, just as a reference.
This is what exactly they have done on the Helios rack, what they have today. The next generation of the
rack will be Arcadia and then the forward-looking of Arcadia will be having the UALink. The UALink,
though the protocol is very strong, it has the right elements, but it doesn't has a solution today. Today,
there is no UALink device.

There's no UALink switch, and it is still floating, but there is hope that it will come up by 2026-27. The
last one is the Ethernet one, which is the most simplest one. This has been basically advertised by a lot of
switch vendors with the inclusion of like Marvell, Broadcom, Cisco, Microsoft, Meta, they all are in the
camp of Ethernet, which is called ESUN, Ethernet Scale-Up Network [sic]. What that does is, since there
is no existing stuff except the NVLink, why don't we explore on the Ethernet and do the scale-up of
these GPUs using Ethernet. Previously, it was done using PCIe. Let's not forget that. If there was nothing
existing, if you go back five years or four years back, how was these GPUs connected if there were non-
Nvidia GPUs was through PCIe, though the product has＃

Analyst 1:
Is Astera doing a lot of PCIe?

Specialist:
Yes. The Astera's first generation of scale-up is through PCIe because they have a PCIe switch, Scorpio.
They have basically said, "Okay, let's the first generation of scale-up being done by PCIe." It basically
doesn't uses the full memory semantics. It operates at a much lower speed, which is 128Gb. The normal
UALink is running at 200Gb. You get a boost of almost 70% in performance. Having said that, Astera has
a customer in hyperscaler who says, "Okay, Gen 0, I'm going to do through PCIe and the next
generation, I'm going to do it through scale up." Let's not forget that you're connecting the XPUs to this
fabric. The XPUs also need to have the technology to be connected. All the XPUs today are on PCIe or on
Ethernet, either one of them. If today, somebody wants to deploy and do a pilot programme, they will
use PCIe or Ethernet and Astera basically meets the requirement of PCIe. If you ask me, is it going to be
long-term? Is it going to be 4-5 years? No. It's going to be a very small, I would say, graphic solution
because ultimately, they are going to embark on the UALink side of things.

Analyst 1:

Private and confidential

4

AI Data Centre Industry 每 Nvidia, Astera Labs & Broadcom 每 Former Senior Executive, Product Line at
Broadcom Inc 每 3 November 2025

Given PCIe has been around for a while, isn't there a lot of other competition? I believe Astera does
retimer chips and they were the first ones to come in for Gen 4, Gen 5, right?

Specialist:
The retimer was used only in Gen 5. Till Gen 4, people were fine. It was running at 16Gb and you really
did not need a retimer. In Gen 5, which is in 2020 timeframe, 2021 timeframe, Gen 5 came into place.
Where Astera Excel was it had all the link up with the OEM and the hyperscaler. They had two strong
companies to back them up, and it's like a perfect tsunami. They had Intel to back them up. They had
even Amazon to back them up to use the PCIe Gen 5 retimer. They capitalised on the market straight
from the get-go because they had a strong customer base. Let's not forget to give them credit that they
even executed and they delivered the stuff to the customers.

Analyst 1:
It seems Broadcom now has a retimer chip for PCIe.

Specialist:
Yes. The competition has got fierceful because there are other entrants like the likes of Broadcom, who
have PCIe Gen 5 and Gen 6 retimers. In terms of growth, it's difficult. In terms of the market share, they
have already captured that market share unless and until the vendor wants a second source, then it's
different. It's becoming more and more competitive in that market space. There are plus Chinese
customers like Montage who are also into that space.

Analyst 1:
In the world of technology, unless one has a big advantage, why would one not use Broadcom? Do you
think Astera will have enough competitive advantage in six or 12 months or will their business not
sustain this growth level?

Specialist:
They don't have an advantage, but the question is not of the advantage because it's the basics of all the
PCIe retimer works. There is no rocket science to it. They keep saying that they have these lab, interop
labs and all those stuff. That is all noise. The main thing is the barrier to entry. Once these customers use
Astera, they have qualified it. They have put it in their software. They have to embed their BIOS. These
server platforms, which have been made are made through different ODMs. They don't have one
manufacturing company. There are different manufacturing companies who design these PCBs and the
boards. Astera has gone through all the call.

For a customer to change Astera and get another vendor, the call period is quite long. It's about 6-9
months. Does the customer have the patience to basically get in some other vendor, do the qualification
and take the risk of their software, the firmware, everything associated with it. That is the stickiness
which Astera has already hooked on the customer to. They have already done the groundwork. It's
already cemented. It works fine. Why will the customer change for some few pennies? If the customer
comes and says, "Okay, I'm getting this from Broadcom for this much amount of money," Astera can
easily price match it or do something or cut a deal for them. There is no incentive for the customer to
make this change and go through the whole grind unless Astera is really squeezing them and causing
them more grief in terms of business.

Analyst 1:
Let's say, for the next generation of design-in, it's when people change vendors.

Specialist:
Absolutely. That is a good point. In next generation, when PCIe Gen 5 required a retimer for sure,

Private and confidential

5

AI Data Centre Industry 每 Nvidia, Astera Labs & Broadcom 每 Former Senior Executive, Product Line at
Broadcom Inc 每 3 November 2025

because it was based on the NRZ protocol. PCIe Gen 6 is basically a PAM4 protocol. It runs at 64Gb. If you
notice like the likes of Nvidia and all, PCIe Gen 6, they don't need a retimer. They have designed their
cards in such a way that the retimer is not needed. In fact, Nvidia went a step ahead. In the ConnectX NIC
cards, they have the PCIe switch also integrated inside. They have completely eliminated Astera from
their usage model.

They had Astera in the PCIe Gen 5, but in Gen 6, no retimers, no switch is needed for Nvidia platform.
They eliminated Astera. Now, what that has said is that has set a precedence in the industry. When the
competition sees that happening with one of the key vendors like Nvidia. For PCIe Gen 6 overall, not just
Astera, but even for other vendors, the retimers will not be as lucrative a business as compared to Gen 5.
It's by the nature of the protocol and using PAM4 and using the long-reach SerDes, you are eliminating
the need of the PCIe retimer. Gen 6 retimer market will not be as hot as the PCIe Gen 5 retimer market.

Analyst 1:
Is this coming with Rubin or Rubin Ultra?

Specialist:
This is coming with Rubin and Rubin Ultra both, and this is coming even with the ConnectX NIC cards,
which are already in production today. I think it was connected seven or eight, if I'm not mistaken.

Analyst 1:
Which vendors are benefiting vs losing in the technology landscape? A lot of people are choosing
Ethernet. Across all parts of the value and supply chain, which companies are going to go through a
massive growth phase?

Specialist:
I would say definitely companies like Broadcom, Astera Labs will, and I will tell you why. Cisco is a black
horse right now, and they haven't really come up with a clear good guidance as to what they're going to
do on the scale of fabric. They are there everywhere, but they are really not making an impact as such. Of
course, Nvidia is the dominant, so that goes by default because they don't have any competition, so I'm
not even going to name them. I would say Marvell, Broadcom and Astera are one of the key guys.

The fourth guy which is going to come up, and it depends how they play is AMD. I'm a little bit surprised
that AMD hasn't made any moves in terms of industry acquisitions or organically growing their
footprint because right now, if you look at it, they have a good market valuation. Their stock is doing
pretty well. They need to look at the next frontier of networking where they are lacking. The only
networking element they have today is the NIC card, which they bought through Pensando, if I
remember. They are not having a solution of connectivity. They're not having a solution of switching
inside it. That's another one, fourth one, which I would keep my eye on depending upon what M&A or
what development they are doing in the R&D.

Analyst 1:
Broadcom is a key vendor; we get that. What about other companies? Is there any interesting
connector company? Is anyone using products and smaller companies?

Specialist:
The smaller companies are all doing photonics like Lightmatter, Celestial and all those guys. They are all
into photonics. That industry is not going to jump start in the next 12 months. It's going to take them at
least 3-4 years to stabilise in that space. That space is a little bit oversaturated with a lot of start-ups. In
terms of connectors, most of the guys are very well-established. There's Credo, there is Broadcom, there
is Marvell. You need to have that expertise to get into the connector business because you're dealing

Private and confidential

6

AI Data Centre Industry 每 Nvidia, Astera Labs & Broadcom 每 Former Senior Executive, Product Line at
Broadcom Inc 每 3 November 2025

with a lot of impediments of different board vendors, different things happening around the stuff in
terms of signal integrity. I would say that I don't see any new start-ups coming up in the connector
space. There is a well-established. Credo is doing fabulously well, to be honest, whatever they are doing,
especially on the 1.6T AEC and all, they have a clear market dominance and a little bit of a leverage.

Analyst 1:
Who directly competes with Credo?

Specialist:
Astera competes with Credo in some format. It's just that they are not putting the full focus on that
space, but Astera has active electric cables. They have done it for Gen 5. Then there is the likes of Marvell
and Broadcom, who are also in that space. Again, Broadcom is not fully invested, they are not really
putting their lights on that space, but, you know how Broadcom operates. The way they operate is when
they see a huge amount of revenue coming from that market space, suddenly, they'll turn on the lights
and quickly ramp to that space in the next 6-9 months. They'll just come like a shield tanker. There are
companies who are in that space competing with Credo.

Analyst 1:
Credo has better technology, right? Do they have an advantage or not?

Specialist:
Credo has an advantage in the sense that they have the stuff lined up.

Analyst 1:
You mentioned some of the connectors, and we know the Spectrum-X switch is coming with Nvidia,
and they're trying to integrate that. Is that a big deal? Who is that going to impact?

Specialist:
On the networking side, the next front end for networking today is 100T fabric, which is currently just
getting deployed, and Broadcom is the only vendor which launched Tomahawk 6. They launched it in the
month of June, July. They are also going through their initial teething problem because the 100T fabric,
which everybody would be launching with the likes of Spectrum-X and so will be Silicon One from Cisco.
This will be the industry first switch for everybody where the 200Gb IOs will be deployed in the industry.
Definitely, as the industry takes a transition from 100Gb to 200Gb, the industry will see teething
problems associated with these connectivities and the IOs. Arista and everybody are using today
Tomahawk 6. Spectrum has already taped out their 100T fabric and so is Cisco.

I would anticipate in the first quarter of next year, a lot of these vendors will be announcing their 100T
fabric in the industry. That would be a turning point for scale out where 100T is required, and this will be
the first time where the switch fabric will be aligned to the AI requirements and have features which are
associated with UAC. Those features are basically the LLR, credit-based flow control and dynamic load
balancing, which are the three key features which are needed for AI type of infrastructure, where the
packets are more very sporadious (ph) and I would say, high bandwidth requirements are needed over
there. Scale-out is basically geared for the next generation. All major vendors with the likes of Microsoft,
Google, Meta, all will be using these classes of fabric. The China customers would not be using it
immediately because there's technology limitations in China. They would take at least another, I would
say, 12 months to embark on the 100T fabric.

Analyst 1:
We understand Arista is doing the pluggable optics, and they won't be able to scale after 1.6. Are you
familiar with Celestica? What about Axon? Is Arista going to gain or lose share relative to Spectrum-X?

Private and confidential

7

AI Data Centre Industry 每 Nvidia, Astera Labs & Broadcom 每 Former Senior Executive, Product Line at
Broadcom Inc 每 3 November 2025

Specialist:
That's a good one. Arista basically is heavily relying on Broadcom. Basically, Broadcom does over USD
1bn of business through Arista. Most of the silicon is done by Broadcom and given to Arista. Arista has a
very strong hold on companies like Microsoft. To some extent, they have a hold even at Google. Having
said that, the silicon is not designed by Arista, it has been designed by Broadcom. On the other side,
Spectrum, which is coming into play, Spectrum gets fully integrated or vertically integrated into the
Nvidia rack, the DGX rack, which comes through.

All of these companies buy these high-performance training platforms. Nvidia is not selling individual
components. They sell the whole cupboard, the whole closet. Spectrum basically sells by default into all
of these boxes. Customers don't get a choice of replacing the Spectrum with Arista or with any Broadcom
silicon over there. In that sense, Nvidia fully dominates and really doesn't cares about Arista's
dominance or Arista's presence. Arista actually has a huge disadvantage. The biggest disadvantage
Arista has, since it doesn't own the silicon piece of the solution, a lot of the margin goes to Broadcom.
They are not able to leverage that.

They don't have the whole price holding as Spectrum, whereas in case of Nvidia, since they're vertically
integrating and they own the silicon, they own the whole ecosystem and the whole food chain, they have
the full control on the entire margin and their business is more profitable compared to what Arista is
seeing today. Arista is a little bit handicapped in this race in the long-term because they don't command
the whole ecosystem. The main piece of the pie is the optics and the switch silicon. They don't have
either one of them. They license their optics from optical vendors. They don't do internal development,
and they do not do internal development on silicon side. Whereas the likes of Cisco and Nvidia are doing
both. Cisco does the silicon, Cisco has the optics. Nvidia also is doing their own optics. Nvidia has been
investing a lot on the photonics side and on the optical side to make their own modules and their own
CPU engines plus they have the silicon side. In terms of matching Arista with Spectrum, Spectrum will
take the lead, if not today, it's imminent in the future. You're seeing Spectrum being circulated into a lot
of these accounts today where they were not there before because through brute force＃

Analyst 1:
Our sense was that Spectrum is more of the backplane of connecting GPUs, whereas Arista and other
networking vendors are more outside of that closet. Is that right?

Specialist:
By the way, Spectrum-X is both. It has an Ethernet switch and it has the NVLink switch. The NVLink
switch is the internal side where the GPUs are getting connected. They have two variants. When it comes
to the inside of the stuff, it is mainly InfiniBand and the GPU connection, which is NVLink, and that is
port limited to whatever their rack architecture is. They have a full variety of scale-out Ethernet
switches, too. In fact, Mellanox made a very bold move in the past four years where they started making
Ethernet class of switches. Today, they have 51T Spectrum-X switch on the Ethernet side, very much
similar to what Marvell has on Teralynx, very similar to what Broadcom has on Tomahawk 5. Tomahawk
6 is 100T and Spectrum will come out with a 100T fabric for Ethernet too. In fact, they are dominant in
both the areas today, Ethernet as well as the scale up.

Analyst 1:
Are there any PCB [printed circuit board] vendors or substrates you feel very good about for
components?

Specialist:
Normally, we go to DNI, Acton, Jabil, Celestica, these are recognised vendors. The reason why we go
there more than the PCB material, we look at the supply chain and their credibility to provide us with the

Private and confidential

8

AI Data Centre Industry 每 Nvidia, Astera Labs & Broadcom 每 Former Senior Executive, Product Line at
Broadcom Inc 每 3 November 2025

stuff when the demand is very high because these demands are very sporadic. There's no predictability.
Sometimes the demand will just skyrocket and suddenly some hyperscaler will just double his demand
for that particular quarter. We need to go with a PCB vendor or an ODM vendor who's able to scale and
provide us that runway. These four are very stable, and they're able to meet our demand in a very short
notice.

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



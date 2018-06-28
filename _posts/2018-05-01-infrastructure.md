---
layout: post
title: "Bootstrapping Infrastructure in the Public Interest"
permalink: infrastructure-for-good
author: Andrew Lovett-Barron
description: Bootstrapping and Disaster Relief Tech
comments: true
tags: [social venture design, newamerica, research, ldln, casestudy]
image: '/images/posts/ldln.jpg'
---

## "You are not connected to a network."

When flashed across a screen on any range of devices, these words often describe a bottleneck to the work we  were trying to get done. For thousands of New Yorkers in 2012, this barrier came with the torrential rain and devastation wrought by Hurricane Sandy. For millions of victims and first responders of natural disasters since, it represents a barrier to contacting loved ones, discovering safe zones, tracking relief efforts, and simply staying updated.

From their volunteer relief efforts with Occupy Sandy, [Chris Guess](https://medium.com/@cguess) and [Matt Grasser](https://medium.com/@msgrasser) felt like they could see some better options for at least part of this puzzle. Chris had watched a friend of his move from distribution point to distribution point recording inventory surpluses and deficits, and then spend long hours filling those into an excel spreadsheet that had to be uploaded over satellite phone only to become a bottleneck for getting resources where they needed to go.


## Making Something Good

Chris and Matt had started playing with an idea around networking for a month months, and came together for a disaster relief hackathon for Typhoon Haiyan in the Philippines. They used this as the opportunity to build a small team with co-founders Nick and Emily around the project idea, and the nascent form of LDLN came into the world.

LDLN is an open source software and pseudo-mesh networking framework for ad-hoc networking between consumer devices in austere situations. If there's no internet or cell service, LDLN and its suite of tools provide high quality data collection and synchronization across devices via low-cost base stations. These base stations are often Raspberry Pis: small sub-$25 computers that can run sophisticated server and networking software, as well as host databases and similar. If this base station is connected to a broader internet via satellite or hard wired connection, then it can be synchronized further up the chain.

First responders and logistics teams engage with the software by configuring the systems to the needs of that responds scenarios: gathering appropriate mapping and tabular data. Individual responders run the software on their devices to collect data offline, and when they come within range of a base station, this data is automatically synchronized with the other responders findings and work.


## Making Something Last

LDLN has been around in a slowly iterating form since 2013. Instead of being a non-profit or a strictly a for-profit entity, Matt and Chris chose to incorporate under a Washington Benefit Corporation, or "Social Purpose Corporation" (SPC). Washington SPCs are structured such that they provide protections to company executives in pursuing social goals that might be counter to the fiduciary duties of the corporation. While a traditional C corporation's officers are bound to pursue better fiduciary outcomes as a responsibility to their shareholders, an SPC may consider the broader social outcome pursuant to their mission.

Matt and Chris took the perspective that investment was a potentially threat to the intent behind their work as a social good. A strictly for-profit entity might make their technology and more attractive to traditional venture capital investment, but comes with it a necessary shift in mission as investors might drive them towards more profitable markets tangential to their primary goals. Non-profit structures come with their own needs: for grant application, for compliance, and similar. Additionally, grant seeking in the non-profit space (especially at the time of LDLN's inception) is often insufficient in both capital and flexibility for the scope of activities around which LDLN was being built.

In the software and product work, **Bootstrapping** is a business and product development approach where founders invest their own time and resources in building up a product. Their investment of time in exchange for "sweat equity" (often actually represented as shares in a company, but really it can be any number of things) builds something that –hopefully– starts creating value on its own, thereby -hopefully- bypassing the need for external investment. Bootstrapped companies are often slower in their growth than venture-backed businesses however, so in many cases the slow growth curve of a product can be a risk as they compete with others for adoption and market share.

The LDLN team made a conscious decision to apply the bootstrapping model in the social good space. They stuck to the value-first lens with which the organization had been started, and chose to slowly incubate the product over time as they built the product up over evenings, weekends, and between contracts in their independent work. 

While professing that Bootstrapping has provided them incredible freedom as an organization, it comes with its costs. Matt and Chris shared stories of hopping on a plane to give a demo for public sector providers or humanitarian organizations, only to not see any effective follow up. Substantial interest in the tool itself was not matched by technical capacity in public and civil sector organizations, and so the open source promise of the tool fell short when confronted by internal inability to implement the freely given technology. Similarly, because of the procurement processes that have metastasized within many public sector organizations, LDLN's team was ill equipped to deal with the multi year or even decade long cycles that might be be involved in selling to governments.

Unfortunately, this economic uncertainty around a high-value tool caused some attrition in the team. Some members had to take on full time roles and reduce their involvement in the tool itself, or other financial stressors (in some cases positive, such as two of the team members getting married) affected the product's develop. But Matt and Chris have both continued building the tool, and with that continued bootstrapping, they have managed to connect with some important communities, including a FEMA-funded Field Innovation Lab, Geeks Without Borders, and NextDayBetter. 


## Lessons for the Bootstrapping Social Entrepreneur

Here are three things that all social entrepreneurs should take from LDLN's example as they set out on their own enterprises.

### 1) Every enterprise is a balance of forces that influence the product vision
The LDLN team recognized this from day one, and made a series of thoughtful decisions that managed their growth and scope to protect that the vision they held for the product and its sphere of influence. While this decision limited options and growth from a business lens, it led to a coherent and valuable product for users and those the LDLN team hoped to positively impact.

### 2) Sometimes a side-gig is sufficient or even preferable
Sometimes, a product does not need to have a full-time team around. When a team decides to go full-time on product development, the product must somehow support that time. That is often where venture capital or grant funding comes into play as a product grows to encompass the needs of the team around it. By bootstrapping their product, the LDLN team allowed the product to grow according to the demand and need for the product in the market, as opposed to forcing the product to grow to meet the growth needs of the business.

### 3) Bootstrapping unlocks the right time, place, and partners
LDLN is a tool that is used and tested in situations of austerity and often profound distress. And one of the challenges of disaster resilience is that preparation is necessary both in the tool and in the community around the tool. By bootstrapping and encouraging resilience in their own practice, LDLN built a tool that can be deployed anywhere, can be deployed quickly, and importantly has the right network of partners in the form of local agencies, open source contributors, and former project members to jump into action when it's needed.

## Slow Burn Social Innovation

In the disaster resiliency space, sometimes the right tool is the one that is around when you needed it, but spends most of its time on the shelf. I've kept in touch with Chris since the interview, and learned about some of the work that he did building [technical infrastructure in relief work in Rockport, Texas](https://medium.com/@cguess/spreading-the-word-9dcfe92c958b). LDLN is a standing example of the "slow burn" social innovation tool. Perhaps there isn't a business model now, and perhaps its time isn't even now. But the work is worth doing and worth pushing until such time as it can be applied in service to others, and in times like that, dedication to the mission and a thoughtful application of a bootstrapping model comes into its own.
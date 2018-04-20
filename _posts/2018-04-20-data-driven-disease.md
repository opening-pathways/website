---
title: Data-driven disease
author_profile: true
author: Dana Lewis
layout: single
permalink: /data-driven-disease
comments: true
---

I was recently describing to a reporter why I think some of the lessons we’ve learned from [OpenAPS](http://www.OpenAPS.org) & related diabetes efforts can be applied to other health communities. “Although diabetes is a data-driven disease,” I said, “I think there are --.” The reporter interrupted me and asked, “What do you mean by data-driven disease?”

I realize, based on that question, that while it’s an intuitive concept for me, it’s not necessarily so to someone who isn’t familiar with how people with diabetes must use data to help decide dozens or more times a day what to do in order to keep ourselves alive.

### Here’s an example of the math a person with diabetes (PWD) has to do:

Take the current blood sugar (aka blood glucose, or “BG”) level - let’s say it is 140 mg/dL. If the target is 100 mg/dL, a person with diabetes (PWD) has to calculate how much insulin to use to bring the BG to target. The person applies their insulin sensitivity factor or “ISF” or “correction factor” to the number of point the BG needs to be adjusted by. If the ISF is 40, e.g. 1 unit of insulin brings the blood sugar down by 40 mg/dL, then to correct from 140 mg/dL to 100 mg/dL, the BG must be adjusted by 40 mg/dL, and therefore the person should take 1 unit of insulin. However, there’s often residual insulin “on board” from previous doses, as well as impacts of food (carbohydrates), which also are taken into account, so the math, while simple overall, can become more complicated when everything is factored in. This is why having a computer do the math and make adjustments every 5 minutes (a la OpenAPS) is nice!

Because PWDs are used to testing their BG either with a fingerstick or getting it via a continuous glucose monitor (CGM), it’s a data-driven process to decide what to do, and when to do it, in order to achieve optimal results (BG levels in range).

### How might we help other conditions become more data-driven?

Not all health conditions are this obviously data-driven, but I believe more of them could become data driven. 

One of my big learnings from my original DIY diabetes work ([with my open loop system, “DIYPS”](https://diyps.org/2016/05/12/how-i-designed-a-diy-closed-loop-artificial-pancreas/)) was how impactful it can be to take the same information that’s locked on my existing medical devices, and [displaying it together](https://diyps.org/2015/11/06/the-power-of-visualizing-your-data-your-way/), in real-time, in a more meaningful way to me. I theorize some of the same improvements can come to other people living with health conditions, who may have data locked down in devices. Or, people may not be able to track necessary data because it’s previously been too burdensome to track, or it’s frustrating to do when there’s not an obvious real- or near-real-time use for it. 

It may not always be real-time like it is in diabetes, but near-real-time, daily, weekly, monthly, or even seasonal display and trends and visualizations can be incredibly helpful for understanding and discovering new patterns.

In fact, that is one of the long-term ripple effects I predict we will see out of our [Opening Pathways project](/about): as more people are able to scale and share their work, we’ll continue to discover simple ways to tie tools together; visualize existing data in meaningful ways; find non-intensive methods for capturing or recording additional relevant data; and build new easy-to-use tools that drastically improve the quality of life for people living with health conditions. 

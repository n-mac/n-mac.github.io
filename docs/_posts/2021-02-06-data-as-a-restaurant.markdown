---
title:  "Data as a Restaurant"
date:   2021-02-06 13:30:00
categories: [data]
tags: [analogies,frameworks]
---

I tend to make sense of complex concepts through analogies, and I tend to use food as the basis for most of my analogies. So to kick off my blog, I'd like to share an analogy that I come back to time and again when considering the many different elements of a successful data organization: The Data Restaurant. 

Imagine having a meal at your favorite restaurant (if you can remember what dining out was like in a pre-COVID world). As a patron, you're probably enjoying the tasty food, the excellent service, the ambient atmosphere - it's great. You're probably *not* worrying about the many behind-the-scenes efforts that went into sourcing and making that meal, and if you were, it probably wouldn't be your favorite restaurant. You're there for the output (the meal), not the process. 

Now, anyone who's worked in food service (*raises hand*) can tell you that "the process" in an industrial kitchen can range anywhere from a chaotic shitshow to a well-oiled machine. So as data practitioners, how can we use some food industry wisdom to make the Data Restaurant a successful establishment with happy customers? 

Let's draw some parallels!

| Raw ingredients | get transported | to kitchens  | to be transformed | into meals  | served to customers |
| --------------- | --------------- | --------------- | ------------------------ | ----------  | ------------------- |
| *Source system data*|*gets ingested*|*into data warehouses*|*to be transformed*|*into reports + analyses*|*for business users* |
| ***Business users/IT***| ***<span style="color:green">Data Engineering</span>***  | ***<span style="color:green">Data Engineering</span>/<span style="color:red">BI</span>*** | ***<span style="color:red">BI</span>/<span style="color:blue">Business Analytics</span>***  | ***<span style="color:blue">Business Analytics</span>*** | ***End users*** |

- **Every player in this process is critical, and a little specialization never hurt anyone**: 
    - Some activities are closer to the customer, some require a highly specialized skillset; they're all necessary. And they're rarely interchangeable. You wouldn't want your waitstaff to be behind the grill any more than you would want your head chef to be farming your produce. 
    - There are certainly data roles that have a significant amount of overlap, but don't be surprised if you get sub-optimal results after asking a data engineer to pump out dashboards. Don't get me wrong, I'm a believer in having roles that span across traditional job descriptions, particularly in a startup or a company with a relatively small data team - you have to be nimble! But ideally it should be a conscious decision rather than a circumstantial burden, and it should come with the necessary training and support systems to pave the way to success. If you have a data viz developer who wants to get more involved in data modeling (or needs to, due to capacity constraints), pair them up with a seasoned data engineer or find external resources to help them be successful. "Being good at data" doesn't mean someone has expertise along every part of the process.
- **Roles and titles may correlate to different responsibilities in different settings**: 
    - A successful sushi chef at a high-end restaurant may not flourish in a fast-paced walk-in TexMex joint. Do certain roles have implied transferable skills? Absolutely. I'd wager a guess that any chef, in any restaurant, has decent knife skills; any front-of-house staff knows how to deal with difficult customers. But knife skills do not a chef make.
    - A title can only tell you so much - what's more important are the skills and experiences that each person brings to the table. One company's solutions owner is another's business analyst; one company's business analyst is another's data viz developer.
- **Regular customers make the world go round**: 
    - A restaurant needs regulars - not only do they bring repeat business, but they bring in new business by telling their family and bringing their friends.
    - A data org needs evangelists, and that comes in the form of business users who are able to gain insights without a heavy lift. They accelerate adoption by bringing their coworkers and teams along with them. And having an exec team that's invested in data/actively leveraging the data org is like having a great review by a food critic - the masses will come. 
- **...but the customer is *not* always right**: 
    - What would you say to a customer asking for medium-rare chicken?
    - Part of a data org's responsibility is understanding the question behind the request. I can't tell you how many times a stakeholder has asked me to build something specific, and won't even entertain alternate suggestions on how to answer the same question through a more optimal delivery method (dashboard instead of spreadsheet) or approach (. But hand that stakeholder a prototype and they're on board. Sometimes people are more confident in the fact that they know what they want, than they are in what they want. So yes, give the people what they want...unless it's a dashboard full of pie charts.
- **Branding matters**:
    - What is the experience that you want to provide to your end users? Is it a highly curated data experience? Because if so, it better be damn good quality and address the needs that are most in demand (no one is paying for prix-fixe waffle fries and deviled eggs). Are you hawking self-service analytics (think buffet)? You need to provide strong building blocks with an intuitive interface to make it easy for end users to build whatever combination they need (stock the salad bar with the staples and put the bowls next to the soup).

Like many others, I got my start in analytics as an enthused patron of the Data Restaurant - I was a data-obsessed business user in a highly data-driven company and I wanted to learn more about how the sausage was made. The data space is constantly evolving but I imagine there will always be parallels with the service industry. Just one woman's thoughts!
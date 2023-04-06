---
author: Phil Whitehouse
title: Here comes the Customer
date: 2008-04-14
description: VRM
---
I’ve been thinking a lot about VRM lately. Not so much about what it means, but rather the mechanism of how it can work.

If you’re new to VRM, it can be summarised like this: it’s the reciprocal of CRM. Rather than being bombarded with advertising, much of which is irrelevant, and the rest irritating, wouldn’t it be nice if you could just tell vendors what you want, on your terms? Without even going to the trouble of looking for them? If they’re willing and able to respond, they do so. Everyone else goes on their merry way. It’s all about sharing the data you want with the people you want.

Some examples from Doc Searls (Cluetrain Manifesto dude), who heads up the VRM project, include:

> I want to:
> - Buy a power convertor near St.Paul’s in the next three hours, at any price
> – Buy a stroller for twins near Highway 70 in Kansas today for under $300
> – Buy an Apple laptop with a 500gb HDD and weighs under five pounds, as soon as it comes out
> – Buy a double decaf cappuccino at the next exit on this highway

(You can see more examples presented by Doc on [this photo](http://www.flickr.com/photos/philliecasablanca/2413485646/))

There are a few big problems that need solving. Filtering is one (both on the outbound request and the way back in), targeting is another (how do you choose which vendor to share your data with?), organisation is a third (by what mechanism do customers agree to share their data, and in what form, while retaining control over it?).

I’m wondering whether the following solution might have some mileage.

## Possible solution

I’m wondering whether most of the problems could be solved by defining the terms by which we, the customers, could engage with brokers that we chose. **Brokers = any directory service which is willing to accept the data on our terms.** After all, the likes of Google, Yell, Yahoo! and Thompson already have a relationship with thousands of vendors. We could offer to share our wish list with e.g. Yell, on the grounds that they’ll pass it onto vendors who meet our criteria, and gather / return the results.

How brokers manage the relationship with the vendors is their challenge, but they’d have a vested interest in ensuring a high quality response to the customer – otherwise the custom will go elsewhere. As for their motives, I imagine brokers could make money out of this by agreeing with vendors which customer queries are forwarded onto them, perhaps based on keyword. Maybe this could work in the same way as Google Adwords, where vendors pay to have ads next to chosen search terms, only instead they get carefully targetted, customer-generated requests.

The customer could receive a confirmation that their request has been passed onto x vendors. Responses could be penalised if they don’t match the request, rather like Amazon encourages customers to rate sellers in their marketplace. Low scores are punished, to prevent spamming.

The number and quality of the responses would be poor to start with, as customers might not be too good at defining their requirements, and vendors try to game the system. But like any new system, the filters would improve over time improving the system for all.

## Obvious problems

1. Hosting the original data is a problem, because customer control is one of the keys to success. Maybe [TiddlyWiki](http://www.tiddlywiki.com/) could help with this? Data could be held locally, new brokers could be managed via plugin, and data can be sent / retrieved via RSS. And it passes the ‘open standards’ litmus test.

2. Defining the form of the customer’s request is problematic. From the above list, we’ve already seen that requests can be incredibly wide-ranging. At minimum, a free text field is required for the bulk of the query. But I think tags should play a part (as this would make the broker’s life easier, matching tags with the terms they’ve ‘sold’ to vendors). And time / location / radius probably need to be defined to some degree, to help tighten the request and responses.

I don’t know much about establishing standards. My erstwhile colleague Paul Downey, on the other hand, represents BT at the W3C and thus knows a bit about standards. He sez this will be a hard problem to crack, and he’s probably right. Big question: to what extent would we, the customers, allow brokers to help create this standard?

My view is this problem needs to be overcome before VRM can move forward, regardless of whether brokers are involved.

But why bother? Well…

## Who wins?

Everybody wins. The customer gets carefully considered responses to their request, with minimal effort. The broker gets paid by the vendor for the targeted information. And the vendor can spend more money dealing with useful leads rather than on frivolous, scattergun advertising.

Incidentally, I’m convinced that VRM will be here one day. Customers’ ability to organise themselves is only going to increase over time, as social tools become more powerful and elegant (quick nod of the head to [Clay Shirky](http://www.amazon.co.uk/Here-Comes-Everybody-Organizing-Organizations/dp/0713999896/ref=pd_bbs_sr_1?ie=UTF8&s=books&qid=1208179787&sr=8-1)). It’s a question of when, not if, this power will eventually fall into customer’s hands.

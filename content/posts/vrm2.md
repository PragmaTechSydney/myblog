---
author: Phil Whitehouse
title: VRM - Collectively immense
date: 2009-03-04
description: Braking the stranglehold
---
After last week’s VRM meeting, I’ve been pondering the merit of my [Personal RFP model](/posts/vrm/). Again, the notion of a broker (especially a powerful one, such as Google) was unpopular, but no-one suggested a better way of getting to a point where a network of individuals can support the model.

So I’ve been mulling over a variation on the theme. Could we create a social network which replaces the broker?

I think we could. I’ve looked at the roles the broker would’ve played and tried to figure out if the abstract notion of a social network could play these roles instead;

* access to large volume of vendors
* filtering RFPs on the way TO vendors
* filtering RFPs on the way FROM vendors back to potential customers
* aggregating recommendations and ratings

I believe that a social network could manage all of these roles using the same mechanisms as wikis (with their low cost of repair, and therefore low level of vandalism), combined with Amazon’s model of recommendation (where recommendations planted by those with vested interests are lost in the collective voice of genuine feedback). And a crowd sourced system of classification.

Neither wikis nor Amazon’s recommendation system are perfect. But they have all proven to be Good Enough.

Let’s look at those roles, starting with accessing large numbers of vendors. We all have our favorite vendors, but without an immediate incentive I can’t see customers alone getting enough vendor data into a system to get sufficient critical mass. But perhaps we could reach that point by scraping data from somewhere? Could be a variety of sources, starting with the Open Directory (update 7/3/23 - link dead) (which is somewhat out of date, but hey you’ve got to start somewhere). This, combined with a way of allowing vendors to edit their own details (with a system of take down and lock down in place, a’la Wikipedia), could work.

Filtering on the way in and out of the system could be handled algorythmically. They could be based on location (given radius), keyword (e.g. carpenter) and rating (minimum that the customer is interested in). Perhaps some level of semantic analysis if we’re feeling clever. My suggestion here is that we start with something basic and open source-it, so that we can constantly improve results based on what we’ve learned, as well as drawing in talented people.

Actually I envision that this whole project would need to be open sourced. No security-by-obscurity here!

For the recommendation engine, I’ve already highlighted Amazon’s model as being the most effective. And I think customers would be far more likely to contribute back their reviews and ratings to a system which is neutral than to one which is commercial.

Which leads us to a business model. Hey, it’s 2009, we don’t need no stinkin‘ business model! Only (half) joking. But seriously, I believe a platform like this could attract advertisers. I’d prefer to avoid charging customers and vendors for using the system, certainly at the beginning. Customers will never be charged of course, but I think vendors would need to see the value in the system before accepting a small charge towards upkeep of the project. I’d prefer to keep investors out of it, if possible.

So the final stage in this very rough analysis of using a social network as a broker is to rationalise it against the evolving [VRM principles](https://cyber.harvard.edu/projectvrm/Main_Page#VRM_Principles). Does it tick all the boxes?

1. Relationships are voluntary.
2. Customers are born free and independent of vendors.
3. Customers control their own data. They can share data selectively and control the terms of its use.
4. Customers are points of integration and origination for their own data.
5. Customers can assert their own terms of engagement and service.
6. Customers are free to express their demands and intentions outside any company’s control.
Boxes 1, 2, 5 and 6 are ticked.

Re: 3, if a customer shares their data with a system, and allows that system to share the data with multiple vendors based on a publicly available algorythm, does this count as still being in “control”? What if the terms of this use are defined by the network of customers, rather than just by the individual? Could we evolve the system further down the line so the customer can define their own algorythym? I like to think so.

Point 4 is a little tricky. Customers would obviously be the point of origin, but given that the filtering and forwarding is happening on a distant server, is the customer still a “point of integration”? My feeling is that this obeys the spirit of the principle, if not the letter. Again, it would be an open system and subject to the same scrutiny as the best open source project – which I think would give the customer the transparency they need to decide whether to trust the system in the first place.

Lots to mull over.

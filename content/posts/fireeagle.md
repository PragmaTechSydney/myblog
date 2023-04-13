---
author: Phil Whitehouse
title: Fire Eagle Has Landed
date: 2008-03-05
description: Platforms
---
After many moons and much fanfare, Fire Eagle, the new location service from Yahoo!, was launched today (in development beta, at least). I’d been really looking forward to this, because they’re tackling a bloody hard problem, and it was looking as though they’d cracked it.

Expectations and hopes were very high. Location Based Services (LBS) have been the holy grail for mobile telcos and web developers for a long time. Many have tried and all have failed.

The first big problem with LBS is finding a reliable way to plot location to within a few feet. And this explains why, up until recently, finding an LBS solution has been a mobile telco problem; after all, your mobile phone follows you around. It’s this degree of accuracy that can bring really useful information, such as guiding you to a cashpoint. But very few mobile devices have GPS, and the telco companies can usually only figure out where your nearest cell tower is (called a Cell ID) which could be miles away. Triangulation is a non-starter because you’d need line of sight and clear weather between you and the towers to makes assumptions about distance based on signal strength.

The second big problem is privacy. Most people have a complex answer to the question “Who do you want to know where you are?”, and it depends on unpredictable, ever changing circumstance.

So when I saw Tom Coates (of BBC and now Yahoo! Brickhouse fame) demo Fire Eagle at FOWA last October, it seemed to handle both problems really elegantly.

First, it accepts location data from just about anywhere including the aforementioned Cell ID and GPS, a texted postcode from a phone, a known wi-fi hotspot I come into range of, my entering a location on a web page, via a Facebook app), with **new location factoring methods welcomed**. Fire Eagle takes all the location data you throw at it, will plot location on a map as best it can (regardless of accuracy), and share that with whatever application you choose. And the service will improve as new and better location input capabilities are invented and added. If I want to broadcast my specific location, I can find a way to do so, and Cell ID can pick up the rest of my movements.

Second, the privacy settings looked great. They’ve given this a lot of thought, and there were several very simple controls for selecting when you’d want to share your location (with dead easy ways to stop sharing immediately). The nicest feature I saw was being able to select a region which, when entered, your location would be set at town or borough level. So e.g. no-one knows exactly where you live.

I found out this afternoon from Salim Ismail (former CEO of the Yahoo! Brickhouse) that they’d had to rebuild much of the Fire Eagle service from scratch relatively recently, so I wasn’t sure what to expect. Here’s a couple of screenshots [on Flickr](http://www.flickr.com/photos/philliecasablanca/2313375070/sizes/l/in/set-72157604050911574/).

Much of the functionality seen at FOWA isn’t available yet, they’ve decided to release it so that developers can play with it. It’s a shame the privacy features didn’t make the cut for this beta release. I can temporarily hide my location though, so at least that’s something. I also think it’s a bit of a shame that they didn’t launch with any of the application widgets live, although I guess that will change soon. I imagine they were under huge pressure to hit this delivery date, especially due to the [current climate](http://www.techcrunch.com/2008/03/05/yahoo-is-still-looking-for-a-white-knight%e2%80%94news-corps-offer-does-not-pencil-out-neither-does-aols/).

But the HUGE plus point is that, finally, developers can get their mucky paws all over it. I can’t wait to see what people come up with. Yahoo! have taken an incredibly complicated problem, and come up with a simple, engaging solution (assuming the FOWA functionality eventually makes the cut). And it looks gorgeous as well. Every single Telco in the world has tried this, spending probably billions of US$ in the process, and the Brickhouse team have come up with the goods.

I think this is the most exciting development to happen in our space so far this year. What do you think?

---
author: Phil Whitehouse
title: Transitioning from Umbraco to Jamstack
date: 2023-02-09
description: Website update
---

![Jamstack illustration](/img/jamstack.png)

I've refreshed my [business website](https://pragmatech.sydney/) today, which normally wouldn't be too much cause for celebration as the content itself hasn't changed - but some interesting stuff has gone on under the hood so I thought I'd capture it here.

There were a few key reasons why I needed to change platform. When I built the site originally in 2020, I selected Umbraco Uno as the managed service provider because I knew how to use Umbraco CMS and the front end was configurable enough for me to meet my fairly basic needs (range of modules, blog, contact form, that kind of thing). The price was fair and it got me off the ground quickly.

But the shine came off in the months that followed. It turned out that Umbraco Uno websites are hosted in Belgium (no local caching), which meant the site was pretty poor performance wise when visiting the site from Sydney. And then a few months ago they announced they were discontinuing the Uno managed service altogether, giving me a couple of years to find another solution.

Long story short, I've moved across to a Jamstack solution which is blazingly fast and free to host. For those new to Jamstack, it's an elegant software stack that enables you to quickly build and deploy [a highly secure static site in the cloud](https://jamstack.org/why-jamstack/). Anything you need outside the website is accessed via APIs. You don't even need a CMS if you don't want one. Here's how it was done:

* First, I had to pick a responsive template. I used a free one called [CoHub](https://jamstackthemes.dev/theme/hugo-cohub/), which gave me a lot of what I needed.
* With support from front end legend Chris Jerochim, I learned how to manipulate the static site generation process. Was a bit challenging, but got there in the end. It's a folder structure with written content, configuration settings, style settings and images. I'm writing this blog post directly into my text editor, Atom, which means I don't even need a CMS.
* I then needed a deployment platform. I chose [Netlify](https://www.netlify.com/) as it's reputable and deploys static sites in [dozens of locations around the world](https://answers.netlify.com/t/is-there-a-list-of-where-netlifys-cdn-pops-are-located/855) (including Sydney). Their basic tier is free, and they also provide a free tier for forms which I can use for my Contact Us form.
- Finally, I needed to set up a deployment pipeline. I use GitHub as my code repository and then Chris helped set it up so any deployments into GitHub trigger a build in Netlify. I have a desktop tool called [GitHub Desktop](https://desktop.github.com/), I press two buttons there and my changes are deployed.

So, to recap: a free template, a free text editor, a free code repository, a free deployment pipeline, and a free hosting solution with a free form functionality. And the end result is a responsive, secure, highly performant website that (I think!) looks smashing.

Huge credit is due to Chris Jerochim, without whom I wouldn't have got very far!

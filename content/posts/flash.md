---
author: Phil Whitehouse
title: Flash vs Javascript
date: 2009-07-27
description: Don't pander to reactionists
---

I know what you’re thinking. There’s a gazillion blog posts on the web arguing about Flash and Javascript. So why write another one?

This one is slightly different. I work in a commercial, competitive environment where there is strong opinion both sides of the aisle. And a mix of clients (doing good work, like the NHS) actively seeking to use both technologies. And strangely enough, a sort of consensus is starting to form. So I’m going to try and capture that consensus and share it here. No doubt colleagues past and present will put me right!

The consensus is that we’re going to use [open web standards](http://www.w3.org/) (HTML, CSS and Javascript) wherever possible and practical, for the following reasons:

* Easy to optimise for accessibility
* Easy to link to specific content (each page has it’s own URL)
* Easy to copy particular text for pasting elsewhere
* Easy to optimise for search engines
* Easy to subsequently change and maintain code
* Works on all devices, all browsers (unlike, say, Flash on an iPhone or Wii)
* No need to download plugin or application
* No dependance on an external vendor
* Ability to view source (supporting the education of development communities)

HTML, CSS and Javascript are the building blocks of the web, and we want to contribute to the ongoing improvement of the web wherever we can. Some of the above is possible when using Flash, but rarely used (especially where budgets and resources are limited) and difficult to implement.

BUT! The challenge comes when we want to do something that *isn’t practical or possible* using open web standards.

I think it’s OK to use Flash when:

* We’re streaming videos or music. This is the only way to get this stuff out to a wide audience (at the moment)
* We’re creating complex, interactive, immersive (maybe 3D) environments. These could include animations. To some extent, this is possible using web standards, but only with a *greatly increased build time*. This is the key: persuading someone to pay for this is a different prospect to a lone developer dabbling with the technology in his or her own time. Depends on how much more expensive it is, of course – but we’ve got to be practical. If we go down this route, we MUST still make the information accessibility compliant, linkable and available for search engines to spider.
* We want to create effects that can’t be created using open web standards. In this instance, it’s still essential that the experience degrades gracefully. We’re talking about design-led flourishes that enhance the mood of the page – but leave the content untouched. If someone visits the page who hasn’t got flash installed, they’ll be none the wiser – the same information will be accessible in the same way. The Team's home page (since changed) is a good example – for those who have Flash installed, the characters at the bottom move around. For those who don’t, they’re static hyperlinks. There’s something to be said for beauty on the web, and sometimes that beauty will be animated.

The open web standards crowd (including many friends) may gag on these points. But I think the above is a practical compromise. It is inclusive and recognises the fact that cutting edge front end development is time consuming. If something takes much longer to design and build using web standards, then we’ll be pushing work away if we don’t compromise. We work in a highly competitive industry, and it’s easy to be idealistic when you don’t have to worry about commercial considerations.

All that said, we actively seek opportunities to innovate using javascript libraries and emerging technologies – within those commercial limitations.

In a large team, working with a complex client, there may also be political issues at play. Does the client have the expertise to maintain complex code? Are the people crafting the user experience sufficiently skilled to understand what javascript can offer? In the real world, these are all factors that will will inform the decision.

What about when clients ask us to build something in Flash? We will inform them of the risks. We won’t turn down work if they insist on using Flash – the alternative is that they’ll go elsewhere, and we won’t be able to work on converting them! And, yes, if we do the work, we’ll get paid. Without our customers, we’ll go out of business.

I’d love to hear views on this, particularly where there are other situations where one would make an argument for using Flash. Further arguments in favour of open web standards are also welcome – but do bare in mind those commercial considerations!

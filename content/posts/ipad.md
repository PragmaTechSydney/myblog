---
author: Phil Whitehouse
title: Publishing on the iPad
date: 2010-05-31
description: A new medium for content creation
---
There’s little debate now that the iPad will be a roaring success, and customers will be demanding content via this format very soon, if they’re not already. It’s tempting to think that the design process can be inherited from traditional web design, or iPhone design, or both. There’s some truth in this, but there are also some new considerations to take into account. Publishing on the iPad is more complex than it seems, so I thought I’d share some early thoughts on how to approach this challenge.

## Range of options

There are numerous ways to get written content onto an iPad, ranging from the cheap and cheerful through to expensive and sophisticated. The right option will depend on several factors, not least of which are budget, audience and business model. Let’s start with the low cost options first:

*PDF*: The iPad opens PDF files in Mail or Safari, whether emailed or downloaded from a website, and they look pretty good there. Pinch to zoom in and out works, although it’s worth testing the specific file before release because there are some rendering issues.

*ePub*: the free iBooks application can open any document in the ePub format. Users can download the file from your website, drop the file into iTunes, and sync the file to the iPad in much the same way as music. However, getting the document into the ePub format in the first place can be a bit tricky. You can use a tool such as Calibre to convert a file from pdf into ePub, but in my limited experience you end up with a messy document (lots of irrelevant content, gaps in words, that kind of thing), and it’s far better to create the ePub document using the original software used to create the pdf.

If you need to charge for publications, but these publications will be rare or ad hoc, you might consider using a service like Lulu, which charges users to download your file and they take a cut.

*Improve your website*: If you already publish content over a website, have a quick look to see how it renders using Safari, the iPad browser. This does a pretty good job helping users view content, and your site might look just fine. Simply being mindful of how it looks could inform the publishing process, leaving you safe in the knowledge that the content looks good on all platforms.

## Applications

Depending on budget, readership, business model, the competitive landscape and other factors, there may well be justification for creating a bespoke iPad application driven by a Content Management System. Even if competitors aren’t yet publishing on the iPad, there’s a good chance they will be soon – and there’s a lot to be said for first mover advantage.

The cost and effort for creating and maintaining such an application is comparable to creating a web site – and in some cases can be even higher. So the decision making process at the start is critical to success.

One of the first considerations will be the business model. Do you charge for the application and / or each issue? What about advertising revenue (Apple have created a bespoke platform called iAd for serving adverts via applications)? What about subscriptions? What about sponsored publications? What about downloading offline versions (done to great effect in the FT app)? Again, this is an area where there will be much experimentation. As Popular Science editor-in-chief Mark Jannot says “we’ll see what the market can bear”.

This business model will inform the level of investment and, as we’ve seen, there’s a range of solutions available depending on budget. As with iPhone apps, there will be several agencies offering cheap iPad applications – but it’s essential for the savvy publisher to understand why cheap might not be best. The design process for new iPad applications requires deep thought, and it will be easy to overlook many of these key issues.

## Gestures

The iPad is truly the first of a kind. While finger based gesturing has been around for a while on the iPhone and Mac laptop trackpads, the size and responsiveness of the screen invite the user to explore with touch. And the early iPad application developers have jumped at the opportunity to explore the potential of this new paradigm.

I’ve played with a few apps (Financial Times, Wired, Popular Science, The New York Times, Epicurious, Marvel) to form these views. What I’ve found that various gestural paradigms have been explored, and the variety – the lack of consistency – across multiple apps is difficult for a user to process.

For example, the Wired app is pretty intuitive – single finger swipe to turn page – while the Popular Science app (while beautiful to look at, and lovely to interact with when you get the hang of it), has several lessons to learn before you can navigate without thinking.

Bear in mind that the previous page said “Move across for the next article >>”, and only needed one finger. So, what’s a “section”? How will I get back? It also takes 1-2 seconds for the images to turn hi-res, during which time swipes don’t work. But they’re stored up, and activate all at once when the page loads. That’s bad design. I’d love to know how they populate the Popular Science app, because from the outside it looks as though it will require a large amount of bespoke tailoring each issue.

It was interesting to read that Wired use the same software that publishes their paper version to publish their iPad version. This could prove a very interesting route for publishers when the relevant functionality in InDesign is made public later this year. I’m wondering whether the necessary simplicity of publishing the Wired app to the iPad encouraged them to keep innovative gestures to a minimum? I’d also like to know how they go about embedding video content into the application, whether this is added after the event or during the design stage. Either way, by the looks of things, Wired and Adobe have created a much simpler mechanism, and a much simpler experience as well.

On the balance of things, I’d recommend all designers to get a solid understanding of the iPad library elements provided by Apple. While various publishers are experimenting with different gestures, the ones most likely to gain traction with users are those which are most familiar – and those provided by Apple will prevail in the long term. Innovation should, of course, be encouraged but great care should be taken to introduce new paradigms with respect to the user.

## Orientation

Orientation change on the iPad is much more of a problem than with the iPhone. The smaller screen on the latter means that the width is simply increased or decreased when the screen is rotated. However, the iPad screen size allows for a more complex screen architecture meaning that it’s easier to lose where you were after orientation change. This is called ‘context shift’.

Indeed, if you’ve got screen assets that go full width in both orientations (this includes menu bars), then you have a less space for other (main) content. As you can see on the New York Times app, you’ll lose content when you switch from portrait to landscape:

In this case it’s a photo missing (see bottom right on portrait version), but I’ve seen text missing in the past.

You need to give some thought to the various states the user context may be in when they switch orientation. If, say, someone is half way through a task when they switch orientation, they should be able to resume their task without breaking stride – and this is very hard to design for. One way this can be helped is via the transition. If the exact same assets are on the screen in both orientations, and the assets don’t change size, then you can simply move each element. I expect (but don’t know) that Apple include this feature in their developer libraries – it’s not unlike the ‘Magic Move’ feature in Keynote. Of course this is a problem if you’re losing content between orientations, but the New York Times have handled this quite nicely by sliding all the panels out and then all the remaining ones back in, very quickly. It creates the impression of content being rotated, but actually replaces it. Still, the context switch is unnerving, especially if you’re reading text missing after an orientation change…

A case in point is the polished iStudiez Pro app, which is beautifully designed, but I found a problem within minutes of playing with it. When writing a lesson note, I changed orientation and the bottom of the note – where I was writing – was hidden by the keyboard.

Oddly enough, I haven’t been able to repeat the error. It goes to show that designing for two orientations, and allowing for multiple context changes between the two, creates a much larger burden on the testing programme. There might even be an argument for testing every single release of content, if the app is for Publishing. Bugs such as the one I found on iStudiez Pro will be hard to find without a rigourous test programme – and at £1.79 for the app it’s going to be financially hard to justify for smaller software houses.

## Conclusions

While it’s fun to write criticism of the early iPad applications, the fact remains that these pioneers are doing a great job showcasing the potential of this new device. The public will vote with their feet, and it will take some time for the results to come in – time will tell whether the early front runners will retain their readership, or whether the price points will need to change.

In the meantime, it’s essential for all those considering publishing on the iPad to spend some time experimenting with existing options and applications, and just as critical that designers become mindful of the vagaries of the iPad. Let’s push the boundaries without making it difficult for users. The UX guidelines produced by Apple – while excellent and compulsory – only take you so far. That said, I’m just thrilled that we get to be the generation that designs all this stuff! And the onus is on us to make sure that users get the same amount of pleasure out of using the device as we get sharing our content and design with the world.

Bonus link: Well worth checking out [Jacob Neilsen’s comments on the iPad](http://www.useit.com/alertbox/ipad.html) as well. Although given that their website looks likes it came from the 90s, you can take their design critique with a pinch of salt…

++

UPDATE 2 June 2010

More information on [how the app was created](http://laytonduncan.tumblr.com/post/640355763/bundle-diving-in-the-wired-ipad-app) (the use of images cut to 1024×768 explains why text can’t be selected, but also why each page looks so darn good), plus the [official press release from Adobe](http://www.adobe.com/aboutadobe/pressroom/pressreleases/201006/060110AdobeDigitalViewer.html).

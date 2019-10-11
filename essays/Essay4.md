---
layout: essay
type: essay
title: Semantic UI Or How I Learned to Stop Worrying and Love the Framework
date: 2019-10-10
labels:
  - Programming
  - Semantic UI
  - Websites
---

# Semantic UI? Semantic U-WHY?

Making a proper website is a very time-consuming process. To be frank, during my time at Heald College, I learned very briefly how to set up a website using Windows Server 2012. Building a proper website, however, is as different as the difference between an Ardipithecus (first bipedal hominid) and a modern human. Raw HTML, when using CSS, can really make a good website. Still, even with all that's said and done, a bare HTML site with standard formatting and style is a relic of pre-2000s internet. Even if it had all relevant information, bare HTML just doesn't grab the attention of the modern internet user and encourage them to stay on the site. Sure, changing styles can do a lot, but that's still not really enough.

That's where Semantic UI comes in. While it's still difficult to pull off and frustrating to use at times, it still can help createfunctional, attractive websites for the modern day. But it's still frustrating to use and get right.

# Where's first gear again?

The documentation for Semantic UI seems pretty confusing at first, but the bare basic thing to add is the following to the head:
```
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/semantic-ui/2.4.1/semantic.min.css">
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/semantic-ui/2.4.1/semantic.min.js"></script>
```
...and that's pretty much it, unless you want to have a local source. That is a different monkey for a different circus.

# How the heck do I use this thing?

Semantic UI is kind of like playing Junkrat in Overwatch. The kit seems pretty simple and straightforward after trying it out a bit, but there are so many ways to use it plus so many ways to mess up that there is a big enough learning curve before you can actually get good at using it. When used right, it can get the job done really well. The trouble is actually using it right. It uses natural language like this:
```
<div class="ui menu">
  <a class="item">Home</a>
</div>
```
That code alone creates a menu with a single item. For further customization, the Semantic UI documentation has several other keywords that can change the appearance and function of the UI element.

Unfortunately, like any other language, there is a pretty good chance of getting something wrong while writing using it. While some functions are stated on the documentation, some things like color, size, and other attributes may not work unless they are placed exactly in the right place.

## Now what?

Other than raw HTML and CSS, Semantic UI is pretty much the only UI framework I have used for websites. Most of my experince with making a user interface in general is from the Unity game engine and the Ren'Py visual novel engine, not for websites, so this is out of my element. However, I can honestly say that I did gain some insight into how to make an aesthetically pleasing website, which should translate nicely to other things such as desktop applications. One thing's for sure, I definitely need to get a lot more practice in if I want to make sure I actually use Semantic UI for my own personal websites.

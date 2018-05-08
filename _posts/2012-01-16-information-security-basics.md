---
id: 786
title: 'Information security concepts for activists, journalists &#038; troublemakers'
date: 2012-01-16T15:31:00+00:00
author: Jonathan Eyler-Werve
excerpt: Much attention has been given to the potential of technology to connect, empower and accelerate movements. Less attention has been given to the fact that technology also empowers the adversaries of these movements.
layout: post
guid: http://www.eylerwerve.com/?p=786
permalink: /2012/information-security-basics/
wpsd_autopost:
  - 1
categories:
  - Jonathan
tags:
  - Information Security for Activists
---
<div id="attachment_791" class="wp-caption aligncenter">
  <a href="http://www.eylerwerve.com/wp-content/uploads/2012/01/onebushstreet.jpg"><img class="size-full wp-image-791" title="onebushstreet" src="http://www.eylerwerve.com/wp-content/uploads/2012/01/onebushstreet-e1326748840665.jpg" alt="" /></a>

  <p class="wp-caption-text">
    One Bush Street, San Francisco. (image: Thomas Hawk CC by/nc)
  </p>
</div>

**Part 1 of a Series: [INFORMATION SECURITY FOR ACTIVISTS](http://www.eylerwerve.com/tag/information-security-for-activists/)**

During a recent Transparency/Accountability Initiative workshop, I led several discussions of information security for activists. During these I was told by incredibly smart leaders in the nonprofit technology space &#8212; people I really respect &#8212; that they had never given the matter much thought. This is a problem.

A bit about me: I&#8217;m not a security expert. I can&#8217;t talk shop on SSH flaws or random number generators. I am, instead, a practitioner of social ventures who cares about the people in our field. I can translate from the tech experts into usable, field tested recommendations, but to do this I depend on peer review from experts, which I gratefully invite on this and all posts.

## Prologue: Keep Calm and Carry On

There are a lot of reasons to be paranoid [1]. Our friends and allies are searched without warrant or probable cause beyond being politically active [2]. In the US, anti-corporate websites are accidentally banned without cause or recourse (Web sites of the powerful fare better) [3]. Journalists are detained at Internet cafes for attempting to file stories [4]. Email is routinely intercepted and stored by governments, without cause &#8212; in the United States, when this practice was challenged in court, Congress blocked the lawsuit and explicitly legalized the mass warrantless interception of email (Senator Obama voted yes) [5].

[<img class="alignright" title="Bring Us Victory poster" src="http://www.eylerwerve.com/wp-content/uploads/2012/01/cheerful-205x300.jpg" alt="" width="205" height="300" />](http://www.eylerwerve.com/wp-content/uploads/2012/01/cheerful.jpg)

Much attention has been given to the potential of technology to connect, empower and accelerate movements. Less attention has been given to the fact that technology also empowers the adversaries of these movements. See Evegeny Morezov&#8217;s book _The Net Delusion_ for a discussion of these issues, [reviewed here](https://www.readwriteweb.com/archives/the_net_delusion_a_review.php) and [here](https://www.nytimes.com/2011/02/06/books/review/Siegel-t.html?_r=1&pagewanted=all).

This creates conflict between privacy advocates and controlling institutions; this conflict has been slow building but is coming to a boil, particularly after Wikileaks and the Arab Spring. To quote a developer  of the TOR privacy tools (used by the US military, among other ironies), who is regularly detained at the US border:

> &#8220;The [US Customs and Border Patrol] agents in Seattle were nicer than ones in Newark. None of them implied I would be raped in prison for the rest of my life this time. &#8221; [6]

Technology is not neutral. It is not &#8220;just a tool.&#8221; All technology creates patterns of power distribution that actively tip the balance towards or away from democratic decision making, often without our intention or consent. Our urgent mission, as activists and technologists participating in the early Internet, is to proactively create, refine and distribute systems that empower the values we care about. I care about democratic participation, diversity of opinion and human rights.

So, that brings us to security for activists.

## How to think about security

The good people at the Electronic Frontier Foundation frequently take the lead on these issues. I turn to them now, by using an intellectual framework they laid out in the guide **[Surveillance Self Defense](https://ssd.eff.org/)**. Please take 30 minutes and read this text now. It&#8217;s ok, I&#8217;ll wait.

My take away from SSD is to break the unhelpful binary of &#8220;secure vs. insecure&#8221; into a more actionable set of information:

  * you have **assets** to protect (your browser history; the contents of an email; a list of sources).
  * you have **threats** against those assets (they could be intercepted, they could be published, they could be lost)
  * you have **adversaries** (specific and finite: government agencies, corporate security, vigilante networks, private surveillance firms)
  * you have a **risk assessment**: based on our understanding of the assets, threats and adversaries, how likely is a bad thing to happen? How do our actions increase or decrease that risk?

To this, I would add the historical observation that privacy by &#8220;policy&#8221; isn&#8217;t working [7]. Instead we have to focus on privacy inherent to the technology we use. It is no longer sufficient to trust institutions to protect our privacy, because they have shown &#8212; repeatedly &#8212; that they do not deserve trust [8]. They roll over to governments, they sell our info for profit, they expose our data through carelessness. Human nature won&#8217;t change. The solution is to build technical solutions that allow us to conduct business, relationships and politics online without transferring power over our privacy, communications, and political participation to invisible controlling bodies.

You are not going to be &#8220;secure&#8221; or &#8220;insecure&#8221;. Instead, you have a framework for understanding undesirable outcomes, and adjusting behavior and technology choices to mitigate against the most destructive or most likely threats. Security is a series of tradeoffs &#8212; most often between usability and privacy of communications.

Fortunately, there are good tools, which give immediate benefits at little cost to users. This is the first post in a series. We&#8217;ll talk about specific counter measures and behavior changes in my next posts.

You feedback and critique is welcome in comments or towards [@eylerwerve](https://twitter.com/#!/EylerWerve "@eylerwerve") on Twitter.

_&#8212; Jonathan Eyler-Werve_

&nbsp;

[1] [Wired &#8211; 9 Reasons Wired Readers Should Wear Tinfoil Hats](http://www.wired.com/threatlevel/2011/11/reasons-to-wear-tinfoil-hats/all/1)

[2] [Wired &#8211; Appeals Court Strengthens Warrantless Searches at Border ](http://www.wired.com/threatlevel/2011/04/border-search/)

[3] [Ars Technica &#8211; ICE admits year-long seizure of music blog was a mistake ](http://arstechnica.com/tech-policy/news/2011/12/ice-admits-months-long-seizure-of-music-blog-was-a-mistake.ars)

[4] [The Investigative Fund &#8211; Fiji Water: Spin the Bottle](http://www.theinvestigativefund.org/investigations/envirohealth/1040/fiji_water%3A_spin_the_bottle/?page=entire)

[5] [Open Congress &#8211; H.R.6304 &#8211; FISA Amendments Act of 2008](http://www.opencongress.org/bill/110-h6304/show)

[6] [BoingBoing &#8211; Wikileaks volunteer detained and searched (again) by US agents ](http://boingboing.net/2011/01/12/wikileaks-volunteer-1.html)

[7] Not my idea; credit to security activists who prefer not to be named.

[8] [LA Times &#8211; Bank of America data leak destroys trust ](http://articles.latimes.com/2011/may/24/business/la-fi-lazarus-20110524)

&nbsp;
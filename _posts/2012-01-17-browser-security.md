---
id: 809
title: How to secure your Web browser
date: 2012-01-17T12:08:32+00:00
author: Jonathan Eyler-Werve
excerpt: 'In terms of effort/benefit ratio, there is no more effective way to improve your security than updating to a current Web browser. '
layout: post
guid: http://www.eylerwerve.com/?p=809
permalink: /2012/browser-security/
wpsd_autopost:
  - 1
categories:
  - Jonathan
tags:
  - Information Security for Activists
---
<div id="attachment_812" style="width: 599px" class="wp-caption aligncenter">
  <a href="http://www.eylerwerve.com/wp-content/uploads/2012/01/bagcontents-e1326810724661.jpg"><img class="size-full wp-image-812 " title="bagcontents" src="http://www.eylerwerve.com/wp-content/uploads/2012/01/bagcontents-e1326810724661.jpg" alt="" width="589" height="422" /></a>

  <p class="wp-caption-text">
    Image: Graham Holiday, CC by/nc/sa
  </p>
</div>

**Part 2 of a series: [INFORMATION SECURITY FOR ACTIVISTS](http://www.eylerwerve.com/tag/information-security-for-activists/)**

It&#8217;s easier to ignore the need for basic information security, and most people do. I&#8217;m asking everyone to adopt a handful of field-tested practices that I have seen used with Global Integrity&#8217;s staff and network of 1,200 contributors around the world.[1] By adopting good info security practices, you can help people particularly at risk of surveillance, censorship and disruption. In my work, these people are mostly journalists who write about corruption, natural resources, organized crime or defense.

This works for three reasons: one, it spreads knowledge around. Two, when secure communication is normal it creates lots of noise that makes it easier for people at risk to work safely. Three, it increases the baseline security of the many systems that all these highly networked people use and interact with.

These recommendations are mostly free, and not difficult. I know that annoying tools get uninstalled, so I don&#8217;t recommend them. This stuff has to work. The advice here is easy to use and will help mitigate against a number of common threats.

This post is part of a series. I&#8217;m starting with at the most basic precautions and we&#8217;ll work our way down to the tinfoil hat stuff.

## Always use an up to date Web browser

In terms of effort/benefit ratio, there is no more effective way to improve your security than updating to a current Web browser. I honestly don&#8217;t care which one. Thanks to Mozilla kicking a complacent industry in the ass, we&#8217;re in a Golden Age of browsers, where standards are mostly agreed on and useful features are quickly copied from innovators to followers. So raise a glass to the nonprofit Mozilla Foundation and use whichever major browser you prefer.

I personally like Mozilla Firefox because Mozilla shares my values and Firefox gets more scrutiny than any other product. I also like Google Chrome because the security model (tabs as processes; quietly pushing updates) is good. But really, _the main thing is that the browser is up to date_. There are many things your browser does to harden you against threats while you surf around the Web &#8212; too many to list here &#8212; but unless you keep the browser up to date, you are seriously screwed. If you click on &#8220;About Firefox&#8221;, if should say &#8220;Firefox is up to date&#8221; &#8212; then set it to update in the background. Chrome does this, and is pretty much always up to date.

A bit about settings: Browsing History is a massive privacy flaw masquerading as a feature. Everyone should turn this off and leave it off. Firefox users: set the browser to never remember your browsing history by default. Chrome doesn&#8217;t even allow this, unless you use &#8220;Incognito Mode&#8221; or a history scrubber plugin. This is unfortunate and I wish Google would change it. Here&#8217;s a 2008 guide to [turning off browser history](https://www.cert.org/tech_tips/securing_browser/#Mozilla_Firefox).

Get a browser here: <https://www.mozilla.org/en-US/firefox/new/>

## Uninstall your plug-ins… except for these

Plugins are little bits of code that let you add features to a Web browser. That&#8217;s generally a good thing, but for people concerned about security, it presents a problem: every major browser is subject to scrutiny and community oversight; the same is not true of plugins. So when you install plugins called WeatherBotz or ClickForLulz or TimezoneHelperz, you&#8217;re putting a everything you do on the Web in the hands of unknown parties. Who can&#8217;t even spell. If they screw up, you are exposed. In some cases, silly plugins have been used as attack vectors for password theft.

So, in general, don&#8217;t install plugins. When you do install plugins, get them from authoritative sources like <https://addons.mozilla.org/> and note how many downloads they&#8217;ve gotten &#8212; if it&#8217;s not in the tens of thousands, skip it.

The following plugins are helpful in locking down your security, and I recommend them. Features like these frequently end up being part of the browser later on (remember pop-up blockers?). Installing them as plug-ins puts you ahead of that adoption curve.

These are all Firefox plugins. AdblockPlus, Ghostery and Web of Trust have plugins available for Chrome.

### HTTPS Everywhere

Why: Forces many popular sites (Facebook, Google, etc) to use encryption, preventing &#8220;man in the middle&#8221; spying on information en route. This would have likely prevented the widespread interception of Facebook logins by security services in Tunisia.

How: Download plugin.

<https://www.eff.org/https-everywhere>

### AdBlockPlus

Why: Prevents adbot trackers from loading, in addition to blocking ads.

How: Download plugin. Pick the default “subscription” for your language of choice — this is the blacklist of ads you won&#8217;t see displayed.

<https://addons.mozilla.org/en-US/firefox/addon/adblock-plus/>

### FlashBlock

Why: Disables content displayed with Adobe Flash unless you specifically ask for it. Flash is a nice format for games, uploaders and video, but has a lousy security record. Many attacks are based on displaying Flash content to browsers and convincing Flash to download malicious code. This will also improve your battery life by not loading power-hogging Flash elements of a page.

How: Download Plugin. To see Flash content, click on the gray Flash icon.

<https://addons.mozilla.org/en-US/firefox/addon/flashblock/>

### Ghostery

Why: Blocks third party code (from advertisers, mostly) that records your activity online. You don&#8217;t know them, so you shouldn&#8217;t trust them to know what you&#8217;re doing.

How: Download plugin. Configure to “block all” and “no alerts” so it will run silently.

<https://addons.mozilla.org/en-US/firefox/addon/ghostery/>

### Web of Trust

Why: Warns of known malware websites via a popup and displays reputation icons on search results pages. As if you didn&#8217;t need a reason to avoid viruses and whatnot, malware is an attack vector for spammers and scammers. It is also used by security services in more targeted attacks on activists. This is particularly useful for people who do a lot of research online, which involves poking around a lot of unknown sites.

How: Download plugin. Set security to the less noisy “moderate” setting. See those little circle icons next to search engine results? Don&#8217;t click on the red ones. If you do, you&#8217;ll get a pop-up warning you of what&#8217;s behind the link; you can click through if you want to.

Important caveat: In order to check your links against their database of sites, Web of Trust receives a LOT of information about your browsing habits, which requires a risk-to-benefit analysis. It is not for people with acute privacy needs.

<https://addons.mozilla.org/en-US/firefox/addon/wot-safe-browsing-tool/>

In our next post, we&#8217;ll talk about [TOR, Virtual Private Networks, and anonymous browsing](http://www.eylerwerve.com/2012/vpn/).

[1] [www.globalintegrity.org](www.globalintegrity.org)
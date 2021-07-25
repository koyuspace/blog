---
title: The months on koyu.space (May 2020)
author: koyu
type: post
date: 2020-06-03T09:55:00+00:00
url: /2020/06/03/the-months-on-koyu-space-may-2020/
featured_image: /wp-content/uploads/2021/03/photo-1507525428034-b723cf961d3e-1568x1042.jpg
categories:
  - The months on koyu.space

---
 

The development work is now over for May 2020 and we are ready to present everything that happened around koyu.space to you. A lot of things happened and we don&#8217;t want you to miss out on all these important changes.

# The big migration

We migrated from masto.host to our own infrastructure and it was a huge success. This gives is a lot more flexibility over what software can run on the server and a lot more scalability. If you need a Mastodon server yourself we can highly recommend masto.host, they have good pricing and a nice support e-mail. Hugo (the owner of masto.host) helped us to get the data from A to B and was there to give us some hints to fix some last minute bugs. Everything should run smoothly now and I hope you like the new koyu.space.

# glitch-soc

You may have heard that we switched to [our own fork][1] of the &#8220;glitch-soc&#8221; platform. This also means we successfully migrated koyu.space from masto.host to our own infrastructure with a little bit of help. Given that we implemented a number of new features and here is just a small list of changes:

  * Media improvements
  * Images inside the CW spoiler
  * fullwidth images
  * scaling options
  * Formatted toots
  * Reply selection in lists
  * Filter improvements
  * Highlighting of misleading links
  * Hiding follower count
  * An app settings modal
  * Collapsible toots
  * Toot visibility icons
  * Local-only toots
  * Threaded mode
  * data-* attributes on statuses for custom CSS targeting
  * Advanced theming via flavours+skins
  * Doodle

# Whitelist mode

We switched into a mode called &#8220;whitelist mode&#8221; on koyu.space. This was a really tough decision to make, but we already whitelisted instances where most of our content comes from anyway so that shouldn&#8217;t be a huge problem for most of our users then. We did this to prevent abuse to our systems. Since the fediverse is an open network anyone could join, especially bad actors and we wanted to throw them out to improve the overall user experience.

# A native koyu.space app

Our latest survey gave us the impression that users wanted to have a native, more performant app on their Android phones. We listened and created our own [fork of Husky][2] which allows you to sign in with your koyu.space account and lets you enjoy the latest koyu.space features while having a performant and consistent user interface. The current limitations are no support for HTML (since it&#8217;s easier to type Markdown on a phone) and no support for stickers or animated emojis. We hope that we can address the last two issues in future updates, but for now we want you to enjoy the app.

# BlueOS

We got nominated with BlueOS on Distro Watch! This is a huge thing and we hope we get listed soon to attract more people to this project. BlueOS is a Linux distribution by koyu.space with a focus on gaming, productivity and the internet. The goal is to have an easy to use operating system that runs great everywhere, especially on limited hardware. We think that recycling your computer with Linux and giving it a second chance is a good thing and we invite you to try it out on your old Windows XP machine (64-bit is required!). You can download BlueOS from [blueoperatingsystem.xyz][3].

# Offtopic

I hope everyone has a good June and we also want to wish you a happy summer and pride month and wanted to say that black lives indeed matter. If you want to help out hop over to our communication channels or give us some money so we can stay awake through the nights. This was the wrap up for last month and I hope you liked the changes. If you want to give us some feedback or have comments or suggestions, press the feedback button on the bottom right corner.

 [1]: https://github.com/koyuspace/mastodon/
 [2]: https://github.com/koyuawsmbrtn/Husky
 [3]: https://blueoperatingsystem.xyz
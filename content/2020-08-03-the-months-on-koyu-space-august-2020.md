---
title: The months on koyu.space (August 2020)
author: koyu
type: post
date: 2020-08-03T09:40:00+00:00
url: /2020/08/03/the-months-on-koyu-space-august-2020/
featured_image: /wp-content/uploads/2021/03/photo-1598520106864-72ed7919100b-1568x1039.jpg
categories:
  - The months on koyu.space

---
The development work is now over for August 2020 and we are ready to present everything that happened around koyu.space to you. A lot of things happened and we don’t want you to miss out on all these important changes.

# Fixing repetitive downtimes

The repeated downtimes of koyu.space are now resolved.

The hosting provider of the routing server had messed up something since the 11th of August.

Despite many, stressful, nights spent trying to resolve it (i.e. blaming our setup), we discovered it was an issue with the hosting provider. The server that manages connectivity for the production machine had intermittent connectivity issues (i.e. pinging 8.8.8.8 would fail, even pinging the hosting providers gateway would also fail).

A ticket was opened with the hosting provider on the 22nd.

Repeated attempts to get a response was met finally with

&#8220;For the root cause we isolated the problem to a rogue device that was failing and was causing a routing loop within the network. &#8220;

Which was very very concerning since it appears only our instance was affected.

So I thought &#8220;ok great, we&#8217;ll see if it goes down again&#8221;. Of course, I woke up to 60 notifications of things going down. I sent 3 follow ups with 1-2 hours inbetween to the provider and was ignored.

The hosting provider has now been ditched, and a new provider is used for the routing setup as of 30 minutes ago.

Apologies for the severe instability from the bottom of my heart, I promise to be more proactive in future.

Automatic downtime alerts are posted to the Telegram channel at <https://t.me/koyuspace>

# Yubikey support

koyu.space got support for Yubikeys and other hardware security keys. Securing admin accounts through hardware 2fa makes it even harder from an outside-attacker to gain access to koyu.space&#8217;s internal infrastructure. We think this is a crucial step to make koyu.space even more secure and fun to use.

# General database fixes

The database was being moved to faster storage to finally resolve some long-standing performance issues, along with a DoS bug we had found.

# Trending hashtags

Trending hashtags are now updating and have been re-enabled again, thanks to [this friendly guy on GitHub][1].

# Offtopic

To celebrate way better speed and stability of koyu.space koyu and arduino101 had a little party. Also koyu is inviting everyone to play some Overwatch soon again.

 [1]: https://github.com/tootsuite/mastodon/issues/13450#issuecomment-684627501
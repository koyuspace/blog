---
title: The months on koyu.space (July 2020)
author: koyu
type: post
date: 2020-08-04T09:45:00+00:00
url: /2020/08/04/the-months-on-koyu-space-july-2020/
featured_image: /wp-content/uploads/2021/03/photo-1481349518771-20055b2a7b24.jpg
categories:
  - The months on koyu.space

---
The development work is now over for July 2020 and we are ready to present everything that happened around koyu.space to you. A lot of things happened and we don’t want you to miss out on all these important changes.

# koyu.space on VHS

koyu.space now has its own PeerTube instance. This is a core service and wouldn&#8217;t be shut down. PeerTube functions like YouTube, but decentralized (with ActivityPub and WebTorrent). The difference is that if a video on koyu.space on VHS should get viral the server doesn&#8217;t get under full load thanks to people that would happily seed the video. If you need a more detailed introduction of what PeerTube is there is a video on [their official website][1]. The server is currently limited to 15 users, but we will increase the limits if we don&#8217;t see people uploading. You can upload as much as you want, but please use this power in moderation or we will have to limit that as well. Of course if you upload something make sure it isn&#8217;t copyrighted or is okay to reupload and also make sure your videos don&#8217;t violate against the koyu.space community guidelines.<figure class="wp-block-image size-large">

<img loading="lazy" width="830" height="472" src="https://blog.koyu.space/wp-content/uploads/2021/03/vhs.png" alt="" class="wp-image-26" srcset="https://blog.koyu.space/wp-content/uploads/2021/03/vhs.png 830w, https://blog.koyu.space/wp-content/uploads/2021/03/vhs-300x171.png 300w, https://blog.koyu.space/wp-content/uploads/2021/03/vhs-768x437.png 768w" sizes="(max-width: 830px) 100vw, 830px" /> </figure> 

# Mastodon 3.2

koyu.space now ships with [Mastodon 3.2][2] which has been released a few days ago at the time of writing. Since koyu.space usually rebases the latest glitch-soc `master` branch, most of these changes were visible in July. It contains a number of useful features and improvements so check out the blog post we linked.<figure class="wp-block-image">

![The new and improved audio player][3] </figure> 

# Nordcast updates

Nordcast received a few bugfixes and improvements in July so these have been published to Google Play now. The iOS version is still pending, because we have problems getting a development machine running for iOS (sadly Apple only allows their compiler to run on Macs).

# What will happen with BlueOS?

BlueOS seems to be a long-standing elephant in the room. Right now the project is halted until koyu can pour more time into this project since maintaining a Linux distro always comes with its consequences. The old ISOs will still run fine until 2023 so there&#8217;s no way to throw them away yet. BlueOS will return, we promise.

# A little bit more speed

koyu.space received next to a few updates a speed boost as well. Previously every container on the machine the container for koyu.space runs on had to fight against each other and claim their resources. Eventually our Minecraft server ran out of memory and consumed over 800% (!) of CPU power. That of course is way too much so we limited what these containers should do. So right now the koyu.space Mastodon instance should run faster than anything else. This is okay, because most people use the Mastodon instance anyway and it consumes the most resources as well. We will adjust these limits as we see fit, but on the bad side we had to temporarily shut down the Minecraft server until we figured out what is causing these massive memory leaks.

# Anything else?

Nope that&#8217;s basically it. We weren&#8217;t that much productive in July, because we also have to take the time. Right now the koyu.space team is very small and keeping such a big project running consumes a lot of time. Sorry if you didn&#8217;t see anything that deserved more love, but we aren&#8217;t physically capable of being at more than one thing at once (until someone gives us superpowers).

 [1]: https://joinpeertube.org
 [2]: https://blog.joinmastodon.org/2020/08/mastodon-3.2/
 [3]: https://blog.joinmastodon.org/2020/08/mastodon-3.2/hero.png
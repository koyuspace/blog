---
title: The months on koyu.space (March-April 2020)
author: koyu
type: post
date: 2020-04-14T09:35:00+00:00
url: /2020/04/14/the-months-on-koyu-space-march-april-2020/
featured_image: /wp-content/uploads/2020/04/photo-1434030216411-0b793f4b4173.jpg
enclosure:
  - |
    |
        https://f001.backblazeb2.com/file/koyuspace-media/media_attachments/files/003/411/609/original/8296cc4053594253.mp4
        31845876
        video/mp4
        
categories:
  - The months on koyu.space

---
The development work is now over for April 2020 and we are ready to present everything that happened around koyu.space to you. A lot of things happened and we don&#8217;t want you to miss out on all these important changes.

# The big summer migration

You might have heard that we are going to migrate to a new host on June 26 2020 (note that down in your calendar). This means we would then have a lot more flexibility than we already have which also means that it will allow us to introduce new features. We are also currently thinking about migrating to glitch-soc which should go flawlessly. If the migration was successful all users will get an e-mail (and our people on Zulip and the app will get a notification as well) so make sure you check your inbox on a regular basis on this day. This is a huge step and we can&#8217;t wait to introduce you to the new features glitch-soc will offer you. Note that we will discontinue the Matrix server so make sure that you migrate your Matrix account to another instance (like ponies.im or yuri.im, matrix.org is too huge to handle the traffic fast enough) and we will also discontinue the Git server so make sure you get your code off it before it&#8217;s being shut down. We recommend using many of the free code hosting sites like Gitlab or GitHub.

# The koyu.space app now has notifications

What&#8217;s making this sound? Brrring! It&#8217;s the new koyu.space app with notifications. Everyone who downloaded the APK file or the app from Google Play will receive notifications about important announcements, updates and things that happened inside of koyu.space right on their phones. The F-Droid version won&#8217;t receive updates anymore, but since there has been no security flaws or new features apart from notifications (which requires the use of proprietary Google libraries) it&#8217;s not a big deal. The push backend is completely [open-source][1] like everything we do, so take a look at the code and report anything unusual to us.<figure class="wp-block-image size-large">

<img loading="lazy" width="225" height="400" src="https://blog.koyu.space/wp-content/uploads/2021/03/app-lockscreen-push.png" alt="" class="wp-image-17" srcset="https://blog.koyu.space/wp-content/uploads/2021/03/app-lockscreen-push.png 225w, https://blog.koyu.space/wp-content/uploads/2021/03/app-lockscreen-push-169x300.png 169w" sizes="(max-width: 225px) 100vw, 225px" /> </figure> 

# A more professional style

We dropped our old bunny-pal from the loading animations and replaced it with a soothing dot animation. Even though we dropped the hopping bunny animation from the loading screen the bunny will still cry if something bad happened. We also changed the background on the front page to match it more with our server banner and cleaned up the front page to only display the most useful information to people. The change should display koyu.space in a more professional manner, but also keep the overall style that makes koyu.space stand out as well. The koyu.space desktop app also received these changes.<figure class="wp-block-image size-large">

<img loading="lazy" width="1010" height="721" src="https://blog.koyu.space/wp-content/uploads/2021/03/desktop.png" alt="" class="wp-image-16" srcset="https://blog.koyu.space/wp-content/uploads/2021/03/desktop.png 1010w, https://blog.koyu.space/wp-content/uploads/2021/03/desktop-300x214.png 300w, https://blog.koyu.space/wp-content/uploads/2021/03/desktop-768x548.png 768w" sizes="(max-width: 1010px) 100vw, 1010px" /> </figure> 

# Minor updates

The koyu.space base (Mastodon) has been updated to version 3.1.3 and the Matrix Synapse server has been updated to version 1.12.3. The Matrix server will receive updates until this summer until it&#8217;s being shut down at the big summer migration. koyu.space Git has been updated to Gitea version 1.11.2 and will also receive updates until the big summer migration. We also fixed the issue on koyu.space Git which has lead to some browsers incorrectly retrieve the custom stylesheet.

# Offtopic

koyu also recently discovered Overwatch for herself and invites everyone to play a round or two. Hit her up on Battle.net at bubblineyuri#2146 for some games with the community. It will be a lot of fun.<figure class="wp-block-video"><video controls src="https://f001.backblazeb2.com/file/koyuspace-media/media_attachments/files/003/411/609/original/8296cc4053594253.mp4"></video></figure>

 [1]: https://gitlab.com/koyuawsmbrtn/koyuspace-app-pushservice
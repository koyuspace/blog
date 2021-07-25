---
title: Moving away from Kubernetes
author: koyu
type: post
date: 2021-03-07T10:11:16+00:00
url: /2021/03/07/moving-away-from-kubernetes/
featured_image: /wp-content/uploads/2021/03/photo-1584524968100-76f90c97a806-1568x1045.jpeg
categories:
  - Engineering

---
This Saturday we moved away from Kubernetes and in this blog post we want to explain how and why we did it.

## How we did it

Of course we backed up the whole database and imported it to a new host. Since our media is stored in S3 we didn&#8217;t have to move this as well. After the database was imported to the new host I began installing koyu.space to the new host and changing the .env vars to point to the new host. To be ultra safe I just ran a database migration, but for my luck there were no pending migrations.

## Why we did it

The biggest problem with Kubernetes is performance. Without Kubernetes we reduced the memory overhead by 3 times! This means a drastical improvement from 12GB RAM in idle to 4GB. Of course this also affects load times and makes koyu.space run much more fluid. This is why I recommend not to run koyu.space or Mastodon in Kubernetes, it&#8217;s just slow.

## Closing words

koyu.space runs a lot faster now and after 8 hours of pure back pain (because I can&#8217;t sit straight) I&#8217;m glad we did this change. I thank everyone who was patient during this huge migration and we&#8217;ll see us on the wired. Have a great weekend!
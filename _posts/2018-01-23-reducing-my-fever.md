---
layout: post
title: "Reducing my Fever"
microblog: false
date: 2018-01-23 12:00 -0800
guid: http://jalvani.micro.blog/2018/01/23/reducing-my-fever.html
---
I've been using [Fever][fever] for nearly a decade; the site was launched in 2008, and I was an early adopter. I've waxed and waned my RSS reading, sometimes going through periods where Digg or Reddit or Twitter gave me more of my news, but over the past few years I've been back in Fever a lot. 

I didn't know, but Fever's creator and author, Shaun Inman, [killed][killed] Fever and [Mint][mint] over a year ago in December 2016! It's a testament to how well written this little PHP app is, and to self-hosting software, that my instances of Fever have been so reliable for so long. I've done almost no maintenance, occasionally clearing disk space on the server, but that's it. It's great. I only found out they were deprecated when I visited the site looking for information on using regex to filter specific posts from a couple of my feeds. 

I'm looking for alternatives. I'm demoing [Feedbin][feedbin] right now, and I like it so far. I do miss Fever's clever aggregation feature[^1], but I might be able to get something close by liberally applying auto-read actions, which actually very easily solved my needs I was using regex filters for in Fever. Good job, Feedbin!


[^1]: Fever had this cool concept where some feeds could be marked as "Sparks". They wouldn't show up in your unread list, but they _would_ add to a "Hot" section. Feed items that used similar language or linked to the same URLs would be aggregated under "Hot", with more popular terms and links getting a higher temperature, and thus being "hotter". So clever, and super useful for especially for squeezing some benefit from the really high-volume feeds that I otherwise won't read. 

[fever]: [http://feedafever.com](https://feedafever.com)
[killed]: [http://shauninman.com/archive/2...](https://shauninman.com/archive/2016/12/24/goodbye_mint_goodbye_fever)
[mint]: [http://haveamint.com](http://haveamint.com/)
[feedbin]: [http://feedbin.com](https://feedbin.com)


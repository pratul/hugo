+++
title = "Shaastra 2010"
date = 2010-10-28
+++

I remember I was in 2nd year when I heard about [Shaastra](http://www.shaastra.org/) for the first time. A school friend, who was studying in Mumbai told me that the [IIT Madras](http://www.iitm.ac.in/) technical festival was awesome and I should attend. Of course, I couldn't. It would have taken me amazing amounts of mental prowess to convince my seniors and friends that a 40 hour train journey across the country would be worth it. 

Move forward 2 years. It's 2010. 

Akarsh (kstar) first asked me about a possible Shaastra hackfest around August. At that time, my first reaction was "Madras? lolwot too far!". I'd never been to Madras. Not that I didn't want to go, I actually love to travel, but going all the way to Chennai all by myself would be rather boring. I've always had friends tag along for hackfests. Its a very social, fun thing. Its not a college lecture, after all. This time, [sid0](http://monogatari.doukut.su/) told me he'd come along and do a Mozilla related hackfest again (he'd already done one in 2009), so I agreed to it as well. 

As per my "allegiance", the first hackfest idea that came to Akarsh's mind was obviously Drupal :-) But this time, I wanted to do something different. I'd already done Drupal hackfests and events at many places over the past 2 years. So I decided to go ahead with Android. I had been working on my own Android app for more than a couple of months. Even my work at IITK involved Android. The hackfest people had no issues, so it was finalized. Now, the tricky part... 

sid0 had clashes with his academic schedule here at IITK and he decided to back out from going. This left me in a fix. Initially, I didn't want to go alone, but here I was again, already committed to the Shaastra folks but having to go alone again. For some time, I considered backing out as well, but then I'd never been to Madras and I'd never met the IITM FOSS junta, so I went ahead. Little did I know how insightful and awesome this trip was going to be :-) 

A student was waiting for me at the airport, the drive back to campus was nice, the weather was sunny but cool. The first thing that hit me about Chennai was, there were _no flyovers_. Actually, there are a few, but that's nothing compared to Delhi. Delhi looks like a different country altogether. The roads weren't as wide either, but the city in general was clean. Nothing prepared me for the IITM campus, however... kstar had told me it was very green and serene, but he didn't tell me it was in the middle of a forest! The campus is very very beautiful indeed, all sorts of wildlife roam free within the campus limits. I saw deer, monkeys and even black-bucks! (They even have rare albino black-bucks.) 

For the hackfest, we had 5 mentors with 5 different projects:

*   GNOME - [Yuvraj Pandian](http://yuvi.in/) (YuviPanda)
*   KDE - [Nikhil Marathe](http://kodeclutz.blogspot.com) (nsm)
*   Linux kernel - Kashyap Garimella
*   Minix - Gautham BT
*   Android - me

## Day 1

I met up with YuviPanda on the first day. He lives in Madras so he took me around the city to random places and of course, the BEACH! I've lived in Mumbai for 7 years and visiting a beach after such a long time was awesome! In all my fun and frolicking, we got nicely late for the first introductory talk that the mentors were supposed to give to the participants. Add to that the fact, that we didn't know our way around the "forest-campus". By the time we reached the lecture hall, the intro talks were over and most of the people had gone :P We caught up with them after dinner, when we decided we'd give a combined IRC + git tutorial. For some reason I've never understood, I always get to give the git talk. Maybe because I just like git so much! (best. VCS. ever.). nsm was supposed to give the IRC talk, which he too outsourced to me conveniently. Eventually, we ended up doing a sort of a discussion, with Nikhil and Yuvi pitching in for support and details. 

I had around 25 people with me in the Android team. Since we didn't have root on the lab machines, it took us most of the night trying to get a chroot environment up and running. Of course, the Android build tools are fairly easy to work with if you're a command line hacker. But these were fresh people, so we were using Eclipse... which is a sad painful story in itself.

## Day 2

By the 2nd day, I had my first major shock. People were waiting outside the lab, 30 minutes before the hackfest even started. This was HUGE. In every hackfest I've been to, 50% or so of the students usually drop out in an hour. The next day, the turnout isn't more than 30%. Here, the turnout was actually \*higher\*. Some more people joined the Android team, mostly those who missed day 1. The dedication and diligence of the participants was staggering. I don't care if this sounds racist, but in my opinion, there is a major cultural divide between students from the north and south. There was much better quality of participants here. Everywhere else, most of the people just wanted to have fun, or wanted their certificates. Here, people actually wanted to _work and learn_. It was a very humbling experience, something I won't forget for a long time. 

We continued on our install-and-setup spree this day as well. Some people got Eclipse to work inside the chroot. We had to set up their internet proxy and get the Android ADT tools from inside Eclipse, which turned out to be a \*huge\* download and \*very\* slow. While this was happening, I gave the introductory talk about the Android system and its internals, showed them around a basic application and its structure. Later however, we hit fails on the downloads on many machines. It was then I realized that I could've just taken the entire already-downloaded SDK from someone's Linux machine and copied it over. We did that, and it worked! It wasn't going to be so easy though, we began getting javac failures while building the Hello World app. Turned out, we had a broken Java install inside the chroot :/ Took most of the 2nd night to fix this, but it was worth the effort.

## Day 3

I knew I could never meet my expectation of the entire hackfest in one night. The build tools and SDK setup had wasted too much time. But still, we wrote \*some\* code after all. I showed the students how to add activities, how to link them together using Intents. XML had to be explained to some people but generally, the students were \*very\* enthusiastic and did all that they could. I tried to give them all the info that they'd need if they went back home and tried Android development on their own. As expected, all this work over the night got the participants rather bored. To fix this, the organizers went great lengths to get all of us coffee and biscuits in the middle of the night! (hats off to Subhashini, Kirtika (rkirti), Sarthak (sp1408) and Kashyap. You folks were awesome!). 

We also did something else — all the mentors demoed some interesting FOSS projects they'd worked on. I decided to demo Goonj and from the peals of laughter from everyone, I'm guessing everyone enjoyed the story (it really is awesome, maybe I'll write a book on it someday...). I also talked about Google Summer of Code and all the mentors pitched in with their GSoC experiences, to help the hackfest participants with tips and useful hints. 

![the-android-hackfest-group-with-me_5061572585_o.jpg](https://pratul.mataroa.blog/images/bfc7e63e.jpeg)

I took this group photo at 5 AM. Most of them are Android participants, with some GNOME and Linux kernel ones as well. A hearty thanks to everyone who was involved with the event and to everyone who participated. This was by far the best hackfest I've attended and I thoroughly enjoyed myself. I'd love to come back again! GO SHAASTRA!
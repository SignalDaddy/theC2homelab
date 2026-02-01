---
date: '2026-01-31T07:47:38-06:00'
draft: false
title: 'A Homelab Can Start Your Career'
description: "How learning to self-host and network bridged the gap between theory and practice."
tags: ["Homelab", "CISSP", "Systems Engineering"]
categories: ["updates"]
series: ["Career & Learning"]
---

![blog post headline photo](homelabsstartsmall.svg)

## Proficiency Requires Practice

I know that opening title sounds like a no-brainer, but stick this out with me before you write it off. I've spent the last 16 years managing and maintaining some of the most complex network architecture in the U.S. Army. People who outrank me and even others who have more experience in the Army as a whole than I do come to me as their specialized advisor for communications and the way ahead for Signal and Cyber operations.

I'm not saying that to brag; in fact, I'm pretty sure that as far as intelligence quotients go, I'm average, maybe even a little below average in some departments. But what I do have that many do not is patience, stubbornness, and an unwavering ability to find myself attempting things I am wholly unprepared or unqualified for (those are stories for another time). It is this combination of qualities that led me to where I am today, not just as a homelabber, but in my career as a Soldier and Engineer. 

If you don't read the rest of this post, take this away: **"Do things that challenge you, and don't give up even if you fail over and over."** Corny advice, I know, but repeat it to yourself a few times a day and you can lead yourself to do some pretty amazing stuff.

Computer Science and Information Technology can be intimidating, especially today. It's incredibly rare to find any I.T. system that isn't, in fact, just a system within a system that's a **System of Systems** fo those having troubling keeping up. The work can be incredibly complex. Software Engineers can find themselves trapped in "dependency hell," while Network Engineers get dropped down rabbit holes trying to find an IP address in a firewall that is off by just a single digit. I won't lie to you: I.T. is hard.



However, thankfully, I.T. isn't very poetic; nothing here is greater than the sum of its parts. It's just basic math: 1 + 0 = 1. If you break a system down to its simplest parts, you are more likely to understand the whole once it's placed back together. With enough repetition you'll find that things generally work the same way as long as you follow the same steps and place the system under similar constraints. Unfortunately, most real-world systems are in production. Trying to learn on them is like trying to fix a car while you're driving it down the road. 

This is where building your homelab comes into play, and you're place yourself in an environment where you can break things without concequences.

## Options for Your First Lab

The biggest misconception I try to steer my soldiers away from is the belief that you need to purchase refurbished enterprise servers that sound like a jet engine and make you cry when the power bill arrives. While that is an option, it often leads to more frustration and e-waste than it's worth. Here is what I recommend based on your current skill level:

---

### Entry Tier: Single Board Computers (SBCs)
{{% badge %}}<a href="https://raspberrypi.com" class="text-orange">Raspberry Pi</a>{{% /badge %}}{{% badge %}}<a href="https://zimaboard.com" class="text-orange">ZimaBoard</a>{{% /badge %}}{{% badge %}}<a href="https://orangepi.com" class="text-orange">Orange Pi</a>{{% /badge %}}{{% badge %}}<a href="https://arduino.cc" class="text-orange">Arduino</a>{{% /badge %}}

SBCs are microprocessors that are power-efficient yet incredibly capable. **Raspberry Pis** currently stand at the top of the mountain for their community support, though alternatives like the x86-based **ZimaBoard** are gaining ground. These devices almost exclusively run **Linux** (the homelabber's kernel of choice). The only drawback is that they may fall short once you scale up to resource-intensive experiments like AI or heavy media streaming.

### Intermediate Tier: Mini-PCs and NUCs 
{{% badge %}}<a href="https://www.gmktec.com/" class="text-orange">GMKtec</a>{{% /badge %}}{{% badge %}}<a href="https://www.asus.com/us/displays-desktops/nucs/all-series/" class="text-orange">Asus NUC</a>{{% /badge %}}{{% badge %}}<a href
="https://www.bee-link.com/" class="text-orange">Beelink</a>{{% /badge %}}{{% badge %}}<a href="https://protectli.com/" class="text-orange">Protectli</a>{{% /badge %}}

NUC (Next Unit of Computing) is now a general term for small form-factor, modular PCs. These range from $200 to $2,000 and are powerful enough for gaming or video editing. I personally use a **Protectli** Mini-PC as my firewall appliance. They are fast enough to handle encrypted VPN traffic and come with multiple ports to design segmented networks, just like an enterprise environment.

### Advanced Tier: DIY Systems
DIY is for later in your journey. While the sky is the limit, the true cost comes in the form of time spent troubleshooting hardware compatibility and maintenance. However, this is the most effective way to learn! There is something truly rewarding about willing a system into existence after spending a weekend figuring out why your DNS won't resolve. 

---

Of course there are all kinds of other ways you can get into homelabs. I've only list a few here to keep my article short and to the point. You can even build a virtual lab inside a cloud enviroment if you already have the know how. My approach has always been to **"Find Your Sweet Spot."** If you play a game against toddlers, you get bored. If you play against pros, you get frustrated and quit. If you play against your friend you start to enjoy the challenge of it and you find your focus is draw in. You need the challenge that is "Just Right" that’s where the flow happens, that where you'll really start learning.




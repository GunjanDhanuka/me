+++
title = 'Summer Internship at Rubrik'
date = 2023-09-21T12:42:06+05:30
description = "The most productive and fun summer I had!"
draft = false
tags = ['experience', 'career', 'intern']
ShowToc = false
+++

In the summer of 2023, I got an opportunity to intern as a Software Engineer at Rubrik's India office in Bengaluru. Let's reflect back on some of the experiences of my internship together. Separate blog on Namma Bengaluru coming soon!

## Day 0
So we (Aman and myself) landed in Bengaluru directly from Guwahati on a fine Saturday afternoon and checked in to our hotels. The weekend was spent in interacting with other interns who were mostly from other old IITs, IIIT-H and BITS. The people had a diverse skillsets and we discussed (*read, complained*) at length about the people, courses and profs at our institutes xD. However, I was very excited to know the CS curriculum (especially at IIT Delhi) was much more hands-on and flexible. I wish IITG soon moves towards such a structure.

{{< figure src="8th_floor.jpg" align="center">}}

## Day 1
So, the first Monday all of us were ready on time and boarded the office cabs at 9 AM sharp. Upon reaching, we were treated with scrumptous breakfast and given our schedules for the week. It was going to be an exciting (*more on that later*) week with all the teams presenting a broad idea of what they do. Also, we were all alloted a buddy/mentor who is a full-time SDE at Rubrik, and will be helping us with regular issues. We would report to our managers, who will assign us projects and tasks.

My buddy (Rishabh) and mentor (Devendra) were both working remotely, so I had brief calls with them. Since we had a floating desk policy, I was feeling kinda lost in the office, seeing other interns going to sit with their mentors/managers. Then Siddharthi from my team (**Team Legion** 💪) took me to where they sat, and we exchanged hello's and hi's.

## Week 1
The first week was mostly onboarding stuff, we would have 3-4 hours of meetings in the first half of the day *(Remember when I told this would be exciting?)* 🥲. The rest of teh day was spent in setting up the dev environments and reading through documentation.

My project required a thorough knowledge of **Kubernetes and Golang**, alongwith a special cluster-management package called gravity. I voraciously read through the Confluence docs on **Trident** (the project I would work on), and several YouTube videos to understand how Kubernetes works.

The first week also introduced me to how the team functions: sprints, standups, and the mighty JIRA! Our team was working on three tracks -- Core Infra, RCV (Rubrik Cloud Vault) and Trident (my project). Trident was picked up fairly recently by our team, and hence only two people (my mentor and manager) were working on it.

{{< figure src="barista.jpg" title="Barista ☕🤍" align="center" width="600">}}

## Week 2 - 4
In the subsequent weeks, I was conducting extensive experiments on the existing set-up and testing out all possible solutions and errors for our requirement. I hadn't written a single line of code in the first month, and that made me really anxious.

> "Comparison is the thief of joy." -- As Theodore Roosevelt rightly said!

On the bright side, I had prepared loads of Google Docs, found out a number of potential errors and figured out a tentative flow for our solution. Then I prepared a single Master Doc that contained all my findings and possible workflows. It was nicely appreciated on our team's Slack, and I was now happy with how things were going!

Most of the Trident team was based in the U.S., but they were always helpful and critical about the smallest of details (which definitely helped me immensely)! The proof-of-concept was now complete, and green flag was given to start the implementation 🚀. 

Rubrik's CEO, Bipul, visited India during our second week and we had a grant treat at The Conrad. He hailed from Bihar, my home state, and I was very moved by the company he had built!

{{< figure src="desk.jpg" title="My desk setup" align="center" width="600" >}}

## Month 2
The second month was much more exciting, since I had finally coding stuff! The first commit we had to make was simply adding my name to the New-Hires list, and funnily enough, it took me two weeks to get that through 😂. It somehow required permissions of a privileged group, and I thought the issue was too insignificant to my manager. That was the commit that took me the longest time to push, throughout my internship! ☠️.

My first actual commit was to print the status of all nodes connected to the cluster on the CLI, a fairly simple task. However, my diff (we call commits as diffs over there) was flooded with comments during code review. All of my experience of writing code came from personal projects, and I didn't use to pay proper attention to refactoring code, checking all edge cases and making it future-proof. The U.S. Team and Rishabh were very kind in pointing out the improvements, and I was able to get them done quickly. This would be the usual flow of my internship:

- Take up tasks in the sprint ✅
- Code during the week 🧑‍💻
- Create a diff when done 📝
- Address reviews on the diff 💬
- Finally sail (push) the diff ⛵!

Thanks to the meticulous PoC I conducted earlier, the coding was very simple and straightforward. Creating test deployments and code reviews used to take up most of the time, and rightly so!
> *"“Don’t fix bugs later; fix them now.” - Steve Maguire*

<!-- <figure class="video_container">
  <video controls="true" allowfullscreen="true">
    <source src="timelapse.mp4" type="video/mp4">
  </video>
</figure> -->

<!-- Embed timelapse video here -->
    
{{< figure src="timelapse.gif" title="Timelapse of my work" align="center" width="600">}}

Three new grads had also joined the team, Atharva, Samiksha and Animesh. Atharva would continue on my project after my internship was over, and we used to chat a lot through the day!
Soon we had my first team outing, where we went for lunch and then to my very first **Escape Room**! The theme of the room was Nuclear Bunker, and we managed to do a pretty good job of cracking most of the puzzles (while ignoring the most blatant clues 🤣).

{{< figure src="legion_escape.jpg" title="Team Legion @ Escape Room, Koramangala" align="center" width="600">}}

## Endgame
In the third month, I was focussing on completing as many deliverables as possible. While my manager mentioned that there were no hard deadlines, I wanted to see my project to as close to completion as possible. Some of the other interns used to stay back till dinner (which was MUCH better than eating at random restaurants everyday), but I stayed till late only for 1-2 days during those 3 months. By this time, I had given several internal demos to my team, and was quite confident about my progress. The diffs were also sailing much more smoothly now.

Soon as the last working day come close, it was time to wrap up my 75 days of work into a 15 minute presentation. The project still needed testing, and a few auxiliary features were left. But the main deliverables were all complete, and I was proud of the work I had done here. It was a high-demand feature by some BIG clients, and there was a lot to learn about Distributed Systems there.

With the help of Rishabh and Devendra, I prepared the presentation and a working demo of all the new features. Meanwhile, I also showed it to Manjunath, who was a Principal Engineer at Rubrik, and pretty much laid the foundation of entire Trident. He was very happy with the project, and congratulated me for it.

The demo went superb, and the VP and Director also lauded the work. Now there was only one unknown, the PPO... I wasn't too stressed about it, thanks to my all-time favorite line:
> "Do your best and forget the rest!"

In the next week, my manager communicated to me that I had been extended a full-time offer 🎉, and I was delighted to hear that! In the final few days after presentation, I didn't do too much and spent my time trying out all that the in-house barista had to offer, and on the massage chairs! 🍵

{{< figure src="massage_chair.jpg" title="Nothing better than a full-body massage" height="500" align="center" >}}

Will write detailed blogs about how I secured the internship, and Bengaluru as well.

Peace ✌️ \
*Gunjan Dhanuka*

Feel free to connect with me over: [Linkedin](https://www.linkedin.com/in/gunjan-dhanuka).

{{< figure src="me_escape.jpg" align="center" height="500">}}
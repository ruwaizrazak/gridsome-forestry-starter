---
date: 2018-10-11
thumbnail: "/uploads/title.png"
title: Building an Event system
categories: []
project_bg_color: ''
project_fg_color: ''

---
![](/uploads/maxresdefault.jpg)

### Problem Statement

We needed a periodical tournament system to engage players within a particular interval. We also have to make sure that, it's not heavy on our resources as well.

### Solved

☑️ Created a tournament system with different rank buckets within the game  
☑️ Design VFX and promotion animations which would elevate the user's experience.

### Outcome

📊 User Engagement and User progression rate got increased.

***

### Interested in knowing more? This is how we started it.

Once the problem is defined by the stakeholders, it is now time to see how are we going to approach the problem. For this, I've been paired up with the Game design lead.

We decided to split the problem into two:

1. Creating a tournament system within the game
2. Create a platform for game designers, developers, and UI artists in such a way that, they don't have to do lots of work on each tournament.

### Collecting Data & Research

As we planned out the approach, now we have to decide how are we going to surface this. But before that, I had to invest in user researching as I joined the company a month ago.

To understand our users, I started referring to user research reports from 2016 onwards, fortunately, our company had lots of research reports for the genre as Deer hunter is an evergreen franchise.

Along with the qualitative reports I got from the research team, I started monitoring the quantitative data using tableau to understand user interaction with different game modes. (As of now, Deer hunter has 4 modes.)

Based on our researches, we decided to create a tournament that goes hand in hand with the game progression while eliminating the Pay to win scenario. Pay to win scenario arises when the user who spends more money with in-game have an upper hand all the time apart from experience.

### Competitor Analysis

We started analyzing other games and their tournament systems to understand how are they running it. During this process, the questions we asked ourselves was:

 1. How are they integrating the tournament into their progression system?
 2. How often are they triggering the notifications
 3. How are they distributing rewards
 4. How are they giving an exclusive look at the event?
 5. How are they introducing the event
 6. Hows the usability
 7. What are the user goals and product goals?
 8. How can we set up an event
 9. what are the trivial information for setting up an event and how can we reduce user's efforts while setting it up.
10. How can we automate, the same process in the future?

We started looking at lots of games that have any events inside them. These are the few games I loved the most among 14+ competitor products.

![](/uploads/companalysis.jpg)

### Architecture

At this part, I and the Game design lead started creating the architecture for the system.

Based on our researches and studies, we decided that the event should be based on the gunning mode and the users will get assessed and rewarded based on their progress in the core loop.

![](/uploads/dhhooked.jpg)

#### Proposition

We will be building a tournament event that would appear on every weekend along with an internal tool that helps designers and developers too setup the event with relatively minimal effort than before.

#### Concept

* The event will be based on gunning mode
* Will trigger within a defined period, for eg: every weekend.
* At the end of the event, users will be rewarded
* The event will be announced exclusively
* Winnings will be celebrated
* There won't be any pay to win scenario

#### Structure

We incorporated the event loop into the core loop as shown below:

![](/uploads/fesstructure.jpg)

### Wireframes

![](/uploads/fesixd-2.jpg)

### Visual Design

![](/uploads/fesvd-3.jpg)

### Conclusion

Once the event went out, we noticed that the user engagement on event days is comparatively intense than other days. As this event is tied to the normal progression, user progression rates rose with monetary benefits. We also noticed a spike in elder players (user's who've been playing the game for a longer time) engagement.
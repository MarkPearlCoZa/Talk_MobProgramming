God morning, welcome to this session of getting the best of everyone using Mob Programming.

I would like to start off this session by sharing an experience I had 2 years ago while attending a conference in the US. Now when I travel I like to spend time doing a thing called Team Tourism. The idea behind Team Tourism is that there are companies all over the world that are doing pockets of brilliance, and if we just spend some time discovering them and applying them to our own teams it can have a dramatic impact on how we do work.

Now, in this instance I was lucky enough spend a day at a company called PluralSight. I knew a bit about Pluralsight before I set this up and I had this expectation that they had a focus on Software Craftmanship and that I would pair up with somebody. So imagine my surprise when I arrived there on the day and the team that I was going to spend time with does not do pariing, they do this thing called Mob Programming. And while I had no clue what Mob Programming was at the time, what I experienced on that day was not just a unique way of tackling work, but also one of the most enjoyable ways of learning and improving as a software developer. 

Today I'm going to share with you a bit about Mob Programming as well as some of the things we have learn't from working this way.

--------------------------------

# About Me

By way of introduction, my name is Mark Pearl, I'm a Dev Lead for MYOB in Auckand. My team maintains parts of MYOB's Practice Online System. If you find today's session interesting, I share many of my ideas and experiences on my Blog and on Twitter.

--------------------------------

I want to start off this session by framing it with a quote from Peter Block which says the value of anothers experience is to give us hope, not to tell us how or whether to proceed. 

I'm not here to tell you that you must do Mob Programming, or that this is the only way that it can be done. 
I am here to give you hope that if you would like to try this way of working, it is possible; 

--------------------------------

# Outline of the session

Now the outline of how this session is going to go is as follows... 

We are going to start off by briefly looking into what Mob Programming is, I'll take you through the roles and mechanics of the practice. 
Then I'm going to spend some time tackling common questions around Mob Programming as well as the things we have learn' specifically in our team as we have applied this practice.

--------------------------------

# What is Mob Programming

So what is Mob Programming?

Mob Programming is when three or more people work together to solve a problem at a single computer.

--------------------------------

And while this may sound like a radical idea, there are companies all over the world that are seeing major benefits from doing Mob Programming in their teams - so it is not as radical as you may think.

--------------------------------

# What are the roles in mob programming

Before I can take you through the mechanics of Mob Programming I need to explain the origins of mobbings and the roles.

Mob Programming evolved from pair programming. In pair programming you have two roles - the driver and the navigator. While the driver has the keyboard and is coding, the navigator looks at the code from a higher level looking for areas that the driver is missing.

The concept of driver and navigator bled into Mob Programming - I would like to change that, I don't think the metaphor of a driver and navigator works well when you have more than two people, and so I prefer to label the roles in Mob Programming as the typist and the rest of the mob.

--------------------------

## The typist

As the typist, all you need to be able to do is:

* Understand what the mob is asking you to do
* Translate it to code
* Become comfortable working with an incomplete understanding for short periods of time

Understanding what the rest of the mob is asking you to do can be a challenge. Sometimes the mob won't be sure what they want, or will give you conflicting requests. At times like this you need to remain calm and ask for further clarification on what the next step is; help get the rest of the mob to a place where they have consensus.

Another important part of your role is to be comfortable working with an incomplete understanding of the solution for short periods of time. Sometimes you will have a good idea of where things are going; other times you will have no clue. During the times when you have no clue it is important that you soldier on and trust the rest of the mob. 

As the typist, you should hold off prematurely challenging why you are being asked to do something by the rest of the mob. A good indication that you are prematurely challenging things is if you haven't translated it to code and typed it out yet. 

In my early days of mobbing, when I was the typist, I would challenge things before they had been translated to code. I found as a mob we would often have lengthy debates with little progress. After changing my approach to only challenging things after I had typed them out I noticed that the number of debates reduced significantly. Looking back, I suspect that when challenging prematurely one of two things was happening; we were probably saying the same thing but with different words and did not realize it because we couldn't see the code, or the approach the rest of the mob wanted me to take was appropriate and I was just not seeing it.

Now, I mentioned that you should be comfortable working with an incomplete understanding of the solution for short periods of time. The phrase "short periods of time" is important. Once an idea has been expressed fully in code, if you still don't understand what's going on, get the rest of the mob to explain it to you. You need to do this because you will be part of the rest of the mob substantially more than you will be the typist. As part of the rest of the mob you need to understand what's going on to be able to add value and help solve the problem at hand - filling in the blanks sooner rather than later will help the mob be effective for the entire session.

--------------------------

## The rest of the mob

As someone who is not the typist but still part of the mob you have three main jobs:

1. Help discover what the next logical step is to solving the problem.  
2. Talk at an appropriate level that everyone can understand.  
3. Always try to increase the level of understanding in the mob.

As part of the rest of the mob, you are part of the problem solving team; it's your job to look for things that still need to be done to solve the current problem; you do this working collaboratively with others in your mob.

You will find that sometimes the mob will loose focus and unintentionally move to a new problem before solving the one at hand; it is part of your role to look out for this, if you notice things getting sidetracked, bring it to everyone's attention and then as a group decide what to do; do you park the current item and finish what you originally started, or does it make sense to tackle the second item first?

> The key is that while you may see many angles and approaches, as a mob you should be trying to get consensus on what the next logical step is.  

Another very important part of your role is to talk at an appropriate level that everyone can understand. For instance, when directing the typist you should talk at a level of abstraction that the typist is able to digest. Depending on how long the typist has been with the mob, how in sync they are with what the mob is wanting them to do, and what their skill level is, the level of abstraction may change. 

An example of this may be that you see a potential refactor to simplify the code by extracting a method. Asking the typist to extract the method may be a sufficient level of abstraction. If the typist looks at you with a blank stare, go to a lower level of abstraction - become a little more explicit - "highlight line 114 to 127 and then press ctrl+alt+m to extract method". 

Finding the appropriate level to talk at is part of the challenge of mobbing. I've noticed that when a mob is just starting out it typically uses lower levels of abstraction, once it begins to find a common understanding it seems to use higher levels of abstraction. 

While not understanding is most apparent when directing the typist, you should be mindful of everyone else who is part of the rest of the mob. If anyone in the mob is not understanding, look for safe opportunities to further explain. 

On the flip side, if you are not understanding what is being said by someone in the mob have the courage to ask for it to be further explained. This falls in line with the third objective of always trying to increase the levels of understanding in the mob. 

Mob Programming is about a group of people doing things together and learning from each other. Talking at levels that others in the mob do not understand significantly impairs learning. Getting this right is a real challenge because we are all different. 

--------------------------

Woody Zuill, the father of Mob Programming, talks about a protocol he uses for working with others when he's in a mob, it's really simple..

> You should always treat people with Kindness, Consideration & Respect 

Now all three of these attributes are important but I would like to spend a bit of time on the attribute of consideration. Consideration is about considering the other person's point of view - it means we have to really focus on listening. And while it is extremely effective once you have the hang of it, sometimes getting started can prove to be a challenge because we are not used to working this way.

Finding the appropriate level of abstraction is part of the challenge of Mob Programming. When a mob is just starting out it typically uses lower levels of abstraction to direct the typist, once a mob begins to get its flow you will find higher levels of abstraction are used. 

So those are the two roles. They are simple, yet challenging. If you get them right, you will have a ton fun Mob Programming. If you get them wrong, keep at it. Being able to collaborate effectively takes time and practice. 

--------------------------

One other quote that I really like about Mob Programming comes from Llewellyn Falco. He has this rule that for an idea to go from someones head into the computer, it must go through someone's elses hands first.

# The mechanics of Mob Programming

So with this in mind, what does Mob Programming look like? Well, the honest truth is its different for different teams, but we found the following technique worked best when we started out. 

--------------------------

First, someone in the mob starts off as the typist. They are in this role for a time boxed period of time - we found ten minutes works well for us and generally we will have a monitor with a dedicated timer counting down the interval. 

During these ten minutes the mob works together to make headway on the problem at hand. At the end of the ten minutes we rotate the typist role and repeat. It's as simple as that.

How does this look like with real people?

--------------------------

I did a time lapsed recording of what a typical day of Mob Programming looked like when I was in my previous team. What you don't see in this video is that we have a large 60" screen in front of us with a smaller monitor to the left. As we work there is in general between 3 & 5 of us at the mobbing station at any one time with 1 person at the keyboard. 

We rotate the typist role reguarly, and since we all had different preferences on keyboards, we kept a range of keyboards available at the mobbing station so that when it is your turn to be the typist, you are comfortable.

You will also see us use a whiteboard to make notes on. We put things we want to come back to, or conversations we want to put on hold on the whiteboard.

Generally we found when we mob we take lunch at the same time. People leave as they have meetings or phone calls to make and them pretty much seamlessly re-join the mob. 

From experience we've learn't that when people re-join the mob it's disruptive to the mob's flow for us to re-explain what we did while they were away. Instead we've found it way more effective if they become the typist next and naturally get context while we work. 

Now, in the time lapse video most of the time people are focussed at the screen. When we work this way I am generally exhausted by the end of the day.

So, that is how a typical mob session looks. There are two scenarios are common enough that I want to make mention of.

-------------------------

The first scenario is when only one person in the mob knows the particular thing and that thing is the core ingredient of the problem at hand - everyone else has absolutely no clue. 

On these occasions it can prove a challenge for the mob to remain engaged if the expert becomes the typist typically because they move faster than everyone else can follow and the rest of the mob battles to contribute. 

At times like this, instead of having a normal rotation of the typist, we've found it works better if the expert does not rotate into the typist role at all. Instead, they remain as part of the rest of the mob and focus on sharing the knowledge, walking the group through how to solve the problem at hand. 

-------------------------

The second scenario is when nobody in the mob knows what's going on. Usually this happens because of one of two situations. 

Either the code is complex and hard to understand OR nobody has enough foundational knowledge of an underlying aspect of the technology being used.

When the code is complex or hard to understand I've found doing a quick "throw away" refactor to increase understanding works really well. How this works is at the beginning of the "throw away" refactoring we save our code and do a check-in to our version control; this makes it easy at the end of the interval to reset the code back to the state it was before we started refactoring. 

Next, as a mob we refactor the complex code in big bold steps; we are refactoring to get a better understanding of the code, identifying smaller pieces of functionality that can be encapsulated or extracted out; while we try to make the refactorings safe, we don't get bogged down by this. 

At the end of the interval as a mob we have a quick discussion on what we have uncovered. Now we **reset the code** and rotate typists and re-attempt to refactor the code, but this time we do it very carefully, focussing on the refactorings being safe. 

The other situation that often results in nobody knowing what's going on is when there is missing foundational knowledge of an underlying aspect of the technology being used. Often an indicator of this is the existence of an online manual that needs to be read or a series of tutorials that need to be done, etc. In these instances we've found it useful to do a time-boxed separation.

A time-boxed separation works as follows. First, you clearly identify what you need to understand before you can move forward. Then you disperse the mob for a pre-determined amount of time. The objective of each person during this time is try to gain the knowledge about the thing holding the mob back from progressing. If anyone gets to that point before the time box has elapsed they let everyone know and re-assemble the mob. If the pre-determined time lapses and nobody has got to that point yet, you still re-assemble the mob, each person shares what they have figured out so far and then as a mob you decide if you need another time-boxed separation or if you have enough context as a group to tackle the problem as a mob.

--------------------------

In general what we are trying to do as a group is default to collaboration. That means we prefer mobs, but if it doesn not make sense working this way we will revert to pairs, and sometimes even solo's

--------------------------

# Is this productive?

So I've spent a bit of time talking about the various practices and techniques of mob programming. I want to take the conversation in a different direction and tackle the most common business question I get when I talk about Mob Programming. 

Just the other day an accountant in the office was walking past our mob and in all honestly asked us "how can you justify working this way - surely you have just quadruppled costs?".To answer this it really boils down to how you measure developer productivity and measuring productivity of software developers is hard. 

Russell Ackoff, a well known organizational theorist said:

> Managers who don't know how to measure what they want settle for wanting what they can measure

Most of the important things related to developer productivity are difficult to measure. Because we struggle to measure these things we pick easier things to measure, and soon because we are measuring these things we begin to think the wrong things are valuable and that they are an indicator of productivity.

Let me share a quick experience a friend of mine had which I think polarizes this. He was working on a project that had slipped well behind schedule. He happened to sit next to the project manager and after one of the many frequent status updates of 'how they were progressing' on the work the project manager turned to him and asked "Can you just not type faster". 

Well, we know that measuring developer productivity by how fast someone types is a warped concept of productivity. We also know things like  hours worked or number of lines of code written are also not good indicators.

So are we more productive using Mob Progrmming?

I like this quote from Peter Block.

> Transformation comes more from pursuing profound questions than seeking profound answers - Peter Block

So let's tackle the question of productivity by asking the question what destroy's productivity for software developers?

Does anyone have any ideas or personal favorties?

{ Take answers from the audience }

Thank you - so it turns out there are a number of things that destroy developer productivity. I've made a list of things that I've encountered in my own development and interestingly many of these things became non-issues when we started Mob Programming. 

When we started Mob Programming we threw away forced WIP limits - after a few months I remember looking up at the board and being astonished that we were naturally gravatating towards one or two items in progress for the entire team of 10 - that was an eye opener for me. 

#### Multi tasking

In speaking to others that have used Mob Programming, a friend of mine sent a measurement he did of another team that started Mob Programming - just looking at the graph you can see at a glance when the team started Mobbing - all of a sudden the cycle time of work decreased. This is interesting.

Prior to Mob Programming I was in a team that used Kanban. A big part of Kanban is limiting work in progress. We actively tried decreasing work in progress with limited levels of success. In a team of 6 developers we typically had 7 or 8 things on the go at any one time - and we actively paired.

Let's take Incomplete Information.

### Waiting for information

You have started on a piece of work and realize you need to know some information before you can continue. Now the person that has that information is busy on something else or isn't available, so you wait for them to be available. To not be idle you start another piece of work. Now you have two things that you are working on. The irony of it is you have introduced context switches for yourself and the person you need to speak to. 

Indications are that context switches can cost you anywhere from 10 minutes upwards per switch so you only need a handful of these a day to loose a large portion of your day on just switching thoughts.

With Mob Programming because there are more people available in the mob you have more information at hand. 

Remember that work we did a few months ago on that UI thingy? Not a chance, but Igor sitting next to you does and remembers where it is in the code base. Darren can remember a discussion you missed about the item you are working on and reminds you to check out something on the wiki. Collectively you have a mob memory that is far superior to your individual memory. And the rule of thumb in a mob is.

> If you are not able to answer our own questions, then we are missing someone in the mob

To share an experience I had that illustrates this, we were working on a project and we needed some business rules. This was when we had just started Mob Programming. We booked some time to meet with the person that had that knowledge.

Now in the past we would have scheduled a meeting with the person, asked the questions we thought we needed answers for, then closed the meeting and continued with the work only to realize we missed one or two things, which would require additional meetings or communication which would require getting more time with that person and in past experience something like that could go on for days.

 In this instance we met at our mob station with the person who was a business person - let me highlight this, they did not understand code AND that didn't seem to be a problem. We opened up to the test scenairo's and showed what we had and what results we were getting - they quickly walked us through the scenario's we were missing - it took about an hour at which point we not only had the information we needed, we had implemented a working solution and pushed through to production. What had previously taken days was now done in hours.

Reducing the amount of information you have to wait for solves a lot of problems and it is just one of the many benefits we've gotten from Mob Programming.

### Quality of Software being written

Another benefit we've gotten from Mob Programming that has had a direct impact on our productivity is software quality. Again this is a big topic that we could spend a substantial time on. I would like to talk on one aspect of it. 

This is a graph Llwelyn Falco uses in his Mob Programming Guidebook. When we work on our own the best and worst of us gets into the code. When we work in a mob, only the best of us get's into the code.

Now does better code mean we are being more productive?

If you took the initial developer hours into considration and compare the time spent to solve a problem on your own compared to solving it in a mob, it takes longer as a mob. So why do I still think we are being more productive when Mob Programming? 

One reason is pretty much every study you will come across will tell you that defects detected during development are significantly less expensive to fix than once they get to production. My experience with Mob Programming is that it substantially reduces your defect rate. This makes sense.

When I write code on my own, the very best of what I do and the very worst of what I do gets into the code. 
When a group of people mob together, you get the best of everyone into all the code. The worst of everyone get's left out. 
In the XP world we talk about the principle of diversity which leads to more robust solutions - I believe this principle is maginified in Mob Programming.

> We get the best of everyone into all the code

It's only when you start taking the total end to end cycle of software into consideration that Mob Programming becomes significantly faster. There is less going to back fix and debug and this ultimately makes you more productive.

So I've just tackled two aspects of productivity related to Mob Programming. There are numerous others but for the sake of time I'm going to move on to other things I would like to cover in this session.

---------------------------------------------------------------------------------------------------------------------------------

# Isn't this just pair programming?

So, another question I get is, isn't this just the same as pair programming. Do I not get all the benefits from Mob Programming in pair programming?

The answer for me is that Mob programming is an evolutionary step forward from pair programming, and I would argue that there are at least two significant advantages that make Mob Programming easier than pair programming. 

Fristly, in my experience pair programming can be more confrontational. Have you ever observed two programmers get into a discussion about what's the best UI framework is, or the best text editor, or how to name something, or whether January should be numerically represented as a zero or a one! It can get really heated.

When these types of discussions emerge in Mob Programming the power of the mob steps in. It's no longer you vs. me, rather it's as a group we think this is the best way to go. That makes it a lot easier to move on and keeps emotions stable.

Secondly, compared with pair programming, the flow of the mob is better. When you are pairing and someone get's a phone call, or needs to go to a meeting or has some sort of disruption - the pair stops. With mobs, these interruptions are significantly decreased. The group can continue with people leaving and re-joining organically.

So don't get me wrong - pair programming is good and is more than appropriate in certain circumstances. In fact, I would argue that if we had wide spread availability of large screens and projectors when pair programming first started, the extreme programming world would probably have ended up with Mob Programming. 

Now this opens up an interesting thought - as we see innovation in virtual reality headsets and speed of networks, what is waiting for us in the next ten years in this area? What's the next evolution of collaborative coding?

> What's the next evolution of collaborative coding?

---------------------------------------------------------------------------------------------------------------------------------

Now before I end I want to share some learnings i've gained as we have done Mob Programming

# Ergonomics & working environment matter

I would like to briefly touch the topic of erognomics and you work environment. Ergonomics & you working environment matter. You need space to effectively mob. For instance, our mob station that we use right now is not ideal. It feels cramped. If you look at our picture people are a bit too close to each other. The table is a bit too small. This can lead to people feeling cramped or in your face. 

I've worked in teams where we substantially more space and it has a large impact on how well you can adopt this practice.

Does that mean if you don't have the space you cannot mob? 

No, you can still make it work with smaller spaces, but as you prove the practice you should be looking at adjusting the physical environment to make it a sustainable practice.

---------------------------------------------------------------------------------------------------------------------------------

# How many people can you have in a mob?

Next, I want to talk about how many people you can have in a mob. In my experience I've found that found 4-5 people in a mob works well provided you have the right setup. In our current space, we are probably pushing it with 4 people - it get's cramped and people disengage when we reach 5. In my previous organization we reguarly had 5 people and sometimes went up to 6.

I've also spoken to teams that have scaled up to 8 people at once although I haven't been in a mob that large but in general 4-5 people is effective and keeps the flow.

---------------------------------------------------------------------------------------------------------------------------------

# You may feel exposed 

Now before I end I want to give a quick warning, you may feel exposed with this type of work. 
If you cannot feel comfortable with someone else in front of the keyboard and you explaining to them why they should do something this form of collaboration is going to be really hard. That said, I would argue that if you cannot work in highly collaborative environments you are significantly impacting your future growth opportunities creating software and maybe it is something worth investing in.

For me, I've had an amazing journey for the last two years with Mob Programming. I've had the priveldge of learning, doing and having fun developing software this way. I would really recommend this practice to people and teams that want to develop better software.

Thank you for being such a good audience. 

## References

- [Real life mobbing](http://blog.crisp.se/2015/12/28/yassalsundman/real-life-mob-programming)  
- [something](http://benjiweber.co.uk/blog/2015/04/17/modern-extreme-programming/)  
- [something else](http://workingsoftware.co.uk/2015/12/17/give-mob-programming-a-go/)  
- [something else again](http://codecoupled.org/2015/10/12/journeyman-twingly/)

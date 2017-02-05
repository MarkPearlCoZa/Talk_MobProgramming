Hi everyone, I'm Mark Pearl, I'm a Dev Lead for one of our Auckland Practice Online teams at MYOB and I'm excited to be here to share with you the experiences I've had with Mob Programming.

I want to start this session by sharing how I was first introduced to Mob Programming - it happened roughly two years ago. At the time I had travelled to the US to speak at a regional agile conference. Something I like to do when I travel is a thing called 'Team Tourism' - basically the idea behind Team Tourism is to spend time with teams other than your own to see how they work in the hopes that you can learn new things that you can use in our own team.

Now, in this instance I was lucky enough spend a day at a company called PluralSight. I was expecting at PluralSight to pair program with someone, instead when I arrived I was told that the team I was going to be with didn't pair - they mobbed. I had no clue what mobbing meant but I was up for anything. Well, I had such an amazing time mobbing with these guys - I was productive within minutes and had an absolutely exhausting and enjoyable day. By the end of it I was hooked. Since then I have used some variant of Mob Programming in all the teams I've been with.

So today I'm going to spend a few minutes on what Mob Programming is. You are going to get to see how a typical mob works; then, with the remainder of the time I'm going to tackle some of the big questions around Mob Programming as well as a few things we've learn't from doing it.

So how many of you here have done Mob Programming before? 

{If someone} - Wonderful, I would love to catch up with you after the session to find out your experiences.
{If nobody} - Well this is exciting to have a new group.

Now before we get into the specifics let's start off with a quote that is often used when speaking about Mob Programming:

> The value of another's experience is to give us hope, not to tell us how or whether to proceeed - Peter Block.

This is really important - I'm not hear to tell you that you need to do Mob Programming or how you should do it. I'm hear in the hope that in sharing my experiences with you it will inspire you to try something in your own team. 

Now what you decide to try is up to you but there is a mindset that originates from Extreme Programming that led to Mob Programming being discovered. The mindset is turning up the good. In XP turning up the good included having two people work together on one thing, building your solution multiple times a day to name a few - these things at that time were considered "extreme". I'm hoping that this session will inspire you to discover your teams brilliance, what good you can turn up.

---------------------------------------------------------------------------------------------------------------------------------

# What is Mob Programming

So with that said, let's tackle what Mob Programming is. 

Mob Programming is when three or more people work together to solve a problem at the same computer.

As I've learn't more about Mob Programming I've discovered that teams all over the world are doing it. 

{Show mobbing around the world slides}

---------------------------------------------------------------------------------------------------------------------------------


# What are the roles in mob programming

Now that you have seen a typical Mob Programming session, I want to talk about the roles in Mob Programming. A quote I find best illustrates these roles is a one by Llewellyn Falco

> For an idea to go from someones head into the computer it must go through someone else's hands - Llewellyn Falco

In Mob Programming we only have two roles

1. The typist
2. The rest of the mob

--------------------------

## The typist

As the typist, all you need to be able to do is:

* Press keys
* Trust the mob  
* Become comfortable working with an incomplete understanding  

Pressing keys on a keyboard is easy and requires little explanation. Trusting the mob and working with an incomplete understanding is a lot harder.

### Trust the mob

Lets talk about trusting the mob. When you are the typist, trust that the rest of the mob knows what they are telling you. If you don't understand **WHAT** they are asking you to do, ask for clarification on what the next step is. If you don't understand **WHY** they are telling you something don't worry about it until you've finished the method or section of code. The right time to discuss and challenge design decisions is after the code is out of their heads and in the editor.

### Become comfortable working with an incomplete understanding

Even if you trust the mob, members of the mob might not be comfortable communicating to you in this style. They might try and explain everything they have done up till then to you before they start giving you useful directions - this slows things down, and depending on your knowledge of the system, can take hours or even days. 

What I've found is that instead of getting a complete understanding before you start work, encourage the mob to start solving the problem at hand - you will gain context as you type. You do not need a complete understand to be an effective typist. 

### What if you have an idea you want to implement

What if you have an idea you want to implement? Great! when that happens you let the mob know and swap out of the typist role with someone else. The person taking the keyboard becomes the typist and you become part of the rest of the mob.  

--------------------------

## The rest of the mob

As someone who is not the typist but still part of the mob you have two main jobs:

1) Help contribute to discovering what the next logical step is to solving the problem  
2) When directing the typist, talk in the highest level of abstraction the typist can understand  

### Discovering what the next logical step is to solving the problem

As part of the rest of the mob, essentially you are part of the problem solving team. It's your job to look for things the typist still needs to do. 
The key is that while you may see many angles and approaches as a mob, you should be helping the typist to only focus on one thing.

One of the challenges many teams new to Mob Programming face is working in close contact with the same people all day, every day. For you to be able to do this for any extended period of time you need to figure out a protocol or some way to work. 

There are many different protocols to do this, I find the protocol that 'Woody Zuil' has is really effective. And it goes like this... 

> You should always treat people with Kindness, Consideration & Respect > Woody Zuil

If we are going to get stuff done, we need to interact well. We have got to figure out how to do that and it's a challenge because we are all different. I've found that if you treat someone with Kindness, Consideration & Respect it makes it a lot easier for people to work together.

Now all three of these attributes are important but I would like to spend a bit of time on the attribute of consideration. Consideration is about considering the other person's point of view - it means we have to really focus on listening. And while it is extremely effective once you have the hang of it, sometimes getting started can prove to be a challenge because we are not used to working this way.

### Talk at the highest level of abstraction the typist can understand

Another very important part of being part of the rest of the mob is that when directing the typist you should talk at the highest level of abstraction that the typist is able to understand at that moment. Depending on how long the typist has been with the mob, how in sync they are with what the mob is wanting them to do, and what their skill level is, the level of abstraction may change. 

Finding the appropriate level of abstraction is part of the challenge of Mob Programming. When a mob is just starting out it typically uses lower levels of abstraction to direct the typist, once a mob begins to get its flow you will find higher levels of abstraction are used. 

At its essence what you are trying to do is communicate in a meaningful way. Don't speak above the rest of the mobs understanding, and keep trying to increase the level of communication and understanding. 

So those are the two roles. They are simple, yet challenging. If you get them right, you will have a ton fun Mob Programming. If you get them wrong, keep at it. Being able to collaborate effectively takes time and practice. So now that I've explained the roles - let's look tackle some common questions.

--------------------------

# The mechanics of Mob Programming

So what does Mob Programming look like?

Well, it's a thing in the Mob Programming community for people to do a time lapse video of them mobbing - and it just so happens that about a year ago I did one of my previous team mobbing for a day.

{ Start the video }

So here we are just after our stand up at our mobbing station, what you don't see in this video is that we have a large 60" screen in front of us with a smaller monitor on the left with a clock counting down ten minutes. As we work there is in general between 3 & 5 of us at the mobbing station at any one time with 1 person at the keyboard. Whenever the timer reaches zero the keyboard is rotated to another person in the mob. 

We keep a range of keyboards available so that when it is your turn to be the typist, you are comfortable typing.

Our work area allows people to visit, in this case a developer from another team passes by to say hello, happens to see what we are working on, and then later comes back with some info that we didn't know.

You will also see us use a whiteboard to make notes on. We put things we want to come back to, or conversations we want to put on hold.

In our layout our product owner would sit right next to the mob so that if we needed any information he was on call.

Generally we would all take lunch at the same time. 

People leave as they have meetings or phone calls to make and them pretty much seamlessly re-join the mob. 

What we have learn't is that if someone leaves the mob, the best way for them to catch up when they re-join is not to ask what happened while they were gone. Instead it's way more effective if they become the typist next. This falls into the roles we have in mob programming - something I will talk about shortly.

So I think you have have enough of an idea of what Mob Programming looks like in the wild. Notice that the most important thing was worked on the whole day moving closer and closer to completion. Also it is very active - and while a video does not convey this, by the end of the day everybody in that mob was exhausted.

---------------------------------------------------------------------------------------------------------------------------------

# The productivity question

So the most common question I get when I explain how Mob Programming works is the productivity question. How can one be productive this way - surely if you have so many people working on one thing together you have massively increased the cost of developing software while decreasing productiivity? 

Measuring productivity of software developers is hard. I love this quote by Russell Ackoff. 

> Managers who don't know how to measure what they want settle for wanting what they can measure - Russell Ackoff

Most of the important things related to developer productivity are difficult to measure and so because we can't effectively measure them we pick easier things to measure, and soon because we are measuring these things we begin to think the wrong things are valuable and that they are an indicator of productivity.

Let me share a quick experience a friend of mine had which I think polarizes this. He was working on a project that had slipped well behind schedule and was unfortunate enough to sit next to the project manager. After one of the many frequent status updates of 'how they were progressing' on the work the project manager turned to him while he was sitting at his desk and pleaded "Can you not just type faster". 

Well, we know that measuring developer productivity by how fast someone types is not an effective. We also know things like counting the number of lines of code written is not any good indicator either. 

In speaking to others that have used Mob Programming, a friend of mine sent a measurement he did of another team that started Mob Programming - just looking at the graph you can see at a glance when the team started Mobbing - all of a sudden the cycle time of work decreased. This is interesting.

Prior to Mob Programming I was in a team that used Kanban. A big part of Kanban is limiting work in progress. We actively tried decreasing work in progress with limited levels of success. In a team of 6 developers we typically had 7 or 8 things on the go at any one time - and we actively paired.

When we started Mob Programming we threw away forced WIP limits - after a few months I remember looking up at the board and being astonished that we were naturally gravatating towards one or two items in progress for the entire team of 10 - that was an eye opener for me. 

So are we more productive using Mob Progrmming?

I like this quote from Peter Block.

> Transformation comes more from pursuing profound questions than seeking profound answers - Peter Block

So let's tackle the question of productivity by asking the question what destroy's productivity for software developers?

Does anyone have any ideas or personal favorties?

{ Take answers from the audience }

Thank you - so it turns out there are a number of things that destroy developer productivity. I've made a list of things that I've encountered in my own development and interestingly many of these things became non-issues when we started Mob Programming. 

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
#Chapter 2 Project Plannning

##Planning the Prime Objective of an Application

{width: 8, float: left}
![](jordan.png)

**Jordan Hudgens:** Hi, and welcome to this guide where we're going to find the prime objective in a UX project.

This is going to be one of the very first things that you do when you're tasked with either building a new application from scratch or even just adding a small feature to an app. Getting this type of context is critical. It's something that Jesse and I have met with and worked on a number of projects with, so let's get into what the very first preliminary stage looks like.

{width: 8, float: left}
![](jesse.png)

**Jesse Cooke:** The first thing you're going to do with any of these projects is that you really need to find your feet inside of the project. You're going to deal with a lot of different ideas. Whether you're working inside of a company with a single product, or if you're taking client work, or even just throughout your career you're going to be confronted with lots of different ideas. That's one of the beautiful things that we love about software. However, you do need to identify what the prime objective of this application, or change, or whatever it is is, you need that 10,000 foot view to get your bearings because everything else is going to revolve around that.

As a consultant, you should be able to step in and say, either, this feature is not building towards that objective, or I'm not understanding how this is all fitting together. To start, before you do anything, you need to know what's happening. I know it seems kind of obvious but it's a little bit more nuanced than that.

One of the pitfalls that I think a lot of people have is also going the other direction where they really want to get into the weeds of the business. Sometimes I really have to hold back a lot of my clients, and tell them "I don't need to run your business for you."

I do have a background in business, so I'm inclined to talk about that, and, in some respects, I do talk about that a little bit, when it is applicable to the project. By understanding the intentions of the product owner whether that's the client, or the manager who's bringing it to you. Knowing their intentions will help you make more clear decisions. Like I said, it's just getting your feet under you. It's just understanding what environment you're working in and what the scope of this product is.

{width: 8, float: left}
![](jordan.png)

I remember a time where I did a horrible job. I was working for a client whom I'd built out a number of applications for over the span of a couple of years, so I thought I was pretty familiar with their wants and needs.

They had e-mailed me this feature request and I just assumed I knew what they meant. I didn't get any contacts, and I didn't find the prime objective. What ended up happening is: I spent two full weeks of development time building out this massive new feature. I sent it to them and... they just sent a question mark back.

{width: 8, float: left}
![](jesse.png)

Haha!

{width: 8, float: left}
![](jordan.png)

Which is never a good thing. I felt I built it perfectly, I used test-driven development, and all this--

{width: 8, float: left}
![](jesse.png)

Is there any punctuation mark that would have been good? Just one?

{width: 8, float: left}
![](jordan.png)

Maybe? Like a smiley face? I would've been good with that.

So it turns out I did not understand what they really needed. They just needed a very simple way of exporting data, but the way they described it, it seemed like they needed this completely different billing system. If I would've been better about this stage, for that one feature, it would've saved a lot of time and heartache.

{width: 8, float: left}
![](jesse.png)

Right! I remember when when you first came to me with DailySmarty. It was really critical for me to understand: who is going to be using this and what are their intentions when using it? Not necessarily what OUR intention was in building DailySmarty - that's important as well, and I need to understand that - but what is the purpose of this? Is it completely social? Is it to build a database? Is it to answer questions? Is it to build credibility? Those questions give me an idea of the type of audience that's going to start using this product and what their individual intentions are going to be in using it.

If I know right from the beginning that this is going to be really heavy on social, then I need to be asking lots of questions about that: What features are in here that are going to engage that social aspect? If the intention is to be a database to store lots of things, then the interaction isn't as important. Then, we need to really optimize for showing the links that are being shared, and directing someone who has no idea what this platform is. You're going to have a lot of people from outside the app coming into it, so they're going to experience it differently than someone who's using it every day, right? So I need to identify the users within users.

Let's take Reddit, for example. You have this platform where people are interacting very heavily on a daily basis. They know the layout, and they know how to use the application because they're using it every day. If, all of a sudden, you know that people are sharing links, or that the business objective is going to be sharing links, then you can have lots of inbound traffic of people who've never interacted with this app before. They're both the same type of user from a database perspective but they are two completely different people. One is just some casual person who saw a link on Facebook, clicked it, and is now reading an article. The other person is deep in it, building up their karma.

{width: 8, float: left}
![](jordan.png)

Right.

{width: 8, float: left}
![](jesse.png)

And so these are two different users even though, on paper, they might be called the same user. I won't identify that unless I know how this app is going to be used and what the long term goal of it is.

{width: 8, float: left}
![](jordan.png)

That's so critical. I've had so many projects where, as soon as I found out what that primary objective was, it also helped get me excited about the project, too. When I found out about something and I fell in love with the concept, it started to give me ideas on different features to add and how to improve the overall user experience. Whether the client is a freelance client or if it's your boss, they're going to have a certain feature set in mind, but they're still just one person. So when you find out what the full goals are, you can bring a ton of other features to the table as well. Just like when I originally took the idea for DailySmarty to you, the feature set grew quite a bit just from you and me talking. That wouldn't have happened if I hadn't told you what the goals for the system were.

{width: 8, float: left}
![](jesse.png)

Another example is this really cool app that we were able to work on. The client came in and he had an idea of what he wanted his app to be. He wanted to stream city council meetings. He was a lobbyist, he was always in city council meetings, and he came up with this idea. He's said "People have no idea what the city council is talking about. We need to have an app that makes it really easy to livestream." So that's what he came in with. Now, in that that first initial conversation, I pointed out a big hole in his logic. He was assuming his potential users didn't go to city council meetings because it's hard to get there, but that's not the case. The reason why people don't go to city council meetings is that they don't care about 99.9% percent of what they're talking about. That's why people don't interact with their local governments: most of the things that they're talking about aren't interesting to them. So I told him, "You can build this up, but it's not going to reach your prime objective. Your prime objective is to increase the engagement of local communities with their local governments. This is not going to do that."

Instead, what you need is in-the-moment notifications when something IS important to you. So instead let's build a user profile. When they sign up for an account, they indicate "I'm interested in zoning and hunting and that's it. That's all I care about." Then, when when they're talking about those things in the city council meeting, users can get a push notification and they know **at that moment** to tune into that stream. **That** is going to increase engagement. I wouldn't have been able to solve that problem for him if I didn't understand what he was trying to accomplish.

{width: 8, float: left}
![](jordan.png)

That also brings up a very good point about the entire goal of UX. I think there's a lot of confusion around people who have never gotten into it much before. Just like people think user interface is just picking out pretty colors and fonts, I think a lot of people think user experience is just saying "Oh, they clicked on this page, and then they went to this other page." That's not true at all. The user experience is part of the development process. It's really very closely aligned with the business side.

{width: 8, float: left}
![](jesse.png)

Yeah!

{width: 8, float: left}
![](jordan.png)

During this process is where you can actually create custom features. This is where you get some of the uniqueness that you're going to be building into these applications. I don't want you to think of user experience as just setting up what pages are going to be directed where. It's much larger than that. It comes down to the overall user experience, like you're talking about with the livestreaming application. You completely changed the way the process worked, because you made an interest-based system instead of just a livestreaming app. None of that would have been possible without this first step.

{width: 8, float: left}
![](jesse.png)

Absolutely. And, at some point, a line gets drawn where it starts becoming "scope creep". My CTO has to hold me back from that all the time, because I think of new things to add. We can discuss what goes into a good MVP and things like that, but it comes down to: this thing needs to be built strictly to serve the objective and nothing else, right? In those initial meetings, you can bring up these things that are going to better help them reach their objective, but unless you're going to get paid for it, you obviously don't want to build on top of that. It's about meeting those initial objectives. Once that line has been drawn in the sand on any level--the creative director, the CTO, team leads, or the developers themselves--at some point, it becomes detrimental to start creating more features.

{width: 8, float: left}
![](jordan.png)

We all want to build all the cool stuff that we can think of, but that's where it gets into some of the project management and system design side of it.

{width: 8, float: left}
![](jesse.png)

Right, right.

{width: 8, float: left}
![](jordan.png)

It is a very fun process and it is critical, but if this part isn't done right, then nothing else is really going to work, because what you're building might not be targeted at the goal that really needs to be achieved.

{width: 8, float: left}
![](jesse.png)

Right! And I wanted to touch on the passion that you were talking about because it's not a small thing. It makes your job into something more than just a job. All of the times that I have stayed late or pulled all nighters, it wasn't because someone made me. It's because I was really excited about what I was doing. That's the same thing with my developers. I don't ever ask them to stay late, but when they are staying late, it's because they're doing something that they're really excited about. If you're two inches away from your code, you might not be excited about it, but if you know what it's doing and you see the bigger picture, then that can be a huge piece of what really drives you and gives you that passion to be a builder, because that's what we are.

{width: 8, float: left}
![](jordan.png)

Absolutely.

In this guide we really wanted to focus on that prime objective and make sure that you have that as a firm foundation. In the next few guides, we're going to see what steps you're going to take once you have the prime objective in mind.


##Guide to User Stories and Analyzing a Feature List

{width: 8, float: left}
![](jordan.png)

Hi, and welcome back to this UX course for developers. In this guide, Jesse's going to focus on user stories and also hit upon the difference between user stories and a feature list. It's a subtle but very important difference. As a new developer, you may get your feature list think that's really all you need. When I was younger, I thought that's what I wanted. I always would tell a client, "Just send me bullet points with what you want the application to do." As much as it seems like that would work, using user stories can actually be a much more effective way of doing it.

{width: 8, float: left}
![](jesse.png)

Absolutely. Like you said, when you think of an app, you think of what it does, right? You think, "It can do this, it can do this, it can do this," but an app is not a one-dimensional thing. It's usually being interacted with by multiple different people. You need to identify all the different people that may ever touch this thing, all the way from the bottom, with a guest user, to the top, with a super admin.

So once you've identified this prime objective--and you may have the bullet points of this feature list that the client, or your manager, or your boss has brought you--and that needs to be converted into user stories. Let's take messaging. The client says, "This app needs to be able to message." That's a feature. Jim, he's a standard user, non-paid. Can he message? Yes. Jim can message.* ***There*** is a user story.

Then you have Susan, who is the super admin. She needs to message, but she also needs to CRUD messages. She needs to be able to do all those things, so she might have deeper access. Maybe she needs to be able to read everyone's messages. Hopefully not, but maybe. But she, at least, needs to be able to CRUD them. Identifying that one feature--which is just "messaging"--can turn into eight different user stories for eight different users. This is an obvious one, but just to show this line of reasoning, you say, OK, we want to have messaging. We have Jim, who's a standard user, and we have Susan, who's a standard user, and they can message back and forth. Can Jim flag inappropriate content inside of messaging? Yes he can. So he flags it. Well then what happens to it? You have to follow that data. Now that it's flagged, who manages the messaging? So Jim can send messages. Jim can receive messages. Jim can flag messages. Can Jim review his flagged messages? Maybe, maybe not.

{width: 8, float: left}
![](jordan.png)

Right.

{width: 8, float: left}
![](jesse.png)

So Susan, who is the super admin, she needs to be able to do something with it. She needs to be able to review the flagged messages and CRUD these flagged messages.

{width: 8, float: left}
![](jordan.png)

Absolutely. There's some very nice overlap here on the UX side with more formal software engineering tasks. When it comes to user stories, if you understand UML, you can use use case diagrams to formalize these user stories. You can set up your actors--the superadmin, the regular users, the guest users--and then you can just have lines that go to each one of those use cases. With this, you can have an entire chart that outlines all of your user stories.

There's a lot of overlap between development, UX, and software engineering. You're going to go back and forth between these worlds quite a bit. I don't want you to think "Oh, right now, I'm just in UX mode, and all I do is I get on Sketch and I do nothing else." There's definitely a time and place when you do that, but then there's also a time where you switch over into LucidChart and you start building a UML use case diagram to design and model your user stories. Being able to understand that there is overlap there is definitely very helpful.

The other thing I really liked about your example is how we started with one feature: messaging. If you ask a client about messaging, they're probably not going to give you a lot of detail on what features need to be there. But if you say "What exactly do you want this guest user to do?" then it makes it a lot easier for them to tell you about that. I think it comes down to how people think. It's a lot easier for them to slide into the mental mindset of a guest user and say "Oh, this is what happens when I visit a page! **This** is what I should see as a guest user."

{width: 8, float: left}
![](jesse.png)

And it requires a lot of empathy, right? Don't just think about how ***you're*** going to  interact with the app. You've got to be able to step outside yourself. It's about being able to see the app as all of the different users that may interact with it.

{width: 8, float: left}
![](jordan.png)

Yes. It's just another step along the path of building a proper UX. We started with a prime objective and right after that we went into those user stories to be able to figure out exactly how this system is going to be interacted with.

{width: 8, float: left}
![](jesse.png)

There's one more thing that I have to bring up: the idea of having that crossover technical ability. Again with the messaging example: not all messaging is created equally. If you're using web sockets, you're going to have a different messaging experience. As a creative director, project manager, or developer, this may not be perfectly communicated to you and you'll need to ask those questions: Are we going to use web sockets? Is this going to be live messaging or is this going to behave more like an inbox?

Those types of questions get asked to the client because, a lot of times, it's a budgetary thing. They're asking questions about cost, and how much time it will take to build it with live messaging, versus an MVP where you can prove out the concept of messaging, and it will be a lot cheaper but it won't be as live as text messaging on your phone. Not everyone knows about web sockets, and they don't know what they don't know, so understanding the technical aspects so that you can bring up those types of questions is very helpful.

{width: 8, float: left}
![](jordan.png)

Absolutely! That's a very good point one when this process needs to occur and how important it is that it doesn't happen too late. Some of the things you just brought up will actually determine the type of technology stack that gets used to build the entire system.

{width: 8, float: left}
![](jesse.png)

Right!

{width: 8, float: left}
![](jordan.png)

So if you do this too late, then you might pick out the wrong stack because you either thought it was going to be much more or less resource-intensive than it ended up being.

I remember a great example of this, for me, where I had a pretty large project. Because it was so large, I didn't get the user stories first. I thought, "I want to build this in Angular, and I want to have this micro service backend with multiple Rails APIs," and I had it in my mind that that's what I was going to do. We started going into the user stories and it didn't need anything that Angular  brought to the table.

{width: 8, float: left}
![](jesse.png)

Haha!

{width: 8, float: left}
![](jordan.png)

It didn't need web sockets. It didn't need live-updated data. It didn't need any of that! And, because we caught it before I started building it, I was able to build it in pure Rails, and I delivered the full set of functionality they asked for in half the time it would've taken me to build what I originally had in mind. And I was able to do that *because* we got into the user stories first.

{width: 8, float: left}
![](jesse.png)

Exactly.

##How to Create Effective Sitemaps

{width: 8, float: left}
![](jordan.png)

So far, we've talked about user stories and finding prime objectives. In this guide we're going to learn what a sitemap is and how to construct one. We'll talk about some of the goals you should have when you're building one and how you can translate those into building the user experience. We'll also discuss providing the sitemap to your developers so that they know what screens to build.

{width: 8, float: left}
![](jesse.png)

The frame of mind that you should be in when you approach a sitemap is that it should answer all of the user stories. We've created all these user stories, so I'm going to create a separate sitemap for each user. Whatever those user stories are, I start going through them. Jim needs to be able to message, so I need to make sure that there is a messaging page. Once I create that page in the sitemap, I indicate the main unique actions that happen on that page.

There's a lot of "dealer's choice" here. Most people are going to build their sitemaps a little bit differently. They're going to use different programs. I really like Lucidchart because of its team aspect and that you can have multiple people participate on it. Then it becomes about how you indicate what a page is, and what actions are.

Another thing is: how granular do you get? You might think, "OK, I have all these pages, and I can click 15 things on each one of these pages." Well, sure, but you don't have to indicate that on every single page. That's a little too granular. In my opinion, it's not very productive, because you could click the logo on every single page and it'll take you to the home page. But I don't need to indicate that on every single page of my sitemap.

![](https://s3-us-west-2.amazonaws.com/devcamp-pictures/UX+for+Developers+images/How+to+Create+Effective+Sitemaps+-+JukeBox+Queue.PNG "JukeBox Sitemap")

Here, you can see that there are two main shapes: rectangles and diamonds. This is my own personal thing. You may be working inside of a company that already has these conventions established, or you'll be coming up with them yourself, but I like using rectangles for pages and diamonds for indicating user actions that solve user stories.

You can see that these actions either take you to other actions or to another page. When you map it all out, you should be left with a picture of all the pages that need to exist and the key actions that can be taken from each of them. This will really give you a clear idea of how you're going to solve all of the user stories you've already created.

{width: 8, float: left}
![](jordan.png)

That's awesome. It's a great example of how you've translated user stories directly into something functional that you can use.

Now, Jesse, after you've built the sitemap, which stakeholders do you meet with and get feedback from? Obviously, I'm assuming the client, but do you also take this to the developers? Who else are you connecting with?

{width: 8, float: left}
![](jesse.png)

It'll hit the developers after it's been approved by the client (or the product owner or whoever is running that). You'll work through the sitemap with them, with the user stories right alongside it. A lot of times, clients will get kind of glossy when they see this. It's not the sexy thing that they see in their mind. But the main thing is that you're saying: here's our list of user stories for Jim. Jim wants to be able to message. Bam, this is where he goes to message. What else can he do? He can send a message, he can receive a message, and he can flag a message, so let's indicate those. What happens after the flags a message? Does he go to another screen? Does he go to an approval screen, or something else? We can indicate that. We have our messages screen represented in our sitemap, and we have an action under it: "flag message." Then we can have an arrow that takes us to review flagged content, and I can represent that.

When I get into later phases of the development I'll have a very clear idea. It's so much better than just taking notes, or even skipping past it. You might be inclined to say "I've got my user stories, let's get this done," but this is helping you fill in the gaps so that you don't have to rework your designs. You don't end up saying, "Oh dang it! I totally forgot about this entire thing. I've got to go back through all my designs," because design is a lot harder to manipulate than just going in and adding rectangles and diamonds.

{width: 8, float: left}
![](jordan.png)

That brings up a great point. We talk about stakeholders and how important it is to have this kind of foundation to look back at. I remember, for one pretty large-scale application, I had a client who was not technical whatsoever. I had already built close to half of the application, and, while ***I*** thought it was going well, this client had nothing to look at that he could understand. He couldn't go look at my code, the application wasn't ready to prototype, and because of that he kept asking for what was essentially a sitemap. He wanted to see lines going to boxes to see what one user could do and what another couldn't. I ended up having to build something like this halfway through the project. If I would've done it at the beginning, it would have helped me in my development, but even more important is that it would have helped the client understand all the processes that were taking place.

{width: 8, float: left}
![](jesse.png)

Right, right. And obviously, after this has been approved by the client, you're taking this to team leads, and the team leads are taking it to the developers. So, regardless of how interested you are in sitemaps, as a developer you will need to know how to understand them. And they're not terribly complicated. Of course, that may also depend on who's creating the sitemap for you, but I don't like making mine terribly complicated because that's just miserable.

{width: 8, float: left}
![](jordan.png)

Right.

{width: 8, float: left}
![](jesse.png)

It's important to be able to understand this because, the better the communication bridge between creative and development, the smoother every project is going to go. The better you can understand the sitemaps that are being created, the more valuable you are as a developer because you won't have to walk through it over and over and over again. You're going to see holes and all the things we talked about before, and you'll be able to get a quick picture of the project and know what's being communicated.

{width: 8, float: left}
![](jordan.png)

Absolutely. I love the tools we have now that we didn't have a few years ago. You could see in the example sitemap that there are spots for comments. When I was working with the design team on this specific diagram they would ask me questions like, "What type of functionality are you looking for right here?" when they didn't have all the clarification they needed. And that's a great thing, because, not only are these tools good for building the sitemap initially, but they're also good for collaboration *while* it's being built. You can clear up a lot of mistakes in the very beginning by being able to communicate properly with all the stakeholders.

{width: 8, float: left}
![](jesse.png)

Right! I definitely get pinged every once in awhile by developers asking, "What is going on here? What is this page? Where did this come from?" It's really nice when you don't have to cut through anything, you can just go right to the question and you're all on the same page really quickly.

##How to Design Low Fidelity Wireframes

{width: 8, float: left}
![](jordan.png)

We've talked about how you can build your diagrams to show pages and what the user flow is, and how you integrate that from the user stories. Now we're taking it one step further with low fidelity wireframes.

The first time I heard "low fidelity wireframe" I had no idea what that was. Give us a high level description of what they are and why you would choose to make one instead of something more detailed.

{width: 8, float: left}
![](jesse.png)

Again, this is a "dealer's choice" kind of thing. Different designers and creative directors might just say "wireframe", but I like breaking it up into both low and high fidelity wireframes. The reason is that with a low fidelity wireframe you are ***strictly*** focusing on the user experience. It's very easy to get carried away and start to design things. You're excited, so you're putting all these objects on there, but the main objective of building low fidelity wireframes is that you know all of the objects that need to exist on every page. It doesn't necessarily matter how big the button is, you just need to know that the button needs to be there.

So the idea with the low fidelity wireframe is to not be thinking of the user interface at all. I mean, maybe 5-10% percent, and saying "I'm going to make a square to mean a button," but that's the extent of it. The important part is that you're actually saying, "For these actions to happen, what objects need to exist?" That may include my nav bar, or some buttons, or a profile picture that's just represented with a circle or something. It's very very low fidelity.

This approach forces you to identify the holes. It helps you figure out things that you hadn't realized while building the sitemap. You might think you've got everything answered once you're done with the sitemap, and then find that a little more context helps you find some more problems.

{width: 8, float: left}
![](jordan.png) A

bsolutely. For anyone that's gone through our UML or Problem Solving course, there are some pretty big areas of overlap here. For example, in the UML specification, it's actually a requirement that you start with your most high-level, generic things first. And that's for the practical reason. You may end up wasting a lot of time if you get too detailed over how a button looks, because you may find out later on that you don't even need the button at all.

![](https://s3-us-west-2.amazonaws.com/devcamp-pictures/UX+for+Developers+images/How+to+Design+Low+Fidelity+Wireframes+-+JukeBox+Player+1.PNG "JukeBox Player Wireframe")

{width: 8, float: left}
![](jordan.png)

I remember the very first time I was ever sent a low fidelity wireframe. I was surprised, because I usually was getting more detailed mockups, like Photoshop screens. They sent me this wireframe and it looked *really* ugly.

{width: 8, float: left}
![](jesse.png)

Oh yeah.

{width: 8, float: left}
![](jordan.png)

But that's good! That's the way it's supposed to be. Like you mentioned, you don't care about user interface at this point.

{width: 8, float: left}
![](jesse.png)

Right.

{width: 8, float: left}
![](jordan.png)

You're just trying to get one step closer to the goal line and make sure that, when you finally hand it off to the developer, they know exactly what they need to build.

{width: 8, float: left}
![](jesse.png)

Exactly. And it allows some of the backend tasks to get started while you're doing the high fidelity mockups. Getting that high fidelity design finished can take some time, especially when you're working with the client. They can get really picky at that point, so that process can go a little bit slower. But if you have these low fidelity wireframes, the backend developers can get started because they know the objects that need to exist. They know the data that needs to be there. They don't care how it looks, but they have something that they can start with to build out the app while you're working on other parts of it.

And, really, I can't emphasize this enough: the low fidelity wireframe is so important because it forces you to focus on the user experience. Even something as simple as Tinder; there are a lot of user interface pieces to it, but let's take the single user experience concept of "what's the best way for me to cycle through profiles?" That gesture kicked off a whole slew of apps using that exact same gesture. It wasn't necessarily a user interface decision. It was saying, "I'm on this screen and I need to take some sort of action. I don't want to use a button, so I'm going to use a gesture."

This wireframing process forces you to think through those specific things and say, "Man, there's a lot of stuff on this page, this is really complicated." or, "Wait a second, how do I know what number to put in here if I haven't pulled this data from this other screen?" It's forcing you to think through that page-by-page user flow. At this point, you'd be wasting your time designing buttons and making everything balance properly, only to discover that you need 10 more objects on the page. That's going to affect everything, and that five hours of design you just did is now worthless because you have to go and change everything.

So this forces you to ***just*** focus on that single user experience problem and create a nice flow from screen to screen to screen. You're going to come back and design it, or a designer is going to design it, but from the user experience standpoint this part is absolutely critical to get right.

{width: 8, float: left}
![](jordan.png)

Yes. That's one thing I've noticed as a team lead on projects. When low fidelity wireframes were used, it automated a lot of the other processes for the development team. I used to wait until the designer was done with the entire system before I really started coding. That was mainly because I'd had many bad experiences where I thought they were done, and I would start building it, but then I'd have to wipe the slate clean and start from scratch because they had changed something very significant. Now, when I work with these types of low fidelity wireframes, it gives me a head start. I don't have to wait for the designs. I can be confident that a significant portion of the user experience in that interaction is accurate. So I can take those wireframes and code straight from them. I don't have to worry about the design; I know I'll take care of implementing that part whenever the high fidelity wireframes are done.

You've mentioned elements such as images, buttons, and even gestures. Are there any other types of elements or any other types of actions that you try to capture?

{width: 8, float: left}
![](jesse.png)

Maybe not actions as much as identifying what data you're pulling in. So, if it's a dashboard, you're saying, "I need to be able to show this piece of metadata and this piece of metadata," which helps the backend developer. He doesn't care what it looks like, just that it needs to be in there.

![](https://s3-us-west-2.amazonaws.com/devcamp-pictures/UX+for+Developers+images/How+to+Design+Low+Fidelity+Wireframes+-+DailySmarty.PNG "DailySmarty homepage")

{width: 8, float: left}
![](jesse.png)

Take DailySmarty for example. One of the objects in your wireframe might be a post. On the post index page, what type of metadata do I need to pull in? Do I need to pull in categories? Do I need to pull in post author? Do I need to pull in the date? With a low fidelity wireframe, I can actually show you that you need all this data here. I don't know how it's going to look, but I can represent it really quickly. I don't care about font sizes, I don't care about much, but it gives you a clear idea of the things you need to pull in to actually start building it.

##Guide to UX Mockups

{width: 8, float: left}
![](jordan.png)

In the last guide, we walked through the concept of wireframing, and specifically low fidelity wireframes. Those allow us to capture a high level view of the system and see the way pages flow, the user interactions and gestures, and where different components on the page are going to be placed. They don't have much detail.

In this guide we're going to discuss high fidelity wireframes, or, "mockups". These are much more detailed. They essentially represent what the system will look like.

We're not going to go into a lot of detail here, because that's what the User Interface course is for. That course teaches you how to create these types of mockups, pick the right color schemes, build a style guide, and design the rest of the interface. We're not going to cover all of that right now. We're simply including this section so you know at what stage to build these types of designs.

{width: 8, float: left}
![](jesse.png)

Following the low fidelity wireframes, you're going to get into these high fidelity designs, or these mockups. Like I said in a previous guide, clients, managers, and bosses start to get really handsy at this point because this is a really fun part.

Generally how I run these projects is that I get sign off on the sitemap and I get sign off on the low fidelity wireframe, so that I'm confident about what's supposed to be there. Armed with that, I create just a couple high fidelity designs of key pages sothat I can give the client a good idea of what the app is going to look like. At this point, I like go to the Bat Cave and tell the client "I'm going to disappear for a little while."

Hopefully, by this time, I've established some trust that they don't need to be involved on every single screen. They know I'm going to match the aesthetic from those first couple of mockups and that I'm going to apply that same design to the others. I'm really just putting the paint on the wireframes. I'm moving things around--maybe I had a button in the low fidelity wireframe, and I didn't care where it went, so I just threw it in the middle.

When I start to design it, there's a domino effect where every decision is going to affect another decision. That's why we did the low fidelity wireframe, because we don't want one change to affect a bunch of things that you put a lot of time and effort into. This is the point where you can start to get really meticulous and start to care about the balance, because you know all the Lego pieces that you're working with. You know when you assemble them that it should stay the way it is. If it doesn't, then it's probably because you've allowed someone like me to add some more scope which I tend to do.

{width: 8, float: left}
![](jordan.png)

Haha!

{width: 8, float: left}
![](jesse.png)

So that's where we flow into this. You want to make sure that everything leading up to this has been signed off--don't skip the low fidelity, because when you hit this point you want to work with confidence and actually put the time into it to make each one of these things look great.

{width: 8, float: left}
![](jordan.png)

That's perfect.

We wanted to keep this section short, since this is what the User Interface course is all about. The main takeaway is that, after you have the sitemaps and the wireframes approved, and the developers are working on the backend, ***that's*** when you get down to business and start designing mockups, style guides, and so on.

##UX Skill Development

{width: 8, float: left}
![](jordan.png)

So far in this course we've talked about what you should be discussing with your clients or stakeholders in the beginning, all the way through when you actually design the system.

We haven't gotten into how you can practice these things and improve as a UX developer. Jesse has a lot of experience in this and is definitely one of the most talented UX/UI guys I've ever had the pleasure of working with.

I want to get your opinion on how you've improved. I know you were probably born with *some* innate talent, but I think you have probably developed it because of how hard you've worked and the different steps you take each day to improve.

{width: 8, float: left}
![](jesse.png)

I think that developers sometimes are a little spooked when the letters "UI/UX" come flying around. But, honestly, UX is a very similar skill set to development. Lots of critical thinking and things like that. However, I want to start with what I believe is the most important part of being a good experience designer, and that's communication.

Improving your ability to communicate is what allows you to get the information from the client. Most of what I do all day is talk. I'm talking to clients and working through problems with them, and then communicating those things to my developers and team leads. Communication is so important in all of this. Of the software projects I've been a part of, communication was the difference between the ones that went well and the ones that went poorly. If there is one thing I could point, to that was it. I mean, I'm sure you've noticed that.

{width: 8, float: left}
![](jordan.png)

Absolutely. That's one thing I do like about the entire study of user experience is that it's communication on the goal of the system and what you want it to do, and explaining that in a visual format. It's saying, "These are the ways that the user should interact with this entire application," and, by visually placing it there, that gives developers like myself the ability to run with it. Whenever I'm trying to do this by myself, I always run into these stumbling blocks. I spend half my time just trying to figure out "So where should I put this button?" and then it ends up being wrong. That's where developing those critical thinking skills and practicing them really comes in handy, so that you can actually improve. You continually build those skills.

{width: 8, float: left}
![](jesse.png)

Right. Think of it like a house. You're working with a homeowner who's having you build this house, and you're laying the blueprint for it. They don't know how you're going to do the electrical or where you're going to put the trusses. They don't know any of that. But they do know if there needs to be a one car or two car garage. That's something they know, right? That's what you need to download from the client, or the manager. You need to translate that onto paper, and then you need to be very good listener and a very good communicator.

That's definitely something that I would recommend. You don't think about becoming a better communicator, but I promise you, it will help you so much. Whether it's through research or just being an active participant in those conversations, it helps to ask those questions and try to root out the things that you don't know that you don't know, or that you you don't know that the client doesn't know. Being honest about whether you understand something or not. Pretending to know what they're talking about is just going to bite you over and over and over again.

The next thing is the ability to both zoom in and zoom out on the fly. Don't spend too much time solving little problems in an isolated environment. Those little problems that you're solving, while good, might have an effect on the larger project. You might solve a problem on this one page, but that might affect how that object is going to behave on mobile or in three pages from now.

{width: 8, float: left}
![](jordan.png)

Right.

{width: 8, float: left}
![](jesse.png)

So you need to be able to zoom in and solve little problems, but always be zooming out and asking yourself "Does this affect other things outside of this one isolated incident?"

{width: 8, float: left}
![](jordan.png)

Absolutely. That's one of the core concepts around critical thinking is being able to have that perspective. Yes, you can dive in and see the little details--you can see where that button goes or what the nav bar looks like--but you also have to zoom back out and say "If I build this one feature, or if I structure the user experience in this way, how does that affect the mobile experience? How does that affect what they're doing on desktop?" And then, when you even have more experience working with developers, or *being* a developer, then you can understand that there might be other ramifications beyond that. You can dream up all you want, but some things need to coincide with the system it's being built with.

{width: 8, float: left}
![](jesse.png)

100% percent. The more you understand about development--and you said it's called a unicorn for a reason--but if you are really good at communicating, you have a firm grasp on the development, you work well with people, and you have some of that design built into your DNA, it is ***so*** valuable. When I'm making design decisions, I'm not making the decisions based on what's easier to develop. But if you know what the development ramifications are, well, holy smokes, you can really optimize that flow. You can gain the most value possible without sacrificing tons of time in development.

{width: 8, float: left}
![](jordan.png)

Absolutely. We talked a lot about critical thinking and developing the mental framework for how to think through these problems. Whether it's in the details or being able to take a step back and look at it at a higher level, it comes down to just actually practicing. When you are building a new application, instead of just jumping straight to the coding and building the design as you go, start practicing these techniques.

Now, you're low fidelity wireframes are not going to look as good as Jesse's the first time you do them, but that's where practice comes in. Your first one may not be the best looking one that's out there, but your fourth and fifth and fiftieth may be. They are going to continue to improve. It's just like any skill. One really big goal of this course is trying to make the entire user experience process a little bit less magical. If you've been going through this course and you've heard all these topics and the very first thing that pops into your mind is that most of this is just common sense: You're right. It is.

{width: 8, float: left}
![](jesse.png)

Haha.

{width: 8, float: left}
![](jordan.png)

And that's the way it should be! If it was any other way, then that would be a problem because this entire process is all about logic, common sense, and having a systematic approach to developing applications. Instead of throwing a blanket over it and hoping everything's just going to work, it's thinking about each stage of that project's lifecycle right from the beginning through to the end.

{width: 8, float: left}
![](jesse.png)

Right. And honestly there's a lot of different traps that you can get caught up in. One of which is just thinking that it's easy, because it really isn't. When you see an app that has good user experience it's like, "Well, duh. Of course you would do it that way." But that's not how most people do it! And you I'm sure you've used a lot of apps where you say, "That took me four clicks to get to and I use that every day! And this other button that I only click once a month is super prominent!" You just should not notice good user experience design. You notice it when it's bad, because it really makes you angry.

{width: 8, float: left}
![](jordan.png)

Haha. Absolutely!

{width: 8, float: left}
![](jesse.png)

So, when you see an app that looks really polished and works really well, don't think that they came up with it by going straight for what was obvious. They got there because they refined it. They took the steps necessary to fill in those gaps, and fill in those holes.

{width: 8, float: left}
![](jordan.png)

The point of this course is to give you a mental mindset that allows you to perform these same tasks without running into some of the issues we've had to fight against through the years. It's so that you could learn from our experiences just the same way that we try to learn from our own. It's really meant to help build that mental framework so that, when you're presented with a project, you don't just start trying to code it, but that you build a system for how to go and build it.

If you went through our problem solving course, part of the reason we created it was to help you develop a system for when you're given something new to build. You may not know how to build the entire system right away, but you would at least know what the first step is, which would lead you to the second one, and the third. That's why I wanted Jesse's design process to be included in this course, because it's a straightforward approach to planning and then executing an application's design.

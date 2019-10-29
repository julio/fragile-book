# Agile Interpretation

## No Design

### Fragile Pattern

Teams new to agile can sometimes believe that in agile there is no need to do any design. System or otherwise.

This is then sometimes interpreted as a positive aspect, and sometimes as a negative one. Either way, it cannot be further from the truth.

In fact, with agile, design is so important that agile teams are constantly designing.

On an agile team, you are designing when you discuss a feature, you are designing when you pair program, you are designing when you retrospect, when you demo, when write unit tests.

The misconception is due to the fact that it is not recommended to have a Big Design Up-Front (the notorious BDUF), like in a more predictable approach such as Waterfall.

When teams assume that they are not supposed to design, the process will devolve into "cowboy coding". A series of hacks until something seems to be working.

### How to recognize it

### What to do

Insist that there is a lot of design, and that many ceremonies and activities are precisely about design.

And also resist a Big Design Up-Front, but not so much that there is no design at all upfront.

Have a brainstorm session, or planning, or a small team offsite, so everyone can align, and stop the design the moment the conversation switches to implementation details.

Everytime the answer to the question "would having more detail now, change the cost of the implementation" is "No", the team is designing too much.

## No Documentation

### Fragile Pattern

No Documentation is a little bit like No Design, but it goes beyond it. It goes all the way to not documentating code, processes, and anything else that is not considered "working software".

It comes from the idea that if we are not adding direct value to the customer of hte software, then we should not be working on it.

Some teams go as far as stopping code comments, or even removing existing and perfectly fine comments, in an attempt to be "more agile".

This is an anti-pattern because though the code ultimately is the real source of truth, it's not accessible to everyone outside the project, and sometimes not even to the team directly involved.

A new team member would have a hard time coming up to speed if the only documentation available was The Code. It's much more practical to have some level of well maintained documentation to be able to communicate with new members, stakeholders, and everyone else who needs the information.


### How to recognize it

### What to do

Avoiding this gotcha requires some common sense at first, and eventually becomes much more natural.

When starting on documentation, ask yourself if this information can be found somewhere else if so, can we point to it instead? This saves time, and even more importantly, avoids information divergence, where both sources gradually change from each other, sometimes to the point of contradicting each other.

Another technique, more specific to code documentation in the form of comments, is to consider making the code self-documenting.

For example, rather than the cliché:

var n; // number of users

consider having:

var number_of_users;

In the end, some documentation is going to be desirable, and healthy, where "none" is almost always wrong, and "too much" is hard to gauge. So use your best judgment, and if the team is starting to have tasks or user stories solely devoted to documentation, you will know that you have wondered too far.

## Kanban Is Easy

### Fragile Pattern

Kanban is a great agile method. As are Scrum, Extreme Programing, and several others. Recently there's been a move from Scrum to Kanban, which is not a bad thing. In fact, when done for the right reasons, it can be a sign of agile maturity.

The important misconception to be aware of, is the notion that Kanban is easiest to implement. It's not. Its simpler set of rules makes it more difficult to get right. A little like a unicycle is hard than bicycle.

Sometimes what teams like about Kanban is its lack of time-boxed iterations (aka sprints), and several ceremonies that come with Scrum for example.

A telling sign that a team is not going to benefit from Kanban, is when you see a fairly large Work In Progress (WIP) number for each state. When that's the case, the team is simply going with the "every person for themselves, and it gets done when it gets done".

Thought there is something to be said about the freedom that comes with that approach, the total lack of constraints is rarely benefitial to the budiness and the customers.

### How to recognize it

### What to do

Two simple rules can be leveraged to avoid a poor transition to Kanban.

Have a Work In Progress value small enough to guarantee that items have go be closed before new items are started. For example, start with a value equal to half the team's size.

In addition, ensure that the team has the opportunity to improve their process. For example, have a team retrospective every other week, to focus on one or two areas of improvement. Do this enough, and any shortcuts the team has done initially, will start showing its negative effects, and the team will be able to adjust.


## Agile About Agile

### Fragile Pattern

This is the notion that agile is not agile, which can be true when teams implement agile by following the rituals without concern for the reason for the rituals.

But imagine that instead of picking the word "Agile", the Agile Manifesto luminaries had chosen the word "Flexible", or "Effective", or "Sensical", or any other word that conveyed what they were trying to convey; a focus on common sense and not being so obsessed with rules.

In that case, teams would now be saying "We are flexible about being Flexible", or some other oxymoron.

Being agile about agile is an anti-pattern because it immediately shows that the team claiming this, has not yet internalized the reasons behind the practices.

They see it as just more process, and sometimes they are right, it's just more process they were told to follow.

It's important to remember that agile (and its practices) was not invented in a vacuum based on a thought experiment. Instead it was based on obsevation. Analyzing what do the successful teams do to be successful.

They work in time boxed iterations? Let's call it sprints. They have a sole person driving the vision and being the liaison between the developers and the customers? Let's call it the Product Owner.

None of this was "invented", simply "observed".


### How to recognize it

To avoid the "agile about agile" anti-pattern, while avoiding falling in a dogmatic mindset, there is a simple approach.

For any deviation, ask the question "how are we going to compensate for the loss of value that practice brings?"

For example, if the team decides to drop sprints (time-boxed iterations), ask the question:

"How are we going to stay predictable vis-à-vis the business, and guarantee working software at a given cadence, and to always focus on the most important functionality?"

Asking these questions implies a high level of agile maturity, since it means the person asking the question clearly understands what sprints (in this example) are for. I recommend that you have access to someone who deeply understands agile when you chose to deviate from the recommendations.

And how do you know when you need to reach out to such coach, and when it's not necessary?

You know you need it, it the team decides to tweak the process, and no one asked the question.

## No Interruptions

### Fragile Pattern

The notion that when the team is agile, they should never be interrupted comes from a good sentiment, to keep the team as focused as possible. At the same time, if that doesn't feel, well, agile, it's because it's not.

It's a question of degree. Should we allow the team to be bombarded with new requests several times a day, "because we are agile", or should we not talk to anyone from the team unless it's Planning time?

The truth is somewhere in the middle.

This is an anti-pattern because at one end, the team is not agile at all, not being flexible about new realities which is the whole point of agile; to be be able to adapt to the real world. If the team cannot do this, perhaps it's an indication of something else going on. Perhaps stories are too big, not enough test? Deployments not frequent enough? Team not working as a team?

But if the team is "too" agile, are they able to be predictable or are they thrashing? Are there signs of burnout?

### How to recognize it

### What to do

Since the truth is somewhere between too agile and too rigid, we need a mechanism to know when we are following rules instead of being adaptable.

A simple enough technique is to have a goal for each sprint. For example, to add users to sign up and log in. Then any new requests that don't immediately align with that goal should postponed to a future sprint.

And if the new request really must be addressed despite conflicting with the sprint goal, then suggest to abort the sprint, re-plan and go from there.

This is dramatic enough that often cooler heads prevail and if possible, the new work is pushed out. And if not, and it's rare enough, then we can be agile about a deviation here and there.

## Develop Sprints Then Test Sprints

### Fragile Pattern

This is when teams alternate development and test sprints. Maybe a sprint or two worth of adding value, followed by a sprint, typically just one, dedicated to test the work that was just completed.

But if work was not tested, was it really completed? The answer is that no, it was not, and the team (and their customers, including the business) benefit from doing less but better, or even from extending the duration of their sprints.

The goal is to have working software by the end of the sprint, as a mechanism for rapid feedback. If the customer's feedback is that the software is not working, trust will erode, with all the negative consequences.

### How to recognize it

### What to do

Avoid this anti-pattern with two simple techniques.

1) If it takes one sprint to develop and one sprint to test, double the duration of the sprint, and do both, development and testing, during the same sprint. The team will be able to do more this way also.

2) Reduce the scope. Instead of implemeting 10 features, then have a sprint that tests the 10 features, keep the sprints the same, but do and test 5 features. Then adjust accordingly.

## No Sprints

### Fragile Pattern

This anti-pattern is based on Scrum and its sprint practice. Sprints of course, are another name for time-boxed iterations.

These time-boxed iterations can sometimes appear as unnecessary process, designed to keep an eye on the team and ensure they are not slacking off.

And certainly, sometimes that is how sprints are sometimes used, as a management tactic.

But sprints provide a real benefit to the team. When there are no sprints, or at least, no real time-boxes, it becomes increasingly difficult to deliver working software in a predictable and regular way.

This is an anti-pattern because having open-ended delivery dates is an anti-pattern. Even in "real" life this is true.

Just like we wouldn't want to order a meal at a restaurant and hear that it will take the time it will take, minutes, hours, or days, the business, and the team themselves, should also not be satisfied with the open-endedness of the No Sprints approach.

### How to recognize it

### What to do

Try to start something of value to someone outside the team truly completed and delivered by the time the sprint completes.

It doesn't have to be everything. You can start small. Try a feature or two, from start to finish in a single sprint. Try it for several sprints, see how much better that works. Then try more features, perhaps most of them.

## Agility Not Agile

### Fragile Pattern

"Agile is dead, long live agility".

Clearly this is about mis-application of agile, and how many teams and companies followed the rituals by the book, did not see much improvement, and agreed that the problem is the process, and that the mindset is worth preserving.

It's just a word. When agility becomes the status quo, we will be looking for yet another word.

### How to recognize it

### What to do

Try to see where the resistance comes from. Since often it's about rituals and dogma, take it as a lighthearted way to say that the core principles are more important than following steps exactly (which is true), have a laugh and move on.

Ensure that your team understands the reason behind the principles, and even the practices, and ignore what labels they have attached to them.

It's important that your team is getting rapid feedback, learning often, and adapting to those learnings. What that process is called should not be a deal breaker.

## Agile Does not Work For My Team Because Of Blank

### Fragile Pattern

I must admit that this is both the most common misconception about agile, and also the one I enjoy debunking the most. So you could say I'm lucky.

This is the notion that agile, yes, it works...for other teams and projects, but not for my team. "What we do is too special for agile".

But why would best practices that were the reasons for successful projects, not work in your case?

Why would having working software on a cadence, regular feedback from customers, well defined work items with clear end goals, not work for your project?

The reason, once again, is probably because you have seen too many agile projects go fragile by their rigidity. The rituals, once again.

This sentiment is dangerous because it gives the team a really good reason to not attempt to follow certain practices?

Agile is difficult to do, it's often counter intuitive, and it certainly requires strong discipline. At least until it becomes second nature to the team.

### How to recognize it

It's simple, team will say something very similar to "Agile is great, but we can't adopt for because of our special circumstances"

### What to do

Don't adopt all the practices at once. For example, start with retrospectives. Can your team benefit from getting together with the stakeholders perhaps once a month, and discuss what we could do better next time, and what we should stop doing?

How about demoing to the rest of the company the worked that got done each month or so?

How about having a backlog with the work that needs to be done, and having it prioritized so everyone knows what's next.

Do enough of these practices, adopting one at the time, and you will be doing agile, even though the team was convinced that for this type of project, it could not work.

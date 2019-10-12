# Agile Interpretation

## No Design

### Misconception

Teams new to agile can sometimes believe that in agile there is no need to do any design. System or otherwise.

This is then sometimes interpreted as a positive aspect, and sometimes as a negative one. Either way, it cannot be further from the truth.

In fact, with agile, design is so important that agile teams are constantly designing.

On an agile team, you are designing when you discuss a feature, you are designing when you pair program, you are designing when you retrospect, when you demo, when write unit tests.

The misconception is due to the fact that it is not recommended to have a Big Design Up-Front (the notorious BDUF), like in a more predictable approach such as Waterfall.

### Why this is an anti-pattern

When teams assume that they are not supposed to design, the process will devolve into "cowboy coding". A series of hacks until something seems to be working.

### How to avoid it

Insist that there is a lot of design, and that many ceremonies and activities are precisely about design.

And also resist a Big Design Up-Front, but not so much that there is no design at all upfront.

Have a brainstorm session, or planning, or a small team offsite, so everyone can align, and stop the design the moment the conversation switches to implementation details.

Everytime the answer to the question "would having more detail now, change the cost of the implementation" is "No", the team is designing too much.

## No Documentation

### Misconception

No Documentation is a little bit like No Design, but it goes beyond it. It goes all the way to not documentating code, processes, and anything else that is not considered "working software".

It comes from the idea that if we are not adding direct value to the customer of hte software, then we should not be working on it.

Some teams go as far as stopping code comments, or even removing existing and perfectly fine comments, in an attempt to be "more agile".

### Why this is an anti-pattern

This is an anti-pattern because though the code ultimately is the real source of truth, it's not accessible to everyone outside the project, and sometimes not even to the team directly involved.

A new team member would have a hard time coming up to speed if the only documentation available was The Code. It's much more practical to have some level of well maintained documentation to be able to communicate with new members, stakeholders, and everyone else who needs the information.

### How to avoid it

Avoiding this gotcha requires some common sense at first, and eventually becomes much more natural.

When starting on documentation, ask yourself if this information can be found somewhere else if so, can we point to it instead? This saves time, and even more importantly, avoids information divergence, where both sources gradually change from each other, sometimes to the point of contradicting each other.

Another technique, more specific to code documentation in the form of comments, is to consider making the code self-documenting.

For example, rather than the cliché:

var n; // number of users

consider having:

var number_of_users;

In the end, some documentation is going to be desirable, and healthy, where "none" is almost always wrong, and "too much" is hard to gauge. So use your best judgment, and if the team is starting to have tasks or user stories solely devoted to documentation, you will know that you have wondered too far.

## Kanban Is Easy

### Misconception

Kanban is a great agile method. As are Scrum, Extreme Programing, and several others. Recently there's been a move from Scrum to Kanban, which is not a bad thing. In fact, when done for the right reasons, it can be a sign of agile maturity.

The important misconception to be aware of, is the notion that Kanban is easiest to implement. It's not. Its simpler set of rules makes it more difficult to get right. A little like a unicycle is hard than bicycle.

### Why this is an anti-pattern

Sometimes what teams like about Kanban is its lack of time-boxed iterations (aka sprints), and several ceremonies that come with Scrum for example.

A telling sign that a team is not going to benefit from Kanban, is when you see a fairly large Work In Progress (WIP) number for each state. When that's the case, the team is simply going with the "every person for themselves, and it gets done when it gets done".

Thought there is something to be said about the freedom that comes with that approach, the total lack of constraints is rarely benefitial to the budiness and the customers.

### How to avoid it

Two simple rules can be leveraged to avoid a poor transition to Kanban.

Have a Work In Progress value small enough to guarantee that items have go be closed before new items are started. For example, start with a value equal to half the team's size.

In addition, ensure that the team has the opportunity to improve their process. For example, have a team retrospective every other week, to focus on one or two areas of improvement. Do this enough, and any shortcuts the team has done initially, will start showing its negative effects, and the team will be able to adjust.

## NoInterruptions
## KanbanIsMoreAgile
## DevelopSprintsThenTestSprints
## KanbanBecauseNoSprints
## AgilityNotAgile
## AgileAboutAgile
## AgileDoesntWorkForMyTeamBecauseOfBlank

# Roles

## NoPO

### The fragile pattern

A team without a dedicated Product Owner, sometimes also called Product Manager, or Main Stakeholder, or even "The Customer" is not so uncommon.

This is problematic because the team does not have someone fully dedicated to representing the users of the product being built. Someone who can have deeper conversations with the potential users and customers, do market research, have enough infomration to understand what ought to be happen first, have a vision for where we the product is going.

This can be problematic and slow down the team, because there is no clear path forward, and certainly not a good representation of where the product should go. Decisions are more contentious, and at best decided by commmittee instead of representing actual needs.

### How to recognize it

- Everyone on the team codes, no one is solely focused on the customers
- A side effect of this tends to be quality and focus of the work items. Inevitably these items will gravitate towards internal engineering tasks, instead of representing what customers need.

It's also common to hear "we don't have a product owner, because we are an internal tool".

### What to do

At the very least nominate one of the team members as the Product Owner, with everything that comes with it: prioritization power, interact with customers, set the vision for the product, code less (or not at all), expect demos, make quick decisions for the team when they are stuck.

Ideally have someone who is a Product Manager already to play the role of the Product Owner.

## ManyPOs

### The pattern

"We don't have just one person to act as the product owner"

Often the reason for this is the complexity of the product, other times it's the lack of resources, and other times it's the the distributed aspect of the team.

Unless the individuals acting as product owners are in perfect harmony every minute of the day, or at least, whenever a decision is needed, or a question needs an answer, or something needs prioritizing, then having more than one product owner is going to slow down the team.

Inevitably they are going to contradict each other, and at the very least ask for more time before they can agree together on the right course of action.

This extra necessary is considered waste, and something to attempt to eliminate in order to enable the team to run as fast as they can.

### How to recognize it

### What to do

Bring this up during a retrospective, that hopefully all product owners also attend, and insist on a single Product Owner. Make sure to clarify that the reason for it is so the teamn ca deliver faster. Document any examples when the team was slowed down for lack of single Product Ownership.

The "new" Product Owner should be empowered to make the right calls, either on their own, or after consulting with the right stakeholders. Ultimately, it should abundantly clear to the team, that the Product Owner is the one in charge of representing the customers of the product, and it is their call, and not a committee's call. This is even if behind the scenes there is a commmittee (see #ProxyPO)

See also #ProxyPO, #NoPO

## ProxyPO

### The fragile pattern

The Product Owner does not actually own the product, its scope, its priorities, its vision, and everything else an owner would own.

Instead, the Product Owner is one the team on behalf of sometone else who acts as the real Product Owner.

Not having an actual Product Owner, and simply a Proxy, will slow down the team, with the role devolving quickly into a Project Manager role.

A dedicated Project Manager is itself a fragile pattern, as the best practice is to have the team, collectively, with the help of the process itself, to act as the "virtual" project manager.

In practice, and the reason why a Proxy role slows down the team, is because the feedback loops tend to grow in length.

When it could take a matter of seconds to clarify a priority question during planning, for example, it might now take hours if not days, for the Proxy to get agreement from the actual Product Owner.

In addition, the Proxy it not necessarily meeting with actual and potential customers, leavingt that task to the actual Owner, and making it necessary for both Proxy and Owner to reconcile often. This is another source of waste.

### How to recognize it

### What to do

The first step, especially if Proxy and Owner have to be two different people, is to enforce that both are perfectly aligned in terms of mission, vision, priorities, etc.

For that, both should meed daily and sync up.

Ideally, and because no perfect harmony will ever be as good as a single owner, see if your team can delegate more of the ownership to the acting Owner, and in time, make the Proxy a real Owner.

This might mean training, culture change more based on trust and experimentation, the scope for the owner (more or fewer teams, depending on the case), and eventually get to the point where the person acting as the Product Owner is empowered to play the role fully.

## Product Owner List Taker

### The fragile pattern

A Product Owner whose tasks are limited at capturing and transcribing requirements from other stakeholders. Sometimes mosly someone with authority, other times this includes everyone who has an idea.

This is a terrible practice for two primary reasons:

* This Product Owner can be easily replaced by a smart automation script, or at the very least by having the requesters enter their own items. This alone should be an indication that the role could and should be extended to something that truly adds value to the team.
* There is no clear and focused path forward. The Product Backlog becomes a shared to-do list, which has *some* value, but minimal when compared to what it could be if the backlog had a single purpose.

### How to recognize it

A telltale sign is the lack of epics, or perhaps an explosion of epics. Epics are like mini-projects inside the product. When there aren't any, or too many, it means the product is lacking focus, which could be from having a passive Product Owner, fully dedicated to capturing whatever comes their way.

Another sign is when most of the items are not written by the Product Owner, or at least not endorsed by them (though this is a little more difficult to detect).

Finally, and most dramatically, the Product Owner does not have answers. This Product Owner might have questions, lots of questions, which is a good step forward, but rarely will provide any answers. In fact, the team has learned this, and goes directly to the author of the request, fully bypassing the Product Owner who is really a List Taker.

### What to do

Give the Product Owner the authority to truly *own* the Product. not just the capturing of the requirements.

This could require training, since Product Owner requires strong Product Management skills, and it that case, make sure to consider it, since the team, and the company, will benefit from a true Product Owner in the long run.

A practical and easier first step, is to require that *all* work items are entered by the Product Owner. This will not fix the problem per se, though it will at least give the Product Owner the visibility they need into what makes the backlog. At least this way the Product Owner will be able to combine similar items, and eliminate contradicting ones.

## ScrumMasterAsMeetingCoordinator

### The fragile pattern

Sometimes the person with the ScrumMaster role is nothing but a meeting coordinator. Someone who ensures the meetings are set up, they start and finish on time, and little else.

Though this is, or could be, part of the Scrummaster's tasks, it's a very small part of it, and certainly not the most interesting.

The more interesting aspects of the role, and the reason why this role is crucial to the success of the team, is manyfold:

- coach for the team
- guardian of the process and the best practices
- liaison with the product owner and other stakeholders
- protector of the team ensuring they can do their best work
- help translate business asks into technical requirements

Think of the scrum master as a coach for the team, and you can imagine how just having a scrum master take care of meetings, leaves quite a bit of value on the table.

### How to recognize it

A common sign of this is when the scrum master is rotated automatically, or given to the person on the team, or the most junior. These are all signs that the team sees the role as a necessary evil, and it might as well be shared or given to someone who is not very productive yet.

### What to do

Give the role to the most productive, most passionate, most senior developer on the team. This is going to be a person who cares about the things that scrum masters care about. Sure, they will need to run those meetings, and that's less interesting, but that would be a small fraction of their contribution.

In this role, the most senior and passionate developer will be tremendously well positioned to influence the team, and raise the bar to their level.

## ScrumMasterAssigningTasks

### The fragile pattern

The Scrum Master assigning tasks either during planning or throughout the spint, is a clear indication that the team is not working in a self organizing way, and are simply waiting to be assigned "tickets".

At this point the team is not mature enough to truly absorb what the product is about and how they, as a team, can work together to accelerate learning, and work on deliverables.


### How to recognize it

This is fairly common with junior teams, or teams who are used to a command and control environment, with limited exposure to agile and its self-organization mindset.

The obvious way to detect this is during planning, when the scrum master assigns each ticket to a specific person. Often based on their expertise or their availability.

At that point, there is little incentive for each individual to work as a team and figure out how to tackle the bigger picture, together.

Another sign of this pattern, and in some ways, even more limiting to the teams, is when the individuals ask for a new ticket when they are done with the current one. Instead of starting on the most important ticket following the current one, they pause and ask for work. Another clear sign that the mission and vision of the product, and the goals of the sprint, are not understood.

This is a problem because a healthy agile environment depends on a team that acts as a partner, sometimes even as a "co-founder". A team that clearly understands what is being built, and why.

When the team pauses and asks for more work, it should be the indication that the team is not aware of why they are building what they are building.

### What to do

A solid strategy is to do nothing. Have the team self-organize and figure out what to do next. If you have a team of professionals you are proud of, this will give them the space they need, to start asking the right questions, and finally truly own the work.

If instead the team stalls and doesn't know what to do, coach them. Ask them what do they think is the most important item to meet the deliverables. Then ask who would like to work on it. It could be one person, or the entire team, it doesn't matter, as long as the work gets done.

Consider letting go and trusting your team. If won't work well right off the bat, but it will eventually, and the product and the team will be better off then.

## ScrumMasterShuttle

### The fragile pattern

There is a famous scene in the movie "Office Space" where Tom Smykowski is trying to justify his job as someone who takes requirements from the customers and gives them to the engineers, because he happens to have people skills.

It's a very funny scene, one that highlights many of the issues that could have been addressed with agile, or common sense in general.

This pattern is similar. Here the scrum master acts as shuttle between the Product Owner and the developers. In a bottleneck fashion.

This scrum master is not helping the teams or the customers make better decisions, and instead, the scrum master is simply acting as the conduit between the stakeholders and the folks making the product.

This is terrible because it adds a significant amount of waste. After all there is a person doing a job that can be better done using at the very least technology, and ideally by having the developers talk to the Product Owner directly. Perhaps during stand-ups, planning, and demos. At the very least.

### How to recognize it

A common sign is a fairly passive Scrum master. One the represents the stakeholders to the dev team, and not the dev team to the stakeholders.

### What to do

Perhaps this person was assigned this role temporarily, and they are not passionate about it, or qualified to represent the team. Have a frank conversation, lay out the expectations for this role, and let the person decide if they still want to be the scrum master.

This implies the team is motivated to have a scrum master that acts as a coach and guardian of the best practices, which would help the team more.

## ScrumMasterProductOwnerManager

### The fragile pattern

When the Scrum Master is also the Product Owner.

This looks like an effective way of leveraging the resources available, which is what makes it so compelling. It's difficult to imagine all the waste it's creating since it's designed to do just the opposite, eliminate waste. Ot so it seems.

If we summarize the role of a Scrum Master to just a single focus, and do the same with the Product Owner, the fragile pattern becomes more apparent.

The focus of the Product Owner is to extract from the team the highest amount of value, in the shortest amount of time. In other words, "quantity first".

The focus of the Scrum Master is to help the team be as efficient as possible, keep focus and sound engineering practices high. In other words, "quality first".

Quantity vs. Quality. These two are often at odds, and having a healthy balance between the two is one of the engines that make agile work.

When the same person is behind the decisions to drive both quality and quantity, the balance is lost and inevitably the product will slowly shift towards one of the two.

This the same reason why most successful companies have a person responsible for engineering, and a different person responsible for product. It's not just a bandwidth or skill constraint. It's primarily to keep the balance.

When this happens it's sometimes the engineering manager who plays those two roles, and now we have an additional problem. The person responsible for the product, is also responsible for engineering, and also for the people's careers. A dangerous combination that prevents agile from really taking off and providing the value that it could.

### How to recognize it

The team has no dedicated Product Owner separate from the Scrum Master. Everyone one the team knows who decides "what to build", and "how to build it". It's the same individual.

There will be no mystery on who is who.

### What to do

Start by cleaningly separate the what, from the why, from the who, from the how. Once that's done, assign owners of what and why, distinct from who and how.

What and Why are a business concern, and therefore fall on the Product Owner. Whereas Who and How are technical responsibilities that fall on the team and the Scrum Master.

This mindset will accelerate faster if the team, and indeed the Scrum Master both get in the habit of asking "what and why" questions of the work being asked of them.

See: Theory of Constraints, Bills of Rights.

## OverworkedTeam

### The fragile pattern

### How to recognize it

### What to do

## GroupOfPeopleNotTeam

### The fragile pattern

### How to recognize it

### What to do

## ScrumMasteringIsBoring

### The fragile pattern

### How to recognize it

### What to do

## AssignedWork

### The fragile pattern

### How to recognize it

### What to do

## ProductOwnerAsBabySitter

### The fragile pattern

### How to recognize it

### What to do

## MyManagerWontGoForThat

### The fragile pattern

### How to recognize it

### What to do

# Fifty Quick Ideas to Improve your User Stories

## Creating stories

#### Tell Stories, dont write them 
Requirements by collaboration. Use physical story cards, electronic ticketing systems and backlog management tools as remainders for conversations, don´t waste too much time nailing down the details upfront.
(Insurance company)

#### Don´t worry too much about story format
The key element :
- Story card is ideally just a token for a conversation.

Prefered ` 'As a .. I want .. So that..' ` Write down who wants something and why.
 
 - Name Stories early, add details later.
 - Avoid spelling out obvious solutions.
 - Thinkg about more than one stakeholder who would be interested in the item.
 - Use a picture instead words
 - Ask a question
 - Focus on the problem statement
 
#### Describe a behaviour change
Valuable initiatives produce observable change in someone´s way of working.Identify what could change in the system that produces a change in the user´s way interaction as an example.A measurable behaviour change make stories easier to split.

#### Describe the system change
Every story should describe behaviour change that represent business value (the why) of the story, it should also be clear about the change a team needs to make to software(what)
 
#### Approach storias as survivable experiments
Stories should be about how much business stakeholders want to invest in learning whether a proposed change will actually give them what they assumed. Help business sponsors manage their investment in software and get the most out of it. 
If a story is too big, which effectively means the potentional cost of the experiment is too high, we can look at alternative ways of learning about something instead just trying to slice the story.

#### Watch out for generic roles
A generic user role can never provide a particular user segment, it impossible to decide whether the proposed solution is the right one, or if it´s just unnecessary scope creep.(Consider how the product will be used as narrow target group)

#### Evaluate zone of control and sphere of influence
- _The zone of control_ includes all those things in a system that we can change on our own.
- _The sphere of influence_ includes activities that we can impact, but can’t exercise full control over.
- _The external environment_ includes the elements over which we have no influence.

A good guideline is that the user need of a story (‘In order to…’) should ideally be in the sphere of influence of the delivery team, and the deliverable (‘I want…’) should ideally be in their zone of control

#### Put a 'best before ' date on stories
Separate user stories from the rest of the back log if they have time constraints and put ir a best before date to calculate when you should start working on, so they wont get "expired".

## Planning with stories

#### Set deadlines for addressing major risks
Delivery teams should work with stakeholders to set explicit deadlines for addressing major risks at sustainable pace ( FBI example). Having an explicit plan to deal with big risks allows stakeholders and the delivery team to strike the right balance bewteen short-term business win and long term sustainability.

#### Use hierarchical backlogs
Try to divide your plan int several tiers and ther avoid breaking donw a higher-level until you complete all the relevant lower-level stories for the previous higher-level item.

Recommended levels:
 - big-picture business objective : example grow mobile suscription
 - smaller scale business change that might contribute to that big picture : better conversion from web to mobile
 - software deliverables that support those changes : data import from competitor formats
 - smaller delirevable slickes that we could ship independently: file access to competitor systems
 
Having an hierarchical backlog you could move toward a differente business objective if the market could change(has differents objectives).

#### Group storis by impact

Impact map ( mind map ) is a visaulisation of how delirevable scopes connects to business goals and the underlying assumptions on four levels.

The first level of the mind map is the business goal for a milestone of a project or a product delivery. The second level of the mind map contains user segments, stakeholders or actors who will be involved in achieving the goal. The third level of the map shows the impacts on users and stakeholders that can contribute to the business goal, or that could hinder achieving the objective. The fourth level of the map is for the deliverables – user stories or even larger deliverables (such as epics) that can cause the impacts.

| Goal                | Actor                 | Impact             | Deliverable       |
|--------             | --------------------- | ------------------ | ----------------- |
| Grow Mobile Adv  	  | ->Super fan	       -> | ->Come back freq-> | ->Push Updates    |
|                     | ->Concert Organizers  | ->Stay Longer      | ->Speacial Offers | 
|                     | -> Artists            | ->View more ads    |                   | 

#### Create a user story map 

#### Change behaviour using the CREATE funnel
 
 - Cue:thepossibilityofactionneedstocrosstheperson’smind
 - Reaction: the person automatically and intuitively reacts to the idea in a fraction of a second, generating an emotional response
 - Evaluation: the person thinks about the action consciously, evaluating the costs and benefits
 - Ability: the person evaluates whether the action is feasible given the current context
 - Timing: the person judges whether they should act now or later

#### Set out globlal concerns at the start of a milestone

User stories are not particulary well suited for addressing global cross-cutting concerns such as capacity, performance and security.
A good stategy for dealing with such issues is to have a separate discussion about global concern per milestone. 
Implementations constraints, resource limitations, operational requirements and licensing requirements all go in this category.
Solutions :
 - Pyramid of quality
 -  FURPS+ mind map. (FURPS stands for functionality, usability, reliability, performance, supportability)

Consider a checklist of expectations for global concerns such as usability or security.

#### Prioritise according to stages of growth

 In Lean Analytics, Alistair Croll and Benjamin Yoskovitz suggest a common growth model for successful products:
 - Empathy: figuring out how to solve a real problem in a way that people will pay for 
 - Stickiness: building the right product to keep users around
 - Virality: growing the user base organically and artificially
 - Revenue: establishing a sustainable, scalable business model with the right margins in a healthy ecosystem
 - Scale: growing the business

You don´t have to go too far because you will have to write user stories depending on the situation on the stage of growth, _focus on critical objectives for the current stage_

#### Prioritise using purpouse alignment

Moscow model, splitting features Must have, Should have, Could have and Would Like.
Ask two questions :
 - It is mission critical ( Can the business run without it?)
 - It is market differentiating ?
 
 Once these questions have been answered, items can end up in one of four categories:
 - Differentiating: both mission critical and market differentiating. This is the area where organisations should focus most of their investment. For such items, good just isn’t enough, excellence is required.
 - Parity: mission critical, but not market differentiating. These are things that have to be done, but they can just be good enough. Making them significantly better than the competition is an over-investment.
 - Partner:market-differentiating opportunities that aren’t mission critical, for example opening up an experimental sales channel using mobile devices.
 - Who cares: ideas that aren’t mission critical or market differentiating.
 
#### Make a stakeholder chart

Answer the next questions
 - Who will be impacted by the project?
 - Who will be responsible or accountable for the project?
 - Who will have decision authority on the project?
 - Who can support the project?
 - Who can obstruct the project?
 - Who has been involved in this type of project in the past?
 
Create a 2x2 grid on the wall or a white- board, with axes labelled interest and power, and group the post- its according to how important your product or initiative is to a stakeholder (interest) and how much ability they have to bring about their preference about a topic (power)

The group of stakeholders is contextual and dependent on the outcome you are trying to create, so make a stakeholder map only once you know the goals of a milestone, and revisit it before starting another milestone.Teams who build consumer products often have to significantly change their stakeholder maps between products or even milestones.

#### Name your milestones
 It is better to name a milestone according to the capability represented by the set of stories included in it.
 
#### Focus milestones on a limited number of user segments
 Selecting a limited number of target segments for each milestone prevents stakeholders from constantly inventing new user roles. This makes people think twice when writing stories to justify pet features, and results in better, more focused stories.


## Discussing stories

#### Use low-tech for story conversations
 Good user stories are a remainder to have a conversation. Please avoid at the beginning to use any technology tool.

#### Imagine the demostration
 Make a demo on the user stories you have been working.Try to imagine how will you demostrate the achivement.

#### Diverge and merge for story discussions
 If the group is more than 10 persons split and discuss then bring the groups together and compare the results. Bringing groups together helps to coordinate and identify sources of misunderstanding.

#### Involve all roles in the discussion
 Create small conversations that involve at least one person representing each of the development, testing and analysis roles.


#### Measure alignment using feedback exercises
 Feedback exercises are driven by questions,ideally structured around some difficult edge cases. It’s very important that while everyone else focuses on the boundary conditions in the exercise, the facilitator focuses on the form of the questions. Exercises should ideally be driven by questions that do not lead people to answers, questions that are as open-ended as possible

#### Play the devil´s advocate
 One good way of discovering bad ideas quickly is playing the devil’s advocate – intentionally challenging the perceived need addressed by a user story
 
 Try challenging several aspects of the story:
 - Argue that the target user doesn’t really have the need (I don’t want to log in)
 - Argue that the target user segment is wrong (someone else wants end-users to do that)
 - Argue that the proposed solution is wrong (delivering the solution will not provide the benefit)

#### Divide	 responsibility for defining stories
 But deciding isn’t the same as defining, and this is where things go wrong! Getting business stakeholders to design solutions wasn’t the original intention of user stories – but many teams have fallen into this trap

 
#### Split business and technical discussions
Discuss business needs and divide stories according to value with business users, then let them go and do their day job while the delivery team looks at stories from a technical perspective

#### Investigate data on multiple levels

When the whole chainof reasoningis clear,it’s much easier to have a useful discussion on what the story really needs to deliver and to design experiments to validate the underlying assumptions.

#### Discuss sliding-scale measurements with QUPER
Quality Performance model visualises and exposes two types of information about the market need and the proposed architectural solitutions: breakpoints and barriers.

Breakpoints are thresholds of usefulness for a particular aspect of a system:
 - Utility : moves from useless to usable
 - Differentiation : product becomes a competitive advantage
 - Saturation : any improvements are an overkill, and make no real difference to users
 
The points where cost-to-benefit ratio changes sharply are called barriers, and they are related to particular potential architectural solutions.

By visualising breakpoints and barriers,we can expose assumptions and have a meaningful discussion about where our solution is compared to the market and where we want it to be (Example :Payment gateways)

Choose ranges instead of numbers ( Complete my transaction in less than 3.4 seconds , my transactions need to be completed in bewteen 2 to 5 seconds)
(quper Model)(http://quper.org/)

## Splitting Stories

#### Start with the outputs
The key benefit of thinking about outputs first is that it becomes much easier to create a sensible incremental delivery plan. Outputs are much easier to slice than inputs because they enable users to achieve something concrete, and people can have fruitful discussions on them.

#### Forget the walking skeleton- put in on crutches
 A dancing skeleton not only delivers a small function on  the target architecture, it also involves an interface for developers to interact with the environment and experiment.
 Early validation is an important consequence of early delivery of value.Instead of showingsomething basic to users and asking them to imagine the final fantastic offering, a skeleton on crutches allows them to actually use something in real work.
 Aim to deliver the user interface part first, on a very simple architecture. Try to skip all back-end components that would slow down delivery, even if for half a day. Deliver a user interface part that looks and works as much like the final version as possible, to avoid future surprises. Iterate on the interface until you confirm that you’re delivering value. Then replace the back end with as few changes to the user interface part as possible to avoid surprises.

#### Narrow down the customer segment 
 Don’t give everyone 2% of what they need, instead give 2% of users everything they need. (Example Reports for 2 people UK transactions)
 
#### Split by examples of usefulness 
  Instead of slicing technical deliverables and then looking for useful chunks of value, try to start from the opposite direction: slice value and look for useful technical chunks.

#### Split by capacity

You can easily open up a discussion on smaller slices and faster feedback if you view capacity as a dimension that can be progressively delivered. A solution that provides less capacity often requires simpler versions of components, and might not require some major parts at all. At the same time , it´s likely that there are use cases that can be satisfied with less capacity, so even those simpler solutions can be shipped to end-users.

#### Start with dummy, then move to dynamic
 The real value of software is mostly in its outputs, not in its inputs. An interesting strategy for splitting stories while preserving most of the value is to avoid any work around preparing inputs at first. This particularly applies to reference data.(Load data from file not from DB example)

#### Simplify outputs
 If you’ve tried to simplify input channels and split by capacity, but a story is still too big, it’s often possible to split the story further from the other end, by simplifying outputs. This approach is particularly applicable to internal enterprise development, where the final output often needs to be stored in an obscure database handled by a completely different team.

#### Split learning from earning
 A helpful way of thinking about this is that a story should be either about learning or earning. Learning stories help stakeholders plan better. Earning stories help to deliver value to end-users

#### Extract basic utility
 The goal is to first make something that enables a user to at least complete a critical task, and then plan for making it faster, easier or require less effort later.
 This technique works particularly well for splitting a time-critical story into a smaller piece that remains time-critical and a larger section that can be managed without a deadline.

#### When all else fails, slice the hamburguer
 1. List technical components
 2. Define quality attributes
 3. List options at different levels of quality
 4. Remove unsatisfactory options
 5. Remove options that don’t produce useful technical slices
 6. Choose a slice
 

  
 
 






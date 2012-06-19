# Using RAD Dev with Trello

[Trello](https://trello.com/) is a project tracking website.
For RAD Development Teams,
Trello serves as the Kanban board that will display the at-a-glance
status of features as they are implemented.
The board should _not_ include implementation details relevant only to developers.

Generally create columns on the board _only_ when features need to be passed between groups,
such as the product owner and developers.

## The Feature Queue

Trello uses a feature queue, not a *todo list*.
This is important to understand,
as people fresh from project management arenas will be
tempted to slot tasks into the **backlog**.

The only things that belong in the backlog are **product features**.

### Product Feature

1. A product feature is the description of a real, 
   tangible result that creates new value in the product.
2. Product features should describe the product from the user perspective.
3. Features should be small units of increment, doable in 3-4 days.

![Trello Feature Queue](img/trello-feature-queue.png?raw=true)

Writing good features is a skill that takes time.
Features should be clear and well-defined,
but not too obsessive about implementation details..

![Trello Feature](img/trello-feature.png?raw=true)

## Roles

There are two main roles, the **Product Owner** and a **Developer**.
While the Product Owner is part of the development team they have different responsibilities.

Each role affects the feature queue differently.
The PO adds and prioritizes features in the backlog,
and verifies completed work in the **done** column.

![Trello Product Owner](img/trello-owner.png?raw=true)

Developers move features through the pipeline by pulling the top most item from backlog,
implementing it and moving them into done.
Features should have an average pace between 3-4 days between start and completion.

![Trello Developer](img/trello-developer.png?raw=true)

The Product Owner may solicit information from the developers while creating features,
by messaging them in chat

![Trello Solicit](img/trello-notify.png?raw=true)

## Limit Work in Progress

We are using Trello to manage a Kanban board.
An important part of Kanban is to limit work in progress.

The entire development team shares the same board.
Individuals _must not_ process items outside the board on their own.
The **In Progress** and **done** columns must have work limits on them.
You cannot pull a feature into a column unless there is free space.

![Trello Limit WIP](img/trello-wip.png?raw=true)

Items are removed from **Done** as they are verified by the product owner,
thus lazy verification will delay the entire project.
By always using the board, anyone can see at-a-glance which group is causing the delay.
Delays are not about blame, but clarity.

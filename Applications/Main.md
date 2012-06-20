# Main

The main way RAD teams are deployed is with 
the following application stack:

1. HipChat
2. Github
3. Trello

The goal is to avoid wasting time,
and keep people productive.
Each tool must be used in a RAD fashion,
they must be **Rapid**, **Asynchronous**, and **Distributed**.

At-a-glance:

1. use [HipChat](../HipChat.md) for notifications and brain dumps
2. use [github](../Git.md) for the important stuff
3. keep [Trello](../Trello.md) focused on features

## HipChat

HipChat is RAD when used for notification and brain dumps.
Despite supporting real-time-chat, its primary purpose is not that.

In a synchronous business environment,
meetings are usually scheduled in order to bring everyone up to date.
If a someone has a thought, idea or suggestion, they often wait for the meeting.
Under RAD, the moment you have the idea, you should post it to HipChat.
Think of the group chat as an event-stream,
or a group stream of consciousness.

Unless engaged in real-time behaviour,
your HipChat posts should be as complete as possible.
Posts should be whole thoughts.
For example, posting "Hey, wanna hear my idea?",
is not as useful as just posting the actual idea.

## Github

Github is the technical heart of the project.
Github is RAD because _any_ team member, at _any_ time, for _any_ reason can open a branch with new changes.
Pull requests are a _shoot first ask questions later_ approach.

Open PRs early, and first address _why_ you are doing what you're doing.
Other developers can weigh in, assist, or stop you from being stupid.

Git is a brilliant program.
It allows the code base to merge just as easily as it does diverge.
Branching is done asynchronously, without coordination,
however merging is _always_ done as a team.
The PR must contain enough information and justification for the other developers to agree to the merge.
The exact consensus rules for merging are left up to the individual team.

We call this approach scatter-gather, a term coined from distributed computing.

## Trello

Github is for hard technical stuff, and HipChat is just an event stream.
We are still missing a piece, which is a centralized overview of the entire project.
Trello is an online Kanban board that bridges communication between developers and the product owner.

A new developer, familiar with RAD, 
should be able to discover available work within a few minutes of joining the team.

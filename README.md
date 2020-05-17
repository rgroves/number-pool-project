# Number Pool

This repo is just for notes related to creating a web site where users can sign-up and create a Lottery Pool type of game.

Tech: React, Node, MongoDB

## Related Repos

This section will link out to the repos where the actual code implementing the site/services reside.

- [Number Pool Backend API](https://github.com/rgroves/number-pool-api)

## Learning Log

I want to keep a log of my thoughts, queries, and things I've learned while building this project out. I will do that in [LearningLog.md](LearningLog.md)

## To Do List

As I work there will be items I'll probably want/need to do at a later time. I'll be keeping track of those here: [TODO](TODO.md)

## MVP Requirements

- Allow visitors to create a user account with email & password
- Allow users to create one or more Lottery Pools
- Allow users to join one or more Lottery Pools
- Allow Pool Members to choose their numbers
- Allow Pool Owners to enter winning numbers
- After winning numbers are entered by Pool Owner, all Pool Members' numbers should be examined to mark which numbers have been selected.
- When one or more Pool Members' numbers have all been selected it should mark the pool as ended and display those members as the winner.
- Every pool will have a Member's view, that will show all members of the pool, and thier chosen numbers with a visual indicatore of which have been selected already and which are still "waiting"

## Future Requirements

- All users should be able to edit their profile (update email & password)

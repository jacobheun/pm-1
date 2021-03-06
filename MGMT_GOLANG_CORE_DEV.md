# Golang Core Dev Team Work Tracking & Managment

## How work gets organized (a tl;dr;)

The Golang Core Dev follows the OKR structure established for the IPFS, libp2p and IPLD projects to set the quarterly targets. Within each quarter, work gets tracked using Github and Waffle.

- Github is used for discussions and track current endeavours.
- Waffle gives us a [Kanban](https://en.wikipedia.org/wiki/Kanban) view over the work at hand.

![](https://ipfs.io/ipfs/QmWNd86qtjyFnygSAHkZDy4fUB1WnRa4WNt8gt1rSiq7of)

In the Waffle board, we have 4 columns:

- **Inbox** - New issues or PRs that haven't been evaluated yet
- **Backlog** - Issues that are blocked or discussion threads that are not currently active
- **Ready** - Issues Ready to be worked on
- **In Progress** - Issues that someone is already tackling. Contributors should focus on a few things rather than many at once.
- **Done** - Issues are automatically moved here when the issue is closed or the PR merged.

We track work for the Golang implementation of IPFS, libp2p and IPLD in 3 separate waffle boards:

- [go-ipfs](http://waffle.io/ipfs/go-ipfs)
- [go-libp2p](http://waffle.io/libp2p/go-libp2p)
- [go-ipld](http://waffle.io/ipld/go-ipld)

## Issue labels and how to use filters

We use labels to tag urgency and the difficulty of an issue. The current label system has:

- `difficulty:{easy, moderate, hard}` - This is an instinctive measure give by the project lead or leads. It is a subjective best guess, however the current golden rule is that an issue with difficulty:easy should not require more than a morning (3~4 hours) to do and it should not require having to mess with multiple modules to complete. Issues with difficulty moderate or hard might require some discussion around the problem or even request that another team (i.e go-ipfs) makes some changes. The length of moderate or hard issue might be a day to ad-aeternum.
- `priority (P0, P1, P2, P3, P4)` - P0 is the most important while P4 is the least.
- `help wanted` - Issues perfect for new contributors. They will have the information necessary or the pointers for a new contributor to figure out what is required. These issues are never blocked on some other issue be done first.

## Weekly Core Dev Team Calls

[💫 Golang Core Dev Team Weekly Sync 🙌🏽](https://github.com/ipfs/pm/issues/674)

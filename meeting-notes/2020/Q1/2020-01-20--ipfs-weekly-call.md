# IPFS All Hands Call Jan 20, 2020

-   **Moderator:** @autonome
-   **Notetaker:** @jacobheun
-   **Attendees:**

    -   _@jessicaschilling_
    -   _@mburns_
    -   _@ribasushi_
    -   _@lidel_
    -   _@jaycarpenter_
    -   _@olizilla_
    -   _@yiannisbot_

  


**Moderator checklist**

-   Ensure that there is a notetaker
-   Start recording
-   Ask attendees to add their names to meeting notes
-   Call for additional agenda items

  


**Agenda**

_General discussions, decisions, etc._

-   Next IPFS meeting will be lightning talks!
-   IPFS Browser Design Guidelines presentation from @autonome


 

**IPFS Browser Design Guidelines** - @autonome

-   @autonome joined IPFS last year coming from browser world (Mozilla)!
-   [SLIDES](https://docs.google.com/presentation/d/1blaW9WbcRVITpWY_hwLTk2VvGi1TKlwBmi0NLM_jZYA/edit?usp=sharing) (please comment!)
-   Pace of change in browsers is slooooow
-   Firefox has a reduced market share, still 100s of millions of users
-   Lots of people have a say in the development standard, making things slow
-   Browser vendors are very careful about changes
-   Audience for this presentation is browser vendors
-   Focus is on the narrowest possible focus, the browser address bar
-   Context: providing information to designers to help them make decisions
-   Context: Clarifying the key differences from http.

    -   Trust doesn’t come from DNS
    -   Cryptographic exchanges
    -   Nature of privacy is quite a bit different from browsers today (no cookies for example)

-   Research: talked to a number of technical and non technical people
-   Did a review of browsers as they are today (top 4 by market share)
-   How do newer features like privacy control relate to IPFS in the browser
-   Non Expert Findings: URLs are not greatly understood, but even non technical people feel like they understand it
-   Non Expert Findings: p2p is generally associated with pirating
-   Expert Findings: the browser bar pretty much just works
-   People really lean on the structure or URLs
-   Long URLs are regarded as suspicious. So are short URLs. Need to be just right.
-   P2P should have a meaningfully different visual
-   Other Research

    -   Power consumption
    -   Bandwidth usage
    -   Offline / Local
    -   Non-Western users

-   Themes:

    -   What is the trust model we need to help designers design for?
    -   How do we communicate these things and make them human readable?
    -   What is the nature of security in current browsers and how do we replicate that?
    -   Privacy and security is important to users, but ad tracking is not well understood by non experts

-   Patterns

    -   Wanted to provide teams with Do’s and Don’ts
    -   Security, hiding access controls, indicating network status, showing progress when loading resources

-   Created recommendations on Iconography, may redo this soon
-   Recommendations on how to show when the address bar is referencing an IPFS resource

    -   What to display when resources are unavailable

Questions:

-   Do people get creeped out by hashes?

    -   Long URLs regardless of what’s in them erode confidence. Human readable structure improves confidence.

-   Protocols have somewhat disappeared from address bars, do we want to push for that to come back?

    -   Browser vendors have not fully decided on what to do here

  


**Demos**

_Show your work!_

  


**Q&A, Help Wanted**

_Ask questions, get answers. Announce issues that need help, get people to help._

# How GitHub Engineering communicates: Tips for leaders
_(Community version, lightly edited, primarily to remove internal URLs and references)_

Overall, the way we communicate as an Engineering organization is informed by the following principles (fully defined in the ["How GitHub Engineering communicates" guidance](./how-github-engineering-communicates.md)):

* Be asynchronous first
* Write things down
* Make work visible and overcommunicate
* Prefer GitHub tools and workflows
* Embrace collaboration
* Foster a culture that values documentation maintenance
* Communicate openly, honestly, and authentically
  * Strive for inclusivity
  * Use emoji and animated GIFs
* Remember practicality beats purity

This document contains a brief set of further expectations for leaders on how to set an example and create an environment on their team(s) that promotes these principles.

## Invest in psychological safety

Start here 👆. If there's one thing you can do to foster stronger asynchronous practices on your team, it's to be intentional about [creating psychological safety](https://rework.withgoogle.com/guides/understanding-team-effectiveness/steps/foster-psychological-safety/). Be open to feedback, admit your mistakes, and show vulnerability. By cultivating an inclusive environment in which your team members feel safe to take risks, share ideas, voice concerns, and provide feedback, all without fear of retribution, you'll empower them to be able to work more independently on the schedule that works best for them, and they won't be held up waiting to ask for your approval. Plus, being open and able to discuss the hard things with each other means we'll always be growing and improving.

Ways to get started: 

* Be open about your strengths, preferences, and areas of opportunity to help your team members feel comfortable being human too (create a [Human User Guide](https://github.com/matthewmccullough/human-interaction-templates/blob/master/human-user-guide.md) and link to it from your Slack profile, and encourage your team to do the same
* Be open to feedback, admit your mistakes, and show vulnerability
* Prioritize and be fully present in 1:1s, and let your team members drive the agenda (it's their time)
* [Write like a human](./how-github-engineering-communicates.md#communicate-openly-honestly-and-authentically) and be as transparent in communications as possible, and consider creating an FAQ for anticipated questions (remember it's better to say "I don't know" or "I can't answer that right now" than to pretend the question doesn't exist)
* Keep your virtual door open and proactively seek out feedback (send out congrats messages for big ships when you have a few minutes between meetings; pick a few team members to review comms before sending and implement a change based on their feedback; ask more direct questions 1:1 like "What support would be helpful?" or, "What's the biggest risk I'm not seeing right now?")

## Be explicit about expectations

As a team, collaboratively author a set of agreements, captured as Markdown files within your team's repo, outlining your agreed-upon working and communication styles, including anticipated response times and preferred channels. This not only ensures everyone is on the same page, but sets a baseline for what's expected of one another – everyone should be clear on what you expect from them, what they can expect from each other, and what they can expect from you. This activity is especially important when spinning up a new team or reorganizing an existing one, but it's also a good practice to periodically revisit these agreements to ensure they continue to reflect the team's shared values and evolving workflows.

Ways to get started:

* Review the ["How GitHub Engineering communicates" guidance](./how-github-engineering-communicates.md) and talk together about what parts of our "common API" for Engineering communications work best for your team, and which might differ
* Talk with your team about the number of standing meetings on their calendars and be explicit about which ones they're expected to attend live and which they can catch up on asynchronously, so they feel more empowered to take control of their time
* Schedule and honor no- and low-meeting days (like Days of Learning and No Meeting First Fridays) by rescheduling any non-urgent meetings
* Agree on and maintain a single source of truth for team decisions (bonus points if it's easy to find and search through)

## Optimize for the information retriever

Rather than optimizing for immediate information exchange, pause to ask yourself how easy you are making it for someone to come along behind you to understand what you are doing and why, so they can contribute to the conversation. It's essential that we write things down – especially the "why" and the "how" of decisions – in the most durable, searchable, and discoverable medium possible. This is slightly more work up front for the one knowledge creator, but optimizing for the long-tail of knowledge retrieval will save countless hours for all the knowledge recipients. Think of it kind of like removing an N+1 in a heavily trafficked code path: The initial re-write takes time, but not as much as it saves in the long run.

Ways to get started:

* Build time to update documentation into team work plans (and if a document's maintenance outweighs its benefits, delete or simplify it)
* Block focus time on your calendar for writing and reading so you can preserve synchronous team time for high-impact conversations and informed decision-making
* Ensure every meeting has an agenda document (bonus points if it's a discussion post) that's shared ahead of time to collect input from team members who can't attend live, so their voices can be heard during the call (and be sure to post pass-down notes after the call, too!)
* Make any big announcements ahead of (not during) synchronous meetings (this ensures the whole team has access to the announcement, even if they can't attend the call, and they have time to process the information and collect their questions)

## Make more of your work visible

The best way to work in the open and to make that work visible is to use GitHub tools and workflows. [So embrace your inner engineer and default to working within GitHub](https://ben.balter.com/2023/01/10/manage-like-an-engineer/), whenever possible and practical. By working more in the open, you'll naturally capture and expose processes, better preserving institutional knowledge, empowering others to learn through observation, and setting the standard for organizational culture and values. Plus, you'll reduce time spent on status updates, as your team can more easily understand what you're working on and why, plus provide feedback along the way. Of course, there's no need to track every one of your administrative tasks in a team repo; surface the important work (like decisions where you want input, or longer-running issues for which your team is looking for regular updates).

Ways to get started:

* Set up and maintain a leadership team project board so your team has better insight into what's currently in flight
* Seek feedback before decisions are made (rather than asking for feedback on a decision); invite collaboration directly on your issues, discussions, Markdown files, and pull requests; and document how you incorporate the team's feedback (to show you're willing to act on it, and thus it was worth their time contributing)
* Use queries in GitHub to automate team status updates and weekly reports as much as possible and free more of everyone's time (if someone's already reported a status in GitHub, they shouldn't have to repeat it in Slack or in a meeting)
* Mark any information in your own weekly report that's more sensitive and not intended for broad consumption as "private", and then share the "public" version of your report back out with your organization in a discussion post


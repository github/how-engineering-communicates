# How GitHub Engineering communicates
_(Community version, lightly edited, primarily to remove internal URLs and references)_

For a tl;dr version of this document, see [the companion quick-reference guide](./quick-ref.md).

# Purpose and motivation

GitHub has long had a culture of each team enjoying a great deal of autonomy in deciding how they communicate day-to-day. While this freedom allows teams to experiment and uncover novel practices, it also means that working across teams requires first negotiating a meta-conversation around how to communicate before any substantive work can occur. Having an open set of shared expectations within the Engineering organization will allow us to be more effective, mindful, and inclusive about how and where we communicate, leading us to make more well-informed decisions in a way that takes into account different needs, preferences, and time zones.

This document is intended to encourage consistency over preference by outlining a common core of shared internal communication practices for all of Engineering in the form of opinionated guidance, and it was informed by a survey run within the Engineering organization in March 2023. Teams are still encouraged to adapt the practices for their unique circumstances, maintaining a common "API" to interface with other teams.

We expect this document and the guidance within will evolve over time along with our organization, and pull requests are welcome.

# Guiding principles

Overall, the way we communicate as an Engineering organization is informed by the following principles:

## Be asynchronous first

Asynchronous communication is any kind of communication where there is a delay between the information being provided by the sender and the time when the recipient accepts the information and acts on it.

Working asynchronously has [a number of benefits](https://ben.balter.com/2022/03/17/why-async/#benefits-of-working-asynchronously). Knowledge workers [are most productive](https://en.wikipedia.org/wiki/Flow_(psychology)) when they have large blocks of uninterrupted time. A two-hour block of time is not fungible with four 30-minute blocks. Unlike working on an assembly line, for example, when knowledge work is accidentally or intentionally interrupted – whether by a popup, a meeting, or a "hey, you got a sec?" drive-by – there's a significant context-switching cost to get back to where you were. Whenever possible, prefer issues and chat messages to "just in time" communications (like a last-minute meeting), reserving more synchronous methods as points of escalation only when the urgency or complexity of the communication requires it (e.g., for tasks that are time-sensitive and business-critical).

And there's an added bonus: Asynchronous mediums necessitate a distributed workflow. There's no "you had to be there" when "there" is online and anytime.

## Write things down

If we want to be asynchronous first as a globally distributed organization, it's essential that we write things down – especially the "why" and the "how" of decisions – in the most durable, searchable, and discoverable medium possible. We prefer workflows that don't require anyone to be in a certain place at a certain time working on a certain thing in order to collaborate with one another, and one practical way to do this is to ensure every task, idea, or decision has its own URL (meaning if someone asks a question, you can provide them a link to the answer).

There are [a number of advantages](https://ben.balter.com/2015/11/12/why-urls/#the-value-of-giving-concepts-urls) to capturing and exposing processes through URLs. Beyond supporting our asynchronous and distributed workflows, writing things down serves as a message in a bottle to our future selves and our future peers, recording what decisions were made and why, capturing and exposing process and decision making.

## Make work visible and overcommunicate

Capturing and exposing processes through URLs also helps make your work more visible. So [work in the open](https://ben.balter.com/2022/02/16/leaders-show-their-work/) and proactively share your work to the widest extent practical. As we continue to grow as an organization, points of collaboration will become even more important as we try to reduce redundant work. Avoid hoarding information: Like in any production system, observability is key. And if you make something useful, find a way to make it available so others can benefit from it too.

Let others opt-in to context and subscribe to updates. Make it easy for others to understand what's going on, and be sure to add a tl;dr summary at the beginning of any communication to ensure your main points get across.

## Prefer GitHub tools and workflows

The best way to work in the open and to make that work visible is to use GitHub tools and workflows, but only use them when they make sense (and don't use them when they don't). The most important thing is to favor systems that naturally capture and expose processes, and if you don't choose to use them initially (e.g., you make decisions via chat or in a live meeting), be sure to durably capture outcomes after the fact.

## Embrace collaboration

Software development is a team sport. Proactively seek input and feedback early and often. Document not just decisions, but also the context, tradeoffs, and consequences, and do so in a way that allows stakeholders to actively participate in the decision-making process.

Opening a pull request (or posting a discussion or opening an issue) is not collaborative in and of itself. Here are a few tips for more collaborative decision making:

* Seek feedback _before_ the decision is made (don't make a decision and then ask for feedback on it). Statements should be more in the form of "I intend to" rather than "I decided".
* Documents should be a collaboration between authors (decision-makers) and stakeholders to agree on what the problem is, what constraints exist, and how (and when) the problem is going to be solved.
* Documents should live in a location where they are easy to discover (remember to make work visible!).
* Documents should have sufficient detail, including things like availability, rollout strategy, scaling patterns, and timelines.
* Be generous with links in documents, as they are often part of a larger conversation. It's helpful to link to issues, discussions, or other artifacts that provide more context to a decision.

## Foster a culture that values documentation maintenance

We should place as much importance on documentation maintenance as we do on creating good documentation in the first place. Whenever teams are reorganized, or whenever code or processes change, remember to update any relevant documentation and its ownership metadata.

This might require managers to build time to update documentation into team work plans, but the time spent updating documentation will be saved the next time someone accesses it (i.e., if someone finds documentation that's outdated or incorrect, confidence in internal tools decreases and a lot of time is wasted trying to track down the correct information). Leave things better than how you found them: If you find outdated documentation, open a pull request or file an issue for the relevant team to correct it.

However, document maintenance should not be a burden. If a document's maintenance outweighs its benefits, it should be deleted or simplified.

## Communicate openly, honestly, and authentically

We are humans, and we appreciate communication that is transparent and direct so that we don't have to spend time trying to extract meaning from heaps of corporate buzzwords. Say what you mean, in a respectful way, and listen to understand each other (e.g., communication patterns and tone can vary across cultures, so ask for clarification before making any assumptions about intent). And when drafting a more complex communication, like when announcing a process or tooling change, try to anticipate any questions your colleagues might have and provide an accompanying FAQ if needed. Be open about what you know and what you don't – it's better to say "we don't know yet" or "we can't answer this right now" than to pretend the question doesn't exist.

### Strive for inclusivity

Strive for inclusivity, whether choosing date formats, avoiding acronyms without context, or generally being more aware of time zones when scheduling meetings or sending chat messages. Practice inclusive language in all communications. And be mindful of accessibility (e.g., ensure images have alt-text, use semantic Markdown headings and descriptive link texts).

### Use emoji and animated GIFs

Emoji and animated GIFs are the facial expressions and body language of online writing. Use them to convey emotion / tone and celebrate wins. Communication should always remain professional and respectful, but it doesn't have to be formal.

There's a reason our collaboration culture is built on a foundation of emoji and animated GIFs: It's not simply because animated GIFs of kittens are adorable, but because a :trollface: is often the most efficient way to express sarcasm. Not to mention, emoji can make our communication more inclusive, especially for the neurodiverse and those for whom English is not their first language.

Do note that while humor and creativity can keep things interesting and help convey tone, not everyone is a fan of animations, so use GIFs and animated emoji (e.g., sirens and alarms) in moderation. If you find animations distracting, [adjust your GitHub settings to prevent autoplay](https://github.blog/changelog/2022-05-19-option-to-prevent-animated-images-from-playing-automatically/).

Don't fret about using the "wrong" emoji, and if you're struggling to find the right one, GitHub alumna `@muan` created [this handy emoji searcher tool](https://emoji.muan.co/). To support accessibility, ensure custom emoji have a semantically meaningful name (as some people opt to convert emoji to plain text), and if you use an animated GIF on GitHub.com, be sure to include an "alt text" description so that the image is accessible to all (e.g., `![a puppy yawning](puppy-yawning.gif)`).

Finally, it's a good practice to use emoji reactions on discussions, issues, and in chat as an async and low-noise way to acknowledge that you've read something (or your thoughts on the subject, serious or otherwise). You'll often see others "ACK"-ing a chat message to **ack** nowledge that they've seen it, even if they can't respond at the moment. Don't think it's rude. This is a nod to the SYN-ACK handshake in the TCP networking protocol. (Yes, we are a bunch of nerds.)

## Remember practicality beats purity

Remember that these are guidelines, not rules. Process should drive outcomes. Favor intent over mechanics, and encourage pragmatism.

# Communication channels

This section describes which communication channel we prefer for which purpose.

## Chat

After GitHub.com, chat (e.g., Slack) is one of the most common ways we collaborate. Chat is great for real-time coordination, quick questions, and to stay connected throughout the day, but it is ephemeral and provides no guarantee of delivery, especially across time zones (where it can be unintentionally exclusive). Chat is one of our primary communication (and culture) tools, but it shouldn't be your sole means of communication within your team.

Generally, use chat for informal office communication, for community comradery, for water-cooler talk, for tactical coordination, to amplify messages communicated elsewhere, and for other time-sensitive matters that are best handled semi-synchronously, but not as a primary means of decision making or a canonical source of truth (due to its lack of discoverability and permanence). A general principle is to use chat as a means of escalation if you've been going back and forth on an issue or pull request for days without resolution, and if you still haven't reached consensus after several rounds of responses, take it to a call (and then be sure to durably record the decision once it has been made).

Treat chat as transient and hold each other accountable for writing important things down more durably.

### Tips for making chat most effective

#### General tips

* Chat is asynchronous. [Don't force synchronous interactions](https://nohello.net/en/) (e.g., don't just send a "hello"; go ahead and share context/links or ask your question in your initial message). Use `@here` and `@channel` sparingly, if ever, and only for messages that are both urgent AND important.
* Unless a message is marked urgent, aim to respond within one business day during your working hours. Treat direct messages (DMs) more like email or text messages and less like a phone call.
* If you urgently need a response to an issue or pull request, include the URL in your message and ask for a response there.
* Post in public channels (rather than using DMs) whenever possible to encourage knowledge sharing, organic situational awareness, and crowdsourcing of responses. You're more likely to get a better answer, more quickly, and chances are others may share the same question and benefit from hearing the answer. Only use DMs for when the subject requires it, and if it doesn't, encourage moving the conversation to a public channel.
* Don't be afraid to post in public channels for fear of creating "too much noise", but do try to find the most specific channel for the subject. Use threads and emoji reactions liberally to increase the channel's signal-to-noise ratio.
* Don't assume everyone in a channel has read every message. There is no expectation that anyone catch up on channels when returning from PTO.
* Update your profile to include your preferred name, name pronunciation, pronouns, and "what [you] do here" to help others better understand your role. Pro-tip: Include a link to your [Human User Guide (HUG)](https://github.com/matthewmccullough/human-interaction-templates/blob/master/human-user-guide.md).

#### When chat is great

* Chat is a good way to get initial feedback in real-time with people who happen to be around. However, any announcements or longer-term decisions should be documented in a discussion, issue, or pull request. That gives everyone an opportunity to review and be aware of the decision and serves as a more durable, permanent record should we need to refer back to it later.
* Chat is also a good way to get solutions to temporary technical issues (e.g., "my codespace is behaving strangely, does anyone know what's going on?"), but if you find the issue is persistent and requires a workaround, document the process in a more durable location.
* ChatOps (commands run via chat that are visible to others) for common tasks are a great way to bring visibility to work and allow others to learn through observation beyond formal onboarding.

#### Tips for notifications

* Set your status and turn off notifications (or log out of chat altogether) when you need focus time or are out of office. You can also set a "notification schedule" to automatically silence notifications outside of working hours. Unless you are on call, there is no expectation that you're online or responsive 24/7 (even if the message is from your manager).
* Be thoughtful about pushing notifications through outside of working hours when the recipient has turned them off, and consider [scheduling](https://slack.com/help/articles/1500012915082-Schedule-messages-to-send-later) chat messages to be sent later if your message is outside of the recipient's working hours.
* Be mindful of vertical space when posting links with previews, especially in larger channels.

#### Tips for creating channels

* Prefer named channels (e.g., #tmp-topic-working-space) over group DMs as it's easier to add people to the conversation later if needed (and to keep track of the topic of discussion).
* Prefer creating public (to the company) channels, unless there is a compelling reason for the channel to be private.
* Keep channel topics as specific as possible. Prefer small, specific channels over large, generic channels. This allows people to opt in to the information they want.
* Keep noisy bots out of non-bot channels.
* Ensure any channels you create have a clear description describing the purpose of the channel and the intended audience.
* Archive channels once they serve their purpose.

## GitHub

### Repositories

A repository (or "repo") is easiest to imagine as a project's (or team's) folder. A repo contains all of the project files (including documentation), and stores each file's revision history. Each repo contains discussions, issues, Markdown files, and pull requests.

Create repositories for distinct teams and work streams for ease of discoverability and transferability. Be sure to grant the "employees" team "write" permissions to any repository you create to ensure everyone in the company can view it and submit pull requests. If you're worried about "rogue" commits, you can use branch protection and CODEOWNERS to require your team's review. For repos intended for documentation rather than code, consider allowing PRs to be merged without a review; that way, you get the more detailed change tracking of a PR, but avoid much of the friction of the review process. At least one team should have "admin" permissions for the repository.

Also be sure to include a README.md file that provides basic information about your repo and keep it updated so the information is current. For example, for a team repo, the README would list the team's charter, org chart, communications channels, and breadcrumbs that help orient people as to where the team fits in the organization (e.g., "Company → Organization → Team").

And finally, when a project is no longer funded, a team has been restructured, or there is some other reason why the content in a repository is no longer relevant or it is no longer being maintained, close out all remaining issues and pull requests, update the README file and description noting the change, and then [archive the repository](https://docs.github.com/en/repositories/archiving-a-github-repository/archiving-repositories). In many cases, cleaning up after the fact is just as helpful to future travelers as capturing the work in progress while it was happening.

### Discussions

Discussions are intended for long-lived conversations that don't involve a todo/shipped state (although you can now "close" a discussion if it is time bound). Discussions are great for Q&A, internal updates, or social discussions, as well as a starting point for feature ideas and designs. You can even treat discussions like an internal blog.

Discussions enjoy many of the benefits of issues, except they are more suited for ongoing discussions, broadcasts, or blog-like posts with comments that live outside day-to-day work streams.

### Issues

Have a question? Open an issue. Have an idea? Open an issue. Notice something's a bit wonky? You guessed it, open an issue. Issues are cheap. They cost seconds to create, and even if duplicative, are closed just as easily. Issues start conversations, surface alternate points of view, and most importantly, create permanent, searchable, and linkable records of internal conversations, even if the answer ultimately landed on is "wontfix". They naturally capture and expose processes, can easily loop in additional teams, create opt-out-able notifications, cross-link to other issues for ease of discoverability, and can be closed out once the required action is complete to increase the visibility of in-flight efforts. Issues are a placeholder for action the organization needs to take (or needs to decide not to take), and whether they relate to a bug, a feature, or a blog post to be written, they exist to be organized, discussed, and assigned. Don't fret over which repo is "right", as issues can be easily moved between repos within the organization.

Issues on GitHub.com are the atomic unit of work across teams and the primary means by which work is planned, tracked, managed, coordinated, communicated, and shared. Issues bring the most value to teams when conversations and status updates happen on and around the issue, rather than the issue being used as a "TODO" with only an open and closed state.

When issues are long-lived or heavily commented, it's a good practice to keep the issue body (sometimes referred to as the "OP" in internet jargon) up to date for anyone first coming to the issue and to regularly summarize the discussion as a comment that restates the current understanding of the problem and its proposed solution. Also note that if there's more ambiguity, questions of "should we even do this", or "we should do this but there are so many ways to implement it that we should consider", a discussion might be a better starting point. Issues can come out of discussions eventually, once decisions have been made.

#### Keep issues logically distinct

The great thing about issues and pull requests, in contrast to something like email, is that they [can be split](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue#creating-an-issue-from-a-comment) when topics diverge. This keeps teams focused on :ship:ing one thing and only one thing at a time. Additionally, discrete topics minimize unnecessary noise and optimize for fast decision-making by ensuring only the most relevant teams are involved.

In practice, that means an issue should have one purpose, defined by the title at the top of the page. When a concern not directly related to the thread's purpose arises through the course of the conversation, as they often do, open a new issue and encourage participants to continue the discussion there, or if you see a teammate hijacking the conversation, do the same on their behalf. If the sub-task is a blocker, note it as such and move on.

#### Cross-link related issues and pull requests (PRs)

Cross-link related issues and pull requests for discoverability. Use task lists to enumerate sub-tasks. Do not do a significant amount of work that's not tracked by an issue. If necessary, ask people to open issues, or open them yourself.

If you reference something – be it a prior issue, the pull request that implemented a feature, a line in a file, whatever  –  and that thing has a URL, it's your obligation to find that URL and make that reference a link. Even if the reader could theoretically search for it, you are infinitely more familiar with the thing you're referencing, and given a comment read by 5, 10, or 50 people, it's more efficient for you to look it up once than for readers to look it up 50 times. Not to mention, on GitHub, linking to another issue or pull request creates a visible cross-reference, meaning that just by commenting, you create an organic map of the organization's knowledge.

### Project boards

The ways different teams track work can vary (e.g., milestones, tracking issues, task lists), but in general, issues track state at the task level and projects track state at the project level - what's on deck, what's in flight, what's done, who's working on what, etc. When using issues (instead of cards) to track work, projects have all the benefits of issues, but offer a perspective one level of abstraction up.

### Markdown files

Pull requests, and thus diffs, are at the core of our workflow. Whether the change is to code, configuration, or prose text, being able to see exactly what's proposed on an extremely granular level, without the need to download special software or leave the browser is key. If your colleague can't see what you're proposing, there's no way for you to have a serious discussion on its merits.

In practice, that means, as early as the drafting stage, prefer formats like Markdown. Tools like Google Docs are great for collaboration early in an idea's lifecycle, but your goal should be to memorialize the document in an issue, discussion, or pull request for visibility and reach.

Open formats not only allow for diffing, but also facilitate targeted discussions through line-by-line commenting. When that's not possible (e.g., when making tweaks to a site's design), provide before and after screenshots within the pull request body to minimize the burden on reviewers. Remember, you're asking others to take time out of their day to provide feedback on your proposed change. Optimize for their experience, not yours.

### Pull requests (PRs)

Pull requests are the primary means by which proposals are reviewed and decisions are finalized. Sometimes, merging a pull request can be a signal of a decision having been accepted; other times, it's capturing the current state of things, with the expectation that documentation will evolve as we learn more information.

Unless it's a minor typo so irrefutable that no one would possibly question it or need to be notified of the change, the only way to change community content is with a pull request. It doesn't matter if it's code, configuration, or internal policy: For 99% of changes, committing directly to main is not the appropriate choice.

If your pull request closes an issue, link to it by including "closes #123" or "fixes #123" in the body to automatically close the issue once the pull request is merged. If a review isn't automatically requested from an appropriately responsible team, be sure to `@mention` the team to make ownership clear for anyone who comes by in the future (an exception is support requests, where you should seek out the on-call individual and `@mention` them directly). And if you raise a pull request and notice an unrelated team is pinged for CODEOWNER review, it's your responsibility to update the ownership information as part of your requested change.

To keep things actionable when reviewing a pull request, prefer specific in-line comments (ideally with suggested changes) over sweeping, document-wide reviews. Avoid "changes requested" unless you intend to block the pull request from merging without your explicit approval. It's not just about the change you're making today, but allowing others to understand context down the line.

### Managing GitHub notifications

While we may not often use email internally, we rely heavily on GitHub notifications. Like your email inbox, it is expected that you subscribe to the appropriate repos, regularly check your GitHub notifications, and respond to `@mentions` and team mentions as necessary. To cut down on some of the noise, consider [enabling the "Only notify requested team members"](https://docs.github.com/en/organizations/organizing-members-into-teams/managing-code-review-settings-for-your-team#about-team-notifications) code review setting for your teams so you can request specific individuals for review without notifying the entire team.

Teams and individuals should strive to respond to non-urgent GitHub notifications within one business day during their regular working hours. If an issue or comment fails to garner a response, consider escalating the issue to the appropriate chat channel.

[Notifications](https://docs.github.com/en/account-and-profile/managing-subscriptions-and-notifications-on-github/setting-up-notifications/configuring-notifications) can be delivered either via email, mobile, or as web notifications via your GitHub.com inbox ([here's one real-world example](https://ben.balter.com/2020/08/25/how-i-manage-github-notifications/) of how to manage notifications). To enable notifications, go to the GitHub Settings page and select [Notifications](https://github.com/settings/notifications). Scroll to the "Participating" section and opt in to email and/or web and mobile notifications.

Whether in GitHub notifications or notifications via any other communications tool, always provide context when `@mentioning` another person. A contextless "`@monalisa`" notification is a lot less actionable than a specific request or call to action. And if you're only referring to someone, but don't actually need their attention, surround the `@mention` in backticks (`) to avoid the ping.

## Google Docs

Google Docs are great for early ideation with a small, trusted group (and it's easier to change the visibility of a Google Doc for different people than it is to manage permissions in a repo), but Google Docs are not as great as a canonical source of truth due to lack of discoverability and closed-by-default permission model. Once an idea becomes sufficiently mature and is ready to be shared more broadly, memorialize it on GitHub via an issue, discussion, or pull request.

Google Docs discovery is poor, as is understanding the state of a document once you discover it and gain access. Use a Google Doc early in an idea's lifecycle, but burn it down as soon as possible and replace the content with a link to the canonical source in GitHub to avoid confusion. Google Docs are great for ideation and definition (or in-meeting note taking), with the goal of ultimately memorializing the document in an issue or PR for visibility and reach. Think of it as "top-of-the funnel collaboration".

Here are some additional tips for using Google Docs:

* Include the document owner, status, and shareability at the top of the document.
* Once moved to GitHub, include the URL in the Google Doc along with a note about the document's status.
* Default to sharing documents with the organization (ability to comment), unless sensitive.
* For longevity, prefer documents in shared drives over an individual person’s account.

## Live meetings

When we say that GitHub is "async first", we mean that literally. Synchronous meetings shouldn't be required to kick off an initiative; instead, they are a [point of escalation](https://ben.balter.com/2023/04/20/meetings-are-a-point-of-escalation/) based on complexity.

Of course, the percentage of time you spend in meetings will vary depending on your role. Some roles, like that of manager, require more synchronous connections (e.g., 1:1s with reports, cross-functional leadership team meetings, coaching sessions) than others. We should always strive to use the right tool for the job, and for managers, based on the jobs they have, that might mean more frequent live meetings.

Here are some ways to ensure meetings are effective:

* Meetings are an incredibly valuable tool when used correctly. Quickly escalate to meetings when the topic calls for it (e.g., interpersonal conflict/connection, problem solving, when you've been unable to reach a resolution via GitHub or chat).
* Meeting topics should be as specific as possible and have the minimum number of the right attendees who remain present and engaged. You are encouraged to leave a meeting if it is not a valuable use of your time.
* Unless it's an informal/social call, all meetings must have an agenda and clear goals (you are empowered to decline if they do not). Consider an ongoing agenda/notes doc to queue up topics for recurring meetings. Phrase agenda items in the form of questions to make it easier to determine if meeting goals were accomplished.
* Meetings should start and end on time. If you finish early, consider using the remainder of the time for informal conversations and to connect as humans.
* Use meetings to discuss information, not to convey it. Send information ahead of time as a pre-read. Do not make any major announcements in live meetings without sending prior written communications.
* Meetings shouldn't be used for status updates, to force work to happen (e.g., scheduling time with someone to ensure they complete a task), or for any task that's best handled asynchronously.
* Memorialize decisions after the meeting in a durable medium. Ad-hoc meetings do not necessarily constitute a final decision (especially on technical matters). See "Write things down" earlier in this document.
* Unless you're having a personal conversation or are discussing sensitive content, record the meeting so those who couldn't join live can catch up.

Here are a few additional meeting pro-tips:

* Either enable "speedy meetings" (end 5/10 minutes early) in your calendar settings or schedule meetings to start 5/10 minutes late to allow for time to be human between meetings, and be strict about ending (or starting) at the specified time.
* In smaller meetings, use the meeting chat for side conversations. Share links outside the meeting via chat (e.g., Slack) so they remain after the meeting concludes.
* In larger meetings (or webinars), consider disabling the meeting chat and opening a separate chat (e.g., Slack) channel for discussion, as screen readers by default read messages posted to the meeting chat over the voice of the presenter.
* Keep your camera on whenever practical. To reduce video-call fatigue, try minimizing the size of the meeting window on your screen and/or turning off your "self view".
* Practice inclusivity: Give people multiple ways to interact, so they can choose the ones that make them most comfortable. Encourage hand raising and use of the meeting chat.
* Managers, be explicit with your team members about which meetings are considered mandatory and which can be skipped (or which meetings they can catch up on via recording at their convenience). Meeting loads can get out of hand, and sometimes it's hard to figure out what's required and what's just FYI.
* Be mindful of holidays and working hours, especially across time zones. You can find someone’s timezone in their chat profile (or in their calendar when you are scheduling a meeting). You can also specify your working hours [on your calendar](https://support.google.com/a/users/answer/9308669?hl=en) to help with scheduling.
* When referring to a meeting time, be sure to include the time zone, and try to avoid location-specific references like "this morning" or "in the Spring" to describe timing. Prefer the ISO 8601 standard YYYY-MM-DD (except in long-form writing), but anything consistent and unambiguous will do.

### Calendar invites, settings, and entitlements

Scheduling is hard, especially across time zones. To make it easier on your colleagues, you can modify [your Google Calendar settings](https://calendar.google.com/calendar/r/settings) to enable the "modify event" default guest permissions. That way, if something comes up, the person you're meeting with can propose an alternate time that works better for them.

Better still, if your role allows, modify your default calendar's permission by checking the "Make available for the organization" box to allow others to see descriptions of your events. Asking someone if they can reschedule a 1:1 or a task reminder you have blocked off is a lot different than rescheduling a customer meeting or daycare drop off. Of course, if you do that, you'll want to mark any potentially sensitive events as private.

## Video recordings

In the spirit of "be asynchronous first", if you have a unidirectional broadcast (e.g., for readouts, demos, design iteration, or announcements that do not require any interaction or audience participation), consider uploading and sharing a recording rather than scheduling a live meeting.

Also, unless you're having a personal conversation or are discussing sensitive content, be sure to record all meetings and share the recording so those who couldn't join live can catch up. Transcripts also make it much easier to find specific information.

For sociability, consider scheduling "watch parties" for recorded content, allowing people the optional opportunity to see each other's faces before playback begins and to use meeting chat to interact during playback.

## Email

Email is an ineffective collaboration medium and an even worse mechanism for storing organizational knowledge. There's no opt-in or opt-out mechanisms, no ability to link to or cross-reference discussions, and conversation history lives in a teammate's personal inbox, so when they leave, so too does the thread's context. Use email sparingly and only when issues or chat, exposed to the company, would be inappropriate for the conversation. Put another way, email is for sensitive conversations (or for conversations with people outside the company).

In practice, that means email is typically reserved only for things like personnel discussions, one-to-one feedback, and external communication. The same goes for other mediums (like phone calls) that don't automatically capture and surface context. If you can have the conversation in a better medium, you should.

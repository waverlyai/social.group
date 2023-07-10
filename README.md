# Social.Group

## What is this space about

We aim to utilize ATProtocol and Bluesky primitives as a foundation to provide communities with tools for organizing themselves. We are developing this project openly and welcome collaboration from other companies or individuals who share the same goal. The purpose of this space is to develop solutions on top of ATP in a generic and reusable manner.

### Waverly

Waverly will also develop separately an opinionated client that incorporates the concepts described here. However, we believe that most of the unique flavor and user experience of Waverly can be developed at the application level through the client and view, independent these building blocks. More information will be provided in the future.

## Context

We are not affiliated with Bluesky and operate independently. As we familiarize ourselves with the ATPProtocol concepts, we may make mistakes. Our initial objectives are:

- Document and consolidate information on the topic.
- Describe our ideas to inspire collaboration from others.

## General goals

These are our current goals, and we are happy to discuss them!

- The group is owned by the community: We aim to apply the same principles as Bluesky. Just as a user account is owned by the end user, a group account should be owned by the community. Group data, including group moderation data (accepted or rejected post references, blocked, muted...), should be stored in a repository owned by the group owner(s).
- User's posts to a group are still owned by individual users, similar to Bluesky. We embrace the distinction between creation and distribution: Users are free to create or delete content, and the group is responsible for managing the dissemination within the group.
- Client choice: We welcome client diversity. In the long run, moderators and members should be able to choose their client. Whether Bluesky can be used or if a specialized client for the group is needed is still to be determined (TBD). We anticipate a choice between compatibility and user experience, but we have decided to prioritize compatibility initially until it becomes unfeasible.

## Group features

Several features are required to support communities. A group is similar to a user in several aspects:

- Users may follow a group to receive content from it.
- A group may choose to distribute a post or not, just like a user may choose to repost a post.
- A group contains a description and a small space to set expectations, similar to a user profile.
- A group may ban or mute an account for moderation purposes.
- A group should be discoverable, just like an individual.

Some differences:

- A group is usually centered around a specific theme but could also be a group of people.
- Different groups have different rules to accept members.
- A group is structured in a way that different individuals have different roles, such as member, moderator, or owner.
- Groups usually come with a set of automation, moderation, and management tools.
- A group could be private. However, similar to Bluesky's lack of support for private direct messages (DMs) in the initial iteration, we plan to initially focus 100% on public groups. This decision is motivated by a greater alignment with Bluesky, and public groups will contribute more to the open network!

## Relevant references

### Moderation proposal

The community experience is a significant aspect. While Waverly aims to integrate guideline application closely with member experience using NLU technology, moderation will always remain a part of the community toolkit.
[Bluesky proposal](https://github.com/bluesky-social/proposals/tree/main/0001-user-lists-replygating-and-thread-moderation)

### A thread about reddit on ATP

[Reddit alternative on ATProto](https://github.com/bluesky-social/atproto/discussions/1199)

## Contributors

- Philippe Gagnon [@p-gag](https://github.com/p-gag), [pgag.bsky.social](https://bsky.app/profile/pgag.bsky.social)

## Disclaimer

This document represents our current goals and ideas for Waverly Social. Please note that as this project evolves, these goals and ideas may change or be refined. While we strive to provide accurate and helpful information and tools, we cannot guarantee their completeness or suitability for your specific needs. The use of any information or tools mentioned in this document is at your own risk. We are not responsible for any damages or consequences that may arise from the use of the information or tools provided. We are actively open to feedback, collaboration, and improvements from the community. Thank you!

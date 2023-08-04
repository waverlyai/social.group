# Bot-Powered Group

Use a bot account as a way to build a collective distribution list with rules.

## Context

We want to develop group functionalities over ATP, but Bluesky is still in its early stages. Because we share their important vision, we don't want to distract them too much until Bluesky's basic features with federation are open for everyone.

This solution started by thinking about how we could hack around the existing features of Bluesky without waiting for federation or protocol expansion. To be frank, the more we dig into it, the more we see benefits stemming from protocol/client compatibility.

We don't know if this solution is sustainable, but it looks like a fun experiment. Once the protocol development and federation are open, we will likely find more elegant ways to handle groups.

## Using existing protocol Solution

Create a bot that will be controlled by a community. The diffusion part will be handled by re-posts from the group, and people will be able to follow the group by following the bot. The bot can signal the acceptance of members by following them back. The bot configuration could be made in different ways, ranging from group managers tagging it with commands (we like NLU) to a classical web interface outside of ATP until we develop a group setting protocol.

- Users may follow a group to receive content from it.
  - [x] Just follow the group-bot.
- A group may choose to distribute a post or not, just like a user may choose to re-post a post.
  - [x] We can build all this in a bot configuration. We could even build a pending list for approval.
- A group contains a description and a small space to set expectations, similar to a user profile.
  - [x] The bot profile.
- A group may ban or mute an account for moderation purposes.
  - [x] Bot profile with Mute/Blocked account.
- A group should be discoverable, just like an individual.
  - [x] Search in Bluesky client or group-bot list in a custom app.
- A group is usually centered around a specific theme but could also be a group of people.
  - [x] Bot configs.
- Different groups have different rules to accept members.
  - [x] Bot configs.
- A group is structured in a way that different individuals have different roles, such as member, moderator, or owner.
  - [x] Bot configs. Group owners could use app passwords for the bot account to give to moderators. The config could also have different access levels.
- Groups usually come with a set of automation, moderation, and management tools.
  - [x] Some may be heavy, but it looks feasible.
- The posts within a group, and the replies to these posts by group members, can be browsed in a group feed.
  - [x] We can do that in a custom app. See Waverly client.

## Limitations

- Bluesky is invite only so we would need to find groups and members that are already in Bluesky.
- Group bot will require invite code which is hard to find at this time.

## Waverly Client Solution

While stretching the existing protocol seems to check most boxes, we believe that groups should provide a unique experience, and we think we need a custom client to fully realize it. While it's great that someone could follow a group from the original Bluesky client, we anticipate that many users will appreciate the focused environment of a 100% group-based platform.

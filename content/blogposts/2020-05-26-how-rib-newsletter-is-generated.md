---
title: "How RiB Newsletter is Generated"
date: "2020-05-26"
description: "How RiB Newsletter is Generated"
author: Aimee
slug: /how-rib-newsletter-is-generated
categories:
  - "blogposts"
  
summary: Rust in Blockchain publishes a monthly newsletter that shares relevant technical content to the Rust blockchain development community. In this post, we will introduce how our monthly newsletter is generated, the content structure and the workflow.
---

Rust in Blockchain publishes a monthly newsletter that shares relevant technical content to the Rust blockchain development community.

In this post, we will introduce how our monthly newsletter is generated, the content structure and the workflow.

We hope it will be easier for you to contribute to the [next issue](https://github.com/rust-in-blockchain/rust-in-blockchain/tree/master/draft).

## RiB Newsletter Structure

- Each month introduction: summary of the month's events
- Thanks:
a list of all the contributors to this issue
- Project Spotlight: one cool project each month, per our preference
- Interesting Things:
  - Interesting Rust & blockchain projects, GitHub repos
  - Articles, particularly on cross-cutting technical topics
  - Twitter threads
  - Anything that you think is interesting to the community
- Most Active in each month: a list of projects with the most GitHub activities
- Project Updates:
  - GitHub activity numbers
  - News
  - Blog posts
  - Videos and podcasts
  - Important or interesting GitHub PRs and issues
- Events: developer related blockchain events
- Careers: a list of developer jobs

## Content Generation

Every month we
- Call for contribution one week ahead of the publish date (will introduce publish date in the next section)
- Accept contribution from GitHub, deal with PRs and issues
- Accept contribution from other channels. e.g. [Twitter](https://twitter.com/rust_blockchain), [Email](hi@rib.rs), [Telegram](https://t.me/rustinblockchain)
- Generate newsfeed from projects' RSS subscription
- Run Ribbot one day ahead to calculate GitHub data from projects in rib-bible
- Discuss on Introduction, Spotlight, Interesting Things sections (we gather some of the content from reading news randomly)
- Review the final draft
- Create the next draft file

## Publishing

The RiB Newsletter publishes on the first Wednesday of each month (Pacific time), towards the end of the day.

- Publish the newsletter. Technically, we move the current issue from draft folder to content folder, build and deploy it
- Copy the published page to Mailchimp and send newsletter to email subscriptions
- Share the published page to Twitter, Reddit, Hacker News, and some related groups

In the future, we will optimize our workflow to make it more efficient and easier to contribute to. The [next draft](https://github.com/rust-in-blockchain/rust-in-blockchain/tree/master/draft) is ready to accept contributions ;)

Please let us know your thoughts and suggestions anytime.

Join RiB [Telegram group](https://t.me/rustinblockchain) for community discussions.

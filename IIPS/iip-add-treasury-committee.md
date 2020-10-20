---
iip: <to be assigned>
title: Create a Treasury Committee
status: WIP
author: <Inje Yeo (@inje)>
discussions-to: <to be assigned>

created: <2020-10-20>
---

## Simple Summary

This is a proposal to create a treasury committee with 10,000 INDEX tokens (approx. \$30,000 at time of writing) that handles rewards distribution modeled after other early-staged communities like YFI.

## Abstract

The Index Coop doesn’t currently have an agreed upon system for how rewards are distributed. This proposal introduces a lite treasury committee initially run by the Set team that helps distribute rewards to the community. The proposal leaves room for the community to evolve into using a multi-sig and SourceCred in the future for objectively quantifiable rewards tracking if we decide to move in that direction in the future.

This IIP proposes the treasury committee be granted 10,000 INDEX tokens (approx. \$30,000 at time of writing) dedicated to paying out contributor rewards over the next 2 - 3 months. After funds are distributed, the treasury committee will reapply for a new rewards grant to continue rewards distribution.

## Motivation

Consistent rewards for valued contributions are important for making members feel like they are part of the community and that their contributions are acknowledged. The current state of the Index Coop does not have a rewards system in place to determine which contributions get rewards, and which do not which leads to no rewards being distributed at all.

We’ve tackled the first two parts of the member ownership cycle in the past two weeks, and now have the last rewards piece remaining in order to make members feel a sense of ownership in the community.

![|418x267](https://lh6.googleusercontent.com/vNnh8x4xG6Cxr3RvoNDGLAH4BP1mhL79wFNcdFRr5FNPdwRPfx9wFM_3rQ5Mi0MtNkAxSiAGxixgDKya8kjtsa-RDFB_jlFoK3aORKKQGC-6ZJSl51GkGn5oLbTAxt-HaCupiSQp)

Without a system to handle rewards, members may struggle to find longer term motivation to continue contributing to the community. Other communities (YFI and Synthetix) have solved this by creating a treasury committee that handles how rewards are distributed. The proposal specifies a system for the Index community modeled after those existing systems.

The treasury committee commits to values of:

- Fairness - Members should feel like the rewards they are given are fair and proportional to the contribution they’ve made.
- Sensibility - The treasury should be spent wisely for the community and goals of the community, not on things that don’t contribute to the goals of the coop.
- Flexibility - The rewards system should take into account multiple types of contributions and and varying depths of contributions (1 off bounties to longer term rewards)

To exemplify these values from the start, the treasury committee will not pay Set or DeFi Pulse team members using these funds.

For

- Create a lite treasury committee initially led by the Set team that spearheads the rewards distribution for the community.
- Initially grant the treasury committee 10,000 INDEX tokens ($30,000 at $3 / INDEX) to distribute as rewards to Index community members.

Against

- Do not create a lite treasury committee.
- Propose a different solution for rewards distribution.

## Prior Work

This proposal pulls on prior work for community contributions from [YFI](https://gov.yearn.finance/t/september-grants-announcement/7044) and [Synthetix’s](https://blog.synthetix.io/synthetix-grantsdao/) rewards systems which have small committees to help the community determine which contributions are rewardable and which ones are not, and Maker which uses SourceCred, an algorithmic system to determine the value of contributions. This helps contributions stay focused with the goals of their respective communities while also providing a framework for community members on what kinds of contributions are rewardable.

Below is a summary of the research gone into YFI, Synthetix, and Maker, all of which are different staged communities that have a rewards system in place.

| Name | Community Age | Rewards System Takeaways                                                                                                                        |
| ---- | ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| YFI  | Early         | - YFI uses a Treasury Committee to distribute rewards. [September Grants Post](https://gov.yearn.finance/t/september-grants-announcement/7044). |

- The Treasury Committee is just Milkyklim and Banteg for now.

- They admit that the system is flawed, and may have biases, and are brainstorming ideas around a rotating committee.

- They pay out at the end of each month.

- They pay long term payroll and one off bounties.|
  |Synthetix|Mid|- Also uses a Treasury Committee.

- Their treasury committee is a DAO called the [GrantsDAO](https://blog.synthetix.io/synthetix-grantsdao/) which is a more formal structure than YFI’s.

- The GrantsDAO is a 4/5 Multisig that discusses and approves/denies improvement proposals.

- Proposals are made to the GrantsDAO in a similar format to SIPs, and have a rewards amount and estimated amount of hours attached to each proposal.|
  |Maker|Late|- Uses [SourceCred](https://sourcecred.io/) to measure and track contributions.

- SourceCred is an algorithmic system based off of PageRank used by Google which ranks website importance based on the amount of links that point to a given website. The algo is built to be sybil resistant.

- They just [finished a trial of SourceCred](https://forum.makerdao.com/t/sourcecred-trial-final-report/4569), and deemed it a success. They’ve voted to extend the trial for an additional 3 months.

- The trial was from June 1st to August 31st.|

![|505x259](https://lh3.googleusercontent.com/LzOPzxGxQs0ADALmgmdsB0wJZqehhPQSwp1zjSNI_ymM3JQ5VMM5h_CgHhhotNAv-LXcuuiuKi-ad8RHwWe5mLSpbBvOS2o6qCw_2Vx3NXDxs6gM3YrfNzPXZj67VkulMwm-uBIH)

From this research, we assume that for an early stage community like the Index Coop, we should go with a lite implementation of a rewards system similar to YFI’s where there’s an initial treasury committee made up of the core team, in this case Set.

Eventually if it makes sense, we can propose evolving the system to something like Synthetix and/or Maker where we use a multi-sig involving community members, and add an algorithmic contribution measuring system like SourceCred.

## Specification

### The Treasury Committee (Lite)

This IIP proposes creating a lite version of a treasury committee initially run by the Set team (like YFI’s rewards system) that handles rewards distribution for the community.

We assume that there will be a certain amount of subjectivity for which contributions are deemed worthy of rewards, and how much each contribution should be paid, which we may be able to reduce in the future through adding more members to the committee and potentially using SourceCred.

#### The Treasury Committee’s Request

The Treasury Committee requests 10,000 INDEX from the community treasury to distribute to members of the community who contribute meaningfully to the Index Coop.

The 10,000 INDEX value is an estimated amount of funds for a 2 - 3 month trial run of the treasury committee. We can expect around 3,000 - 5,000 INDEX ($10,000 - $15,000) worth of rewards given out each month to contributing community members, excluding the Set team.

Follow Up Funding

After the funds are spent, the Treasury Committee will apply for a new grant from the community treasury while also posting a report on how the previous funds were spent to demonstrate a good record of spending community funds wisely.

### How it works

The treasury committee handles:

- Deciding Reward Sizes - The committee determines which contributions should get rewarded and by how much depending on if the contributions fall in line with the general goals of the coop, how much impact the contribution has, and how much effort the contribution required.
- Creating Reward Distribution Proposals - The committee creates proposals for rewards distributions at a regular cadence for contributing members.
- Keeping Track Of Contributions - The treasury committee should keep track of contributions happening to the Index Coop in order to properly create rewards distribution proposals, and give an early indication whether or not proposed contributions will see a reward by acknowledging proposals.

![|624x223](https://docs.google.com/drawings/u/1/d/sXndlY_3JEkaOSvAyNsQA8w/image?w=624&h=223&rev=1&ac=1&parent=1oatOdJw5r0mRISvEQynvV__Tb_NwSahOEqD0XfFsHIA)

Contribution Rewards Submission

In order to mitigate community members not getting their rewards from missing some contributions, we’ve created a Typeform where community members can submit their contribution so that they’re tracked. Members can submit their submissions here for rewards consideration.
https://setlabs.typeform.com/to/jMjgA5z3

### Maintaining Integrity

If the Treasury Committee does a good job, future treasury grant requests will continue to be approved by the community. If the Treasury Committee does not do a good job, then the Index Coop can deny their treasury grant requests and a different community member can propose an alternative community funding mechanism.

### Rewards Flow

1. Proposal - An improvement proposal is proposed by a community member on the forum or Discord.
2. Initial Eligibility Determination - If a user proposing an improvement asks if there’d be a reward for adding a contribution, the treasury committee will chime in to say if the proposal is rewardable based on the goals of the Index community.

3. Accepted - If it is eligible for a reward, the community searches for members to implement the proposal. It’s assumed that some proposers will be the implementers.
4. Denied - If it is denied, a treasury committee member lets the proposer know that it’s not eligible for a reward.

5. Implementation - The proposal goes through implementation, then is reviewed.
6. Final Review - The treasury committee views the work and determines if it meets the bar for a reward to be paid out.

7. Accepted - The implementation is accepted and a reward is paid out to the implementer.
8. Denied - The implementation is deemed ineligible for the reward. The implementor is required to revise their implementation before submitting for review again.

9. Payment - The treasury committee sends payment to the implementor.

### Copyright

Copyright and related rights waived via CC0

# DIP1: Monthly Governance Cycle

## Preamble  

```
DIP#: 1
Title: DGC Monthly Governance Cycle
Author: Saleem Fareed (@Dijets-Inc)
Domain: 0
Type: Process
Status: Accepted 
Date Proposed: 2023-05-25
Date Ratified: 2023-05-25
Dependencies: n/a
Replaces: n/a
Notes: Founders Category
```

## References  

N/A

## Sentence Summary

DIP1 defines a Monthly Governance Cycle that provides a predictable framework for Dijets Governance decisions.

## Paragraph Summary

DIP1 describes DGC Governance Schedule by proposing a Monthly Governance Cycle that can help provide the council with a predictable framework for Dijets Governance activities, discussions & decisions. The Governance Cycle aims to provide an efficient and accessible framework as an anchor-point for the council to refine and improve upon the governance schedules.

## Modules Summary

**DIP1m1: Governance Cycle Breakdown**

Breaks the Governance Cycle down into individual actions that take place each week of the monthly cycle.

**DIP1m2: Voting & Ratification Polls**

Defines the parameters for a Poll under the DIPs governance framework process.

**DIP1m3: Calendar Exceptions**

Defines exceptions to the monthly governance cycle.

## Motivation

Dijets monthly governance cycle aims to provide advance notification and high predictability of governance activities to occur during any given month for DGC Members to stay informed on relevant subjects and progress etc. Having a predictable and standardised framework for a monthly schedule also allows DGC Members to participate in voting without any time constraints. The schedule should encourage DGC Members to pick governance activities in their own time.

The structure of the governance cycle enables DGC Members to join the discussionat the proposal submission level from the very beginning right to the end of its lifecycle and implementation. Members with less governance participation can simply review the end results at the end of the month and decide whether or not to vote for any polls or mandates. Note that members participation is directly proportional to their prospective earnings via HAL's incentives pool and contribution objectives.

Proposals submitted into the Monthly Governance Cycle must follow the guidelines defined in [DIP0](https://dips.dijets.io/dips/details/DIP0).

## Specification / Proposal Details

### DIP1m1: Governance Cycle Breakdown

The first Monday of each calendar month marks the beginning of Dijets Monthly Governance Cycle.

### Week 1

**Week 1, Monday through Wednesday**

- DGC Members acquire their monthly **_Collateralised Accountability Position_** or CAP.
- CAP can be procured by a DGC Member by locking min 1000 DJTX as collateral to mint the equivalent amount of HAL tokens required to participate in Dijets Governance.
- At the end of the monthly governance cycle DGC members can redeem 1050 HAL Tokens for the originally locked 1000 DJTX back. 
- The 50 additional HAL Tokens act as a superficial fee to close and settle their CAP positions. HAL Tokens can only be earned by participating in Dijets Governance.
- CAPs are designed to encourage accountability and positive contributions. Failing to return the required 1050 HAL Tokens may result in DGC Member's CAP position being liquidated with the 
collateralised 1000 DJTX moving into HAL's incentive pool for other members to earn.

**Week 1, Thursday through Sunday**

- DGC Members submit their proposals to **Formal Submission**. The window lasts for 8 days.
- Proposals must be moved into the [Formal Submission](https://forum.dijets.io/c/dips/formal-submission/6) subcategory on Dijets forum under the [Dijets Improvement Proposals](https://forum.dijets.io/c/dips/5) category.
- DGC Members should inform a [DIP Editor](https://forum.dijets.io/g/DIP-Editors) of the status change via commonly used communication channels.

### Week 2

**Week 2, Monday through Thursday**

- **Formal Submission** window is open.

**Week 2, Friday through Saturday**

- Core Team conducts **Submission Reviews** as part of the weekly Governance process and communicates which of the proposed DIPs are in accordance with the guidelines (defined in the [DIP0](https://dips.dijets.io/dips/details/DIP0) Framework).
- Core Team communicates required amendments/improvements to the submission with the authoring DGC Member.

**Week 2, Sunday**

- DIPs that meet the guidelines and are not found objectionable by the Core Team will be published to the [DGC-Polls GitHub](https://github.com/Dijets-Inc/dgc-polls/tree/master/governance/polls), with the member's details.
- Successful submissions are recorded on-chain and appear on the official [voting portal](https://vote.dijets.io) for DGC members to begin voting on.

### Week 3

**Week 3, Monday through Sunday**

- DGC Members must vote and come to a consensus on each of the poll to move it forward to the execution phase. 
- DGC Members may consider blocking a proposal if they believe the proposal to not be in the best interests of Dijets.
- Member voting 'NO' to a proposal from moving to execution phase, must communicate his/her reasons for doing so via the comment option in the polls.
- Polls will run for 9 days.

### Week 4

**Week 4, Monday through Tuesday**

- Voting continues.

**Week 4, Wednesday**

- Voting Results are officially published on the [Voting Portal](https://vote.dijets.io) with each proposal marked **Accepted** or **Rejected**

**Week 4, Thursday through Saturday**

- DGC Members reverse their monthly CAPs and reset their accountability obligation to zero.

**Week 4, Sunday**

- Proposal Implementation begins following a mandatory pause delay of 48 hours.

---

### DIP1m2: Polls

Each Poll held under the Monthly Governance Cycle must meet the following requirements:
* **Duration:** Min one week.
* **Minimum Positive Participation:** 10,000 HAL.
* **Type:** Binary Poll (yes/no/abstain).

Ratification Polls under the Monthly Governance Cycle must contain:
* Links to a *specific version* of a single proposal or set of related proposals (DIP Sets) within the official DIPs GitHub repo.
* The Sentence and Paragraph Summaries of each included proposal.

In order for an approval Poll to conclude successfully and the proposal(s) contained therein to move to Accepted status, each of the following conditions must be true:
* `Yes` vote-weight must exceed `No` vote-weight when the poll closes.
* `Yes` vote-weight must exceed the `Minimum Positive Participation` value of 10,000 HAL when the poll closes. This equates to majority consent among the council members provided that each member starts the monthly governance cycle with the same amount of HAL Tokens hence had the same voting weight.

---

### DIP1m3: Calendar Exceptions

In its current state and term Dijets Governance Council is mostly comprised of members residing and located in Europe. Due to the multitude of holidays occurring in and around the month of December primarily in Europe and North America, there will be no Monthly Governance Cycle for the month of December each year.

---

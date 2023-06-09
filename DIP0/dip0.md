# DIP0: Dijets Improvement Proposal Framework

## Preamble
```
DIP#: 0
Title: Dijets Improvement Proposal Framework
Author(s): Core Team (@Dijets-Inc)
Contributors: @lasthyphen
Type: Process Module
Domain: 0
Index: 0
Status: Accepted 
Date Proposed: 2020-04-22
Date Ratified: 2020-05-22
Notes: Founder's Category
Dependencies: n/a
Replaces: n/a
```

## Sentence Summary

DIP0 defines and describes the DIPs Framework. 

## Paragraph Summary

DIP0 is the genesis proposal describing the DIPs Framework. This includes the core components and statuses as well as the various DIP types and the overall DIP lifecycle. Furthermore, it provides the necessary tools, such as DIP templates, replacement processes, and dependencies. DIP0 also provides details for the key roles of the framework, the DIP Editor and the Governance Arbiter along with the process for adding and removing them.

## Modules Summary

**DIP0m1: Definitions of the Dijets Improvement Proposal Framework**  
Defines several concepts that are important for understanding the DIPs process.

**DIP0m2: Core Principles**  
Describes the core principles that all DIPs must adhere to.

**DIP0m3: The DIP Lifecycle**  
Explains the DIP lifecycle process from its inception all the way to becoming Accepted or Rejected.

**DIP0m4: DIP Domains and DIP Domain Indices**  
Discusses the use of domains and index to better organise the DIPs

**DIP0m5: DIP Amendment Process**  
Describes how DIPs can be amended/replaced and the steps required to maintain its dependencies.

**DIP0m6: Supporting Materials**
A module that defines how to include external materials inside DIPs.

**DIP0m7: DIP Templates**  
Defines the DIP templates for both General and Technical DIPs.

**DIP0m8: Core Personnel Role Dependencies**  
Outlines Core Personnel roles and dependencies in the DIPs Framework.

**DIP0m9: DIP Editor Role**  
Defines the responsibilities, criteria and grounds for removal for the DIP Editor role.

**DIP0m10: Governance Arbiter Role**  
Defines the responsibilities, criteria and grounds for removal for the Governance Arbiter role.

**DIP0m11: Core Personnel Onboarding**  
A process module that describes the process to add personnel to the DIP Editor or Arbiter roles.

**DIP0m12: Core Personnel Offboarding**  
A process module that describes the process to remove personnel from the DIP Editor or Arbiter roles.


## Motivation

The purpose of the DIPs Framework is to provide a standardised approach to improving Dijets Governance across the Ecosystems five main domains by the currently serving council.

By standardising the participation of the governance council to have a unified approach to proposing improvements, specifications, or process and state changes, the goal is to enable an open and fully transparent governance structure that rewards accountability and encourages positive contribution.

In order for DIPs to be comprehensively functional they need to comply with a basic standard which clearly outlines their internal structure and external dependencies. This standard is described in DIP0, as the genesis proposal for Dijets Improvement Proposal Framework.


## Specification / Proposal Details

### DIP0m1: Definitions of Dijets Improvement Proposal Framework

-   **Dijets Improvement Proposals (DIPs):** are the preferred mechanism for improving Governance across Dijets five domains through an open and documented process, the goal is to collect Dijets Council's feedback and voting as the definitive way to reach the broadest possible consensus on how Dijets Ecosystem should evolve. A proposal clearly defines how and why an index component across the five main domains of Dijets Ecosystem should be changed and ensures that this improvement is introduced in a responsible way, respecting the highest quality, security and standards.
-   **DIP0:** The genesis DIP defining the DIPs framework. This DIP defines all of the processes that are required for the implementation of future DIPs. 
-   **DIP Sets:** A DIP set is a group of several DIPs that are interdependent, wherein without the entire set of DIPs existing, individual DIPs in the Set become inconsistent, invalid or uncomprehensive. The intention is for DIP sets to together describe a single complex behaviour in such a way that allows each individual DIP to be written following the principle of Specificity but work together as a single cohesive unit.
-   **DIP Domains:** DIPs are separated into the Ecosystem's five main domains of:

      - Network & Protocol
      - Governance Models
      - Metaverse
      - Money Markets and
      - Products & Services. 

-   **Process DIP:** Process DIPs are used to create and define a specific recurring process that Dijets Governance will implement. This very document is a Process DIP.
-   **Subproposals (SPs):** A subproposal is an instance of a sub-process that has been defined by a specific DIP. Subproposals are named in the following format: DIP0-SP1 (where DIP0 is a Process DIP and DIP0-SP1 is a subproposal under that Process DIP)  
-   **Governance Arbiter(s):** Governance Arbiters are tasked with ensuring the smooth operation of the governance process. This involves a wide range of activities, anything from general administration to governance scheduling. Dijets Core Team assumes this role until the council elects a member following the submission of a DIP0m11 proposal.
-   **DIP Editor(s):** Enforce the administrative and editorial aspects of the overall DIPs process and program. The program will start out with an interim editor chosen by Dijets Core Team and the council can decide to elect others after the program's maturity.
    

---
### DIP0m2: Core Principles

 1. **Specificity:** A DIP needs to define and address a specific behaviour or single responsibility. DIPs with many different behaviours or responsibilities will not be allowed and must be split up into multiple DIPs.
	 - This mitigates the risk of having “fine print” or potential attacks hidden in large, complex technical DIPs.
 2. **Completeness:** A DIP or DIP Set is complete if it has all the necessary or appropriate parts that cover a whole behaviour and avoids being only a specific part of a greater whole.
	 - This is important for both understandability, readability and accessibility of DIPs.
3.  **Avoid overlap:** Multiple DIPs should not implement the same type of behaviour independently. For instance, there should not be two separate but interchangeable ways to onboard core personnel.
	- This way the primary and best-understood process for each particular behaviour will be fairly available to all the members equally, without risking having a knowledge gap that makes it possible for one member with better access to information to use different and potentially better processes
4. **Clarity:** A DIP must not have equally valid conflicting interpretations. DIP Authors and DIP Editors must strive to reduce ambiguity. A DIP must be as clear and easy to understand as possible.
	- Any ambiguous DIPs are likely to cause contention or confusion in the future. Making everything as clear as possible also aids readability and helps to mitigate security risks.
5. **Brevity:** A DIP must be as short as possible, including only that which is essential given the other core principles.
	- The shorter the DIPs are the more likely it is for people to read them in full. This also serves to reduce the surface area for hidden attacks.
	
---

### DIP0m3: The DIP Lifecycle

**The DIP Lifecycle Flow and DIP Statuses**

![DIPs Lifecycle](https://raw.githubusercontent.com/lasthyphen/truffle/develop/lifecycles.svg)

**1. Conception:** The lifecycle of a DIP begins when the DIP proposal is posted on [Dijets forum](https://forum.dijets.io). However, in order for a DIP to move to the next stage, it needs to satisfy the transition criteria (1) described below:

-   Submitted to the Dijets Forum under DIPs Section.
-   Submitted to the DIPs Github repository (DIP Editor can submit a pull request for this).
-   The format must follow the appropriate DIP Template for its type.
-   DIPs must be original or replacement versions of older DIPs (No repeats allowed).

**2. Approved by DIP Editor:** This phase of a DIP’s life cycle is when the DIP Editor confirms that the proposed DIP follows the correct structure and editorial criteria defined in the DIP template. If the criteria is not met, the DIP Editor will provide an explanation to the authoring member as to why and allow them to make the appropriate changes before reconsideration. If the criteria have been met, the DIP Editor performs the following actions:
    
-   The DIP is approved by a DIP Editor and is assigned a formal DIP number.
-   The PR is merged in by a DIP Editor.

**3. Request for Comments (RFC):** This phase is when a DIP goes through a formal review period, including feedback from the rest of the members, further drafting and additions.
     
 - The authoring member finalises changes to the DIP, based on other members feedback.

**4. Qualification: **The timeline for the RFC phase is defined by its and Frozen Period. In order to move to the next phase, it needs to satisfy the transition criteria listed below:

 - DIPs must not have had any changes for a minimum of 24 hours before they move to the next phase.

**5. Formal Submission (FS):** This phase is when the authoring members submit their complete DIP(s) to the Governance cycle by posting it to the formal submission forum category within the formal submission window of a governance cycle.

 - A DIP can be re-submitted to the formal submission process a maximum of 2 additional times (3 total), without having to go through phase 1-3 again, if it failed to pass due to legitimate external reasons (e.g. subject to the governance Arbiters judgement).
  
**6. Approved by the Governance Arbiter(s):** This phase is when the DIP must be formally approved by the Governance Arbiters.   

- Once approved by the Governance Arbiter, the DIP will be included in the inclusion poll of the Voting cycle.
- If the DIP is not approved by the Governance Arbiter, it may be reconsidered at a later date to enter the Voting cycle. 
    
**7. Voting Cycle:** This phase is when the DIP becomes officially available for voting. Determined by the DGC Members votes, the DIP is ultimately accepted or rejected.  

**7. Consensus Reached:** DGC Members votes are tallied and the results are published.

**9. Accepted/Rejected:** If accepted, the DIP is officially accepted and is given the accepted status and published to the official DIPs Directory. If the voting fails to pass before expiring, the DIP is rejected.
      

**Other DIP Statuses:**  


**Withdrawn:** when a DGC Member withdraws their DIP proposal, such as when:

 - A DIP may be withdrawn at any point before it enters the Voting cycle. 
 - Note that a withdrawn proposal can be taken over from the original DGC Member with a simple transition facilitated by a DIP Editor. If the original authoring member ceases to be available, the DIP Editor may proceed with the transfer of Authorship and the resultant HAL scores.

**Obsolete:** when a proposal is no longer used or is out of date, such as:
    
-   A DIP has been replaced by a newer, more updated DIP Proposal.
-   A DIP Author has abandoned the proposal and no other member has communicated willingness to take over the Authoring responsibility.
-   A DIP no longer makes sense to keep in consideration.
    
  
**DIP Status Change Process:**
    

DIP Editor reviews the DIPs directory to see if any of the DIPs meet the status criteria for a status change. If it does, the Editor will change the status of the DIP and the Author is notified along with the directory being updated. Status change request can also be made by the members to the DIP Editor.
    
---
### DIP0m4: DIP Modules and DIP Module Types


**DIP Modules**

- When necessary, DIPs can have multiple modules if it needs to contain multiple units of logic to satisfy completeness. A DIP can also have only one module.
- DIP modules are categorised by types, depending on what kind of logic they contain. DIP modules are named by their parent DIP. The abbreviation convention DIPXmY is used to refer to these modules ( exactly as seen in this very document with this module being DIP0m4).
- A DIP module has one type or no types. 


**Module Types**
    
-   **Process DIP Modules**  
      
    **Summary:** The purpose of a Process DIP module is to shape a specific process flow for Dijets to adopt and standardise with respect to how governance operates within the specified domain. This DIP module type helps streamline specific processes in a transparent, open and traceable manner. A Process DIP will provide a publicly documented scope of a proposed process framework as well as a detailed description of the subproposal structure.  
      
    **Template:** None required
      
    
-   **Subproposals**  
      
    **Summary:** A subproposal is an expedited process that is defined within a DIP to serve as a definition of how to run a given process within the DIPs framework. 

- Subproposals require a template, and are submitted using that template. Subproposals go through the DIPs process in the same way that DIPs do. The template, and frozen period for a set of subproposals are defined using a DIP module known as a Process module. Any DIP containing a Process Module gains the Process type.
- The subproposal naming convention is DIP**X**m**Y**-**SPZ** where X is the parent DIP containing a module and Y is the Module that contains the subproposal template. This is important in order to delineate between different types of subproposals defined within the same DIP under different Process modules.
   
![DIPs Lifecycle](https://raw.githubusercontent.com/lasthyphen/truffle/develop/conventions.svg)
  
---

### DIP0m5: DIP Replacement Process

A DIP can define one or more replacement targets in its preamble. If the DIP is given the accepted status, the replacement target DIPs then receive the status **Obsolete** and effectively become inactive. The replaced DIP will in its DIP document contain the number of the DIP that replaced it, and other DIPs that depend on the replaced DIP, will instead interact with the new DIP.

Dependencies in DIPs carry over, as a result a DIP with defined replacement targets must, in order to be valid, strictly adhere to dependency requirements and interface correctly with DIPs that depend on the replaced DIP.

---

### DIP0m6: Supporting Materials

DIPs can optionally refer to external materials. External materials must be added to the DIPs github in the same folder as the DIP which references them.

Externally referenced materials are not DIP content, and are not strictly part of the DIP once its Accepted unless explicitly stated otherwise.

---

### DIP0m7: DIP Templates

**General DIP Template**
- The General DIP Template should be used for DIPs whenever the proposal does not relate to Dijets Codebase or any of the smart contracts in Dijets Utility Chain. 
- The General DIP Template can be found at **[General-DIP-Template.md](https://github.com/lasthyphen/dips/blob/master/DIP0/General-DIP-Template.md)**. This template is considered officially published and ratified by the council once this DIP moves to Accepted status.

**Technical DIP Template**
- The Technical DIP Template should be used for DIPs whenever a DIP proposes changes to Dijets Codebase or any of the smart contract code hosted on Dijets Utility Chain.
- The Technical DIP Template can be found at **[Technical-DIP-Template.md](https://github.com/lasthyphen/dips/blob/master/DIP0/Technical-DIP-Template.md)**. This template is considered officially published and ratified by the council once this DIP moves to Accepted status.
---    

### DIP0m8: DIP0 Core Personnel Role Dependencies


The DIPs Framework depends on the following Core Personnel Roles & their responsibilities:
-   **DIP Editor:** Enforces the administrative and editorial aspects of the overall DIPs process and program.
-   **Specific authority of the DIP Editor within the DIPs framework:**
	-   The DIP Editor controls phase 2 of the DIP lifecycle and can assign DIP numbers
	-   The DIP Editor is an admin on the DIPs Github repository
	-   The DIP Editor is a moderator on DIPs forum with a badge assigned for an Editor role
	-   The DIP Editor is responsible for updating the status of DIPs, as described in DIP0m3 “The DIP Lifecycle”.
-   **Governance Arbiter:** Operates voting frontend, runs governance meetings and accepts DIPs that are ready to be included in the Governance Cycle and thus, voted on.
-   **Specific authority of the Governance Arbiter in DIP0 processes:**

	-   Consensus from all governance Arbiters controls phase 6 of the DIP lifecycle, which allows them to, with consensus, add valid DIPs to the inclusion poll of the next governance cycle, moving them from phase 5 (formal submission) to phase 7 (voting cycle).
    -   At the start of the program the Arbiters role will be assumed by the Core Team until the council elects personnel to the role.

Personnel may be added to these roles using a DIP0m11 sub-proposal.

**Example: **
- John Smith gets added to the role of a DIP Editor via DIP0m11SP1
- Jane Doe gets added to the role of a DIP Editor via DIP0m11SP2

Personnel may be removed from these roles using a DIP0m12 sub-proposal.

**Example: **
- John Smith gets removed frpm the role of a DIP Editor via DIP0m12SP1
- Jane Doe gets removed from the role of a Arbiter via DIP0m12SP2

---

### DIP0m9: DIP Editor Role  


**Responsibilities**

The DIP Editor enforces the administrative and editorial aspects of the overall DIPs process and framework. This includes:
-   Maintain and manage dips.dijets.io
-   Provide feedback and have discussions in the DIP section of forum.dijets.io (ex: helping vet proposal ideas).
-   DIPs processing.
-   Management and organisation of DIPs and Subproposal Preambles. 
-   Onboard and vet new DIP Editors when required
-   Enforcing the proper DIPs process with responsibilities such as:
    -   Confirm that the title accurately describes the content of the proposal.
    -   Assign formal number labels to the proposed DIPs.
    -   Change DIP statuses.
    -   Correct DIP domain and index categories and placement.
    -   Correspond with the DIP authoring DGC Member.
    -   Review the DIP for obvious issues and defects (completeness, format, spelling, grammar, structure) and that it follows the template guide. DIP Editors are allowed to correct problems themselves, but are not required to do so and can send comments to the authoring members to improve it themselves.
    -   Work and communicate with Governance Arbiters on coordinating governance and mandate votes in relation to DIPs and the voting cycles.

**Selection Criteria**
    
DGC Members should note the following criteria when selecting a DIP Editor:

-   A complete understanding of the DIPs Framework
-   The Core Team will provide all the assistance required by DIP Editor once onboarded but prospective candidates must be fully familiar with Dijets Ecosystem, DIPs framework and how it operates.
-   Dijets Council can elect a DIP Editor amongst themselves or decide on electing individuals from the wider community after the governance programs maturity. Selecting individuals for an Editor role could depend upon some of the following criterias:
    -   Past forum posts
    -   Attendance and general contribution in discussions on Qowalts and Forum.
    -   Articles written about Dijets Ecosystem and/or its domains.
    -   Guides, videos or informational literature about Dijets Ecosystem and/or its governance.
-   Technical Familiarity with the inner workings of Dijets Protocol (bonus but not a requirement)
-   Experience with Github and its basic features
    -   Merging, editing, closing Pull Requests
    -   Addressing issues
    -   Adding tags / labels
-   Experience with Markdown language
    -   DIPs are written in Markdown, so editors will need to be familiar with the language. An online editing tool [Marko](https://marko.dijets.io) is available to help with drafting proposals in markdown.

**Addition**

Once a person has been onboarded to the DIP Editor role, they will be invited to join Dijets Inc. organisation on Github and subscribe to watching the DIP repository. They will also become a Moderator on Dijets Forum and Qowalts. Much of the correspondence regarding DIPs will be handled through GitHub as well as through Qowalts and Dijets Forum.


**Removal**

A DIP Editor should be considered for removal if they are:
    
-   Absent from their duties for a prolonged period
-   Inadequately performing their defined duties
-   Displaying biased or malicious behaviour
-   Expressing unwillingness to continue in their role.

The removal process begins once the council has agreed on the reasoning for removal. This process must be communicated publicly via the forums in order to provide complete transparency. **The DIP Editor will then have the assigned authorities, HAL scores, incentives removed from their profile:**

---

### DIP0m10: Governance Arbiter Role

**Responsibilities**

The Governance Arbiter's responsibilities are as follows:

Core Responsibilities
- Responsible for ensuring the health and integrity of communication channels used across Dijets Governance. These tasks include moderation duties, establishing processes and social norms, and defending the channels from trolling and Sybil attacks.
- Required to remain neutral and objective on issues outside the governance domain and focus on policy, procedure and facilitation.
- Required to schedule, run and moderate governance meetings from a position of neutrality.
- Required to manage and run governance processes as directed by relevant Accepted DIPs or DIP sets. 
- Required to create on-chain polls on the Dijets Voting Portal as directed by governance processes defined in relevant Accepted DIPs or DIP sets.
- Should aim to foster a culture of openness, receptiveness and reasoned discussion within the community.


Encouraging Participation
- Should work to maintain and encourage healthy debate and discussion.
- Should ensure that the upcoming governance schedule is well communicated to all members at least a week in advance.
- Should aim to promote and increase engagement by all members in the governance process. 
- Should ensure that the community and public understand the general level of decorum and civility expected by the participants of all communication channels.

Improving Efficiency

- Should ensure that appropriate consensus gathering methods are enacted once the discussion and debate reaches its natural conclusion.
- Should support and facilitate communications between DGC Members and any other stake holders where required.
- Should look for opportunities to streamline the governance process and models without sacrificing their underlying integrity. 

Cohesion and Morale
- Responsible for raising Dijets Council governance issues to the Core Team and ensuring appropriate follow up for the council.
- Should help to build and maintain morale and engagement among members of the council.
- Should encourage the council members to come to consensus over the least objectionable option(s) rather than treating decision-making as a competition where a subset with a differing opinion feel disappointed in the outcome. 
- Should work to bring the governance council together on divisive topics and to prevent political polarisation and demagoguery. 

**Selection Criteria**
    
The following criteria should be used when evaluating an individual for the role of Governance Arbiter:

- Should have a complete understanding of the DIPs Framework and content, especially in relation to core governance DIPs.
- Required to be a community member for some time. This can be shown through various proof of participation methods, such as:
	- Past forum posts
	- Attendance of community and governance calls
	- Input into issues of governance in any communications venue.
- Core team will provide all the assistance required once the personnel has onboarded but the candidate must be familiar with the roles and responsibilities of Arbiters.
- Should have familiarity with the technical inner workings of Dijets Ecosystem (not a requirements but bonus)
- Should be confident and must have experience engaging DGC Members and the community in all the different communication channels including qowalts rooms, forum and video conference calls.
- Should have an interest in autonomous organisations, governance mechanisms being used currently and historically across the world.

**Removal**

A Governance Arbiter should be considered for removal if they are:
-   Inadequately performing their defined duties.
-   Absent from their duties for a prolonged period.
-   Displaying biased or malicious behaviour.
-   Expressing unwillingness to continue in their role.

---

### DIP0m11: Core Personnel Onboarding

DIP0m11 is a Process DIP module that allows the onboarding of core personnel using a subproposal. DIP0m11 subproposals must have a parameter clearly stating the **Frozen Period** requirement which ensures no last minute changes are brought about to a process module about to be implemented such as an individual onboarding as an Editor or Arbiter:
-   **Frozen Period**: 24 hours

DIP0m11 subproposals must use the template located at  **[DIP0m11-Subproposal-Template.md](https://github.com/lasthyphen/dips/blob/master/DIP0/DIP0c11-Subproposals/DIP0c11-SP1.md)**. This template is officially considered as implemented once this DIP moves to Accepted status.

---

### DIP0m12: Core Personnel Offboarding

DIP0m12 is a Process DIP module that allows the removal of core personnel using a subproposal. DIP0m12 subproposals have the following parameters:

-   **Frozen Period**: 0 hours

DIP0m12 subproposals must use the template located at  **[DIP0m12-Subproposal-Template.md](https://github.com/lasthyphen/dips/blob/master/DIP0/DIP0c11-Subproposals/DIP0c12-SP1.md)**. This template is considered ratified once this DIP moves to Accepted status.

---
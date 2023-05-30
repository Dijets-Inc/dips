# DIP2: DIPs Amendment and Removal Process

## Preamble

```
DIP#: 2
Title: Amendment and Removal process for accepted DIPs
Author(s): Saleem Fareed (@Dijets-Inc)
Domain: Governance
Type: Process
Status: Accepted
Date Proposed: 2023-05-25
Date Ratified: 2023-05-25
Dependencies: n/a
Replaces: n/a
Notes: 

```

## References

**[DIP2m2-Subproposal-Template.md](DIP2m2-Subproposal-Template.md)**

**[DIP2m3-Subproposal-Template.md](DIP2m3-Subproposal-Template.md)**

## Sentence Summary

DIP2 defines the standard processes for any amendments and removal of accepted DIPs.

## Paragraph Summary

The Amendment and Removal Process DIP outlines the process for making changes to the DIPs. Rather than having two separate DIPs (one for amendments and one for removals) DIP2 consists of two key process modules. Wherein one module deals with the Removal pocess of already accepted DIPs, and the second module deals with amendments to current DIPs.

## Modules Summary

**DIP2m1: Purpose Description**
Suggests the purpose of the amendment and removal processes and possible reasons for using each process.

**DIP2m2: Amendment Process for DIPs**
The process module which defines a method and template for amendment to an already accepted DIP.

**DIP2m3: DIP Removal Process**
The process module which defines a method and template for the removal of an accepted DIP.

## Motivation

The main motivation behind this proposal is to avoid scenarios where each minor or relatively superficial change to a DIP ends up making it obsolete or replaced with a newly edited DIP without having outlined the process behind making said changes. Each DIP in Dijets governance goes through a lengthy and strictly standardised lifecycle from its inception to implementation. The amendment and removals process for these DIPs must also be upheld with same standards. Each edit, small or large must be recorded with canonical versions and its purpose descriptions. Additionally, this DIP defines the process for the removal of DIPs that have become obsolete due to a change in direction or a breaking change in code.

## Specification / Proposal Details

### DIP2m1: Purpose Description

**Amendments**
DIP Amendments that preserve the DIP number can be performed as long as there are no changes to the logic of the DIP or to the DIP's external output dependencies. They should only be used when minor changes are required.

Amendments to DIPs will follow a general set of rules outlined in DIP2m2. Changes to newer DIPs for any given domain will always take precedence over their older counterparts.

Amendments to multiple DIPs are allowed to be submitted as a single proposal if the changes are linked in some way like being part of a larger change that impacts multiple DIPs.

**Validity**
The validity of DIP Amendments is up to the proposing and voting DGC members but possible reasons for amendments could be (but are not limited to):

- Clarifications/Rewrites
- Standard format change
- Typos

**Removals**

DIP2 also enables the removal of one or multiple DIPs that become obsolete. If there are other DIPs that depend on a DIP that is being removed, they must also be removed or amended in the same governance cycle, otherwise the removal will be invalid.

Removal of multiple DIPs are allowed to be submitted as a single proposal if the changes are linked in some way like being part of a blanket change that impacts multiple DIPs.

### DIP2m2: Amendment Process for DIPs

DIP2m2 is a Process DIP component that regulates the amendment of one or multiple Accepted DIPs.

Amendment Subproposals must be submitted to a minimum of one week's feedback period on Dijets Forum where initially all the members and later the community should be able to table questions and offer their comments. This requirement is parameterised in the template as the **Default Feedback Period**. This is followed by a 48 hour frozen period, during which the Amendment proposal cannot be changed any more.

All DIP2m2 subproposals must use the template located at **[DIP2m2-Subproposal-Template.md](DIP2m2-Subproposal-Template.md)**.

### DIP2m3: DIP Removal Process

DIP2m3 is a Process DIP component that allows the removal of an Accepted DIP or a group of linked DIPs

DIP2m3 subproposals must use the template located at **[DIP2m3-Subproposal-Template.md](DIP2m3-Subproposal-Template.md)**. 

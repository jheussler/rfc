# ObjectivePHP RFC process

## What is an RFC?

RFC stands for "Request for comments". They are documents stating any improvement or new feature one would like to get in ObjectivePHP. Once the idea is exposed, others are invited to discuss this idea. Finally, the RFC will be - or not - validated and implemented into an upcoming version of the framework (or concerned component).

## Who can submit an RFC for ObjectivePHP?

Anyone, whether they are contributor or not, are likely to submit an RFC. Likewise, anyone is welcome to enter the debate regarding RFC proposals.

## Who will vote for RFC proposals?

Core contributors only are allowed to vote. To become part of the voters... just contribute to ObjectivePHP's code! 

## How to submit an RFC?

RFCs are created, discussed and voted as issues in this repository. 

To ease writing and reading of proposals, we strongly suggest you to create your RFC using [rfc-template.md](our template).

## RFCs lifecycle

RFCs lifecycle is represented using labels on issues. Here are the different labels, and their meaning regarding the lifecycle:

Under author responsability:
 - when just created, and before starting debating, RFCs are in "DRAFT" state
 - when the author wants to start receiving comments and discussing their proposal, RFCs are in "UNDER DISCUSSION" state
 
Under core team responsability:
 - when discussions are over, and no show stopper has raised, RFCs are in "VOTING" state
 - depending on the vote result, RFCs can be either in "ACCEPTED" or "REJECTED" state
 
 ## Voting phase
 
 Every voter will be expected to vote within 10 days once the RFC turned to "VOTING" state. A negative vote will need to be explained to be taken in account ("I don't like the author" or "I don't understand the point" will **not** be considered as an explanation for a negative vote!).
 
 ## Implentation
 
 If an RFC is accepted by the core team, it will be numbered and copied to a dedicated .md file in a dedicated subfolder named after the RFC. Then, depending on the nature of the RFC (improvement or new component), a new branch on an existing repository or a new repository will be created to start woking on it.
 
 The core team will assign developers to the issues created to reflect the different tasks needed in order to implement the RFC.
 
 Eventually, this new code will be merged and a tag will be created. Before that anyway, a test team, also designated by the core team, will have to validate the developments.

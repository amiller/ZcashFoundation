Governance proposal for Zcash Foundation
==

It’s time for the Zcash Foundation to conduct its first election. After the election, we’d like to continue in mostly the same way we’ve already been operating. (See Josh’s vision document). 
The board of directors is important since we are officially the root authorities in control of the organization. A small board that is motivated and engaged is better than one with a diffuse sense of responsibility. However, we’d also like to be held publicly accountable in as a broad sense as we can.

To begin with, we’d like to gradually increase the board size. We’re planning to increase the board size to 7, with 2 new board seats to fill via an election.

Furthermore, the existing board members have all expressed a preference of being “up for reelection.” While we’re each willing to continue in this role, it’s only worth it if the community actively wants us to stay. In our [founding public statement](https://z.cash.foundation//blog/hello-world/), we described ourselves as a “bootstrap board.”

What should this election look like? Who are the “stakeholders” in our organization? Some approaches include polling the miners, or polling stakeholders. Each of these is appealing because it’s quantitative, and has a technical description. They’re examples of _“On Chain governance”._ We have issues for discussing these in our public github repository. As a non-profit, we must operate inline with a broad public mission, rather than to enrich a few. It’s difficult to pick a mechanism that gives a fair but effective representation and cannot be gamed.

Community Approval Panel
--
Our approach will be to appoint a “Community Approval Panel,” consisting of a broad collection of people who have contributed in some way to the Zcash community via some public & visible presence.

  - Can we make it broad representation (e.g. not all US?)
  - Not stacked with insiders to the Zcash Foundation directors, or to the Zcash Company
	- The selection outcome is transparent.
	- Anticipate it is around ~200 people.

The Foundation will then contact members of the Panel and,
  - solicit their communication preferences (e.g., Twitter, GPG signed or not, etc.)
  - get their permission to acknowledge them in our transparent list of assented voters
  - encourage them to acknowledge their intent to participate via posting on their medium of choice

Example:
	```
  @socrates1024 says: I’m going to participate as an approval voter of the Zcash Foundation. My name’s on their spreadsheet here: <link to z.cash.foundation/election-2018-Q12>, with my permission. Correspondence as part of that will be GPG signed by me. I’ll also tweet about it after I vote.```

We’ll have an informal process for suggesting and adding new Panel members we’ve missed. Executive Director authorized to manage this list.

Conducting the first board election using the Community Approval Panel
--
We’ll conduct an election of board members using the Community Approval Panel. The election will be conducted ahead of Zcon0 if possible, remotely, although an in-person component will be included too. We’ll collect votes online, via the communication method preferred by each Panel member. 

Our primary design goals will be to ensure that votes are not double counted or suppressed. We’ll achieve this through transparency. Votes will not be secret. Instead we’ll publish and archive all the votes, so that missing or changed votes would be easy to detect. 
We’d love to develop the technical capacity to have private voting in the future, probably using the Zcash protocol itself. https://eprint.iacr.org/2017/585.pdf 

Due to our bylaws, decisions must ultimately be made by majority vote of board members. Hence we cannot declare this election to be binding, instead the outcome of the election will have to be ratified by the board members before taking effect.

Three proposals for the “Community Approval Panel” to discuss and approve/reject by vote
----

1. Approval of the process: approve/reject
If this does not pass, we should throw an exception and end this process early.

2. Existing board member Re-election:

	- Matt Green: 		approve/reject
	- Naval Ravikant: 	approve/reject
	- Andrew Miller: 	approve/reject
	- Yan Zhu: 		approve/reject
	- Peter Van Valkenburgh: approve/reject

If a majority of board members are rejected, this would seem to suggest a vote of no confidence in the board overall, and hence should also be considered an exception. Proposed way to handle the exception: in the interest of stability and continuity, in this case we should vacate at most 2 seats.

3. Electing new board members

This will use the “Satisfaction Approval Voting” voting method.

Suppose we have N candidates, and k seats to fill, 
(where k is between 2 and 4 depending on outcome of Step 2.)

Each voter sees a list of checkboxes next to names:

- Candidate 1:  	approve/reject (or number between 0 and 1)
- Candidate 2: 	approve/reject (or number between 0 and 1)

...

- Candidate N: 	approve/reject (or number between 0 and 1)

The k candidates with the most total votes are the winners. 
The votes are weighted so that every voter contributes 1.0 total weight. If you pick two candidates, your vote counts 0.5 for each of them, 0 for the rest. If you pick 5 candidates, your vote counts 0.2 for each of them.
	

https://en.wikipedia.org/wiki/Satisfaction_approval_voting

Nominating candidates:  Candidates for board election can nominate themselves along with a “running for election” notice to our mailing list. Nominations can be included via alternative media, as long as they can be linked to from our mailing list and reasonably archived. 

4. Other proposals to vote on as needed…

Immediate next steps and management plan:

- Post informal draft of this plan to github issue for public discussion
- Draft an initial list of Community Approval Panel members
- Plan on collection mechanisms, how much effort is needed, steps to archive and secure data
- Get board approval to proceed based on feedback
- Announce approved plan Foundation blogpost
- Contact appointees and solicit their communication preferences, and their agreement or declined to participate
- ...




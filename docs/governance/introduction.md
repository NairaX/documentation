title: Blocknet Superblock Governance
description: Blocknet is a self-funded and community-governed project through a 2-part governing system consisting of Service Nodes and Superblocks.


# Introduction
[Blocknet](/project/introduction) is a self-funded and community-governed project. Decentralization defines the template for group decision-making and is self-managed through a 2-part governing system consisting of Service Nodes and Superblocks. There is also additional funding aside from the Superblock, which is explained under [Community Funds](#community-funds).

---

## Superblock
Superblocks are special blocks that occur every 43,200 blocks, or approximately once each month. On each Superblock, **up to a maximum of 40,000 [BLOCK](/blockchain/introduction)** can be minted to fund the project. It's important to note that only the total amount of BLOCK requested by *passing* proposals will be minted, so **if no proposals pass then no BLOCK will be minted in the Superblock**. 

To request funding from a Superblock, a proposal must be submitted to the network prior to the Superblock. Service Node operators then have the opportunity to review these proposals and [vote on each proposal](/governance/proposal-voting) with either a ‘yes’ or ‘no’ to approve or decline funding. 

---

#### Passing Criteria
For a proposal to pass and receive funding:

* The amount requested must be 40,000 BLOCK or less.
* Votes in favor must be greater than votes against by at least 10% of the total number of Service Nodes.
* The proposals that pass are sorted in a descending order list by the sum of yes votes minus no votes.
* If multiple proposals have an equal sum of yes votes minus no votes, those are sorted randomly.
* If there are not enough funds remaining in the Superblock for a proposal to be paid out, it is skipped (not paid out), and the next proposal in the passing list is checked for qualification.
* Multi-month proposals are voted on each month and are treated in the same manner as normal proposals in the ordered list.

Voting Turnout	| Yays Required | Max Nays Allowed
----------------|---------------|-----------------
100% 			| 55% 			| 45%
80% 			| 56.25% 		| 43.75%
40% 			| 62.5% 		| 37.5%
20% 			| 75% 			| 25%
10% 			| 100% 			| 0%
<10% 			| cannot pass 	| cannot pass

---

#### Superblock Value Calculator

--8<-- "superblock-value-calculator.md"

---

#### Superblock Dates

--8<-- "superblock-dates.md"


---

## Community Funds
In addition to Superblocks, there are also Community Funds. These funds were created after a [staking protocol exploit](https://steemit.com/blocknet/@theblocknet/stake-bug-resolved-announcing-the-blocknet-bug-bounty) was successfully stopped and [it was voted on](http://blocknetdx.forumotion.com/t10-community-fund-proposals-redeem-fund-allocations) by the community to create various funds. [An additional proposal](/proposals/project-funding) was voted on (and passed) to also add the retrieved exploited funds to the Community Funds instead of those funds being burns, as was originally planned. 


The current balance and use of these funds can be tracked in the [Blocknet's Financial Tracker](https://docs.google.com/spreadsheets/d/1xFm5LJsRNN62-9XZFqfDckUt2x8ps3pUOBISUxNQYpc/). Usage of these funds go through a 3-of-5 approval process by the following fund approvers: 

* Dan Metcalf (@atcsecure)
* Arlyn Culwick (@synchist)
* Michael Madgett (@michael)
* Jeff Madgett (@86b)
* Hanni Abu (@hanniabu)
















<script type="text/javascript">
// read instructions for related links in ../snippets/extras.md
var relatedLinks = [];
</script>

--8<-- "extras.md"






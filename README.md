![](https://github.com/lunardao/dao/blob/master/moon3.gif)

# LunarDAO Architecture

**THIS DOCUMENT IS A PROPOSAL AND REFERENCE FOR THE COMMUNITY FEEDBACK AND [DISCUSSION](https://forum.lunardao.net/t/tokenomics-lunar-vox/89/45)!**

**Resources & References**

* [LunarDAO architecture discussion](https://forum.lunardao.net/t/tokenomics-lunar-vox/89/45)
* [MolochDAO V2](https://github.com/MolochVentures/moloch)
* [Metacartel Ventures whitepaper](https://github.com/metacartel/MCV/blob/master/MCV-Whitepaper.md#asset-management)
* [Moloch Baal - V3](https://github.com/Moloch-Mystics/Baal)
* [DaoHaus](https://daohaus.club/docs/handbook/)
* [Summon a DAO](https://summon.daohaus.fun/)
* [LunarDAO tokenomics V1](https://wiki.lunardao.net/tokens.html) - this model will NOT be used, however this report refers to it in some parts
* [LunarDAO Manifesto](https://wiki.lunardao.net/)
* [LunarDAO: Why are we anonymous](https://lunardao.net/why-anon.html)
* [LunarDAO Multi-sig Anouncement](https://lunardao.net/sentinel-committee-announcement.html)


## Introduction

[LunarDAO](https://lunardao.net/) aims to function as an **INVESTMENT FUND INTO PRIVACY PROJECTS & ANONYMITY TOOLING**, a squad wealth based DAO spreading [Lunarpunk narrative](https://wiki.lunardao.net/) & philosophy. The DAO is creating possibilities for education by building [research](https://wiki.lunardao.net/anoma.html)/[wiki](https://wiki.lunardao.net/intro.html) and supporting [educational](https://wiki.lunardao.net/academy_intro.html) processes where people master the skills in their field and bring value back to the ecosystem.

Based on the discussions with the allies & the community, the most feasible way for the LunarDAO architecture to meet its aim, seems to be [MolochDAO V3](https://github.com/Moloch-Mystics/Baal). The contracts have much more optionality on both the initial setup and throughout the DAO life time in comparison to Moloch V2. V3 is also easier to set up and launch, possibly using existing UI and implement changes on the fly, in a more democratic manner (based on community discussions and squad vote).

## Terminology

### Governance

* **Community:** Anyone engaging on the forum & chats. To be a member of the community does NOT grant voting/governance power.
* **Squad:** DAO members holding shares, voting power.
* **Sentinels:** Eight guardians ([multi-sig](https://lunardao.net/sentinel-committee-announcement.html)) of the DAO treasury.
* **Stewards:** [Anonymous](https://lunardao.net/why-anon.html) core-team/founders of the DAO, securing operations (can be exchanged, archived, scaled up).
* **Committees:** Working groups with a specific focus (research, media, education).

### Threshold protocols

**Note:** ***In all cases DAO participants/members are encouraged to setup [anonymized wallets](https://wiki.lunardao.net/anonymizing_assets.html) before joining the DAO!***

The option on restricted governance access/ Squad membership refers to terms *"Squad invites"* and *"Minimal Tribute"* as possible threshold protocols:

**Squad Invites**

* Every Squad member can add a new Squad member (can be combined with a minimal tribute option).
* The number of invites per Squad member is limited (or limited per time period) -> incentive to chose wisely.
* Adding a new member can be instant or not (ie. one week), which allows others to propose to GuildKick the host or a RageQuit themselves, if they disagree with adding the new member. 

**Minimum Tribute**

* A size of a minimum tribute is defined by the Squad.
* Every new member to join the Squad must escrow a minimum tribute to the DAO treasury.
* When a new member joins the DAO Squad, the tribute will be exchanged for equal amount of shares assigned to the new member.

The above mentioned thresholds can be further developed and combined together.

## The Architecture Proposal

### General

***Every point marked with \* symbol is to be further evaluated and decided upon by the initial LunarDAO Squad formed by all participants of the first launch, also referred to as a Genesis event***.

**Design**

- Multisig Gnosis Safe and Moloch v3 on chain execution are compatible -> the DAO can be setup on top of the [Gnosis safe multisig](https://lunardao.net/sentinel-committee-announcement.html). Start with the trusted (and more secure) setup and plan a roadmap milestone to discuss, propose (LIP) and vote on a multi-sig removal in a forseeable future -> full trustless setup. \*
- RageQuit & GuildKick is included in this design.
- Setup minimum retention 25% - if 75% of shares are ragequitted, the proposal will fail automatically as the original circumstances when the proposal was submitted, including access to funds, changes dramatically.\*
- LunarDAO is launched on existing [contracts](https://github.com/Moloch-Mystics/Baal) and customized version of the [UI by DAOhaus](https://summon.daohaus.fun/). 
- Further upgrades and customization will be discussed in the community and voted upon.\*

**Launch/ Genesis Event** 

- LunarDAO launch is permissionless in the sense that anyone can join/invest.
- However, it is only possible to join during period of the fundraising event.
- The initial fundraising event is the launch of LunarDAO and will be opened for a period of two weeks. 
- Proposal is to have 4 fundraising events in the first year\*. The initial Squad (formed by all participants of the first event) will evaluate and democratically decide if, how and when to open future fundraising events.
- A minimum tribute is a set up as a low threshold for entry. It aligns well with Moloch v3 architecture.\*  
- The architecture puts an emphasis on anonymity combined with inclusivity for the initial Squad formation, both which is essential for a privacy oriented investment fund which aims to develop infrastructure for parallel economy.

**Governance: Community & Squad**

- LunarDAO Community is anyone engaging on the forum & chats. To be a member of the community does NOT grant voting/governance power.\*  
- LunarDAO Squad member is any community member owning at least one $VOX (Share). LunarDAO Squad has governance power.\* 
- Ragequit based design, with no fee.
- GuildKick included (malicious actors can be proposed to be kicked out of the DAO - force a RageQuit).


**Tokenomics 101**
 
- Shares are represented by $VOX. 
    - $VOX is LunarDAO governance token. 
    - $VOX is a symbol representing Shares (1 $VOX = 1 Share). 
    - An account bound, non-transferable token. 
    - $VOX-loot represents loot.\*  
- $LUNAR token is not introduced at launch. It will be designed and introduced as part of the roadmap.\*  

**Fundraising Events**

- A fundraising event is proposed to take place every third month in the first year.\* There will only be raise connected to a concrete investment proposal. If there are still funds from previous raise, the number of fundraising events will be adjusted to this reality.  
- The fundraising is open two weeks the first time, and thereafter a week on each occation.\*  
- During this time anyone can become a Squad member by buying $VOX.\*  
- Minimum tribute is 1 ETH\*
    - 1 ETH = 100 $VOX (shares)
    - Minimum denomination is 0.1 ETH = 10 $VOX (shares)  

**LunarDAO Management, Admin, Dev & Research**

* LunarDAO has 6 [Stewards](https://wiki.lunardao.net/governance.html#stewards) (core-team members, founders) at the time of launch.
* Several externals are supporting with design, administration, legal questions, web3 development and translations.
* A management/admin fee of 0.5% is sent to core-team multi-sig wallet (ETH: 0xAb501a8Eb58c9780eb04D683feB504fcE391A2DD). This fee is calculated from:
    a) The initial tribute of every new member. 
    b) Once every three months from the treasury. 
        * Alternatively this can be done with every deal/investment execution instead of every three months.
* For extra costs/expenses such as dev, research, education etc a LIP is submitted and voted upon.

### Fund Management & Governance

LunarDAO makes investments in privacy projects through the governance process, which includes research, discussion, proposals and voting. The Squad allocates funds to selected teams while building a treasury of its investments. There are several ways how to approach treasury management and govern the funds. For easier understanding we summarized them under two main types: ***Portfolio*** (or Investment club) and ***Syndicate***. These two approaches are explained with examples below. The following table may help for simplier understanding of the concepts.

*Table 1: Fundamental approaches: Portfolio & Syndicate*

| **FUND MANAGEMENT – Design Essentials**                          | **Portfolio/ investment club**                                                                                                                                                                                                                                                                                                                                               | **Syndicate**                                                                                                                                                                                                                                                                                                                              |
|:------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Description:                                                | All the assets in the treasury are pooled together as a common portfolio. Each share despite the time of purchase represents the same value (1 share = all assets net value / # shares ). The Squad members can start different sub-DAOs or specific guilds just like in the “Syndicate” option. The Squad decides how often and how open the future raising events will be. | Each investment or raising cycle is treated as a separated entity. New members don’t have exposure to the old investments. The investments or raising cycles can be separated into sub-DAOs or guilds or alternatively tokens representing the past investments are minted based on on-chain snapshot taken at the time of the investment. |
| Exposure to the past investments:                           | Yes. New members are exposed to the old investments.                                                                                                                                                                                                                                                                                                                         | No, new members aren’t part of the portfolio of the past investments.                                                                                                                                                                                                                                                                      |
| Aim of LunarDAO launch raise size (minimum, aim, maximum):  | 700 ETH, 7000 ETH, 15000 ETH (if hit, the smart contract expires).                                                                                                                                                                                                                                                                                                            | *As Portfolio*                                                                                                                                                                                                                                                                        |
| How often LunarDAO runs a raise event:                      | Proposal for default: 4x the first year. An investment deal is expected to happen before any next raise. After the initial one, the formed Squad can propose to cap (# ETH) he next raise or make a sub-DAO and turn into the syndicate option. Every sub-DAO then makes autonomus decisions on this question.                                                                                                                                                                                                                                                     | Proposal 4x the first year. Before any next raising event a new separated guild/sub-DAO is opened for the new members who will manage funds separately from the others. Every sub-DAO then makes autonomus decisions and can futher continue as *portfolio* style managed DAO.                                                                                                                                                                    |
| How often the LunarDAO opens for new Squad members:         | Every raising event.                                                                                                                                                                                                                                                                                                                                                          | *As Portfolio*                                                                                                                                                                                                                                                                                                                       |
| Condition to join LunarDAO Squad at launch:                 | Permissionless with a minimum tribute.                                                                                                                                                                                                                                                                                                                                        | *As Portfolio*                                                                                                                                                                                                                                                                                                     |
| Condition to join LunarDAO Squad in the future:             | The initial Squad will decide whether to keep the permissionless setup, introduce invites, raise the minimum tribute bar, limit the max Squad members size etc.                                                                                                                                                                                                              | Every new guild or sub-DAO is permissionless, the Squad decides how often to run raising events and open new guild/ sub-DAO.                                                                                                                                                                                                                |
| Minimum tribute on launch / future raise events:            | 1 ETH on launch/ further raises to be decided.                                                                                                                                                                                                                                                                                                                                | *As Portfolio*                                                                                                                                                                                                                                                                                            |
| On-boarding contract design:                                | Contract is opened for a limited period and mints new Shares equal to new Squad member tribute. It expires after maximum raise is met or based on pre-defined period. Every Share for every Squad member has an equal entry price.                                                                                                                                            | *As Portfolio*                                                                                                         |
| On-boarding contract expiry period (1st one/ any next one): | 2 weeks the first raise/ 1 week any other one.                                                                                                                                                                                                                                                                                                                                | 2 weeks the initial/ the future ones to be decided.                                                                                                                                                                                                                                                                                         |
| Share price on launch:                                      | 1 ETH ( + management fee) = 100 SHARES.                                                                                                                                                                                                                                                                                                                                       | *As Portfolio*                                                                                                                                                                                                                                                                                                   |
| Minimum Shares denomination (above minimum tribute):        | 10 Shares (denominations of 0.1ETH)%.                                                                                                                                                                                                                                                                                                                                         | *As Portfolio*                                                                                                                                                                                                                                                                                                      |
| Management/ admin fee for new members:                      | 0.50%                                                                                                                                                                                                                                                                                                                                                                        | *As Portfolio*                                                                                                                                                                                                                                                                                                                                     |
| Continuous management/ admin fee:                           | 0.5% once per quarter or alternatively 0.5% every investment execution.                                                                                                                                                                                                                                                                                                       | *As Portfolio*                                                                                                                                                                                                                                                                     |
| Shares price bonding curve:                                 | + 10% each next funding cycle.                                                                                                                                                                                                                                                                                                                                                | As the shares don’t represent the past investments, only the net value of the new treasury, no bonding curve.                                                                                                                                                                                                                               |

*Table 2: Tokenomics - Portfolio & Syndicate*

| **TOKENOMICS**                          | **Portfolio/ investment club**                                                                                                                                                                                                                                                                                                                                               | **Syndicate**                                                                                                                                                                                                                                                                                                                              |
|:------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| $VOX (shares) token:                                        | $VOX is LunarDAO governance token. A symbol representing Shares (1 $VOX = 1 Share). An account bound, non-transferable token.                                                                                                                                                                                                                                                 | $VOX is LunarDAO governace token. A symbol representing Shares (1 $VOX = 1 Share). An account bound non-transferable token. In the syndicate case an index for easier navigation needs to be introduced as every guild/ sub-DAO shares represent different value.                                                                          |
| $VOX price:                                                 | At launch the price is 1 ETH (+ management fee) = 100 $VOX.                                                                                                                                                                                                                                                                                                                  | *As Portfolio*                                                                                                                                                                                                                                                                                |
| $VOX value calculation:                                     | 1 $VOX = LunarDAO net value / # of $VOX (shares).                                                                                                                                                                                                                                                                                                                             | *As Portfolio*                                                                                                                                                                                                                                                                                |
| Loot:                                                       | Loot = owners $VOX value in the time of RageQuit. Including owners access to the future allocations if the member was part of the Squad during the investment.                                                                                                                                                                                                               | *As Portfolio*                                                                                                                                                 |
| $LUNAR token:                                               | No. Start without a community token and introduce it later.                                                                                                                                                                                                                                                                                                                   | *As Portfolio*                                                                                                                                                                                                                                                                                 |

*Table 3: Governance - Portfolio & Syndicate*

| **GOVERNANCE**                          | **Portfolio/ investment club**                                                                                                                                                                                                                                                                                                                                               | **Syndicate**                                                                                                                                                                                                                                                                                                                              |
|:------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Squad membership:                                           | Everyone owning at least 1 $VOX is a Squad member. Squad members have voting power.                                                                                                                                                                                                                                                                                           | Everyone owning at least 1 $VOX is a Squad member, however members can vote on treasury decisions only in the guilds/ sub-DAOs in which their $VOX (shares) are allocated.                                                                                                                                                                 |
| Becoming a Squad member                                     | During the raising events only.                                                                                                                                                                                                                                                                                                                                              | *As Portfolio*                                                                                                                                                                                                                                                                                                           |
| RageQuit:                                                   | Yes, any time. No fee, re-entry only during the future raising events.                                                                                                                                                                                                                                                                                                       | *As Portfolio*                                                                                                                                                                                                                                                                    |
| GuildKicks (forced RageQuit proposals):                     | Yes, any Squad member can propose others to be kicked out. In case of YES vote, the $VOX (shares) of such member are transferred to Loot.                                                                                                                                                                                                                                    | *As Portfolio*                                                                                                                                                                     |
| Minimum retention:                                          | 25% - if 75% RageQuit during the grace period, the proposal is cancelled.                                                                                                                                                                                                                                                                                                    | *As Portfolio*                                                                                                                                                                                                                                                                 |
| Proposals:                                                  | 5 proposals per day/35 per week can be submitted. A proposal deposit of 0.2ETH is required for submission. Voting process according to LIP, voting open for 72h. Stewards call processProposal function.                                                                                                                                                                     | *As Portfolio*                                                                                                                                  |
| Shaman:                                                     | Permission 3: pause, mint, burn shares and loot without DAO proposal. Governor permission not advicable as changes based on LIP.                                                                                                                                                                                                                                             | *As Portfolio*                                                                                                                                                                                                           |
| Gnosis safe with multisig:                                  | The DAO will be summoned from Gnosis safe. Sentinels (multisig) will remain in their responsibility. On-chain execution in roadmap.                                                                                                                                                                                                                                          | *As Portfolio*                                                                                                                                                                                                        |


Both of these approaches are explained below with examples.

### Portfolio/ Investment Club

By default all the assets are pooled in the DAO main treasury. The new members joining are part of the same portfolio and exposed to the past investments. The Squad members can decide to set up any further guilds or sub-DAOs just like in the syndicate option. Everyone can RageQuit at any time and their shares value (and represented assets) in the time of RageQuit will be transfered to loot. RageQuited members can re-join during the next raising event.

**Genesis Event: DAO launch & the initial raise**

* Price: 100 $VOX (shares) = 1 ETH
* Minimum tribute: 1 ETH
* Permissionless entry
* Contract has upper limit & time expiry; mints shares according to investors' tribute size, the price of everyone's shares is the same.

**Example**

*In examples we will use place holders X, Y & Z for supported projects and Tx, Ty & Tz for their tokens*

In the real life scenario the amount of shares (the tribute) will be arbitrary per each member and some members will likely RageQuit with their funds. This example is simplified to get the understanding of the portfolio logic.

* 100 people join the Squad for 10 ETH each -> 1000 $VOX (shares) each.
* Treasury net = 1000 ETH; 100 000 $VOX (shares) was minted.
* The Squad invests 500 ETH to X in exchange for their token Tx. Deal is 1 ETH = 1000 Tx.
* No-one RageQuits.
* Treasury net = 500 ETH + 500 000 Tx, represented by 100 000 $VOX (shares).
* Each member owns 1000 $VOX (shares) representing 5 ETH + 5000 Tx.

**Second LunarDAO raising event**

Because the new members have access to the deals of the past, the entry price is always 10% higher than the price during the previous event. This premium rewards members who entered past deals and stayed in the DAO exposing their part of portfolio to the new members. Any old member can RageQuit before the event with their assets and re-enter with ETH again.

* Price: 100 VOX (shares) = 1.1 ETH 
* Conditions and minimum tribute to be decided by the existing Squad.

**Example**

* 100 new people join the existing Squad -> Each of the new member paid 11 ETH -> 1000 $VOX (shares) -> 100 000 new $VOX were minted.
* Treasury has 200 000 $VOX total.
* Squad = 200 members
* Treasury net = 500 + 1100 ETH + 500 000 Tx
* Each $VOX (share) represents:
    - 0.008 ETH
    - 2.5 Tx
* Every Squad member has the same amount of shares: 1000 $VOX.  Their shares representing:
    - 8 ETH (1600/ 200)
    - 25 000 Tx (500 000 / 200)
* The first 100 members paid 10 ETH each, the new members paid 11 ETH each.
* The Squad invests 800 ETH to Y in exhange for their token Ty. Deal is 1 ETH = 10 000 Ty.
* Treasury net = 800 ETH + 500 000 TX + 8 000 000 Ty
* Each member holding 1000 $VOX (shares) is an owner of:
    - 4 ETH
    - 2500 Tx
    - 40 000 Ty
    

**Summary**
    
* At any point any member can exit with their funds partly or fully.
* The Squad decides if, how and when to do next rasing events.
* A bonding curve adds 10% to the price of $VOX (shares) for every next raising event.
* Every member can add more funds during the next fundraising event.
* All Squad members share a RageQuitable portfolio together, equal to the size of their tribute.
* The Squad can decide to open separated guilds.


### Syndicate

Each investment or fundraising cycle is treated as a separated entity. Members joining in future fundraising events share a new treasury (sub-DAO or a guild) without an access to the investments from the past. All treasury related proposals have impact only on the separated guild/sub-DAO in which the proposing Squad member is at. Alternatively the assets can be still pooled together but an on-chain Snapshot of $VOX at the time of the investment is taken. The DAO uses proxy tokens to track who had tokens at the time of investment. This greatly simplifies raising, because the treasury is always ETH. The price of $VOX for new members would have to be calculated differently than in the Portfolio case.

**Genesis Event: DAO launch & the initial raise**

* Price: 100 $VOX (shares) = 1 ETH
* Minimum tribute: 1 ETH
* Permissionless entry
* Contract has upper limit & time expiry; mints shares according to investors' tribute size, the price of everyone's shares is the same.

**Example**

*In examples we will use place holders X, Y & Z for supported project and Tx, Ty & Tz for their tokens*

In the real life scenario the amount of shares (the tribute) will be arbitrary per each member and some members will likely RageQuit with their funds. This example is simplified to get the understanding of the portfolio logic.

* 100 people join the Squad for 10 ETH each -> 1000 $VOX (shares) each.
* Treasury net = 1000 ETH; 100 000 $VOX (shares) was minted.
* The Squad invests 500 ETH to X in exchange for their token Tx. Deal is 1 ETH = 1000 Tx.
* No-one RageQuits.
* Treasury net = 500 ETH + 500 000 Tx, represented by 100 000 $VOX (shares).
* Each member owns 1000 $VOX (shares) representing 5 ETH + 5000 Tx.

**Second LunarDAO raising event**

Because the new members joining another entity, separated from the initial DAO launch treasury, raise looks like the same like the Genesis Event. In such scenario each sub-DAO manages their funds on their own in parallel to each other. 

**Summary**

* Every new raise is unrelated to the previous investments andf starts in the same fashion
* Old members are innaffected by the new members
* Each member can be part of multiple sub-DAOs
* Decisions regarding to the general governance can be voted in all the sub-DAOs together and counted as one vote event.
* If pooling together: Investment = N amount of proxy token which can be converted when RageQuitting. Cost more in gas fees.

## Conclusion

LunarDAO is an anonymity-first organization. However our mission is bigger than that. The Portfolio and Syndicate options (and anything between and beyond) the largest question remaining to be resolved. We believe that the launch may be easier and more interesting with the Portfolio option as a default, which leaves the door open for anyone to join the Squad and decide in the future how to manage further fundraising events, guilds, sub-DAOs and all the changes. Build a strong united Squad accountable to the common mission and shared wealth. Looking into investment DAOs based on Moloch V1 & V2, listening to the allies in chats and multiple meetings with builders, we believe that LunarDAO should not kick-off as an experiment, instead start on well tested mechanisms. 

There is still several questions which we listed below and would like to hear as many opinions on as possible. 

We would like to remind all the participants to protect themselves and read our [docs on anonymizing assets](https://wiki.lunardao.net/anonymizing_assets.html) and use Aztec or TornadoCash mixers, ensure network protection and [change RPC](https://wiki.lunardao.net/change_rpc.html) as a basis to join LunarDAO.

## Questions

### Main Question

However there are many important details to decide upon, giving all the pros and cons, the main discussion is in between the presented fund management options (or their timing):

**1.A) Shall LunarDAO launch on a variation of the PORTFOLIO approach and eventually open guilds or sub-DAOS based on future voting?**

or:

**1.B) Shall LunarDAO launch as a SYNDICATE?**  

### Other Attributes to Decide

Keep in mind that if we were to choose Moloch V3 model, the questions are related for the setup on launch with a possibility to change many of these settings later on. Those changes, or at least a discussion about them can be included in the roadmap, so different options in different phases of the DAO life cycle are already considered.

2. What amount does the DAO aim to raise (the first round)? - the proposed mark is 7000 ETH (700 minimum and 15000 cap).
3. Is the minimum tribute of 1 ETH too large/small? 
4. In the case of Portfolio; is 10% bonding curve too (dis-)advantageous for the old or new members?
5. In the case of Syndicate design; would people prefer separated sub-DAOs or a common pool with proxy tokens? 
6. Do we want to use Arbitrum or Polygon as a layer 2 solution or stay on Ethereum Mainnet? The latter has higher liquidity and gas fees. Those can be seen as an obstacle when managing many different tokens or a feature preventing from spam. Importantly, some of the supported projects may have bridged tokens only to the Mainnet.
7. Is management/admin fee of 0.5% acceptable for the community?
    a) On entry & every three months.
    b) On entry & with every deal execution.


## LFG!


As decided in LunarDAO [Objectives & Key Results for February](https://github.com/lunardao/okr/blob/master/okrs_february_23.md) the DAO structure shall be finished and approved by the community by March 6th.

**LET'S DECIDE THE BEST WAY TOGETHER, JOIN THE [DISCUSSION](https://forum.lunardao.net/t/tokenomics-lunar-vox/89/45)!**

**[SUPPORT THE DEVELOPMENT](https://github.com/lunardao/dao/blob/master/SUPPORT.md) OF LUNARDAO ARCHITECTURE!**


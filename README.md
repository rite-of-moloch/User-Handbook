---
description: >-
  Raid Guild is introducing an open source dApp (decentralized application) to
  help offset the costly onboarding process and reduce turnover.
---

# RiteOfMoloch

DAOs commit resources towards onboarding new members (cohorts), while cohort participants often have little to no skin in the game. This can lead to suboptimal resource management of DAOs and low onboarding success rates of cohort participants.

To align incentives during onboarding, this tool has been designed for DAOs to require new cohort members to stake certain assets. In exchange for committing funds to the contract, individual participants of the cohort receive a soul bound token (non-transferable token tied to that member). After staking the participants can use the token to enter gated oboarding channels and access DAO onboarding resources.

If the user does not complete the onboarding process or refuses to engage sufficiently, the staked assets are then forfeited. Due to the fact that individual cohort contracts are not upgradeable, the cohort clone factory contract enables additional implementations to be added. This feature grants the deploying DAO to minimise maintenance cost of its tooling for onboarding new members and enables a wide range of extensibility for different types of tokenized communities.

{% hint style="info" %}
Currently, the cohorts are specifically designed for Moloch DAOs, but we can easily add new implementations for staking NFTs, or different membership criteria.
{% endhint %}

<figure><img src="https://i.imgur.com/VAZ8SDT.jpg" alt=""><figcaption></figcaption></figure>

## Interport RFP

### Distribution Plan

Our token allocation is based on allocation points (hereinafter, the “AP”). As of May 01, 2024, Interport’s core products, including cross-chain swaps and bridging, were available on 17 networks. To ensure a fair and proportional distribution of tokens via LayerZero, we have issued 17,000 allocation points (1,000 per network). Using AP allows us, where appropriate, to tailor the distribution according to each category, promoting balanced growth and incentivizing participation across all categories. This method ensures that our token distribution aligns with the actual use and performance of our core services.

The distribution plan of the allocation points, and hence the token allocation, will be the following:
- **Developers:** 1,700 AP
- **Cross-chain swaps & stablecoin bridge users** (depending on user’s volume): 10,200 AP
- **Gas Transfer users** (depending on user’s transactions amount): 1,020 AP
- **OFT Token Bridge users** (depending on user’s transactions amount): 85 AP
- **Stablecoin liquidity providers across 6 networks** (depending on user’s TVL): 1,700 AP (283.333333333333 AP per network)
- **Liquidity providers for ITP Token among 5 networks** (depending on user’s TVL): 1,275 AP (255 AP per network)
- **ITP Token Holders** (depending on user’s ITP amount): 850 AP
- **Interport League Ranks Campaign** (depending on user’s Campaign Rank): 170 AP

### Justification for Distribution Plan

Considering our project's community interests, as well as principles of equity and fairness, we justify our token distribution plan with the following argumentation per each category of the drop.

#### Timeline Notice
All data used and analyzed is as of UTC 11:59 PM of May 01, 2024.

#### Developers
- **Allocation Points:** 1,700 AP

Developers are essential for building and maintaining the Interport Finance platform. Their continuous efforts ensure the stability, security, and enhancement of the platform's core functionalities. This allocation recognizes their critical role and incentivizes ongoing innovation and improvement. As required by LayerZero, this amount does not exceed the 10% threshold.

#### Cross-Chain Swaps & Stablecoin Bridge Users
- **Allocation Points:** 10,200 AP
- **Unique Users:** 139,834
- **Volume Amount:** $440,734,133

As cross-chain swaps and bridge are the core products of our Protocol, as well as providing the biggest volume and usage, we decided to distribute a solid amount of AP to this category. All of our cross-chain operations are powered by LayerZero technologies, showcasing the advanced functionality and seamless integration provided by LayerZero.

The drop in this category will be split pro rata by volume of the user via the next formula: `[User’s Volume / All Volume * 10,200 AP]`.

Example: If a user has conducted $10,000 worth of transactions and the total transaction volume is $440,734,133, the user receives: `$10,000 / $440,734,133 * 10,200 AP = 0.23143204 AP`.

#### Gas Transfer Users
- **Allocation Points:** 1,020 AP
- **Unique Users:** 17,637
- **Transaction Amount:** 30,938

This product plays a complementary role in our cross-chain hub by allowing users to transfer native tokens across networks. All gas transfer operations are powered by LayerZero technologies.

The drop in this category will be split pro rata by transactions amount of the user via the next formula: `[User’s Transactions / All Transactions * 1,020 AP]`.

Example: If a user has conducted 10 transactions and the total transaction amount is 30,938, the user receives: `10 / 30,938 * 1,020 AP = 0.329691641 AP`.

#### OFT Token Bridge Users
- **Allocation Points:** 85 AP
- **Unique Users:** 1,311
- **Transaction Amount:** 2,321

Users who utilize the OFT bridge play a crucial role in demonstrating the functionality and reliability of LayerZero's technology. As the total amount of transactions of OFT Tokens via our bridge is significantly less than the utilization of other features on our Protocol, we find it reasonable to limit the AP for this category.

The drop in this category will be split pro rata by transactions amount of the user via the next formula: `[User’s Transactions / All Transactions * 85 AP]`.

Example: If a user has conducted 10 transactions and the total transaction amount is 2,321, the user receives: `10 / 2,321 * 85 AP = 0.36622146 AP`.

#### Stablecoin Liquidity Providers
- **Allocation Points:** 1,700 AP
- **Unique Users:** 307
- **TVL:** $3,466,809.97

Stablecoins are used for cross-chain swaps and bridge routing, thus stablecoin liquidity providers are essential for Interport's functionality and stability. As this category of users also receives ITP Token incentives we seem reasonable to provide them with the mentioned amount of AP.

Furthermore, as we recognize that each networks’ liquidity is crucial for the protocol’s seamless operations we decided to split equally the AP for this category, meaning that Liquidity Providers on each network will receive 283.333333333333 of AP, which will further be distributed to them based on the pro rata of their TVL provided.

The drop in this category will be split pro rata by TVL amount of the user via the next formula: `[User’s TVL / Network TVL * 1,700 AP/6]`.

Example: If a user has provided $1,000 worth of TVL and the total TVL on the Fantom network is $138,924, the user receives: `$1,000 / $138,924 * 1,700 AP / 6 = 2.03948442 AP`.

#### Liquidity Providers for ITP Token
- **Allocation Points:** 1,275 AP
- **Unique Users:** 253

Liquidity providers for ITP tokens are crucial for ensuring the availability and stability of the ITP token within the ecosystem, as well as incentivization of stablecoin liquidity providers. By providing liquidity, they support trading activities and contribute to the overall health of the protocol.

Furthermore, as we recognize that each network’s liquidity is crucial for the protocol’s seamless operations we decided to split equally the AP for this category, meaning that Liquidity Providers on each network will receive 255 of AP, which will further be distributed to them based on the pro rata of their TVL provided.

The drop in this category will be split pro rata by LP amount of the user via the next formula: `[User’s LP / Network LP * 1,275 AP/5]`.

Example: If a user has provided 10 LP and the total LP amount on the Ethereum network is 3,205, the user receives: `10 LP / 3,205 LP * 1,275 AP / 5 = 0.795631825 AP`.

#### ITP Token Holders
- **Allocation Points:** 850 AP
- **Unique Users:** 23,563
- **Total ITP:** 4,980,889 ITP

ITP token holders represent the core supporters and community in the Interport Finance ecosystem. By holding ITP tokens, they demonstrate long-term commitment and belief in the Project's success.

The drop in this category will be split pro-rata by ITP amount of the user via the next formula: `[User’s ITP / All ITP * 850 AP]`.

Example: If a user held 1,000 ITP Tokens and the total ITP Token amount was 4,980,889, the user receives: `1,000 ITP / 4,980,889 ITP * 850 AP = 0.17065227 AP`.

#### Interport League Ranks Campaign
- **Allocation Points:** 170 AP
- **Unique Users:** 712
- **Total Transactions:** 6,234

We want to reward users for their active participation through the Interport League Ranks Campaign. The more transactions a user makes, the higher their rank, and the greater their share of the 170 AP.

The distribution is based on the number of transactions users made to achieve their rank. Each rank has a specific AP allocation, and users receive AP cumulatively for all ranks they have passed.

AP per Rank = (Transactions for Rank / Total Transactions) × 170 AP

AP Allocation per Rank:
- **Rank 1:** 0.0818 AP
- **Rank 2:** 0.3272 AP
- **Rank 3:** 0.9544 AP
- **Rank 4:** 1.3635 AP
- **Rank 5:** 2.7269 AP

Example: Rank 3 User: `0.0818 AP (Rank 1) + 0.3272 AP (Rank 2) + 0.9544 AP (Rank 3) = 1.3634 AP`

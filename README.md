### Project Title
HedgeWave Protocol - Decentralized Parametric Insurance Framework utilizing RLUSD on XRPL EVM Sidechain.

### Project Lead Name
Saurav Dhar

### Company/Institution Name (if applicable)
N/A

### Legal Entity Name (if applicable)
N/A

### Where is the majority of your team based?
United States

### Project Team Members
The team currently consists of a solo developer, with plans to expand to two developers within 1–2 months of receiving the grant.

Current Team:

- Saurav Dhar
- Lead Developer and Founder of HedgeWave
- Based in Seattle, U.S. permanent resident and Indian citizen.
- Software developer since 2015 with 8+ years of Web2 experience as a Fullstack engineer and founding engineer at an Adtech startup that was later acquired.
- Building full-time in Web3 since late 2023, focused on Solidity and applied ZK. Winner of multiple hackathons including ETHDenver (2024, 2025), ETHGlobal (Circuit Breaker, San Francisco 2024), and zkHack (Istanbul & Montreal).

### Project Description/Summary
HedgeWave Protocol is a decentralized parametric insurance framework. It enables trustless insurance using smart contracts and oracles that get real world data. Payouts for real-world risks such as flight delays, bad weather, earthquakes, wildfires or inflation are triggered instantly when smart contract conditions are met based on oracle data. Users purchase coverage in RLUSD and receive compensation automatically, with no need for manual claims. Yield-seeking investors underwrite risk in exchange for returns. The framework includes vaults, oracle integration, and liquidation bots. It is open-source, and developers are encouraged to build new insurances on different verticals using this framework.

### Company Summary (if applicable)
N/A

### Project Demo (Required)
https://www.loom.com/share/6e4137a0f2334aa2a88cbb96bad26d83?sid=6e1719f0-59e8-4dda-8874-55d1eb7ac53c

### External Project or Company URL
https://hedge-wave-ripple.vercel.app/

### Social Media Handles (Optional)
N/A


### Do you have a pitch deck to upload?
https://github.com/enderNakamoto/xlm_evm_insure/blob/main/Ripple%20Deck%20I%20.pdf

### In a few sentences please summarize what you will build with XRPL Grants funding

At ETHDenver 2025 hackathon, we built a proof of concept for a decentralized hedge against Turkish Lira inflation but had to cut corners on protocol design to meet the hackathon deadline. With XRPL Grants funding, we’ll upgrade to a parametric insurance framework that offers faster, transparent, and automated payouts compared to traditional insurance. Flight delay coverage will be the first vertical, using RLUSD for both premiums and underwriting. The system will be powered by smart contracts, oracles, and decentralized liquidation bots. It also creates a new yield source that's uncorrelated to crypto and equity markets for investors underwriting real-world risk.

### Proposed Project Roadmap and Key Milestones (for XRPL Grants Funding)

Over a 10-month period, we will take HedgeWave Protocol from a validated proof of concept to a fully functional, testnet-proven, closed-beta-ready product for decentralized flight delay insurance.

* Month 1–2: Risk Vault Architecture + Protocol Refactor:
We will implement the Central Risk Vault architecture, replacing separate risk vault per market architecture with a pooled structure to improve capital efficiency and simplify investor exposure. RLUSD will be used for both underwriting and payouts.
More details here - https://github.com/enderNakamoto/xlm_evm_insure/blob/main/technical.md#central-risk-vault-architecture

* Month 2–3: Oracle Infrastructure Update
We’ll deploy an Oracle Aggregator Contract and supporting off-chain ingestion scripts using Acurast TEEs or Chainlink Functions. This will modularize and decouple flight data from core contract logic for scalability.
More details here - https://github.com/enderNakamoto/xlm_evm_insure/blob/main/technical.md#oracle-layer-enhancements

* Month 4–5: Flight Delay Insurance Interface
A dedicated UI will be developed for RLUSD-based flight insurance, including real-time flight search, policy discovery, and payout transparency. It will cater to both crypto-native and mainstream users.

* Month 5: Automated Market Infrastructure
We’ll integrate frontend logic that checks whether a flight is already insured, and if not, trigger creation of a new Hedge Vault on-chain. This enables just-in-time insurance for long-tail flights.
More details - https://github.com/enderNakamoto/xlm_evm_insure/blob/main/technical.md#automated-market-creation

* Month 6: E2E Testing + Liquidation Bots
Deploy to EVM testnet and simulate real user journeys—including purchasing RLUSD policies, oracle-based claim triggers, and investor withdrawal. We’ll also open source liquidation bots for executing payouts.
More details - https://github.com/enderNakamoto/xlm_evm_insure/blob/main/technical.md#decentralized-liquidation-bots

* Month 7: zkTLS Flight Ticket Verification
Integrate zkTLS to verify that users actually have flight tickets, without revealing private data. We will use reclaim protocol (https://reclaimprotocol.org/), vlayer(https://www.vlayer.xyz/) or comething similar.

* Month 8: Closed Beta Launch + Yield Study
Launch a closed beta on the XRPL EVM Sidechain and onboard test users and RLUSD underwriters. In parallel, conduct a detailed yield analysis using live flight delay data to model capital sustainability.

* Month 9-10: Auditing + Risk Mitigation
Conduct third-party audits of all smart contracts and oracle integrations. Finalize mitigation strategies for edge cases such as failed or stale oracles, and prep for public release.

### Target Users and General Market Opportunity

Target Users


- Travelers (starting with crypto-native flyers): We begin with Web3-savvy travelers attending events like ETHGlobal, Devcon, and Token2049—comfortable with stablecoins and self-custody. Over time, we’ll expand to mainstream users via airline and travel platform integrations.

- DeFi yield seekers: Users looking for sustainable, uncorrelated RLUSD-based returns by underwriting real-world risks like flight delays—offering an alternative to lending, LPs, or trading strategies.

- Builders and dev teams: Our open-source HedgeWave Protocol enables developers to build vault-based parametric insurance products for risks like wildfire, crop failure, and weather events.

- Future users across verticals: As we expand beyond flight delay, our user base will grow to include farmers, enterprises, and public-sector agencies seeking automated, event-based coverage.

Market Opportunity

Parametric insurance is growing fast. The global market was valued at $16.2 billion in 2024 and is projected to reach $40.6 billion by 2033, growing at a 9.9% CAGR (according to Global Market Insights and EIN Presswire). Growth is fueled by climate volatility and enabling tech like IoT, AI, and remote sensing.

One of the most promising applications is parametric flight delay insurance. These policies issue automatic payouts when flights are delayed beyond a preset threshold.

Blockchain enhances this model further. Smart contracts automate payouts. DeFi-native players like Ensuro allow crypto investors to underwrite these policies and earn yield.

The global travel insurance market is projected to reach $143.5 billion by 2033, growing at 20.1% CAGR. If even 10% of policies include parametric delay coverage, that’s a $3B+ opportunity—well-suited for blockchain-native products.

(Full market research: https://github.com/enderNakamoto/xlm_evm_insure/blob/main/market.md)

### Does your project have a GitHub Repository?
Yes

### Github Repo Link(s)

* Hackathon Submission - https://github.com/enderNakamoto/hedgr
* This submission along with technical architecture and market research - https://github.com/enderNakamoto/xlm_evm_insure

### Is your project already integrated with the XRP Ledger?
No

 

### How will your project integrate with the XRP Ledger?

We are building on the XRPL EVM Sidechain, not the XRP Ledger itself. HedgeWave Protocol will be deployed on this EVM environment, using RLUSD as the native currency for purchasing insurance, underwriting risk, and processing payout

### What chains are you currently building on?
Multi-chain


### Please share all chains or sidechains you are currently building on for this project
We initially deployed on Ethereum's Sepolia testnet during the hackathon because it was the only network with a working RLUSD faucet. We'll continue prototyping on Sepolia, but we're open to deploying on any EVM-compatible chain with sufficient RLUSD liquidity—prioritizing the XRPL EVM Sidechain for mainnet launch.

### Project Traction & Growth
HedgeWave Protocol was created just one month ago as a hackathon project at ETHDenver 2025. At this early stage, we have no active users, no transaction volume, and no wallet metrics, as we are still in the transition from prototype to product.

Current Traction

- Deployed an initial prototype on Sepolia testnet (due to available RLUSD faucet).
- Received strong validation from Ripple mentors and ETHDenver hackathon judges
- Conducted user interviews with crypto-native travelers and DeFi-native investors
- Identified Flight Delay Insurance as the first high-impact vertical
- User feedback confirmed clear pain points that our protocol can solve through automation and oracle-driven claims
- We are now ready to build on this early momentum and launch HedgeWave Protocol on the XRPL EVM Sidechain.


### What is your current financial runway?
We currently do not have any financial runway. We have not raised external funding or received any grants yet. This application represents the beginning of our journey, and we are applying to XRPL Grants to build something valuable with real-world impact.

### Monetization Strategy
Our current strategy is to take a small commission fee of 1–2% from insurance purchases and vault yields. In the future, we aim to support multiple insurance verticals by routing capital through our vault infrastructure, generating revenue as more users buy coverage and underwriters participate across different risk markets

### Main Project Category
Decentralized Finance (DeFi)

### Secondary Project Category (if applicable)
Real-world Asset (RWA)



### Will your project utilize the EVM Sidechain?
Yes

### EVM Sidechain Use Case
Our use case is a parametric insurance framework built with EVM smart contracts. It will be deployed on the XRPL EVM Sidechain and use RLUSD as the stablecoin for both purchasing insurance and underwriting risk. RLUSD, as an ERC-20 standard token, is easy to integrate into our vault-based architecture and supports seamless interactions across all protocol components. Insurance buyers pay in RLUSD, and DeFi users earn real yield in RLUSD by acting as counterparties to real-world risks like flight delays.

### Is your project open source?
100% open source

### Project Stage
Prototype: Earliest stage of startup development, building proof-of-concept or MVP to test product-market fit, still figuring out business model, may not have revenue yet

### Which of the following best describes your current motivation(s) for being or working on your project? (Select up to Three Options)
* Build a successful long-term business using blockchain technologies
* Make a meaningful impact on society
* Disrupt the centralized systems/establishment
* Drive adoption of blockchain technology
* Use blockchain to build something that is financially successful with real world application

### Were you recommended to apply to XRPL Grants?
Yes, we were encouraged to apply by Ripple mentors and judges during the ETHDenver 2025 hackathon. We received positive feedback on our project.

### Has any member of your project team previously received funding from XRPL Grants, XRPL Accelerator, or another Ripple-affiliated program?
No

### Was this project part of a recent XRPL Hackathon?
Yes

### Hackathon Participation
We participated in the ETHDenver 2025 hackathon, where Ripple sponsored a bounty. Our project was built as part of that bounty track.

* Hackathon: ETHDenver 2025
* Dates: February 23 – March 1, 2025
* Project Name: HedgeWave Protocol (originally submitted as "HedgeWave")
* Bounty: 1st Place in Ripple’s "RLUSD: Mission Stablecoin Adoption" – $5,000 prize

* Project Links:
* * Devfolio: https://devfolio.co/projects/hedgewave-d63e
* * GitHub: https://github.com/enderNakamoto/hedgr
* * UI Demo: https://hedge-wave-ripple.vercel.app/
* * Loom Video - https://www.loom.com/share/7180f236165a4dfdbc817b934c1082d7?sid=eeec0514-2eab-4acc-a783-698b1b8c0f4e

The prototype used RLUSD to create a decentralized hedge against Turkish Lira inflation. This served as the foundation for what is now HedgeWave Protocol, a broader parametric insurance framework offering real-world coverage and uncorrelated yield on the XRPL EVM Sidechain.

### How did you find out about XRPL Grants?
Hackathon

### Please provide any additional details on how you found the XRPL Grants program
We first came across XRPL Grants while researching the Ripple bounty at ETHDenver 2025. During the event, we spoke with Ripple engineers and mentors, who explained the grant follow-up process and encouraged us to apply after the hackathon.

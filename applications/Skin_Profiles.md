# Mintbase Grant Proposal

- **Project Name:** Adaptive Blend - Skin Priority Profiles.
- **Team Name:** Adaptive Blend
- **Payment Address:** adaptiveblend.near
- **[Level](../README.md#level_slider-levels):** 1

## Project Overview : 📄
***Skin Priority Profiles** : Digital representations of users’ personalized skin priorities based on an initial 512 potential combinations.*

<br/>

Adaptive Blend is transforming skincare by prioritizing users’ real-time skin needs through ***Digital—Skin Priority Profiles***,  which anchor personalized skincare experiences, enable
data-driven decisions and foster engagement in a gamified Web3 ecosystem, **shifting focus from product-driven solutions to individual skin priorities.**


---
<br>

**The Problem** : The skincare industry is vast, yet highly impersonal. 

Consumers face:
  - Uncertainty in product selection.
    - *>$70/user/year wasted on mismatched products spending*
    - *> 2 hours spent researching per product*
  - Lack of personalized solutions
    - *>30 hours/user/year wasted managing allergic reactions and subpar results*
  - Difficulty tracking skincare progress.
    - *Users struggle to assess long-term improvements.*

<br>

***"The Core Problem: Skincare revolves around products rather than the unique needs of individual skin priorities."***

<br>




**The Vision** : Shifting Skincare to Skin Priorities.

<!--Adaptive Blend is on a mission to transform skincare by making users’ skin priorities the focal point.-->
Adaptive Blend redefines skincare by placing users at the center. By prioritizing real-time individual skin priorities, we empower users to control their skincare journeys with adaptive, data-driven tools that cater directly to their unique needs.

  - Personalized Skin Priority Profiles
    - ***Core of Personalization:** 512 unique combinations of skin concerns, goals, and characteristics ensure precise guidance.*
    - ***Data-Driven Insights:** Profiles adapt to users’ evolving needs, making skincare dynamic and personalized.*

  - AI-Powered Decision-Making
    - ***Product Compatibility Analysis:** <3s Evaluation of product compatibility based on individual profiles*
    - ***Product Recommendations:** Products efficacy-aligned to present skin priorities.*
    - ***Vendor Verification:** Verifies vendor authenticity using real-world feedback.*

  - Building a Gamified, Composable Ecosystem: 
    - *Routine tracking and performance evaluation.*
    - *Custom formulation creation tailored to user needs.*
    - *Secondary marketplaces for community-generated formulations.*


The ultimate goal is to build a *Composable Skincare Ecosystem*, blending Real-World Applications with Gamified, NFT-driven features, paving the way for collective intelligence in skincare.
 starting with compatibility analysis, routine tracking and evolving into a Crafting Station for custom formulations that users can digitally create, share and sell in a secondary marketplace.

<br>



**Integration into the Mintbase / NEAR Ecosystem:**
- **Mintbase :** For minting and managing NFT Skin Priority Profiles.
- **Mintbase GraphQL Indexer:**  To query NFT Metadata.
- **NEAR Protocol :** The foundational blockchain for our Smart Contracts. 

<br>


**Why Our Team is Interested :**
We are motivated to solve the inefficiencies of trial-and-error skincare, a process that costs consumers both time and money while delivering inconsistent results. We envision a world where every individual has access to personalized skincare that adapt and evolve with their needs. By leveraging Mintbase/NEAR, we demonstrate how web3 technologies can merge digital innovation and tangible consumer benefits, setting a new standard for transparency and personalization in skincare.

<br/>

---
<br/>

### Project Details
<!--The Technical Implementation-->
**Objective: Develop and Deploy **Skin Priority Profiles NFTs**, enabling personalized skincare experiences by encoding user-specific skin needs into a secure and composable digital format.**

***Note: The Skin Priority Profiles NFTs is the only part that will be developed as this Level 1 grant application, as shown on the milestones.***

The Foundation of the Adaptive Blend Ecosystem are the Skin Priority Profiles. These are Digital representations of users’ personalized skin priorities based on an initial 512 potential combinations. Each unique combination forms a Single Skin Profile, and minted as an NFT.

These NFTs encode 512 scientifically-defined skin priority combinations with deterministic precision, enabling :
  - Personalized product compatibility analysis and recommendation.
  - Gamified engagement mechanics.
  - Routine tracking and performance evaluation.
  - Secondary marketplace opportunities.
  - Interoperable data structures for long-term adaptability

This implementation establishes the critical infrastructure for Adaptive Blend’s personalized and composable skincare ecosystem.
 
 Further Specification: - https://github.com/Adaptive-Blend/skin-profiles

<br/>



- Technology Stack:
    - Smart Contracts: Rust, NEAR SDK, Mintbase API
    - Front End: Svelte.
    - Hosting: Arweave.
    - Interactive Comms stack: TikTok



### Ecosystem Fit
<!--Help us locate your project in the Mintbase landscape and what problems it tries to solve by answering each of these questions: -->

- Where and how does your project fit into the ecosystem?
  - Built on Mintbase, driving web3 adoption through a novel use case.
  - Expanding Mintbase’s reach into wellness and personalized services.
  - Expand NFT use cases by introducing a groundbreaking application for skincare personalization.
  

- Who is your target audience?
  - Skincare consumers seeking personalized solutions.

- What need(s) does your project meet?
  - Enhancing transparency and user engagement through ownership.
  - Enabling data-driven improvements in skincare.
  - Fostering collective intelligence in personalized skincare.

- Are there any other projects similar to yours in the Mintbase / NEAR ecosystem?
  - No directly comparable projects within the Mintbase/NEAR ecosystem. Adaptive Blend leverages NFTs uniquely for wellness and personalization in skincare.

## Team 👥

### Team members

- Muriithi : Founder
- Additional team members TBD.

### Contact

- **Contact Name:** Carlos Muriithi
- **Contact Email:** c_muriithi@outlook.com
- **Website:**

### Legal Structure

- **Registered Address:** N/A (DAO incorporation pending)
- **Registered Legal Entity:** N/A (DAO incorporation pending)

### Team's experience

- Web3 engineer and part-time security researcher on Immunefi.

- Relevant expertise in blockchain, NFTs, and user-centric application design.



### Team Code Repos

- https://github.com/Adaptive-Blend
- https://github.com/Adaptive-Blend/skin-profiles

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

- https://github.com/117l11


## Development Status 📖

Current development ongoing at [Skin Profiles](https://github.com/Adaptive-Blend/skin-profiles) 


## Development Roadmap 🔩


***NFT Skin Profiles** : Digital representations of users’ personalized skin priorities based on an initial 512 potential combinations.*

### **3 Milestones:**
- **1) v2 Encoding Specification and Metadata Schema.**
- **2) Skin Priority Profile Metadata Storage and Updates on Arweave.**
- **3) Skin Priority Profile NFT Smart Contract.**

### Overview


- **Total Estimated Duration:** 1.5 Month.
- **Full-Time Equivalent (FTE):**  1 FTE.
- **Total Costs:** $10,000.

### Milestone 1 — v2 Encoding Specification and Metadata Schema.

- **Estimated duration:** 1 week
- **FTE:**  1
- **Costs:**  2,000 USD



| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. 		| License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. 		| Documentation | Inline schema documentation, usage and reference. |
| 0c. 		| Testing Guide | Unit tests validating schema integrity and versioning. |
| 1. 		| Encoding Specification v2 | Detailed markdown document establishing encoding rules and standards for **Skin Priority Profiles v2**. This document specifies how skin priority data is deterministically encoded and represented in the **Off-Chain JSON Metadata** of our NFTs built on **NEP-254**, extending the metadata standards to integrate Adaptive Blend functionality. It defines a precise, extensible structure for encoding all 512 Skin Priority Profile combinations, ensuring compatibility with the standard while enabling dynamic, composable integrations unique to the Adaptive Blend ecosystem.|
| 2. 		| Off-Chain Metadata Schema |  Deterministic JSON metadata schema encoding all 512 Skin Priority Profile combinations while adhering to **Encoding Specification v2**. |
| 3. 		| Schema Update Rules | Markdown document defining the update and validation rules, for metadata changes in the Adaptive Blend ecosystem. It establishes clear guidelines for ensuring backward-compatible updates to Skin Priority Profile NFT metadata while adhering to **Encoding Specification v2**. |



### Milestone 2 — Metadata Storage and Updates on Arweave

- **Estimated Duration:** 2 weeks
- **FTE:**  1
- **Costs:** 3,500 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. 		| License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. 		| Documentation | Inline schema documentation, usage and reference. |
| 0c. 		| Testing Guide | Test suite ensuring metadata integrity,  update compliance and version control on Arweave. |
| 1. 		| Metadata Storage on Arweave | Uploading and Retreive complete 512 metadata set to Arweave.  |
| 2. 		| Schema Update Rules Logic|   **Schema Update Rules** Logic. Implement Logic to handle schema updates while preserving metadata history. |


### Milestone 3 — Skin Priority Profile NFT Smart Contract

- **Estimated Duration:** 3 weeks
- **FTE:**  1
- **Costs:** 4,500 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. 		| License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. 		| Documentation | Inline contract documentation, tutorial for deployment, and usage reference.|
| 0c. 		| Testing Guide | Unit tests for contract functions, edge case handling, and integration with metadata. |
| 0e. 		| Article | End-to-end demonstration with summary of achievements, challenges, and usage.|
| 1. 		| NFT Smart Contract  | NEP-254 compliant Smart Contract extended from `mb-nft-v2`.|
| 2. 		| Update Logic | Functions for Contract updates and change logging. |
| 3. 		| Testnet Deploy | Deploy Skin Priority Profile NFT smart Contract on Near Testnet linking metadata URI and reference and run mint tests.|
| 4. 		| Mainnet Deploy  | Deploy NEP-254 compliant Skin Priority Profile NFT smart Contract on Near Mainnet linking metadata URI and reference.|
| 5.    | End-to-End Workflow | Fully functional system for creating, minting and updating personalized skincare NFTs.|




## Future Plans

- Short-Term:
  - Launch AI-Powered Decision-Making
    - ***Product Compatibility Analysis:** Evaluates product compatibility based on individual profiles*
    - ***Product Recommendations:** Products efficacy-aligned to present skin priorities.*
    - ***Vendor Verification:** Verifies vendor authenticity using real-world feedback.*
  - Launch tools for routine tracking and progress evaluation.
  - Expand into personalized skincare formulations engine with a gamified crafting stations.
  - Secondary marketplace for custom formulations.


- Long-Term:
  - Build a data-driven ecosystem for innovation and development in skincare.




## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** 

- Mintbase Website

Adaptive Blend represents the culmination of extensive research, experimentation, and user feedback, designed to redefine the skincare industry with a systemized, user-centric approach. Through iterations involving AI, customer feedback, and market validation, we transformed *NoSass* into *Adaptive Blend—a decentralized, blockchain-powered ecosystem designed to redefine skincare personalization*.

Key milestones of this journey include:  
  - Building the Skin Priority Engine from First Principles
  - Harnessing AI to Create Personalized Formulations
  - Market Validation via TikTok and Ad Optimization
  - Learning from NoSass Market Validation and Challenges
  - Iterations and Insights Shaping Adaptive Blend
  - Refining the Go To Market: From Formulations to Compatibility Tools


This grant proposal seeks to accelerate the growth of Adaptive Blend by expanding its reach, enhancing its blockchain-powered infrastructure, and fostering an active community that continuously contributes to the evolution of skincare personalization.

By partnering with Mintbase and leveraging the NEAR blockchain, we will bring scalable personalization, transparency, and user empowerment to the world of skincare, revolutionizing an industry in need of change.




Thank you for considering our proposal. We look forward to your support in bringing Adaptive Blend to life.

Best regards,  
Carlos Muriithi (Founder)  
Adaptive Blend  



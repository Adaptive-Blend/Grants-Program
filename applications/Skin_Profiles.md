# Mintbase Grant Proposal

- **Project Name:** Adaptive Blend - NFT Skin Profiles.
- **Team Name:** Adaptive Blend
- **Payment Address:** adaptive-blend.near
- **[Level](../README.md#level_slider-levels):** 1

## Project Overview : 📄
***NFT Skin Profiles** : Digital representations of users’ personalized skin priorities based on an initial 512 potential combinations.*

<br/>

Adaptive Blend is on a mission to transform skincare by prioritizing the unique needs of users’ skin over generic product-driven solutions. The cornerstone of this transformation lies in users’ unique ***Digital Skin Profiles***, which anchor personalized skincare experiences and gamification in web3.

 <!--Adaptive Blend is on a mission to transform skincare by making users’ skin priorities the focal point.  The foundation of this transformation is our users’ unique ***Digital Skin Profiles***.-->

---
<br>

**The Problem** : The skincare industry is vast, yet highly impersonal. 

Consumers face:
  - Uncertainty in product selection, leading to wasted spending.
    - *>$70/user/year wasted on mismatched products spending*
    - *> 2 hours spent researching skincare products per product*
  - Lack of personalized solutions, resulting in allergic reactions or subpar results. 
    - *>30 hours/user/year wasted on trial-and-error per product*
  - Difficulty tracking skincare progress, leaving users guessing about long-term improvements.
    - Users lack clarity on long-term improvements.


***"The core problem is that skincare revolves around products rather than the unique needs of individual skin priorities."***

<br>




**The Vision** : Shifting Skincare to Skin Priorities.

Adaptive Blend is on a mission to transform skincare by making users’ skin priorities the focal point. 
 We aim to:
  - Empower users with personalized insights through Digital Skin Profiles built on first principles.
    - *Digital representations of users’ personalized skin priorities*
    - *Grounded in an initial 512 scientifically driven combinations of skin concerns, goals, and characteristics.*
  - Introduce an AI-powered Product Skincare Compatibility Analysis Tool (PSCT) for product evaluation.
    - *An AI agent that analyzes whether a given product aligns with a user’s Skin Profile*
  - Create a gamified and composable skincare system using NFT Skin Profiles for routine tracking and custom formulation creation.

The ultimate goal is to build a *Composable Skincare Ecosystem* that blends Real-World Applications with gamified, NFT-driven features, starting with compatibility analysis, routine tracking and evolving into a Crafting Station for custom formulations that users can digitally create, share and sell in a secondary marketplace.

<br>



**Integration into the Mintbase / NEAR Ecosystem:**
- **Mintbase :** For minting and managing NFT Skin Profiles.<!--Utilized for minting and managing NFTs representing users’ unique Skin Profiles. These NFTs facilitate composability and gamification in skincare routines while enabling traceable secondary sales of custom formulations.-->
- **Mintbase GraphQL Indexer:**  For querying NFT Metadata..
- **NEAR Protocol :** Serves as the foundational blockchain infrastructure for our Smart Contracts. 

<br>


**Why Our Team is Interested :**
- Our team is driven by the inefficiency of trial-and-error in skincare, a process that costs consumers both time and money while delivering inconsistent results. We envision a world where every individual has access to personalized skincare that adapt and evolve with their needs. By leveraging the Mintbase/NEAR ecosystem, we demonstrate how web3 technologies can merge digital innovation and tangible consumer benefits, setting a new standard for transparency and personalization in skincare.



### Project Details
<!--The Technical Implementation-->

**Step 1 : Building the Skin Priority Profiles**

The foundation of the ecosystem lies in creating unique Skin Profiles based on a user’s key inputs:

  - **Primary Concerns (up to 2):** Dryness, Dullness, Fine Lines & Wrinkles, Acne, Redness/Inflammation.
  - **Desired Results (up to 3):** Deep Hydration, Brightening, Graceful Aging, Clearing Breakouts, Soothing Irritation.
  - **Skin Type:** Dry, Normal, Combination, Oily.
  - **Sensitivity:** Yes/No.
  - **Allergies/Ingredient Sensitivities**.

<!--Each combination forms a Single Skin Profile, unique to both the individual and ecosystem, and minted as an NFT. This ensures the data is secure, portable, and composable within the Adaptive Blend ecosystem.-->

Each unique combination forms a Single Skin Profile, and minted as an NFT, ensuring secure and composable data for ongoing engagement in the Adaptive Blend ecosystem. These NFTs dynamically update as users interact with the platform, enabling:
- Personalized product compatibility analysis and recommendations.
- Routine tracking and performance evaluation.
- Gamified features and secondary marketplace opportunities for custom formulations.

- Technology Stack:
    - Smart Contracts: Rust, NEAR SDK, Mintbase API
    - Front End: React,  Svelte.
    - Hosting: AWS.
    - Interactive Comms stack - TikTok

We expect the teams to already have a solid idea about your project's expected final state. Therefore, we ask the teams to submit (where relevant):

- Mockups/designs of any UI components
- Data models / API specifications of the core functionality
- An overview of the technology stack to be used
- Documentation of core components, protocols, architecture, etc. to be deployed
- PoC/MVP or other relevant prior work or research on the topic
- What your project is _not_ or will _not_ provide or implement
  - This is a place for you to manage expectations and to clarify any limitations that might not be obvious

### Ecosystem Fit

<!--Help us locate your project in the Mintbase landscape and what problems it tries to solve by answering each of these questions: -->

- Where and how does your project fit into the ecosystem?
  - Built on Mintbase, driving web3 adoption through a novel use case.
  - Expanding Mintbase’s reach into wellness and personalized services.
  - Expand NFT use cases by introducing a groundbreaking application for skincare personalization.
  

- Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)?
  - Skincare consumers seeking personalized solutions.

- What need(s) does your project meet?
  - Enhancing transparency and user engagement through ownership.
  - Enabling data-driven improvements in skincare.
  - Fostering collective intelligence in personalized skincare.

- Are there any other projects similar to yours in the Mintbase / NEAR ecosystem?
  - No directly comparable projects within the Mintbase/NEAR ecosystem. Adaptive Blend leverages NFTs uniquely for wellness and personalization.

## Team 👥

### Team members

- Muriithi : Founder
- Additional team members TBD.

### Contact

- **Contact Name:** Carlos Muriithi
- **Contact Email:** c_muriithi@outlook.com
- **Website:**

### Legal Structure

- **Registered Address:** Address of your registered legal entity, if available. Please keep it in a single line. (e.g. High Street 1, London LK1 234, UK)
- **Registered Legal Entity:** Name of your registered legal entity, if available. (e.g. Duo Ltd.)

### Team's experience

- Web3 engineer and part-time security researcher on Immunefi.

- Relevant expertise in blockchain, NFTs, and user-centric application design.

<!--Please describe the team's relevant experience. If your project involves development work, we would appreciate it if you singled out a few interesting projects or contributions made by team members in the past. For research-related grants, references to past publications and projects in a related domain are helpful.

If anyone on your team has applied for a grant at the Mintbase previously, please list the name of the project and legal entity here.-->

### Team Code Repos

- https://github.com/Adaptive-Blend
- https://github.com/Adaptive-Blend/skin-profiles

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

- https://github.com/117l11


## Development Status :open_book:
**Research Conducted:**
- **User Input Combinations Designed:** Developed 512 unique profiles tailored to various skin concerns, goals, and characteristics.

- **Preliminary UI/UX Mockups Completed:** Initial designs for user interface and experience to ensure intuitive navigation and engagement.

- **Early Integration Tests:** Conducted successful trials utilizing Mintbase and NEAR tools to validate technical feasibility and compatibility.


If you've already started implementing your project or it is part of a larger repository, please provide a link and a description of the code here. In any case, please provide some documentation on the research and other work you have conducted before applying. This could be:

- links to improvement proposals or [RFPs](https://github.com/mintbase/Grants-Program/tree/master/rfp-proposal) (requests for proposal),
- academic publications relevant to the problem,
- links to your research diary, blog posts, articles, forum discussions or open GitHub issues,
- references to conversations you might have had related to this project with anyone from the Mintbase Foundation,
- previous interface iterations, such as mock-ups and wireframes.

## Development Roadmap :nut_and_bolt:

This section should break the development roadmap down into milestones and deliverables. To assist you in defining it, we have created a document with examples for some grant categories [here](../docs/grant_guidelines_per_category.md). Since these will be part of the agreement, it helps to describe _the functionality we should expect in as much detail as possible_, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Mintbase. We _recommend_ that teams structure their roadmap as 1 milestone ≈ 1 month.

For each milestone,

- make sure to include a specification of your software. _Treat it as a contract_; the level of detail must be enough to later verify that the software meets the specification.
- include the amount of funding requested _per milestone_.
- include documentation (tutorials, API specifications, architecture diagrams, whatever is appropriate) in each milestone. This ensures that the code can be widely used by the community.
- provide a test suite, comprising unit and integration tests, along with a guide on how to set up and run them.
- commit to providing Dockerfiles for the delivery of your project.
- indicate milestone duration as well as number of full-time employees working on each milestone.
- **Deliverables 0a-0d are mandatory for all milestones**, and deliverable 0e at least for the last one. If you do not intend to deliver one of these, please state a reason in its specification (e.g. Milestone X is research oriented and as such there is no code to test).

> :zap: If any of your deliverables is based on somebody else's work, make sure you work and publish _under the terms of the license_ of the respective project and that you **highlight this fact in your milestone documentation** and in the source code if applicable! **Teams that submit others' work without attributing it will be immediately terminated.**

### Overview

- **Total Estimated Duration:** 1 Month.
- **Full-Time Equivalent (FTE):**  1 FTE.
- **Total Costs:** $10,000.

### Milestone 1 Example — Implement Mintbase Modules

- **Estimated duration:** 2 weeks
- **FTE:**  1
- **Costs:** 8,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. | Documentation | Inline code documentation and a basic tutorial. |
| 0c. | Testing Guide | Unit tests covering core functions with setup instructions. |
| 0d. | Docker | Dockerfile(s) for testing functionality. |
| 0e. | Article | Publish a detailed article/workshop explaining project progress.
| 1. | Mintbase Module: Profile Creation | Create module for minting NFT Skin Profiles. |  
| 2. | Mintbase module: Y | We will create a Mintbase / NEAR module that will... |  
| 3. | Mintbase module: Z | We will create a Mintbase / NEAR module that will... |  
| 4. | NEAR chain integration | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |  


### Milestone 2 Example — Additional features

- **Estimated Duration:** 1 month
- **FTE:**  1
- **Costs:** 4,000 USD

...
## Future Plans

- Short-Term:

  - Improve consumer trust in skincare recommendations with actionable insights.
  - Establish PSCT as a trusted platform for skincare compatibility analysis.
  - Introduce routine tracking tools for skincare progress.

- Long-Term:

  - Expand into personalized skincare formulations with a gamified crafting station and formulations engine.
  - Build a data-driven ecosystem for innovation and development in skincare.

Please include here

- how you intend to use, enhance, promote and support your project in the short term, and
- the team's long-term plans and intentions in relation to it.


## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Mintbase Website / Medium / Twitter / Element / Announcement by another team / personal recommendation / etc.

Here you can also add any additional information that you think is relevant to this application but isn't part of it already, such as:

- Work you have already done.
- If there are any other teams who have already contributed (financially) to the project.
- Previous grants you may have applied for.

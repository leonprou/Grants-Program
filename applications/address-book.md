# Polymesh Association Grant Proposal


- **Project Name:** Address Book
- **Team Name:** Leon Prouger
- **Payment Address:** Polymesh (POLYX) payment address. Please also specify the currency.  
- **Level:** 1

## Project Overview :page_facing_up:

### Overview

The project introduces an address book to the Polymesh portal, allowing users to assign name tags to common contracts using either DID or address. This addition aims to enhance the overall user experience of the portal, making it easy to perform and oversee transactions with the help of the address book.

### Project Details

#### Address Book Page
Opening the address book page the user views  table of entities with the fiels: name tag, DID, address (or list of them), text note (maybe). The user can search add, remore or edit items. The entities are stored in the local storage. The user can also import and export the address book to CSV or JSON.


When accessing the address book page, user is presented with a table displaying address book entities with fields such as name tag, DID, and address (or a list of them). The available actions include adding, removing, or editing items within the address book. Users can conveniently search the address book, and there are options for exporting and importing items to and from CSV

The address book entities are stored in local storage, making it accessible within the user's browser environment only.

![Examplle mock](image.png)

#### Name tag funcionality

The name tag will be displayed alongside the user's DID or address on all portal screens. Additionally, when performing transfers and other actions, users can select a recipient by the name tag, while the associated DID is automatically fetched in the background.

![Mock](image-1.png)

* *The mocks are for presentation purposes only and do not represent the final version.*

### Ecosystem Fit

Address book enhace the user experience of the polymesh portal.

## Team :busts_in_silhouette:

### Team members

- Name of team leader
- Names of team members

### Contact

- **Contact Name:** Leon Prouger
- **Contact Email:** leonprou@gmail.com
- **Website:** https://github.com/leonprou

### Legal Structure

- **Registered Address:** 
- **Registered Legal Entity:**

### Team's experience

I have 10 years of engineering experience - JS, TS, Python, Rust. And 5 years working with blockchain - Solidity, EVM, Web3. I led the development of Fuse Network, and its Wallet as a service platform. I also was involed in the release of https://safe.fuse.io/.

### Team Code Repos

Provide the address of the github org and repos where the completed project will be hosted
- https://github.com/leonprou
- https://github.com/leonprou/polymesh-portal

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

- https://github.com/leonprou

### Team LinkedIn Profiles (if available)

- https://www.linkedin.com/in/leon-prouger-60646540/

## Development Status :open_book:

I have a PoC version that presents address book with a mock data.

## Development Roadmap :nut_and_bolt:

This section should break the development roadmap down into milestones and deliverables. To assist you in defining it, we have created a document with examples for some grant categories [here](../docs/grant_guidelines_per_category.md). Since these will be part of the agreement, it helps to describe _the functionality we should expect in as much detail as possible_, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Polymesh. We _recommend_ that teams structure their roadmap as 1 milestone ≈ 1 month. We also _recommend_ that you build up the scope of the project in a way that it can be completed in max 3 months. If the entirety of your project is going to take more than 3 months, please submit it's parts that can be completed in 3 months as one grant project. This helps us move forward quickly and deliver features quickly.

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

- **Total Estimated Duration:** Duration of the whole project (e.g. 2 months)
- **Full-Time Equivalent (FTE):**  Average number of full-time employees working on the project throughout its duration (see [Wikipedia](https://en.wikipedia.org/wiki/Full-time_equivalent), e.g. 2 FTE)
- **Total Costs:** Requested amount in USD for the whole project (e.g. 12,000 USD). Note that the acceptance criteria and additional benefits vary depending on the [level](../README.md#level_slider-levels) of funding requested. This and the costs for each milestone need to be provided in USD; since the grant is paid out in POLYX, the amount will be calculated according to the exchange rate at the time of payment.

### Milestone 1 Example — Implement Substrate Modules

- **Estimated duration:** 1 month
- **FTE:**  2
- **Costs:** 8,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will show how the new functionality works. |
| 0c. | Testing Guide | Core functions will be fully covered by unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0d. | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article**/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language and medium should reflect your target audience described above.)
| 1. | Feature: X | We will create a feature that will... (Please list the functionality that will be implemented for the first milestone) |  
| 2. | Feature: Y | We will create a feature that will... |  


### Milestone 2 Example — Additional features

- **Estimated Duration:** 1 month
- **FTE:**  1
- **Costs:** 4,000 USD

...


## Future Plans

Please include here

- how you intend to use, enhance, promote and support your project in the short term, and
- the team's long-term plans and intentions in relation to it.


## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Polymesh Website / Medium / Twitter / Discord / Newsletter / Announcement by another team / personal recommendation / etc.

Here you can also add any additional information that you think is relevant to this application but isn't part of it already, such as:

- Work you have already done.
- If there are any other teams who have already contributed (financially) to the project.
- Previous grants you may have applied for.

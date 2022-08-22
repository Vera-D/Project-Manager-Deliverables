# Project Management for Medical Devices

## Introduction

This repository contains links to Project Manager deliverables intended to describe my process, approach, and experience with software product development. Particular emphasis will be given to the development of medical device products. This repo was created to show some simple examples of requirement elicitation outputs for the development of software products. The examples include wireframes, storyboards, and journeymaps that were created using:

- AdobeXD
- Figma
- UXpresia

There are three types of products that are showcased in this repo. The [(Vitec)](./Vitec) project includes artifacts created for a software product that develops applications for hospitals and clinics. The RoboCivics project [(UXbotz)](./UXbotz) was intended to teach children about microplastics. The  [(Zealbots)](./ZealBots) that was developing an AI powered search engine for academics. 

While the three projects are not technically medical devices, the principles applied to the projects are simplified principles that would apply to a medical device software. 

## Starting a New Project

When starting a new project at an organization, familiarize yourself with the company's products life cycle. Organizations will vary in the stages and phases they recognize. As an example, a product life with 3 stages with sub phases is listed below.

### Stages
1. Pre-market
    1. Concept
    1. Feasibility
    1. Design and Development
    1. Verification
    1. Validation
    1. Clinical Investigation
1. On market
    1. Transfer
    1. Commercial Release
1. Post-market
    1. Service and Support
    1. Retirement

### Agile Software Development Tools

Within the life cycles of a medical device product a software team may decide to apply agile principles to product development. When managing a software product that interfaces with what would be considered "waterfall" methods, a PM must balance user needs from various stakeholders and communicate clearly to the develpment team through the requirements the stage of the system being developed. The use of projet management tools within the development teams product repository is beneficial to enhance comminication and project visibility. Examples of tools include:
- [issues in GitLab](https://docs.gitlab.com/ee/user/project/issues/)
- [work items in TFS](https://docs.microsoft.com/en-us/azure/devops/cross-service/manage-requirements?view=azure-devops&tabs=agile-process)
- [projects in GitHub](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)
- [Jira roadmap](https://www.atlassian.com/software/jira/features/roadmaps)


## Pertinent Reference Standards

International standadards are required aids that should be referenced throug all stages of a products life cycle. Common standards for software development of medical devices include:

- [ISO 62366 for Usability](https://www.iso.org/obp/ui/#iso:std:iec:62366:-1:ed-1:v1:en)
- [ISO 62304 for Softare Life Cycle](https://www.iso.org/obp/ui/#iso:std:iec:62304:ed-1:v1:en)
- [ISO 13485 for Medical Device Quality Management Systems](https://www.iso.org/obp/ui/#iso:std:iso:13485:ed-3:v1:en)
- [ISO 14971 for Risk Management](https://www.iso.org/obp/ui/#iso:std:iso:13485:ed-3:v1:en)
- [ISO 16086 for System and Software Life Cycle Risk Management](https://www.iso.org/obp/ui/#iso:std:iso-iec-ieee:16085:ed-1:v1:en)
- [IEC/TR 80002-1 for applying Risk Management to Medical Device Software](https://www.iso.org/obp/ui/#iso:std:iec:tr:80002:-1:ed-1:v1:en)
- [ISO 27001 for IT, Cybersecurity and Privacy Protection](https://www.iso.org/obp/ui/#iso:std:iso-iec:27013:ed-3:v1:en)

## User Needs and Requirements

Requirenments management is a continual process. Products are built for users and a common acronym thrown around by product teams is the minimum lovable product (MLP) or minimum viable product (MVP). The MLP or MVP refers to a version of a product that includes the most important *User Needs* that will delight when using the product [1](prodcuct-school). This version of the product will allow the organization to collect actionable learnings from formative usability tests.

All products have users and *User Needs* are a special type of requirement that describes what the users want from the product. *User Needs* may be based on directly solicited information or indirectly collected information conveyed as a *User Need*. Indirect information may be provided by company stakeholders that represent the user. If products are intended to be used by the internal team, an internal representative should be included to provide input on *User Needs.*  

Software requirements can be part of the User Needs or they can be lower level requirements that should trace to a User Need. Software requirements can vary by organization. Certain teams that have adopted agile frameworks may be documenting requirements as *Initiatives*, *Epics* and *User Stories*. Furthermore, test teams may enforce the use of syntax to standardize requirements. One such example includes [Gherkin syntax](https://cucumber.io/docs/gherkin/reference/).

---
[prodcuct-school]: https://productschool.com/blog/product-management-2/minimum-lovable-product/ "product school"

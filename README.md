# Recruitment

Welcome to Recruitment

The purpose of this repository is to provide an assignment that will highlight the strengths required by a team member in our cloud effort workforce.

## Table of contents

- [General Information](#general-information)
- [Assignment](#assignment)
    - [Current scenario](#current-scenario)
    - [Transformation and Migration to the Public Cloud](#transformation-and-migration-to-the-public-cloud)
- [Deliverables](#deliverables)
- [Links](#links)

## General Information

This assignment is meant to challenge the potential applicant in the complete spectrum of designing a solution and delivering an environment in the public cloud using Infrastructure as Code (IaC).

Please be aware of the fact that we are not only looking at the actual deliverables but also the process followed to achieve these results. *The presentation of the results is of equal importance as the actual results.*

## Assignment

### Current scenario

You have participated in a meeting with a client to assess their strategy to migrate to the public cloud. They are currently hosting a customer facing web application on their premises in an environment based on a NodeJS application behind an NGINX reverse proxy. 

They are utilizing a MongoDB cluster for storing data relevant to the application. As a result of their processes, they are generating lots of PDF files for which they utilize local storage. The finance team needs to have access to these files via FTP. All the above services are hosted on several virtual machines.

Finally, the customer currently has 3 environments, namely Test, Acceptance and Production. They wish to keep the same environments in Azure, while following best practices in terms of workload isolation.

### Transformation and Migration to the Public Cloud
The customer is interested in migrating the complete environment to the Public Cloud. They want to leverage within Azure the maximum potential availability from a design perspective and they want the proposed solution to reflect this. The region of choice is West Europe. They are willing to make small modifications regarding to how the application is deployed to the target infrastructure as long as the impact in terms of development technology is minimum and the benefits of the public cloud in terms of scalability substantial. They are not willing to change database technology as they have invested a lot of time in optimizing their MongoDB queries.

You have undertaken the task to design the future state of this environment in the public cloud. The solution needs to:
* be highly available, scalable and flexible.
* utilize only native Azure Services and Products.
* deployable completely using Infrastructure as Code (IaC) from a single codebase.

Any further assumptions that you need to make are welcome as long as they are documented accordingly.

## Deliverables

Please provide the following:
1. An architectural design of the solution. Please use only the latest [Azure Architecture Icons](https://docs.microsoft.com/en-us/azure/architecture/icons/) and export the solution in PDF.
2. An IaC project/codebase using Terraform code for an MVP demo of the solution.
3. A link to a publicly accessible git repository containing all the above.

## Links

- [Draw.io](https://www.draw.io/)
- [Microsoft Azure Cloud Design Patterns](https://docs.microsoft.com/en-us/azure/architecture/patterns/)
- [Introduction to GitHub](https://github.com/skills/introduction-to-github)

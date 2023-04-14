```
*************************************************************
*                                                           *
*       ________  __    __  ________    ____       ______   *
*      /_/_/_/_/ /_/   /_/ /_/_/_/_/  _/_/_/_   __/_/_/_/   *
*     /_/_____  /_/___/_/    /_/    /_/___/_/  /_/          *
*    /_/_/_/_/   /_/_/_/    /_/    /_/_/_/_/  /_/           *
*   ______/_/       /_/    /_/    /_/   /_/  /_/____        *
*  /_/_/_/_/       /_/    /_/    /_/   /_/    /_/_/_/ . io  *
*                                                           *
*************************************************************
```

# Sytac DevOps/Cloud Engineering Technical Assignment

We would like to extend our warmest congratulations on making it this far in the interview process with Sytac for the DevOps/Cloud Engineer role. 
The role of a DevOps/Cloud engineer is critical in today's fast-paced technology environment. 
With the increasing use of cloud-based solutions, these engineers are responsible for developing and maintaining the infrastructure, tools, and processes needed to deploy software quickly and reliably. 
In this technical assessment, we will evaluate your skills and experience in these areas, as well as your ability to communicate technical information to non-technical stakeholders.

We are testing a few skills including the following:
- Architecture design
- Ability to present solutions
- Engineering skills
- Coding Standards
- Documentation
- Security

A few notes: Please try to deliver the best solution you can, given the time that you have
available. Concentrate on the components that you think matter most. If there are any parts
of this assessment that are not clear, please do not hesitate to reach out to us for
clarification.

Study the assignment, create your own implementation and prepare to demo/explain it in the
interview. The goal is not to develop an exhaustive and perfect solution with all the bells and
whistles, but to reflect your experience and approach to this assignment. However, it does
need to fulfill the acceptance criteria. Please also keep the “Business Case” in mind while
designing your solution.

## 1/3 Assignment for the technical interview
### Deliverables
- All the code related to your implementation, in a form that is deployable by the Interviewer

- Comprehensive and understandable documentation of your solution

- Presentation of your solution during the following technical interview


### Acceptance Criteria for the Implementation
- The application should be able to scale depending on the load

- The application must return consistent results across sessions

- The implementation should be built in a resilient manner

- Observability must be taken into account when implementing the solution

- The deployment of the application and environment should be automated

##2/3 Assignment for the technical interview
### Business Case
The client DigiGeld B.V. currently operates their website on an outdated platform hosted in their own data center. 
They are getting ready to launch a new product that will disrupt the market and wish to enhance their social media presence through a blogging platform. 
As part of their modernization process, they have selected Ghost Blog platform for their marketing efforts.

The customer anticipates an increase in traffic during the new product launch or marketing campaigns, and they do not know the amount of traffic they will receive. 
The solution should be able to handle traffic spikes, with the potential for up to four times the normal load. 
It is crucial that the platform remains available, even if a significant geographical failure occurs. 
Disaster recovery capabilities are also necessary in case of a regional failure.

DigiGeld B.V. intends to have five DevOps teams working on the project, as Ghost will play a critical role in their marketing efforts. 
The teams will need to release new versions of the application multiple times a day, without any downtime. 
The customer also requires several separate environments to support their development efforts.

DigiGeld B.V.'s operations team will maintain the environment and will require tools to assist with visualizing and debugging the environment's state. 
As the website will be exposed to the internet, the security team needs visibility into the platform and its operations. 
Additionally, the customer has requested a serverless function to delete all posts at once.

As a cloud/devops engineer, your task is to deliver a Proof of Concept for DigiGeld B.V.'s new website. 
You must design and implement a solution architecture that meets the aforementioned requirements on the major public cloud platform (AWS, Azure) for which you are interviewing. 
The solution should be cost-effective and easy to maintain/develop in the future

## 3/3 Assignment for the technical interview
### Provided Resources
The Ghost platform and related documentation is available on ghost.org/docs. There are
multiple ways to install Ghost and they all have the same functionality.

### Environment
We kindly ask that you utilize your personal environment/account in the appropriate cloud provider, as unfortunately we are unable to provide one for you. 
Most major cloud providers offer a free-tier option, which should allow you to complete the assignment without incurring any significant expenses.
# Enablement Playbook
Prescriptive approach to enabling people on PCF

### Technical Enablement

#### [No Rocket Scientist Required - Developing +14,000 Message p/second IOT Systems](https://www.youtube.com/watch?v=dzdytNrMafM&list=PLAdzTan_eSPRoRJGArqipaN_r5K74o31H&index=17)
A great discussion of scaling up a 14,000 message per second system IoT system  


### CF Summit 2017 Talks
For a complete list of our customer stories from CF Summit 2017 visit  
https://www.youtube.com/playlist?list=PLAdzTan_eSPRoRJGArqipaN_r5K74o31H

## Technical Material to get Started
For your first hands-on taste of working with Pivotal Cloud Foundry try our 15 minute online tutorial at:
https://pivotal.io/platform/pcf-tutorials/getting-started-with-pivotal-cloud-foundry/introduction

Once you are ready for more sign-up for the Pivotal Partner Portal at: http://partners.pivotal.io
It has lots of great material including:
- Free Developer Self Study Classes on PCF and Spring Boot
- Technical material like reference architectures etc.
- an FAQ that's great for helping with proposals
- Sales Plays and Collateral such as .ppt slides

Here is a short video that shows you how to setup your free account on the Pivotal Partner Portal.  
https://youtu.be/xQdGs2BYZDY


## Environments you can use for hands-on Development work with Pivotal Cloud Foundry
Your team members have 4 main options for environments to develop applications on Pivotal Cloud Foundry.  The table below summarizes those options.

| |PCF Dev installed on your laptop| Pivotal Web Services | Your Internal Sandbox | Deploy your own PCF to AWS/GCP/Azure|
| --- | --- | --- |--- | --- |
| Start today | √ | √ | | |
| Cost | Zero | 1st Month Free / ~$10-$20 per month per AI| Zero | $100 - $150 per month in cloud charges |
| Operator / Administrator experience | | | | √ |

Here is a more complete discussion of the various options:
### PCF Dev
PCF Dev provides a PCF developer experience on a developer’s local machine.  It is free to download from [https://pivotal.io/pcf-dev](https://pivotal.io/pcf-dev) and you can start pushing apps right away using your local machine.
This is one of the fastest ways for developers to get started.
#### Advantages:
*	Start today
*	No cost solution
*	Supports common services including: Spring Cloud Services, MySQL, Rabbit, Redis
#### Disadvantages:
*	Limited to local machine
*	No Administrator / Operator experience available.  This is really a stripped-down, single VM Cloud Foundry for developers.


###  Pivotal Web Services
Pivotal Web Services is Pivotal’s hosted Cloud Foundry environment where pay for the time they use.  It is a great way to get started becaue you start with $87 of credit, which is roughly 60 days of service.  After the free credit is consumed a small applicaton instances cost ~$10-$20 per month.

#### Advantages:
*	Start today
*	Low cost solution
*	Centralized billing - one org with multiple spaces results in centralized billing
*	Lots of services
#### Disadvantages:
*	Does not currently support Spring Cloud Services or Spring Cloud Data Flow (planned for Q42016)
*	Not the same services that a customer’s PCF may have.
*	No Administrator / Operator experience - it’s a shared service that doesn’t have admin capabilities.

### Deploy your own PCF to AWS/GCP/Azure
It is possible to deploy your own full installaiton of PCF into one of the Cloud Providers such a AWS, GCP, or Azure for non-commercial, non-revenue generating activities.  Your project team will be responsible for the cost of the cloud infrastructure which typically costs about $100 - $150 per day.  If you are interested in this option please contact your Pivotal leads for more details.
#### Advantages:

*	Supports everything customers use: Spring Cloud Services, MySQL, Rabbit, Redis
*	Provides Administrator / Operation experience
*	Flexible configuration - can scale up / scale down based on your needs.
*	No Permanent costs like dedicated hardware
#### Disadvantages:
*	Estimated cost:  $100 - $150 per day in Cloud Provider charges.
*  	Setup requires full installation of PCF (average first time install takes a experienced Linux admin ~3 days)

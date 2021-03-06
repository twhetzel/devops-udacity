# [DevOps P0] Improvement Plan: Submission Template

Use this template to generate your own submission for the project. The template is already in Markdown and has space for you to provide your answers. Read the [Project Description](https://github.com/udacity/Project-Descriptions-for-Review/blob/master/DevOps/P0/P0_Fictional_Company.md) and the [Sample Submission](https://github.com/udacity/Project-Descriptions-for-Review/blob/9d7b8dd2c0d6d23fe5ecf768351b68184835a443/DevOps/P0/P0_Sample_Submission.md) for details and suggestions about how to complete your answers. Delete this paragraph before submitting your project. 

## Organization Snapshot

#### Provide a brief description of your company and your team's role in it.

**April 22, 2016** 

Twisted Threads is an on demand T-shirt company. The company is 10 years old and currently has over 200 employees. The company properties include one warehouse, serveral brick-and-mortar stores, and an e-commerce site. Our team is involved in software development for the company. The IT department has 25 people. My team of 5 is part of the IT department and responsible for running the e-commerce site.

#### What is the core function of your team? What is the core function of your company or organizational unit? Is the core function of your team well aligned with the function of the larger organizational unit or the company as a whole?

**April 22, 2016** 

* Team Goal: Provide an online T-shirt store for customers
* Organizational Unit: Manage the customer facing web site and internal data inventory system. 
* Company Goal: Sell customized T-shirts on demand


#### Who are your team's customers? Are they internal or external? What do they need?

**April 22, 2016** 

* External customer: Users of the online store that want to purchase customized T-shirts
* Internal customer: Company product team that requests new features
* Internal customer: Company users of the separate inventory systems for each physical store and warehouse

#### What is the current flow of software development and delivery in your team? List the main steps and whether they are manual or automated. 

**April 22, 2016** 

* Bugs and Feature requests are reviewed weekly and new items are prioritized whether they need to be in this months release or a future release (manual)
* Code gets written based on priorities, although sometimes a developer works on their own project that is not in the tracker (manual)
* Code is checked into the repository and the tracker item status is updated to Ready for QA (manual)
* Code updates are reviewed weekly and the tracker item status is either updated to Ready for Release or In Progress and turned back to the developer for more work (manual). Some data quality checks are verfied programmaticaly (automated).
* A few days prior to release, a code freeze occurs and only fixes for current items scheduled for the release are worked on (manual)
* New releases are pushed on Tuesday (manual)
* If there are enough features to announce to customers, the announcement is sent out on Thursday after allowing the new release to run in production for a few days to catch any major issues (manual)

#### What are all the teams or people that are involved in a product release, from start to finish? 

**April 22, 2016** 

* Project manager: 1 manager who does some coding, analysis of logs.
* Developers: 1 front end, 1 back end, and 1 full stack developer.
* QA: 1 dedicated person.
* Marketing/Sales
* Design: Same team handles design for both website and shirts
* Warehouse team: Needs daily report of what to ship where.
* Customer service: Needs to be able to look up sales if a customer calls or emails with problems around an online order.

#### How is communication handled in your organization? 

**April 22, 2016** 

We have weekly sit down meetings (Developers + PM + QA) and a week prior to release there are daily standup meetings (Developers + PM) for status check-ins. 

## Quantitative Ratings

#### How satisfied are you with how other teams work and support the work that you do? (Scale: 1-10, 10 is best)

**April 22, 2016** 

Rating: 6

#### Do deployments go smoothly? (Scale: 1-10, 10 is best)

**April 22, 2016** 

Rating: 7. Generally deployments go smoothly. We did have a data quality issue, but have since implemented an automated check that is run before and after deployment.

#### Do you have planned downtime for system upgrades or maintenance? 

**April 22, 2016** 

Yes, it is generally as needed based on feedback from Ops.

#### How much time does it take to set up the environment for a new project? 

**April 22, 2016** 

About 1 day if it is not a release week or the sysadmin is not busy with other projects.

#### How often do you deploy to production? 

**April 22, 2016** 

* Currently: 1/month
* Patch releases occur throughout the month as needed to fix any severe issues resulting from the release, usually 1 or 2. 

#### How long does it take to deploy a new feature or bugfix from "code checked in to repository" to "feature is live to customers"? 

**April 22, 2016** 

1-3 weeks

#### How easy is it to deploy a new feature or bugfix from "code checked in to repository" to "feature is live to customers"? (Scale: 1-10, 10 is best)

**April 22, 2016** 

Rating: 8. While the releases occur monthly vs. weekly, pushing the release to production is generally smooth. 

#### How would you rate the quality of your software? (Scale: 1-10, 10 is best)

**April 22, 2016** 

Rating: 8

#### How easy it is to test your software? (Scale: 1-10, 10 is best)

**April 22, 2016** 

Rating: 6. The software is easy to test, but most of the process is manual.

#### How satisfied are your customers? (Scale: 1-10, 10 is best) 

**April 22, 2016** 

Rating: 8

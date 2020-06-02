# Information System Development Methodologies Assignment
Harrison Kellick (13196997) | Jennifer Luu (13591502) | Kenson Lang (13554148) | Alexander An (13190677)

__Link To Video Presentation:__[Video Presentation Link](https://www.youtube.com/watch?v=leCHLGkw7wQ&feature=youtu.be)

## Introduction
Our project documents the process and methodologies our group used to develop and information system for the provided case study. We have developed a 2000 word business report and recorded presentation to demonstrate our journey. The report has been developed in Markdown format using version control in Github. We have included all resulting documentation from our Design Thinking and Agile methodology, including UML workproducts and models. Within Github, we have used tools such as commits, pull requests, issues and projects to record our collaborative progression.

## Objectives 
The aim of this project is to develop an information system for a travel company to optimise their call management and in doing so, improve customer experience and increase their potential for sale.
It will create an effective and efficient information system that will be able to appropriately match relationship managers and customers based on the relationship managers skill and customers profile. Customers will be able to effortlessly find possible products that are suited to their needs and wants, increasing the probability of product purchasing. Relationship managers will be able to tailor their approach to suit the customers preferences and identify the customers target market, allowing them to strengthen their sales pitch. 
The system will effectively optimise and improve the call experience overall.

For example, the system will match a customer wishing to purchase a travel package for Europe to a well informed relationship manager aware of the destination, traditions, culture and travel packages. 

## Problem Definition 
Currently there is no system that is able to effectively connect customers to suitable relationship managers. This leads to unproductive sales pitches and thus lower the potential for sales as relationship managers are not properly matched to customer profiles. There is also currently no method to gauge the customer's travel preferences prior to reaching a relationship manager meaning that customers may be left to wait a long periods of time for service as traffic is not monitored and optimised for greatest efficacy. Ultimately,  customers are likely to be matched with any relationship manager who is currently available for call instead of one who is well informed about their desired travel destination. 

## Stakeholders 
This project has 3 main stakeholders, they are the major travel company, relationship managers and customers.

### Empathy Maps
1. Major Travel Company
![Empathy Map for Major Travel Company](https://github.com/kellickharry/ISDM/blob/master/Major-Travel-Company-Empathy-Map.PNG)
2. Relationship Managers
![Empathy Map for Relationship Managers](https://github.com/kellickharry/ISDM/blob/master/RM-Empathy-Map.PNG)
3. Customer
![Empathy Map for Customers](https://github.com/kellickharry/ISDM/blob/master/Customer-Empathy-Map.PNG)

### User Stories
The user stories written from the perspective each of the 3 stakeholders. 

__*Major Travel Company*__
* As a major travel company, I want to develop an information system so that I can improve the operation of our in-house call management centre (CMC).
* As a major travel company, I want the system to automatically dial numbers according to a generated customer target list, so that I can target the best potential buyers. 
* As a major travel company, I want a call routing and distribution routine so that inbound call costs are minimised by reducing per-call handling time.
* As a major travel company, I want to redirect customers to an Interactive Voice Response during busy time, so that I can manage customers the best way possible while maintaining good customer service.

__*Relationship Manager*__
* As a Relationship Manager (RM), I want the system to provide assistance in serving end-customers (or potential customers) and match end-customers according skill and customers profiles, so that there is improved call routing and dynamic call flow control for both inbound and outbound calls.
* As a Relationship Manager (RM), I want a supporting tool to create customer profiles, so that I can segment customers into social and cultural segments according to their postcodes and surnames.
* As a Relationship Manager (RM), I want the system to display buyer details and provide me with guidelines and a script so that I can provide an improved service to the end-customer.
* As a Relationship Manager (RM), I want a calculated customer skill score based on previous call durations and customer profiles, so that I can prioritise customers most likely to purchase.

__*Customer*__
* As a customer, I want to be matched with an employee based on their performance and product knowledge, so that I receive the best experience for my booking.
* As a customer, I want shorter waiting periods when on hold, so that I don’t feel like I am wasting my time.

### POV Statements
The POV statements written from the perspective each of the 3 stakeholders. 

__*Major Travel Company*__
User | Need | Insight 
-----|------|--------
A major travel company lacking useable technology | The development of a suitable information system specific to the companies needs | The company will improve many aspects of their business with a new system, namely the "operation of our in-house call management centre (CMC)."
An employee of a major travel company, who's job is to contact new potential customers | A system which automatically dials numbers according to a generated customer target list | Natural human bias and decison making isn't working for the current business model 
A major travel company system developer | A call routing and distribution routine | Implementing routine into the business will reduce costs
An employee who has worked during the busiest of times at the company | To be able to redirect customers to an Interactive Voice Respinse during busy times | Employees want to maintain the best customer service no matter the situation, however sometimes get overwhelmed by the volume of work at one time

__*Relationship Manager*__
User | Need | Insight 
-----|------|--------
A Relationship Manager (RM) seeking a better working experience for both myself and my customers | Assistance in serving end-customers or potential customer, and matching end-customer according to skill and customer profiles | The RMs want this improved experience for both themselves and customers, as these changes would improve call routing and the dynamic call flow control
An RM struggling with the current tools in place to develop customer profiles | A supporting tool which creates customer profiles | A tool like this would provide the ability to segment customers socially and culturally, or by postcode and surnames
A Relationship Manager wanting to know the perfect thing to say to customers | A system which displays customer details and provides a guideline or script as to what to say | This would improve customer service
A Relationship Manager | Customer skill scores to be calculated, this could be based on previous call durations and customer profiles | RMs want to prioritise the customers most likely to purchase

__*Customer*__
User | Need | Insight 
-----|------|--------
Customer | To be matched with employees who have the best performance and product knowledge | Customers want the best custoer experience possible
Customer | Shorter waiting periods when I am on hold | Customers don't want to feel like they are wasting their time

### How Might We Statements
The following "How Might We" statements are based off the POV statements.
* How might we improve the travel company business with the implementation of a new information system?
* How might we ensure the successful integration of a new system?
* How might we train employees to use the new system?
* How might we notify customers of the changes, and respond to their comments and questions?
* How might we develop the sytem in a way that doesn't affect the customers negatively?
* How might we manipulate employees pre-existing skills within the new system to make sure they aren't useless?
* How might we account for natural human bias within an automated information system?
* How might we reduce costs through the use of this system?
* How might we account for customers responses to an Interactive Voice Response system?
* How might we ensure minimal holding times for customers within the new system, so as to not waste their time?
* How might we create a better working experience for employees?
* How might we use a Customer Profiling tool to this best of its ability?

## Approach
Our approach revolved around converting the travel company’s needs into demand, which will improve their business. Design Thinking encourages us to take a customer-oriented approach using agile decision making. In this case study, we recognise the travel company, their relationship managers and their customers as key stakeholders. When looking to remove the stakeholders pain points, the first step is to empathize with the stakeholders. By placing ourselves in the users’ shoes, we can pinpoint their wants, needs and struggles. Key tools we used to do this were Empathy Maps for each stakeholder, User Stories and How Might We’s.

Next, we look to define the problems that we have identified. We believe it is important to know our stakeholders, and their needs, in order to properly define their problems and work towards a solution. This can be done through re-framing the problem(s). By using Point of View statements, we were able to clearly define the problems of each of our stakeholders.

The next stage of our approach follows into the Ideation stage. In this stage, we develop as many ideas for our previously identified problems as possible. At this point of the approach any idea is written down, which we later collate and refine into a feasible solution. Similarly, we use exercises like Brainstorming and Worst Possible Idea to look for more ways to reframe the problems. Following on from this, collating and refining ideas based on potential and through voting revels our most feasible solutions we can then use to prototype.

By prototyping our solutions, we can develop inexpensive, shareable products to help use further identify the best solutions. These can be shown to stakeholders to seek feedback, looking for acceptance, improvement or rejection. This stage also allows us to have a better perspective on real world users and their behaviour. With these products, we can ask questions like, “Would people use it?”, “Would people buy it?”, “Will it be easier for them to use?” and “Will the design be simple and novel?”

The final stage of our Design Thinking approach is iterative testing. We use our prototypes to redefine problems we previously defined and develop greater understanding of the users, their condition, thoughts, behaviour and feelings. As this is an iterative cycle, we can alter and refine in order to rule out problem solutions and therefore derive deeper understanding of our prototypes and ideas, users and their problems.

## Choosen Agile Methodology & Associated Activities 
The agile methodology choosen for this project is SCRUM. SCRUM is an agile process that  focuses on delivering te business value in the shortest time possible and does so through rapid and repeated production of working software. It emphasises accountability, team work and agility, it looks as software development as a complicated and unpredictable process. Within SCRUM there are many different structures such as ceremonies, roles and artefacts all of which play a vital role

For this project the following SCRUM structures have been modified to accomodate for the project requirements. 

The following modifications have been made:
* Sprint planning is no longer a stand-alone formal ceremony, it has been incorporated into daily sprint for better time efficiency.
* Daily sprint/stand-up has been replaced with a weekly team meeting hosted over Zoom.
* Sprint review and retrospective are no longer a formal ceremonies, but continual processes of improvement.It is informally conducted through weekly team meetings, tutorial classes or through messages.

Team structure has been appropriated with the removal of the need for a product owner and scrum master. The team operates as a unit of self organising individuals whose roles and responsibilities can change situationally. 

The sprint duration has been made 1-week to better accomodate for the project timeline as well as the expected progress that was outlined in the project plan and alignment document. 

Although SCRUM structured have been modified, the fundamental methodology and ideaology of SCRUM is still implemented as the team is actively working to produce workproducts and artefacts in an agile manner.

As part of the project, the team is working collaboratively through GitHub. Each team member has their own fork, each fork should have a master and a develop branch. Team members should work on the develop branch until a change is finalised, once finalised the main respository can be updated. Upon updating the main repository, team members should open a pull request with a meaningful name, assign the pull request to themselves, request reviews from the team and linked to appropriate issue/s. If the pull request has been reviewed by at least one team member, the pull request can be merged and closed. Commits should also have meaningful names that makes it easier to trace back through the change history. 

## Assumptions 
Below are the assumptions made throughout the project. 
* Relationship Managers
    * It is assumed that Relationship Managers are all around the same level in the management hierarchy and are not high up in management. This assumption is made as the concerns raised in the empathy map for Relationship Managers illustrates those concerns held by employees following the implementation of the proposed information system whereas managers may be more focused on the return on investment and profits garnered by the proposed system.
    * The empathy map for Relationship Managers also assumes that business is taking place during a normal situation e.g. not during the COVID-19 pandemic, and thus does not aim to address any concerns or issues presented by out of the ordinary situations. 
* Customers 
    * Customers are not quarantined and are free to travel where they choose.
    * Customers do not hang up once they call the centre.
    * Customers are aware of their own score between 1-10.
    * Customers have to have their information registered in the database prior to purchasing a product.
    * All customers are matched with an employee based on their product knowledge and availability.	
    * The demographics of the Customers are not considered in their score.
    * Only inbound customer calls are considered (for empathy map).
    * Customers will hand up after 20 minutes of waiting. 

* CMC System - Information System
    * During outbound calls, if a custmer does not pick up their phone, the information system will automatically search for a new target customer and proceed to call them instead.
    * For outbound calls, the information system will not attempt to contact a target customer twice if the customer does not pick up the call. This will only occur if the target customer forms part of the new target list formulated by the information system.
    * The profile tool uses segments customers by their postcode and surname.


## Proposed Workproducts & Models
The proposed workproducts and models for this project are use case diagrams, activity diagrams, a class diagram and collaborative diagrams. 

### Use Case Diagrams
__*Inbound Calls from Customers*__
![Use Case Diagram for Inbound Calls](https://github.com/kellickharry/ISDM/blob/master/Inbound%20Calls%20Customers%20Use%20Case%20Diagram.png)

__*Outbound Calls from CMC System (Information System)*__
![Use Case Diagram for Outbound Calls](https://github.com/kellickharry/ISDM/blob/master/Outbound%20Calls%20Use%20Case%20Diagram.png)

### Activity Diagrams
__*Inbound Calls from Customers*__
![Activity Diagram for Inbound Calls](https://github.com/kellickharry/ISDM/blob/master/Outbound%20Calls%20v3.png)

__*Outbound Calls from CMC System (Information System)*__
![Activity Diagram for Outbound Calls](https://github.com/kellickharry/ISDM/blob/master/Outbound%20Calls%20v3.png)

__*Employee Onboarding to CMC System*__
![Activity Diagram for Employee Onboarding](https://github.com/kellickharry/ISDM/blob/master/Employee%20v3.png)

### Class Diagram
![Class Diagram for CMC System](https://github.com/kellickharry/ISDM/blob/master/Relationship%20Diagram%20v2.png)

### Collaboration Diagrams
__*Inbound Calls*__
![Collaboration Diagram for Inbound Calls](https://github.com/kellickharry/ISDM/blob/master/Customer%20Collaboration%20Diagram.png)

__*Outbound Calls*__
![Collaboration Diagram for Outbound Calls](https://github.com/kellickharry/ISDM/blob/master/Collaboration%20Diagram%20-%20Outbound%20Calls%20-%20Page%202.png)

## Benefits 
There are various advantages that arise whilst following the success of the information system, one being that calls will be more cost efficient because numbers are dialed automatically by the system rather than hiring specific employees to do so and thus, the quantity of these calls will significantly improve. This improvement in the quantity calls will undoubtedly enhance the level of customer satisfaction, as they are no longer waiting long periods in the queue and hence, will be less likely to hang up. Additionally, another advantage includes being able to easily access customer details as it enables employees to utilise the script generated by the system to interact with customers in a customised format and thereby, heavily increasing the chances that the customer is willing to purchase a holiday package. Resultantly, due to this customised style of serving customers, profits and sales are bound to improve exponentially.

Furthermore, other advantages of a successful information system to the call center include being able to share and process information faster across different departments. By being able to process information faster and in a clearer manner, customer data and information is less likely to be compromised and mixed up with other customers and hence, leads to a strong security framework. Another advantage, includes being able to prioritise customers who are likely to purchase again by pairing them with the highest rated managers. As such, by being able to prioritise these customers further increases the chance that they are going to purchase a holiday package and thus, increases company profit.

## Potential Disadvantages If Information System Fails 
The largest impact that will occur if the project fails would be a loss of resources and wasted time spent whilst trying to implement that project. This loss in resources and capital, would most likely result in a cut in operational expenses and thus, reduce the efficiency of serving customers which would lead to a significant decrease in the level of customer satisfaction. Stemming from this increasing customer dissatisfaction, the company should expect some damages to their reputation for failing to meet customer needs such as processing their travelling applications. Resulting from a deteriorating reputation, the company is bound to experience lower levels of profits and may potentially lose the trust of business partners.

Another product of a failing project would be the potential decline of employees' motivation levels as they are less likely to work efficiently due to having a decreased income from reduced company expenses. This declining motivation is most definitely bound to promote a careless work habit which may potentially cause a breach of privacy and a leakage of customer information. Thus, leading to customers losing confidence in the trustworthiness and credibility of the company.

## Summary
Overall, our group successfully implemented information system development methodologies, and applied them to the case study. In doing so, we produced a business report and recorded presentation, highlighted by our Design Thinking and Agile methodology, and UML diagrams. We used Github to our benefit, taking full advantage of the tools provided to develop a backlog of tasks and implement sprints, as well as ensuring the group work was divided equally.  

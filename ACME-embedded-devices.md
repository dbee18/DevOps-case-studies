# ACME Appliances

ACME Appliances is a large enterprise with thousands of employees. ACME develops and sells home appliances such as refrigerators,
washing machines, dish washers, tumble driers and the like.

ACME is an old corporation that the last twenty years has had increasing software needs and capabilities.

## The Team

This case focuses on the R&D department, maintaining and developing the software that goes onto the hardware.
The department has around 200 developers, most in Europe, but most of the testing capabilities resides with the Indian team.

The department has different teams centered around the specific products. One team handles laundry machines, while another handles freezers and refrigerators and so on.

One of the teams is responsible for building at platform package that interacts with the hardware at the lowest level to allow the product teams to focus more on their products.

## The product

The software is composed of C code fragmented into components. The developers would like to transition to C++, but management deems C++ too difficult for the developers,
and the software is working as is. There bare many custom definitions and types used that make the C variant they are using non-standard.

Automated Testing and Continuous Delivery is implemented throughout the department.
A Continuous Delivery team is maintaining the build infrastructure and pipelines for the developers. The developers do not feel ownership over their pipelines, and as such they
are seen more as a nuisance than a valuable tool.
Automated tests work well at the unit and component integration level, but full end to end tests are difficult to implement and maintain as this needs to run on physical hardware.
The department maintains physical pcs connected to test-equipment and part of the automation tool chain. In order to maintain these test machines an administrative account 
is used, that has access to everything. The password to this account is shared between all team members. It happens that people sometimes use this account rather than their
personal account, because it is easier.

The Continuous Delivery teams has migrated most of the teams to Git, but one team refuses to move from SVN and doesn't see the value in this.

There is a well-defined agile process defined in Word documents in SharePoint. Developers feel they go to too many meetings that do not bring value.
Teams develop in three week sprints, and release every two sprints.
The Scrum teams are highly variant in velocity. Tasks are often overrunning their estimates. The organization is starting to look into SAFe.
Tasks are usually broken down into steps that should take less than a week to complete.

There is a complex process due to ISO-certifications. Bug handling workflows has a lot of information required and many states with transitions between them.
These complex workflows has been implemented in Jira. They host their Jira locally, it has grown huge over time, and it is now difficult to change workflows or projects as they are all intertwined. Developers hate using Jira, as there are many required fields and it takes a lot of time to move and create tasks.
As a consequence of this a lot of ad-hoc work is not tracked anywhere.

Customer contact is handled through installation engineers, support and sales staff. Engineers do not see a bug before it is created in Jira.
As there is physical hardware, with firmware that can't be updated over the air, the department has to maintain a lot of versions of their software simultaneously.
Contractually they are mandated to support any given version for ten years.

ACME has a classical IT organization responsible for computers, phones, outlook, cloud and everything in between. Virtual Machines are ordered through a service desk portal.
Lead time on the machines is everything from hours to days.

The teams are extremely risk averse. The Status Quo is rarely challenged. Trying new things are often met with _"That doesn't work here"_ or _"We've 

As IOT is becoming a thing, ACME has split out a team with younger developers in a separate building with more fancy furniture, and a more startup feel. The department wants to shield the IOT from all the legacy software and enterprise processes.

## The Cases

### DevOps Consultant

ACME has hired you as a DevOps consultant. What are the steps that you are going to recommend them taking?
How are you going to establish an overview of the current situation?

### Department Head Mentor

You are struggling with meeting deadlines, and getting a clear answer on when features will be ready is difficult to say the least.
You have a hard time attracting and retaining talent. What would you coach the Department Head to look into. What is the most important issue?

### Agile Coach

The C-level has proclaimed that ACME needs to be more Agile! Thus the department head has hired you as an agile coach.
How would you approach this? What process improvements do you suggest? What are the technical enablers for
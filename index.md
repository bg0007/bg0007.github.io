# The EveryDay IT Audit & Security Hub

``` mermaid
graph LR
  A[Start] --> B{IT Audit?};
  A[Start] --> C{Cyber Audit?};
  B --> D[You need help?];
  C --> D[You need help?];
  D ----> |Yes| E[You are at the right place];
```

> **Note**<br />
> This is not an official site, its a side project by two really into-the-industry folks.

### Hello, fellow enthusiasts!
Andrew and I (Gabor), have created this site to share our knowledge, hopefully initiate some discussion and to support the professional community, along with everybody who might be interested in the topic.

### What you can expect from us?
We have approx 25+ years of experience in the fields of IT/Cyber security and IT Audit. 
The things we have seen, heard, done might be relevant for you.
The things You have seen, heard, done might be relevant for us and the community.
We will share some experiences, practices with examples.
Detail some of the struggles we faced and how we have overcome those.

Most importantly though, we will list here our materials that we use for our everyday job.

### What is the format?
Short problem statements with potential solutions.
Send us your problem, and we try it to solve it for you.
You don t like the solution? Express your views in comments.

### It sounds like Stackoverflow, why should I care?
Indeed it sounds like that - however, this is specific for IT Security and Audit professionals. We welcome you here :)

### I am interested in contributing, how can I do that?
Our mail address is: XXX - drop us a mail and we will discuss the rest ;)
But usually: write a problem statement and a potential solution. If it flies, we will post it (hopefully this will be more automatic in the future, but that requires effort, money… and we are doing this as a hobby, hence be patient). 

### Topics I can count on You:
SAP, AWS, Azure, Workday, SalesForce, ServiceNow, SOC, SOX, Cybersecurity, IT Governance
(The list will grow, hopefully)

### Who we are?
*Andrew - Chief Problem Solver:

*Gabor - Chief Problem Architect: 
exIT Auditor, Star Wars and Lord of The Rings fan (though there is only one Return…), … Currently in the business, as business architect and driving transformation topics. Gained experience at PwC (Budapest office), Diageo (SAP SoD Specialist), IT Auditor (MSCI, Budapest office) and Siemens (IT Auditor, Munchen office). Holds CISA, CRISC, ITIL certifications, and recently passed CCSP.

Guest Problem solvers:
*Can be you...


### Useful Links

|ID|Topic|Problem|Description|Link|Source|Trust score|
|---|---|---|---|---|---|---|
|L001|SOC reports (SSAE/ISAE)|What is a SOC report|SOC reports provide assurance over a 3rd party. SOC reports have 3 major categories, and within SOC2 there are 2 types of reports. These are used for different purposes - SOC1 is used to assess financial stability of a company, while SOC 2 Type1 is used to evaluate the security controls from design aspect of a company, while SOC2 Type2 is used to evaluate controls from the Type1 report for effectiveness, while SOC3 is a high level excerpt of SOC2. The different reports serve different purposes, which needs to be kept in mind, while evaluating them!<br />**1.** For an IT or Cyber security testing You may choose SOC2 Types 1&2<br />**2.** For a Financial audit You may use SOC1<br />**3.** For generic vendor evaluation, You may choose SOC3, which is publicly available. As another constraints, SOC reports 1 and 2 are restricted.|[Link](https://www.ssae-16.com/soc-1/)|SSAE-16 Blog|High|

[Checkout our curated link collection>>](link_collection.md)


### Mysteries to solve

|ID|Problem|How to solve it|
|---|---|---|
|M001|How I achieve assurance on 3rd party service providers|[Link](mysteries/how_to_read_a_soc.md)|
|M002|How to read a SOC report|Link|
|M003|Do I get the same assurance from a SOC 2 Types1&2 reports as from an ISO 270001|Link|

[More mysteries to Read>>](mysteries/mistery_index.md)



### Typical risks

|ID|Risk title|Risk business impact/description|Impact|
|---|---|---|---|
|R001|Vendor goes out of business|Relevant if outsourcing is used - Any business operations require stable, available IT processes and systems. These requirements are defined in the BCR. Outsourcing can mean leased body, or SW or HW like a cloud provider. If such, are built in the IT services, the utilised 3rd parties stability (operational/fiscal) are key. <br />If a 3rd party goes out of business or reduces service provisions (e.g. decreased SLA), business processes could be significantly impacted, meaning that business goals could not be achieved, resulting in financial (e.g. loss of customers; potential compensation), operational (e.g. increased response time), repetitional losses.|High|

[More risks>>](risks/risk_index.md)

## Welcome to EveryDay IT Audit & Security Hub!

Find details about useful materials and issues to be solved.

``` mermaid
graph LR
  A[Start] --> B{IT Audit?};
  A[Start] --> C{Cyber Audit?};
  B --> D[You need help?];
  C --> D[You need help?];
  D ----> |Yes| E[We will help you];
```

### Useful Links

|ID|Topic|Problem|Description|Link|Source|Trust score|
|---|---|---|---|---|---|---|
|L001|SOC reports (SSAE/ISAE)|What is a SOC report|SOC reports provide assurance over a 3rd party. SOC reports have 3 major categories, and within SOC2 there are 2 types of reports. These are used for different purposes - SOC1 is used to assess financial stability of a company, while SOC 2 Type1 is used to evaluate the security controls from design aspect of a company, while SOC2 Type2 is used to evaluate controls from the Type1 report for effectiveness, while SOC3 is a high level excerpt of SOC2. The different reports serve different purposes, which needs to be kept in mind, while evaluating them!<br />**1.** For an IT or Cyber security testing You may choose SOC2 Types 1&2<br />**2.** For a Financial audit You may use SOC1<br />**3.** For generic vendor evaluation, You may choose SOC3, which is publicly available. As another constraints, SOC reports 1 and 2 are restricted.|[Link](https://www.ssae-16.com/soc-1/)|SSAE-16 Blog|High|

### Mysteries to solve

|ID|Problem|How to solve it|
|---|---|---|
|M001|How I achieve assurance on 3rd party service providers|[Link](misteries/how_to_read_a_soc.md)|
|M002|How to read a SOC report|Link|
|M003|Do I get the same assurance from a SOC 2 Types1&2 reports as from an ISO 270001|Link|


### Typical risks

|ID|Risk title|Risk business impact/description|Impact|
|---|---|---|---|
|R001|Vendor goes out of business|Relevant if outsourcing is used - Any business operations require stable, available IT processes and systems. These requirements are defined in the BCR. Outsourcing can mean leased body, or SW or HW like a cloud provider. If such, are built in the IT services, the utilized 3rd parties stability (operational/fiscal) are key. <br />If a 3rd party goes out of business or reduces service provisions (e.g. decreased SLA), business processes could be significantly impacted, meaning that business goals could not be achieved, resulting in financial (e.g. loss of customers; potential compensation), operational (e.g. increased response time), reputational losses.|High|

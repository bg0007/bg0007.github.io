## How to read a SOC report?

[<<Back to main page](index.md)

### Problem statement
My company/client utilises outsourced services in its value chain.
For a security audit: I, as an auditor have to make sure, that all risks, associated with this business process are all identified, remediated, corrected or mitigated through controls.
For a compliance/financial audit: I, as and auditor have to make sure, that the selected vendor/3rd party is stable enough to continue provisioning such services for my company/client, that won't impact my company's/clients operations/service quality/etc.
Such services could be integral part of a value chain:
- physical hardware
- physical location for hardware
- virtual hardware
- leased body
<br/>
If these services are key/significant part of the business process, they might be SOX/regulatory relevant, and as such, will be in scope of an audit.

>**Note**
>Internal audits can also focus on outsourcing risks, its not only relevant from compliance aspect. Hence, as an audit professional, you always have to make sure, that you understand the scope of your audit!

### Solution
I need to identify responsibility boundaries. For that, I have to understand, of what aspects of the business process are managed my company/client - and what belongs to the 3rd party.
>**Note** 
>The risk arising from outsourcing (accountability of the third party) ***ALWAYS*** recedes at outsourcer - in this case, the auditor's company/client.

Options:
- my company/client utilises HW provided by the 3rd party (if virtual, then its a S/Paas model)
- my company/client utilises and manages HW provided by the 3rd party (if virtual, then its a Iaas model)
- my company/client utilises HW provided by the 3rd party and the HW is managed by the 3rd party (Saas)

By understanding the *options* I am defining responsibility boundaries.
Internal actions will be covered by the evaluation of internal controls (ToD+ToE).

External actions will be covered by two options:
1. right to audit
2. independent assessment of service providers controls (SOC*, ISO*, etc.)

For this example, we continue with SOC.
For fiscal stability, I check SOC 1 report.

For security and compliance aspects, I check SOC 2 Type1 report for controls. I evaluate, if we have a gap between what we expected, and what the provider has audited in the SOC. If there is a gap, I check contractual agreements, if the vendor provides me additional evidence for the gap. If not, potential finding.

If I can rely on the SOC 2 Type1, I will look into Type2 to test effectiveness.
If I identify any observation, I evaluate if my business has incorporated in their risk assessment and they defined a proper response. If the observation has not been addressed, then I potentially have found a gap.

### Key aspects to pay attention to:
- Coverage period of the SOC report - these reports are issued annually. Depending what is your companies fiscal period and the vendors fiscal period, there might be a gap for an annual coverage - e.g. Your company has a FY that matches the CY, but the vendor has a FY that starts in October, then you might have a gap for the October-December period for your assurance. You must make sure, that the gap is covered from assurance aspect - e.g. by a cover letter
- What activities are covered by the SOC report - it can be tricky, that you get infrastructure services from a vendor and also leased bodies. Then, you have to make sure, that the SOC report you received covers both activities (usually under services section). If the two separate activities are covered by separate reports, you must ask for both SOC reports.
- Which locations are covered by the SOC report - it can happen, that the vendor provides you DC services from Location A,B and C. However, their SOC report covers only locations A and B. Make sure, that the relevant information for location C is also collected!
- Chain of service - it can be, that your vendor, utilises another vendor (or multiple) to provision the service for you. In this case, you must identify the chain of providers, and request the same assurance report (unless, the vendor provide that assurance in their SOC report - e.g. practices its right to audit their vendors and they share that result). Especially in such case, the above points are crucial to be considered!
- CUEC - has the vendor provided complementary (mandatory) user entity controls? If yes, has your company deployed those? This is key to achieve appropriate coverage of risks arising from the consumption of outsourced services.
- Right report for the right purpose! Remember, SOC1 is for fiscal stability, SOC2 for security controls test and design.

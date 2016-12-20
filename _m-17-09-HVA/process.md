---
layout: default
display_order: 5
title: The Agency HVA Process
permalink: /hva/process/
description:
---


Agencies must take a strategic enterprise-wide view of risk that accounts for all critical business and mission functions when identifying HVAs.  Agencies must also establish appropriate governance of HVA activities across the enterprise and should integrate HVA remediation activities into agency planning, programming, budgeting, and execution processes.  These efforts must align with OMB policy, Federal law and regulations, Federal standards and guidelines, and agency policies, processes, and procedures.

![Process]({{https://policy.cio.gov}}/assets/img/AgencyHVAProcessFramework.png)

<sup><sup>Figure one represents the continuous HVA process, including the specific actions that make up the process. <sup>[3](#3)</sup><sup>


#### PLAN:
Agencies must develop, maintain, and regularly update their HVA inventory lists, at least annually, to implement this guidance.<sup>[#4](#4)</sup>  At a minimum, the planning process must include the following considerations:

* Stakeholder engagement, including identifying and engaging information system and information/data owners, business process experts, IT experts, information security experts, privacy experts, and risk management experts, as necessary;
* Review of business processes and identification of appropriate management controls to protect HVA and critical business functions over the entire data and information lifecycle;
* Governance and oversight, including identification of a senior accountable official and a lead office to be responsible to agency leaders and OMB for management of the overall HVA initiative;
* Engagement with third parties on behalf of the agency to ensure appropriate contract clauses or legal agreements are in place to assess and remediate system vulnerabilities as necessary;
* Engagement with contracting officers and the agency's general counsel to ensure all necessary agreements for contracted services, such as penetration testing, auditing, and security architecture reviews (SARs), are in place; and
* Incorporation of HVA activities into broader agency IT and information security and privacy management planning activities, including:
	* Enterprise risk management;
	* Budget, procurement, and contract management plans to address potential assessor findings;
	* Change management;
	* Information Security Continuous Monitoring (ISCM) Strategy;
	* IT lifecycle management, including plans to upgrade legacy components, system migration, and disposal;
	* Privacy compliance and Privacy Continuous Monitoring (PCM);<sup>[5](#5)</sup>
	* Performance measurement and metrics; and 
	* Contingency planning.

#### IDENTIFY, CATEGORIZE AND PRIORITIZE:
Agencies should use the following guidelines to identify, categorize, and prioritize HVAs to ensure that information systems performing or enabling mission essential functions have been considered as potential HVAs and that appropriate agency stakeholders have been engaged.

* Start with an agency-specific assessment of risk by using FIPS 199<sup>[6](#6)</sup> and NIST SP 800-60 to assist with information and information system identification and categorization.
* Next, consider the value of agency systems and data from a potential adversary’s perspective.   This means agencies should maintain awareness of malicious actor intent, capabilities, targeting, and trends based on government threat intelligence as well as commercial sources of threat intelligence.   Such information includes cybersecurity threats to the agency by nation-state and criminal actors as well as current threat actor tactics, techniques, and procedures.
* Throughout the identification process, agencies should also take a Federal enterprise-wide perspective of the risks posed by their HVAs and of their mission responsibilities to both identify their most critical functions, information, and data and to use that information to categorize information systems as critical mission enablers or mission essential functions.
* Once an initial collection of HVAs has been identified, agencies should protect that collection according to the handling directions at the end of this guidance, take measures to determine the physical location of those HVAs, determine key stakeholders (including third parties) involved in the administration of those HVAs, clearly communicate roles and expectations to those stakeholders, and identify information system interdependencies.
* After the agency-level list of HVAs has been assembled, agency CIOs should ensure that the owners and operators of the HVAs are notified of their designation as an HVA.
Once the agency-level inventory of HVAs has been produced, agencies should develop a risk­ based matrix of threats, vulnerabilities, impacts, and likelihood of compromise.  The matrix should serve as a basis for prioritizing the agency's HVA assessment activities.  This will support the delivery of an annual "Top 10" prioritized list of HVAs to OMB and DHS. For those HVAs that do not qualify as top 10, agencies have the discretion to rank and rate them using either a "1-to-n" or "tiered" approach.

The following criteria should be used by agencies as additional inputs to their own prioritization when categorizing and prioritizing identified HVAs.  This is not an exhaustive list, and it does not preclude agencies from considering additional criteria.

* Adversary and criminal interest;
* Nature and sensitivity of Federal information processed, stored, or otherwise utilized by the HVA;
* Whether the HVA contains Controlled Unclassified Information (CUI),<sup>[7](7)</sup> particularly one or more of the following:
	* PII on agency employees or customers;
	* CUI used for traveler/cargo vetting or other law enforcement purposes; 
	* Proprietary information; and
	* CUI related to Federal or national critical infrastructure or key resources;
* Nature and sensitivity of processes controlled by the system, as in the case of an Industrial Control System (ICS) or Supervisory Control and Data Acquisition (SCADA) system;
* Quantity of information stored or handled by the HVA;
* Uniqueness of the stored or handled information or data and/or the information system function(s) (e.g., if the information system is a single point of failure);
* Degree to which the HVA is essential to supporting the agency's mission essential functions, including whether the HVA is connected with HVAs in other agencies so that a compromise could significantly impact mission essential functions within other agencies;
* Scale of impact (i.e., local, multiagency, Federal enterprise, national-level  impact) of the loss or compromise of the information or data and/or information system functionality; and
* Nature of impact (i.e. national security interests, foreign relations, or economy of the United States or to the public confidence, civil liberties, or public health and safety of the American people).
<br>
Many of these inputs focus on the potential resulting impact or consequence should the confidentiality, availability, or integrity of a given HVA be compromised.  As agencies consider potential inputs for their own individual prioritization approaches, they should also consider privacy risk to individuals, potential threats to the HVA, as well as known vulnerabilities and the overall security posture of the HVA.  All three categories of risk (threat, vulnerability, and consequence) should be considered when ranking HVAs.

#### REPORT:

All Federal agencies are responsible for keeping their internal HVA lists up-to-date.  All CFO Act agencies<sup>[8](#8)</sup> are required to report all of their HVAs, including the prioritized top 10 list, to DHS on an annual basis.  DHS will coordinate with OMB and other interagency partners to ensure appropriate oversight and governance across the Federal Government.  Although HVAs can be either classified or unclassified systems, agencies are only required to report their non-national security HVAs to DHS.  The Fiscal Year 2017 reporting date is January 15, 2017. CFO Act agencies will be required to submit the following data fields to DHS on an INTELINK platform on either the Joint Worldwide Intelligence Communications System (JWICS) or Secret Internet Protocol Router (SIPR) platforms.  Non-CFO Act agencies are encouraged, but not required, to follow the same review and reporting process.  Agency HVA points of contact must maintain an active INTELINK account on either JWICS or SIPR.  The required data fields are as follows:

* Agency Name;
* Agency Component or Bureau Name (if applicable);
* HVA Name;
* Is the HVA a Top 10 Priority HVA (yes/no);
* Description of HVA Function (maximum of 500 characters);
* Description of Impact of HVA Compromise to the Agency (maximum of 500 characters);
* Valid Authorization to Operate (ATO) (yes/no);
* Is the HVA an ICS or SCADA system (yes/no);
* Date of the Last HVA Assessment;
* Type of Assessor  (Agency/DRS/Third-party);
* Current Plan of Action and Milestones (POA&M) to Remediate Assessment Findings (yes/no); and
* If Applicable, How Many Critical/High, Moderate, and Low Impact Actions Remain Incomplete from the Most Recent POA&M.

#### ASSESS:
__Pre-Assessment__
In addition to the standard processes agencies must use for all information systems, to include tailoring security and privacy controls following the selection of the appropriate baseline (commiserate with NIST SP 800-53), agencies must prepare the HVA for assessment and ensure appropriate protections are in place by completing the steps listed below:

* *Implement and validate security controls* -Per the direction of Binding  Operational Directive (BOD) 16-01,<sup>[9](9)</sup> and using the security engineering principles, concepts, and techniques in [NIST SP 800- 160, Considerations for a Multidisciplinary Approach  in the  Engineering of Trustworthy Secure Systems,](http://csrc.nist.gov/publications/drafts/800-160/sp800_160_second-draft.pdf) agencies must implement the following security activities for all HVAs:
	* Secure configuration management;
	* Increased phishing awareness training and testing of personnel with access to HV.A.s;
	* Continual validation of strict access controls, including multifactor authentication;
	* Routine vulnerability scanning and remediation;
	* Increased monitoring and analysis of relevant audit logs; 
	* Network segmentation;
	* Appropriate boundary protections;
	* Verification of data recovery capabilities;
	* Routinely tested incident response procedures; and
	* Maintenance of 100% automated asset visibility and control.
* *Identify system dependencies and interdependencies* -Agencies must identify the connections between HVAs and other systems, including other HVAs and non-HVAs, to understand critical dependencies.
* *Conduct security assessments of HVAs* - After validation of security controls and identification of dependencies and interdependences at the identified HV.A.s, the agency, in coordination with OMB and DHS, shall create and implement a plan for prioritizing and conducting assessments.
* *Ensure appropriate agreements with DHS or independent third-party assessment providers are in place to facilitate timely and comprehensive assessments* - A.11 CFO .Act agencies are required to participate in the HVA initiative and ensure all required legal agreements are signed and in place with DHS prior to commencement of assessment work.<sup>[10](10)</sup> This includes having a valid and signed standing Federal Network Authorization (F.N.A.) and a Rules of Engagement (ROE) in place with DHS consistent with [OMB M-16-03.](https://www.whitehouse.gov/sites/default/files/omb/memoranda/2016/m-16-03.pdf)(<sup>[11](11)</sup> In addition, all Federal Executive Branch agencies are encouraged to follow these procedures.

All agencies are responsible for the ongoing assessment and authorization of their systems to ensure accuracy of information pertaining to the security posture of their HVAs.  Agencies should leverage the results of security audits and voluntary third party assessments to ensure that HVAs are assessed on a regular basis.  Following the assessments, DHS or, alternatively, an independent third party assessment organization will provide specific findings and recommendations and will work with agencies to develop a remediation plan to address findings discovered during the assessment.   Agencies must ensure that the independent third party assessment findings and recommendations are provided to DHS in a timely manner. In addition to including appropriate confidentiality and data handling requirements in any agreements with independent third party assessors, agencies must ensure that relevant agreements with independent third party assessors specify that the agency is the sole owner of all agency information collected by the third party and such information and any derivative work, including notes and working documents, must be returned to the agency.

__Assessment Process__
HVA assessments will focus on the agency's assets, systems, information, data, and datasets as prioritized by the agency and will be reviewed by DHS in coordination with OMB.  These assessments will not replace existing cybersecurity assessment programs for the agency. Agencies may work with DHS to receive comprehensive assessment services or may, and are encouraged to, procure similar HVA risk management services from commercial providers, so long as such services meet the DBS-established baseline requirements of the newly developed Highly Adaptive Cybersecurity Services (HACS) Special Item Numbers (SINs) on GSA's IT Schedule 70.<sup>[12](12)</sup>

HVA assessment activities include:

* Risk and Vulnerability Assessment (RVA) - This service, provided by the DHS National Cybersecurity Assessment and Technical Services (NCATS) team, uses a number of techniques to identify weaknesses in the security posture of a given HVA. These can include network mapping, vulnerability scanning, phishing tests, wireless assessments, web application assessments, and database assessments.
* Security Architecture Review (SAR) -As appropriate and as resources are available, DHS will review the architecture of the HVA and develop recommendations for improving the security of the HVA related to the design and interconnections of the system.  Once the SAR is complete, DHS will develop a report in collaboration with agency personnel to outline the current state of the agency's architecture and propose recommendations for a target state architecture.  If requested by the agency, and if resources are available, DHS will also provide security engineering services to assist the agency with planning and implementation of the recommendations.
* Additional Services, as needed -
	* ICS I SCADA System Assessments - Comprised of tailored assessments based on the type of HVA, this assessment can supplement or replace other assessment activity, as appropriate.
	* Hunting for Potential Malicious Activity - A hunt capability can be deployed to search for malicious activity on any HVA and should be deployed, at a minimum, when the RVA or SAR finds evidence of a potential incident.
	* Federal Incident Response Evaluation -Based on the HVA and its inter-connectedness to other internal or external systems, including other HVAs, it may be appropriate to evaluate incident response readiness specifically tailored around the HVA or related systems.
* Remediation Plans -After the reviews of the HVA have been conducted, DHS, or the agency's independent third party assessment provider, will provide a report on the results, including detailed recommendations on actions that should be taken to address findings. Agencies will then be responsible for the creation of a remediation plan, to include a POA&M detailing specific actions, milestones, and timelines.  The remediation plan does not represent the end of the process, as assessments should be completed on a continuous basis, and agencies should always ensure that HVAs receive an appropriate level of attention and resources to enhance their security posture.

#### REMEDIATE:
The agency must complete its remediation plan expeditiously and should treat it as a priority.  The remediation plan must include actions, milestones, and timelines for remediating the weaknesses or deficiencies identified in the assessment's findings.  This plan should be validated by the CISO, CIO, CFO, SAOP (if the HVA contains PII), and CAO, and it should conform with DHS reporting requirements, including BOD 16-01 or any successor document for timely status updates.

Agencies should work with their budget offices and governance structures to ensure that potential remediation strategies are in alignment with the organization's broader cybersecurity risk-based budgeting plan outlined in the Capital Planning and Investment Control (CPIC) process. <sup>[13](13)</sup>

*** 

#### *Footnotes*
<a name="3">3</a> **Plan**: Prepare for the HVA process, including stakeholder engagement, governance and oversight, third party engagement, and incorporation of HV A activities into broader agency IT planning. 

**Identify**: Examine systems from the agency's perspective, adversary's perspective, and enterprise-wide perspective to determine those assets which may be considered HV As. 

**Categorize**: Organize information systems based on (among other things) system function, what kind of and how much information the system contains, the system's importance to the agency's mission, and the scale of impact from system loss or compromise. 

**Prioritize**: Rank HVA systems in terms of risk, considering the categories of threat, vulnerability, and consequence. 

**Report**: Agencies are responsible for keeping their internal HVA lists up-to-date. All CFO Act agencies are required to report their HV As to DHS on an annual basis. 

**Assess**: The HVA system(s) will be assessed by DHS through a Risk and Vulnerability Assessment (RVA), Security Architecture Review (SAR), and any additional services as deemed necessary. 

**Remediate**: Agencies will receive a detailed report from DHS regarding the HVA system including recommended actions to address the findings. 

<a name="4">4</a> HVA management processes should take advantage of current security-related processes and artifacts produced by agencies in accordance with their responsibilities under FISMA, thus avoiding duplication and redundancies. 

<a name="5">5</a> Per A-130, agencies are required to establish and maintain an agency-wide PCM program that implements the agency's PCM strategy

<a name="6">6</a> There is no minimum FIPS categorization for a system to be considered an HVA, as FIPS ratings are only one factor to consider in the identification and prioritization process. 

<a name="7">7</a> Per [Executive Order CEO) 13556. Controlled Unclassified information](https://www.whitehouse.gov/the-press-office/2010/11/04/executive-order-13556-controlled-unclassified-information), Controlled Unclassified Information is information that requires safeguarding or dissemination controls pursuant to and consistent with law, regulations, and government-wide policies, excluding information that is classified under [EO 13526, Classified National Security Information](https://www.whitehouse.gov/the-press-office/executive-order-classified-national-security-information), of December 29, 2009, or the Atomic Energy Act (P.L. 83-703), as amended. 

<a name="8">8</a> Per 31 U.S.C § 90l(b), as amended, the current CFO Act agencies include the Departments ofAgriculture, Commerce, Defense, Education, Energy, Health and Human Services, Homeland Security, Housing and Urban Development, Interior, Justice, Labor, State, Transportation, the Treasury, Veterans Affairs, Environment Protection Agency, General Services Administration, National Aeronautics and Space Administration, National Science Foundation, Office ofPersonnel Management, Small Business Administration, Social Security Administration, U.S. Agency for International Development, and U.S. Nuclear Regulatory Commission. 

<a name="9">9</a> Published BODs are available to OMB MAX Executive Branch users at [community.max.gov/x/RJQ5JQ](community.max.gov/x/RJQ5JQ)
	
<a name="10">10</a> The ROE establish the guidelines and agreement between DHS and the agency, authorizing DHS, typically through DHS's National Cybersecurity Assessment and Technical Services (NCATS) to conduct RVAs on the agency's networks. 

<a name="11">11</a> OMB M-16-03 directed agencies (not only CFO Act agencies), consistent with applicable law, to provide a signed FNA to DHS by November 13, 2015, to ensure DHS, typically through US-CERT, can rapidly deploy on-site resources to conduct incident response activities, as necessary.  

<a name="12">12</a> The HACS SINS are comprised of the following cybersecurity services: 132-45A: Penetration Testing - Security testing in which assessors mimic real-world attacks to identify methods for circumventing the security features of an application, system, or network. 132-45B: Incident Response Services -These services help organizations impacted by a cybersecurity compromise determine the extent of the incident, remove the adversary from their systems, and restore their networks to a more secure state.
132-45C: Cyber Hunt Services -These activities are undertaken in response to crises or urgent situations within the pertinent domain to mitigate immediate and potential threats. Cyber hunt activities start with the premise that threat actors that are known to target some organizations in a specific industry, or organizations using specific systems, likely to also target other organizations in the same industry or with the same systems. The processes use information and threat intelligence specifically focused on the proximate incident to identify undiscovered attacks. Cyber hunt activities also include the investigation and analysis of all relevant response activities. 
132-45D: Risk and Vulnerability Assessment- These activities include assessments of threats and vulnerabilities, deviations from acceptable configurations, and enterprise or local policy to assesses the current level of risk. The assessor then develops and/or recommends appropriate mitigation countermeasures in operational and non­ operational situations. 

<a name="13">13</a> [www.whitehouse.gov/sites/default/files/omb/assets/egov docs/fy_18_it_budget_guidance.pdf](www.whitehouse.gov/sites/default/files/omb/assets/egov docs/fy_18_it_budget_guidance.pdf )

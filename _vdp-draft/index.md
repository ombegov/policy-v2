---
layout: default
title: Improving Vulnerability Identification, Management, and Remediation
permalink: /vdp-draft/
---
## MEMORANDUM FOR THE HEADS OF EXECUTIVE DEPARTMENTS AND AGENCIES

### SUBJECT: Improving Vulnerability Identification, Management, and Remediation

<div class="usa-alert usa-alert-info" >
  <div class="usa-alert-body">
    <h3 class="usa-alert-heading">Draft Policy</h3>
    <p>
    OMB has posted this draft policy for public feedback. You may provide feedback in three ways:
    </p>
    <p>
    1. Content suggestions and discussions are welcome via GitHub “issues.” Each issue is a conversation initiated by a member of the public. We encourage you to browse and <a href="https://github.com/{{ site.github.organization }}/{{ site.github.repository }}/issues">join in on discussions</a> in existing issues, or start a new conversation by opening a <a href="https://github.com/{{ site.github.organization }}/{{ site.github.repository }}/issues/new">new issue</a>.
    </p>
    <p>
    2. Direct changes and line edits to the content may be submitted through a <a href="https://help.github.com/articles/creating-a-pull-request">&quot;pull request&quot;</a> by clicking &quot;Edit this page&quot; on any site page in <a href="https://github.com/{{ site.github.organization }}/{{ site.github.repository }}/tree/{{ site.github.default_branch }}/">the repository.</a>. You do not need to install any software to suggest a change. You can use GitHub's in-browser editor to edit files and submit a pull request for your changes to be merged into the document. Directions on how to submit a pull request can be found <a href="https://help.github.com/articles/creating-a-pull-request">on GitHub</a>. Open pull requests for the proposed guidance can be found <a href="https://github.com/{{ site.github.organization }}/{{ site.github.repository }}/pulls">in the site repository on GitHub</a>
    </p>
    <p>
    3. Send your content suggestions or proposed revisions to the OMB Office of the Federal Chief Information Officer via email to <a href="mailto:{{site.mail}}">{{site.mail}}</a>. Please note that all comments received will be posted publicly.
    </p>
    <p>
    The deadline for submitting comments is 5:00 PM EST on December 27, 2019.
    </p>
  </div>
</div>

### Background ###

As the Federal Government’s digital footprint has expanded, the risks to its networks and information have also grown. In particular, the level of increased complexity and change across agency networks has hindered the Government’s ability to manage risk across the Federal enterprise in a data-driven, evidence-based manner. One particularly difficult aspect of the risk management challenge is the identification and management of vulnerabilities in large and complicated Federal networks. These vulnerability identification and management challenges are further exacerbated by the Federal Government’s shortage of information technology and cybersecurity personnel. 

As one additional lever to combat these challenges in vulnerability identification and management, many agencies have begun integrating Coordinated Vulnerability Disclosure<sup id="fnref:1"><a href="#fn:1" class="footnote">1</a></sup> (CVD) principles into their security postures. CVD programs seek to mitigate security risks by authorizing security researchers and the public at large with a way to safely and responsibly report security vulnerabilities they uncover. The CVD concept expands vulnerability identification in a way which derives its value from the incorporation of the larger cybersecurity community into the protection of Federal information assets through identification, recommending remediation steps, and communicating effectively with Federal agencies. When implemented effectively, these programs enable organizations to improve the security of Federal information systems using supplemental information approaches. 

Federal agencies are currently incorporating two types of CVD programs into their security efforts: vulnerability disclosure policies (VDPs) and bug bounties. VDPs, which are processes for the intake and addressing of security vulnerabilities uncovered by security researchers and the public, are among the most effective methods for obtaining new insights regarding security vulnerability information. They also provide protection for those who uncover these vulnerabilities by differentiating between acceptable and unacceptable means of gathering security information (also known as “authorizing good faith security research”). VDPs make it easier for the security research community to report vulnerabilities to appropriate agency contacts, who can then use the reports to address vulnerabilities of which they may not have been aware. Bug bounty programs go a step further than VDPs by offering financial compensation based on established parameters to security researchers who report the vulnerabilities. While several organizations in the military and Federal civilian community have used bug bounty programs to great effect, the cost, organizational competence, and maturity required for a strong program has led them to be introduced sparingly thus far, and be limited in duration.<sup id="fnref:2"><a href="#fn:2" class="footnote">2</a></sup> 

OMB has already espoused the utility and positive outcomes of CVD programs, and some Federal agencies already use VDPs, bug bounties, or a combination of the two to identify and manage vulnerabilities.<sup id="fnref:3"><a href="#fn:3" class="footnote">3</a></sup> This policy provides Federal agencies with guidance on CVD programs and mandates a baseline of government-wide CVD requirements

### Discovery and Remediation of Vulnerabilities ###
Maintaining processes, procedures, and toolsets to identify and remediate vulnerabilities<sup id="fnref:4"><a href="#fn:4" class="footnote">4</a></sup> (i.e., managing the full vulnerability life cycle), no matter how they are discovered, is key to sustaining a risk-aware enterprise cybersecurity program. Vulnerability disclosure most often is described as the providing of information, including vulnerabilities discovered and potential remediation suggestions, to an entity that was believed to not be previously aware. While many Federal agencies already maintain certain capabilities to discover vulnerabilities, such as penetration testing or receiving threat and vulnerability information from the Department of Homeland Security (DHS), agencies can benefit from closer partnerships with the security research community (“vulnerability reporters”) who choose to use their skills to find, report, and assist the remediation of vulnerabilities on agency internet accessible assets as a means to improving national cybersecurity.

In order to maintain the interest of vulnerability reporters in reporting observed vulnerabilities in Federal information systems, agency VDPs must address the following areas: 

- **Clearly Identified Reporting Mechanism**: Each Federal agency will clearly and publicly identify where and how vulnerabilities should be reported to it. 

- **Timely Feedback**: Federal agencies will provide timely feedback to good-faith vulnerability reporters. Once a vulnerability is reported, those who report them deserve to know they are being taken seriously and that action is being taken. Agencies should establish clear expectations for follow-up communications with the vulnerability reporter.  

- **Clearly Worded VDPs**: Federal agencies will provide clear assurances that good-faith security research is welcomed and authorized.  Many government information systems are accompanied by strongly worded statements warning visitors against unauthorized use and implying legal reprisal. Agency VDPs should clearly articulate which systems are in scope and the set of vulnerability research activities that can be performed against them to protect those who would report vulnerabilities.

With a clear VDP in place that addresses the above considerations, agencies make it easy for the public to know where to send a report, explicitly authorize types of testing allowed for a defined set of systems, and set an expectation of communication with vulnerability reporters regarding timely remediation and consultation with the researcher. 

### Government-wide Actions & Responsibilities ###

*Vulnerability Disclosure Policies (VDPs)*

The following applies to the Department of Homeland Security’s (DHS) Cybersecurity and Infrastructure Security Agency (CISA):

1. Within 60 calendar days, CISA, in consultation with the Department of Justice (DOJ)<sup id="fnref:5"><a href="#fn:5" class="footnote">5</a></sup> and the National Institute of Standards and Technology (NIST) of the Department of Commerce (Commerce)<sup id="fnref:6"><a href="#fn:6" class="footnote">6</a></sup>, will publish immediate actions agencies shall take to begin instantiating a VDP into agency’s information security programs in an effective, responsible, and tailored manner.

2. Within 150 calendar days, CISA will publish a Federal-wide strategy and implementation plan, which will stipulate how CISA will coordinate with agencies to identify and address persistent and common challenges that have emerged related to vulnerability reporting and remediation, or common threat or vulnerability findings.

3. Within 240 calendar days, CISA will work with the Office of the Federal Chief Information Officer (OFCIO) and Federal agencies on the appropriate methods or mechanisms to coordinate the tracking of submitted vulnerabilities across the Federal enterprise, including where centralized CISA programs or services can help address common vulnerabilities.

In order to support the implementation work required by this memorandum, Federal agencies will need to take affirmative steps to put in place an initial VDP as a baseline for accepting reports from researchers. Beyond these initial actions, agencies will work with CISA to improve the maturity and scope of their VDPs, and integrate those policies into their overall risk management and information security programs. The following applies to all Federal agencies:

1. Within 180 calendar days of the publication of this memorandum, each Federal agency shall publish a VDP, consistent with the requirements. Thereafter, agencies will work with OFCIO and CISA to continue maturing the processes developed for their VDPs and incorporate their VDP findings and remediation activities into their overall information security program.

2. Within 180 calendar days of the publication of this policy, each Federal agency shall develop or update its internal vulnerability handling procedures to incorporate actions required by CISA pursuant to the previous section. 

3. Each Federal agency’s CISO, or equivalent senior official of a different title, is responsible for implementing the above policy requirements.

4. Agencies will use the quarterly Federal Information Security Modernization Act (FISMA) reporting to meet the requirements above, pursuant to additional guidance by OFCIO, in coordination with CISA.

*Bug Bounties*

As described previously, a bug bounty can be leveraged by Federal agencies as a key incentive-focused tool to identity vulnerabilities in a more targeted way. This type of program should be considered in the greater context of an agency’s enterprise risk management program. Federal agencies are encouraged to consider the use of bug bounty programs, namely those that would replicate other Federal programs that have experienced success.

In furtherance of the Federal Government’s effort to identify mission support functions suitable for sharing based on cross-agency agreement on targeted outcomes and service delivery standards, OMB will convene DHS, the General Services Administration, the Department of Commerce and other agencies, as appropriate, to make recommendations to the Federal Chief Information Security Officers Council (CISO Council) on the effective use cases, implementation options, and potential agency demand and benefits of leveraging bug bounty programs.

### Conclusion ###
While significant progress has been made toward securing the Federal Government’s networks and information assets, agencies should continue to leverage useful practices and pursue ways to incorporate these ideas, information, and innovation into their vulnerability management programs. The Federal Government remains committed to finding new and innovative ways to leverage top talent to help agencies meet critical cybersecurity needs, and CVD will continue to offer a unique lever in securing the Federal enterprise. Implementing VDPs and, where feasible, running bug bounty programs, will help agencies more effectively align resources to achieve the greatest return on their cybersecurity investments. 

### Appendix I: Cross-Comparison of Crowdsourced Security Methods ###
As an industry best practice, crowdsourced security approaches have taken on several forms, most notably presented to or by commercial enterprises as CVD, an approach that may include a VDP, a bug bounty program, or a combination of the two, implemented in conjunction with internally developed vulnerability handling procedures. 

A VDP, with supporting vulnerability handling procedures, helps protect the information the public has entrusted to the government, enhances the resiliency of the government’s digital services, and encourages meaningful collaboration between federal agencies and the public. Integrating the procedures into the activities agencies already perform in managing cybersecurity risk allows for a wider array of concerns to be weighed and fixed.  With a VDP in place, agencies make it easy for security researchers to know where to submit vulnerability reports, explicitly authorize types of testing allowed for a defined set of systems, offer legal “safe harbor” to those who abide by the policy, and set an expectation of communication with the reporter. This must be supported by organizational process that evaluates the response needed for a given vulnerability and prioritizes where necessary, leveraging resources from their information security program.

Generally, a VDP is a publicly available statement that defines terms and methods preferred by the authoring organization so that a member of the public may report a vulnerability within the scope authorized by an organization. VDPs typically include:
1. A description of how the organization prefers to receive vulnerability reports and where they should be sent (e.g., URL, email address);
2. Guidance as to when and what a reporter can expect to hear from the organization;
3. A statement that the organization will not pursue legal action against those who follow the policy in good faith;
4. The scope of systems covered by the policy (and often those that are explicitly not covered), and the types of testing allowed; and
5. A document version number.

In the case of a Federal agency, a well-crafted VDP helps to protect the information that the public has entrusted to the government and enhance the resiliency of the government’s digital services.  By integrating handling procedures for submitted vulnerabilities into the processes and activities that Federal agencies already perform to manage cybersecurity risk – vulnerability remediation in particular – a wider array of concerns become known, weighed, and fixed as part of normal operations.  Feedback of this nature can then be used to more efficiently patch or to improve software development lifecycles where applicable – whether actualized by the agency or by one of its vendors.  It may also improve the CVD process itself.<sup id="fnref:7"><a href="#fn:7" class="footnote">7</a></sup> 

VDP adoption and integration is sfvimilar to, but distinct from, a bug bounty.  While both methods strive to incentivize external reporting of vulnerabilities, in bug bounty programs, organizations offer a material reward for valid and impactful findings of certain types of vulnerabilities.  By adding a financial reward, an organization incentivizes action toward systems of most interest and may attract people who would not otherwise look for vulnerabilities.  This may also result in a higher number of reports or increase low-quality submissions, which could overwhelm organization staff in charge of triaging reports.  While security can be enhanced through the use of a bug bounty, organizations should consider the resources and effort required to implement an effective program of this nature in addition to their potential return on investment.

To better understand how methods compare, contrast, or complement each other, the below table provides a high-level overview of the standard visibility, incentives<sup id="fnref:8"><a href="#fn:8" class="footnote">8</a></sup>, and scope of each method type.

|Method Type||Visibility|Incentive<sup id="fnref:9"><a href="#fn:9" class="footnote">9</a></sup>|Scope|
|---------------------------------------------------|---------------------------------|-----------------------------------------------|--------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------|
|Crowdsourced Vulnerability Disclosure (VDP)||Public|Varies; Typically recognition|Generally broad, accepting anything that could be considered a security risk|
|Crowdsourced Penetration Testing|Public Bug Bounty Program|Public|Recognition and/or cash or other incentive of relative value to the reporter|Slightly less broad (typically targeting key systems), accepting anything that could be considered a security risk and that requires a fix|
|Crowdsourced Penetration Testing|Private Bug Bounty Program|Private|Recognition and/or high-value incentive|More specific scope or focus, to encourage testing on a   particular aspect of an attack surface|
|Standard Penetration Testing||Private|Contractual agreement<sup id="fnref:10"><a href="#fn:10" class="footnote">10</a></sup>|More specific scope or focus, to encourage testing on a particular aspect of an attack surface|

#### Endnotes <a id="Endnotes"></a> ####
<div class="footnotes">
<ol>
<li id="fn:1">
<p>Vulnerability disclosure is the “act of initially providing vulnerability information to a party that was not believed to be previously aware”. The individual or organization that performs this act is the reporter. Per ISO/IEC 29147:2018, §3.1 and §3.5.
</p>
</li>
<li id="fn:2">
<p>See Department of Defense “Hack the Pentagon” program: <a>https://www.defense.gov/Newsroom/Releases/Release/Article/1671231/department-of-defense-expands-hack-the-pentagon-crowdsourced-digital-defense-pr/</a>; or the General Services Administration’s Vulnerability Disclosure Policy: <a>https://18f.gsa.gov/vulnerability-disclosure-policy/</a>. Also, the Department of Commerce’s National Telecommunication and Information Administration convened a multistakeholder process for Cybersecurity Vulnerabilities that leverage best practices and templates to assist Federal agencies in adopting coordinated vulnerability disclosure: <a>https://www.ntia.doc.gov/other-publication/2016/multistakeholder-process-cybersecurity-vulnerabilities</a>. 
</p>
</li>
<li id="fn:3">
<p>A Budget for a Better America – President’s Fiscal Year 2020 Budget, Information Technology Analytical Perspectives Chapter: <a>https://www.whitehouse.gov/wp-content/uploads/2019/03/ap_19_it-fy2020.pdf</a>.
</p>
</li>
<li id="fn:4">
<p>Vulnerability is a “[w]eakness in an information system, system security procedures, internal controls, or implementation that could be exploited or triggered by a threat source.” <a>https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r4.pdf#page=105</a>.
</p>
</li>
<li id="fn:5">
<p>To ensure consistency with the Computer Fraud and Abuse Act (18 U.S.C. 1030) and other applicable laws that may be related to the authorized use of agency information systems for security research.
</p>
</li>
<li id="fn:6">
<p>To ensure consistency with NIST Special Publication 800-40 and other standards with Federal applicability: <a>https://csrc.nist.gov/publications/detail/sp/800-40/rev-3/final</a>
</p>
</li>
<li id="fn:7">
<p>Carnegie Mellon University Software Engineering Institute, The CERT Guide to Coordinated Vulnerability Disclosure: <a>https://resources.sei.cmu.edu/asset_files/SpecialReport/2017_003_001_503340.pdf</a>.
</p>
</li>
<li id="fn:8">
<p>Incentives, as presented in this document, refer to those mechanisms leveraged by the organization sponsoring the VDP or bug bounty to drive participation.  These are different than potential motivations of the finder or reporter, which may include a desire to protect the organization, solve a puzzle, obtain notoriety or prestige, earn a profit, or further a political agenda, as described by I Am The Cavalry: <a>https://www.iamthecavalry.org/motivations</a>.
</p>
</li>
<li id="fn:9">
<p>Vulnerability disclosure is the “act of initially providing vulnerability information to a party that was not believed to be previously aware”. The individual or organization that performs this act is the reporter. Per ISO/IEC 29147:2018, §3.1 and §3.5.
</p>
</li>
<li id="fn:10">
<p>For example, the Highly Adaptive Cybersecurity Services (HACS) Special Item Number (SIN) 132-45 on the General Service Administration’s (GSA) IT Schedule 70 includes a sub-category for Penetration Testing that is currently available to agency customers, as well as to vendors seeking to be added to the sub-category’s catalog of providers.
</p>
</li>
</ol>

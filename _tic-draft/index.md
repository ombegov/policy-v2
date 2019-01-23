---
layout: default
title: Update to the Trusted Internet Connections (TIC) Initiative
permalink: /tic-draft/
---
#### MEMORANDUM FOR THE HEADS OF EXECUTIVE DEPARTMENTS AND AGENCIES

### SUBJECT: Update to the Trusted Internet Connections (TIC) Initiative

{% if site.draft %}
<div class="usa-alert usa-alert-info" >
  <div class="usa-alert-body">
    <h3 class="usa-alert-heading">Draft Policy</h3>
    <p>
    As a part of the <a href="https://cloud.cio.gov">Cloud Smart strategy</a>, OMB has posted this draft policy for public feedback. You may provide feedback in three ways:
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
    Due to the partial lapse in appropriations, the deadline for submitting comments has been extended.
    </p>
  </div>
</div>
{% endif %}

A.  **Purpose of the TIC Initiative**

The purpose of the TIC initiative is to enhance network security across
the Federal Government. Accordingly, this memorandum provides an
enhanced approach for implementing the TIC initiative that provides
agencies with increased flexibility to use modern security capabilities.
This memorandum also establishes a process for ensuring the TIC
initiative is agile and responsive to advancements in technology and
rapidly evolving threats. To this end, this memorandum rescinds a number
of OMB Memoranda that previously required agency traffic to flow through
a physical TIC access point. In accordance with [Office of Management
and Budget (OMB) Memorandum M-17-26, *Reducing Burden for Federal
Agencies by Rescinding and Modifying OMB
Memoranda*](https://www.whitehouse.gov/sites/whitehouse.gov/files/omb/memoranda/2017/M-17-26.pdf),
OMB is rescinding the following memoranda:

-   [M-08-05, *Implementation of Trusted Internet Connections
    (TIC)*](https://www.whitehouse.gov/sites/whitehouse.gov/files/omb/memoranda/2008/m08-05.pdf)
    (November 20, 2007)

-   [M-08-16, *Guidance for TIC Statement of Capability Form
    (SOC)*](https://www.whitehouse.gov/sites/whitehouse.gov/files/omb/memoranda/2008/m08-16.pdf)
    (April 4, 2008)

-   [M-08-27, *Guidance for TIC
    Compliance*](https://www.whitehouse.gov/sites/whitehouse.gov/files/omb/memoranda/2008/m08-27.pdf)
    (September 30, 2008)

-   [M-09-32, *Update on the TIC
    Initiative*](https://www.whitehouse.gov/sites/whitehouse.gov/files/omb/memoranda/2009/m09-32.pdf)
    (September 17, 2009)

B.  **Removing Barriers to Cloud and Modern Technology
    Adoption**

This memorandum affirms that agencies may use modern and emerging
technologies to meet TIC initiative requirements. The Department of
Homeland Security (DHS) will define TIC initiative requirements in
documentation called TIC Use Cases. The TIC Use Case documentation will
outline which alternative security controls, such as endpoint and
user-based protections, must be in place for specific instances where
traffic is not required to flow through a physical TIC access point. The
capabilities used to meet TIC Use Case requirements may be separate from
an agency's existing network boundary solutions provided by a Trusted
Internet Connection Access Provider (TICAP) or Managed Trusted Internet
Protocol Services (MTIPS).

1.  ***Agencies shall** meet the requirements of the TIC Use Cases. See
    Appendix A for the initial list of approved TIC Use Cases.*

Given the diversity of platforms and implementations across the Federal
Government, the TIC Use Cases will highlight proven, secure scenarios,
where agencies are not required to route traffic through a TICAP/MTIPS
solution to meet the requirements for government-wide intrusion
detection and prevention efforts, such as the National Cybersecurity
Protection System (including the EINSTEIN suite of capabilities). For
example, some TIC Use Cases may include application deployments where
full-packet inspection is not necessary to achieve proper situational
awareness.

C.  **Collaborative and Iterative Updates**

Due to the rapid pace that technology and threats change, it is critical
that the TIC Use Cases, as well as other TIC reference architecture
documentation, are reviewed and updated on a continuous basis. This
memorandum establishes a collaborative and iterative process, which
includes input from both industry and Federal agencies. The process
includes the following elements:

1.  ***Developing Pilots: The Chief Information Security Officer (CISO)
    Council will** solicit and review agency and industry TIC pilot
    proposals on an ongoing basis, participate in the approval process
    for updates to TIC Use Cases and other TIC reference architecture
    documentation, and establish the timeline for DHS to review pilot
    results and approve updates to TIC Use Cases and other TIC reference
    architecture documentation;*

2.  ***Initiating Pilot Activity: OMB, DHS, the General Services
    Administration (GSA), and the CISO Council will** oversee and
    support agency TIC pilots, as appropriate;*

3.  ***Approving Use Cases: DHS, in coordination with OMB and the CISO
    Council, will** review pilot results and approve updates to TIC Use
    Cases and other TIC reference architecture documentation;*

4.  ***Soliciting Feedback: DHS, in coordination with GSA, will**
    establish a process for soliciting agency and industry input on
    approved TIC Use Cases and other TIC reference architecture
    documentation. DHS will ensure TIC Use Cases and other TIC reference
    architecture documentation are kept up to date as changes are
    approved; and*

5.  ***Acquisitions: GSA, in coordination with DHS, will** update
    government-wide procurement vehicles, as appropriate, within 6
    months of the approval of new TIC Use Case requirements and other
    TIC reference architecture documentation.*


D.  **Streamlining and Automating Verification Processes**

DHS, in coordination with agencies, should streamline and automate
processes to validate agency compliance with TIC Use Cases, where
possible. The goal is to shift from burdensome, point-in-time spot
checks to a scalable, comprehensive, and continuous validation process.

1.  ***Within 90 days of the release of each TIC Use Case, DHS, in
    coordination with GSA, will** develop a compliance verification
    process to validate that agencies are implementing the security
    controls required by TIC Use Cases. DHS will update this
    verification process as necessary to promote continuous improvement.*

E.  **Agency Implementation**

Agency Chief Information Officers shall maintain an accurate inventory
of agency network connections, including details on the service
provider, cost, capacity, traffic volume, logical/physical
configurations, and topological data for each connection in the event
OMB, DHS, or others request this information to assist with
government-wide cybersecurity incident response or other cybersecurity
matters.

1.  ***Within one year of the release of this memorandum, agencies
    will** complete updates to their own network and system boundary
    policies to reflect this memorandum. OMB and DHS will track agency
    implementation through the Federal Cybersecurity Enhancement Act of
    2015 and Federal Information Security Modernization Act of 2014
    (FISMA) reporting.*


**Appendix A - Initial Common Trusted Internet Connections (TIC) Use
Cases**

The following list of TIC Use Cases are released in concert with this
memorandum. The expectation is that the process described under Section
C of this memorandum results in the continuous improvement and
development of updated TIC Use Cases that account for emerging
technologies and evolving cyber threats.

1.  **Cloud**: These sets of TIC Use Cases cover some of the most
    prevalent cloud models used by agencies today.

    a.  Infrastructure as a Service (IaaS)

    b.  Software as a Service (SaaS)

    c.  Email as a Service (EaaS)

2.  **Agency Branch Office**: This use case assumes that there is a
    branch office of an agency, separate from the agency headquarters
    (HQ), which utilizes HQ for the majority of their services
    (including generic web traffic). This case supports agencies that
    want to enable Software-Defined Wide Area Network (SD-WAN)
    technologies.

3.  **Remote Users**: This use case is an evolution of the original
    FedRAMP TIC Overlay (FTO) activities. The use case demonstrates how
    a remote user connects to the agency's traditional network, cloud,
    and the Internet using government furnished equipment (GFE).

4.  **Traditional TIC**: For instances not covered in other DHS TIC Use
    Cases, agencies are required to continue following the Traditional
    TIC use case. The Traditional TIC use case may include agency use of
    TICAP and MTIPS providers. This memorandum, as described in Section
    C -- *Collaborative and Iterative Updates*, encourages agencies to
    propose TIC pilots on an ongoing basis to demonstrate new ways in
    which agencies can achieve the security goals of the TIC initiative
    using state-of-the-practice methods as well as emerging
    technologies.

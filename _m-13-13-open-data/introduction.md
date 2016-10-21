---
layout: default
display_order: 1
title: M-13-13 — MEMORANDUM FOR THE HEADS OF EXECUTIVE DEPARTMENTS AND AGENCIES
permalink: /open-data/
description:
---

<h3> From: </h3> <br/>

* **Sylvia M. Burwell**<br />Director
* **Steven VanRoekel**<br />Federal Chief Information Officer
* **Todd Park**<br />U.S. Chief Technology Officer
* **Dominic J. Mancini**<br />Deputy Administrator, Office of Information and Regulatory Affairs
{: #from}

**Subject:** Open Data Policy&#8212;Managing Information as an Asset

Information is a valuable national resource and a strategic asset to the Federal Government, its partners, and the public. In order to ensure that the Federal Government is taking full advantage of its information resources, executive departments and agencies (hereafter referred to as "agencies") must manage information as an asset throughout its life cycle to promote openness and interoperability, and properly safeguard systems and information. Managing government information as an asset will increase operational efficiencies, reduce costs, improve services, support mission needs, safeguard personal information, and increase public access to valuable government information.

Making information resources accessible, discoverable, and usable by the public can help fuel entrepreneurship, innovation, and scientific discovery &#8211; all of which improve Americans' lives and contribute significantly to job creation. For example, decades ago, the Federal Government made both weather data and the Global Positioning System (GPS) freely available to anyone. Since then, American entrepreneurs and innovators have used these resources to create navigation systems, weather newscasts and warning systems, location-based applications, precision farming tools, and much more.

Pursuant to the Executive Order of May 9, 2013, *Making Open and Machine Readable the New Default for Government Information*, this Memorandum establishes a framework to help institutionalize the principles of effective information management at each stage of the information's life cycle to promote interoperability and openness. Whether or not particular information can be made public, agencies can apply this framework to all information resources to promote efficiency and produce value.

Specifically, this Memorandum requires agencies to collect or create information in a way that supports downstream information processing and dissemination activities. This includes using machine-readable and open formats, data standards, and [common core and extensible metadata](https://project-open-data.cio.gov/v1.1/schema/) for all new information creation and collection efforts. It also includes agencies ensuring information stewardship through the use of open licenses and review of information for privacy, confidentiality, security, or other restrictions to release. Additionally, it involves agencies building or modernizing information systems in a way that maximizes interoperability and information accessibility, maintains internal and external data asset inventories, enhances information safeguards, and clarifies information management responsibilities.

The Federal Government has already made significant progress in improving its management of information resources to increase interoperability and openness. The President's Memorandum on *Transparency and Open Government* <sup id="fnr1"><a href="#fn1">1</a></sup> instructed agencies to take specific actions to implement the principles of transparency, participation, and collaboration, and the Office of Management and Budget's (OMB) *Open Government Directive* <sup id="fnr2"><a href="#fn2">2</a></sup> required agencies to expand access to information by making it available online in open formats. OMB has also developed policies to help agencies incorporate sound information practices, including OMB Circular A-130 <sup id="fnr3"><a href="#fn3">3</a></sup> and OMB Memorandum M-06-02. <sup id="fnr4"><a href="#fn4">4</a></sup> In addition, the Federal Government launched [Data.gov](http://www.data.gov), an online platform designed to increase access to Federal datasets. The publication of thousands of data assets through [Data.gov](http://www.data.gov) has enabled the development of numerous products and services that benefit the public.

To help build on these efforts, the President issued a Memorandum on May 23, 2012 entitled *Building a 21st Century Digital Government* <sup id="fnr5"><a href="#fn5">5</a></sup> that charged the Federal Chief Information Officer (CIO) with developing and implementing a comprehensive government-wide strategy to deliver better digital services to the American people. The resulting *Digital Government Strategy* <sup id="fnr6"><a href="#fn6">6</a></sup> outlined an information-centric approach to transform how the Federal Government builds and delivers digital services, and required OMB to develop guidance to increase the interoperability and openness of government information.

This Memorandum is designed to be consistent with existing requirements in the Paperwork Reduction Act, <sup id="fnr7"><a href="#fn7">7</a></sup> the E-Government Act of 2002, <sup id="fnr8"><a href="#fn8">8</a></sup> the Privacy Act of 1974, <sup id="fnr9"><a href="#fn9">9</a></sup> the Federal Information Security Management Act of 2002 (FISMA), <sup id="fnr10"><a href="#fn10">10</a></sup> the Confidential Information Protection and Statistical Efficiency Act of 2002 (CIPSEA), <sup id="fnr11"><a href="#fn11">11</a></sup> the Freedom of Information Act, <sup id="fnr12"><a href="#fn12">12</a></sup> the Information Quality Act, <sup id="fnr13"><a href="#fn13">13</a></sup> the Federal Records Act, <sup id="fnr14"><a href="#fn14">14</a></sup> and existing OMB and Office of Science and Technology Policy (OSTP) guidance.

If agencies have any questions regarding this Memorandum, please direct them to OMB at [datause@omb.eop.gov](mailto:datause@omb.eop.gov).

---

This attachment provides definitions and implementation guidance for M-13-13, *Open Data Policy&#8212;Managing Information as an Asset*.

### I. Definitions

**Data:** For the purposes of this Memorandum, the term "data" refers to all structured information, unless otherwise noted. <sup id="fnr15"><a href="#fn15">15</a></sup>

**Dataset:** For the purposes of this Memorandum, the term "dataset" refers to a collection of data presented in tabular or non-tabular form.

**Fair Information Practice Principles**: The term "Fair Information Practice Principles" refers to the eight widely accepted principles for identifying and mitigating privacy impacts in information systems, programs and processes, delineated in the National Strategy for Trusted Identities in Cyberspace. <sup id="fnr16"><a href="#fn16">16</a></sup>

**Government information:** As defined in OMB Circular A-130, "government information" means information created, collected, processed, disseminated, or disposed of, by or for the Federal Government.

**Information:** As defined in OMB Circular A-130, the term "information" means any communication or representation of knowledge such as facts, data, or opinions in any medium or form, including textual, numerical, graphic, cartographic, narrative, or audiovisual forms.

**Information life cycle:** As defined in OMB Circular A-130, the term "information life cycle" means the stages through which information passes, typically characterized as creation or collection, processing, dissemination, use, storage, and disposition.

**Personally identifiable information:** As defined in OMB Memorandum M-10-23, <sup id="fnr17"><a href="#fn17">17</a></sup> "personally identifiable information" (PII) refers to information that can be used to distinguish or trace an individual's identity, either alone or when combined with other personal or identifying information that is linked or linkable to a specific individual. The definition of PII is not anchored to any single category of information or technology. Rather, it requires a case-by-case assessment of the specific risk that an individual can be identified. In performing this assessment, it is important for an agency to recognize that non-PII can become PII whenever additional information is made publicly available (in any medium and from any source) that, when combined with other available information, could be used to identify an individual.

**Mosaic Effect**: The Mosaic Effect occurs when the information in an individual dataset, in isolation, may not pose a risk of identifying an individual (or threatening some other important interest such as security), but when combined with other available information, could pose such risk. Before disclosing potential PII or other potentially sensitive information, agencies must consider other publicly available data &#8211; in any medium and from any source &#8211; to determine whether some combination of existing data and the data intended to be publicly released could allow for the identification of an individual or pose another security concern.

**Open data:** For the purposes of this Memorandum, the term "open data" refers to publicly available data structured in a way that enables the data to be fully discoverable and usable by end users. In general, open data will be consistent with the following principles:

* *Public.* Consistent with OMB's *Open Government Directive*, agencies must adopt a presumption in favor of openness to the extent permitted by law and subject to privacy, confidentiality, security, or other valid restrictions.

* *Accessible.* Open data are made available in convenient, modifiable, and open formats that can be retrieved, downloaded, indexed, and searched. Formats should be machine-readable (i.e., data are reasonably structured to allow automated processing). Open data structures do not discriminate against any person or group of persons and should be made available to the widest range of users for the widest range of purposes, often by providing the data in multiple formats for consumption. To the extent permitted by law, these formats should be non-proprietary, publicly available, and no restrictions should be placed upon their use.

* *Described.* Open data are described fully so that consumers of the data have sufficient information to understand their strengths, weaknesses, analytical limitations, security requirements, as well as how to process them. This involves the use of robust, granular metadata (i.e., fields or elements that describe data), thorough documentation of data elements, data dictionaries, and, if applicable, additional descriptions of the purpose of the collection, the population of interest, the characteristics of the sample, and the method of data collection.

* *Reusable.* Open data are made available under an open license that places no restrictions on their use.

* *Complete.* Open data are published in primary forms (i.e., as collected at the source), with the finest possible level of granularity that is practicable and permitted by law and other requirements. Derived or aggregate open data should also be published but must reference the primary data.

* *Timely.* Open data are made available as quickly as necessary to preserve the value of the data. Frequency of release should account for key audiences and downstream needs.

* *Managed Post-Release.* A point of contact must be designated to assist with data use and to respond to complaints about adherence to these open data requirements.

* *Project Open Data:* "Project Open Data," a new OMB and OSTP resource, is an online repository of tools, best practices, and schema to help agencies adopt the framework presented in this guidance. Project Open Data can be accessed at [project-open-data.cio.gov](https://project-open-data.cio.gov/). <sup id="fnr18"><a href="#fn18">18</a></sup> Project Open Data will evolve over time as a community resource to facilitate adoption of open data practices. The repository includes definitions, code, checklists, case studies, and more, and enables collaboration across the Federal Government, in partnership with public developers, as applicable. Agencies can visit Project Open Data for a more comprehensive glossary of terms related to open data.

### Footnotes
<ul style="list-style-type:none">
<li id="fn1"><sup>1</sup> President Barack Obama, Memorandum on Transparency and Open Government (Jan. 21, 2009), *available at* <a>http://www.whitehouse.gov/the_press_office/TransparencyandOpenGovernment</a>. <a href="#fnr1">&#8617;</a> </li>
<li id="fn2"><sup>2</sup> OMB Memorandum M-10-06, *Open Government Directive* (Dec. 8, 2009), *available at* <a>http://www.whitehouse.gov/sites/default/files/omb/assets/memoranda_2010/m10-06.pdf</a> <a href="#fnr2">&#8617;</a></li>
<li id="fn3"><sup>3</sup> OMB Circular A-130, *available at* <a>http://www.whitehouse.gov/omb/Circulars_a130_a130trans4/</a> <a href="#fnr3">&#8617;</a></li>
<li id="fn4"><sup>4</sup> OMB Memorandum M-06-02, *Improving Public Access to and Dissemination of Government Information and Using the Federal Enterprise Architecture Data Reference Model* (Dec. 16, 2005), *available at* <a>http://www.whitehouse.gov/sites/default/files/omb/memoranda/fy2006/m06-02.pdf</a> ** <a href="#fnr4">&#8617;</a></li>
<li id="fn5"><sup>5</sup> President Barack Obama, Memorandum on Building a 21st Century Digital Government (May 23, 2012), *available at* <a>http://www.whitehouse.gov/sites/default/files/uploads/2012digital_mem_rel.pdf</a> <a href="#fnr5">&#8617;</a></li>
<li id="fn6"><sup>6</sup> Office of Management and Budget, *Digital Government: Building a 21<sup>st</sup> Century Platform to Better Serve the American People* (May 23, 2012), *available at* <a>http://www.whitehouse.gov/sites/default/files/omb/egov/digital-government/digital-government-strategy.pdf</a> <a href="#fnr6">&#8617;</a></li>
<li id="fn7"><sup>7</sup> 44 U.S.C. § 3501 *et seq.* <a href="#fnr7">&#8617;</a></li>
<li id="fn8"><sup>8</sup> Pub. L. No. 107-347, 116 Stat. 2899 (2002) (codified as 44 U.S.C. § 3501 note). <a href="#fnr8">&#8617;</a></li>
<li id="fn9"><sup>9</sup> 5 U.S.C. § 552a. <a href="#fnr9">&#8617;</a></li>
<li id="fn10"><sup>10</sup> 44 U.S.C. § 3541, *et seq*. <a href="#fnr10">&#8617;</a></li>
<li id="fn11"><sup>11</sup> Section 503(a), Pub. L. No. 107-347, 116 Stat. 2899 (2002) (codified as 44 U.S.C. § 3501 note); *see also* Implementation Guidance for Title V of the E-Government Act, Confidential Information Protection and Statistical Efficiency Act of 2002 (CIPSEA), *available at* <a>http://www.whitehouse.gov/sites/default/files/omb/assets/omb/fedreg/2007/061507_cipsea_guidance.pdf</a> <a href="#fnr11">&#8617;</a></li>
<li id="fn12"><sup>12</sup> 5 USC 552(a)(2). <a href="#fnr12">&#8617;</a></li>
<li id="fn13"><sup>13</sup> Pub. L. No. 106-554 (2000) (codified at 44 U.S.C. § 3504(d)(1) and 3516). *See also* OMB Memorandum M-12-18, *Managing Government Records Directive* (Aug. 24, 2012), *available at*  <a>http://www.whitehouse.gov/sites/default/files/omb/memoranda/2012/m-12-18.pdf</a>. <a href="#fnr13">&#8617;</a></li>
<li id="fn14"><sup>14</sup> 44 U.S.C. Chapters 21, 22, 29, 31, and 33. *See also* 36 CFR Subchapter B &#8211; Records Management. <a href="#fnr14">&#8617;</a></li>
<li id="fn15"><sup>15</sup> *Structured* information is to be contrasted with *unstructured* information (commonly referred to as "content") such as press releases and fact sheets. As described in the *Digital Government Strategy*, content may be converted to a structured format and treated as data. For example, a web-based fact sheet may be broken into the following component data pieces: the title, body text, images, and related links. <a href="#fnr15">&#8617;</a></li>
<li id="fn16"><sup>16</sup> The White House, *National Strategy for Trusted Identities in Cyberspace* (April 2011), *available at* <a>http://www.whitehouse.gov/sites/default/files/rss_viewer/NSTICstrategy_041511.pdf</a> <a href="#fnr16">&#8617;</a></li>
<li id="fn17"><sup>17</sup> OMB Memorandum M-10-23, *Guidance for Agency Use of Third-Party Websites and Applications* (June 25, 2010), *available at* <a>http://www.whitehouse.gov/sites/default/files/omb/assets/memoranda_2010/m10-23.pdf</a> <a href="#fnr17">&#8617;</a></li>
<li id="fn18"><sup>18</sup> Links to the best practices developed in Project Open Data referenced in this memorandum can be found through the directory on this main page. <a href="#fnr18">&#8617;</a></li></ul>

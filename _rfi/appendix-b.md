---
layout: default
display_order: 8
title: Appendix B. Security
permalink: /rfi/appendix-b/
description:
---
|Security Baseline|	FedRAMP|NIST|New
|Vendor shall disclose the locations by (City, State/Country) where data centers and any ordering activity will have data-at-rest (either primary storage or replicated storage), while within the provider’s control inside the provider’s security authorization boundary.| x|x|
|This requirement is part of the pass/fail criteria, if the Vendor does not provide data center locations, the Vendor’s submission will not be considered. <br>a. If the Vendor provides U.S. Based Pricing in accordance with pricing requirements but utilizes Non-U.S. Based Data Centers, the Vendor’s submission will not be considered.|x | | |
|Maintenance, hardware and software services must be provided by United States citizens.| | | x|
|Solution able to meet the Essential Characteristics of Cloud Computing as defined in the National Institute of Standards and Technology (NIST) Special Publication 800-145 and NIST Special Publication 800-88: Guidelines for Media Sanitization, September 2006.|x|x| |
|As per NIST SP 800-37 rev.1 and SP 800-53 rev.3, and OMB A-130, the Vendor shall be responsible for protecting data at rest and data in transit according to applicable NIST encryption standards.  Vendor shall detail how their service protects data-at-rest and data-in-transit.| |x| |
|Solution shall comply with all current EINSTEIN requirements.|x|x| |
|Solution shall comply with [US-CERT reporting requirements.](https://www.us-cert.gov/incident-notification-guidelines)| | |x|
|Solution able to meet the Essential Characteristics of the National Institute of Standards and Technology Special Publication 800-53 Rev4 Security and Privacy Controls for Federal Information Systems and Organizations.|x|x| |
|Solution shall implement host-based and/or network-based IDS/IPS implementations/protections.| | |x|
|The solution shall support the use of agency-issued digital signature and key management certificates for the purposes of encrypting and signing e-mails and documents, including both PIV certificates and software certificates provisioned by the agency.| | |x|
|The solution shall deliver content via SSL/TLS.| | |x|
|System shall be able to deliver all sites on ports 80 and 443.| | |x|
|Solution shall provide the ability to identify and secure/destroy verifiably including any and all backups and delete data upon 2 days.| | |x|
|Solution shall provide the ability to perform a secure wipe of slack space on the mail server disk array after data spill. Solution shall, in the case of a security incident, notify and coordinate with affected Component within 30 minutes of identification.| | |x|
|Solution shall provide the ability for anti-virus scanning, content filtering, anti-spam filtering, phishing attack prevention, custom content rules, and extension filtering.  (Spam filters must support a minimum of 5 layer inspection.) Solution shall detect spam emails and take appropriate action (e.g. purge, quarantine, and move to junk folder). Solution shall have the ability to prevent delivery (i.e. block) of incoming and outgoing email based on the following fields at a minimum: sender, recipient, subject, attachment name, attachment file extension <br>-Solution shall have the ability to accept blocking/filtering signatures through an API and user interface<br>-Shall have the ability to centrally manage all filters <br>-Shall have the ability to generate reports of blocked messages which must contain the following at a minimum: Email meta data (sender, recipient, subject, date sent, etc.) number of messages blocked with associated cause of prevention (i.e. the blocking rule or rationale)<br>-Shall have the ability to place blocked messages in an admin-approval queue (i.e. quarantine) which will allow for delivery (or deletion) of blocked emails after a security review<br>-Shall have the ability (separate from the quarantine ability) to prevent user defined content (email body or attachments) from blocked inbound messages from being stored in any email store, repository, database, etc., to include any log files.<br>Solution shall have the ability to accept blocking/filtering signatures and quarantine other emails for later inspection and if not a known signature, provide ability to deploy signature in the email system.| | |x|
|Solution shall provide the ability to deliver all SMTP logs on a real-time basis.  SMTP information will include (at a minimum) Sender, Receiver (to, cc, bcc), subject line, attachment name, size, date and time.  This includes all internal to internal, internal to external, and external to internal transactions.| | |x| 
|Solution shall have the ability to purge (delete from all email stores, repositories, databases, etc.) specific emails based on the following fields at a minimum: sender, recipient, subject, attachment name.| | |x|
|System Operators will test backup/recovery process on at least a quarterly basis and provide results to designated agency personnel.|x|x| |
|System shall provide geographically dispersed disaster recovery capability| |x| |
|Backup/restore features that include daily incremental and weekly full backups with 3 year off-site retention.| | |x|
|Solution shall provide the capability to "freeze" (apply a litigation hold) on an email with attachments and prevent any further changes to content, metadata or deletions on the email and attachment until the "freeze" is lifted;  multiple "freeze" layers must be allowed (i.e. a document with attachments may be frozen for reasons of separate investigations).| | | x|
|The solution shall support multi-factor authentication using agency-issued PIV cards and PIV Derived PIV Credentials.|x|x| |
|All interfaces to the solution, including user-facing, administrative, and maintenance interfaces, shall require multi-factor authentication using agency-approved mechanisms.| | | x|
|All Agency data at rest and in transit must be encrypted using FIPS 140-2 validated or NSA-approved encryption, as appropriate.|x|x| |
|The solution should support TIC Compliance through a TIC Overlay or other approved solution.| | |x|


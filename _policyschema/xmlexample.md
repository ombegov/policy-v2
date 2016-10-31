---
layout: default
display_order: 6
title: Example of Schema in XML
permalink: /policyschema/xmlexample/
description: 
---
In this section you will find a example of the Policy Schema in XML format.  XML offers the best utilization for providing structure to policy documents.  It is structured in a way that makes it easy to consume large documents.

~~~

<?xml version="1.0" encoding="UTF-8"?>
<root>
    <policy>
        <element>
            <OMBPolicyID>M-16-19</OMBPolicyID>
            <issuingBody>Office of Management and Budget (OMB)</issuingBody>
	    <issuingDate>8/1/2016</issuingDate>
	    <linkToPolicy>https://www.whitehouse.gov/sites/default/files/omb/memoranda/2016/m_16_19_1.pdf</linkToPolicy>
            <policyStatus>
                <element>CURRENT</element>
            </policyStatus>
            <policyTitle>Data Center Optimization Initiative(DCOI)</policyTitle>
            <precedentPolicies>
                <element>FITARA</element>
                <element>FDCCI</element>
            </precedentPolicies>
            <requirements>
                <element>
                    <agenciesImpacted>CFO Act Agencies</agenciesImpacted>
                    <cita>
                        <element>FITARA Section 834(b)(1)(A)-(E)</element>
                    </cita>
                    <deadline>Yearly</deadline>
                    <policySection>Reporting</policySection>
		    <policySubSection>Strategic Plan</policySubSection>
		    <keywords>
                       <element>IT Project Management</element>
                       <element>Governance - Implementation</element>
                    </keywords>
                    <ombDataCollection>Data Center Inventory</ombDataCollection>
                    <requirementID>1201.5</requirementID>
                    <requirementIssuanceYear>2016</requirementIssuanceYear>
                    <requirementText>In accordance with FITARA, beginning in fiscal year 2016, each agency head shall annually publish a Strategic Plan to describe the agency’s consolidation and optimization strategy for fiscal years 2016, 2017, and 2018.
		    </requirementText>
                    <requirementType>
                        <element>CURRENT</element>
                    </requirementType>
		</element>
                <element>
                    <agenciesImpacted>CFO Act Agencies</agenciesImpacted>
                    <deadline>Yearly</deadline>
                    <keywords>
                        <element>IT Project Management</element>
                        <element>Governance - Implementation</element>
                    </keywords>

~~~

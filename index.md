---
title       : Introduction to DHIS2
subtitle    : 
author      : DHIS2 Community
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---

## DHIS2 Background

* DHIS 2 is open source software developed, customized and used for reporting, analysis and dissemination of health data
* Developed since 2004 by a global community
* Core DHIS 2 activities coordinated from University of Oslo, funded by Norad
* Used in more than 30 countries
  
[Main site](http://dhis2.org)
  
[Development site](http://launchpad.net/dhis2)
  
[Demo site](http://apps.dhis2.org/demo)
  

---

## What is DHIS2?
* A software platform to support integrated management of (health) information.
* A generic tool, rather than a pre-configured database.
* A open model allows user to design the contents of the specific system without programming.
* This allows an administrator to integrate information from various sources for sector-wide analysis.

---

## Main components

* Metadata/registry management
* Data collection
* Analysis and visualization
* Scheduled aggregation and indicator calculations optimised for responsiveness in analysis tools
* DHIS Tracker (individual records): case-based (anonymous) or program tracking
* DHIS Mobile clients: Browser, Smartphone, J2ME, SMS
* Application programming interface for interoperability

---

## The DHIS 2 architecture in a nutshell
* What you download is a platform with tools and features to support health information systems - a "skeleton"
* The platform must be filled with local content to be useable, a.k.a. "implementation", "customisation", "local design"
  * Define what to collect, where to collect, indicators to calculate and report outputs to analyse and disseminate
  * A local process via the user interface - no programming needed!
  * Flexible metadata design supports an integrated HIS approach with a wide range of HIS data sources/programmes
  * Each implementation is localised and different, but based on the same core software platform
  * Enables local ownership of the system - "designed" locally

---

## A local system on a global platform

* Global core system
  * Collection, processing and maintenance of data
  * Metadata management
  * Data visualizer and GIS
  * Reporting tools
  * User management
  * Security
  * Application programming interface (API)

---

## Local customization
* Local content
  * Organisational hierarchy
  * Data entry forms
  * Data validation rules
  * Data element and indicator definitions
  * Reports, Charts, Maps and other outputs
  * Users
*Local modules
  * Extends the core
  * Special requirements such as cold chain, logistics, reporting
  *__Requires a strong local development team__
* Local languages
  * System support essentially any language through translation
  * No development (but rather translation) required
---

## Implementation highlights
  * Kenya
  * Uganda
  * Ghana
  * Zambia

---

## Kenya: Rapid rollout
* Status
  * First national online DHIS 2 implementation (Aug 2011)
  * Based on Mobile Internet connectivity
  * Cloud-based server hosting
  * National roll-out to 250 districts in 5 months (fast!)

* Plans: 
  * EMR integration using DHIS 2 Web-API
  * PEPFAR partner reporting through DHIS
  * DHIS Web Portal for easy dissemination of data

---

## Uganda: Making full use of the DHIS platform

* National HIS roll-out (finalised Aug 2012) using Mobile Internet + online server hosted at MoH
* Registering and analysing maternal and neonatal deaths using DHIS Tracker
* Tracking mothers and children using DHIS Tracker  and mobile clients (pilot)
* ARV ordering and reporting through national DHIS 2 (pilot) 
* Partner-based rollout and support (CDC, UNICEF, USAID ++)

---

## Ghana: Patient level data collection

* National online HIS roll-out (May 2012)
* Use DHIS 2 to capture all inpatient cases at district hospitals
* Using anonymous single event program in DHIS Tracker
* Using ICD-10 codes for more accurate diagnosis aggregation
* Captures basic insurance data
* Server hosted at a data centre in the country 


--- 

## Zambia: Mobile solutions
* Using DHIS Mobile clients (J2ME) to capture malaria incidence data directly from ~450 health facilities to strengthen malaria surveillance
* Implemented by National Malaria Control Programme 
* Both data entry and basic feedback reports on the low-end phones
* New programmes have come on board (Community Health workers, Male circumcision, etc)
* Communication with the national DHIS2 instance through (meta)data exchange

--- 

## Supoprt options
* Global network of technical consultants
* In-field precense of core developers from University of Oslo
* Community mailing lists
* Extensive, open-source documtnation
* THe DHIS2 Academy
  * Training Program to strengthen regional capacity to implement DHIS 2
  * 1-2 weeks training workshops every year in West Africa, East Africa, Asia, and Latin America
  * For ministries, NGOs, universities, private sector ++

--- 

## Roadmap highlights
* Support PEPFAR partner reporting
* Object access control (private/groups/public)
* Dynamic dimensional analysis engine
* New report/pivot table module
* Improved reporting in Tracker
* Better security and privacy in Tracker

---

## References

[DHIS 2 website:](http://dhis2.org) Downloads, documentation and much more

[Development platform: Launchpad](http://launchpad.net/dhis2)

[DHIS 2 demo](http://apps.dhis2.org/demo)

[The implementation guide](http://dhis2.org/doc/snapshot/en/implementer/html/)

---

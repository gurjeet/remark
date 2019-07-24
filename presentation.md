Postgres-2.0 & Blobstore
========================

---

Team
====

- Gurjeet (SO for both services)
- Shashi (Blobstore)
- Dinesh (Contractor, Bangalore)
- Saurabh (Contractor, Bangalore)
- Suhas (Contractor, Bangalore)

---

Customers
=========

- Audit team
- APM
- Schindler
- South32
- UAA
- Every team in platform

---

Points of Presence
==================

- US-East
- Frankfurt
- GovCloud (no US Person)
- PPC

---

How We Survived So Far
======================

- By saying "No"
  + No DBA-like support from us

    We have an email crafted to explain why.

  + No US-East deployment
  + No integrations with Zipkin
  + Said "no" numerous other things

  Now we direct the customers to Product Mgmt. and say no to PM. After PM has
  enough customers asking for a feature, we add that to the backlog.

---

How We Survived So Far (Part II)
================================

- Developed a great MVP _before_ going GA
- Implementing limits and integrations _before_ goig GA
- Provide Lowest Common Denominator features
- Commit to providing these features in all PoPs

  Same interface and features, released gradually in all PoPs. E.g. 
  https://docs.predix.io/en-US/content/service/data_management/sql_database/

- SOP for everything we do
- Everything is version controlled in Git. E.g https://postgres-20-docs.run.aws-usw02-dev.ice.predix.io/

  Very few things in Confluence

---

Background
==========

- Data Stores are a much different beasts than other applications
- Service takes care of
  + HA
  + PITR
  + Backups
  + Encryption (not in PPC)

- Automation
  + Create
  + Modify
  + Destroy
  + Backups
  + Restore

---

Priorities
==========

Q3
----

- Team
  + Convert at least 1 Contractor to FTE

- Rosneft
  + Postgres extensions
  + Self-service storage increase
  + PITR

- Cloud
  + Cost attribution/revenue recognition
  + Frankfurt hardening

---

Priorities
==========

Q4
----

- Team
  + Hire a US Person (for GovCloud)
  + Hire from Open Source communities
  + Convert another Contractor to FTE

- Rosneft
- Cloud
  + Storage threshold warnings

- PPC 2.0
  + Open Source projects deployments
    - Minio (Blobstore)
    - CrunchyData: major version upgrade (Postgres)
  + Plan Upgrades
  + Plan Downgrades


---

Concerns
========

- Shortage of people
- Need for right kind of talent
- Contributing back to FOSS communities
- Too many PoPs
- Lack of clear focus
- Multiple Git hosts
- Slow onboarding (multiple weeks; laptop, tokens, VPNs,...)
- Too many networks (Internet, BlueSSO) * (3 VPNs) * (HTTP Proxy vs no Proxy)
- Fragmented documentaion/communication

  Spreadsheets, Smartsheets, Confluence pages, Powerpoints, Box folders, Word docs.

  Version (in Git) everything.

---

Silver Lining
==========

PPC 2.0
-------

- Unified CI/CD






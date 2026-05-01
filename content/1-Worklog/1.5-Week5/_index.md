---
title: "Week 5 Worklog"
date: 2026-04-27
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---


### Week 5 Objectives:

* This week focused on integrating Amazon RDS into the PHP application and performing basic fixes to ensure stable database connectivity.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | **-	Tasks:**  <br>&emsp; + Created an RDS MySQL instance. <br>&emsp; + Configured database credentials. <br> **- Output:**  <br>&emsp; + RDS instance successfully deployed. <br> **- Reflection:**  <br>&emsp; + Managed database services simplify infrastructure setup.           | 06/04/2026   | 06/04/2026      | Create RDS Instance – <https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_CreateDBInstance.html> |
| 3   | **-	Tasks:**  <br>&emsp; + Configured Security Group to allow EC2 access. <br>&emsp; + Opened port 3306. <br> **- Output:**  <br>&emsp; + EC2 could connect to RDS. <br> **- Reflection:**  <br>&emsp; + Network configuration is critical for connectivity.           | 07/04/2026   | 07/04/2026      | RDS Security Group Setup – <https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Overview.RDSSecurityGroups.html> |
| 4   | **-	Tasks:**  <br>&emsp; + Imported existing SQL database into RDS. <br> **- Output:**  <br>&emsp; + Data successfully migrated. <br> **- Reflection:**  <br>&emsp; + Data migration must be handled carefully.     | 08/04/2026   | 08/04/2026      | MySQL Import Guide – <https://dev.mysql.com/doc/refman/8.0/en/mysqlimport.html> |
| 5   | **-	Tasks:**  <br>&emsp; + Updated database configuration in PHP code. <br>&emsp; + Replaced localhost with RDS endpoint. <br> **- Output:**  <br>&emsp; + Application connected to RDS. <br> **- Reflection:**  <br>&emsp; + Cloud database improves scalability.          | 09/04/2026   | 09/04/2026      | PHP MySQL Connection |
| 6   | **-	Tasks:**  <br>&emsp; + Tested CRUD operations. <br>&emsp; + Fixed minor connection issues. <br> **- Output:**  <br>&emsp; + Database operations worked correctly. <br> **- Reflection:**  <br>&emsp; + Small fixes are necessary for system stability.           | 10/04/2026   | 10/04/2026      | CRUD Operations Guide |


### Week 5 Achievements:

* Successfully integrated RDS and ensured stable operation.
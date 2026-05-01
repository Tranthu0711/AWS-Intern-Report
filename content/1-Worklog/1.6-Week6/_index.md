---
title: "Week 6 Worklog"
date: 2026-04-27
weight: 1
chapter: false
pre: " <b> 1.6. </b> "
---


### Week 6 Objectives:

* This week focused on integrating Amazon S3 into the application to manage and store static files such as images.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | **-	Tasks:**  <br>&emsp; + Created a new S3 bucket for storing application files. <br>&emsp; + Configured basic bucket settings. <br> **- Output:**  <br>&emsp; + S3 bucket was successfully created and ready for use. <br> **- Reflection:**  <br>&emsp; + S3 provides a highly scalable and reliable storage solution.            | 13/04/2026   | 13/04/2026      | Amazon S3 Getting Started – <https://docs.aws.amazon.com/AmazonS3/latest/userguide/GetStartedWithS3.html> |
| 3   | **-	Tasks:**  <br>&emsp; + Configured bucket policy to allow public access for image files. <br>&emsp; + Adjusted permissions for secure access. <br> **- Output:**  <br>&emsp; + Files in S3 could be accessed via public URLs. <br> **- Reflection:**  <br>&emsp; + Security configuration must be handled carefully to avoid exposing sensitive data.           | 14/04/20265   | 14/04/2026      | S3 Bucket Policy Guide – <https://docs.aws.amazon.com/AmazonS3/latest/userguide/bucket-policies.html> |
| 4   | **-	Tasks:**  <br>&emsp; + Installed AWS SDK for PHP on the EC2 instance. <br>&emsp; + Configured credentials for accessing S3. <br> **- Output:**  <br>&emsp; + Application successfully connected to S3 service. <br> **- Reflection:**  <br>&emsp; + Using SDK simplifies interaction with AWS services.      | 15/04/2026   | 15/04/2026      | AWS SDK for PHP – <https://docs.aws.amazon.com/sdk-for-php/> |
| 5   | **-	Tasks:**  <br>&emsp; + Implemented functionality to upload images from the application to S3. <br>&emsp; + Tested file upload process. <br> **- Output:**  <br>&emsp; + Files were uploaded successfully to S3. <br> **- Reflection:**  <br>&emsp; + Storing files in S3 reduces the storage load on EC2.            | 16/04/2026   | 16/04/2026      | Upload Files to S3 using PHP – <https://docs.aws.amazon.com/sdk-for-php/v3/developer-guide/s3-examples.html> |
| 6   | **-	Tasks:**  <br>&emsp; + Displayed images stored in S3 on the website. <br>&emsp; + Verified correct loading of files. <br> **- Output:**  <br>&emsp; + Images were displayed correctly on the website. <br> **- Reflection:**  <br>&emsp; + Integrating S3 improves performance and scalability of the application.             | 17/04/2026   | 17/04/2026      | AWS Console |


### Week 6 Achievements:

* Successfully integrated Amazon S3 into the application for storing and serving static files.
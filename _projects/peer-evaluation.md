---
layout: project
title: Peer Evaluation
order: 4
summary: Multi-level peer assessment system with automated anomaly detection and escalation workflow
---

## **Project Overview**

Peer Evaluation is an intelligent assessment system facilitating peer-to-peer evaluation with built-in quality control. The system assigns unique IDs to each student per quiz, ensuring anonymity and security. QR codes are generated only when teachers use bulk download for later PDF uploads. When students upload directly via portal, unique IDs generate automatically without QR codes. Algorithm-based anomaly detection flags issues to Teaching Assistants, who can escalate to teachers, maintaining academic integrity throughout.

## **Key Features**

The platform automatically generates unique IDs for anonymous evaluation. Teachers choose between bulk download with QR codes for offline distribution or direct student portal uploads with auto-generated IDs. Students evaluate peers anonymously while algorithm-based detection identifies suspicious patterns and statistical outliers. The multi-level escalation workflow moves from peer reviews to automated detection to TA review to teacher intervention.

TAs review flagged submissions through their dashboard, while teachers handle final escalation for complex cases. Rubric-based evaluation ensures consistency. The platform provides comprehensive analytics on evaluation patterns, manages structured feedback with quality controls, and uses statistical analysis for fair rating aggregation. Complete audit trails track the entire process.

## **Technologies Used**

Frontend: React, Javascript. Backend: Express.js, Node.js. Database: MongoDB. QR code libraries for unique code generation. Statistical outlier detection algorithms (standard deviation analysis, etc.) for anomaly detection. Authentication: JWT/OAuth.

## **Evaluation Workflow**

### Bulk Download Path
Teacher creates assessment with rubrics, downloads unique IDs with QR codes, distributes printed assessments, then scans and uploads PDFs. System links PDFs to student IDs via QR codes. Students evaluate assigned peer submissions anonymously.

### Student Portal Upload Path
Teacher creates assessment with rubrics. Students upload directly from portal. System auto-generates unique IDs without QR codes. Students evaluate assigned peer submissions anonymously.

### Common Workflow
System runs algorithm-based analysis for anomalies. Flagged cases go to TAs for investigation. Complex cases escalate to teachers. Validated evaluations aggregate using statistical methods for fair final marks.

## **Project Goals**

The project implements a fair, transparent multi-level evaluation system ensuring accurate assessment. Anonymity is achieved through unique ID-based identification. The platform supports flexible submission methods (bulk upload or student portal) and automates anomaly detection using statistical algorithms. The efficient escalation workflow ensures issues are handled at appropriate levels. Comprehensive analytics help instructors understand evaluation quality, while multiple checkpoints maintain academic integrity. The system provides actionable insights for continuous improvement.

## **GitHub Repository**

[PES](https://github.com/vicharanashala/pes)

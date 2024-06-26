# Scalable Data Storage Workshop

![Workshop Banner](/images/backup_and_data.png)

Welcome to the Scalable Data Storage Workshop organized for the students at Maple College by Autonomous Vehiculum. This workshop aims to introduce you to scalable data storage solutions and their applications in self-driving car scenarios. Let's dive into the technologies that make scalable data storage possible and explore practical implementations.

▶️  [Workshop Video](https://mylambton-my.sharepoint.com/personal/c0894894_mylambton_ca/_layouts/15/stream.aspx?id=%2Fpersonal%2Fc0894894%5Fmylambton%5Fca%2FDocuments%2FRecordings%2FCall%20with%20Mahakdeep%20and%202%20others%2D20240626%5F120125%2DMeeting%20Recording%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E5d8098ac%2D6de3%2D4adb%2Db9f1%2D6f86949cc492)

🔗 [Workshop PPT Link](https://www.canva.com/design/DAGJDbXDXNg/y7etTndrNT1o3Dq1ek9hWw/edit)

## Table of Contents
- [Overview](#overview)
- [Agenda](#agenda)
- [Workshop Sections](#workshop-sections)
  - [Introduction to Scalable Data Storage](#introduction-to-scalable-data-storage)
  - [NoSQL Databases](#nosql-databases)
  - [Distributed File Systems](#distributed-file-systems)
  - [Data Leaks](#data-leaks)
  - [Interactive Section](#interactive-section)
- [Resources](#resources)
- [Q&A](#qa)

## Overview
In this workshop, you will learn about scalable data storage solutions and their importance in self-driving car technologies. We will cover the following topics:
- Introduction to Scalable Data Storage
- NoSQL Databases
- Distributed File Systems
- Data Leaks

## Agenda
1. **Introduction**
   - Welcome and objectives
2. **Scalable Data Storage Overview**
   - Key concepts and importance
3. **NoSQL Databases**
   - Overview, use cases, and examples
4. **Distributed File Systems**
   - Explanation and benefits
5. **Data Leaks**
   - Definition, architecture, and applications
6. **Interactive Section**
   - Hands-on activities and exercises
7. **Q&A and Closing Remarks**

## Workshop Sections

### Introduction to Scalable Data Storage
![Introduction](/images/intro-scalable-storage.webp)
- **What is scalable data storage?**
  - Scalable data storage refers to systems and methods that allow data storage capacity to grow and manage large volumes of data efficiently. It ensures that performance remains stable even as data scales.
- **Importance in autonomous vehicles**
  - Autonomous vehicles generate vast amounts of data from sensors, cameras, and other sources. Efficiently storing and managing this data is crucial for real-time processing and analysis.

### NoSQL Databases
![NoSQL Databases](/images/Types-of-NoSQL-Databases.webp)
- **Overview**
  - NoSQL databases provide a way to store and retrieve data that is modeled in means other than the tabular relations used in relational databases.
- **Types of NoSQL databases**
  - **Document-based**: Store data in document formats like JSON or BSON (e.g., MongoDB).
  - **Key-value stores**: Store data as key-value pairs (e.g., Redis).
  - **Column-based**: Store data in columns rather than rows (e.g., Apache Cassandra).
  - **Graph-based**: Store data as nodes and edges, suitable for data with complex relationships (e.g., Neo4j).
- **Use cases in self-driving cars**
  - Storing sensor data, vehicle logs, and map data for quick access and analysis.
- **Examples and demos**
  - Setting up MongoDB, inserting sample data, and running queries.

### Distributed File Systems
![Distributed File Systems](/images/distributed-file-system-diagram.png)
- **Definition and explanation**
  - Distributed file systems allow multiple users to access and store files across a network as if they were on a local disk.
- **Benefits for large-scale data storage**
  - Scalability, fault tolerance, and high availability.
- **Popular distributed file systems**
  - **Hadoop Distributed File System (HDFS)**: Designed for large-scale data processing.
  - **Amazon S3**: Scalable object storage service.
- **Applications in autonomous vehicle data management**
  - Storing large volumes of video and sensor data for processing and analysis.

### Data Leaks
![Data Leaks](/images/data-leak.webp)
- **What is a data leak?**
  - A data leak is an unauthorized transmission of data from within an organization to an external destination or recipient.
- **Causes of data leaks**
  - Weak security measures, human error, system vulnerabilities, and malicious attacks.
- **Prevention strategies**
  - Implementing robust security protocols, regular audits, employee training, and using data leak prevention (DLP) software.
- **Real-world applications in self-driving car scenarios**
  - Protecting sensitive vehicle data, such as location information, sensor data, and personal information from unauthorized access.

### Interactive Section
![Interactive Section](/images/activity.jpeg)
- **Activity 1: Setting up a NoSQL database**
  - **Instructions**: Follow the MongoDB installation guide.
  - **Sample Data**: Insert sample JSON data related to vehicle logs.
  - **Query Examples**: Write and execute queries to retrieve specific log entries.
- **Activity 2: Working with Distributed File Systems**
  - **Setup**: Install Hadoop and configure HDFS.
  - **File Operations**: Upload a sample dataset and perform basic file operations (copy, move, delete).
- **Activity 3: Preventing Data Leaks**
  - **Setup**: Install and configure DLP software.
  - **Simulations**: Create scenarios to test the effectiveness of DLP measures.
  - **Analysis**: Review logs and reports to identify potential vulnerabilities.

## Resources
- [MongoDB Documentation](https://docs.mongodb.com/)
- [Hadoop Distributed File System Guide](https://hadoop.apache.org/docs/r1.2.1/hdfs_design.html)
- [Introduction to Data Leaks](https://www.imperva.com/learn/data-security/data-leak/)
- [AWS S3 Documentation](https://docs.aws.amazon.com/s3/index.html)
- [AWS Athena Documentation](https://docs.aws.amazon.com/athena/index.html)

## Q&A
If you have any questions or need further assistance, please feel free to ask during the Q&A session or reach out to us through our GitHub Issues page.

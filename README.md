# Scalable Data Storage Workshop

Welcome to the Scalable Data Storage Workshop organized for the students at Maple College by Autonomous Vehiculum. This workshop aims to introduce you to scalable data storage solutions and their applications in self-driving car scenarios. Let's dive into the technologies that make scalable data storage possible and explore practical implementations.

## Table of Contents
- [Overview](#overview)
- [Agenda](#agenda)
- [Workshop Sections](#workshop-sections)
  - [Introduction to Scalable Data Storage](#introduction-to-scalable-data-storage)
  - [NoSQL Databases](#nosql-databases)
  - [Distributed File Systems](#distributed-file-systems)
  - [Data Lakes](#data-lakes)
  - [Interactive Section](#interactive-section)
- [Resources](#resources)
- [Q&A](#qa)

## Overview
In this workshop, you will learn about scalable data storage solutions and their importance in self-driving car technologies. We will cover the following topics:
- Introduction to Scalable Data Storage
- NoSQL Databases
- Distributed File Systems
- Data Lakes

## Agenda
1. **Introduction**
   - Welcome and objectives
2. **Scalable Data Storage Overview**
   - Key concepts and importance
3. **NoSQL Databases**
   - Overview, use cases, and examples
4. **Distributed File Systems**
   - Explanation and benefits
5. **Data Lakes**
   - Definition, architecture, and applications
6. **Interactive Section**
   - Hands-on activities and exercises
7. **Q&A and Closing Remarks**

## Workshop Sections

### Introduction to Scalable Data Storage
- **What is scalable data storage?**
  - Scalable data storage refers to systems and methods that allow data storage capacity to grow and manage large volumes of data efficiently. It ensures that performance remains stable even as data scales.
- **Importance in autonomous vehicles**
  - Autonomous vehicles generate vast amounts of data from sensors, cameras, and other sources. Efficiently storing and managing this data is crucial for real-time processing and analysis.

### NoSQL Databases
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
- **Definition and explanation**
  - Distributed file systems allow multiple users to access and store files across a network as if they were on a local disk.
- **Benefits for large-scale data storage**
  - Scalability, fault tolerance, and high availability.
- **Popular distributed file systems**
  - **Hadoop Distributed File System (HDFS)**: Designed for large-scale data processing.
  - **Amazon S3**: Scalable object storage service.
- **Applications in autonomous vehicle data management**
  - Storing large volumes of video and sensor data for processing and analysis.

### Data Lakes
- **What is a data lake?**
  - A data lake is a centralized repository that allows you to store all your structured and unstructured data at any scale.
- **Architecture of data lakes**
  - Comprises raw data storage, data processing, and data consumption layers.
- **How data lakes differ from traditional data storage**
  - Unlike traditional data warehouses, data lakes can store raw data in its native format until needed.
- **Real-world applications in self-driving car scenarios**
  - Collecting and storing diverse data types from various sources for advanced analytics and machine learning.

### Interactive Section
- **Activity 1: Setting up a NoSQL database**
  - **Instructions**: Follow the MongoDB installation guide.
  - **Sample Data**: Insert sample JSON data related to vehicle logs.
  - **Query Examples**: Write and execute queries to retrieve specific log entries.
- **Activity 2: Working with Distributed File Systems**
  - **Setup**: Install Hadoop and configure HDFS.
  - **File Operations**: Upload a sample dataset and perform basic file operations (copy, move, delete).
- **Activity 3: Building a Data Lake**
  - **Structure**: Create a basic data lake architecture using AWS S3.
  - **Data Loading**: Load different types of data (text, images, logs).
  - **Analysis**: Use AWS Athena to query the data.

## Resources
- [MongoDB Documentation](https://docs.mongodb.com/)
- [Hadoop Distributed File System Guide](https://hadoop.apache.org/docs/r1.2.1/hdfs_design.html)
- [Introduction to Data Lakes](https://aws.amazon.com/big-data/datalakes-and-analytics/what-is-a-data-lake/)
- [AWS S3 Documentation](https://docs.aws.amazon.com/s3/index.html)
- [AWS Athena Documentation](https://docs.aws.amazon.com/athena/index.html)

## Q&A
If you have any questions or need further assistance, please feel free to ask during the Q&A session or reach out to us through our GitHub Issues page.

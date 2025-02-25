# Distributed Database Internals Course Materials

![CC BY-SY 4.0 logo](https://mirrors.creativecommons.org/presskit/buttons/80x15/png/by-sa.png)
![DOI](https://zenodo.org/badge/938955831.svg)](https://zenodo.org/badge/latestdoi/938955831)

Course materials for the graduate course ``Distributed Database Internals,``
which focuses on understanding the storage and networking layers of databases
with the goal of helping students understand the performance and reliability
tradeoffs of different approaches.  The course was originally developed and taught
by [RJ Nowling](https://rnowling.github.io/) at the
[Milwaukee School of Engineering](https://www.msoe.edu/) for the Master's in Machine
Learning program.

## Course Description
In some applications, data storage and processing needs have vastly exceeded what can be
accomplished using a single computer. A number of database and file systems that use
distributed computing techniques to provide enhanced scalability and reliability have
become available and been widely adopted. This course will cover software architectures,
algorithms, and practical implications of approaches for scaling storage systems to large
data sizes and high read/write throughputs, providing elasticity in the face of changing
loads, and reliability in the face of failures. Relevant papers will be reviewed alongside
case studies of industry and open-source implementations. Students will complete a
term-long project to implement a functional distributed storage system.

## Learning Outcomes
After completing this course, students will be able to:

* Storage Engines
    * L1: Understand the details of on-disk data structures such as B-trees and log-structured merge (LSM) trees in sufficient depth to explain the theoretical and practical performance of associated operations (e.g., insert, update, search, and read)
    * L2: Explain fundamental tradeoffs in read performance, write performance, and space utilization of data structures in accordance with the read-update-modify (RUM) conjecture
* Network Services and Concurrency
    * L3: Use non-blocking I/O patterns to implement a network server capable of serving multiple connections concurrently
    * L4: Explain how reader-writer and writer-writer conflicts manifest in databases executing multiple operations concurrently
    * L5: Explain the theoretical and practical trade offs of common solutions to concurrent access conflicts
* Distributed and Replicated Storage Systems
    * L6: Describe hashing-based techniques for associating data with partitions
    * L7: Describe the consensus problem and associated algorithms for maintaining consistency in a distributed databases
    * L8: Explain the practical and theoretical implementations of the CAP and PACELC theorems
* Analysis of Database Systems
    * L9: Analyze a database’s design and implementation to determine performance characteristics in terms of throughput versus latency; size versus number of concurrent queries; scalability with respect to number of connections, servers, and dataset sizes; and consistency versus availability and identify (in)appropriate workloads

## Repository Contents
This repository contains the following teaching materials:

* [Syllabus](Syllabus.docx)
* [Course schedule](Course_Schedule.xlsx) including assigned readings
* [Programming Projects](projects) in which students practice implementing concepts from the readings
* [Reading Introduction and Reflection Questions](readings)

## Licensing
The materials are licensed under the
[Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) license.

This license requires that reusers give credit to the creator. It allows reusers to distribute, remix, adapt, and build upon the material in any medium or format, even for commercial purposes. If others remix, adapt, or build upon the material, they must license the modified material under identical terms.

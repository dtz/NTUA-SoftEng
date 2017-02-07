# SoftEng
Software Engineering: Project

## Overview
This project was developed as part of Software Engineering Class at National Technical University of Athens (NTUA). The purpose was to extend SIP communicator client and JAIN SIP Proxy with 3 additional features using modern Software Engineering practices. These programs implement Session Initiation Protocol which is used among others for communication applications over Internet such as VoIP (Voice over IP).

The project consists of three phases:

1. SRS: Document describing in detail the application's software requirements both functional and non-functional in the form of UML diagrams (use case, sequence, interaction).
2. SDD: Document describing decisions on software architecture as well as the class diagram of the final application. A state diagram is also included describing state transitions under possible application use cases.
3. Implementation of the application according to the above described specifications with extensions to both frontend and backend parts.

## SIP Extensions
* **Call Forwarding**: User A can forward his/her calls to user B. In this case, when trying to reach user A, user's B phone will actually ring. There could be a chain of multiple forwarding calls but circles are not permitted.
* **Call Blocking**: User A can choose to block user's B calls. That means that when B is trying to reach A, user A seems to be unavailable.
* **Call Billing**: Users choose a billing policy from an available list and their calls are charged based on this policy. Only the caller is charged.

## Requirements
* Java >= 1.7
* JMF 2.1.1
* MySQL 5.x

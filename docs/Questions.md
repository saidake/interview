<!-----------------------------------------------------------
Author:  Craig Brown
Version: simi-docs-1.6.0
Source:  https://github.com/saidake/simi-docs
------------------------------------------------------------->
# Table of Contents
[Back to Main Project README](../README.md)  
- Java
  - [1. How does `AbstractQueuedSynchronizer` function internally?](#1-how-does-abstractqueuedsynchronizer-function-internally) 
- Internet
  - [2. How to solve CORS issue?](#2-how-to-solve-cors-issue) 
<!-- - Spring Boot  -->
  <!-- - [3. How to ensure Kafka messages are not lost?](#3-how-to-ensure-kafka-messages-are-not-lost) -->
## 1. How does `AbstractQueuedSynchronizer` function internally?  <!-- {4} -->
### References
* **Java.pdf / Java / java.base / java.util / concurrent / locks / AbstractQueuedSynchronizer**     
  1. State Management
  2. Node-based Queuing
  3. Exclusive and Shared Modes
  4. Condition Support
### Answer
AbstractQueuedSynchronizer is a utility for creating custom synchronizers in Java, using a node-based queue mechanism.

To customize lock behavior, implement `tryAcquire/tryRelease` for exclusive locks or `tryAcquireShared/tryReleaseShared` for shared locks. 
These methods define when a lock can be acquired or released.

The `state` field tracks the lock's status, and `AbstractQueuedSynchronizer` automatically manages the queue and wake-up process for waiting threads.

## 2. How to solve CORS issue?  <!-- {3-2} -->
### References
* **Internet.pdf / Network Model / Application Layer / HTTP (Hypertext Transfer Protocol) / Cross-domain communication**
  1. Same-Origin Policy (SOP)
  2. Cross-Origin Resource Sharing (CORS)
  3. Preflight Request
* **Config.pdf / Work Environment / nginx / Core / Proxy**     
  1. Forward Proxy (Normal Proxy)
  2. Reverse Proxy
### Answer
1. Return the necessary CORS headers for all requests directly from the server.
2. Configure the Nginx server to intercept both preflight and normal requests, adding the required CORS headers.

<!-- ## 3. How to ensure Kafka messages are not lost?
### References
* **DatabaseAndMiddleware / Kafka / Configuration / Leader Election**
  1. Assigned Replicas (AR)
  2. In-Sync Replicas (ISR)
  3. Out-of-Sync Replicas (OSR)

### Answer
1. Set `unclean.leader.election.enable` to `false` as OSR nodes may lack the latest messages, risking data loss if elected as the leader.

2. 

 -->





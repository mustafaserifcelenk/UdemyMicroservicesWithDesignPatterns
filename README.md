# You can see branches for design-patterns.

## Udemy Microservices With Design Patterns

### 1) Saga Choreography

![image](https://user-images.githubusercontent.com/72551126/216779818-27d2ea77-9448-47f9-9551-116cbbda14f1.png)

Each local transaction publishes domain events that trigger local transactions in other services.

### 2) Saga Orchestration 

![image](https://user-images.githubusercontent.com/72551126/216779879-1ec6e4cd-3235-4334-9e59-826caf9e837c.png)

An orchestrator (object) tells the participants what local transactions to execute.

### 3) Event Sourcing Pattern

![image](https://user-images.githubusercontent.com/72551126/216779923-d9559097-11fe-4932-a50e-c3914d0f2438.png)

Instead of storing just the current state of the data in a domain, use an append-only store to record the full series of actions taken on that data.

### 4) Resiliency Patterns

1. Retry Pattern: If an error occurs on a service request is re-send continuously. It is applied in cases where it is sure that the service will be up again in a short time.

2. Circuit-Breaker Pattern: If an error occurs on a service request is re-send periodically instead continuosly. 

## RUN

You can run design patterns by download related design pattern branch and add your connection strings in appsettings. 

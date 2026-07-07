# Round Robin Load Balancer

A Java distributed systems project developed as a university coursework assignment (year 2). The application simulates a client, a UDP based load balancer and multiple worker nodes to distribute jobs using a round robin scheduling approach.

> **Academic project:** This repository contains a university implementation created to demonstrate distributed systems concepts. It is not intended for production deployment.

## Features

* Client job submission
* UDP based communication between components
* Round robin distribution of jobs across worker nodes
* Worker node registration
* Heartbeat monitoring for worker availability
* Job queueing when no worker node is available
* Completion logging for processed jobs
* System status requests showing worker nodes, queued jobs and completed jobs

## Technologies Used

* Java
* UDP Sockets
* Multithreading
* Object Oriented Programming
* Queue Based Task Handling
* Distributed Systems Concepts

## Project Structure

```text
round-robin-load-balancer/
├── client/
│   └── src/
├── load-balancer/
│   └── src/
├── worker-node/
│   └── src/
├── README.md
└── .gitignore

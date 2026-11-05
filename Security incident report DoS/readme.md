# SYN Flood Attack – Security Incident Analysis

![Focus](https://img.shields.io/badge/Focus-Network%20Security-blue)
![Attack](https://img.shields.io/badge/Attack-DoS-red)

## Overview

A practical network security exercise focused on investigating a suspected TCP SYN flood attack affecting a web server.

The project involves analyzing TCP traffic logs, identifying malicious activity and explaining how a SYN flood can disrupt legitimate network connections.

## Investigation Tasks

- Analyzed TCP traffic and connection patterns.
- Identified repeated SYN requests targeting the server.
- Distinguished normal traffic from suspected attack activity.
- Investigated failed connections and TCP resets.
- Examined the TCP three-way handshake.
- Explained how SYN flooding exhausts server resources.
- Documented the incident and its potential impact.

## Key Findings

- Suspected SYN flood activity originating from `203.0.113.0`.
- Target server: `192.0.2.1`.
- Legitimate connections experienced failures and timeouts.
- The server's ability to handle new connections was disrupted.

## Tools & Technologies

- TCP log analysis
- Microsoft Excel
- TCP/IP
- HTTP

## Skills Demonstrated

Network traffic analysis, DoS attack identification, TCP troubleshooting, incident investigation and technical reporting.

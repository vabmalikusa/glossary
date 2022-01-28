---
title: mTLS (Mutual Transport Layer Security)
status: Completed
category: Concept
---

## What it is
Mutual TLS (mTLS) is a technique used to authenticate and encrypt messages sent between two [services](https://glossary.cncf.io/service/). Mutual TLS is the standard Transport Layer Security (TLS) protocol but, instead of validating the identity of just one connection, both sides are validated.

## Problem it addresses
[Microservices](https://glossary.cncf.io/microservices/) communicate over a network and, just like your wifi network, communication in transit over that network can be hacked. mTLS ensures that no unauthorized party can listen in on or impersonate legitimate requests.

## How it helps
mTLS ensures that traffic is secure and trusted in both directions between a client and server, providing an additional layer of security for users who log in to a network or applications. It also verifies connections with client devices that do not follow a login process, such as Internet of Things (IoT) devices. Attacks like on-path attacks, spoofing attacks, credential stuffing, brute force attacks, etc. can be prevented by mTLS.
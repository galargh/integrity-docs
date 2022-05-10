---
layout: page
title: About
permalink: /storage
---

This sections describes decentralized storage provider options within Starling Integrity project.

| <br><span style="float: right;">Provider</span><br/><span style="float: left;">Feature</span> | IPFS | Storj | Tahoe-LAFS |
| :-- | --- | --- | --- |
| **Geofencing** | | |
| **Allowlisting** | | |
| **Access Control** | | |
| **Content Erasure** | | |

# Geofencing

- 1st level being US vs. EU (via IP address or KYC)
- 2nd level being by country (via IP address or KYC)

# Allowlisting

- 1st level being that nodes have a persistent identity on the network, can be pseudonymous
- 2nd level being we have contact information via some KYC process that we can “call a node operator” to sort issues
- 3rd level being established orgs (like Internet Archive, etc.) are the only node operators (similar to how Lit imagines their validator network)

# Access Control

- 1st level being data everywhere, encryption key is only protection
- 2nd level being a static shared key to gate access of actual encrypted content (e.g. private ipfs swarm key)
- 3rd level being a dynamically provisioned, ACL-based, or revokable key to gate access of content (so leak keys have remedy)

# Content Erasure

A programatic way to signal an erasure of content on the network.

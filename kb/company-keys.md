---
layout: page
title: Company keys
permalink: /kb/company-keys
---

Starting with Antigen Plus 8.5, product licensing and PHI encryption is handled
using _company keys_.

A company key is an RSA-2048 key pair which is generated during product
registration. The key pair is stored in the Windows cryptographic key store on
each workstation running Antigen Plus. During registration, the user is also
prompted to save a copy of the key pair to a file named <code>Antigen Plus
company key for <i>Company</i>.APCompanyKey</code>.

## Importing company keys to additional workstations

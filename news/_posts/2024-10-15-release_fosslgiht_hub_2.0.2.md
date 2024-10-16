---
layout: post
title: Release FOSSLight Hub 2.0.2
description: >
  Release FOSSLight Hub 2.0.2
hide_last_modified: true
---


We’re excited to announce the release of FOSSLight Hub 2.0.2! 
This version is the official 2.0 release, 
including the new UI from the pre-release and significant database (DB) updates.

FOSSLight Hub 2.0 brings a more intuitive user interface (UI) and enhanced features for better usability. 
We’ve also included updates like Restriction data aligned with the Osori project and more.

Here’s a quick summary of the key changes:

- **Enhanced License and Open Source Information**
  - Restriction data updated for the Osori project 
  - Added Restriction and Source Code Disclosing Scope information to License data 
  - Added Restriction info to Open Source data 
  - Improved Open Source Vulnerability matching logic (including CPE, excluding CPE, version alias)

- **Schema Changes for Efficient Data Management**
  - Separated tables into OSS_COMMON and OSS_VERSION to streamline Open Source data management


Please note that there are several database-related changes in 2.0, 
so make sure to review the 
[Release Notes](https://github.com/fosslight/fosslight/blob/develop/RELEASE_NOTES.md#200-2024-09-27) before updating.

Currently, the latest version of FOSSLight Hub is 2.0.2. 
Here’s what’s been updated compared to previous versions:

- v2.0.1: A hotfix addressing an issue where jqGrid CDN could not load in 2.0.0.
- v2.0.2: Fixes for various issues, including save functionality, with performance improvements.
For more details, please check out the Release Notes for each version: 
([v2.0.1](https://github.com/fosslight/fosslight/blob/develop/RELEASE_NOTES.md#201-2024-09-30),
[v2.0.2](https://github.com/fosslight/fosslight/blob/develop/RELEASE_NOTES.md#201-2024-09-30)).

We recommend all FOSSLight 2.0 users use version 2.0.2. 
Since the 2.0 release includes many changes, we’re releasing frequent updates to ensure stability.
If you encounter any issues, please report them via [Github issue](https://github.com/fosslight/fosslight/issues)
We also welcome any contributions! 🤗

Thank you for your continued support and interest in the growth of FOSSLight Hub. 🙏

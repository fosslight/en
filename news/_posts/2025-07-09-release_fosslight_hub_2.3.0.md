---
layout: post
title: Release FOSSLight Hub 2.3.0 
description: >
  Release Hub 2.3.0 
hide_last_modified: true
---

The Fosslight Hub version 2.3.0 has been released. This update includes new features and several improvements.


**⭐️3rd Party**  
3rd Party Information Sheet has been added when exporting the FOSSLight Report, providing more comprehensive information about third-party components.

**⭐️Project**  
A new field has been added to Project Information for specifying the Security Responsible Person. They will also receive security-related emails from FOSSLight Hub along with creators and editors. Additionally, OSORI DB Information has been added to the Pre-Review > Open Source and License tabs, allowing users to view data from the OSORI database. The DEP Tab now features a Dependency Tree View that visualizes relationships between dependencies when analysis is performed using the FOSSLight Dependency Scanner.

**⭐️API**  
New APIs have been added to update Security Responsible Person information (/api/v2/projects/{id}/security-person) and Security Mail information (/api/v2/projects/{id}/security-mail). The user can now check their issued Token information in the User Settings menu within the FOSSLight Hub. Additional parameters have been added to existing APIs for enhanced functionality.

**⭐️Common**  
The Custom Column feature has been expanded and is now available in the Security tab, Project/3rd Party Identification, and Self-Check sections. A tab refresh feature has been added - if you enter a tab in any way other than clicking on the open tab at the top, a refresh pop-up will appear.

**⭐️Packaging**  
The number of uploadable OSS Package files has been increased from 4 to 5. When generating SPDX and CycloneDX documents, the output will be based on the package URL in the DEP tab, ensuring all relationships are displayed even when OSS Name and OSS Version are the same but package URLs differ. Support for CycloneDX 1.6 has been added.

**⭐️License, OSS**  
A Share URL button has been added, and the color of the Restriction icon now changes based on the level, providing better visual feedback to users.

**⭐️Security**  
The "Running on/with" information under CPE now displays OS information, providing more detailed system context for security analysis.


📦[Release Note](https://github.com/fosslight/fosslight/blob/develop/RELEASE_NOTES.md#230-2025-07-09)  
For more changes and bug fixes, please refer to the Release Notes.

With the enhanced features of FOSSLight 2.3.0, we expect to perform open source-related tasks more efficiently. We hope your valuable feedback will contribute to the development of FOSSLight. Please share your opinions with us!

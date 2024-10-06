---
layout: post
title: Release FOSSLight Hub 2.0.1
description: >
  Release FOSSLight Hub 2.0.1
hide_last_modified: true
---


FOSSLight Hub 2.0.1 Released!
We are excited to announce the release of FOSSLight Hub 2.0.1! 
This version marks the official 2.0 release, 
which not only includes the updates from the pre-release version with the new UI 2.0 
but also introduces significant changes related to the database (DB).

Key DB-Related Updates:

- Updated restriction data to align with the Badger project.
- Added restriction and source code disclosing scope information to license.
- Added restriction information to open source.
- Enhanced logic for improving open source vulnerability information matching (includes CPE, excludes CPE, version alias).

For more details on other changes, 
please refer to the [Release Notes](https://github.com/fosslight/fosslight/releases/tag/v2.0.0).

In addition, we identified a critical bug in version 2.0.0, 
where the jqGrid CDN was not being properly loaded. 
This issue has been resolved in the hotfix version 2.0.1. 
Please take note of this update.

---
layout: page
title: FOSSLight Scanner
description: >
  Introduce the FOSSLight Scanner.
hide_description: true
sitemap: false
permalink: /scanner/
---

* toc
{:toc}

## Introduction

![](../assets/img/fosslight_scanner_overview.png){: width="80%" .center}

FOSSLight Scanner can perform an analysis for open source compliance at once. It can perform open source analysis of source code, binary and dependency and generate the report that contains the open source information that can be extracted. You can use the report file with [FOSSLight Hub](/fosslight). Also, it can check whether an open source complies with the copyright/license writing rule.

## Features
<div class="row">
  <div class="column">
    <div class="feature_card">
      <div class="icon-wrapper">
        <i class="fa-solid fa-magnifying-glass"></i>
      </div>
      <h3>Improving<br>Analysis Accuracy</h3>
      <div class="feature_content">
        <p>It supports source code string detection and snippet matching, and also supports binary analysis as well as dependency analysis for various package managers to increase the accuracy of open source analysis.
        </p>
      </div>
    </div>
  </div>
  <div class="column">
    <div class="feature_card">
      <div class="icon-wrapper">
        <i class="fas fa-gears"></i>
      </div>
      <h3>Fast & Light Independent Module</h3>
      <div class="feature_content">
        <p>Each scanner can run independently, so you can run only the target you want to scan (ex, source code, binary, dependency) quickly and lightly.</p>
      </div>
    </div>
  </div>
  <div class="column">
    <div class="feature_card">
      <div class="icon-wrapper">
        <i class="fa-solid fa-share-nodes"></i>
      </div>
      <h3>Scalability<br>through Hub</h3>
      <div class="feature_content">
        <p>Output file of scanners is directly available in the Hub, so you can use the open source information management functions and also generate SBOM.</p>
      </div>
    </div>
  </div>
</div>

## Description

FOSSLight Scanner Projects **inherit** other open source projects.

- FOSSLight Prechecker can check reuse compliance by using the **[reuse-tool](https://github.com/fsfe/reuse-tool)**.
- FOSSLight Source Scanner can scan using the **[scancode-toolkit](https://github.com/nexB/scancode-toolkit)** and **[scanoss.py](https://github.com/scanoss/scanoss.py)**.
- FOSSLight Dependency Scanner can analyze the dependency using the following open source software.
  - NPM : **[NPM License Checker](https://github.com/davglass/license-checker)**
  - Pypi : **[pip-licenses](https://github.com/raimon49/pip-licenses)**
  - Gradle : **[License Gradle Plugin](https://github.com/hierynomus/license-gradle-plugin)**
  - Maven : **[license-maven-plugin](https://github.com/mojohaus/license-maven-plugin)**
  - Pub : **[flutter_oss_licenses](https://github.com/espresso3389/flutter_oss_licenses)**
  - Android(gradle) : **[android-dependency-scanning](https://github.com/fosslight/android-dependency-scanning)**
- FOSSLight Binary Scanner can analyze the open source info. in '.jar' file by using **[Dependency-check-py](https://github.com/jhermann/dependency-check-py)**.

## Scanner Projects

- [**FOSSLight Scanner**](https://github.com/fosslight/fosslight_scanner) (License: [**Apache-2.0**](https://github.com/fosslight/fosslight_scanner/blob/main/LICENSE))
- [**FOSSLight Prechecker**](https://github.com/fosslight/fosslight_prechecker) (License: [**GPL-3.0-only**](https://github.com/fosslight/fosslight_prechecker/tree/main/LICENSES))
- [**FOSSLight Source Scanner**](https://github.com/fosslight/fosslight_source_scanner) (License: [**Apache-2.0**](https://github.com/fosslight/fosslight_source_scanner/blob/main/LICENSE))
- [**FOSSLight Dependency Scanner**](https://github.com/fosslight/fosslight_dependency_scanner) (License: [**Apache-2.0**](https://github.com/fosslight/fosslight_dependency_scanner/blob/main/LICENSE))
- [**FOSSLight Binary Scanner**](https://github.com/fosslight/fosslight_binary_scanner) (License: [**Apache-2.0**](https://github.com/fosslight/fosslight_binary_scanner/blob/main/LICENSE))
- [**FOSSLight Yocto Scanner**](https://github.com/fosslight/fosslight_yocto_scanner) (License: [**Apache-2.0**](https://github.com/fosslight/fosslight_yocto_scanner/blob/main/LICENSE))
- [**FOSSLight Android Scanner**](https://github.com/fosslight/fosslight_android_scanner) (License: [**Apache-2.0**](https://github.com/fosslight/fosslight_android_scanner/blob/main/LICENSE))

<br/>
<br/>
<div class="right"><a href="https://icons8.com/icon">&lt;Icons by Icons8&gt;</a></div>

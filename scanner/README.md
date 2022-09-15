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

![](../assets/img/fosslight_scanner.png)

FOSSLight Scanner can perform an analysis for open source compliance at once. It can perform open source analysis of source code, binary and dependency and generate the report that contains the open source information that can be extracted. You can use the report file with [FOSSLight Hub](/fosslight). Also, it can check whether an open source complies with the copyright/license writing rule.

## Features

<div class="flex-container">
  <div class="flex-contents">
    <div>
      <div id="feature_title">
        Inclusive Scanning
      </div>
      <div id="feature_img">
        <img src="https://img.icons8.com/dotty/80/000000/check-all.png"/>
      </div>
      <div id="feature_content">
        It can detect source code, binary as well as dependency.
      </div>
    </div>
  </div>

  <div class="flex-contents">
    <div>
      <div id="feature_title">
        Integrated One
      </div>
      <div id="feature_img">
        <img src="https://img.icons8.com/wired/64/000000/workspace-one.png"/>
      </div>
      <div id="feature_content">
        It can work from one command line through a single integrated package.
      </div>
    </div>
  </div>

  <div class="flex-contents">
    <div>
      <div id="feature_title">
        Independent Module
      </div>
      <div id="feature_img">
        <img src="https://img.icons8.com/dotty/80/000000/module.png"/>
      </div>
      <div id="feature_content">
        The scanner module can be used independently and lightly.
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

<br/>
<br/>
<div class="right"><a href="https://icons8.com/icon">&lt;Icons by Icons8&gt;</a></div>

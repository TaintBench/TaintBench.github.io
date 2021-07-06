---
layout: page
title: TaintBench Framework
subtitle: Faster Construction, Automatic Evaluation, Easier Inspection
---
Along with the [TaintBench suite](taintbenchSuite.md), we contribute the TaintBench framework to the research community. The TaintBench framework is a set of tools that are designed to support benchmark suite construction, automatic evaluation of Android taint analysis tools and manual inspection of analysis results.  
# Part 1 -- Construction
The following tools support benchmark suite construction:
- ## TB-Extractor (Jadx Extension)
  - [Download](https://github.com/TaintBench/TaintBench/releases/download/TBFramework/TBExtractor-EMSE.zip)
  - [Source Code Repository (to appear)]()
- ## TB-Profiler 
  - [Download](https://github.com/TaintBench/TaintBench/releases/download/TBFramework/TB-Profiler-0.0.1-EMSE.zip)
  - [Source Code Repository (to appear)]()

# Part 2 -- Evaluation
The following tools support automatic evaluation of Android taint analysis tools:
- ## ReproDroid with TB-Loader
  - [Download](https://github.com/TaintBench/TaintBench/releases/download/TBFramework/BREW-2.0.0-SNAPSHOT-EMSE.zip)
  - [Source Code Repository (to appear)]()

- ## TB-Mapper
  - [Download](https://github.com/TaintBench/TaintBench/releases/download/TBFramework/TBSaSMapper-1.0-SNAPSHOT-EMSE.zip)
  - [Source Code Repository (to appear)]()

- ## DeltaApkGenerator
  - [Download](https://github.com/TaintBench/TaintBench/releases/download/TBFramework/DeltaApkGenerator-0.0.2-EMSE.zip)
  - [Source Code Repository (to appear)]()

- ## MinApkGenerator
  - [Download](https://github.com/TaintBench/TaintBench/releases/download/TBFramework/MinApkGenerator-0.0.1-SNAPSHOT-EMSE.zip)
  - [Source Code Repository (to appear)]()

# Part 3 -- Inspection
The following tools support manual inspection (triaging) of analysis results:
- ## TB-Viewer (Visual Studio Code Extension)
  - [Download](https://github.com/TaintBench/TaintBench/releases/download/TBFramework/TB-Viewer-0.0.1-EMSE.zip)
  - [Source Code Repository (to appear)]()

# User Study
We conducted a user study for the two GUI-based tools --- TB-Extractor and TB-Viewer. Our evaluation results show that experts document and inspect taint flows more efficiently when using the tools. Details about the user study can be found [here](userstudy.md).


**Notice**: Please cite the following paper if you are using TaintBench: 

@article{TaintBench2021, <br>
author = {Linghui Luo and Felix Pauck and Goran Piskachev and Manuel Benz and Ivan Pashchenko and Martin Mory and Eric Bodden and Ben Hermann and Fabio Massacci},<br>
title = {TaintBench: Automatic Real-World Malware Benchmarking of Android Taint Analyses}, <br>
year = {2021}, <br>
journal = {Empirical Software Engineering}, <br>
note = {to appear} <br>
}

** Disclaimer**
Your download and use of this benchmark suite are at your own risk.
We will not be liable for any loss or damage caused by malware or other technologically harmful material that may infect your computer equipment, computer programs, data or other proprietary material due to your use of the TaintBench suite, or in any way in conjunction with, the TaintBench suite.

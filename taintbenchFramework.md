---
layout: page
title: TaintBench Framework
subtitle: Faster Construction, Automatic Evaluation, Easier Inspection
---

# Part 1 -- Construction
The following tools support benchmark suite construction:
- ## TB-Extractor (Jadx Extension)
  [Download](https://github.com/TaintBench/TaintBench/releases/download/TBFramework/TBExtractor-EMSE.zip)

- ## TB-Profiler 
  [Download](https://github.com/TaintBench/TaintBench/releases/download/TBFramework/TB-Profiler-0.0.1-EMSE.zip)
 

# Part 2 -- Evaluation
The following tools support automatic evaluation of Android taint analysis tools:
- ## ReproDroid with TB-Loader
  [Download](https://github.com/TaintBench/TaintBench/releases/download/TBFramework/BREW-2.0.0-SNAPSHOT-EMSE.zip)
  
- ## TB-Mapper
  [Download](https://github.com/TaintBench/TaintBench/releases/download/TBFramework/TBSaSMapper-1.0-SNAPSHOT-EMSE.zip)
  
- ## DeltaApkGenerator
  [Download](https://github.com/TaintBench/TaintBench/releases/download/TBFramework/DeltaApkGenerator-0.0.2-EMSE.zip)
  
- ## MinApkGenerator
  [Download](https://github.com/TaintBench/TaintBench/releases/download/TBFramework/MinApkGenerator-0.0.1-SNAPSHOT-EMSE.zip)


# Part 3 -- Inspection
The following tools support manual inspection (triaging) of analysis results:
- ## TB-Viewer (Visual Studio Code Extension)
  [Download](https://github.com/TaintBench/TaintBench/releases/download/TBFramework/TB-Viewer-0.0.1-EMSE.zip)


# User Study
We conducted a user study for the two GUI-based tools --- TB-Extractor and TB-Viewer. Our evaluation results show that experts document and inspect taint flows more efficiently when using the tools. Details about the user study can be found [here](userstudy.md).
---
layout: page
title: Continuous Benchmarking
subtitle: Continuous Benchmarking with TaintBench
---
# Continuous Benchmarking of Android Taint Tools.
We set up GitHub Actions for the following Android Taint Tools. 
Using from the TaintBench framework, we configured the evaluation of each tool as an automated workflow of Github Actions.
The source and sink configuration of each tool is at app-level based on the benchmark cases in TaintBench.
The outcome of each workflow includes a benchmark file computed by BREW containing performance metrics (precision, recall, F-measure, analysis time) and raw analysis results of the tool.
| Status        |  GitHub Actions Workflow       | Latests Evaluation Results  |
| ------------- |:-------------:| -----:|
| ![Evaluate FlowDroid April 2017 Nightly](https://github.com/TaintBench/TaintBench/workflows/Evaluate%20FlowDroid%20April%202017%20Nightly/badge.svg)| [Workflow FlowDroid April 2017 Nightly](https://github.com/TaintBench/TaintBench/actions?query=workflow%3A%22Evaluate+FlowDroid+April+2017+Nightly%22)| [Results FlowDroid April 2017 Nightly](https://github.com/TaintBench/TaintBench/actions/runs/157028087)|
|![Evaluate FlowDroid 2.7.1](https://github.com/TaintBench/TaintBench/workflows/Evaluate%20FlowDroid%202.7.1/badge.svg)| [Workflow FlowDroid 2.7.1](https://github.com/TaintBench/TaintBench/actions?query=workflow%3A%22Evaluate+FlowDroid+2.7.1%22)| [Results FlowDroid 2.7.1](https://github.com/TaintBench/TaintBench/actions/runs/157028086)|
![Evaluate Amandroid 3.1.2](https://github.com/TaintBench/TaintBench/workflows/Evaluate%20Amandroid%203.1.2/badge.svg) |[Workflow Amandroid 3.1.2](https://github.com/TaintBench/TaintBench/actions?query=workflow%3A%22Evaluate+Amandroid+3.1.2%22) |[Results Amandroid 3.1.2]( https://github.com/TaintBench/TaintBench/actions/runs/157028088)|
|![Evaluate Amandroid 3.2.0](https://github.com/TaintBench/TaintBench/workflows/Evaluate%20Amandroid%203.2.0/badge.svg)|[Workflow Amandroid 3.2.0](https://github.com/TaintBench/TaintBench/actions?query=workflow%3A%22Evaluate+Amandroid+3.2.0%22)| [Results Amandroid 3.2.0](https://github.com/TaintBench/TaintBench/actions/runs/157028083)|




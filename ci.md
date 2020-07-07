---
layout: page
title: Continuous Benchmarking
subtitle: Continuous Benchmarking with TaintBench
---
# Continuous Benchmarking of Android Taint Tools
We set up GitHub Actions for the following Android Taint Tools. 
Using from the TaintBench framework, we configured the evaluation of each tool on TaintBench as an automated workflow of Github Actions.

Source and sink configuration (App-level):
- For each benchmark app, a list of sources and sinks defined in this app is used to configure the evaluated tool. Each tool analyzes each benchmark app with the associated list of sources and sinks.

Outcome of each workflow:
 - A benchmark result file containing performance metrics (precision, recall, F-measure, analysis time).
 - Raw analysis results outputed by the evaluated tool.


| Status        |  GitHub Actions Workflow       | Latests Evaluation Results  |
| ------------- |:-------------:| -----:|
| ![Evaluate FlowDroid April 2017 Nightly](https://github.com/TaintBench/TaintBench/workflows/Evaluate%20FlowDroid%20April%202017%20Nightly/badge.svg)| [Workflow FlowDroid April 2017 Nightly](https://github.com/TaintBench/TaintBench/actions?query=workflow%3A%22Evaluate+FlowDroid+April+2017+Nightly%22)| [Results FlowDroid April 2017 Nightly](https://github.com/TaintBench/TaintBench/actions/runs/157028087)|
|![Evaluate FlowDroid 2.7.1](https://github.com/TaintBench/TaintBench/workflows/Evaluate%20FlowDroid%202.7.1/badge.svg)| [Workflow FlowDroid 2.7.1](https://github.com/TaintBench/TaintBench/actions?query=workflow%3A%22Evaluate+FlowDroid+2.7.1%22)| [Results FlowDroid 2.7.1](https://github.com/TaintBench/TaintBench/actions/runs/157028086)|
![Evaluate Amandroid 3.1.2](https://github.com/TaintBench/TaintBench/workflows/Evaluate%20Amandroid%203.1.2/badge.svg) |[Workflow Amandroid 3.1.2](https://github.com/TaintBench/TaintBench/actions?query=workflow%3A%22Evaluate+Amandroid+3.1.2%22) |[Results Amandroid 3.1.2]( https://github.com/TaintBench/TaintBench/actions/runs/157028088)|
|![Evaluate Amandroid 3.2.0](https://github.com/TaintBench/TaintBench/workflows/Evaluate%20Amandroid%203.2.0/badge.svg)|[Workflow Amandroid 3.2.0](https://github.com/TaintBench/TaintBench/actions?query=workflow%3A%22Evaluate+Amandroid+3.2.0%22)| [Results Amandroid 3.2.0](https://github.com/TaintBench/TaintBench/actions/runs/157028083)|




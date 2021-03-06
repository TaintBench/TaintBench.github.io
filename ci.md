---
layout: page
title: Continuous Benchmarking
subtitle: Continuous Benchmarking with TaintBench
---
# Continuous Benchmarking of Android Taint Tools
Considering the future extension of the TaintBench suite, we set up GitHub Actions for continuous benchmarking of the following Android taint tools. 
- FlowDroid April 2017 Nightly
- FlowDroid 2.7.1
- Amandroid 3.1.2
- Amandroid 3.2.0

Using tools from the TaintBench framework, we configured the evaluation of each tool on TaintBench as an automated workflow of Github Actions.

Source and sink configuration (App-level) in a workflow:
- For each benchmark app, a list of sources and sinks defined in this app is used to configure the evaluated tool. Each tool analyzes each benchmark app with the associated list of sources and sinks.

Outcome of each workflow:
 - A benchmark result file containing performance metrics (precision, recall, F-measure, analysis time).
 - Raw analysis results outputed by the evaluated tool.


| Status        |  GitHub Actions Workflow       | Latests Evaluation Results  |
| ------------- |:-------------:| -----:|
| ![Evaluate FlowDroid April 2017 Nightly](https://github.com/TaintBench/TaintBench/workflows/Evaluate%20FlowDroid%20April%202017%20Nightly/badge.svg)| [Workflow FlowDroid April 2017 Nightly](https://github.com/TaintBench/TaintBench/actions/workflows/workflowfdold.yml)| [Results FlowDroid April 2017 Nightly](https://github.com/TaintBench/TaintBench/actions/runs/613671652)|
|![Evaluate FlowDroid 2.7.1](https://github.com/TaintBench/TaintBench/workflows/Evaluate%20FlowDroid%202.7.1/badge.svg)| [Workflow FlowDroid 2.7.1](https://github.com/TaintBench/TaintBench/actions/workflows/workflowfd271.yml)| [Results FlowDroid 2.7.1](https://github.com/TaintBench/TaintBench/actions/runs/613671647)|
![Evaluate Amandroid 3.1.2](https://github.com/TaintBench/TaintBench/workflows/Evaluate%20Amandroid%203.1.2/badge.svg) |[Workflow Amandroid 3.1.2](https://github.com/TaintBench/TaintBench/actions/workflows/workflowad312.yml) |[Results Amandroid 3.1.2]( https://github.com/TaintBench/TaintBench/actions/runs/613671654)|
|![Evaluate Amandroid 3.2.0](https://github.com/TaintBench/TaintBench/workflows/Evaluate%20Amandroid%203.2.0/badge.svg)|[Workflow Amandroid 3.2.0](https://github.com/TaintBench/TaintBench/actions/workflows/workflowad320.yml)| [Results Amandroid 3.2.0](https://github.com/TaintBench/TaintBench/actions/runs/613671646)|



# New contributions are welcome!
TaintBench serves as a starting point for automatic benchmarking of Android taint analysis tools. 
We welcome new contributions to TaintBench. 

### Contribute a new finding to an existing benchmark app
If you find more taint flows in a TaintBench benchmark app. Please document it with [TB-Extractor](https://taintbench.github.io/taintbenchFramework) in [TAF-format](https://github.com/TaintBench/TaintBench/blob/master/TAF-schema.json) and make a pull request to the GitHub repositiory of the benchmark app.  

### Contribute a new benchmark app to the TaintBench suite
Please contact us by leaving an issue [here](https://github.com/TaintBench/TaintBench/issues).  

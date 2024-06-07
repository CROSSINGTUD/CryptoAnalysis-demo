# Demo for the github Action of CryptoAnalysis - executed on CamBench
This repository is a demo on how to integrate the on github Action of [CryptoAnalysis](https://github.com/CROSSINGTUD/CryptoAnalysis) into a reposity.
This demo is performed on [CamBench](https://github.com/CROSSINGTUD/CamBench) as it provides labeled examples of cryptographic API misuses and correct usages in [CamBench_Cap](https://github.com/CROSSINGTUD/CamBench/tree/main/CamBench_Cap)
The github action is configured in [cognicrypt.yml](https://github.com/CROSSINGTUD/CryptoAnalysis-demo/blob/main/.github/workflows/cognicrypt.yml) and executed in [pull requests](https://github.com/CROSSINGTUD/CryptoAnalysis-demo/pull/1). More detailed results can be seen in the [workflow's summary](https://github.com/CROSSINGTUD/CryptoAnalysis-demo/actions/runs/8359083312).



# CamBench - Cryptographic API Misuse Detection Tool Benchmark

![](./logos/CamBench.png)

CamBench envisions to be a comprehensive benchmark for cryptographic API misuse detection tools consisting of three components: 
- CamBench_Real includes real-world Java applications with manually labeled usages. 
- CamBench_Cap includes synthetic test cases to cover analysis capabilities.
- CamBench_Cov is a heuristic for crypto API coverage. 

CamBench is accepted as [a registered report at MSR 22](https://conf.researchr.org/track/msr-2022/msr-2022-registered-reports?#event-overview) [^1].
If you are interested in the progress of CamBench, please watch the repository or reach out to us. 
If you want to contribute to CamBench, feel free to raise an issue or contact us. 


## Project structure

- *logos* contains the CamBench logo 
- *presentations* contains the various slides we used to present CamBench

[^1] Schlichtig, M., Wickert, A. K., Krüger, S., Bodden, E., & Mezini, M. (2022). CamBench--Cryptographic API Misuse Detection Tool Benchmark Suite. arXiv preprint [arXiv:2204.06447](https://arxiv.org/abs/2204.06447).

## License

The artwork and logos of the projects are licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

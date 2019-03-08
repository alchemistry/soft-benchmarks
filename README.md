# "Soft benchmarks" for binding free energy calculations

This repository is for benchmark sets for assessing the overall performance of binding free energy calculations; the intention is for the community to be able to develop a series of standard tests of these calculations. 
A particular focus is on alchemical free energy calcualtions, but the files and systems here may be useful more broadly.

The intention here is to begin providing well-curated sets which can be used widely to assess overall performance of these calculations.

To some extent, this work builds on and spins off from the perpetual review paper [("Predicting binding free energies: Frontiers and benchmarks (a perpetual review)"](https://github.com/mobleylab/benchmarksets) and associated repository, and it attempts to use some of the same terminology introduced there for consistency.
Here, for shorthand, we will refer to this perpetual review paper as the "benchmarksets" paper.  

## Terminology

The benchmarksets paper introduced the following categories of benchmarks (which have different uses, as further detailed below):
- **Hard benchmarks**: Benchmark systems where convincingly converged results can be generated relatively readily, allowing a variety of quantitative tests and comparisons.
- **Soft benchmarks**: Systems where convincingly converged results *cannot* readily be generated, but which nevertheless may still be useful if subjected to concerted study

### Hard benchmarks serve a variety of uses

Several key uses may be noted for hard benchmarks:
- **Correctness**: *Systems to test software implementation and usage.* -- essentially, validating correctness of protocols and codes by comparison to known, gold-standard results.
- **Performance**: *Systems to check sampling correctness and efficiency* -- assessing performance, e.g. how quickly a given protocol or method converges.
- **Accuracy**: *Systems to assess force field (or other) accuracy* -- assessing how well a set of well converged results on a system (given a particular force field and system preparation) agree with experiment.

All of these require well converged results, otherwise it can be impossible to separate these aspects.

### Soft benchmarks may also be valuable

The benchmarksets review highlighted several uses of systems which cannot be convincingly converged. Such systems, it noted, may also be useful for:
- *Sampling assessment*: Challenging conformational sampling techniques
- *Error assessment*: Direct tests of the overall error of binding free energy calculations

**This repository is especially focused on the latter case -- assessing typical error in applications to somewhat challenging systems.** 
For real-world applications, end users want to know how well free energy techniques are likely to do in typical applications, regardless of whether the errors are from incorrect protocols, slow convergence, inadequate sampling, or force field or system preparation errors. 
For this, we need appropriate "soft benchmark" systems with high quality experimental data that are hopefully representative of such applications.

## Manifest


## Contributors
- David L. Mobley (UCI)

(Please add your name here if you contribute significantly)

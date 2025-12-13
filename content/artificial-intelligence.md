---
title: Artificial Intelligence
created: 2025-12-04, 12:33:20
modified: 2025-12-04, 15:43:58
---

> Machine learning, deep learning

## Organizations

- [FluxML](https://fluxml.ai/)
- [Julia AI (Alan Turing Institute)](https://github.com/JuliaAI)
- [Julia ML](https://juliaml.github.io)

## Resources

- [An evaluation of Deep Learning Frameworks](https://github.com/zer0n/deepframeworks)
- [Caltech's machine learning course](https://home.work.caltech.edu/telecourse.html) by Prof. Yaser Abu-Mostafa with videos on Youtube.
- [Examples from Thoughtful Machine Learning](https://github.com/thoughtfulml/examples)
- [Grokking Deep Learning with Julia](https://github.com/deepaksuresh/Grokking-Deep-Learning-with-Julia)
- [machine-learning-cheat-sheet](https://github.com/soulmachine/machine-learning-cheat-sheet) : Classical equations and diagrams in machine learning by @soulmachine.
- [Machine Learning in Julia 2020](https://github.com/ablaom/MachineLearningInJulia2020)
- [mlpnnets.jl](https://github.com/tautologico/learning/blob/master/nnets/mlp/julia/mlpnnets.jl) : Feed-forward MLP neural network implementation.

## Machine Learning Frameworks

- [AutoMLPipeline.jl](https://github.com/IBM/AutoMLPipeline.jl) : a package to create complex ML pipeline structures using simple expressions.
- [CombineML.jl](https://github.com/ppalmes/CombineML.jl) : Create ensembles of machine learning models from scikit-learn, caret, and julia.
- [EasyML.jl](https://github.com/OML-NPA/EasyML.jl) : Using machine learning in Julia through a graphical user interface.
- [Lux.jl](https://github.com/LuxDL/Lux.jl) : A explicitly parameterized neural network using deeply nested named tuples.
- [PredictMD.jl](https://github.com/bcbi/PredictMD.jl) : Uniform interface for machine learning in Julia. It is the official machine learning framework of the [Brown Center for Biomedical Informatics](https://github.com/bcbi).

### Flux

[Flux.jl](https://github.com/FluxML/Flux.jl) : Pure Julia ML stack with lightweight abstractions on top of Julia's native GPU and AD support.

- [FastAI.jl](https://github.com/FluxML/FastAI.jl) : Repository of best practices for deep learning in Julia, inspired by [fastai](http://docs.fast.ai/).
- [FluxTraining.jl](https://github.com/FluxML/FluxTraining.jl) : A powerful, extensible neural net training backend.
- [GeometricFlux.jl](https://github.com/FluxML/GeometricFlux.jl) : Geometric Deep Learning for `Flux.jl`.
- [model-zoo](https://github.com/FluxML/model-zoo) : Various demonstrations of the `Flux.jl` machine learning library.

### Knet

[Knet.jl](https://github.com/denizyuret/Knet.jl) : Koç University deep learning framework - A machine learning module implemented in Julia.

- [KnetNLP](https://github.com/egeersu/KnetNLP) : NLP examples in Knet.
- [KnetOnnx.jl](https://github.com/egeersu/KnetOnnx.jl) : ONNX integration with Knet.

### MLJ

[MLJ.jl](https://github.com/JuliaAI/MLJ.jl) : A Julia machine learning framework by The Alan Turing Institute.

- [MLJLinearModels.jl](https://github.com/JuliaAI/MLJLinearModels.jl): Generalized Linear Regressions Models for MLJ.

### Bindings for external libraries

- [LIBLINEAR.jl](https://github.com/JuliaML/LIBLINEAR.jl) : Julia binding to [Liblinear](https://github.com/cjlin1/liblinear), a library for Large Linear Classification.
- [LIBSVM.jl](https://github.com/JuliaML/LIBSVM.jl) : Julia bindings for [LIBSVM](https://github.com/cjlin1/libsvm) C library.
- [ONNX.jl](https://github.com/FluxML/ONNX.jl) : Read [ONNX](https://onnx.ai/) graphs and load these models in Julia.
- [ONNXNaiveNASflux.jl](https://github.com/DrChainsaw/ONNXNaiveNASflux.jl) : Import/export ONNX models for `Flux.jl`.
- [ONNXRunTime.jl](https://github.com/jw3126/ONNXRunTime.jl) : Julia bindings for the [onnxruntime](https://github.com/microsoft/onnxruntime) to perform inference.
- [ScikitLearn.jl](https://github.com/cstjean/ScikitLearn.jl) : Julia implementation of the [scikit-learn](http://scikit-learn.org/) API via `PyCall.jl`.
- [XGBoost.jl](https://github.com/dmlc/XGBoost.jl) : a Julia interface of [XGBoost](https://github.com/dmlc/xgboost), an efficient and scalable implementation of distributed gradient boosting framework. [Julia Con 2023 Video](https://www.youtube.com/watch?v=d5v4ELN3NSc)

## Clustering

- [Clustering.jl](https://github.com/JuliaStats/Clustering.jl): Basic functions for clustering data e.g, k-means, dp-means, etc..
- [DecisionTree.jl](https://github.com/JuliaAI/DecisionTree.jl) : Julia implementation of Decision Tree (CART) and Random Forest algorithms.
- [EvoTrees.jl](https://github.com/Evovest/EvoTrees.jl) : Boosted decision trees in Julia.
- [NearestNeighbors.jl](https://github.com/KristofferC/NearestNeighbors.jl) : High performance nearest neighbor data structures and algorithms for Julia.
- [UMAP.jl](https://github.com/dillondaudert/UMAP.jl) : Uniform Manifold Approximation and Projection ([UMAP](https://arxiv.org/abs/1802.03426)) implementation in Julia.

## Dataset Utilities

- [Discretizers.jl](https://github.com/sisl/Discretizers.jl) : A package to support discretization methods and mapping functions for data discretization and label maps.
- [MLDatasets.jl](https://github.com/JuliaML/MLDatasets.jl) : Utility package for accessing common Machine Learning datasets in Julia.
- [MLLabelUtils.jl](https://github.com/JuliaML/MLLabelUtils.jl) : Utility package for working with classification targets and label-encodings.

## Misc

- [Boltzmann.jl](https://github.com/dfdx/Boltzmann.jl) : Restricted Boltzmann Machines and Deep Belief Networks in Julia
- [ExplainableAI.jl](https://github.com/Julia-XAI/ExplainableAI.jl) : Explainable AI in Julia.
- [InvertibleNetworks.jl](https://github.com/slimgroup/InvertibleNetworks.jl) : Building blocks for invertible neural networks in the Julia programming language.
- [KernelFunctions.jl](https://github.com/JuliaGaussianProcesses/KernelFunctions.jl) : Kernel functions for machine learning.
- [LossFunctions.jl](https://github.com/JuliaML/LossFunctions.jl) : Julia package of loss functions for machine learning. [Documentation](https://juliaml.github.io/LossFunctions.jl/stable)
- [NetworkLearning.jl](https://github.com/zgornel/NetworkLearning.jl) : Baseline collective classification library, including observation-based learning and entity-based learning.
- [NeuralVerification.jl](https://github.com/sisl/NeuralVerification.jl) : verifying whether a neural network satisfies certain input-output constraints. [JuliaCon 2021 video](https://youtu.be/jyC2fVmHcF8).
- [PrivateMultiplicativeWeights.jl](https://github.com/mrtzh/PrivateMultiplicativeWeights.jl) : [Differentially private synthetic data](https://www.nist.gov/blogs/cybersecurity-insights/differentially-private-synthetic-data).
- [SimulatedNeuralMoments.jl](https://github.com/mcreel/SimulatedNeuralMoments.jl) : Bayesian and classical estimation and inference based on statistics that are filtered through a trained neural net.
- [SumProductNetworks.jl](https://github.com/trappmartin/SumProductNetworks.jl) : Sum-Product Networks (deep probabilistic networks) package in Julia.
- [TopoChains.jl](https://github.com/irhum/TopoChains.jl) : A flexible data structure for multi-input multi-output models.
- [ValueHistories.jl](https://github.com/JuliaML/ValueHistories.jl) : Utilities to efficiently track learning curves or other optimization information.

## Reinforcement Learning (RL)

[Wikipedia: Reinforcement Learning](https://en.wikipedia.org/wiki/Reinforcement_learning)

- [ReinforcementLearning.jl](https://github.com/JuliaReinforcementLearning/ReinforcementLearning.jl) : A Reinforcement Learning package. Introduction: [ReinforcementLearningAnIntroduction.jl](https://github.com/JuliaReinforcementLearning/ReinforcementLearningAnIntroduction.jl)

## Natural language processing (NLP)

- [Wikipedia: Natural language processing](https://en.wikipedia.org/wiki/Natural_language_processing)
- [JuliaText organization](https://github.com/JuliaText)

---

- [AdaGram.jl](https://github.com/sbos/AdaGram.jl) : Adaptive Skip-gram implementation in Julia.
- [BKTrees.jl](https://github.com/JuliaNeighbors/BKTrees.jl) : Julia implementation of Burkhard-Keller trees.
- [ConceptnetNumberbatch.jl](https://github.com/zgornel/ConceptnetNumberbatch.jl) : Julia interface to [ConceptnetNumberbatch](https://github.com/commonsense/conceptnet-numberbatch).
- [CorpusLoaders.jl](https://github.com/JuliaText/CorpusLoaders.jl) : A variety of loaders for various NLP corpora.
- [DependencyTrees.jl](https://github.com/dellison/DependencyTrees.jl) : A package for dependency parsing.
- [GloVe.jl](https://github.com/domluna/GloVe.jl) : Implements Global Word Vectors.
- [Glowe.jl](https://github.com/zgornel/Glowe.jl) : Julia interface to Global Word Vectors.
- [Languages.jl](https://github.com/JuliaText/Languages.jl) : A package for working with human languages.
- [ParserCombinator.jl](https://github.com/andrewcooke/ParserCombinator.jl) : A parser combinator library.
- [StringAnalysis.jl](https://github.com/zgornel/StringAnalysis.jl) : A hard fork of the `TextAnalysis.jl` package, designed to provide a richer, faster and orthogonal API.
- [TextAnalysis.jl](https://github.com/JuliaText/TextAnalysis.jl) : A Julia package for text analysis.
- [TopicModels.jl](https://github.com/slycoder/TopicModels.jl) : Topic models are Bayesian, hierarchical mixture models of discrete data.
- [Word2Vec.jl](https://github.com/JuliaText/Word2Vec.jl) : Julia interface to [word2vec](https://code.google.com/archive/p/word2vec/).
- [WordNet.jl](https://github.com/JuliaText/WordNet.jl) : A Julia package for Princeton's [WordNet®](https://wordnet.princeton.edu/).

### English

- [EnglishText.jl](https://github.com/TotalVerb/EnglishText.jl) : Utilities for English-language quirks in Julia.
- [Why.jl](https://github.com/TorkelE/Why.jl) : A simple function, `why()`, which gives randomly generated answers.

## Spiking neural network

[Wikipedia: Spiking neural network](https://en.wikipedia.org/wiki/Spiking_neural_network)

See also: [[health#Neuroscience]]

---

- [Conductor.jl](https://github.com/wsphillips/Conductor.jl) : a Julia-based neuronal network simulator engine.
- [Neuroblox.jl](https://github.com/Neuroblox/Neuroblox.jl) : Multi-scale computational neuroscience models. [JuliaCon 2025](https://youtu.be/_chc1i8DEnI)
- [NeuronBuilder.jl](https://github.com/Dhruva2/NeuronBuilder.jl) : building small networks of detailed, conductance-based neurons out of ion channels and synapses.
- [SpikeSynchrony.jl](https://github.com/JuliaNeuroscience/SpikeSynchrony.jl) : Measuring distances, synchrony and correlation between spike trains.
- [SpikingNeuralNetworks.jl](https://github.com/JuliaSNN/SpikingNeuralNetworks.jl) : Julia Spiking Neural Network Simulator.
- [WaspNet.jl](https://github.com/leaflabs/WaspNet.jl) : fixed-time-step simulations of primarily spiking neural networks (SNNs).

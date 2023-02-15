# Awesome software for AutoML [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome AutoML frameworks.

## Frameworks and libraries

### :snake: Python

#### Machine Learning

* [TPOT - Data Science Assistant](https://github.com/EpistasisLab/tpot) - A Python Automated Machine Learning tool that optimizes machine learning pipelines using genetic programming. http://epistasislab.github.io/tpot/

* [Featuretools](https://github.com/Featuretools/featuretools) - An open source python framework for automated feature engineering. https://www.featuretools.com

* [Auto-sklearn](https://github.com/automl/auto-sklearn) - Automated Machine Learning with scikit-learn<sup>1</sup>. https://automl.github.io/auto-sklearn

* [Lightwood](https://github.com/mindsdb/lightwood) - Lightwood is Legos for Machine Learning.

* [MindsDB Native](https://github.com/mindsdb/mindsdb) - Machine Learning in one line of code. http://mindsdb.com

* [mljar-supervised](https://github.com/mljar/mljar-supervised) - Automated Machine Learning for Supervised Tasks: Binary Classification, MultiClass Classification and Regression (work in progress). https://mljar.com

#### Deep learning

* [Auto-Keras](https://github.com/keras-team/autokeras) - Accessible AutoML for deep learning. http://autokeras.com/

* [NNI](https://github.com/microsoft/nni) - An open source AutoML toolkit for neural architecture search and hyper-parameter tuning. https://nni.readthedocs.io/en/latest/

* [AdaNet](https://github.com/tensorflow/adanet) - Fast and flexible AutoML with learning guarantees. https://adanet.readthedocs.io

* [Ludwig](https://github.com/uber/ludwig) - Ludwig is a toolbox built on top of TensorFlow that allows to train and test deep learning models without the need to write code. http://ludwig.ai

* [darts](https://github.com/quark0/darts) - Differentiable architecture search for convolutional and recurrent networks. https://arxiv.org/abs/1806.09055

#### Hybrid solutions

* [automl-gs](https://github.com/minimaxir/automl-gs) - Provide an input CSV and a target field to predict, generate a model + code to run it. https://github.com/minimaxir/automl-gs

* [MLBox](https://github.com/AxeldeRomblay/MLBox) - MLBox is a powerful Automated Machine Learning python library. https://mlbox.readthedocs.io/en/latest/

* [mindsdb](https://github.com/mindsdb/mindsdb) - In-Database Machine Learning. MindsDB automates and abstracts machine learning models through virtual AI Tables.

### R

#### Machine Learning

* [forester](https://github.com/ModelOriented/forester) - Full automation of the process of training tree-based models, wrapped into a single `train()` function.

#### Deep learning

* [R interface to Auto-Keras](https://github.com/jcrodriguez1989/autokeras) - Package: R interface to Auto-Keras. http://autokeras.com/

### Scala

#### Machine Learning

* [TransmogrifAI](https://github.com/salesforce/TransmogrifAI) - is an AutoML library for building modular, reusable, strongly typed machine learning workflows on Apache Spark with minimal hand-tuning. https://transmogrif.ai

### Java

#### Machine Learning

* [Glaucus](https://github.com/ccnt-glaucus/glaucus) - A general data-flow-based machine learning suit combining auto machine learning and multiple simplified machine learning algorithm for "unprofessional" data scenitists

## Supplementary tools

### Java

* [Fione: Fess AutoML](https://github.com/codelibs/fione) -  AutoML extension for Fess.

### Python

* [PocketFlow](https://github.com/Tencent/PocketFlow) - An Automatic Model Compression (AutoMC) framework for developing smaller and faster AI applications. https://pocketflow.github.io

* [Ray](https://github.com/ray-project/ray) - A fast and simple framework for building and running distributed applications. Ray is packaged with RLlib, a scalable reinforcement learning library, and Tune, a scalable hyperparameter tuning library. https://ray.readthedocs.io/en/latest/

* [SMAC3](https://github.com/automl/SMAC3) - Sequential Model-based Algorithm Configuration. https://www.automl.org/automated-algorithm-design/algorithm-configuration/smac/

<sup>1</sup>*Warning: auto-sklearn seems to be unstable at the moment - Travis build is failing and lot of unresolved issues (>100)*

# TensorFlow Gradient Boosted Trees

A standalone Python export of a TensorFlow Estimator example that trains a boosted-tree classifier and regressor on the Boston Housing dataset.

## Compatibility

This example uses the legacy TensorFlow Estimator API. Use Python 3.10 with the pinned dependencies in `requirements.txt`; newer TensorFlow releases and the active Python 3.14 interpreter are not supported by this setup.

```bash
python -m pip install -r requirements.txt
python gradient_boosted_trees.py
```

The Keras Boston Housing dataset is downloaded on the first run, so setup and execution require internet access. The script trains both models and prints their evaluation results. It disables GPU visibility because this Estimator GBDT example is CPU-oriented.

## Attribution

The notebook identifies Aymeric Damien and the [TensorFlow-Examples project](https://github.com/aymericdamien/TensorFlow-Examples/) as the original author and source. This repository preserves that attribution while exporting the notebook code cells to a Python script.
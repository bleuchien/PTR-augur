# Notebooks

- *data_preprocessing\*.ipynb* : raw data manipulation, update, encoding and export
- *neuralnet.ipynb* : preliminary tests on different neural network architectures
- *neuralnet2\*.ipynb* : network optimizations
- *neuralnet-[batch, batch2, ragged, unsorted].ipynb* : tests with different batch sizes, input sorting effects on the neural networks and ragged tensor creation
- *neuralnet_baseline.ipynb* : selected model training and evaluation on the small dataset
- *neuralnet_baseline-opt2.ipynb* : further model optimizations, training and evaluation
- *neuralnet_full.ipynb* : selected model training and evaluation on the full dataset
- *neuralnet_full-opt2.ipynb* : training and evaluation with optimized model and full dataset
- *tests\*.ipynb* : variety of tests
- *\*.keras* : trained and evaluated models

# Pyton Environment and Jupyter Lab

The virtual environment to run the notebooks can be created by

```
$ python -m venv .venv
$ source .venv/bin/activate
$ pip install -r requirements.txt
```

and Jupyter lab run the usual way

```
$ jupyter lab
```
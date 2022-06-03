<a href="https://user-images.githubusercontent.com/13848158/154338760-edfe1885-06f3-4e02-87fe-4b13a403516b.png"><img src="https://user-images.githubusercontent.com/13848158/154338760-edfe1885-06f3-4e02-87fe-4b13a403516b.png" title="source: imgur.com" /></a>

Ludwig is a toolbox built on top of TensorFlow that allows users to train and test deep learning models without the need to write code.

All you need to provide is a dataset file containing your data, a list of columns to use as inputs, and a list of columns to use as outputs, Ludwig will do the rest. Simple commands can be used to train models both locally and in a distributed way, and to use them to predict new data.

A programmatic API is also available in order to use Ludwig from your python code. A suite of visualization tools allows you to analyze models' training and test performance and to compare them.

### Why use Aim

`Aim` is an open-source, self-hosted ML experiment tracking tool. It's good at tracking lots (1000s) of training runs and it allows you to compare them with a performant and beautiful UI.

You can use not only the great Aim UI but also its SDK to query your runs' metadata programmatically. That's especially useful for automations and additional analysis on a Jupyter Notebook.

Aim's mission is to democratize AI dev tools.

### Using Aim with Ludwig

Aim allows for seamless integration into the inner backend of ludwig (training/inference pipelines) and allows you to track your experiments with in-depth granularity.
For the demo please observe the notebook embedded within the repo.

Training is easy:
`ludwig train --dataset DATA_PATH --config_file CONFIG_PATH --aim`

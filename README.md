# Malicious URL detection with datasets comparison
[![Python](https://img.shields.io/badge/python-3.6-blue.svg?style=flat-square)](https://docs.python.org/3/)



## Quickstart

### On Windows
Use Python 3.4, 3.5 or 3.6 (compatibility with Tensorflow)

```bash
python -m venv venv
venv\Scripts\activate.bat
pip install -r requirements.txt
```

## Datasets
[Dataset 1](https://github.com/faizann24/Using-machine-learning-to-detect-malicious-URLs/blob/master/data/data.csv): Unbalanced dataset with 80% safe URLs, 20% malicious - repeated URLs

[Dataset 2](https://github.com/incertum/cyber-matrix-ai/blob/master/Malicious-URL-Detection-Deep-Learning/data/url_data_mega_deep_learning.csv): Balanced dataset

## Credits
The code here is based on the work of the following people:
- Hillary Sanders and Joshua Saxe - *Garbage In, Garbage Out How purportedly great ML models can be screwed up by bad data* - [paper](https://www.blackhat.com/docs/us-17/wednesday/us-17-Sanders-Garbage-In-Garbage-Out-How-Purportedly-Great-ML-Models-Can-Be-Screwed-Up-By-Bad-Data-wp.pdf), [slides](https://www.blackhat.com/docs/us-17/wednesday/us-17-Sanders-Garbage-In-Garbage-Out-How-Purportedly-Great-ML-Models-Can-Be-Screwed-Up-By-Bad-Data.pdf)
- Joshua Saxe and Konstantin Berlin - *eXpose: A Character-Level Convolutional Neural Network with Embeddings For Detecting Malicious URLs, File Paths and Registry Keys* - [paper](https://arxiv.org/abs/1702.08568) and their [github](https://github.com/joshsaxe/eXposeDeepNeuralNetwork)


## Contributing

- Create a branch, e.g. `feature/new_algorithm` or `fix/nasty_bug`.
- Add commits.
- When ready, push to remote: `git push -u origin feature/new_algorithm`.
- Open a Pull Request: document the changes and provide any useful additional context.
- Ask someone to review your code.
- When ready and tests pass: merge it!

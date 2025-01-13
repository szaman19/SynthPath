# AiZynthFinder

## Installation

Install the package using pip:

```bash
pip install aizynthfinder
```

***Note:*** The package installs quite a few depenencies include PyTorch (`torch=1.13.1`) and RDkit (`rdkit=2020.9.5`). These are large and can interfere with other existing installations especially with newer versions available. 

Integrating the package with an existing environment can be tricky, so get started with a fresh environment. Will work on a more elegant solution in the future.

## Setting up Stock and Reaction data

Run the following command to download the stock and reaction data:

```bash
download_public_data .
```

## Running AiZynthFinder

Run the example Python script:

```bash
python ZynthFinderExample.py
```

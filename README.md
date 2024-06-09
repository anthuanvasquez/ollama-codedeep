# Ollama CodeDeep

This is model is based on the qwen2:1.5b model. The parameters are tuned based on a macbook pro with 16gb ram and a 2.7 ghz i7 processor. The main goal is to create a model that can assist with coding styles, best practices, and code optimization.

## Installation

Install the `ollama` command line tool using the following command:

With Python:

```sh
pip install ollama
```

With homebrew:

```sh
brew install ollama
```

## Use the Model

Clone the repository and navigate to the directory.

```sh
git clone git@github.com:anthuanvasquez/ollama-codedeep.git
cd ollama-codedeep
```

Start working with the model using the command.

```sh
ollama create codedeep:1.5b -f Modelfile
```

## Push the Model to the Hub

If you want to push the model to the hub, you can use the following command:

```sh
ollama create -f Modelfile anthuanvasquez/codedeep
ollama push anthuanvasquez/codedeep
```

And replace the `anthuanvasquez/codedeep` with your own repository name.

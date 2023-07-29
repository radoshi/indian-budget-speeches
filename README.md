# Indian Budget Chatbot

Simple chatbot to answer questions related to Budget Speeches made by Indian Finance Ministers over the years.

## Installation

Requires `poetry`. If you don't have it, install it using `brew` or `pip`.

```bash
brew install poetry
```

```bash
poetry install
```

## Usage

```bash
poetry run juptyer notebook
```

# Downloading budget speeches

https://www.indiabudget.gov.in/bspeech.php

```bash
wget -r -nd -nc -A.pdf -l 1 -e robots=off https://www.indiabudget.gov.in/bspeech.php
```

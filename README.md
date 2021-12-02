# JOJ Tiger

The new generation of JOJ Judge Daemon. "Tiger" is named after "Tiger Machine", or slot machine. It is also inspired by the logo of JI, "Blue Tiger".

## Requirements

+ Python >= 3.7
+ rabbitmq

## Installation

Install <https://github.com/joint-online-judge/autograder-sandbox> first.

### Setup venv (Optional)

```bash
python3 -m venv env
source env/Scripts/activate
```

(get judger JWT from horse)

```bash
pip3 install -e .
python3 -m joj.tiger <JWT>
```

### Run Flower (Optional)

```bash
flower
```

### For developers

```bash
pip3 install -r requirements-dev.txt
pre-commit install
```

# sales-forecasting-explore
Sales Forecasting Exploration (Work in Progress)

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)
    1. [Installing Dependencies](#installing-dependencies)
    1. [Defining and Running Experiments](#defining-and-running-experiments)
    1. [Testing](#testing)
    1. [Code Formatting](#code-formatting)
1. [Outcomes](#outcomes)
1. [Architecture](#architecture)
1. [Given More Time](#given-more-time)
1. [Roadmap](#roadmap)
1. [Deployed Staging Link](#deployed-staging-link)
1. [Portfolio](#portfolio)

## Usage

>Explore historical sales data and compare a variety of sales forecasting methodoligies. The purpose of this repo is provide a minimal setup for time series exploration and model development.

## Requirements

- Python 3.11.10 or higher
- Pip 24.2 or higher
- Poetry 1.8.3 or higher

## Development

### Installing Dependencies

From within the root directory:

```
poetry install
```

To create an ipykernel associated with this projects virtual env:
```
poetry run python -m ipykernel install --user --name="da_$(basename $(pwd))" --display-name="da_$(basename $(pwd))"
```

## Defining and Running Experiments

From within the root directory:

```
poetry run jupyter lab
```

## Testing

From within the root directory:

```
poetry run pytest tests
```

### Code Formatting

For this project I'm using the popular [Python Black Code Formatting](https://github.com/psf/black).

### Outcomes

The outcome for this exploration is very simple:

1. You can predict sales demand for a given future interval. This would typically be defined based on the business case.

### Architecture

- TODO

### Given More Time

- TODO

### Roadmap

- TODO

### Deployed Staging Link

- TODO

### Portfolio

Follow this link to find my [Portfolio](https://blakedanson.com) and resume.
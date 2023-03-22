# New Relic Playground

This repository contains a sample notebook and some required files to get you started with the New Relic GraphQL API.

## Getting Started

1. Clone this repository

```bash
git clone git@github.com:zodiacfireworks/newrelic-playground.git
```

2. Install the dependencies

```bash
pyenv install $(cat .python-version)
poetry env use $(cat .python-version)
poetry install
```

3. Create a `.env` file with your New Relic API key

```bash
cp .env.example .env
```

4. Run the Jupiter lab server

```bash
poetry run jupyter lab --ContentsManager.allow_hidden=True
```

5. Open the `newrelic-playground.ipynb` notebook

## Resources

- [New Relic GraphQL API](https://docs.newrelic.com/docs/apis/nerdgraph/get-started/introduction-new-relic-nerdgraph/)
- [New Relic GraphQL Explorer](https://api.newrelic.com/graphiql)

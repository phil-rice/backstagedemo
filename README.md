# [Backstage](https://backstage.io)

This is your newly scaffolded Backstage App, Good Luck!

To start the app, run:

```sh
yarn install
yarn dev
```

# Installation
As administrator, run the following command to install the TechDocs CLI and the TechDocs MkDocs plugin. Order matters:

```shell
pip install techdocs
pip install  mkdocs-techdocs-core
#Note: We recommend Python version 3.11 or higher.
# Caveat: Please install the mkdocs-techdocs-core package after all other Python packages. The order is important to make sure we get correct version of some of the dependencies.
```

# Learnings

Components are the parent for lots of things

Services are the actually things that implements the service
API is the definition of an interface for a service
Libraries are good

A single project can have multiple roles. It might define a service, an api and a library.
Thus we need to have the idea of multiple.

Lots of stuff can be defined by a POM.
We can add <backstage.xxx> to the POM to add more things to it. Making this the single source of truth.
We can obviously do the same to package.json



# Development

There are two options for the local development:

1. Native development
2. `docker` development

In this part we will discuss native development. 
Read more about [`docker`](/wemake-vue-template/docker.html) here.
Choose the one that fits the best for you.


## Prerequisites

You will need to install [`nvm`](https://github.com/creationix/nvm/blob/master/README.md) before starting.


## Setting up

You will need to install the same `node` version that we use to be able to run this project.

Hopefully, it is very easy. Just run:

```bash
# Run this command inside your root project directory
nvm install
nvm use
```

While `nvm install` is a one time action, that just downloads the required `node` version, do not forget to run `nvm use` each time you open a new terminal window.


## Dependencies

After you have activated the correct `node` version it is time to install 
dependencies. Run:

```bash
yarn install
```

You will see that two new folders are created: 

- `node_modules` with all your dependencies
- `flow-typed` with external `flow` type definitions


## Running

After your dependencies are installed, run `yarn dev` to start a development server.
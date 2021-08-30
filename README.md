# Full Stack typescript project boilerplate setup

## How to use

```
# Clone in repo
git clone https://github.com/japrozs/ts-project-setup.git
cd ts-project-setup
cd packages/server
yarn install
cd ../app/
yarn install
```

## How to run the server

```
cd packages/server
createdb <name> # then change this name in the index.ts file in in the first few lines of the main function
yarn watch # to start the typescript compilation
```

Then, in another terminal window run:

```
yarn dev
```

This will start the GraphQL Server on `http://localhost:4000/graphql`

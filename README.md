# SubQuery - Moonbeam ERC721 indexer
This is a very basic ERC721 indexer on Moonbeam using Subquery Substrate Frontier EVM.

## To run it on docker:

```
npm install
```
```
subql build
```
```
docker-compose pull
```
```
docker-compose up
```

## To deploy on subquery managed services:

Set the environment variable SUBQL_ACCESS_TOKEN from the platform, then run:

```
subql publish
```

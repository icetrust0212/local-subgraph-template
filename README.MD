# Subgraph local development template

## Check network

```yaml
- kind: ethereum
  name: Contract
  network: testnet
```

## Create new subgraph

```cmd
npx graph create --node http://18.201.242.131:8020/ erc20-test
```

`erc20-test` is subgraph name - should use different network by project

## Deploy subgraph

```cmd
npx graph deploy --node http://18.201.242.131:8020/ --ipfs http://18.201.242.131:5001 erc20-test
```

## Remove subgraph

```cmd
npx graph remove --node http://18.201.242.131:8020/ erc20-test
```

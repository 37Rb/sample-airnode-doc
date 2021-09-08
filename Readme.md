# How to use { MySample API } on Web3

> Airnode API Documentation

{ MySample is a fake API that demonstrates how to write documentation for Airnode APIs. This paragraph is where you would give a brief overview of your API and what it does. }

**Home Page:** { https://www.coingecko.com/en/api }  
**Web2 Docs:** { https://www.coingecko.com/en/api/documentation }

## Call this Airnode API

Read the [Airnode developer documentation](https://docs.api3.org/d/call-an-airnode) to learn how to call Airnode APIs. You'll need to know the **Airnode address** to call any endpoint in this API.

`airnode`: { 0xd29B9f8588120F75c27e9C84c4cbe88E29034F19 }

[Reserved Parameters](https://docs.api3.org/r/reserved-parameters) are used to control Airnode behavior and are available for all endpoints.

## This API is available on: { edit table below }

| Chain                                | Airnode RRP contract                                                    | P   |
| ------------------------------------ | ---------------                                                         | --: |
| [Ethereum](https://ethereum.org)     | 0xd29B9f8588120F75c27e9C84c4cbe88E29034F19 | 1m  |
| [RSK](https://www.rsk.co)            | 0xd29B9f8588120F75c27e9C84c4cbe88E29034F19 | 1m  |
| [Moonbeam](https://moonbeam.network) | 0xd29B9f8588120F75c27e9C84c4cbe88E29034F19 | 1m  |
| [xDai](https://www.xdaichain.com)    | 0xd29B9f8588120F75c27e9C84c4cbe88E29034F19 | 1m  |
| [Solana](https://solana.com)         | 0xd29B9f8588120F75c27e9C84c4cbe88E29034F19 | 1s  |

# Endpoints

---

## /endpoint/one

{ This is an endpoint that can be called by this API. Explain what it does and consider deep linking to it in your Web2 docs. }

**Web2 Docs:** { https://www.coingecko.com/en/api/documentation }

You'll need to know the **endpoint ID** to call this endpoint.

`endpointId`: { 0xd37251d64f9aa2e06ec1e3393e52724d091ecf3c458670f2938ac2c94da37fa2 }

[Request Parameters](https://docs.api3.org/d/request-parameters) { edit below }

```solidity
bytes32 param1; // The first parameter
uint256 param2; // The second parameter
```

[Fixed Parameters](https://docs.api3.org/p/fixed-parameters) { edit below }

```solidity
bytes32 format = 'json'; // The format parameter is fixed to the value 'json'
```

[Response](https://docs.api3.org/d/response-parameters) { edit below }

```solidity
int32 result; // The response value of of the request
```

---

## /second/endpoint

{ This is an endpoint that can be called by this API. Explain what it does and consider deep linking to it in your Web2 docs. }

**Web2 Docs:** { https://www.coingecko.com/en/api/documentation }

You'll need to know the **endpoint ID** to call this endpoint.

`endpointId`: { 0xd37251d64f9aa2e06ec1e3393e52724d091ecf3c458670f2938ac2c94da37fa2 }

[Request Parameters](https://docs.api3.org/d/request-parameters) { edit below }

```solidity
bytes32 param1;
uint256 param2;
```

[Response](https://docs.api3.org/d/response-parameters) { edit below }

```solidity
bool result;
```

---

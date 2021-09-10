# How to use {{ API Name }} on Web3

> [Airnode](https://api3.org/airnode) API Documentation

{{ Give an overview of the API. Describe what it does. }}

**Home Page:** {{ URL to API home page }}  
**Web2 Docs:** {{ URL to API documentation }}

## Call this Airnode API

Read the [Airnode developer documentation](https://docs.api3.org/d/call-an-airnode) to learn how to call Airnode APIs. You'll need the **Airnode Address** to call any endpoint in this API.

**Airnode Address:** {{ 0xd29B9f8588120F75c27e9C84c4cbe88E29034F19 }}

[Reserved Parameters](https://docs.api3.org/r/reserved-parameters) are used to control Airnode behavior and are available for all endpoints.

## Available on Mainnets:

<!-- Only include chains your Airnode is configured to use. -->

| Chain                                | Airnode RRP Contract                       | P   |
| ------------------------------------ | ------------------------------------------ | --: |
| [Ethereum](https://ethereum.org)     | 0xd29B9f8588120F75c27e9C84c4cbe88E29034F19 | 1m  |
| [RSK](https://www.rsk.co)            | 0xd29B9f8588120F75c27e9C84c4cbe88E29034F19 | 1m  |
| [Moonbeam](https://moonbeam.network) | 0xd29B9f8588120F75c27e9C84c4cbe88E29034F19 | 1m  |
| [xDai](https://www.xdaichain.com)    | 0xd29B9f8588120F75c27e9C84c4cbe88E29034F19 | 1m  |

## Available on Testnets:

<!-- Only include chains your Airnode is configured to use. -->

| Chain                                                                          | Airnode RRP Contract                       | P   |
| ------------------------------------------------------------------------------ | ------------------------------------------ | --: |
| [Ethereum Ropsten](https://ethereum.org/en/developers/docs/networks/#testnets) | 0xd29B9f8588120F75c27e9C84c4cbe88E29034F19 | 1m  |
| [RSK Testnet](https://developers.rsk.co/rsk/rbtc/conversion/networks/testnet/) | 0xd29B9f8588120F75c27e9C84c4cbe88E29034F19 | 1m  |

# Endpoints

---

## {{ /endpoint/one }}

{{ Describe the endpoint. Explain what it does and, if possible, deep link to the Web2 documentation. }}

**Web2 Docs:** {{ URL to endpoint documentation }}

You'll need the **Endpoint ID** to call this endpoint.

**Endpoint ID:** {{ 0xd37251d64f9aa2e06ec1e3393e52724d091ecf3c458670f2938ac2c94da37fa2 }}

[Request Parameters](https://docs.api3.org/d/request-parameters)

<!-- Edit parameters to match the endpoint. -->

```solidity
bytes32 param1; // The first parameter
uint256 param2; // The second parameter
```

[Fixed Parameters](https://docs.api3.org/p/fixed-parameters)

<!-- Edit parameters to match the endpoint. -->

```solidity
bytes32 format = 'json'; // The format parameter is fixed to the value 'json'
```

[Response](https://docs.api3.org/d/response-parameters)

<!-- Edit response to match the endpoint. -->

```solidity
int32 result; // The response value of the request
```

---

## {{ /second/endpoint }}

{{ Describe the endpoint. Explain what it does and, if possible, deep link to the Web2 documentation. }}

**Web2 Docs:** {{ URL to endpoint documentation }}

You'll need the **Endpoint ID** to call this endpoint.

**Endpoint ID:** {{ 0xd37251d64f9aa2e06ec1e3393e52724d091ecf3c458670f2938ac2c94da37fa2 }}

[Request Parameters](https://docs.api3.org/d/request-parameters)

<!-- Edit parameters to match the endpoint. -->

```solidity
bytes32 param1;
uint256 param2;
```

[Response](https://docs.api3.org/d/response-parameters)

<!-- Edit response to match the endpoint. -->

```solidity
bool result;
```

---

<!-- Add more endpoints as needed... -->

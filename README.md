<h1>SETUP</h1>

BNB Faucet: https://www.bnbchain.org/en/testnet-faucet

Bridge from BNB to OPbnb: https://opbnb-testnet-bridge.bnbchain.org/deposit

OPbnb RPC: https://chainlist.org/chain/5611

<h1>RUN NODE</h1>

```console
docker run -d -e PRIVATE_KEY=$YOUR_PRIVATE_KEY --name glacier-verifier docker.io/glaciernetwork/glacier-verifier:v0.0.2
```

<h1>CHECK LOGS</h1>

```console
docker logs -f glacier-verifier
```

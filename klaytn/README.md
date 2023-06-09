# Klaytn Endpoint Node

## Explorer
https://scope.klaytn.com/

https://docs.klaytn.foundation/content/installation-guide/deployment/endpoint-node/installation-guide/configuration

## Testing the node
```
curl -H "Content-Type: application/json" --data '{"jsonrpc":"2.0","method":"rpc_modules","params":[],"id":1}' https://klaytn.omnirpc.io
```

## Prometheus metrics
klaytn_blockchain_head_blocknumber

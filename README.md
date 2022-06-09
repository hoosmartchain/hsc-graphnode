
# HSC GraphNode  Service
```
https://graphapi.hoosmartchain.com/deploy/ 
https://graphapi.hoosmartchain.com/ipfs/ 
https://graphapi.hoosmartchain.com/index/graphql/playground
```

# HSC graph deploy example

```
  "scripts": {
    "create-local": "graph create nftminer --node http://127.0.0.1:8020",
    "create-hsc": "graph create nftminer --node https://graphapi.hoosmartchain.com/deploy/     ",
    "codegen": "graph codegen",
    "build": "graph build",
    "deploy": "graph deploy nftminer --ipfs https://graphapi.hoosmartchain.com/ipfs/  --node https://graphapi.hoosmartchain.com/deploy/ ",
    "deploy-local": "graph deploy nftminer --ipfs http://localhost:5001 --node http://127.0.0.1:8020"
  },
```

# TheGraph Help Document
https://thegraph.com/docs/developer/quick-start
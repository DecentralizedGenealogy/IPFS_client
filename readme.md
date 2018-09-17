# Client based on IPFS
This is a crude tree client based on the InterPlanetary File System underneath. Each file represetns a person, and each file is distributed across [IPFS](https://ipfs.io/). Each person maintains references or links with other people.

- Install IPFS (https://ipfs.io/docs/install/)
- run: ipfs init
- Add CORS headers
  - ipfs config --json API.HTTPHeaders.Access-Control-Allow-Origin '["*"]'
  - ipfs config --json API.HTTPHeaders.Access-Control-Allow-Methods '["PUT", "GET", "POST"]'
  - ipfs config --json API.HTTPHeaders.Access-Control-Allow-Credentials '["true"]'
- Run: ipfs daemon
- Go to http://localhost:5001/webui/

# Technology to look at
- https://github.com/orbitdb/orbit-db
- https://github.com/amark/gun

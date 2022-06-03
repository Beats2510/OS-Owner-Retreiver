# OS-Owner-Retriever

Author: Beats2510

A simple Python script to **retrieve Owners/Holders of a whole NFT collection on ETH (OpenSea)**.

# requirements

- OpenSea Collection Path/Slug 

- Contract Address

- Total Minted / Total Collection Tokens

- OpenSea API Key


# Usage

#### Running with user input
```
python os-checker.py
```
- Fill the inputs with your data
- Filter is `OPTIONAL` (Example: 2 If you want to filter by holders with 2 or more tokens...)


#### Running with flags
```
-s, --slug / Slug
-c, --contract / Contract Address
-m, --minted / Total Minted - Total Collection Tokens
-k, --apikey / OS API Key
-f, --filter (OPTIONAL) / Filter by Tokens (2 If you want to filter by holders with 2 or more tokens...)
```
- Type ```python os-checker.py -h``` to get the available flags

# Results

- It will generate a JSON file inside `./snapshots` directory.
- Will follow the next Schema:
  - Wallet Address: Number of tokens


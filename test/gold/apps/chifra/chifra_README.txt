chifra argc: 2 [1:-th] 
chifra -th 
### Usage

`Usage:`    chifra command  
`Purpose:`  Access to all TrueBlocks tools (`chifra <cmd> --help` for more).

`Where:`  
```
 ACCOUNTS
   list          list every appearance of an address anywhere on the chain
   export        export full detail of transactions for one or more addresses
   monitors      add, remove, clean, and list address monitors
   names         query addresses or names of well known accounts
   abis          fetches the ABI for a smart contract
 CHAIN DATA
   blocks        retrieve one or more blocks from the chain or local cache
   transactions  retrieve one or more transactions from the chain or local cache
   receipts      retrieve receipts for the given transaction(s)
   logs          retrieve logs for the given transaction(s)
   traces        retrieve traces for the given transaction(s)
   when          find block(s) based on date, blockNum, timestamp, or 'special'
 CHAIN STATE
   state         retrieve account balance(s) for one or more addresses at given block(s)
   tokens        retrieve token balance(s) for one or more addresses at given block(s)
 ADMIN
   status        report on the status of the TrueBlocks system
   serve         serve the TrueBlocks API using the flame server
   scrape        scan the chain and update the TrueBlocks index of appearances
   init          initialize the index of appearances by downloading Bloom filters
   pins          manage pinned index of appearances and associated Bloom filters
 OTHER
   quotes        freshen and/or display Ethereum price data
   explore       open an explorer for a given address, block, or transaction
   slurp         fetch data from EtherScan for any address
 
```


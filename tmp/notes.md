# why mine?

  - so each node the the BC is collecting transactions
  - there is a difficulty target with a certain # of zeros
  - The purpose of the difficulty target:
    - to maintain a 10 minutes average delay between each block
    - to ensure the Bitcoin emission rate.
  - you adjust the nonce to get the correct hash
    - this includes the hash header, the merkle root, and the previous block
  - if you find the nonce, you announce it
  - other nodes check against their current transaction
    - the merkle root represents the transaction, so it guarantees you can't cheat
  - WIN!
    - current reward is 12.5 BTC == $54,000

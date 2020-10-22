# DevChain

Chain ID 111

## Node 1

### Address

0x485f02BF68F3900DD5Ef71EfF6C719c2e4d40dfe

### Start Command

./geth --datadir node1 --unlock 485f02BF68F3900DD5Ef71EfF6C719c2e4d40dfe --mine --rpc --allow-insecure-unlock

## Node 2

### Address

0x2B0F5f1ad7BBCF30436BfbBDd8fDfff305C600A0

### Start Command

./geth --datadir node2 --unlock 2B0F5f1ad7BBCF30436BfbBDd8fDfff305C600A0 --mine --port 30304 --bootnodes enode://f33dfb8532061530b1b5b0049d1d2d85bbb9192786de18018e36083af01c8cfe5498b01d4621a8dafeeca9e453ab5137a178ae9f6fff5e6312920baebcd32d0d@127.0.0.1:30303
 --ipcdisable --allow-insecure-unlock

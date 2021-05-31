# Blockchain_Testnet
##Zbank blockchain startup
Run ./geth commands on blockchain tools folder to activate blockchain. Password is zbank for each node.
'''
 ./geth --datadir node1 --unlock "0xA7AbAB88820c543677e5E34CdBE09a43f9636B5c" --mine --miner.threads 1
'''
'''
./geth --datadir node_2_zbank --unlock "0x9669745b23CBfe162Ab5d2be0977816a2D81E311" --port 30304 --rpc --bootnodes "enode://a399a18d543824af367df468fec736d466e05c19d7b328a4d24690c11360223479b381f091b8ffcedf90234727f28c250874344294439be0794a13b317a41cd8@127.0.0.1:30303" --ipcdisable --allow-insecure-unlock
'''
Blockchain time is set to 10 seconds as Proof of Authority. Chain ID is 333. 
At this time, I had difficulty setting up MyCrypto as the original class network is interfering with the HW directions. 

# HLF-ERC20
Implementation of ERC20 Token standard in chaincode (Hyperledger fabric (golang))

This is just a demo chaincode. All the functions and events in ERC20 standard is not included in this

Testing arguments:

'{"function": "TokenCreation","Args":["ERCFT","1000", "ERC20 TOKEN","jeff"]}'
'{"function": "TransferFrom","Args":["jeff", "sam", "10"]}'
'{"function": "BalanceOf","Args":["jeff"]}'

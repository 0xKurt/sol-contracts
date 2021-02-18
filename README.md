# Solidity Smart Contracts

### AdressProxy.sol
Stores contract names and their addresses in a mapping.
Addresses can be accessed by addresses["contract name"].

In addition to the management of contract addresses in public 'addresses' mapping, several admins can be created and deleted. 
 
The owner cannot be deleted from the admins mapping, but can be changed.

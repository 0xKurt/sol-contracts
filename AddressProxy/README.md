# AddressProxy
*AddressProxy*
## constructor

**Development notice:**
*Set owner to msg.sender and add msg.sender to admins mapping.*

## addContractAddress

**Development notice:**
*Add a new contract address to addresses mapping.*


**Parameters:**
* name `string`: *The name of the contract to add.*
* contractAddress `address`: *The address of the contract to add.*

## removeContractAddress

**Development notice:**
*Removes an address from addresses mapping.*


**Parameters:**
* name `string`: *The name of the contract to remove*

## addAdmin

**Development notice:**
*Adds a new admin to admins mapping.*


**Parameters:**
* newAdmin `address`: *Address of new admin.*

## removeAdmin

**Development notice:**
*Removes an admin from admins mapping.*


**Parameters:**
* oldAdmin `address`: *The address to remove from admins list.*

## setOwner

**Development notice:**
*Overwrites the existing owner.*


**Parameters:**
* newOwner `address`: *Address of the new owner.*

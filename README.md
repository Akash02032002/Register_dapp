# Register_dapp
This is a Register_dapp written in smartpy.

The above code is a Smart Contract written in SmartPy language, a high-level language for developing smart contracts on the Tezos blockchain.

The code defines a Registry contract with two entry points: addRecord and addRecordAdmin. The contract keeps a registry of accounts and their associated amounts in a map.

The addRecord entry point allows a sender to add a record to the registry, with their address as the key and the amount parameter as the value.

The addRecordAdmin entry point allows the admin to add a record to the registry, but first verifies that the sender is the specified admin. If the sender is the admin, a record is added to the registry with the specified account as the key and the amount as the value.

The code also includes a test scenario for testing the Registry contract. The test scenario creates an instance of the contract, adds records to the registry using both entry points, and verifies the expected outcome.

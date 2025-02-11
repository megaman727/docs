# Use smart contracts

Smart contracts are an advanced feature of Terra Station. If you’re using Terra Station for the first time, follow the [Terra Station tutorial](/Tutorials/Get-started/Terra-station-desktop.md).

## Prerequisites

Compile a contract locally and create a `.wasm` file.  

## Upload

Deploy a contract by uploading your `.wasm` file to Terra Station.

1. Open Terra Station and connect your wallet. Click **Contracts**.

2. Click **Upload**.

3. Upload your `.wasm` file and enter the contract info. Click **Next**.

4. Enter your password and click **Upload**.

Your contract is now uploaded, and you received a contract code ID.

## Create

Use **Create** to initialize your contract after uploading.

1. Click **Create**.

2. Enter your contract code ID, `InitMsg JSON`, name, and description. Click **Next**.

3. Confirm the fee amounts and enter your password. Click **Create**.

Your contract is now initialized.

## Query

Use **Query** to find out contract values. Querying does not cost anything.

1. Click **Query** located under your contract address.

2. Enter your `HandleMsg JSON`. Click **Next**.

Station will show your query result.

## Interact

Use **Interact** to use the contract. Interacting will spend gas.

1. Click **Interact** located under your contract address.

2. Enter your `HandleMsg JSON`. Click **Next**.

3. Confirm the fee amounts and enter your password. Click **Interact**.

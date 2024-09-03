# Ethereum Blockchain Explorer

This project is a simple Ethereum blockchain explorer built using Python and Flask. It connects to the Ethereum blockchain using the Web3 library and allows users to view block and transaction details. The explorer is connected to the Sepolia test network using Infura.

## Features

- Connects to the Ethereum blockchain via Infura.
- Displays the latest block information.
- Allows users to search for transaction details using transaction hashes.

## Prerequisites

- Python 3.9
- Flask 1.1.1
- Web3.py


Notes
- This project connects to the Sepolia test network using Infura. If you want to connect to a different network or node provider, update the eth variable with the appropriate URL.
- Error handling is minimal; if the connection fails or an invalid transaction hash is provided, the page may not display expected results.

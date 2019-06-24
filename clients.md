# Clients

The Cortex repository is a fork of [Go Ethereum](https://github.com/ethereum/go-ethereum>) which contains protocol changes to support machine learning model inference. This implements the Cortex network, which maintains a separate ledger from the Ethereum network, for several reasons, the most immediate of which are AI inference support and the deterministic inference consensus.

## Requirements

To ensure that your Cortex client runs gracefully, please check your system meets the following requirements:

- System: Linux Ubuntu 16.04+
- CPU: Xeon processor 16 Cores 
- GPU: Nvidia GPU 1060
- RAM: 32GB
- Space: 2TB  (*the size of the blockchain increases over time*)
- CUDA version: 9.2+
- CUDA driver: 396+
- Compiler: Go 1.10+, GCC 5.4+

note: Currently, we only officially support Linux (Ubuntu), but we are actively investigating development for other operating systems and platforms(e.g., macOS, Ubuntu, Windows, Fedora). 

Building Cortex clients requires a Go (version 1.10 or later), a C compiler, and a CUDA (version 9.2 or later). We will guide you through the Installation section.





## How to Run a Client

Refer to [CortexTheseus](https://github.com/CortexFoundation/CortexTheseus)
# DeFiScan Data Repository

A collection of permission scanner results for compiling reports for [defiscan.info](https://defiscan.info)

## Overview

This repository serves as a central hub for sharing and comparing permission scanner results across different DeFi protocols. The scanner analyzes smart contract permissions and access controls, helping identify potential security considerations.

## Repository Structure

Each protocol has its own directory with the following structure:

```
protocol-name/
├── list_contracts.json     # List of analyzed contract addresses and metadata
├── result.json            # Scanner output with detailed permission analysis
└── etherscan_contracts/   # Directory containing verified contract source code

```

## File Descriptions

- `list_contracts.json`: Defines the scope of the analysis, including contract addresses, deployment dates, and other relevant metadata
- `result.json`: Contains the detailed output from the permission scanner, including identified access controls and role assignments.
- `etherscan_contracts/`: Contains the verified source code for each analyzed contract, retrieved from Etherscan


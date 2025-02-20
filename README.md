# ProjectSolidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

/**
 * @title EventNFT
 * @dev A simple smart contract to issue NFTs for event participation.
 * 
 * ## Overview
 * This contract mints non-fungible tokens (NFTs) for users attending an event. 
 * Each participant receives an NFT that represents their participation.
 * 
 * ## Features:
 * - Mint NFTs to event participants.
 * - Store metadata for each NFT (e.g., event details, unique badge).
 * - Track NFT ownership and balances.
 * - No external dependencies (e.g., OpenZeppelin), making it lightweight.
 * 
 * ## Functions:
 * - `mint(address to, string memory _tokenURI)`: Mints a new NFT for a participant.
 * - `tokenURI(uint256 tokenId)`: Retrieves the metadata (URI) of an NFT.
 * 
 * ## Events:
 * - `Transfer(address indexed from, address indexed to, uint256 indexed tokenId)`: 
 *   Emits when a new NFT is minted.
 * 
 * ## How to Use:
 * 1. Deploy the contract on Ethereum, Binance Smart Chain, or any Solidity-compatible blockchain.
 * 2. Call `mint(address, "ipfs://event-metadata")` to issue NFTs to participants.
 * 3. Use `tokenURI(tokenId)` to get NFT metadata.
 * 
 * ## Example Use Case:
 * - A conference issues NFTs as proof of attendance.
 * - A sports event provides collectible NFTs to ticket holders.
 * - A university gives digital certificates as NFTs.
 * 
 */

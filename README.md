# Endless NFT Tagger

On-chain module for adding and managing custom tags to NFTs in the Endless Protocol ecosystem.

## Description

This module allows users to attach arbitrary string tags to any NFT (by object ID). Tags are stored fully on-chain, immutable, and publicly readable through view functions.

**Competition Category:** Upgrade & Optimize  
Improves metadata organization and discoverability of NFTs in Luffa and other Endless ecosystem applications. Solves the problem of lost or unstructured off-chain metadata by providing a reliable on-chain tagging system.

## Contract Details

- Network: Endless Testnet
- Package/Module Address: [INSERT CONTRACT ADDRESS HERE, e.g. 0x123...abc]
- Module name: `tagger` (or your actual published module name)

## Features

- `add_tags(nft_id: address, tags: vector<String>)` – adds new tags to an NFT (owner or authorized only)
- `get_tags(nft_id: address): vector<String>` – view function to read all tags
- Tags are stored in a dynamic object field for efficiency and scalability

## Demo

Frontend demo in progress (will be deployed on Vercel)  
GitHub repository: https://github.com/Bellafuria/endless-nft-tagger

## Future Improvements

- Integration with Luffa UI
- Collaborative tagging (community-voted tags)
- AI-powered auto-tagging suggestions
- Search index for tagged NFTs across the ecosystem

---

Submitted to **Endless Ecosystem Creative Proposal Competition**  
January 2026  
Built by @Bellafuria

# Skill Token Marketplace Smart Contract

## Overview

This repository contains the Solidity smart contract code for the Skill Token Marketplace. The Skill Token Marketplace is a decentralized platform enabling users to list their skills, exchange SkillTokens, stake SkillTokens, give kudos, and engage in a community-driven marketplace.

## Contract Details

- **Contract Address:** (0x2E6d1cbcEB54E2C92023a8E806a7750152b19197 (Scroll Sepolia Testnet)
- **link to scroll-etherscan :** (INSERT LINK)
## Functions

1. **Create Skill Listing:**
   - Admin can add a new skill listing, specifying skill, price, and activation status.

2. **Remove Skill Listing:**
   - Users can remove their own active skill listings.

3. **Exchange Skill Tokens:**
   - Users can exchange SkillTokens for a listed skill, with events emitted for successful exchanges.

4. **Give Kudos:**
   - Users can give kudos to others, fostering community engagement.

# Skill Token Contract

## Overview

This repository contains the Solidity smart contract code for SkillTokens. SkillTokens are ERC-20 compliant tokens that can be minted and exchanged within the Skill Token Marketplace.

## Contract Details

- **Contract Address:** 0xEEF7901D040BFB5C42293e513192d61f579D59ea, 0xB70c85fE15C2FF1Fa4c26B2794d2811387A4aa8F
## Functions

1. **Mint Skill Tokens:**
- Only the contract owner can mint new SkillTokens, controlling token supply.

2. **Exchange Skill Tokens:**
- Users can exchange SkillTokens, with basic exchange logic ensuring sufficient balance.




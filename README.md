# The ImmutableX Handbook [WiP]

Welcome. This is EasyA's legendary handbook. If you want to learn ImmutableX like a legend, then you're in the right place.

# Purpose

This handbook serves as a guide to the ImmutableX ecosystem, geared towards those just joining for the first time. It isn't just a beginners' handbook; it's a legendary handbook. Even if you've already immersed yourself in the ecosystem, you'll find tons of helpful tidbits around here!

# The EasyA App

Of course, the best place to start is always the [EasyA](https://www.easya.io) app! Download it here for the fastest and most fun way to learn about ImmutableX. Download it directly right [here](https://links.easya.io/links/gotoapp)!

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Core Concepts](#core-concepts)
- [Development Tools](#development-tools)
- [Smart Contracts](#smart-contracts)
- [ImmutableX Network](#immutablex-network)
- [Ecosystem Projects](#ecosystem-projects)
- [Resources](#resources)
- [Handy Code Snippets](#handy-code-snippets)
- [Contributing](#contributing)

## Introduction

What is ImmutableX:

- [ImmutableX Website](https://www.immutable.com/) - The official website for ImmutableX, a Layer 2 scaling solution for NFTs on Ethereum.

## Getting Started

The no-fluff starter:

- [ImmutableX Documentation](https://docs.x.immutable.com/) - Official documentation to get you started with ImmutableX.
- [ImmutableX Explorer](https://explorer.immutable.com/) - Block explorer for the ImmutableX network.

## Core Concepts

Explanation of fundamental concepts in the ImmutableX ecosystem:

- [NFT Minting](https://docs.x.immutable.com/docs/minting-on-immutable-x) - Explanation of how NFTs are minted on ImmutableX.

## Development Tools

Key tools and environments for ImmutableX:

[To be Added]

## Smart Contracts

How to write and deploy smart contracts on ImmutableX:

[To be Added]

## ImmutableX Network

Going into the network level:

[To be Added]

## Ecosystem Projects

Cool projects built on ImmutableX:

- [Gods Unchained](https://godsunchained.com/) - A competitive trading card game built on ImmutableX.
- [Guild of Guardians](https://www.guildofguardians.com/) - A mobile RPG game utilizing ImmutableX for in-game assets.
- [Illuvium](https://illuvium.io/) - An open-world RPG adventure game built on ImmutableX.

...and of course many more - check them out in the EasyA app!

## Resources

Extra stuff:

- [ImmutableX Blog](https://www.immutable.com/blog) - Official blog with updates and insights into ImmutableX development.
- [ImmutableX GitHub](https://github.com/immutable) - The main repository for ImmutableX's development.

## Handy Code Snippets

Get a taste of ImmutableX development with these code snippets:

### Connecting to ImmutableX

```javascript
import { ImmutableXClient, Link } from '@imtbl/imx-sdk';

const client = await ImmutableXClient.build({ publicApiUrl: 'https://api.x.immutable.com/v1' });
console.log('Connected to ImmutableX');
```

### Minting an NFT

```javascript
const result = await client.mint({
  mints: [{
    etherKey: '0x...',  // The recipient's address
    tokens: [{
      type: 'ERC721',
      data: {
        tokenId: '1',
        blueprint: 'metadata:url',
        royalties: [
          { recipient: '0x...', percentage: 3.0 }
        ]
      }
    }]
  }]
});
console.log('NFT minted:', result);
```

These examples showcase:
1. How to connect to the ImmutableX network using the ImmutableX SDK.
2. How to mint an NFT on ImmutableX.

## Contributing

We welcome contributions to make this handbook even more legendary! Here's how you can contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-addition`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add some amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-addition`)
6. Create a new Pull Request

Please ensure your contributions align with our code of conduct and contribution guidelines.

## Credit/Inspiration

This handbook was inspired by the famous awesome lists by sindresorhus. We need awesome lists for Web3 ecosystems, with more of a hacker's guide to how they work. This is the answer to that need.

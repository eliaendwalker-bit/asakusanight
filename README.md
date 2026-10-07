# AsakusaNight
![AsakusaNight logo](assets/logo.png)

A cinematic Unreal Engine boss-fight demo set in Asakusa, with victory minting an on-chain relic NFT.

## Overview
AsakusaNight is a vertical-slice 3D action demo built in Unreal Engine 5. It features one beautifully rendered Asakusa street scene and a boss battle against a dark organization enforcer. Defeating the boss triggers a Solana wallet connection that mints a unique 'Spirit Seal' NFT as proof of victory, showing how AAA-quality visuals can merge with on-chain ownership.

## Problem
Most Web3 games have weak graphics and shallow gameplay. Our team has strong 3D and Unreal Engine skills but no blockchain experience, and we wanted to showcase both in a crypto hackathon.

## Solution
We built one gorgeous, playable combat scene in Unreal Engine and bolted on a minimal Solana integration, so a real game moment (boss defeat) produces a verifiable on-chain reward.

## Features (MVP)
- One fully modeled Asakusa street environment (Kaminarimon-inspired) with dynamic lighting
- Single boss encounter with combo attacks, dodge, and a defeat cinematic
- Solana wallet connect screen triggered after boss defeat
- Mint of a 1-of-1 'Spirit Seal' NFT via Metaplex on victory
- Simple HUD showing health, stamina, and wallet status

## Tech Stack
- Unreal Engine 5 (Nanite, Lumen)
- Blender for asset creation
- Metaplex Core for NFT minting
- Solana Wallet Adapter
- Node.js backend for mint trigger

## How It Works

```
[Player] -> [Unreal Engine Scene: Asakusa Street]
              |
              v
        [Boss Fight Logic]
              |
        (boss defeated)
              v
   [HUD triggers Wallet Connect]
              |
              v
 [Solana Wallet Adapter: Connect Wallet]
              |
              v
 [Node.js Backend: Mint Trigger]
              |
              v
 [Metaplex Core: Mint 'Spirit Seal' NFT on Solana]
              |
              v
   [Player receives on-chain proof of victory]
```

## Roadmap
- Expand to a full chapter with multiple enemies and story beats
- Add dynamic NFT traits that evolve based on player performance
- Explore mobile/cloud streaming to reach players without high-end PCs

## Pitch
- [Pitch deck (PDF)](docs/pitch.pdf)
- [Pitch script](docs/pitch-script.md)

## Team
- [Name] - Unreal Engine / Gameplay Programming
- [Name] - 3D Art & Environment Design
- [Name] - Blockchain Integration
- [Name] - Design / Producer

---

🎬 Pitch video: [docs/pitch-video.webm](docs/pitch-video.webm)


## Prototype

Live prototype: https://eliaendwalker-bit.github.io/asakusanight/

The source is [docs/index.html](docs/index.html) (served with GitHub Pages from the /docs folder). All data is simulated.

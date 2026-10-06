# pokeplayer

**Play Pokémon together with an AI.**

pokeplayer lets you and a language model play a Pokémon game as a pair. The AI
is the player: it reads the game, presses the buttons, battles, explores and
keeps going. You are its companion. Talk to it while it plays, ask what it is
doing and why, suggest a plan, name a Pokémon with it, or say nothing and watch.
You never have to touch the controls.

**[Download for Mac](https://github.com/stewberticus/pokeplayer-releases/releases/latest/download/pokeplayer-mac-arm64.dmg)**
· Apple Silicon, macOS 14 or later · signed and notarized by Apple

Then open [`MAC-START-HERE.md`](https://github.com/stewberticus/pokeplayer-releases/releases/latest)
from the same release. It walks you through the first game.

## What it does

- **Plays the whole game.** English Pokémon Red, Blue, Gold, Silver and Crystal.
  The aim is the badges, the Elite Four and the champion.
- **Keeps playing.** The AI carries on between your messages. Leave it alone and
  it plays by itself.
- **Talks with you.** Ask a question, give advice or change its mind. It answers
  from what is happening in the game.
- **Remembers.** Adventures, saves and conversations are kept, so you can stop and
  continue later.
- **Uses the brain you choose.** A model that runs on your Mac, your own account
  with OpenRouter or MiniMax, or a local server such as LM Studio or MTPLX.
- **Looks the way you like.** Three styles, six colorways, light and dark.

## What you need

- A Mac with Apple Silicon (M1 or later) running macOS 14 or later.
- Your own English Pokémon ROM (`.gb` or `.gbc`). pokeplayer does not include
  or download games. For Crystal, use the 1.1 release.
- A model. The built-in local models are 2.7 GB, 5.7 GB and 19 GB; setup checks
  your disk and memory and recommends what fits. Or use a cloud provider key.

Nothing else to install: no Python, Node.js or model server.

## Install

1. Download the disk image above, drag pokeplayer to Applications and open it.
2. In System Settings, add your ROM and pick a model.
3. Choose New game and start playing.

The full guide is `MAC-START-HERE.md`, attached to every
[release](https://github.com/stewberticus/pokeplayer-releases/releases)
together with `SHA256SUMS.txt`, so you can check your download.

## Windows

A Windows installer is not part of the current release.

## About this repository

It holds only the downloads. The source is private. Release notes for each
version are on the [releases page](https://github.com/stewberticus/pokeplayer-releases/releases).
Pokémon is a trademark of Nintendo, Game Freak and Creatures. pokeplayer is an
independent project and is not affiliated with them.

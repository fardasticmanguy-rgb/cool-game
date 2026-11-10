# Crashpot

A fast party card game for 2 to 5 players. Rounds take about 10 seconds and a full game takes about 2 minutes.

**Play:** https://fardasticmanguy-rgb.github.io/cool-game/

## How to play

- Everyone holds cards 1 to 8. Each card works once. Six rounds.
- Everyone picks a card at the same time. If your card matches someone else's, you both crash and score nothing.
- The best solo card takes the pot. If everyone crashes, the pot rolls into the next round.
- Every round has a twist:
  - **High Roller**: highest solo card takes the pot
  - **Lowball**: lowest solo card takes the pot
  - **Double Up**: highest solo card takes double the pot
  - **Landmine**: one secret number is mined; play it and lose 4
  - **Payday**: every solo card pays its own number
  - **Heist**: the winner also steals 3 from the leader
- The last round pays double.

## Online play

Host a lobby and it shows up under **Open lobbies** for everyone who has the page open. Tap a lobby to join, no codes needed. The host can fill empty seats with bots. **Practice vs bots** works offline.

Multiplayer runs peer to peer over WebRTC using PeerJS. The host's browser runs the game and everyone else syncs from it.

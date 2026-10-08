# Coin Chess

A two-player chess game with a twist: a coin flip decides whether you can move.

## How to play

1. Open `coin-chess.html` in a web browser.
2. White goes first. Click **Flip the coin**.
3. **Heads:** select a piece, then a highlighted square to make your move.
4. **Tails:** your turn is skipped and play passes to your opponent.

**The special rule:** If your king is in check, you move without flipping. You must make a legal move to escape check.

Checkmate wins the game. Stalemate or only two kings remaining results in a draw.

## Features

- Two players sharing one device
- Legal move highlighting and check detection
- Castling, en passant, and a choice of promotion piece
- Board rotation
- A game journal recording moves and coin flips
- A **New game** button to start again

An en passant opportunity expires at the end of the next turn, including a turn skipped because of tails.

## Requirements

A modern web browser is all you need. The game is contained in one HTML file and works offline, with no installation or account required.

There is no computer opponent or online multiplayer. Refreshing or closing the page resets the game. Repetition and the fifty-move rule are not automatically enforced.

## Copyright

© 2026 Felix Beacher. All rights reserved.

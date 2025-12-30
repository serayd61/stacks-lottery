# Stacks Lottery

Decentralized lottery on Stacks with on-chain randomness.

## Features
- Fair ticket system
- Automatic prize pools
- Verifiable winner selection
- Multiple rounds

## How It Works
1. Admin starts a round
2. Users buy tickets (1 STX each)
3. Round ends after ~1 day
4. Winner is drawn using block height
5. Winner claims prize

## Functions
```clarity
(start-round)
(buy-ticket (round-id))
(draw-winner (round-id))
(get-round (round-id))
(get-user-tickets (round-id) (user))
```

## License
MIT



---
## Decentralized Lottery
- ✅ Fair random selection
- ✅ STX prize pool
- ✅ Mainnet live

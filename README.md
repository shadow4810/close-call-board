# Close Call Board

A public leaderboard for **close-1**, the NVDA trading contest on [technocore.chat](https://technocore.chat)
([rules](https://github.com/flop-labs/technocore-close-call-challenge)).

**Live page:** https://shadow4810.github.io/close-call-board/

## Where the numbers come from

Only from the close-1 referee's own signed posts (referee `did:key:z6MkowHQwsx9xr84WbWN3YCnKutyBnBXkT1ChKY4uEAAMzte`),
one set per five-minute sweep, in the rooms `d-close1-price`, `-flow`, `-positions`, `-pnl` and `-state`.
Nothing is estimated or recomputed.

- **History:** each room keeps only its last ~200 posts (about 17 hours), so earlier sweeps are archived
  and embedded in `index.html` (archive starts at sweep 216).
- **Latest sweeps:** the page reads the referee's rooms directly from your browser every minute and keeps
  only posts signed by the referee's DID. You can check any figure against those rooms yourself.
- **Limits:** the referee publishes the top 25 only; per-key balances are not public
  ([close-1#6](https://github.com/flop-labs/technocore-close-call-challenge/issues/6)).

Unofficial and independent: not made or endorsed by FLOP Labs. Built by a close-1 participant
(GitHub `shadow4810`).

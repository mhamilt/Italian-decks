# Italian Decks

A repository of images of Italian card decks.

## About

The intention of this repository is to be used as a submodule for any italian card game applications.

It has been tricky to find all these in one place, so I have taken inspiration from the [Scopa repository by OMerkel](https://github.com/OMerkel/Scopa/tree/master).

## Structure

Decks can be found in the [`decks/`](./decks/) directory. cards are named by first name of suit and their rank

| suit               | initial |
| ------------------ | ------- |
| bastone / scettro  | b       |
| spade / scimitarra | s       |
| cuppe              | c       |
| denaro             | d       |


Rank starts from Ace and ends at king. For 40 card decks king is `10` and 52 decks king is `13`. Ace is always `1`.

e.g. the king of clubs in the napoletane deck would be `decks/napoletane/b10.png`

### Tarocco

For Tarocco decks, there is a directory for the `semi/` and `triunfi/`. Triunfi are numbered `1` - `22`, e.g. `t1.png`, `t2.png`, `...`, `t22.png`.


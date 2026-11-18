<p align="center">
  <img src="assets/vesper-logo.png" width="96" alt="Vesper">
</p>

<h1 align="center">Vesper by SypherScore</h1>

<p align="center">
  Market-making bot for perpetual DEXs.<br>
  <a href="https://sypherscore.com/vesper">Website</a> ·
  <a href="https://sypherscore.com/vesper/guides">Guides</a> ·
  <a href="https://x.com/Vesper_mm">X</a> ·
  <a href="https://t.me/sypherscore">Telegram</a> ·
  <a href="https://discord.gg/2q74j5faJv">Discord</a>
</p>

---

Vesper makes markets on your own exchange account. You choose the exchange, the market and the mode, then press Start. The bot runs around the clock.

Traders use it to build volume on perp DEX points and rewards programs without sitting in front of a chart, and to earn maker-side fills instead of paying the spread.

More than **$2B** has been traded through Vesper since launch.

## Exchanges

| Exchange | Markets | Mode |
|---|---|---|
| Ondo Perps | US equities, indices, gold | Market making, Lumen (several markets in one session) |
| QFEX | Stocks, indices, commodities, FX | Market making |
| Hyperliquid HIP-3 (Entropy) | HIP-3 perps | Market making |
| Arcus | Crypto, stocks, gold | Market making, delta-neutral pairs |
| Lighter | Crypto, stocks | Delta-neutral with Arcus |
| RISEx | Crypto | Delta-neutral with Arcus |
| TxFlow | Crypto | Delta-neutral with Arcus |
| PopDEX | Crypto | Market making, up to four markets |
| Perpl | Crypto | Market making |
| Phoenix | Crypto | Market making |

Setup guides for each exchange: **https://sypherscore.com/vesper/guides**

## How it works

1. **Connect.** Open [sypherscore.com/vesper](https://sypherscore.com/vesper), connect your wallet and approve a trade-only key for the exchange you picked. The key can place and cancel orders. It cannot withdraw.
2. **Pick a market and a mode.** Each exchange has its own preset, tuned to how that order book behaves.
3. **Press Start.** Vesper trades for you inside the limits you set. Press Stop at any time from the dashboard.

Your funds stay in your own exchange account the whole time.

## Modes

**Market making.** Two-sided quotes on one exchange, without betting on direction.

**Delta-neutral.** Two exchanges in one session, with price exposure kept balanced across the pair.

**Lumen (Ondo Perps).** Several Ondo markets in one session.

## FAQ

**Does Vesper hold my funds?**
No. Vesper trades through a key that can only place and cancel orders on your own account.

**What does it cost?**
Exchange trading fees apply as usual. On some exchanges orders placed through Vesper also carry a small builder fee.

**Can I stop it?**
Yes, at any moment, from the dashboard.

**Is profit guaranteed?**
No. Market making can lose money when prices move fast. Start small, watch the first sessions and read the guide for your exchange.

**Which wallet do I need?**
An EVM wallet for most exchanges. BULK uses a Solana wallet.

## Data

Vesper's Hyperliquid volume carries the builder code `0x0ee49cd701e9575d683e409e23750a487e521053` and can be checked in Hyperliquid's public `builder_fills` archive.

---

<p align="center"><sub>Vesper is built by the SypherScore team. Trading perpetual futures carries risk.</sub></p>

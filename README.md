# 量化机器人中文版

[![GitHub Pages](https://img.shields.io/badge/docs-online-blue)](https://iterativv.github.io/NostalgiaForInfinity/)

## 介绍

引擎 [Freqtrade](https://www.freqtrade.io) crypto bot.回滚测试, check out the comments in the individual [commit](https://github.com/iterativv/NostalgiaForInfinity/commits/main) page.

## General Recommendations

为了获得最佳性能，建议使用 4 到 6 个同时持仓，且无限制资金。

建议使用包含 40 到 80 个交易对的 pairlist。Volume pairlist 效果很好。

优先选择稳定币（USDT、USDC 等）交易对，而不是 BTC 或 ETH 交易对。

强烈建议拉黑杠杆代币（如 *BULL、*BEAR、*UP、*DOWN 等）。

确保不要覆盖 config.json 中的任何变量。尤其要注意。 时间周期必须设置为 5m。

- `use_exit_signal` must set to true (or not set at all).
- `exit_profit_only` must set to false (or not set at all).
- `ignore_roi_if_entry_signal` must set to true (or not set at all).

## Discord Link
This is where we chat, hangout and contribute as a community (both links is the same server)

- [Discord Invite 1](https://discord.gg/DeAmv3btxQ)
- [Discord Invite 2](https://discord.gg/nzVeNvZsQq)

## Referral Links
If you like to help, you can also use the following links to sign up to various exchanges:

- [Binance: (20% discount on trading fees)](https://www.binance.com/join?ref=C68K26A9)
- [Kucoin: (20% lifetime discount on trading fees)](https://www.kucoin.com/r/af/QBSSS5J2)
- [Gate: (20% lifetime discount on trading fees)](https://www.gate.io/share/nfinfinity)
- [OKX: (20% discount on trading fees)](https://www.okx.com/join/11749725931)
- [MEXC: (10% discount on trading fees)](https://promote.mexc.com/a/luA6Xclb)
- [ByBit: (signup bonuses)](https://partner.bybit.com/b/nfi)
- [Bitget: (lifetime 20% rebate all plus 10% discount on spot fees)](https://bonus.bitget.com/fdqe83481698435803831)
- [BitMart: (20% lifetime discount on trading fees)](https://www.bitmart.com/invite/nfinfinity/en-US)
- [HTX: (Welcome Bonus worth 241 USDT upon completion of a deposit and trade)](https://www.htx.com/invite/en-us/1f?invite_code=ubpt2223)

## Donations
Absolutely not required. However, will be accepted as a token of appreciation.

- BTC: `bc1qvflsvddkmxh7eqhc4jyu5z5k6xcw3ay8jl49sk`
- ETH (ERC20): `0x83D3cFb8001BDC5d2211cBeBB8cB3461E5f7Ec91`
- BEP20/BSC (USDT, ETH, BNB, ...): `0x86A0B21a20b39d16424B7c8003E4A7e12d78ABEe`
- TRC20/TRON (USDT, TRON, ...): `TTAa9MX6zMLXNgWMhg7tkNormVHWCoq8Xk`

- Patreon : https://www.patreon.com/iterativ

# Main Sources & Reference Information to read beforehand
- Pairlists meant for the [Freqtrade](https://www.freqtrade.io) crypto bot.
- Strategy's main repository is located here [NFI](https://github.com/iterativv/NostalgiaForInfinity).

# Curated Static Lists

The pair lists generated are pairs which have had over 6 months of performance data analyzed, based on:

- Results: by amount of trades & profits given.
- Chart data: did some Technical Analysis of the pairs at hand on the daily and hourly charts. The 5 and 1 minute charts were used to observe activity on the latest 2 days to avoid "dead in the water" pairs. It was nothing profound ;).
- Behavioral: this was a more subjective approach, offset from Technical Analysis, I made decisions based on my experience on cryptocurrencies and unwanted patterns that most undesirable pairs have in common and noticed in my experience as an amateur trader.
- Fundamental Analysis: some pairs might have some sudden situation that makes them undesirable (e.g. LUNA).
- Other considerations: they are separated by exchange.
- Type of coin used: **USDT** (and some day in the future I'll make a list for BTC pairs)

## General Recommendations

 - The stable coin used is **USDT**, don't try to use other stable or whatnot pairs (~~BUSD~~, ~~BTC~~, ~~ETH~~). Of course, you can try using them but many coins might not even have the trading pair of your choice.
 - The config file has the name of the exchange it is meant for, don't try to use it for another exchange, mainly because some coins have different behaviours depending on the exchange and some pairs are not in all main exchanges. With NFI it is also possible that a certain pair A/B will give you profits on Exchange 1, but will give you losses on Exchange 2, so be careful!
- The list has leveraged (3L) coins included (commented out for your safety) for the *Kucoin* exchange, so keep in mind that these leveraged pairs carry risks! Suggest reading about them before allowing them to the list.
- I will be reviewing these lists often, might reduce how often depending on many factors (personal availability, exchanges & pairs used, time, etc.).
- May be seggragate into multiple config files to make the modification or download of the list easier.

### Discord Link

Here are the links to the Discord servers so you can chat and share with the community:

* [NFI Discord](https://discord.gg/DeAmv3btxQ)
* [Freqtrade Discord](https://discord.gg/YSVV29g2AD)

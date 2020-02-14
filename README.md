# TradingView Scripts

This repo contains all of the scripts I wrote for TradingView.

## Bands

The scripts here are bands with usually an upper, mid and bottom ranges.

### VWMA Bands

The bands are composed of these:

* Upper: VWMA with highs as source
* Mid: VWMA with HL2 as source
* Bottom: VWMA with lows as source

I find the best period for the band is `5`. It's important for the band to be closer to the price. VWMA is a volume based average, to widen the band, volume must increase.

There is a threshold setting which is gonna be different for assets and timeframes. Experiment with your own ideas.

![VWMA Bands](https://www.tradingview.com/x/bz2mnFAo/)

## Oscillators

The scripts here are oscillators usually being used to spot overbought or oversold conditions which is a load of crap. Using these as divergences spotter bodes well.

### Money Flow Index

Money Flow Index indicator script taken from [https://www.tradingview.com/script/g58H59ub-Money-Flow-Index-Beasley-Savage/](https://www.tradingview.com/script/g58H59ub-Money-Flow-Index-Beasley-Savage/).

## Histograms

The scripts are are histograms to spot weaknesses we can exploit. Also good for divergences if applicable.

### CM Williams Fix Vix Red Green

Modified from [https://www.tradingview.com/script/og7JPrRA-CM-Williams-Vix-Fix-Finds-Market-Bottoms/](https://www.tradingview.com/script/og7JPrRA-CM-Williams-Vix-Fix-Finds-Market-Bottoms/) to also draw red bars for shorting opportunities.

## Divergences

The scripts here will plot bullish and bearish divergences both hiddens or regulars.

### Awesome Oscillator Divergences

This is by far the most accurate divergence indicator in any timeframe. It's hard to go wrong with AO.

![AO Divergence](https://www.tradingview.com/x/gvF1C5F3/)

### CCI Divergences

Modified TradingView's built-in `Divergences Indicator` script to use [Commodity Channel Index](https://www.investopedia.com/terms/c/commoditychannelindex.asp) indicator as the oscillator.

![CCI Divergence](https://www.tradingview.com/x/hNbi7Dnp/)

### CCI High/Low Divergences

Modified TradingView's built-in `Divergences Indicator` script to use [Commodity Channel Index](https://www.investopedia.com/terms/c/commoditychannelindex.asp) indicator as the oscillator. There are 2 oscillators with bullish divergences calculated from candle lows while bearish divergences are calculated from candle highs.

![CCI High/Low Divergence](https://www.tradingview.com/x/jLaK5H5Q/)

### MFI Divergences

Modified TradingView's built in `Divergences Indicator` script to use [Money Flow Index](https://www.investopedia.com/terms/m/mfi.asp) indicator as the oscillator. Money Flow Index indicator script taken from [https://www.tradingview.com/script/g58H59ub-Money-Flow-Index-Beasley-Savage/](https://www.tradingview.com/script/g58H59ub-Money-Flow-Index-Beasley-Savage/).

![MFI Divergence](https://www.tradingview.com/x/W1sAty3D/)

### OBV Divergences

This indicator uses On Balance Volume indicator as the oscillator to spot for divergences.

![OBV Divergence](https://www.tradingview.com/x/EGrGG5IM/)

### Stochastic RSI Divergence

This indicator uses Stochastic RSI indicator as the oscillator to spot for divergences.

![Stochastic RSI Divergence](https://www.tradingview.com/x/7EYAukaG/)

## Averages

The scripts here will plot moving average indicators.

### Tri VWMA

Use 3 VWMA ribbons with only 1 indicator.

![Tri VWMA](https://www.tradingview.com/x/ihqC6HRE/)

## Reversals

The scripts here mainly highlight reversals.

### Engulfing - EMA

This script will highlight bullish and bearish engulfing candles with arrows on your chart. Using EMA as a confirmation if you wish to draw the arrows.

![Engulfing Candles - EMA](https://www.tradingview.com/x/MLs4ArAb/)

### Engulfing - VWMA

This script will highlight bullish and bearish engulfing candles with arrows on your chart. Using VWMA as a confirmation if you wish to draw the arrows. Also shows a second VWMA line for reference.

![Engulfing Candles - VWMA](https://www.tradingview.com/x/jP4lbLP8/)

# Max Super Trend

Max Super Trend is a custom indicator for MetaTrader 5 (MT5) developed by Forex Robot Easy Team. This indicator calculates the Super Trend based on the Average True Range (ATR) and plots it on the chart. It also calculates the initial stop distance based on the Super Trend.

## Input Parameters

- ATRPeriod: The period used to calculate the ATR (default value: 14).
- ATRMultiplier: The multiplier applied to the ATR to calculate the upper and lower bands of the Super Trend (default value: 2.0).
- SuperTrendPeriod: The period used to calculate the Super Trend (default value: 10).
- InitialStopDistance: The initial stop distance from the Super Trend (default value: 0.5).

## Indicator Buffers

- atrBuffer: Stores the calculated ATR values.
- superTrendBuffer: Stores the calculated Super Trend values.
- stopBuffer: Stores the calculated initial stop values.

## Indicator Initialization

The OnInit() function is called when the indicator is initialized. In this function, the indicator buffers are mapped and the indicator labels and name are set.

## Indicator Calculation

The OnCalculate() function is called for each new bar. In this function, the ATR is calculated using the iATR() function. Then, the Super Trend and initial stop values are calculated based on the ATR and price data. The calculated values are stored in the indicator buffers.

## Expert Initialization

The OnInitExpert() function is called when the expert advisor using this indicator is initialized. In this function, trading is enabled if it is allowed.

## Expert Deinitialization

The OnDeinitExpert() function is called when the expert advisor using this indicator is deinitialized. In this function, no action is taken.

## Expert Tick

The OnTick() function is called on each tick. In this function, no action is taken.

## Expert Start

The OnStart() function is called when the expert advisor using this indicator starts. In this function, no action is taken.

---

This code is provided as a sample and is not the official product developed by Forex Robot Easy Team. It is intended to demonstrate how the Max Super Trend indicator works. To find the official developer and obtain the full version of this product, please visit the MQL5 website.

For detailed reviews and trading results of this Max Super Trend indicator, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/max-super-trend-review-forex-software-with-real-results/). Forex Robot Easy is not the official developer of this product, but they provide comprehensive information and reviews about various forex software products.

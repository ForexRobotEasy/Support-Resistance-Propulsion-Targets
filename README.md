# SupportResistance.mq5 ReadMe File

## About
This code is a custom indicator for MetaTrader 5 that calculates support and resistance levels based on historical data. It also detects potential price reversals and calculates potential trading distances based on the support and resistance levels. This code is provided as a sample and is not the official product developed by Forex Robot Easy. For detailed reviews and trading results of the official product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/support-resistance-propulsion-targets-forex-software-review/).

## Input Parameters
1. `numberOfDays` (default: 2): Number of days to consider for support and resistance calculation.
2. `numberOfWeeks` (default: 6): Number of weeks to consider for support and resistance calculation.
3. `numberOfMonths` (default: 6): Number of months to consider for support and resistance calculation.
4. `reversalThreshold` (default: 0.5): Threshold to determine potential price reversals.

## Variables
1. `supportLine`: Variable to store the calculated support line.
2. `resistanceLine`: Variable to store the calculated resistance line.
3. `propulsionGap`: Variable to store the calculated propulsion candle gap.

## Functions
1. `OnInit()`: Custom indicator initialization function.
2. `OnCalculate()`: Custom indicator iteration function.

### CalculateSupportResistance()
Calculates support and resistance lines based on historical data. The implementation of this function is not provided in the sample code.

### CalculatePropulsionGap()
Calculates the propulsion candle gap based on historical data. The implementation of this function is not provided in the sample code.

### IsPotentialReversal()
Checks if the price is at a potential reversal point based on the price and threshold. The implementation of this function is not provided in the sample code.

### TradeSupportResistance()
Trades based on the support and resistance levels. The implementation of this function is not provided in the sample code.

### CalculateTradingDistance()
Calculates the potential trading distance based on the support and resistance levels. The implementation of this function is not provided in the sample code.

## Usage
This code can be used as a starting point to develop a custom indicator for MetaTrader 5 that calculates support and resistance levels, detects potential price reversals, and calculates potential trading distances. It is recommended to consult the official developer of the product for detailed information and to find the official version of this code on the MQL5 website.

## Disclaimer
Forex Robot Easy is not the official developer of this product. This code is provided as a sample and can work as described in the official product. For detailed reviews and trading results of the official product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/support-resistance-propulsion-targets-forex-software-review/). For the official developer of this product, please refer to MQL5.

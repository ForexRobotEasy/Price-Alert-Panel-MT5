# Forex Robot Easy - Candlestick Patterns Finder

This code is a sample implementation of a Forex robot that detects and alerts traders about various candlestick patterns. The robot scans the market in real-time and checks for the presence of four specific candlestick patterns: Doji, Engulfing, Hammer, and Shooting Star.

## How it Works

The code consists of several functions and a main function that is executed on every tick of the market. Here's a breakdown of the code:

### Input Parameters

The code starts by defining four input parameters that allow the user to customize the candlestick patterns to be detected.

### DetectPattern Function

The `DetectPattern` function is responsible for looping through the bars on the chart and checking if a specific candlestick pattern is present. It takes two arguments: `pattern` (the pattern to detect) and `timeframe` (the timeframe to scan). It returns a boolean value indicating whether the pattern was detected or not.

### Candlestick Pattern Detection Functions

The code includes four functions (`IsDoji`, `IsEngulfing`, `IsHammer`, and `IsShootingStar`) that check if a given candlestick pattern is present based on the open, high, low, and close prices of the current bar. Each function returns a boolean value indicating whether the pattern was detected.

### SendAlert Function

The `SendAlert` function is responsible for sending an alert to the trader when a candlestick pattern is detected. It takes a string parameter `pattern` (the detected pattern) and displays an alert message to the trader.

### SetCustomAlert Function

The `SetCustomAlert` function sets a custom alert for a specific pattern. It takes a string parameter `pattern` and calls the `SendAlert` function if the specified pattern matches one of the input parameters.

### OnTick Function

The `OnTick` function is the main function that is executed on every tick of the market. It checks for the presence of each candlestick pattern using the `DetectPattern` function and sends alerts accordingly. It also sets custom alerts for specific patterns using the `SetCustomAlert` function.

## Product Description

Forex Robot Easy presents the Candlestick Patterns Finder, a powerful tool for traders looking to identify and capitalize on profitable candlestick patterns. This expert advisor (EA) is designed to scan the market in real-time and detect four popular candlestick patterns: Doji, Engulfing, Hammer, and Shooting Star.

With the Candlestick Patterns Finder, traders can receive instant alerts whenever these patterns are identified, allowing them to make informed trading decisions. The EA is fully customizable, allowing users to specify the patterns they are interested in detecting and the timeframe they want to scan.

This product is based on proven candlestick pattern detection algorithms, ensuring accurate and reliable results. Traders can confidently rely on the Candlestick Patterns Finder to enhance their trading strategies and improve their overall profitability.

To learn more about the Candlestick Patterns Finder and see detailed reviews and trading results, visit our website at [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/review-price-alert-panel-mt5-the-candle-stick-patterns-finder/).

Please note that Forex Robot Easy is not the official developer of this product. We are showcasing a sample code that demonstrates the functionality of the Candlestick Patterns Finder. For the official developer of this product, please refer to MQL5.

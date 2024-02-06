# ISolz MTF Candles2

This code is a custom indicator for MetaTrader 4 developed by the Forex Robot Easy Team. It is designed to enhance forex trend analysis by allowing the user to select and display the high and low values of a specific candle based on different time frames.

## Indicator Initialization Function

The `OnInit` function is called when the indicator is initialized. It initializes the global variables, including `selectedCandle` which stores the index of the selected candle, and `candleTimeFrames` which is an array of available candle time frames. The available time frames are 'M1', 'M5', 'M15', 'M30', 'H1', 'H4', and 'D1'. It also sets the indicator buffers and their styles.

## Indicator Iteration Function

The `OnCalculate` function is called for each new tick or bar. It calculates the index of the selected candle based on the `selectedCandle` variable and sets the indicator values for the high and low of that candle. The calculated bars are returned.

## Indicator Input Parameters Function

The `OnParameters` function displays the available candle time frames and prompts the user to select the desired candle index. The selected index is stored in the `selectedCandle` variable.

## Indicator Deinitialization Function

The `OnDeinit` function is called when the indicator is deinitialized. It cleans up resources by resetting the `selectedCandle` variable and freeing the memory used by the `candleTimeFrames` array.

---

Product Description:

This code is a custom indicator developed by the Forex Robot Easy Team. It is designed to enhance forex trend analysis by allowing the user to select and display the high and low values of a specific candle based on different time frames.

With ISolz MTF Candles2, traders can easily analyze trends and identify potential entry and exit points. By selecting the desired candle index, users can view the high and low values of that specific candle on their charts.

The indicator offers a range of candle time frames, including 'M1', 'M5', 'M15', 'M30', 'H1', 'H4', and 'D1', allowing traders to analyze trends on different time scales.

Please note that Forex Robot Easy is not the official developer of this product. We are showcasing this sample code that can work as described in the product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, visit [here](https://forexroboteasy.com/forex-robot-review/isolz-mtf-candles2-review-enhance-forex-trend-analysis/).

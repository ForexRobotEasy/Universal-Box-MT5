# Universal Box MT5

[![Forex Robot Easy](https://forexroboteasy.com)](https://forexroboteasy.com)

Universal Box MT5 is a code snippet that allows you to draw rectangles on your MetaTrader 5 (MT5) chart to represent different trading sessions. This can be useful for visualizing the different time zones and market open/close times, aiding in your trading decisions.

## Features
- Draws rectangles on the chart to represent Asian, European, and American trading sessions
- Customizable session open and close times
- Customizable box color

## How it Works
The code uses the input parameters to define the start and end times for each trading session. It then calls the `DrawRectangle` function to draw rectangles on the chart with the specified session start and end times, using the specified box color.

The `OnInit` function initializes the session start and end times based on the current time and the input parameters. The `OnCalculate` function is called for every new tick and draws the rectangles on the chart.

The `DrawRectangle` function creates a rectangle object on the chart using the `ObjectCreate` function. It sets the rectangle color using the `ObjectSet` function.

Please note that this code is provided as a sample and not as an official product developed by Forex Robot Easy Team. To find the official developer of this product, please refer to MQL5.

## Usage
To use this code, follow these steps:
1. Copy the code and paste it into a new script or expert advisor in MetaEditor.
2. Set the desired input parameters, such as the session open and close times and the box color.
3. Compile the code.
4. Drag and drop the script or expert advisor onto your MT5 chart.
5. The rectangles representing the trading sessions will be drawn on the chart.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - Universal Box MT5 Review](https://forexroboteasy.com/forex-robot-review/universal-box-mt5-review-optimize-forex-trading-with-breakout-strategies/).

Please note that Forex Robot Easy is not the official developer of this product. We only provide this code as a sample that can work as described in the product. To find the official developer of this product, please use MQL5.

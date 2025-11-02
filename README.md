# Custom Session Indicator for MetaTrader 5

This is a flexible and highly customizable indicator for MetaTrader 5 (MT5) that allows you to draw session boxes for any time period directly on your chart. It's designed to help traders visualize and analyze price action during specific trading hours, such as the New York session, London session, or any other custom time frame you define.



## Description

The Custom Session indicator is a powerful tool for traders who focus on session-based strategies. It automatically draws a box around the high and low of a specified time period each day, making it easy to spot key levels of support and resistance. The indicator is fully customizable, allowing you to adjust the session times, timezone, colors, and other visual elements to fit your trading style.

## Features

*   **Customizable Session Times:** Define the exact start and end time of the session you want to track.
*   **Timezone Offset:** Easily adjust the session times to any timezone, so you can track sessions from around the world, regardless of your broker's server time.
*   **Visual Customization:** Control the colors of the session box, border lines, and middle line. You can also adjust the line width and style.
*   **Session Labels:** Add a custom text label to your session boxes to easily identify them. You can control the label's position, font size, and color.
*   **Middle Line:** Optionally display a middle line within the session box, which can act as a significant price level.
*   **Automatic Broker Timezone Detection:** The indicator automatically detects your broker's GMT offset, simplifying the timezone setup.
*   **Clean and Efficient:** The indicator is designed to be lightweight and efficient, so it won't slow down your trading platform.

## How to Use

1.  **Download:** Download the `CustomSession.mq5` file from this repository.
2.  **Installation:**
    *   Open your MetaTrader 5 platform.
    *   Go to `File` -> `Open Data Folder`.
    *   Navigate to the `MQL5` -> `Indicators` folder.
    *   Copy the `CustomSession.mq5` file into this folder.
3.  **Activation:**
    *   Restart MetaTrader 5 or refresh the indicator list in the `Navigator` window.
    *   Drag the "CustomSession" indicator from the `Navigator` onto your chart.
4.  **Configuration:** Adjust the indicator's settings in the "Inputs" tab to your preferences.

## Input Parameters

### Session Time Settings

*   `SessionStartHour`: The hour when the session starts (0-23).
*   `SessionStartMinute`: The minute when the session starts (0-59).
*   `SessionEndHour`: The hour when the session ends (0-23).
*   `SessionEndMinute`: The minute when the session ends (0-59).
*   `TimezoneOffsetHours`: The GMT offset of the session's timezone (e.g., -4 for New York).
*   `TimezoneOffsetMinutes`: The minute offset of the session's timezone.

### Display Settings

*   `MaxBoxes`: The maximum number of session boxes to display on the chart.
*   `BoxColor`: The fill color of the session box.
*   `LineColor`: The color of the session box's border lines.
*   `LineWidth`: The width of the border lines.
*   `LineStyle`: The style of the border lines (e.g., solid, dashed, dotted).

### Middle Line Settings

*   `ShowMiddleLine`: Set to `true` to display the middle line, or `false` to hide it.
*   `MiddleLineColor`: The color of the middle line.
*   `MiddleLineStyle`: The style of the middle line.

### Session Label Settings

*   `SessionLabelText`: The text to display as the session label (leave empty for no label).
*   `LabelPosition`: The position of the label (Top, Middle, or Bottom of the session box).
*   `LabelFontSize`: The font size of the label.
*   `LabelColor`: The color of the label.

## Author

*   **CallMeAM**
*   Telegram: [https://t.me/amirmasoud_rsli](https://t.me/amirmasoud_rsli)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

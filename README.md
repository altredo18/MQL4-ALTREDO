# MQL4-ALTREDO
Metatrader (MT4, MT5) indicators and EAs (Robots) are here | ALTREDO
https://www.altredo.com/
Forex Signals and Forecast Currency Indicator is based on the well-known Super Trend indicator. We added a filter based on the Moving Average to get rid of noise and refine the indicator signals. By filtering signals, we were able to improve the accuracy of the indicator's currency trend prediction, as well as increase the overall efficiency of the indicator.

The indicator is recommended to be used on the following timeframes: H1, H4, D1, W1, MN (Month).
Currency pairs: Everything.

The indicator can generate alerts in the form of messages and a sound signal when a new signal appears, as well as send a message about the emerging signal by email.

Indicator settings:
extern int    Amplitude        = 2;     // Amplitude (Supertrend)
extern int    MA_Period        = 3;     // MA Filter Period
extern bool   alertsOn         = false; // Alerts ON/OFF
extern bool   alertsOnCurrent  = false; // Alerts on Current Bar ON/OFF
extern bool   alertsMessage    = true;  // Alerts Message ON/OFF
extern bool   alertsSound      = false; // Alerts Sound ON/OFF
extern bool   alertsEmail      = false; // Send Email ON/OFF

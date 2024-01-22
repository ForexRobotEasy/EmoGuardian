# EmoGuardian ReadMe File

This ReadMe file provides an overview and basic instructions for using the EmoGuardian Forex software. EmoGuardian is a cutting-edge software designed to manage emotions and prevent impulsive trading. Please note that ForexRobotEasy is not the official developer of this product. We are only showcasing sample code that can work as described in this product. To find the official developer of EmoGuardian, please refer to MQL5.

For detailed reviews and trading results of EmoGuardian, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/emoguardian-review-forex-software-for-emotion-controlled-trading/).

## Compatibility

- EmoGuardian is compatible with most Hedging accounts.
- EmoGuardian is not compatible with Netting Accounts.
- EmoGuardian does not function on the strategy tester.

## User Manual

For comprehensive and detailed instructions on using EmoGuardian and its functionalities, please refer to the user manual.

## Daily Limits

EmoGuardian provides several daily limit settings to help traders manage their trading activities effectively. These limits include:

1. Minimum and Maximum Equity Levels: Traders can set minimum and maximum equity levels in the account currency.
2. Maximum Loss or Gain: Traders can define a maximum loss or gain per day in currency or percentage.
3. Customizable Start Time: Traders have the option to customize the start time of each trading day.

## Code Overview

The provided code is an example implementation of EmoGuardian. It includes the following functions:

### Expert initialization function (`OnInit()`)

- Checks compatibility with Hedging accounts. If the account is a Netting Account, an error message is displayed.
- Checks if running in the strategy tester. If running in the tester, an error message is displayed.
- Loads user-defined settings.
- Initializes other necessary variables and indicators.

### Expert deinitialization function (`OnDeinit(const int reason)`)

- Performs necessary cleanup and tasks before the Expert Advisor is removed.

### Expert tick function (`OnTick()`)

- Checks if the current time matches the user-defined start time.
- Performs necessary actions for the start of the trading day.
- Checks equity levels and adjusts if necessary.
- Checks daily loss and gain limits and adjusts if necessary.
- Places trades or performs other trading actions.
- Displays appropriate messages or notifications to the trader.

### Load user-defined settings function (`LoadSettings()`)

- Loads minimum and maximum equity levels from user inputs.
- Loads maximum loss or gain per day from user inputs.
- Loads customizable start time from user inputs.

### Save user-defined settings function (`SaveSettings()`)

- Saves minimum and maximum equity levels to user inputs.
- Saves maximum loss or gain per day to user inputs.
- Saves customizable start time to user inputs.

## Disclaimer

Please note that ForexRobotEasy is not the official developer of EmoGuardian. We are only showcasing sample code that can work as described in this product. To find the official developer of EmoGuardian, please refer to MQL5. For detailed reviews and trading results of EmoGuardian, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/emoguardian-review-forex-software-for-emotion-controlled-trading/).

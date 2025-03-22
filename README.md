# Moving Average Crossover Strategy with Configurable Stop Losses and Take Profit

This TradingView strategy script implements a **Moving Average Crossover System** enhanced with **multiple configurable stop loss** options and **take profit** functionality. The strategy allows traders to test various risk management techniques alongside a classic crossover entry signal.

## Features

-   **Moving Average Crossover Entry**
    
    -   Buy when the fast MA crosses above the slow MA.
        
    -   Sell (exit) when the fast MA crosses below the slow MA.
        
-   **Configurable Stop Loss Options**  
    Choose one or more of the following to manage risk:
    
    -   **Fixed Stop Loss** (% below entry)
        
    -   **Trailing Stop Loss** (% below high since entry)
        
    -   **ATR-based Stop Loss** (volatility-based using ATR)
        
    -   **Support Level Stop Loss** (recent lowest low over a configurable period)
        
-   **Take Profit Option**
    
    -   Exit position when a predefined % gain is achieved.
        

## Inputs

Input

Description

Fast MA Length

Period for the fast moving average

Slow MA Length

Period for the slow moving average

Use Fixed Stop Loss

Enable fixed % stop loss

Fixed Stop Loss Percentage

% below entry price

Use Trailing Stop Loss

Enable trailing stop loss

Trailing Stop Loss Percentage

% below high since entry

Use ATR Stop Loss

Enable ATR-based stop loss

ATR Length

Period for ATR calculation

ATR Multiplier

Multiplier for ATR value

Use Support Stop Loss

Enable stop loss based on support level

Support Level Length

Lookback for recent low

Use Take Profit

Enable take profit

Take Profit Percentage

% above entry price

## Plots

-   Moving Averages (Fast & Slow)
    
-   Stop Loss Levels (color-coded)
    
-   Take Profit Level
    
-   Buy/Sell Signals
    

## How It Works

1.  **Entry Signal**: A long position is opened when the fast moving average crosses above the slow moving average.
    
2.  **Exit Signals**: The position is closed on any of the following:
    
    -   Fast MA crosses below Slow MA
        
    -   Price hits any active stop loss level
        
    -   Price reaches take profit level
        

## Notes

-   Multiple stop loss types can be used simultaneously.
    
-   The trailing stop dynamically adjusts upwards with price movement.
    
-   This strategy is backtestable on TradingView's strategy tester.

# Moving Average Crossover Strategy with Configurable Stop Losses and Take Profit

This TradingView strategy script implements a **Moving Average Crossover System** enhanced with **multiple configurable stop loss** options and **take profit** functionality. The strategy allows traders to test various risk management techniques alongside a classic crossover entry signal.

## Features

-   **Moving Average Crossover Entry**
    
    -   Buy when the fast MA crosses above the slow MA.
        
    -   Sell (exit) when the fast MA crosses below the slow MA.
        
-   **Configurable Stop Loss Options**  
    Choose one or more of the following to manage risk:
    
    -   **Fixed Stop Loss** (% below entry)
        
    -   **Trailing Stop Loss** (% below high since entry)
        
    -   **ATR-based Stop Loss** (volatility-based using ATR)
        
    -   **Support Level Stop Loss** (recent lowest low over a configurable period)
        
-   **Take Profit Option**
    
    -   Exit position when a predefined % gain is achieved.
        

## Inputs

Input

Description

Fast MA Length

Period for the fast moving average

Slow MA Length

Period for the slow moving average

Use Fixed Stop Loss

Enable fixed % stop loss

Fixed Stop Loss Percentage

% below entry price

Use Trailing Stop Loss

Enable trailing stop loss

Trailing Stop Loss Percentage

% below high since entry

Use ATR Stop Loss

Enable ATR-based stop loss

ATR Length

Period for ATR calculation

ATR Multiplier

Multiplier for ATR value

Use Support Stop Loss

Enable stop loss based on support level

Support Level Length

Lookback for recent low

Use Take Profit

Enable take profit

Take Profit Percentage

% above entry price

## Plots

-   Moving Averages (Fast & Slow)
    
-   Stop Loss Levels (color-coded)
    
-   Take Profit Level
    
-   Buy/Sell Signals
    

## How It Works

1.  **Entry Signal**: A long position is opened when the fast moving average crosses above the slow moving average.
    
2.  **Exit Signals**: The position is closed on any of the following:
    
    -   Fast MA crosses below Slow MA
        
    -   Price hits any active stop loss level
        
    -   Price reaches take profit level
        

## Notes

-   Multiple stop loss types can be used simultaneously.
    
-   The trailing stop dynamically adjusts upwards with price movement.
    
-   This strategy is backtestable on TradingView's strategy tester.

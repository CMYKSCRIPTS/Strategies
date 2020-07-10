## ◊ Introduction 
This script makes use of three RMI's, that indicate Overbought/Oversold on different timescales that correspond with Frequency’s that move the market. 

## ◊ Origin 
The Relative Momentum Index was developed by Roger Altman and was introduced in his article in the February, 1993 issue of Technical Analysis of Stocks & Commodities magazine. 
While RSI counts up and down ticks from close to close, the Relative Momentum Index counts up and down ticks from the close relative to a close x number of days ago. 
This results in an RSI that is smoother, and has another setting for fine tuning results. 

This bot originated out of Project XIAM, an investigative script that outlined my approach towards Automated Trading Strategies. 
Are you interested in writing bots yourself ? check out the beta version of this script. 
It has many bugs, but also most of the Skeleton. 

## ◊ Usage 
This script is intended for Automated Trading with AUTOVIEW or TVAUTOTRADER, on the 1 minute chart. 

## ◊ Features Summary 
- Overlay Mode
- Indicator Mode 
- Three RMI's 
- Trend adjustment 
- Pyramiding
- Ignore first entries 
- Take Profit 
- Stop Loss 
- Interval between Entries
- Multiring Fix
- Alert signal Seperation

## ◊ Community 
Wanna try this script out ? need help resolving a problem ? 

CMYK :: https://discord.gg/bg2TDvh 
AUTOVIEW :: https://discordapp.com/invite/BFz8VPn 
TRADINGVIEW UNOFFICIAL :: https://discord.gg/fZFcJBy 

## ◊ Setting up Autoview Alerts 
Use the study version of this script, To set up The Alerts Autoview Picks up on. 

The Signals to work with are : 
Open 1 Long
Use this to open one Long Position. 
With quantity being : / 
Once per bar 
Being larger than 0 
Comment example : e=exchange b=long q=amount t=market 
Open 1 Short
Use this to open one Short Position. 
With quantity being : / 
Once per bar 
Being larger than 0 
Comment example : e=exchange b=short q=amount t=market 
Close1 Position
Use this to Close The amount of one Open Position. 
With quantity* being : / 
Once per bar 
Being larger than 0 
Comment example : e=exchange c=position q=amount t=market 

*Beware when using a percental % quantity, instead of an absolute quantity. 
Percental Quantities are based on the , Not 
And will change in absolute value relative to the amount of open trades. 

Close All positions
Use this to Close All Open Positions. 
With quantity being : 
Once per bar 
Being larger than 0 
Comment example : e=exchange c=position t=market 

For the specific Syntax used in the comment of the alert, visit Autoview. 

## ◊ Backtesting 
Use the strategy version of this script for backtesting. 

## ◊ Contact 
Wanna try this script out ? need help resolving a problem ? 

DISCORD CMYK :: https://discord.gg/c79jf7s

# Trader-Behaviour-vs-Market-Sentiment-Analysis

## Overview
This project analyzes how trader behaviour changes across Bitcoin market sentiment regimes (Fear vs Greed).

Using Hyperliquid trade history and the Fear-Greed Index, I examined whether traders adjust leverage, frequency and position bias — and whether those adjustments actually improve profitability.

The goal is not just correlation, but identifying behavioural patterns that could inform trading decisions.

## Dataset

1) Bitcoin Fear-Greed Index — daily sentiment classification

2) Hyperliquid historical trades — execution level trade data

Both datasets were aligned on daily timestamps before analysis.

## How to Run
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook analysis.ipynb

## Method
• Aggregated trades into daily trader metrics (PnL, win rate, size, leverage)
• Compared behaviour across sentiment regimes
• Segmented traders by leverage and activity level
• Evaluated performance differences

## Key Findings
• Traders increased activity during Greed but profitability per trade decreased
• Fear regimes produced larger but less frequent profits
• High leverage amplified losses during volatile periods

##Strategy Implications
• Reduce leverage during Fear regimes
• Avoid overtrading during Greed regimes
• Risk scaling should depend on trader consistency


# Short-Term Futures Price Prediction
**Stage:** Problem Framing & Scoping (Stage 01)

## Problem Statement
Junior traders face uncertainty during intraday swings and lack quantified guidance for entries/exits. This project builds a model to forecast the next 1–5 minute price movement on selected futures using order book depth, tick data, and recent price patterns.

## Stakeholder & Useful Answer
Primary users: junior futures traders. Useful answer: predictive directional signal (+1/0/–1) with probability score, updated near real time. Success = Sharpe ↑ ≥0.3 vs baseline and hit rate ≥55% over a rolling 2-week window.

## Repo Layout
data/, src/, notebooks/, docs/

<div align="center">

# 📐 Black-Scholes Option Pricing Calculator & Heatmap

**Interactive web-based Black-Scholes calculator with real-time option pricing, payoff curves, and a dual call/put price heatmap across spot price × volatility dimensions.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Chart.js](https://img.shields.io/badge/Charts-Chart.js-FF6384)](https://chartjs.org)

</div>

---

## Overview

Browser-based Black-Scholes option pricing tool that computes call and put prices with full calculation transparency. Features a real-time payoff curve chart and a dual heatmap showing how option prices vary across spot price and volatility dimensions. Supports time input in days, months, or years.

## Features

- **Option Pricing Engine** — Black-Scholes formula with custom normal CDF implementation
- **Payoff Curve** — Chart.js line chart showing option price vs. stock price (50%–150% of current)
- **Dual Heatmaps** — 10×10 call and put price grids across configurable spot price and volatility ranges
- **Time Unit Flexibility** — Input expiry in days, months, or years
- **Calculation Transparency** — Displays S, K, T, r, σ, and option type alongside the result
- **Responsive Design** — Grid layout adapts to desktop and mobile viewports
- **Zero Dependencies** — Pure HTML/CSS/JS with Chart.js CDN only

## Quick Start

```bash
git clone https://github.com/RHarmit/Black-Scholes.git
cd Black-Scholes
# Open index.html in any browser — no server needed
```

## Parameters

| Input | Description | Default |
|-------|-------------|---------|
| Stock Price (S) | Current underlying price | $100 |
| Strike Price (K) | Option strike | $100 |
| Time (T) | Time to expiry | 1 year |
| Risk-Free Rate (r) | Annual risk-free rate | 5% |
| Volatility (σ) | Implied volatility | 20% |
| Option Type | Call or Put | Call |

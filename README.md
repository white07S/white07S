<h1 align="center">Preetam Sharma</h1>

<p align="center">
  <em>Quantitative modelling · LLM inference &amp; compression · Retrieval systems</em>
</p>

<p align="center">
  Associate Director, Risk &amp; AI Modelling at <a href="https://www.ubs.com/global/en.html">UBS</a> ·
  MSc Artificial Intelligence, <a href="https://www.put.poznan.pl/">Poznan University of Technology</a>
</p>

---

I build systems where the maths has to survive contact with a machine — option
pricers that run fast enough to be useful, quantizers that hold accuracy at
5 bits, retrieval that ships as a single file. Most of what's here started as a
question I couldn't find a satisfying answer to, so I wrote one.

Everything below is work I stand behind. Older experiments have been retired
rather than left to rot in public.

## Systems & ML infrastructure

| Project | What it is |
| :--- | :--- |
| **[valise](https://github.com/white07S/valise)** ·&nbsp;`Rust` | Retrieval in one file. Documents, a BM25 index, and compressed vectors live in a single portable `.vls` capsule — no server, no index build step. Vectors are quantized to ~5.5 bits/dim and the search sketch is derived at open, never written to disk. On [crates.io](https://crates.io/crates/valise) and [PyPI](https://pypi.org/project/valise/). |
| **[qam-w](https://github.com/white07S/qam-w)** ·&nbsp;`Rust` | Companion code for *QAM-W: Joint 2D Codebook Quantization for LLM Weights via Hadamard Rotation and Activation-Aware Scaling.* Encodes pairs of rotated coordinates jointly under a 2D Lloyd–Max codebook. At ≈5.5 bpw it stays within ±0.4% of BF16 perplexity across five models from 1.1B–13B. |

## Quantitative finance

| Project | What it is |
| :--- | :--- |
| **[TradingPatternScanner](https://github.com/white07S/TradingPatternScanner)** ·&nbsp;`Python` | Detects complex chart patterns — head and shoulders, wedges, and more — from price series. |
| **[OptionPricingModels](https://github.com/white07S/OptionPricingModels)** ·&nbsp;`Rust` | Binomial, Black–Scholes, Heston and intrinsic-value pricing, with Least Squares Monte Carlo and random-forest regression for the American exercise boundary. |
| **[Pricing-Models](https://github.com/white07S/Pricing-Models)** ·&nbsp;`Python` | Option pricing accelerated with Numba, written with as few dependencies as possible. Several models carry their own ML component and performance assessment. |
| **[BayesRegimeVol](https://github.com/white07S/BayesRegimeVol)** ·&nbsp;`Python` | Bayesian nonlinear pricing under regime switching. Hidden Markov regimes and Heston-type stochastic volatility, estimated jointly by particle MCMC with an unscented Kalman filter for the latent volatility. |
| **[OptionPricing](https://github.com/white07S/OptionPricing)** ·&nbsp;`Java` | JavaFX desktop application pricing American, Bermudan and European options by Monte Carlo simulation. |

## Trading strategies

| Project | What it is |
| :--- | :--- |
| **[ForexRL](https://github.com/white07S/ForexRL)** ·&nbsp;`Python` | Deep reinforcement learning for high-volume, high-frequency FX portfolio management. |
| **[Forex-Trading](https://github.com/white07S/Forex-Trading)** ·&nbsp;`Python` | A DQN-based high-frequency trading agent for the FX market. |
| **[ForexMeanReversion](https://github.com/white07S/ForexMeanReversion)** ·&nbsp;`Python` | Mean reversion on EUR/USD 1-minute data via an Ornstein–Uhlenbeck process, with feature engineering, dynamic signal generation and a backtesting harness. |
| **[Forex-Fibonacci](https://github.com/white07S/Forex-Fibonacci)** ·&nbsp;`Python` | Fibonacci retracement as a mathematical model, with ML-driven entry and exit formulation. |
| **[Fibonacci-Retracement](https://github.com/white07S/Fibonacci-Retracement)** ·&nbsp;`Python` | Learned identification of retracement, support and resistance levels. |
| **[HFT-hedging](https://github.com/white07S/HFT-hedging)** ·&nbsp;`Python` | Optimises the hedging decision at every timestep `t` under high-frequency constraints. |

---

<h3>Interests</h3>

Order-book modelling and market microstructure · post-training quantization and
efficient inference · retrieval systems · brain–computer interfaces, which I'd
happily collaborate on.

<h3>Elsewhere</h3>

<p>
  <a href="mailto:sharmapreetam.uk@outlook.com">sharmapreetam.uk@outlook.com</a> ·
  <a href="https://linkedin.com/in/preetam_sharma">LinkedIn</a>
</p>

<p align="center">
  <sub><code>Rust</code> · <code>Python</code> · <code>C/C++</code> · <code>Java</code> · <code>PyTorch</code> · <code>Numba</code> · <code>Metal</code> · <code>Docker</code></sub>
</p>

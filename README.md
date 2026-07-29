# Preetam Sharma

**Quantitative modelling · ML infrastructure · Retrieval systems**

I lead risk and AI modelling at [UBS](https://www.ubs.com/global/en.html). Away from
the day job I write mostly Rust and Python, on problems where the maths has to
survive contact with a machine — option pricers fast enough to be worth running,
weight quantizers that still hold up at five bits, retrieval that ships as a
single file.

Most of what's here started the same way: I ran into a question, decided the
existing answers were heavier than the problem deserved, and wrote my own. A few
turned out well. The rest I've retired rather than leave them sitting in public
padding the repo count — so what's below is the work I'd actually want someone to
open.

---

## Open to work

I'm open to conversations about **quantitative research, ML infrastructure, and
inference systems** — full-time or contract. What gets my attention is a problem
where the difficulty is real and someone is going to read the code properly.

I'm employed and not in a hurry, which I mention only because it means I'd rather
find the right problem than the quickest one. If you're early in your thinking and
want to talk something through before it's a role, that's genuinely fine.

📫 **[sharmapreetam.uk@outlook.com](mailto:sharmapreetam.uk@outlook.com)** — email
is the fastest way to reach me. Also on [LinkedIn](https://linkedin.com/in/preetam_sharma).

---

## Selected work

### Retrieval

**[valise](https://github.com/white07S/valise)** · `Rust`
Retrieval in one file. Documents, a BM25 index, and compressed vectors all live in
a single portable `.vls` capsule — no server, no index build step. Vectors are
quantized to ~5.5 bits/dim, and the search sketch is derived when you open the file
rather than written to disk. Published on [crates.io](https://crates.io/crates/valise)
and [PyPI](https://pypi.org/project/valise/).

### Quantitative finance

| Project | |
| :--- | :--- |
| **[TradingPatternScanner](https://github.com/white07S/TradingPatternScanner)** · `Python` | Detects complex chart patterns — head and shoulders, wedges, and others — from raw price series. The most-used thing I've written. |
| **[OptionPricingModels](https://github.com/white07S/OptionPricingModels)** · `Rust` | Binomial, Black–Scholes, Heston and intrinsic-value pricing, with Least Squares Monte Carlo and random-forest regression handling the American exercise boundary. |
| **[Pricing-Models](https://github.com/white07S/Pricing-Models)** · `Python` | Option pricing accelerated with Numba, written against as few dependencies as I could get away with. Several models carry their own ML component and performance assessment. |
| **[BayesRegimeVol](https://github.com/white07S/BayesRegimeVol)** · `Python` | Bayesian nonlinear pricing under regime switching — Hidden Markov regimes and Heston-type stochastic volatility, estimated jointly by particle MCMC with an unscented Kalman filter for the latent volatility. |
| **[OptionPricing](https://github.com/white07S/OptionPricing)** · `Java` | A JavaFX desktop app pricing American, Bermudan and European options by Monte Carlo. Built because I wanted to hand someone a pricer they could just open. |

### Trading strategies

| Project | |
| :--- | :--- |
| **[ForexRL](https://github.com/white07S/ForexRL)** · `Python` | Deep reinforcement learning for high-volume, high-frequency FX portfolio management. |
| **[Forex-Trading](https://github.com/white07S/Forex-Trading)** · `Python` | A DQN-based high-frequency trading agent for the FX market. |
| **[ForexMeanReversion](https://github.com/white07S/ForexMeanReversion)** · `Python` | Mean reversion on EUR/USD 1-minute data via an Ornstein–Uhlenbeck process, with feature engineering, dynamic signal generation and a backtesting harness. |
| **[Forex-Fibonacci](https://github.com/white07S/Forex-Fibonacci)** · `Python` | Fibonacci retracement treated as a mathematical model, with ML-driven entry and exit formulation. |
| **[Fibonacci-Retracement](https://github.com/white07S/Fibonacci-Retracement)** · `Python` | Learned identification of retracement, support and resistance levels. |
| **[HFT-hedging](https://github.com/white07S/HFT-hedging)** · `Python` | Optimises the hedging decision at every timestep `t` under high-frequency constraints. |

---

## Elsewhere in my head

Order-book modelling and market microstructure. Post-training quantization and
getting large models to run on hardware that shouldn't really fit them. Retrieval
systems. And brain–computer interfaces, which I know far less about than the rest
of this list and would happily collaborate with someone who knows more.

<sub>`Rust` · `Python` · `C/C++` · `Java` · `PyTorch` · `Numba` · `Metal` · `Docker`</sub>

<sub>MSc Artificial Intelligence, [Poznan University of Technology](https://www.put.poznan.pl/).</sub>

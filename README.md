# Preetam Sharma

**Quantitative modelling · ML infrastructure · Retrieval systems**

Most things here started with the same irritation: the standard answer wanted
three services, a container and a rebuild step, when the problem deserved one
file.

I do quant risk and AI modelling at [UBS](https://www.ubs.com/global/en.html).
Away from that I write Rust and Python, on problems where the maths has to
survive contact with a machine. Option pricers fast enough to be worth running.
Weight quantizers that still hold at five bits. Retrieval that fits in a single
portable file.

I'd rather finish one thing that's genuinely hard than five that aren't.
Everything below is work I'd want someone to open and read properly. The rest I
retired.

---

## Open to work

I'm open to conversations about quantitative research, ML infrastructure, and
inference systems.

What gets my attention is a problem where the difficulty is real.

📫 **[sharmapreetam.uk@outlook.com](mailto:sharmapreetam.uk@outlook.com)**

---

## Selected work

### Retrieval

**[valise](https://github.com/white07S/valise)** · `Rust`

Documents, a BM25 index and compressed vectors, all inside one portable `.vls`
file. No server. No index to build. Copy it, version it, attach it to a release,
`scp` it to an air-gapped box, then open it and query it in place. Vectors are
quantized to roughly 5.5 bits per dimension, and the search sketch is derived the
moment you open the file rather than written to disk.

SQLite made this obvious for relational data thirty years ago. Retrieval never
caught up. On [crates.io](https://crates.io/crates/valise) and
[PyPI](https://pypi.org/project/valise/).

### Quantitative finance

| Project | |
| :--- | :--- |
| **[TradingPatternScanner](https://github.com/white07S/TradingPatternScanner)** · `Python` | Finds head-and-shoulders, wedges and other complex formations in raw price series. 300+ stars and 85 forks, which makes it the most-used thing I've written. |
| **[OptionPricingModels](https://github.com/white07S/OptionPricingModels)** · `Rust` | Binomial, Black–Scholes, Heston and intrinsic value, with Least Squares Monte Carlo and random-forest regression taking on the American exercise boundary. |
| **[Pricing-Models](https://github.com/white07S/Pricing-Models)** · `Python` | Option pricing on Numba, written against as few dependencies as I could get away with. Several models carry their own ML component and performance assessment. |
| **[BayesRegimeVol](https://github.com/white07S/BayesRegimeVol)** · `Python` | Bayesian nonlinear pricing under regime switching. Hidden Markov regimes and Heston-type stochastic volatility, estimated jointly by particle MCMC, with an unscented Kalman filter tracking the latent volatility. |
| **[OptionPricing](https://github.com/white07S/OptionPricing)** · `Java` | A JavaFX desktop app pricing American, Bermudan and European options by Monte Carlo. Built because I wanted to hand someone a pricer they could just open. |

### Trading strategies

| Project | |
| :--- | :--- |
| **[ForexRL](https://github.com/white07S/ForexRL)** · `Python` | Deep reinforcement learning for high-volume, high-frequency FX portfolio management. |
| **[Forex-Trading](https://github.com/white07S/Forex-Trading)** · `Python` | A DQN-based high-frequency trading agent for the FX market. |
| **[ForexMeanReversion](https://github.com/white07S/ForexMeanReversion)** · `Python` | Mean reversion on EUR/USD 1-minute data through an Ornstein–Uhlenbeck process, with feature engineering, dynamic signal generation and a backtesting harness. |
| **[Forex-Fibonacci](https://github.com/white07S/Forex-Fibonacci)** · `Python` | Fibonacci retracement treated as a mathematical model, with ML-driven entry and exit formulation. |
| **[Fibonacci-Retracement](https://github.com/white07S/Fibonacci-Retracement)** · `Python` | Learned identification of retracement, support and resistance levels. |
| **[HFT-hedging](https://github.com/white07S/HFT-hedging)** · `Python` | Optimises the hedging decision at every timestep `t` under high-frequency constraints. |

---

## What I keep circling back to

Order-book modelling and market microstructure. Post-training quantization, and
the general problem of running large models on hardware that has no business
fitting them. Retrieval systems. And brain–computer interfaces, where I know
considerably less than I'd like and would gladly work alongside someone who
knows more.

<sub>`Rust` · `Python` · `C/C++` · `Java` · `PyTorch` · `Numba` · `Metal` · `Docker`</sub>

<sub>MSc Artificial Intelligence, [Poznan University of Technology](https://www.put.poznan.pl/).</sub>

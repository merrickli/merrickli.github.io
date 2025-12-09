---
layout: archive
title: "Working Papers"
permalink: /working-papers/
author_profile: true
---

- [Multi-Horizon Test for Market Frictions](https://doi.org/10.13140/RG.2.2.25644.58246)  
  with Xiye Yang (2025), accepted by **Journal of Econometrics**.  
  • [Supplement](/assets/papers/Supple_mht.pdf) • [Code (minimac)](https://github.com/merrickli/minimac)


  **Abstract**: We test for the presence of market frictions that induce transitory deviations of observed asset prices from the underlying efficient prices. Our test is based on the joint inference of return covariances across multiple horizons. We demonstrate that a small set of horizons suffices to identify a broad spectrum of frictions, both theoretically and practically. Our method works for high- and low-frequency data under different asymptotic regimes. Extensive simulations show our method outperforms widely used state-of-the-art tests. Our empirical studies indicate that intraday transaction prices from recent years can be considered effectively friction-free at significantly higher frequencies.


  **What the test can do:**
  - Check whether intraday prices are relatively **free of microstructure noise**
  - Diagnose whether the underlying return series is **uncorrelated** or exhibits serial dependence
  - Detect persistent returns driven by large drifts or **drift bursts**
  - Outperforms modern **variance ratio** and **portmanteau tests**


  **Empirical Results**: Annual rejection rates of $\mathbb{H}_0$ (semimartingale without microstructural errors) for SPY (2014-2021) at 1% significance level:

  <div style="display: flex; justify-content: space-between; font-size: 0.85em; margin: 20px 0;">
    <div style="width: 48%;">
      $$
      \begin{array}{c|ccccc}
      \hline\hline
      \mathbf{2014} & \mathbf{1s} & \mathbf{5s} & \mathbf{10s} & \mathbf{30s} & \mathbf{60s} \\
      \hline
      \bK_0 & 99.6 & 65.1 & 36.5 & 7.9 & 7.9 \\
      \bK_1 & 99.6 & 63.9 & 35.3 & 7.9 & 5.6 \\
      \bK_2 & 100.0 & 63.1 & 34.5 & 6.3 & 4.0 \\
      \hline\hline
      \end{array}
      $$

      $$
      \begin{array}{c|ccccc}
      \hline\hline
      \mathbf{2015} & \mathbf{1s} & \mathbf{5s} & \mathbf{10s} & \mathbf{30s} & \mathbf{60s} \\
      \hline
      \bK_0 & 98.0 & 43.7 & 22.6 & 6.3 & 3.6 \\
      \bK_1 & 98.4 & 43.3 & 20.6 & 6.7 & 4.4 \\
      \bK_2 & 98.0 & 42.1 & 17.5 & 4.4 & 2.8 \\
      \hline\hline
      \end{array}
      $$

      $$
      \begin{array}{c|ccccc}
      \hline\hline
      \mathbf{2016} & \mathbf{1s} & \mathbf{5s} & \mathbf{10s} & \mathbf{30s} & \mathbf{60s} \\
      \hline
      \bK_0 & 98.4 & 52.4 & 27.8 & 9.1 & 8.3 \\
      \bK_1 & 98.0 & 54.0 & 27.4 & 8.7 & 5.6 \\
      \bK_2 & 97.6 & 53.2 & 25.8 & 7.1 & 3.2 \\
      \hline\hline
      \end{array}
      $$

      $$
      \begin{array}{c|ccccc}
      \hline\hline
      \mathbf{2017} & \mathbf{1s} & \mathbf{5s} & \mathbf{10s} & \mathbf{30s} & \mathbf{60s} \\
      \hline
      \bK_0 & 99.6 & 72.1 & 36.7 & 14.3 & 8.8 \\
      \bK_1 & 99.6 & 71.3 & 37.5 & 14.3 & 7.2 \\
      \bK_2 & 99.6 & 71.3 & 34.7 & 10.8 & 6.0 \\
      \hline\hline
      \end{array}
      $$
    </div>

    <div style="width: 48%;">
      $$
      \begin{array}{c|ccccc}
      \hline\hline
      \mathbf{2018} & \mathbf{1s} & \mathbf{5s} & \mathbf{10s} & \mathbf{30s} & \mathbf{60s} \\
      \hline
      \bK_0 & 76.5 & 25.9 & 7.6 & 4.4 & 2.4 \\
      \bK_1 & 78.5 & 25.5 & 6.8 & 2.0 & 1.6 \\
      \bK_2 & 77.7 & 23.9 & 5.2 & 0.8 & 0.4 \\
      \hline\hline
      \end{array}
      $$

      $$
      \begin{array}{c|ccccc}
      \hline\hline
      \mathbf{2019} & \mathbf{1s} & \mathbf{5s} & \mathbf{10s} & \mathbf{30s} & \mathbf{60s} \\
      \hline
      \bK_0 & 92.9 & 23.8 & 11.5 & 1.2 & 2.0 \\
      \bK_1 & 91.3 & 21.8 & 9.5 & 1.6 & 1.2 \\
      \bK_2 & 90.1 & 20.2 & 8.3 & 1.6 & 0.8 \\
      \hline\hline
      \end{array}
      $$

      $$
      \begin{array}{c|ccccc}
      \hline\hline
      \mathbf{2020} & \mathbf{1s} & \mathbf{5s} & \mathbf{10s} & \mathbf{30s} & \mathbf{60s} \\
      \hline
      \bK_0 & 71.1 & 15.4 & 4.0 & 1.6 & 0.0 \\
      \bK_1 & 72.3 & 15.8 & 4.0 & 0.8 & 0.4 \\
      \bK_2 & 71.9 & 17.0 & 3.2 & 0.4 & 0.8 \\
      \hline\hline
      \end{array}
      $$

      $$
      \begin{array}{c|ccccc}
      \hline\hline
      \mathbf{2021} & \mathbf{1s} & \mathbf{5s} & \mathbf{10s} & \mathbf{30s} & \mathbf{60s} \\
      \hline
      \bK_0 & 88.5 & 12.3 & 0.4 & 3.2 & 0.8 \\
      \bK_1 & 86.9 & 9.5 & 2.4 & 1.6 & 0.4 \\
      \bK_2 & 85.7 & 10.3 & 3.6 & 0.8 & 0.4 \\
      \hline\hline
      \end{array}
      $$
    </div>
  </div>

  **Table shows rejection rates (%) of our single-horizon ($\bK_0$), two-horizon ($\bK_1$), and four-horizon ($\bK_2$) tests across different sampling frequencies. The results demonstrate that intraday prices become effectively friction-free at higher frequencies in recent years.**
    <div style="width: 45%;">

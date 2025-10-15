---
layout: archive
title: "Working Papers"
permalink: /working-papers/
author_profile: true
---

- [Multi-Horizon Test for Market Frictions](/assets/papers/mht.pdf)  
  with Xiye Yang (2025).  
  [PDF](/assets/papers/mht.pdf) • [Supplement](/assets/papers/Supple_mht.pdf) • [Code (minimac)](https://github.com/merrickli/minimac)

  **Abstract**: We test for the presence of market frictions that induce transitory deviations of observed asset prices from the underlying efficient prices. Our test is based on the joint inference of return covariances across multiple horizons. We demonstrate that a small set of horizons suffices to identify a broad spectrum of frictions, both theoretically and practically. Our method works for high- and low-frequency data under different asymptotic regimes. Extensive simulations show our method outperforms widely used state-of-the-art tests. Our empirical studies indicate that intraday transaction prices from recent years can be considered effectively friction-free at significantly higher frequencies.
 
  **What the test can do:**
  - Check whether intraday prices are relatively **free of microstructure noise**
  - Diagnose whether the underlying return series is **uncorrelated** or exhibits serial dependence
  - Detect persistent returns driven by large drifts or **drift bursts**
  - Outperforms modern **variance ratio** and **portmanteau tests**

  **Empirical Results**: Annual rejection rates of H₀ for SPY (2014-2021) at 1% significance level:

  <div style="display: flex; justify-content: space-between; font-size: 0.8em;">
    <div style="width: 45%;">
      <table style="border-collapse: collapse; width: 100%; margin: 10px 0;">
        <tr style="border-top: 2px solid black; border-bottom: 1px solid black;">
          <th style="text-align: left; padding: 4px;"><strong>2014</strong></th>
          <th style="padding: 4px;">1s</th><th style="padding: 4px;">5s</th><th style="padding: 4px;">10s</th><th style="padding: 4px;">30s</th><th style="padding: 4px;">60s</th>
        </tr>
        <tr style="border-bottom: 1px solid black;">
          <td style="padding: 4px;">bK₀</td><td style="padding: 4px;">99.6</td><td style="padding: 4px;">65.1</td><td style="padding: 4px;">36.5</td><td style="padding: 4px;">7.9</td><td style="padding: 4px;">7.9</td>
        </tr>
        <tr>
          <td style="padding: 4px;">bK₁</td><td style="padding: 4px;">99.6</td><td style="padding: 4px;">63.9</td><td style="padding: 4px;">35.3</td><td style="padding: 4px;">7.9</td><td style="padding: 4px;">5.6</td>
        </tr>
        <tr style="border-bottom: 2px solid black;">
          <td style="padding: 4px;">bK₂</td><td style="padding: 4px;">100.0</td><td style="padding: 4px;">63.1</td><td style="padding: 4px;">34.5</td><td style="padding: 4px;">6.3</td><td style="padding: 4px;">4.0</td>
        </tr>
      </table>

      <table style="border-collapse: collapse; width: 100%; margin: 10px 0;">
        <tr style="border-top: 2px solid black; border-bottom: 1px solid black;">
          <th style="text-align: left; padding: 4px;"><strong>2015</strong></th>
          <th style="padding: 4px;">1s</th><th style="padding: 4px;">5s</th><th style="padding: 4px;">10s</th><th style="padding: 4px;">30s</th><th style="padding: 4px;">60s</th>
        </tr>
        <tr style="border-bottom: 1px solid black;">
          <td style="padding: 4px;">bK₀</td><td style="padding: 4px;">98.0</td><td style="padding: 4px;">43.7</td><td style="padding: 4px;">22.6</td><td style="padding: 4px;">6.3</td><td style="padding: 4px;">3.6</td>
        </tr>
        <tr>
          <td style="padding: 4px;">bK₁</td><td style="padding: 4px;">98.4</td><td style="padding: 4px;">43.3</td><td style="padding: 4px;">20.6</td><td style="padding: 4px;">6.7</td><td style="padding: 4px;">4.4</td>
        </tr>
        <tr style="border-bottom: 2px solid black;">
          <td style="padding: 4px;">bK₂</td><td style="padding: 4px;">98.0</td><td style="padding: 4px;">42.1</td><td style="padding: 4px;">17.5</td><td style="padding: 4px;">4.4</td><td style="padding: 4px;">2.8</td>
        </tr>
      </table>

      <table style="border-collapse: collapse; width: 100%; margin: 10px 0;">
        <tr style="border-top: 2px solid black; border-bottom: 1px solid black;">
          <th style="text-align: left; padding: 4px;"><strong>2016</strong></th>
          <th style="padding: 4px;">1s</th><th style="padding: 4px;">5s</th><th style="padding: 4px;">10s</th><th style="padding: 4px;">30s</th><th style="padding: 4px;">60s</th>
        </tr>
        <tr style="border-bottom: 1px solid black;">
          <td style="padding: 4px;">bK₀</td><td style="padding: 4px;">98.4</td><td style="padding: 4px;">52.4</td><td style="padding: 4px;">27.8</td><td style="padding: 4px;">9.1</td><td style="padding: 4px;">8.3</td>
        </tr>
        <tr>
          <td style="padding: 4px;">bK₁</td><td style="padding: 4px;">98.0</td><td style="padding: 4px;">54.0</td><td style="padding: 4px;">27.4</td><td style="padding: 4px;">8.7</td><td style="padding: 4px;">5.6</td>
        </tr>
        <tr style="border-bottom: 2px solid black;">
          <td style="padding: 4px;">bK₂</td><td style="padding: 4px;">97.6</td><td style="padding: 4px;">53.2</td><td style="padding: 4px;">25.8</td><td style="padding: 4px;">7.1</td><td style="padding: 4px;">3.2</td>
        </tr>
      </table>

      <table style="border-collapse: collapse; width: 100%; margin: 10px 0;">
        <tr style="border-top: 2px solid black; border-bottom: 1px solid black;">
          <th style="text-align: left; padding: 4px;"><strong>2017</strong></th>
          <th style="padding: 4px;">1s</th><th style="padding: 4px;">5s</th><th style="padding: 4px;">10s</th><th style="padding: 4px;">30s</th><th style="padding: 4px;">60s</th>
        </tr>
        <tr style="border-bottom: 1px solid black;">
          <td style="padding: 4px;">bK₀</td><td style="padding: 4px;">99.6</td><td style="padding: 4px;">72.1</td><td style="padding: 4px;">36.7</td><td style="padding: 4px;">14.3</td><td style="padding: 4px;">8.8</td>
        </tr>
        <tr>
          <td style="padding: 4px;">bK₁</td><td style="padding: 4px;">99.6</td><td style="padding: 4px;">71.3</td><td style="padding: 4px;">37.5</td><td style="padding: 4px;">14.3</td><td style="padding: 4px;">7.2</td>
        </tr>
        <tr style="border-bottom: 2px solid black;">
          <td style="padding: 4px;">bK₂</td><td style="padding: 4px;">99.6</td><td style="padding: 4px;">71.3</td><td style="padding: 4px;">34.7</td><td style="padding: 4px;">10.8</td><td style="padding: 4px;">6.0</td>
        </tr>
      </table>
    </div>

    <div style="width: 45%;">
      <table style="border-collapse: collapse; width: 100%; margin: 10px 0;">
        <tr style="border-top: 2px solid black; border-bottom: 1px solid black;">
          <th style="text-align: left; padding: 4px;"><strong>2018</strong></th>
          <th style="padding: 4px;">1s</th><th style="padding: 4px;">5s</th><th style="padding: 4px;">10s</th><th style="padding: 4px;">30s</th><th style="padding: 4px;">60s</th>
        </tr>
        <tr style="border-bottom: 1px solid black;">
          <td style="padding: 4px;">bK₀</td><td style="padding: 4px;">76.5</td><td style="padding: 4px;">25.9</td><td style="padding: 4px;">7.6</td><td style="padding: 4px;">4.4</td><td style="padding: 4px;">2.4</td>
        </tr>
        <tr>
          <td style="padding: 4px;">bK₁</td><td style="padding: 4px;">78.5</td><td style="padding: 4px;">25.5</td><td style="padding: 4px;">6.8</td><td style="padding: 4px;">2.0</td><td style="padding: 4px;">1.6</td>
        </tr>
        <tr style="border-bottom: 2px solid black;">
          <td style="padding: 4px;">bK₂</td><td style="padding: 4px;">77.7</td><td style="padding: 4px;">23.9</td><td style="padding: 4px;">5.2</td><td style="padding: 4px;">0.8</td><td style="padding: 4px;">0.4</td>
        </tr>
      </table>

      <table style="border-collapse: collapse; width: 100%; margin: 10px 0;">
        <tr style="border-top: 2px solid black; border-bottom: 1px solid black;">
          <th style="text-align: left; padding: 4px;"><strong>2019</strong></th>
          <th style="padding: 4px;">1s</th><th style="padding: 4px;">5s</th><th style="padding: 4px;">10s</th><th style="padding: 4px;">30s</th><th style="padding: 4px;">60s</th>
        </tr>
        <tr style="border-bottom: 1px solid black;">
          <td style="padding: 4px;">bK₀</td><td style="padding: 4px;">92.9</td><td style="padding: 4px;">23.8</td><td style="padding: 4px;">11.5</td><td style="padding: 4px;">1.2</td><td style="padding: 4px;">2.0</td>
        </tr>
        <tr>
          <td style="padding: 4px;">bK₁</td><td style="padding: 4px;">91.3</td><td style="padding: 4px;">21.8</td><td style="padding: 4px;">9.5</td><td style="padding: 4px;">1.6</td><td style="padding: 4px;">1.2</td>
        </tr>
        <tr style="border-bottom: 2px solid black;">
          <td style="padding: 4px;">bK₂</td><td style="padding: 4px;">90.1</td><td style="padding: 4px;">20.2</td><td style="padding: 4px;">8.3</td><td style="padding: 4px;">1.6</td><td style="padding: 4px;">0.8</td>
        </tr>
      </table>

      <table style="border-collapse: collapse; width: 100%; margin: 10px 0;">
        <tr style="border-top: 2px solid black; border-bottom: 1px solid black;">
          <th style="text-align: left; padding: 4px;"><strong>2020</strong></th>
          <th style="padding: 4px;">1s</th><th style="padding: 4px;">5s</th><th style="padding: 4px;">10s</th><th style="padding: 4px;">30s</th><th style="padding: 4px;">60s</th>
        </tr>
        <tr style="border-bottom: 1px solid black;">
          <td style="padding: 4px;">bK₀</td><td style="padding: 4px;">71.1</td><td style="padding: 4px;">15.4</td><td style="padding: 4px;">4.0</td><td style="padding: 4px;">1.6</td><td style="padding: 4px;">0.0</td>
        </tr>
        <tr>
          <td style="padding: 4px;">bK₁</td><td style="padding: 4px;">72.3</td><td style="padding: 4px;">15.8</td><td style="padding: 4px;">4.0</td><td style="padding: 4px;">0.8</td><td style="padding: 4px;">0.4</td>
        </tr>
        <tr style="border-bottom: 2px solid black;">
          <td style="padding: 4px;">bK₂</td><td style="padding: 4px;">71.9</td><td style="padding: 4px;">17.0</td><td style="padding: 4px;">3.2</td><td style="padding: 4px;">0.4</td><td style="padding: 4px;">0.8</td>
        </tr>
      </table>

      <table style="border-collapse: collapse; width: 100%; margin: 10px 0;">
        <tr style="border-top: 2px solid black; border-bottom: 1px solid black;">
          <th style="text-align: left; padding: 4px;"><strong>2021</strong></th>
          <th style="padding: 4px;">1s</th><th style="padding: 4px;">5s</th><th style="padding: 4px;">10s</th><th style="padding: 4px;">30s</th><th style="padding: 4px;">60s</th>
        </tr>
        <tr style="border-bottom: 1px solid black;">
          <td style="padding: 4px;">bK₀</td><td style="padding: 4px;">88.5</td><td style="padding: 4px;">12.3</td><td style="padding: 4px;">0.4</td><td style="padding: 4px;">3.2</td><td style="padding: 4px;">0.8</td>
        </tr>
        <tr>
          <td style="padding: 4px;">bK₁</td><td style="padding: 4px;">86.9</td><td style="padding: 4px;">9.5</td><td style="padding: 4px;">2.4</td><td style="padding: 4px;">1.6</td><td style="padding: 4px;">0.4</td>
        </tr>
        <tr style="border-bottom: 2px solid black;">
          <td style="padding: 4px;">bK₂</td><td style="padding: 4px;">85.7</td><td style="padding: 4px;">10.3</td><td style="padding: 4px;">3.6</td><td style="padding: 4px;">0.8</td><td style="padding: 4px;">0.4</td>
        </tr>
      </table>
    </div>
  </div>

  *Table shows rejection rates (%) of our bK₀, bK₁, bK₂ multi-horizon tests across different sampling frequencies. The results demonstrate that intraday prices become effectively friction-free at higher frequencies in recent years.*
---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
- [Multi-Horizon Test for Market Frictions](https://doi.org/10.13140/RG.2.2.25644.58246), with X. Yang (2025). **Journal of Econometrics**, forthcoming.
• [Supplement](/assets/papers/Supple_mht.pdf) • [Code](https://github.com/merrickli/minimac) • [Highlights](#mht-highlights)

  <!-- markdownlint-disable MD033 -->
  <details id="mht-highlights">
    <summary>Highlights (click to expand)</summary>

    {% capture mht_highlight_md %}
    {% include mht_highlight_content.md %}
    {% endcapture %}
    {{ mht_highlight_md | markdownify }}
  </details>

  <script>
    (function () {
      function openMhtHighlightsIfNeeded() {
        if (window.location.hash === "#mht-highlights") {
          var details = document.getElementById("mht-highlights");
          if (details && details.tagName && details.tagName.toLowerCase() === "details") {
            details.open = true;
          }
        }
      }

      window.addEventListener("hashchange", openMhtHighlightsIfNeeded);
      window.addEventListener("DOMContentLoaded", openMhtHighlightsIfNeeded);
    })();
  </script>
  <!-- markdownlint-enable MD033 -->
  
- [Robust estimation of integrated and spot volatility](https://doi.org/10.1016/j.jeconom.2023.105614), with O. Linton (2023). **Journal of Econometrics**, 105614.

- [A ReMeDI for Microstructure Noise](https://doi.org/10.3982/ECTA17505), with O. Linton (2022). **Econometrica**, 90(1), 367–389.

- [Dependent microstructure noise and integrated volatility estimation from high-frequency data](https://doi.org/10.1016/j.jeconom.2019.10.004), with R. J. A. Laeven, M. H. Vellekoop (2020). **Journal of Econometrics**, 215(2), 536–558.

- [A barrier-based smoothing proximal point algorithm for NCPs over closed convex cones](https://epubs.siam.org/doi/10.1137/12087565X0), with C. B. Chua (2013). **SIAM Journal on Optimization**, 23(2), 745-769.

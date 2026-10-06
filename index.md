---
title: 'CONFIRMS — Causal Inference in RCTs'
filename: links.md
layout: base
--- 

Use of causal inference methods commonly used in non-interventional studies to estimate treatment effects in clinical trials. EMA funded research project of the CONFIRMS consortium.

## Papers

* Jespersen, L., Klinglmüller, F., Fellinger, T., Hendrickx, N., Starke, P., Urach, S., Centanni, M., Geroldinger, A., Hohberg, M., Huang, Z., Schneider, L., Schulz, M., Benda, N., König, F., Karlsson, M., Friede, T., Hooker, A., Posch, M., Ristl, R., "Causal inference methods for intercurrent events in randomised clinical trials: a simulation study" [Upcoming Paper]

## Study Protocols and Reports

* Simulation Study Protocol and Simulation Study Report in the [EMA RWD Catalog](https://catalogues.ema.europa.eu/node/4623/study-documents)

## R-packages

* CI.RCT.Sim: Package to Facilitate a Simulation Study on Causal Inference Methods in RCTs. [https://ci-rct-sim.github.io/CI.RCT.Sim/](https://ci-rct-sim.github.io/CI.RCT.Sim/)

## Share this page

![QR-code](qrcode.png)<br />
[https://ci-rct-sim.github.io/CI.RCT.links/](https://ci-rct-sim.github.io/CI.RCT.links/)

<button id="sharebutton" style="display: none;">Share 🔗</button>

<script>
      let shareData = {
        title: 'Causal Inference in RCTs',
        text: 'Use of causal inference methods commonly used in non-interventional studies to estimate treatment effects in clinical trials. EMA funded research project of the CONFIRMS consortium.',
        url: 'https://ci-rct-sim.github.io/CI.RCT.links/',
      };

      const btn = document.querySelector('#sharebutton');
      
      if(navigator.canShare && navigator.canShare(shareData)){
        btn.style.display="inline";
        btn.addEventListener('click', () => {
            navigator.share(shareData);
        })
      }
    </script>

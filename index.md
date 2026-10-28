---
title: 'CONFIRMS — Causal Inference in RCTs'
filename: links.md
layout: base
--- 

Reseach Project *"Use of causal inference methods commonly used in non-interventional studies to estimate treatment effects in clinical trials"*. Funded by EMA under EMA/2020/46/TDA, Lot 3 - ROC36, awarded to and conducted by the CONFIRMS consortium. (Administrative Details in the [EMA RWD Catalog](https://catalogues.ema.europa.eu/node/4623/administrative-details))

## Papers

* Jespersen, L., Klinglmüller, F., Fellinger, T., Hendrickx, N., Starke, P., Urach, S., Centanni, M., Geroldinger, A., Hohberg, M., Huang, Z., Schneider, L., Schulz, M., Benda, N., König, F., Karlsson, M., Friede, T., Hooker, A., Posch, M., Ristl, R., "Causal inference methods for intercurrent events in randomised clinical trials: a simulation study" [Upcoming Paper]

## Conference Talks

### 8th International Symposium on Biopharmaceutical Statistics (ISBS), October 2026, Madrid

* Susanne Urach: *Review of causal inference methods for randomised trials in European Public Assessment Reports*
* Florian Klinglmüller: *Estimating principal-stratum vaccine efficacy under incomplete regimen completion* ([slides](documents/2026_ISBS_Klinglmueller_handling_rescue_medication_in_diabetes_trials.pdf))
* Niels Hendrickx: *Treatment discontinuation and while-on-treatment estimation*
* Robin Ristl: *Treatment switching in randomised trials with time-to-event outcomes – hypothetical estimand strategy via causal inference*
* Louise Jespersen: *Causal inference methods for estimating treatment effects in the presence of rescue medication and treatment* ([slides](documents/2026_ISBS_Jespersen_principal_stratum_vaccine_efficace_with_incomplete_vaccination.pdf))
* Paula Starke: *Causal inference methods for specific estimands in the context of randomised trials – scoping review*
* Tobias Fellinger: *Simulation studies in regulatory science* ([slides](documents/2026_ISBS_Fellinger_simulation_studies_in_regulatory_science.pdf))

## Study Protocols and Reports

* Simulation Study Protocol and Simulation Study Report in the [EMA RWD Catalog](https://catalogues.ema.europa.eu/node/4623/study-documents)

## R-package

* CI.RCT.Sim: Package to Facilitate a Simulation Study on Causal Inference Methods in RCTs. [https://ci-rct-sim.github.io/CI.RCT.Sim/](https://ci-rct-sim.github.io/CI.RCT.Sim/)

## CONFIRMS Consortium

CONFIRMS: **CON**sortium **F**or **I**nnovation in **R**egulatory **M**edical **S**tatistics

* Center for Medical Data Science (CeDAS), Medical University of Vienna (MUW), Austria
* Department of Medical Statistics, University Medical Center Göttingen (UMG), Germany
* Pharmacometrics Research Group, Uppsala University (UU), Sweden
* Austrian Medicines and Medical Devices Agency (MEA), A Business Division of the Austrian Agency for Health and Food Safety (AGES), Austria

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

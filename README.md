
<center>

# $\text{Causal Structure Analysis For Anomaly Detection In Spacecraft Telemetry Data}$
</center>

_This repository implements a hybrid model combining Continuous-Time Bayesian Networks (CTBNs), Dynamic Bayesian Networks (DBNs), and Factor Graphs for telemetry anomaly detection in spacecraft systems on ESA-Mission1 Dataset._

<center>


[![ArXiv](https://img.shields.io/badge/ArXiv-00A1D6?logo=arxiv&logoColor=white)](https://arxiv.org/) [![HuggingFace](https://img.shields.io/badge/HuggingFace-F9AB00?logo=huggingface&logoColor=white)](https://huggingface.co/) [![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?logo=kaggle&logoColor=white)](https://kaggle.com/) [![ESA](https://img.shields.io/badge/ESA-Data-003087?logo=satellite&logoColor=white)](https://esa.int/)
</center>


<!-- ![image](https://github.com/user-attachments/assets/ba0ce6e2-145e-44f4-9501-f0f70e43ea9d) -->
<!-- ![image](https://github.com/user-attachments/assets/40d0df5a-c678-42b8-af9f-6efe6d194335) -->

## $\text{●•Authors}$

<center>
<table align="center" style="width: 100%; text-align: center;">
  <tr>
    <td align="center"><img src="https://github.com/user-attachments/assets/40d0df5a-c678-42b8-af9f-6efe6d194335" alt="Baimam Boukar Jean Jacques" width="150" height="150"></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/ba0ce6e2-145e-44f4-9501-f0f70e43ea9d" alt="Kipngeno Koech" width="150" height="150" style="border-radius: 10px;"></td>
  </tr>
  <tr>
    <td>$\text{Baimam Boukar Jean Jacques}$</td>
    <td>$\text{Kipngeno Koech}$</td>
  </tr>
  <tr>
    <td>Carnegie Mellon University Africa</td>
    <td>Carnegie Mellon University Africa</td>
  </tr>
  <tr>
    <td>
      <stong>bbaimamb@andrew.cmu.edu</stong>
    </td>
    <td>bkoech@andrew.cmu.edu</td>
  </tr>
  <tr>
    <td>
      <a href="https://linkedin.com/in/baimamboukar"><img src="https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
      <a href="https://github.com/baimamboukar"><img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white" alt="GitHub"></a>
      <a href="https://kaggle.com/baimamboukar"><img src="https://img.shields.io/badge/Kaggle-20BEFF?logo=kaggle&logoColor=white" alt="Kaggle"></a>
    </td>
    <td>
      <a href="https://linkedin.com/in/kipngenokoech"><img src="https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
      <a href="https://github.com/kkipngeokoech"><img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white" alt="GitHub"></a>
      <a href="https://kaggle.com/kipngenokoech"><img src="https://img.shields.io/badge/Kaggle-20BEFF?logo=kaggle&logoColor=white" alt="Kaggle"></a>
    </td>
  </tr>
</table>
</center>

## ●• $\text{Dataset Description}$

The analysis used telemetry data from the European Space Agency's ESA-Mission1. It has over 14 million records collected across several years. This continuous multivariate time series includes 87 mission-critical channels, annotated for anomalies and rare events through iterative manual and algorithmic refinement of flight control reports. The dataset targets two event categories

●• Anomalies $\to$ Unexpected behaviors or system failures <br>
●• Nominal Events $\to$ unusual but expected operational patterns. 

The data is divided into a training set spanning 14 years of operations and a test set covering a 6-month unpublished segment.

The dataset has 87 telemetry channels, 58 target channels monitored for anomalies, 18 auxiliary environmental variables, and 11 telecommand channels that are binary control commands, prefixed with `telecommand_`

## ●• $\text{Methodology}$

<p align="left">
  <a>
    <img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,github,markdown,latex&perline=19" alt="Skill Icons">
  </a>
  
## ●• $\text{Reproduction Steps}$

## ●• $\text{Cite This Paper}$

```bibtex
@software{bbaimamb_bkoech_2025,
author = {Baimam Boukar Jean Jacques and Kipngeno Koech},
month = apr,
title = {{Causal Structure Analysis for Telemetry Anomaly Detection in Spacecraft Systems}},
url = {https://github.com/baimamboukar/causual-structure-discovery-spacecraft-telemetry},
version = {1.0},
year = {2025}
}
```
<h1 style="color: cyan; font-family:Monaco, monospace; text-align: center;">
Causal Structure Analysis for Telemetry Anomaly
Detection in Spacecraft Systems<br>
</h1>

_This repository implements a hybrid model combining Continuous-Time Bayesian Networks (CTBNs), Dynamic Bayesian Networks (DBNs), and Factor Graphs for telemetry anomaly detection in spacecraft systems, developed for ESA-Mission1_

<h2 style="color: cyan; font-family:Monaco, monospace">●•Authors</h1>

<center>
<table align="center" style="width: 100%; text-align: center;">
  <tr>
    <td><img src="" alt="Baimam Boukar Jean Jacques" width="150" height="150"></td>
    <td><img src="https://avatars.githubusercontent.com/u/84391547?v=4" alt="Kipngeno Koech" width="150" height="150" style="border-radius: 10px;"></td>
  </tr>
  <tr>
    <td>$Baimam Boukar Jean Jacques$</td>
    <td>Kipngeno Koech</td>
  </tr>
  <tr>
    <td>Carnegie Mellon University Africa</td>
    <td>Carnegie Mellon University Africa</td>
  </tr>
  <tr>
    <td>bbaimamb@andrew.cmu.edu</td>
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

<h2 style="color: cyan; font-family:Monaco, monospace">●•Dataset Description</h2>

The analysis used telemetry data from the European Space Agency's ESA-Mission1. It has over 14 million records collected across several years. This continuous multivariate time series includes 87 mission-critical channels, annotated for anomalies and rare events through iterative manual and algorithmic refinement of flight control reports. The dataset targets two event categories

●• Anomalies $\to$ Unexpected behaviors or system failures
●• Nominal Events $\to$ unusual but expected operational patterns. 

The data is divided into a training set spanning 14 years of operations and a test set covering a 6-month unpublished segment.

The dataset has 87 telemetry channels, 58 target channels monitored for anomalies, 18 auxiliary environmental variables, and 11 telecommand channels that are binary control commands, prefixed with `telecommand_`

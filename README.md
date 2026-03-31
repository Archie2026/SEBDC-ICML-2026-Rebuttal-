# SEBDC: Structured Exploration with Behavior Density Constraints for Offline-to-Online Reinforcement Learning (ICML 2026 Rebuttal)
Table A. Comparison of actual training times for Agents=1, Agents=2, Agents=3, and the TD3 baseline in the `walker2d-random-v2` environment, using a single NVIDIA 3090 GPU. For further details, please refer to Rebuttal R1-5.

---

Table B. D4RL normalized scores on MuJoCo locomotion control tasks, after online fine-tuning, averaged over five random seeds. All methods first perform 1M steps of offline pretraining, followed by 300k steps of online fine-tuning. Unless otherwise specified, all datasets are the v2 versions.

<p align="center">
  <img src="./images/Table-2.png" alt="Table B" width="50%">
</p>

---

Figure A. PCA visualization of perturbation vectors at 100K and 300K online steps in the `halfcheetah-random-v2` environment. For further details, please refer to Rebuttal R1-1.

<p align="center">
  <img src="./images/Figure-1-1.png" alt="Figure A" width="70%">
</p>

---
Figure B. The impact of varying numbers of agents on SEBDC performance in the `walker2d-medium-replay-v2` and `halfcheetah-medium-v2` environments. For further details, please refer to Rebuttal R1-3.

<p align="center">
  <img src="./images/Figure-2.png" alt="Figure B" width="70%">
</p>

---

Figure C. The impact of final Gaussian noise and the matched Gaussian baseline. Final Gaussian noise is removed (`w/o FG`), and the matched Gaussian is used to replace structured perturbations (`w/ MG`).

<p align="center">
  <img src="./images/Figure-3.png" alt="Figure C" width="70%">
</p>

---

Figure D. Performance comparison between SEBDC and WSRL on the D4RL MuJoCo benchmark.

<p align="center">
  <img src="./images/Figure-4.png" alt="Figure D" width="80%">
</p>

---

Figure E. Comparison of the `4:3:3` and `8:1:1` data splitting strategies.

<p align="center">
  <img src="./images/Figure-5.png" alt="Figure E" width="70%">
</p>

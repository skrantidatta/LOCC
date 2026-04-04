# LoCC: Detection and Localization of Lip-Syncing Deepfakes via Counterfactual Frame Consistency
Soumyya Kanti Datta, Shan Jia, Siwei Lyu

Accepted by ICME 2026


## Abstract
Lip-syncing deepfakes are among the most challenging forms of manipulated media because their artifacts are localized almost exclusively to the mouth region and evolve
dynamically over time. Detecting such deepfakes requires precise temporal and spatial modeling of lip motion.  In this paper, we propose LoCC, a novel detection framework that performs fine-grained detection and localization of lip-syncing deepfakes at both segment and frame levels. Unlike prior approaches that analyze videos holistically, our method evaluates whether each frame aligns with a counterfactual estimate generated from its temporal neighbors. Real videos exhibit strong and stable consistency, whereas lip-sync deepfakes introduce localized inconsistencies.  Following a teacher–student learning paradigm, our model effectively captures these frame-level discrepancies and achieves superior performance over state-of-the-art methods on multiple benchmark lip-syncing deepfake datasets, including  LAV-DF, AVDF1M, FakeAVCeleb, and KODF, and generalizes well across compression levels and datasets.

<img src='./Images/LIPINC+MSTIE_main.png' width=900>

## Code will be available soon



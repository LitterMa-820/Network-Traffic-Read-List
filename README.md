# Network Traffic Read List
This repository primarily focuses on network traffic detection methods (including classification, detection, and fingerprinting) and provides an overview of relevant code and papers.

--------------------------------------------------------------------------------------
 :heavy_exclamation_mark:
 
 :running: **We will keep updating it.** :running:    
--------------------------------------------------------------------------------------

------
## Content:

1. [Network Traffic Classification](#NTC)
2. [Network Intrusion Detection](#NID)
3. [Related Network Traffic Measurement and Datasets](#related)
4. [The Network traffic dataset download](#data)
5. [Evaluation Metrics](#eval)
6. [Comparison with state-of-the-arts](#leaderboard)

<a name="NTC"></a> 
# Network Traffic Classification <a id="Network Traffic Classification" class="anchor" href="Network Traffic Classification" aria-hidden="true"><span class="octicon octicon-link"></span></a>    

## 2026      
**No.** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-  | :-: 
:triangular_flag_on_post: 01 | **ICASSP** | WaveFormer: Cross-Modal Fusion with Robust Multi-View Flow Representation for Encrypted Traffic Classification | [Paper](https://ieeexplore.ieee.org/document/11461639/) 
:triangular_flag_on_post: 02 | **IoT-J** | NetTTT: Online Self-Adaptation Inference via Test-Time Training for Encrypted Traffic Classification | [Paper](https://ieeexplore.ieee.org/document/11346491/) 
:triangular_flag_on_post: 03 | **TDSC** | Ultimate Encrypted Traffic Feature Engineering: HTTPS Encrypted Traffic Classification Using Restored Application Data Unit Length | [Paper](https://ieeexplore.ieee.org/document/11184470/) 
:triangular_flag_on_post: 04 | **TIFS** | DQSA: Dynamic Quantized Self-Attention for Multi-Task Encrypted Network Traffic Classification | [Paper](https://ieeexplore.ieee.org/document/11311538/) 
:triangular_flag_on_post: 05 | **TIFS** | End-to-End Open-Set Semi-Supervised Learning for Fine-Grained Encrypted Traffic Classification | [Paper](https://ieeexplore.ieee.org/document/11347052/) 
:triangular_flag_on_post: 06 | **TIFS** | EO-EPTC: End-to-End Original Traffic-Based Encrypted Proxy Traffic Classification Framework | [Paper](https://ieeexplore.ieee.org/document/11310800/) 
:triangular_flag_on_post: 07 | **TIFS** | MT-DEGCL: Multi-Task Encrypted Traffic Classification With Dual Embedding and Graph Contrastive Learning | [Paper](https://ieeexplore.ieee.org/document/11394812/) 
:triangular_flag_on_post: 08 | **TON** | MUFFIN: A Meta-Knowledge Decoupling-Based Approach to Few-Shot IoT Traffic Classification | [Paper](https://ieeexplore.ieee.org/document/11131505/) 
:triangular_flag_on_post: 09 | **TON** | When Pre-Training Meets Contrast Learning: Few-Shot Encrypted Traffic Classification With Novelty Detection | [Paper](https://ieeexplore.ieee.org/document/11435484/) 

## 2025      
**No.** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-  | :-: 
:triangular_flag_on_post: 01 | **AAAI** | Revolutionizing Encrypted Traffic Classification with MH-Net: A Multi-View Heterogeneous Graph Model | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/32091/34246)/[Code](https://github.com/ViktorAxelsen/MH-Net) 
:triangular_flag_on_post: 02 | **CCS** | MM4flow: A Pre-trained Multi-modal Model for Versatile Network Traffic Analysis | [Paper](https://dl.acm.org/doi/10.1145/3719027.3744804) 
:triangular_flag_on_post: 03 | **CCS** | Training Robust Classifiers for Classifying Encrypted Traffic under Dynamic Network Conditions | [Paper](https://dl.acm.org/doi/10.1145/3719027.3765073) 
:triangular_flag_on_post: 04 | **Computer Networks** | BTG-RF: Recognizing Douyin payment behaviors based on behavioral traffic graph analysis | [Paper](https://linkinghub.elsevier.com/retrieve/pii/S1389128625003524) 
:triangular_flag_on_post: 05 | **Computer Networks** | EAPT: An encrypted traffic classification model via adversarial pre-trained transformers | [Paper](https://linkinghub.elsevier.com/retrieve/pii/S1389128624008053) 
:triangular_flag_on_post: 06 | **Computers & Security** | A graph representation framework for encrypted network traffic classification | [Paper](https://linkinghub.elsevier.com/retrieve/pii/S0167404824004395) 
:triangular_flag_on_post: 07 | **Computers & Security** | Hierarchical Perception for Encrypted Traffic Classification via Class Incremental Learning | [Paper](https://linkinghub.elsevier.com/retrieve/pii/S0167404824005005) 
:triangular_flag_on_post: 08 | **INFOCOM** | FlowMiner: A Powerful Model Based on Flow Correlation Mining for Encrypted Traffic Classification | [Paper](https://ieeexplore.ieee.org/document/11044724/) 
:triangular_flag_on_post: 09 | **IoT-J** | A Deep-Learning-Based Traffic Classification Method for 5G Aerial Computing Networks | [Paper](https://ieeexplore.ieee.org/document/10844867/) 
:triangular_flag_on_post: 10 | **JNCA** | SAT-Net: A staggered attention network using graph neural networks for encrypted traffic classification | [Paper](https://linkinghub.elsevier.com/retrieve/pii/S1084804524002467) 
:triangular_flag_on_post: 11 | **SIGCOMM** | The Sweet Danger of Sugar: Debunking Representation Learning for Encrypted Traffic Classification | [Paper](https://dl.acm.org/doi/10.1145/3718958.3750498) 
:triangular_flag_on_post: 12 | **TIFS** | FG-SAT: Efficient Flow Graph for Encrypted Traffic Classification Under Environment Shifts | [Paper](https://ieeexplore.ieee.org/document/11007150/) 
:triangular_flag_on_post: 13 | **TIFS** | Reliable Open-Set Network Traffic Classification | [Paper](https://ieeexplore.ieee.org/document/10900396/) 
:triangular_flag_on_post: 14 | **TIFS** | Respond to Change With Constancy: Instruction-Tuning With LLM for Non-I.I.D. Network Traffic Classification | [Paper](https://ieeexplore.ieee.org/document/11018090/) 
:triangular_flag_on_post: 15 | **TNSE** | DFE: Deep Flow Embedding for Robust Network Traffic Classification | [Paper](https://ieeexplore.ieee.org/document/10856394/) 
:triangular_flag_on_post: 16 | **TON** | High Precision and Efficient Anonymous Traffic Classification in the Real-World | [Paper](https://ieeexplore.ieee.org/document/10818994/) 
:triangular_flag_on_post: 17 | **arXiv** | SoK: Decoding the Enigma of Encrypted Network Traffic Classifiers | [Paper](http://arxiv.org/abs/2503.20093) 

## 2024      
**No.** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-  | :-: 
:triangular_flag_on_post: 01 | **NOMS** | Encrypted Traffic Classification at Line Rate in Programmable Switches with Machine Learning | [Paper](https://ieeexplore.ieee.org/document/10575394/) 
:triangular_flag_on_post: 02 | **TON** | A Novel Self-Supervised Framework Based on Masked Autoencoder for Traffic Classification | [Paper](https://ieeexplore.ieee.org/abstract/document/10380504/)/[Code](https://github.com/NSSL-SJTU/YaTC) 

## 2023      
**No.** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-  | :-: 
:triangular_flag_on_post: 01 | **AAAI** | Yet Another Traffic Classifier: A Masked Autoencoder Based Traffic Transformer with Multi-Level Flow Representation | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/25674)/[Code](https://github.com/NSSL-SJTU/YaTC) 
:triangular_flag_on_post: 02 | **S&P** | Robust Multi-tab Website Fingerprinting Attacks in the Wild | [Paper](https://ieeexplore.ieee.org/document/10179464/)/[Code](https://github.com/Xinhao-Deng/Multitab-WF-Datasets) 
:triangular_flag_on_post: 03 | **WWW** | TFE-GNN: A Temporal Fusion Encoder Using Graph Neural Networks for Fine-grained Encrypted Traffic Classification | [Paper](https://dl.acm.org/doi/10.1145/3543507.3583227) 
:triangular_flag_on_post: 04 | **arXiv** | Facing Unknown: Open-World Encrypted Traffic Classification Based on Contrastive Pre-Training | [Paper](http://arxiv.org/abs/2308.16861) 
:triangular_flag_on_post: 05 | **arXiv** | Many or Few Samples? Comparing Transfer, Contrastive and Meta-Learning in Encrypted Traffic Classification | [Paper](http://arxiv.org/abs/2305.12432) 

## Unknown Year      
**No.** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-  | :-: 
:triangular_flag_on_post: 01 | **—** | Enhancing Website Fingerprinting Attacks against Traffic Drift | — 
:triangular_flag_on_post: 02 | **—** | MIETT: Multi-Instance Encrypted Traffic Transformer for Encrypted Traffic Classification | —


<a name="NID"></a>
# Network Intrusion Detection <a id="Network Intrusion Detection" class="anchor" href="Network Intrusion Detection" aria-hidden="true"><span class="octicon octicon-link"></span></a> 

## 2026      
**No.** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-  | :-: 
:triangular_flag_on_post: 01 | **TIFS** | Contextual Masking Distillation for Network Traffic Anomaly Detection | [Paper](https://ieeexplore.ieee.org/document/11358423/) 

## 2025      
**No.** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-  | :-: 
:triangular_flag_on_post: 01 | **CCS** | Training with Only 1.0 ‰ Samples: Malicious Traffic Detection via Cross-Modality Feature Fusion | [Paper](https://dl.acm.org/doi/10.1145/3719027.3765143) 
:triangular_flag_on_post: 02 | **FGCS** | WFE-Tab: Overcoming limitations of TabPFN in IIoT-MEC environments with a weighted fusion ensemble-TabPFN model for improved IDS performance | — 
:triangular_flag_on_post: 03 | **KDD** | Wedjat: Detecting Sophisticated Evasion Attacks via Real-time Causal Analysis | [Paper](https://dl.acm.org/doi/10.1145/3690624.3709218) 
:triangular_flag_on_post: 04 | **NDSS** | MineShark: Cryptomining Traffic Detection at Scale | [Paper](https://www.ndss-symposium.org/wp-content/uploads/2025-402-paper.pdf) 
:triangular_flag_on_post: 05 | **TIFS** | Malware Traffic Classification via Expandable Class Incremental Learning With Architecture Search | [Paper](https://ieeexplore.ieee.org/document/11030736/) 
:triangular_flag_on_post: 06 | **WWW** | Helios: Learning and Adaptation of Matching Rules for Continual In-Network Malicious Traffic Detection | [Paper](https://dl.acm.org/doi/pdf/10.1145/3696410.3714742)/[Code](https://github.com/sznnzs/Helios) 
:triangular_flag_on_post: 07 | **arXiv** | Hierarchical Local-Global Feature Learning for Few-shot Malicious Traffic Detection | [Paper](http://arxiv.org/abs/2504.03742) 

## 2024      
**No.** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-  | :-: 
:triangular_flag_on_post: 01 | **CCS** | Detecting Tunneled Flooding Traffic via Deep Semantic Analysis of Packet Length Patterns | [Paper](https://dl.acm.org/doi/10.1145/3658644.3670353) 
:triangular_flag_on_post: 02 | **TIFS** | Enhanced Few-Shot Malware Traffic Classification via Integrating Knowledge Transfer With Neural Architecture Search | [Paper](https://ieeexplore.ieee.org/document/10517987/) 
:triangular_flag_on_post: 03 | **TON** | Flow Interaction Graph Analysis: Unknown Encrypted Malicious Traffic Detection | [Paper](https://ieeexplore.ieee.org/document/10474390/) 

## 2023      
**No.** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-  | :-: 
:triangular_flag_on_post: 01 | **CCS** | Point Cloud Analysis for ML-Based Malicious Traffic Detection: Reducing Majorities of False Positive Alarms | [Paper](https://dl.acm.org/doi/10.1145/3576915.3616631) 
:triangular_flag_on_post: 02 | **IoT-J** | A Deep Subdomain Adaptation Network With Attention Mechanism for Malware Variant Traffic Identification at an IoT Edge Gateway | [Paper](https://ieeexplore.ieee.org/document/9738802/?arnumber=9738802) 

## Unknown Year      
**No.** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-  | :-: 
:triangular_flag_on_post: 01 | **—** | TriFusion-IDS: A Multimodal Graph-Tabular-Text Contrastive Framework for Cross-Dataset Intrusion Detection | —


<a name="related"></a>
# Related Network Traffic Measurement and Datasets <a id="Related Network Traffic Measurement and Datasets" class="anchor" href="Related Network Traffic Measurement and Datasets" aria-hidden="true"><span class="octicon octicon-link"></span></a> 

## 2025      
**No.** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-  | :-: 
:triangular_flag_on_post: 01 | **CSUR** | Deep Learning on Network Traffic Prediction: Recent Advances, Analysis, and Future Directions | [Paper](https://dl.acm.org/doi/10.1145/3703447) 
:triangular_flag_on_post: 02 | **IEEE Data Descriptions** | Descriptor: UNSW IoT Traffic Data With Packets, Flows, and Protocols (UNSW-IoTraffic) | [Paper](https://ieeexplore.ieee.org/document/11137365/) 

## 2024      
**No.** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-  | :-: 
:triangular_flag_on_post: 01 | **IMC** | ReACKed QUICer: Measuring the Performance of Instant Acknowledgments in QUIC Handshakes | [Paper](https://dl.acm.org/doi/10.1145/3646547.3689022) 

## Unknown Year      
**No.** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-  | :-: 
:triangular_flag_on_post: 01 | **—** | Exposing and Circumventing SNI-based QUIC Censorship of the Great Firewall of China | —


<a name="data"></a>  
# The Network traffic dataset download    <a id="The Network traffic dataset download" class="anchor" href="The Network traffic dataset download" aria-hidden="true"><span class="octicon octicon-link"></span></a> 
* CICIIOT25 datasets [download1](xx.xxx).
* UNSW-IoTraffic: Descriptor: UNSW IoT Traffic Data With Packets, Flows, and Protocols [Paper](https://ieeexplore.ieee.org/document/11137365/).


<a name="eval"></a>
# Evaluation Metrics  <a id="Evaluation Metrics" class="anchor" href="Evaluation Metrics" aria-hidden="true"><span class="octicon octicon-link"></span></a> 
* Network traffic classification.      
This link near all evaluation metrics for Network traffic classification including xxx.
You can found in [here](xxx.xx).        
 

<a name="leaderboard"></a>
# Comparison with state-of-the-arts  <a id="Comparison with state-of-the-arts" class="anchor" href="Comparison with state-of-the-arts" aria-hidden="true"><span class="octicon octicon-link"></span></a> 
* [Here](https://xxx.xxx) includes the performance comparison of almost all Network traffic classification algorithms. 



### Conference Deadlines
[Realted Networking and Measurement Conference deadline](https://noise-lab.net/networking-deadlines/)     
[Realted CCF Conference deadline](https://ccfddl.com)     
[Realted AI Conference deadline](https://aideadlin.es/?sub=ML,CV,NLP,RO,SP,DM)     
[Realted AI Conference Accepted Rate](https://github.com/lixin4ever/Conference-Acceptance-Rate)


### Auxiliary / Excluded from Core Traffic Sections
The following CSV entries were not merged into the core NTC/NID tables because they are auxiliary methodology or non-network-traffic security papers:

## 2025      
**No.** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-  | :-: 
:triangular_flag_on_post: 01 | **TIFS** | Image Steganalysis Based on Dual-Path Enhancement and Fractal Downsampling | [Paper](https://ieeexplore.ieee.org/document/10746506/) 

## 2022      
**No.** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-  | :-: 
:triangular_flag_on_post: 01 | **Stochastic analysis, filtering, and stochastic optimization: a commemorative volume to honor mark H. A. Davis's contributions** | Developing the path signature methodology and its application to landmark- based human action recognition | [Paper](https://doi.org/10.1007/978-3-030-98519-6_18)


### Thanks
Inspiration from [this](https://github.com/jiwei0921/SOD-CNNs-based-code-summary-) repository.

# Privacy-Preserving Federated Learning 
* Privacy-Preserving Federated Learning is a technique for training machine learning models on decentralized data while protecting privacy

## Characteristics
* **Federated Learning (FL):** A machine learning paradigm where models are trained across decentralized data sources (clients) without moving raw data.
* **Privacy-Preserving FL (PPFL):** Enhances FL with techniques to ensure sensitive user data remains protected even during training and aggregation.
* **Core ideas:**
  * Local training → models learn directly on devices or silos.
  * Secure aggregation → only encrypted or masked model updates are shared.
  * Differential privacy → random noise added to updates prevents leakage of individual data.
  * Homomorphic encryption / MPC → allows computations on encrypted updates.
* **Benefits:** Protects user data, complies with regulations (e.g., GDPR), and enables collaboration across organizations without exposing raw datasets.
* **Applications:** Healthcare, finance, IoT, mobile devices, cross-silo collaboration.


## Terms and abbereviations
* **FL**: _Federated Learning_
* **PPFL**: _Privacy-Preserving Federated Learning_
* **Cross-silo FL**:
   * ML labels are created internally by the institution
   * These labels never leave the institution
* **Non-IID Data**: not independent & identically distributed client data
* **DP**: _Differential Privacy_: adds noise to client data - during model updates - to prevent information leakage


# Literature review
* Google's Feaderated learning page: https://federated.withgoogle.com/#research
* Google Research blog:  Federated Learning: Collaborative Machine Learning without Centralized Training Data
https://research.google/blog/federated-learning-collaborative-machine-learning-without-centralized-training-data/

# Hi, I'm Raja Babu Sahu 

> **Finalist : Indian Army Terrier Cyber Quest 2025** &nbsp;|&nbsp; **AI/ML Engineer in the making** &nbsp;|&nbsp; **Problem-Solver** &nbsp;|&nbsp; **Strategic Team Leader**

---

## About Me

I'm a final-year Computer Science Engineering student at **GIET University, Gunupur**, specializing in **Artificial Intelligence and Machine Learning**. I build ML systems end-to-end - from raw data and model training to deployment behind real APIs.

My recent work spans **multi-modal deep learning** (fusing image, video, and audio models for deepfake detection) and **rigorous ML evaluation on real sensor data** (drone fault detection, tested with proper cross-validation instead of trusting a single lucky train/test split). I care as much about *proving a model actually works* as I do about building it.

I'm actively looking for **AI/ML Engineering roles** where I can build, evaluate, and ship intelligent systems.

### Skills & Expertise

- **Languages:** Python, C, SQL
- **ML / Deep Learning:** PyTorch, TensorFlow, Keras, Scikit-learn, XGBoost, CNNs, LSTMs, Attention/Transformers
- **MLOps & Deployment:** FastAPI, Docker, Kubernetes, TorchServe, Kafka, REST API Design
- **Model Evaluation:** Cross-Validation (GroupKFold, LOFO), Data Leakage Detection, Model Calibration
- **Tools:** Git, GitHub, Jupyter, Google Colab, VS Code

---

## Projects

###  [LENS - Multi-Modal Deepfake Detection Platform](https://github.com/rajababusahu07/Ai-synthetic-media-detection-system)
*Python · PyTorch · FastAPI · Kafka · Docker · Kubernetes · Next.js*

A production-grade platform that detects deepfakes across **images, video, and audio** using an event-driven microservices architecture.

- Integrated **5 deep learning models** (EfficientNet-B4, TimeSformer, ResNet34+RawNet3, SyncNet, Bayesian Fusion MLP), achieving up to **97% AUROC** on fused predictions.
- Built an event-driven pipeline on **Apache Kafka** with **KEDA autoscaling**, independently scaling GPU workers across image, video, and audio workloads.
- Designed a **Bayesian Fusion MLP** with **MC Dropout** uncertainty estimation and **Isotonic Regression** calibration, and deployed the full stack (13 services) via **TorchServe**, Docker, and Kubernetes.

###  [Drone Anomalies Detection System](https://github.com/rajababusahu07/Drone_Anomalies_Detection_System)
*Python · Scikit-learn · XGBoost · Deep Learning (CNN+LSTM+Attention) · FastAPI*

A multi-label fault detection system built on **37 real drone flight logs**, with a strong emphasis on proving the model actually generalizes.

- Processed **395,926 sensor readings** into a clean, leakage-free dataset, catching and fixing a data leakage bug that had inflated F1 scores from ~0.99 down to a real, honest 0.29–0.82.
- Designed a **CNN + LSTM + Self-Attention** model on sliding time windows to handle severe class imbalance (rarest fault at 0.08% prevalence).
- Validated with **Leave-One-Flight-Out (LOFO) cross-validation** across all 37 flights, proving the deep learning model more than doubled the baseline's honest F1 score (0.27 → 0.67), then deployed it via a **FastAPI** endpoint.

---

## Hackathons & Achievements

-  **Finalist - Indian Army Terrier Cyber Quest 2025** (New Delhi): Top 6 nationally for the Drone Anomaly Detection problem statement.
-  **Finalist - CyberHack 2025** (IIM Nagpur): Recognized nationally for an innovative IoT-integrated solution.
-  **3rd Place - HackFest 2025** (Startup Odisha, O-Hub Bhubaneswar): AI-driven solution for a real-world startup problem.
-  **6th Technovation Hackathon Winner** (Sharda University, New Delhi)
-  **6th Place - Smart India Hackathon 2025**: Plastic detection system in water, among 500 national teams.
-  **Qualified - ISRO Robotics Challenge (IRoC) 2026**: Cleared Preliminary and Qualification rounds.
-  **Publications:** Two research abstracts at the International TRIBE Conference (Science Global Publication), ISBN: 979-8-88-599-135-3.
-  **Organizer - Hacknovation** (University-Level Hackathon): 6 problem statements, 600+ participants.
-  **Organizer - Cybersecurity Awareness Program**, under Rayagada District Police Administration & SDM.

---

## Let's Connect

I'm always open to collaborating on interesting AI/ML projects or discussing new opportunities.

-  **LinkedIn:** [linkedin.com/in/raja-babu-sahu-b3986b349](https://www.linkedin.com/in/raja-babu-sahu-b3986b349)
-  **Email:** [rajababu2003sahu@gmail.com](mailto:rajababu2003sahu@gmail.com)

> "Innovation distinguishes between a leader and a follower." — Steve Jobs

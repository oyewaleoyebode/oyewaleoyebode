# About Me

I’m Oyebode Oluwatobi Oyewale, a Master’s student at the Cyber Resilience Laboratory, NAIST (Japan). I specialize in voice biometrics and the development of secure speaker verification systems. My research bridges artificial intelligence, cybersecurity, and practical deployment, particularly for mobile banking in underserved and low-resource environments.

---

## Research Projects

### Degradation-Aware Verification Framework  

Proposed and implemented **Predictive Degradation Threshold Modeling (PDTM)**, **which forecasts verification risks based on SNR, MFCC variability, and previous outcomes**. This enables adaptive security controls like liveness detection and fallback mechanisms.

**> Repositories Coming Soon**

### Dataset Creation: SecureVoice50

---
**license: cc-by-4.0**

This paper introduces a **speech dataset** developed to advance research in **speaker identification** and **voice biometric verification**, 
particularly in the context of **mobile banking** and other security-sensitive applications. 

The dataset comprises recordings from **50 participants** with diverse linguistic and cultural backgrounds and varying levels of English proficiency. 

Each participant provided voice samples across multiple devices, including low-end smartphones, in-call scenarios, and external microphones, recorded in both indoor and outdoor environments to reflect real-world usage conditions.

**> Repositories Coming Soon**


### Real-Time Speaker Identification System  
---
**The rise of the mobile era**, especially with the **availability of the internet**, has significantly contributed to the **growth of mobile banking**, enhancing **financial inclusion**, particularly among **underserved populations**. However, **reliance on basic mobile devices** without **advanced biometric security features** exposes users to risks of **financial fraud**, **unauthorized account access**, and **identity theft**.

This study introduces a **lightweight speaker identification system** tailored to improve the **security of mobile banking** in **low-resource environments**. By utilizing **voice biometric authentication**, the system **confirms the user’s identity through their voice** at the end of each transaction, ensuring that only the **authorized user** can complete the transaction even if their **Personal Identification Number (PIN)** is compromised.

The system combines **advanced deep learning models**, such as **Whisper-large-v3** and **Emphasized Channel Attention, Propagation, and Aggregation in Time Delay Neural Network (ECAPA-TDNN)**, to **extract detailed voice features**, including **linguistic patterns** and **unique speaker traits**, ensuring **high accuracy** and **reliability** in **real-time identification**. Additionally, **liveness detection** is integrated to **defend against advanced spoofing**, further enhancing **system security**.

Evaluations on **real-world data** demonstrate the system’s **robust performance**, achieving **99.59% accuracy**, **99.62% precision**, and an **Equal Error Rate (EER) of 0.0017**, validating the system’s **practicality in constrained environments** without requiring **extensive computational resources**.

This solution provides a **scalable and secure voice authentication method** that is particularly beneficial for **underserved communities**, advancing both **mobile banking security** and **financial inclusion**.

**Developed a speaker identification pipeline** that uses **fused embeddings from Whisper and ECAPA-TDNN**. The system performs **one-to-many speaker verification** without requiring **passphrases**. It is designed for **low-end mobile devices** in **real-time banking use cases**.


**> Repositories Coming Soon**

### Optimizing Voice Biometric Verification in Banking 
---
**Biometric verification** is essential for **secure identity verification** and **authentication** during banking transactions, using **fingerprints**, **facial features**, **irises**, and **voices**. **Voice biometrics** is a **promising** alternative among these methods, owing to its **potential for robust and convenient user authentication**.

However, their effectiveness is significantly challenged by **variations in the voice** caused by **different device configurations** and **environmental conditions**. These variations can **reduce the effectiveness** of speaker identification and **undermine the reliability** of voice-based systems in **securing online transactions**. This study addresses these challenges to an **effective comparative solution** by focusing on the difficulties posed by **voice variations** resulting from differences in **device hardware**, **microphone quality**, and **environmental noise**.

Our approach employs **machine learning techniques** using **advanced speech enhancement methods** to **improve the consistency and accuracy of voice biometric verification across diverse devices**. Specifically, we employ an **adaptive filter** model that enhances **signal extraction**, **noise suppression**, and **predictive precision**. Furthermore, our **empirical demonstration** demonstrated that **the adaptive filter significantly improved the accuracy of voice biometric systems by mitigating the impact of device-induced voice variations**. In addition, we evaluate the performance of this model using a range of **metrics**.

**This project addresses the challenges of device variation and environmental noise in voice-based banking systems. I adopted a machine learning approach, combining CNN-LSTM architectures with speech enhancement techniques (including adaptive filtering) to improve speaker consistency across devices.**

**> View Repositories https://github.com/oyewaleoyebode/Optimizing-Voice-Biometric-Verification-in-Banking-with-Machine-Learning-for-Speaker-Identification**



## Publications
---
**Optimizing Voice Biometric Verification in Banking with Machine Learning for Speaker Identification**  
*Presented at APCC 2024*  
O. O. Oyewale, M. D. Hossain, Y. Taenaka, and Y. Kadobayashi  
2024 IEEE 29th Asia Pacific Conference on Communications (APCC), Bali, Indonesia, pp. 377–384  
DOI: [10.1109/APCC62576.2024.10768085](https://doi.org/10.1109/APCC62576.2024.10768085)

---

## Tools & Technologies I Use

- Voice Models: Whisper, ECAPA-TDNN, Wav2Vec2  
- Languages: Python (main), JavaScript, Shell scripting  
- Libraries: PyTorch, Hugging Face Transformers, SpeechBrain, Scikit-learn, Librosa  
- Workflow: Google Colab, Jupyter, VS Code, Git/GitHub  
- Deployment: FastAPI, Streamlit, REST APIs for voice-based access

---

## Let's Connect

- LinkedIn: [linkedin.com/in/oyebode-oluwatobi-oyewale-583114179](https://www.linkedin.com/in/oyebode-oluwatobi-oyewale-583114179)  
- Website: [https://sites.google.com/view/oyebodeoluwatobi/about](https://sites.google.com/view/oyebodeoluwatobi/about)

---

## Collaboration & Interests

I'm open to:

- Research collaborations in biometric security and speech AI  
- Consulting on secure voice systems for financial and identity platforms  
- PhD academic partnerships focused on privacy-preserving voice technologies

##Contact: Feel free to message me on LinkedIn for collaboration, research, or speaking opportunities.


Feel free to reach out.


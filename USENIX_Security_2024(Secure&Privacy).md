USENIX Security 2024会议accepted论文合集

[TOC]



# 会议主题

Crypto I: Secret Key Exchange

Crypto II: Searchable Encryption

Crypto III: Password and Secret Key

Crypto IV: Position and Elections

Crypto V: Private Information Retrieval

Crypto VI: Security Analysis

Crypto VII: Private Set Operations

Crypto VIII: Side Channel

Crypto IX: Attacks

Differential Privacy I

Differential Privacy II

Zero-Knowledge Proof I

Zero-Knowledge Proof II

Blockchain I

Blockchain II

Cryptographic Protocols I: Multi-Party Computation

Cryptographic Protocols II

Cryptographic Protocols III

ML I: Federated Learning

ML II: Fault Injection and Robustness

ML III: Secure ML

ML IV: Privacy Inference I

ML V: Backdoor Defense

ML VI: Digital Adversarial Attacks

ML VII: Adversarial Attack Defense

ML VIII: Backdoors and Federated Learning

ML IX: Model Extraction and Watermark

ML X: Privacy Inference II

ML XI: Physical Adversarial Attacks

ML for Security

Software Security + ML 1

Software Security + ML 2

Network Security I: DDoS

Network Security II: Attacks

Network Security III: Detection

Network Security IV: Infrastructure

Wireless Security I: Cellular and Bluetooth

Wireless Security II: Sky and Space

Web Security I

Web Security II: Privacy

Web Security III: XSS and PHP

Cloud Security

Hardware Security I: Attacks and Defense

Hardware Security II: Architecture and Microarchitecture

Hardware Security III: Signals

Hardware Security IV: Firmware

Hardware Security V: Embedded

Side Channel I: Transient Execution

Side Channel II: RowHammer

Side Channel III

Side Channel IV

User Studies I: Social Media Platforms

User Studies II: At-Risk Users

User Studies III: Privacy I

User Studies IV: Policies and Best Practices I

User Studies V: Policies and Best Practices II

User Studies VI: Privacy II

User Studies VII: Policies and Best Practices III

User Studies VIII: Cryptography

System Security I: OS

System Security II: OS Kernel

System Security III: Memory I

System Security IV: Multithreading

System Security V: Memory II

Social Issues I: Phishing and Password

Social Issues II: Surveillance and Censorship

Social Issues III: Social Media Platform

Social Issues IV

Measurement I: Fraud and Malware and Spam

Measurement II: Network

Measurement III: Auditing and Best Practices I

Measurement IV: Web

Measurement V: App

Measurement VI: Human Behavior and Security

Measurement VII: Auditing and Best Practices II

Fuzzing I: Software

Fuzzing II: Method

Fuzzing III: Network

Fuzzing IV: Hardware and Firmware

Security Analysis I: Source Code and Binary

Security Analysis II: Program Analysis

Security Analysis III: Protocol

Security Analysis IV: OS

Security Analysis V: ML

Mobile Security I

Mobile Security II

Mobile Privacy

LLM I: Attack and Defense

LLM II: Jailbreaking

LLM III: Abuse

LLM for Security

Deepfake and Synthesis

Forensics

Software Vulnerability Detection

Language-Based Security

AR and VR

Autonomous and Automatic Systems

IoT and CPS




# Wireless Security II: Sky and Space

**Title：**

Orbital Trust and Privacy: SoK on PKI and Location Privacy Challenges in Space Networks

**Authors：**

David Koisser, Sanctuary; Richard Mitev, Technische Universität Darmstadt; Nikita Yadav, Indian Institute of Science, Bangalore; Franziska Vollmer and Ahmad-Reza Sadeghi, Technische Universität Darmstadt

**Abstract：**

The dynamic evolution of the space sector, often referred to as "New Space," has led to increased commercialization and innovation. This transformation is characterized by a surge in satellite numbers, the emergence of small, cost-effective satellites like CubeSats, and the development of space networks. As satellite networks play an increasingly vital role in providing essential services and supporting various activities, ensuring their security is crucial, especially concerning trust relationships among satellites and the protection of satellite service users.
Satellite networks possess unique characteristics, such as orbital dynamics, delays, and limited bandwidth, posing challenges to trust and privacy. While prior research has explored various aspects of space network security, this paper systematically investigates two crucial yet unexplored dimensions: (i) The integrity of PKI components directly impacts the security and privacy of satellite communications and data transmission, with orbital delays and disruptions potentially hindering timely certificate revocation checks. (ii) Conversely, transmitting user signals to satellites requires careful consideration to prevent location tracking and unauthorized surveillance. By drawing on insights from terrestrial studies, we aim to provide a comprehensive understanding of these intertwined security aspects, identify research gaps, and stimulate further exploration to tackle these research challenges in the evolving domain of space network security.



**Title：**

RECORD: A RECeption-Only Region Determination Attack on LEO Satellite Users

**Authors：**

Eric Jedermann, RPTU Kaiserslautern-Landau; Martin Strohmeier and Vincent Lenders, armasuisse; Jens Schmitt, RPTU Kaiserslautern-Landau

**Abstract：**

Low Earth orbit (LEO) satellite communication has recently experienced a dramatic increase of usage in diverse application sectors. Naturally, the aspect of location privacy is becoming crucial, most notably in security or military applications. In this paper, we present a novel passive attack called RECORD, which is solely based on the reception of messages to LEO satellite users on the ground, threatening their location privacy. In particular, we show that by observing only the downlink of "wandering" communication satellites over wide beams can be exploited at scale from passive attackers situated on Earth to estimate the region in which users are located. We build our own distributed satellite reception platform to implement the RECORD attack. We analyze the accuracy and limiting factors of this new attack using real-world measurements from our own Iridium satellite communication. Our experimental results reveal that by observing only 2.3 hours of traffic, it is possible to narrow down the position of an Iridium user to an area below 11 km of radius (compared to the satellite beam size of 4700 km diameter). We conduct additional extensive simulative evaluations, which suggest that it is feasible to narrow down the unknown location of a user even further, for instance, to below 5 km radius when the observation period is increased to more than 16 hours. We finally discuss the transferability of RECORD to different LEO constellations and highlight possible countermeasures.



**Title：**

Wireless Signal Injection Attacks on VSAT Satellite Modems

**Authors：**

Robin Bisping, ETH Zurich; Johannes Willbold, Ruhr University Bochum; Martin Strohmeier and Vincent Lenders, Cyber-Defence Campus, armasuisse

**Abstract：**

This work considers the threat model of wireless signal injection attacks on Very Small Aperture Terminals (VSAT) satellite modems. In particular, we investigate the feasibility to inject malicious wireless signals from a transmitter on the ground in order to compromise and manipulate the control of close-by satellite terminals. Based on a case study with a widely used commercial modem device, we find that VSATs are not designed to withstand simple signal injection attacks. The modems assume that any received signal comes from a legitimate satellite. We show that an attacker equipped with a low-cost software-defined radio (SDR) can inject arbitrary IP traffic into the internal network of the terminal. We explore different attacks that aim to deny service, manipulate the modem's firmware, or gain a remote admin shell. Further, we quantify their probability of success depending on the wireless channel conditions and the placement of the attacker versus the angle of arrival of the signal at the antenna dish of the receiver.



**Title：**

On a Collision Course: Unveiling Wireless Attacks to the Aircraft Traffic Collision Avoidance System (TCAS)

**Authors：**

Giacomo Longo, DIBRIS, University of Genova; Martin Strohmeier, Cyber-Defence Campus, armasuisse S + T; Enrico Russo, DIBRIS, University of Genova; Alessio Merlo, CASD, School of Advanced Defense Studies; Vincent Lenders, Cyber-Defence Campus, armasuisse S + T

**Abstract：**

Collision avoidance systems have been a safety net of last resort in aviation since their introduction in the 1980s. Through constantly refined safety procedures and hard lessons learned from mid-air collisions, the TCAS II Version 7.1 has become the global standard, significantly improving safety in a fast-growing field.
Despite this safety record, TCAS was not designed with security in mind, even in its newest versions. With the rise of software-defined radios, security researchers have shown many wireless technologies in aviation and critical infrastructures to be insecure against radio frequency (RF) attacks. However, while similar attacks have been postulated for TCAS with its built-in distance measurement, all attempts to execute them have failed so far.
In this paper, we present the first working RF attacks on TCAS. We demonstrate how to take full control over the collision avoidance displays and create so-called RA of arbitrary aircraft on collision course. We build the necessary tooling using commercial off-the-shelf hardware, creating sufficient conditions for the attacker to spoof colliding aircraft from a distance of up to 4.2 km.
We evaluate this and further attacks extensively on a live, real-world, certified aircraft test system and discuss potential countermeasures and mitigations that should be considered by aircraft and system manufacturers in the future.



# Network Security I: DDoS

**Title:**

SmartCookie: Blocking Large-Scale SYN Floods with a Split-Proxy Defense on Programmable Data Planes

**Authors:**

Sophia Yoo, Xiaoqi Chen, and Jennifer Rexford, Princeton University

**Abstract:**

Despite decades of mitigation efforts, SYN flooding attacks continue to increase in frequency and scale, and adaptive adversaries continue to evolve. Meanwhile, volumes of benign traffic in modern networks are also growing rampantly. As a result, network providers, which run thousands of servers and process 100s of Gbps of traffic, find themselves urgently requiring defenses that are secure against adaptive adversaries, scalable against large volumes of traffic, and highly performant for benign applications. Unfortunately, existing defenses local to a single device (e.g., purely software-based or hardware-based) are failing to keep up with growing attacks and struggle to provide performance, security, or both. In this paper, we present SmartCookie, the first system to run cryptographically secure SYN cookie checks on high-speed programmable switches, for both security and performance. Our novel split-proxy defense leverages emerging programmable switches to block 100% of SYN floods in the switch data plane and also uses state-of-the-art kernel technologies such as eBPF to enable scalability for serving benign traffic. SmartCookie defends against adaptive adversaries at two orders of magnitude greater attack traffic than traditional CPU-based software defenses, blocking attacks of 136.9 Mpps without packet loss. We also achieve 2x-6.5x lower end-to-end latency for benign traffic compared to existing switch-based hardware defenses.



**Title:**

Loopy Hell(ow): Inﬁnite Traffic Loops at the Application Layer

**Authors:**

Yepeng Pan, Anna Ascheman, and Christian Rossow, CISPA Helmholtz Center for Information Security

**Abstract:**

Denial-of-Service (DoS) attacks have long been a persistent threat to network infrastructures. Existing attack primitives require attackers to continuously send traffic, such as in SYN floods, amplification attacks, or application-layer DoS. In contrast, we study the threat of application-layer traffic loops, which are an almost cost-free attack primitive alternative. Such loops exist, e.g., if two servers consider messages sent to each other as malformed and respond with errors that again trigger error messages. Attackers can send a single IP-spoofed loop trigger packet to initiate an infinite loop among two servers. But despite the severity of traffic loops, to the best of our knowledge, they have never been studied in greater detail.

In this paper, we thus investigate the threat of application-layer traffic loops. To this end, we propose a systematic approach to identify loops among real servers. Our core idea is to learn the response functions of all servers of a given application-layer protocol, encode this knowledge into a loop graph, and finally, traverse the graph to spot looping server pairs. Using the proposed method, we examined traffic loops among servers running both popular (DNS, NTP, and TFTP) and legacy (Daytime, Time, Active Users, Chargen, QOTD, and Echo) UDP protocols and confirmed the prevalence of traffic loops. In total, we identified approximately 296k servers in IPv4 vulnerable to traffic loops, providing attackers the opportunity to abuse billions of loop pairs.



**Title:**

Zero-setup Intermediate-rate Communication Guarantees in a Global Internet

**Authors:**

Marc Wyss and Adrian Perrig, ETH Zurich

**Abstract:**

Network-targeting volumetric DDoS attacks remain a major threat to Internet communication. Unfortunately, existing solutions fall short of providing forwarding guarantees to the important class of short-lived intermediate-rate communication such as web traffic in a secure, scalable, light-weight, low-cost, and incrementally deployable fashion. To overcome those limitations we design Z-Lane, a system achieving those objectives by ensuring bandwidth isolation among authenticated traffic from (groups of) autonomous systems, thus safeguarding intermediate-rate communication against even the largest volumetric DDoS attacks. Our evaluation on a global testbed and our high-speed implementation on commodity hardware demonstrate Z-Lane's effectiveness and scalability.



**Title:**

Towards an Effective Method of ReDoS Detection for Non-backtracking Engines

**Authors:**

Weihao Su, Hong Huang, and Rongchen Li, Key Laboratory of System Software (Chinese Academy of Sciences) and State Key Laboratory of Computer Science, Institute of Software, Chinese Academy of Sciences; University of Chinese Academy of Sciences; Haiming Chen, Key Laboratory of System Software (Chinese Academy of Sciences) and State Key Laboratory of Computer Science, Institute of Software, Chinese Academy of Sciences; Tingjian Ge, Miner School of Computer & Information Sciences, University of Massachusetts, Lowell

**Abstract:**

Regular expressions (regexes) are a fundamental concept across the fields of computer science. However, they can also induce the Regular expression Denial of Service (ReDoS) attacks, which are a class of denial of service attacks, caused by super-linear worst-case matching time. Due to the severity and prevalence of ReDoS attacks, the detection of ReDoS-vulnerable regexes in software is thus vital. Although various ReDoS detection approaches have been proposed, these methods have focused mainly on backtracking regex engines, leaving the problem of ReDoS vulnerability detection on non-backtracking regex engines largely open.

To address the above challenges, in this paper, we first systematically analyze the major causes that could contribute to ReDoS vulnerabilities on non-backtracking regex engines. We then propose a novel type of ReDoS attack strings that builds on the concept of simple strings. Next we propose EvilStrGen, a tool for generating attack strings for ReDoS-vulnerable regexes on non-backtracking engines. It is based on a novel incremental determinisation algorithm with heuristic strategies to lazily find the k-simple strings without explicit construction of finite automata. We evaluate EvilStrGen against six state-of-the-art approaches on a broad range of publicly available datasets containing 736,535 unique regexes. The results illustrate the significant efficacy of our tool. We also apply our tool to 85 intensively-tested projects, and have identified 34 unrevealed ReDoS vulnerabilities.



# ML I: Federated Learning

**Title：**

Defending Against Data Reconstruction Attacks in Federated Learning: An Information Theory Approach

**Authors：**

Qi Tan, Department of Computer Science and Technology, Tsinghua University; Qi Li, Institute for Network Science and Cyberspace, Tsinghua University; Yi Zhao, School of Cyberspace Science and Technology, Beijing Institute of Technology; Zhuotao Liu, Institute for Network Science and Cyberspace, Tsinghua University; Xiaobing Guo, Lenovo Research; Ke Xu, Department of Computer Science and Technology, Tsinghua University

**Abstract：**

Federated Learning (FL) trains a black-box and high-dimensional model among different clients by exchanging parameters instead of direct data sharing, which mitigates the privacy leak incurred by machine learning. However, FL still suffers from membership inference attacks (MIA) or data reconstruction attacks (DRA). In particular, an attacker can extract the information from local datasets by constructing DRA, which cannot be effectively throttled by existing techniques, e.g., Differential Privacy (DP). In this paper, we aim to ensure a strong privacy guarantee for FL under DRA. We prove that econstruction errors under DRA are constrained by the information acquired by an attacker, which means that constraining the transmitted information can effectively throttle DRA. To quantify the information leakage incurred by FL, we establish a channel model, which depends on the upper bound of joint mutual information between the local dataset and multiple transmitted parameters. Moreover, the channel model indicates that the transmitted information can be constrained through data space operation, which can improve training efficiency and the model accuracy under constrained information. According to the channel model, we propose algorithms to constrain the information transmitted in a single round of local training. With a limited number of training rounds, the algorithms ensure that the total amount of transmitted information is limited. Furthermore, our channel model can be applied to various privacy-enhancing techniques (such as DP) to enhance privacy guarantees against DRA. Extensive experiments with real-world datasets validate the effectiveness of our methods.



**Title：**

FAMOS: Robust Privacy-Preserving Authentication on Payment Apps via Federated Multi-Modal Contrastive Learning

**Authors：**

Yifeng Cai, Key Laboratory of High Confidence Software Technologies (PKU), Ministry of Education; School of Computer Science, Peking University; Ziqi Zhang, Department of Computer Science, University of Illinois Urbana-Champaign; Jiaping Gui, School of Electronic Information and Electrical Engineering, Shanghai Jiao Tong University; Bingyan Liu, School of Computer Science, Beijing University of Posts and Telecommunications; Xiaoke Zhao, Ruoyu Li, and Zhe Li, Ant Group; Ding Li, Key Laboratory of High Confidence Software Technologies (PKU), Ministry of Education; School of Computer Science, Peking University

**Abstract：**

The rise of mobile payment apps necessitates robust user authentication to ensure legitimate user access. Traditional methods, like passwords and biometrics, are vulnerable once a device is compromised. To overcome these limitations, modern solutions utilize sensor data to achieve user-agnostic and scalable behavioral authentication. However, existing solutions face two problems when deployed to real-world applications. First, it is not robust to noisy background activities. Second, it faces the risks of privacy leakage as it relies on centralized training with users' sensor data.
In this paper, we introduce FAMOS, a novel authentication framework based on federated multi-modal contrastive learning. The intuition of FAMOS is to fuse multi-modal sensor data and cluster the representation of one user's data by the action category so that we can eliminate the influence of background noise and guarantee the user's privacy. Furthermore, we incorporate FAMOS with federated learning to enhance performance while protecting users' privacy. We comprehensively evaluate FAMOS using real-world datasets and devices. Experimental results show that FAMOS is efficient and accurate for real-world deployment. FAMOS has an F1-Score of 0.91 and an AUC of 0.97, which are 42.19% and 27.63% higher than the baselines, respectively.



**Title：**

Efficient Privacy Auditing in Federated Learning

**Authors：**

Hongyan Chang, National University of Singapore; Brandon Edwards, Intel Corporation; Anindya S. Paul, University of Florida; Reza Shokri, National University of Singapore

**Abstract：**

We design a novel efficient membership inference attack to audit privacy risks in federated learning. Our approach involves computing the slope of specific model performance metrics (e.g., model's output and its loss) across FL rounds to differentiate members from non-members. Since these metrics are automatically computed during the FL process, our solution imposes negligible overhead and can be seamlessly integrated without disrupting training. We validate the effectiveness and superiority of our method over prior work across a wide range of FL settings and real-world datasets.



**Title：**

Lotto: Secure Participant Selection against Adversarial Servers in Federated Learning

**Authors：**

Zhifeng Jiang and Peng Ye, Hong Kong University of Science and Technology; Shiqi He, University of Michigan; Wei Wang, Hong Kong University of Science and Technology; Ruichuan Chen, Nokia Bell Labs; Bo Li, Hong Kong University of Science and Technology

**Abstract：**

In Federated Learning (FL), common privacy-enhancing techniques, such as secure aggregation and distributed differential privacy, rely on the critical assumption of an honest majority among participants to withstand various attacks. In practice, however, servers are not always trusted, and an adversarial server can strategically select compromised clients to create a dishonest majority, thereby undermining the system's security guarantees. In this paper, we present Lotto, an FL system that addresses this fundamental, yet underexplored issue by providing secure participant selection against an adversarial server. Lotto supports two selection algorithms: random and informed. To ensure random selection without a trusted server, Lotto enables each client to autonomously determine their participation using verifiable randomness. For informed selection, which is more vulnerable to manipulation, Lotto approximates the algorithm by employing random selection within a refined client pool. Our theoretical analysis shows that Lotto effectively aligns the proportion of server-selected compromised participants with the base rate of dishonest clients in the population. Large-scale experiments further reveal that Lotto achieves time-to-accuracy performance comparable to that of insecure selection methods, indicating a low computational overhead for secure selection.



# ML V: Backdoor Defense

**Title：**

Neural Network Semantic Backdoor Detection and Mitigation: A Causality-Based Approach

**Authors：**

Bing Sun, Jun Sun, and Wayne Koh, Singapore Management University; Jie Shi, Huawei Singapore

**Abstract：**

Different from ordinary backdoors in neural networks which are introduced with artificial triggers (e.g., certain specific patch) and/or by tampering the samples, semantic backdoors are introduced by simply manipulating the semantic, e.g., by labeling green cars as frogs in the training set. By focusing on samples with rare semantic features (such as green cars), the accuracy of the model is often minimally affected. Since the attacker is not required to modify the input sample during training nor inference time, semantic backdoors are challenging to detect and remove. Existing backdoor detection and mitigation techniques are shown to be ineffective with respect to semantic backdoors. In this work, we propose a method to systematically detect and remove semantic backdoors. Specifically we propose SODA (Semantic BackdOor Detection and MitigAtion) with the key idea of conducting lightweight causality analysis to identify potential semantic backdoor based on how hidden neurons contribute to the predictions and to remove the backdoor by adjusting the responsible neurons' contribution towards the correct predictions through optimization. SODA is evaluated with 21 neural networks trained on 6 benchmark datasets and 2 kinds of semantic backdoor attacks for each dataset. The results show that it effectively detects and removes semantic backdoors and preserves the accuracy of the neural networks.



**Title：**

On the Difficulty of Defending Contrastive Learning against Backdoor Attacks

**Authors：**

Changjiang Li, Stony Brook University; Ren Pang, Bochuan Cao, Zhaohan Xi, and Jinghui Chen, Pennsylvania State University; Shouling Ji, Zhejiang University; Ting Wang, Stony Brook University

**Abstract：**

Recent studies have shown that contrastive learning, like supervised learning, is highly vulnerable to backdoor attacks wherein malicious functions are injected into target models, only to be activated by specific triggers. However, thus far it remains under-explored how contrastive backdoor attacks fundamentally differ from their supervised counterparts, which impedes the development of effective defenses against the emerging threat.

This work represents a solid step toward answering this critical question. Specifically, we define TRL, a unified framework that encompasses both supervised and contrastive backdoor attacks. Through the lens of TRL, we uncover that the two types of attacks operate through distinctive mechanisms: in supervised attacks, the learning of benign and backdoor tasks tends to occur independently, while in contrastive attacks, the two tasks are deeply intertwined both in their representations and throughout their learning processes. This distinction leads to the disparate learning dynamics and feature distributions of supervised and contrastive attacks. More importantly, we reveal that the specificities of contrastive backdoor attacks entail important implications from a defense perspective: existing defenses for supervised attacks are often inadequate and not easily retrofitted to contrastive attacks. We also explore several promising alternative defenses and discuss their potential challenges. Our findings highlight the need for defenses tailored to the specificities of contrastive backdoor attacks, pointing to promising directions for future research.



**Title：**

Mudjacking: Patching Backdoor Vulnerabilities in Foundation Models

**Authors：**

Hongbin Liu, Michael K. Reiter, and Neil Zhenqiang Gong, Duke University

**Abstract：**

Foundation model has become the backbone of the AI ecosystem. In particular, a foundation model can be used as a general-purpose feature extractor to build various downstream classifiers. However, foundation models are vulnerable to backdoor attacks and a backdoored foundation model is a single-point-of-failure of the AI ecosystem, e.g., multiple downstream classifiers inherit the backdoor vulnerabilities simultaneously. In this work, we propose Mudjacking, the first method to patch foundation models to remove backdoors. Specifically, given a misclassified trigger-embedded input detected after a backdoored foundation model is deployed, Mudjacking adjusts the parameters of the foundation model to remove the backdoor. We formulate patching a foundation model as an optimization problem and propose a gradient descent based method to solve it. We evaluate Mudjacking on both vision and language foundation models, eleven benchmark datasets, five existing backdoor attacks, and thirteen adaptive backdoor attacks. Our results show that Mudjacking can remove backdoor from a foundation model while maintaining its utility.



**Title：**

Xplain: Analyzing Invisible Correlations in Model Explanation

**Authors：**

Kavita Kumari and Alessandro Pegoraro, Technical University of Darmstadt; Hossein Fereidooni, Kobil; Ahmad-Reza Sadeghi, Technical University of Darmstadt

**Abstract：**

Explanation methods analyze the features in backdoored input data that contribute to model misclassification. However, current methods like path techniques struggle to detect backdoor patterns in adversarial situations. They fail to grasp the hidden associations of backdoor features with other input features, leading to misclassification. Additionally, they suffer from irrelevant data attribution, imprecise feature connections, baseline dependence, and vulnerability to the "saturation effect".

To address these limitations, we propose Xplain. Our method aims to uncover hidden backdoor trigger patterns and the subtle relationships between backdoor features and other input objects, which are the main causes of model misclassification. Our algorithm improves existing path techniques by integrating an additional baseline into the Integrated Gradients (IG) formulation. This ensures that features selected in the baseline persist along the integration path, guaranteeing baseline independence. Additionally, we introduce quantitative noise to interpolate samples along the integration path, which reduces feature dependency and captures non-linear interactions. This approach effectively identifies the relevant features that significantly influence model predictions.

Furthermore, Xplain proposes sensitivity analysis to enhance AI system resilience against backdoor attacks. This uncovers clear connections between the backdoor and other input data features, thus shedding light on relevant interactions. We thoroughly test the effectiveness of Xplain on the Imagenet and the multimodal domain of the Visual Question Answering dataset, showing its superiority over current path methods such as Integrated Gradient (IG), left-IG, Guided IG, and Adversarial Gradient Integration (AGI) techniques.



**Title：**

Verify your Labels! Trustworthy Predictions and Datasets via Confidence Scores

**Authors：**

Torsten Krauß, Jasper Stang, and Alexandra Dmitrienko, University of Würzburg

**Abstract：**

Machine learning is a rapidly evolving technology with manifold benefits. At its core lies the mapping between samples and corresponding target labels (SL-Mappings). Such mappings can originate from labeled dataset samples or from prediction generated during model inference. The correctness of SL-Mappings is crucial, both during training and for model predictions, especially when considering poisoning attacks.

Existing standalone works from the dataset cleaning and prediction confidence scoring domains lack a dual-use tool offering an SL-Mappings score, which is impractical. Moreover, these works have drawbacks, e.g., dependence on specific model architectures and reliance on large datasets, which may not be accessible, or lack a meaningful confidence score.

In this paper, we introduce LabelTrust, a versatile tool designed to generate confidence scores for SL-Mappings. We propose pipelines facilitating dataset cleaning and confidence scoring, mitigating the limitations of existing standalone approaches from each domain. Thereby, LabelTrust leverages a Siamese network trained via few-shot learning, requiring minimal clean samples and is agnostic to datasets and model architectures. We demonstrate LabelTrust's efficacy in detecting poisoning attacks within samples and predictions alike, with a modest one-time training overhead of 34.56 seconds and an evaluation time of less than 1 second per SL-Mapping.



# ML VIII: Backdoors and Federated Learning

**Title：**

Lurking in the shadows: Unveiling Stealthy Backdoor Attacks against Personalized Federated Learning

**Authors：**

Xiaoting Lyu, Beijing Jiaotong University; Yufei Han, INRIA; Wei Wang, Jingkai Liu, and Yongsheng Zhu, Beijing Jiaotong University; Guangquan Xu, Tianjin University; Jiqiang Liu, Beijing Jiaotong University; Xiangliang Zhang, University of Notre Dame

**Abstract：**

Federated Learning (FL) is a collaborative machine learning technique where multiple clients work together with a central server to train a global model without sharing their private data. However, the distribution shift across non-IID datasets of clients poses a challenge to this one-model-fits-all method hindering the ability of the global model to effectively adapt to each client's unique local data. To echo this challenge, personalized FL (PFL) is designed to allow each client to create personalized local models tailored to their private data.
While extensive research has scrutinized backdoor risks in FL, it has remained underexplored in PFL applications. In this study, we delve deep into the vulnerabilities of PFL to backdoor attacks. Our analysis showcases a tale of two cities. On the one hand, the personalization process in PFL can dilute the backdoor poisoning effects injected into the personalized local models. Furthermore, PFL systems can also deploy both server-end and client-end defense mechanisms to strengthen the barrier against backdoor attacks. On the other hand, our study shows that PFL fortified with these defense methods may offer a false sense of security. We propose PFedBA, a stealthy and effective backdoor attack strategy applicable to PFL systems. PFedBA ingeniously aligns the backdoor learning task with the main learning task of PFL by optimizing the trigger generation process. Our comprehensive experiments demonstrate the effectiveness of PFedBA in seamlessly embedding triggers into personalized local models. PFedBA yields outstanding attack performance across 10 state-of-the-art PFL algorithms, defeating the existing 6 defense mechanisms. Our study sheds light on the subtle yet potent backdoor threats to PFL systems, urging the community to bolster defenses against emerging backdoor challenges.



**Title：**

ACE: A Model Poisoning Attack on Contribution Evaluation Methods in Federated Learning

**Authors：**

Zhangchen Xu, Fengqing Jiang, and Luyao Niu, University of Washington; Jinyuan Jia, Pennsylvania State University; Bo Li, University of Chicago; Radha Poovendran, University of Washington

**Abstract：**

In Federated Learning (FL), a set of clients collaboratively train a machine learning model (called global model) without sharing their local training data. The local training data of clients is typically non-i.i.d. and heterogeneous, resulting in varying contributions from individual clients to the final performance of the global model. In response, many contribution evaluation methods were proposed, where the server could evaluate the contribution made by each client and incentivize the high-contributing clients to sustain their long-term participation in FL. Existing studies mainly focus on developing new metrics or algorithms to better measure the contribution of each client. However, the security of contribution evaluation methods of FL operating in adversarial environments is largely unexplored. In this paper, we propose the first model poisoning attack on contribution evaluation methods in FL, termed ACE. Specifically, we show that any malicious client utilizing ACE could manipulate the parameters of its local model such that it is evaluated to have a high contribution by the server, even when its local training data is indeed of low quality. We perform both theoretical analysis and empirical evaluations of ACE. Theoretically, we show our design of ACE can effectively boost the malicious client's perceived contribution when the server employs the widely-used cosine distance metric to measure contribution. Empirically, our results show ACE effectively and efficiently deceive five state-of-the-art contribution evaluation methods. In addition, ACE preserves the accuracy of the final global models on testing inputs. We also explore six countermeasures to defend ACE. Our results show they are inadequate to thwart ACE, highlighting the urgent need for new defenses to safeguard the contribution evaluation methods in FL.



**Title：**

BackdoorIndicator: Leveraging OOD Data for Proactive Backdoor Detection in Federated Learning

**Authors：**

Songze Li, Southeast University; Yanbo Dai, HKUST(GZ)

**Abstract：**

In a federated learning (FL) system, decentralized data owners (clients) could upload their locally trained models to a central server, to jointly train a global model. Malicious clients may plant backdoors into the global model through uploading poisoned local models, causing misclassification to a target class when encountering attacker-defined triggers. Existing backdoor defenses show inconsistent performance under different system and adversarial settings, especially when the malicious updates are made statistically close to the benign ones. In this paper, we first reveal the fact that planting subsequent backdoors with the same target label could significantly help to maintain the accuracy of previously planted backdoors, and then propose a novel proactive backdoor detection mechanism for FL named BackdoorIndicator, which has the server inject indicator tasks into the global model leveraging out-of-distribution (OOD) data, and then utilizing the fact that any backdoor samples are OOD samples with respect to benign samples, the server, who is completely agnostic of the potential backdoor types and target labels, can accurately detect the presence of backdoors in uploaded models, via evaluating the indicator tasks. We perform systematic and extensive empirical studies to demonstrate the consistently superior performance and practicality of BackdoorIndicator over baseline defenses, across a wide range of system and adversarial settings.



**Title：**

UBA-Inf: Unlearning Activated Backdoor Attack with Influence-Driven Camouflage

**Authors：**

Zirui Huang, Yunlong Mao, and Sheng Zhong, Nanjing University

**Abstract：**

Machine-Learning-as-a-Service (MLaaS) is an emerging product to meet the market demand. However, end users are required to upload data to the remote server when using MLaaS, raising privacy concerns. Since the right to be forgotten came into effect, data unlearning has been widely supported in on-cloud products for removing users' private data from remote datasets and machine learning models. Plenty of machine unlearning methods have been proposed recently to erase the influence of forgotten data. Unfortunately, we find that machine unlearning makes the on-cloud model highly vulnerable to backdoor attacks. In this paper, we report a new threat against models with unlearning enabled and implement an Unlearning Activated Backdoor Attack with Influence-driven camouflage (UBA-Inf). Unlike conventional backdoor attacks, UBA-Inf provides a new backdoor approach for effectiveness and stealthiness by activating the camouflaged backdoor through machine unlearning. The proposed approach can be implemented using off-the-shelf backdoor generating algorithms. Moreover, UBA-Inf is an "on-demand" attack, offering fine-grained control of backdoor activation through unlearning requests, overcoming backdoor vanishing and exposure problems. By extensively evaluating UBA-Inf, we conclude that UBA-Inf is a powerful backdoor approach that improves stealthiness, robustness, and persistence.

# Differential Privacy I

**Title：**

Less is More: Revisiting the Gaussian Mechanism for Differential Privacy

**Authors：**

Tianxi Ji, Texas Tech University; Pan Li, Case Western Reserve University

**Abstract：**

Differential privacy (DP) via output perturbation has been a de facto standard for releasing query or computation results on sensitive data. Different variants of the classic Gaussian mechanism have been developed to reduce the magnitude of the noise and improve the utility of sanitized query results. However, we identify that all existing Gaussian mechanisms suffer from the curse of full-rank covariance matrices, and hence the expected accuracy losses of these mechanisms equal the trace of the covariance matrix of the noise. Particularly, for query results with multiple entries, in order to achieve DP, the expected accuracy loss of the classic Gaussian mechanism, that of the analytic Gaussian mechanism, and that of the Matrix-Variate Gaussian (MVG) mechanism are lower bounded by terms that scales linearly with the number of entries.

To lift this curse, we design a Rank-1 Singular Multivariate Gaussian (R1SMG) mechanism. It achieves DP on high dimension query results by perturbing the results with noise following a singular multivariate Gaussian distribution, whose covariance matrix is a randomly generated rank-1 positive semi-definite matrix. In contrast, the classic Gaussian mechanism and its variants all consider deterministic full-rank covariance matrices. Our idea is motivated by a clue from Dwork et al.'s seminal work on the classic Gaussian mechanism that has been ignored in the literature: when projecting multivariate Gaussian noise with a full-rank covariance matrix onto a set of orthonormal basis, only the coefficient of a single basis can contribute to the privacy guarantee.

This paper makes the following technical contributions.

(i) The R1SMG mechanisms achieves DP guarantee on high dimension query results in, while its expected accuracy loss is lower bounded by a term that is on a lower order of magnitude by at least the dimension of query results compared with that of the classic Gaussian mechanism, of the analytic Gaussian mechanism, and of the MVG mechanism.

(ii) Compared with other mechanisms, the R1SMG mechanism is more stable and less likely to generate noise with large magnitude that overwhelms the query results, because the kurtosis and skewness of the nondeterministic accuracy loss introduced by this mechanism is larger than that introduced by other mechanisms.



**Title：**

Relation Mining Under Local Differential Privacy

**Authors：**

Kai Dong, Zheng Zhang, Chuang Jia, Zhen Ling, Ming Yang, and Junzhou Luo, Southeast University; Xinwen Fu, University of Massachusetts Lowell

**Abstract：**

Existing local differential privacy (LDP) techniques enable untrustworthy aggregators to perform only very simple data mining tasks on distributed private data, including statistical estimation and frequent item mining. There is currently no general LDP method that discovers relations between items. The main challenge lies in the curse of dimensionality, as the quantity of values to be estimated in mining relations is the square of the quantity of values to be estimated in mining item-level knowledge, leading to a considerable decrease in the final estimation accuracy. We propose LDP-RM, the first relation mining method under LDP. It represents items and relations in a matrix and utilizes singular value decomposition and low rank approximation to reduce the number of values to estimate from O(k2) to O(r), where k is the number of all considered items, and r < k is a parameter determined by the aggregator, signifying the rank of the approximation. LDP-RM serves as a fundamental privacy-preserving method for enabling various complex data mining tasks.



**Title：**

Gradients Look Alike: Sensitivity is Often Overestimated in DP-SGD

**Authors：**

Anvith Thudi and Hengrui Jia, University of Toronto and Vector Institute; Casey Meehan, University of California, San Diego; Ilia Shumailov, University of Oxford; Nicolas Papernot, University of Toronto and Vector Institute

**Abstract：**

Differentially private stochastic gradient descent (DP-SGD) is the canonical approach to private deep learning. While the current privacy analysis of DP-SGD is known to be tight in some settings, several empirical results suggest that models trained on common benchmark datasets leak significantly less privacy for many datapoints. Yet, despite past attempts, a rigorous explanation for why this is the case has not been reached. Is it because there exist tighter privacy upper bounds when restricted to these dataset settings, or are our attacks not strong enough for certain datapoints? In this paper, we provide the first per-instance (i.e., "data-dependent") DP analysis of DP-SGD. Our analysis captures the intuition that points with similar neighbors in the dataset enjoy better data-dependent privacy than outliers. Formally, this is done by modifying the per-step privacy analysis of DP-SGD to introduce a dependence on the distribution of model updates computed from a training dataset. We further develop a new composition theorem to effectively use this new per-step analysis to reason about an entire training run. Put all together, our evaluation shows that this novel DP-SGD analysis allows us to now formally show that DP-SGD leaks significantly less privacy for many datapoints (when trained on common benchmarks) than the current data-independent guarantee. This implies privacy attacks will necessarily fail against many datapoints if the adversary does not have sufficient control over the possible training datasets.



**Title：**

DPAdapter: Improving Differentially Private Deep Learning through Noise Tolerance Pre-training

**Authors：**

Zihao Wang, Rui Zhu, and Dongruo Zhou, Indiana University Bloomington; Zhikun Zhang, Zhejiang University; John Mitchell, Stanford University; Haixu Tang and XiaoFeng Wang, Indiana University Bloomington

**Abstract：**

Recent developments have underscored the critical role of differential privacy (DP) in safeguarding individual data for training machine learning models. However, integrating DP oftentimes incurs significant model performance degradation due to the perturbation introduced into the training process, presenting a formidable challenge in the differentially private machine learning (DPML) field. To this end, several mitigative efforts have been proposed, typically revolving around formulating new DPML algorithms or relaxing DP definitions to harmonize with distinct contexts. In spite of these initiatives, the diminishment induced by DP on models, particularly large-scale models, remains substantial and thus, necessitates an innovative solution that adeptly circumnavigates the consequential impairment of model utility.

In response, we introduce DPAdapter, a pioneering technique designed to amplify the model performance of DPML algorithms by enhancing parameter robustness. The fundamental intuition behind this strategy is that models with robust parameters are inherently more resistant to the noise introduced by DP, thereby retaining better performance despite the perturbations. DPAdapter modifies and enhances the sharpness-aware minimization (SAM) technique, utilizing a two-batch strategy to provide a more accurate perturbation estimate and an efficient gradient descent, thereby improving parameter robustness against noise. Notably, DPAdapter can act as a plug-and-play component and be combined with existing DPML algorithms to further improve their performance. Our experiments show that DPAdapter vastly enhances state-of-the-art DPML algorithms, increasing average accuracy from 72.92% to 77.09% with a privacy budget of ϵ = 4.



# Differential Privacy II

**Title：**

DAAP: Privacy-Preserving Model Accuracy Estimation on Unlabeled Datasets Through Distribution-Aware Adversarial Perturbation

**Authors：**

Guodong Cao, Wuhan University; Zhibo Wang, Zhejiang University; Yunhe Feng, University of North Texas; Xiaowei Dong, Wuhan University

**Abstract：**

In the dynamic field of deep learning, accurately estimating model performance while ensuring data privacy against diverse and unlabeled test datasets presents a critical challenge. This is primarily due to the significant distributional shifts between training and test datasets, which complicates model evaluation. Traditional methods for assessing model accuracy often require direct access to the entire test dataset, posing significant risks of data leakage and model theft. To address these issues, we propose a novel approach: Distribution-Aware Adversarial Perturbation (DAAP). This method is designed to estimate the accuracy of deep learning models on unlabeled test datasets without compromising privacy. Specifically, DAAP leverages a publicly available dataset as an intermediary to bridge the gap between the model and the test data, effectively circumventing direct interaction and mitigating privacy concerns. By strategically applying adversarial perturbations, DAAP minimizes the distributional discrepancies between datasets, enabling precise estimation of model performance on unseen test data. We present two specialized strategies for white-box and black-box model contexts: the former focuses on reducing output entropy disparities, while the latter manipulates distribution discriminators. Overall, the DAAP introduces a novel framework for privacy-preserving accuracy estimation in model evaluation. This novel approach not only addresses critical challenges related to data privacy and distributional shifts but also enhances the reliability and integrity of model performance assessments. Our extensive evaluation on the CIFAR-10-C, CIFAR-100-C, and CelebA datasets demonstrates the effectiveness of DAAP in accurately estimating performance while safeguarding both data and model privacy.



**Title：**

Closed-Form Bounds for DP-SGD against Record-level Inference Attacks

**Authors：**

Giovanni Cherubin, Microsoft Security Response Center; Boris Köpf, Microsoft Azure Research; Andrew Paverd, Microsoft Security Response Center; Shruti Tople, Microsoft Azure Research; Lukas Wutschitz, Microsoft M365 Research; Santiago Zanella-Béguelin, Microsoft Azure Research

**Abstract：**

Machine learning models trained with differentially-private (DP) algorithms such as DP-SGD enjoy resilience against a wide range of privacy attacks. Although it is possible to derive bounds for some attacks based solely on an (ε,δ)-DP guarantee, meaningful bounds require a small enough privacy budget (i.e., injecting a large amount of noise), which results in a large loss in utility. This paper presents a new approach to evaluate the privacy of machine learning models against specific record-level threats, such as membership and attribute inference, without the indirection through DP. We focus on the popular DP-SGD algorithm, and derive simple closed-form bounds. Our proofs model DP-SGD as an information theoretic channel whose inputs are the secrets that an attacker wants to infer (e.g., membership of a data record) and whose outputs are the intermediate model parameters produced by iterative optimization. We obtain bounds for membership inference that match state-of-the-art techniques, whilst being orders of magnitude faster to compute. Additionally, we present a novel data-dependent bound against attribute inference. Our results provide a direct, interpretable, and practical way to evaluate the privacy of trained models against specific inference threats without sacrificing utility.



**Title：**

PrivImage: Differentially Private Synthetic Image Generation using Diffusion Models with Semantic-Aware Pretraining

**Authors：**

Kecen Li, Institute of Automation, Chinese Academy of Sciences and University of Chinese Academy of Sciences; Chen Gong, University of Virginia; Zhixiang Li, University of Bristol; Yuzhong Zhao, University of Chinese Academy of Sciences; Xinwen Hou, Institute of Automation, Chinese Academy of Sciences; Tianhao Wang, University of Virginia

**Abstract：**

Differential Privacy (DP) image data synthesis, which leverages the DP technique to generate synthetic data to replace the sensitive data, allowing organizations to share and utilize synthetic images without privacy concerns. Previous methods incorporate the advanced techniques of generative models and pre-training on a public dataset to produce exceptional DP image data, but suffer from problems of unstable training and massive computational resource demands. This paper proposes a novel DP image synthesis method, termed PRIVIMAGE, which meticulously selects pre-training data, promoting the efficient creation of DP datasets with high fidelity and utility. PRIVIMAGE first establishes a semantic query function using a public dataset. Then, this function assists in querying the semantic distribution of the sensitive dataset, facilitating the selection of data from the public dataset with analogous semantics for pre-training. Finally, we pre-train an image generative model using the selected data and then fine-tune this model on the sensitive dataset using Differentially Private Stochastic Gradient Descent (DP-SGD). PRIVIMAGE allows us to train a lightly parameterized generative model, reducing the noise in the gradient during DP-SGD training and enhancing training stability. Extensive experiments demonstrate that PRIVIMAGE uses only 1% of the public dataset for pre-training and 7.6% of the parameters in the generative model compared to the state-of-the-art method, whereas achieves superior synthetic performance and conserves more computational resources. On average, PRIVIMAGE achieves 6.8% lower FID and 13.2% higher Classification Accuracy than the state-of-the-art method. The replication package and datasets can be accessed online.



**Title：**

"What do you want from theory alone?" Experimenting with Tight Auditing of Differentially Private Synthetic Data Generation

**Authors：**

Meenatchi Sundaram Muthu Selva Annamalai, University College London; Georgi Ganev, University College London and Hazy; Emiliano De Cristofaro, University of California, Riverside

**Abstract：**

Differentially private synthetic data generation (DP-SDG) algorithms are used to release datasets that are structurally and statistically similar to sensitive data while providing formal bounds on the information they leak. However, bugs in algorithms and implementations may cause the actual information leakage to be higher. This prompts the need to verify whether the theoretical guarantees of state-of-the-art DP-SDG implementations also hold in practice. We do so via a rigorous *auditing* process: we compute the information leakage via an adversary playing a distinguishing game and running membership inference attacks (MIAs). If the leakage observed empirically is higher than the theoretical bounds, we identify a DP violation; if it is non-negligibly lower, the audit is loose.

We audit six DP-SDG implementations using different datasets and threat models and find that black-box MIAs commonly used against DP-SDGs are severely limited in power, yielding remarkably loose empirical privacy estimates. We then consider MIAs in stronger threat models, i.e., passive and active white-box, using both existing and newly proposed attacks. Overall, we find that, currently, we do not only need white-box MIAs but also worst-case datasets to *tightly* estimate the privacy leakage from DP-SDGs. Finally, we show that our automated auditing procedure finds both known DP violations (in 4 out of the 6 implementations) as well as a new one in the DPWGAN implementation that was successfully submitted to the NIST DP Synthetic Data Challenge.

The source code needed to reproduce our experiments is available from https://github.com/spalabucr/synth-audit.



# Blockchain I

**Title:**

Mempool Privacy via Batched Threshold Encryption: Attacks and Defenses

**Authors:**

Arka Rai Choudhuri, NTT Research; Sanjam Garg, Julien Piet, and Guru-Vamsi Policharla, University of California, Berkeley

**Abstract:**

With the rising popularity of DeFi applications it is important to implement protections for regular users of these DeFi platforms against large parties with massive amounts of resources allowing them to engage in market manipulation strategies such as frontrunning/backrunning. Moreover, there are many situations (such as recovery of funds from vulnerable smart contracts) where a user may not want to reveal their transaction until it has been executed. As such, it is clear that preserving the privacy of transactions in the mempool is an important goal.

In this work we focus on achieving mempool transaction privacy through a new primitive that we term batched-threshold encryption, which is a variant of threshold encryption with strict efficiency requirements to better model the needs of resource constrained environments such as blockchains. Unlike the naive use of threshold encryption, which requires communication proportional to O(nB) to decrypt B transactions with a committee of n parties, our batched-threshold encryption scheme only needs O(n) communication. We additionally discuss pitfalls in prior approaches that use (vanilla) threshold encryption for mempool privacy.

To show that our scheme is concretely efficient, we implement our scheme and find that transactions can be encrypted in under 6 ms, independent of committee size, and the communication required to decrypt an entire batch of B transactions is 80 bytes per party, independent of the number of transactions B, making it an attractive choice when communication is very expensive. If deployed on Ethereum, which processes close to 500 transaction per block, it takes close to 2.8 s for each committee member to compute a partial decryption and under 3.5 s to decrypt all transactions for a block in single-threaded mode.



**Title:**

Speculative Denial-of-Service Attacks In Ethereum

**Authors:**

Aviv Yaish, The Hebrew University; Kaihua Qin and Liyi Zhou, Imperial College London, UC Berkeley RDI; Aviv Zohar, The Hebrew University; Arthur Gervais, University College London, UC Berkeley RDI

**Abstract:**

Transaction fees compensate actors for resources expended on transactions and can only be charged from transactions included in blocks. But, the expressiveness of Turing-complete contracts implies that verifying if transactions can be included requires executing them on the current blockchain state.

In this work, we show that adversaries can craft malicious transactions that decouple the work imposed on blockchain actors from the compensation offered in return. We introduce three attacks: (i) ConditionalExhaust, a conditional resource-exhaustion attack against blockchain actors. (ii) MemPurge, an attack for evicting transactions from actors' mempools. (iii) GhostTX, an attack on the reputation system used in Ethereum's proposer-builder separation ecosystem.

We evaluate our attacks on an Ethereum testnet and find that by combining ConditionalExhaust and MemPurge, adversaries can simultaneously burden victims' computational resources and clog their mempools to the point where victims are unable to include transactions in blocks. Thus, victims create empty blocks, thereby hurting the system's liveness. The attack's expected cost is $376, but becomes cheaper if adversaries are validators. For other attackers, costs decrease if censorship is prevalent in the network.

ConditionalExhaust and MemPurge are made possible by inherent features of Turing-complete blockchains, and potential mitigations may result in reducing a ledger's scalability.



**Title:**

GuideEnricher: Protecting the Anonymity of Ethereum Mixing Service Users with Deep Reinforcement Learning

**Authors:**

Ravindu De Silva, Wenbo Guo, Nicola Ruaro, Ilya Grishchenko, Christopher Kruegel, and Giovanni Vigna, University of California, Santa Barbara

**Abstract:**

Mixing services are widely employed to enhance anonymity on public blockchains. However, recent research has shown that user identities and transaction associations can be derived even with mixing services. This is mainly due to the lack of guidelines for properly using these services. In fact, mixing service developers often provide guidebooks with lists of actions that might break anonymity, and hence, should be avoided. However, such guidebooks remain incomplete, leaving users unaware of potential actions that might compromise their anonymity. This highlights the necessity for providing users with a more comprehensive guidebook. Unfortunately, existing methods for compiling anonymity compromising patterns rely on postmortem analyses, and they cannot proactively discover patterns before the mixing service is deployed.

We introduce GuideEnricher, a proactive approach for extending user guidebooks with limited human intervention. Our key novelty is a deep reinforcement learning (DRL) agent, which automatically explores patterns for transferring tokens via a mixing service. We introduce two customized designs to better guide the agent in discovering yet-unknown anonymity-compromising patterns: design proper tasks for the agent that possibly lead to compromised anonymity, and include a rule-based detector to detect the known patterns. We train the agent to finish the task while evading the detector. Using a trained agent, we conduct a second analysis step, employing clustering methods and manual inspection, to extract yet unknown patterns from the agent's actions. Through extensive evaluation, we demonstrate that GuideEnricher can train effective agents under multiple mixing services. We show that our agents facilitate the discovery of yet-unknown anonymity-compromising patterns. Furthermore, we demonstrate that GuideEnricher can continuously enrich the guidebook via an iterative update of the detector and our DRL agents.



**Title:**

All Your Tokens are Belong to Us: Demystifying Address Verification Vulnerabilities in Solidity Smart Contracts

**Authors:**

Tianle Sun, Huazhong University of Science and Technology; Ningyu He, Peking University; Jiang Xiao, Huazhong University of Science and Technology; Yinliang Yue, Zhongguancun Laboratory; Xiapu Luo, The Hong Kong Polytechnic University; Haoyu Wang, Huazhong University of Science and Technology

**Abstract:**

In Ethereum, the practice of verifying the validity of the passed addresses is a common practice, which is a crucial step to ensure the secure execution of smart contracts. Vulnerabilities in the process of address verification can lead to great security issues, and anecdotal evidence has been reported by our community. However, this type of vulnerability has not been well studied. To fill the void, in this paper, we aim to characterize and detect this kind of emerging vulnerability. We design and implement AVVERIFIER, a lightweight taint analyzer based on static EVM opcode simulation. Its three-phase detector can progressively rule out false positives and false negatives based on the intrinsic characteristics. Upon a well-established and unbiased benchmark, AVVERIFIER can improve efficiency 2 to 5 times than the SOTA while maintaining a 94.3% precision and 100% recall. After a large-scale evaluation of over 5 million Ethereum smart contracts, we have identified 812 vulnerable smart contracts that were undisclosed by our community before this work, and 348 open source smart contracts were further verified, whose largest total value locked is over $11.2 billion. We further deploy AVVERIFIER as a real-time detector on Ethereum and Binance Smart Chain, and the results suggest that AVVERIFIER can raise timely warnings once contracts are deployed.



**Title:**

Using My Functions Should Follow My Checks: Understanding and Detecting Insecure OpenZeppelin Code in Smart Contracts

**Authors:**

Han Liu, East China Normal University, Shanghai Key Laboratory of Trustworthy Computing; Daoyuan Wu, The Hong Kong University of Science and Technology; Yuqiang Sun, Nanyang Technological University; Haijun Wang, Xi'an Jiaotong University; Kaixuan Li, East China Normal University, Shanghai Key Laboratory of Trustworthy Computing; Yang Liu, Nanyang Technological University; Yixiang Chen, East China Normal University, Shanghai Key Laboratory of Trustworthy Computing

**Abstract:**

OpenZeppelin is a popular framework for building smart contracts. It provides common libraries (e.g., SafeMath), implementations of Ethereum standards (e.g., ERC20), and reusable components for access control and upgradability. However, unlike traditional software libraries, which are typically imported as static linking libraries or dynamic loading libraries, OpenZeppelin is utilized by Solidity contracts in the form of source code. As a result, developers often make custom modifications to their copies of OpenZeppelin code, which may lead to unintended security consequences.

In this paper, we conduct the first systematic study on the security of OpenZeppelin code used in real-world contracts. Specifically, we focus on the security checks in the official OpenZeppelin library and examine whether they are faithfully enforced in the relevant OpenZeppelin functions of real contracts. To this end, we propose a novel tool named ZepScope that comprises two components: MINER and CHECKER. First, MINER analyzes the official OpenZeppelin functions to extract the facts of explicit checks (i.e., the checks defined within the functions) and implicit checks (i.e., the conditions of calling the functions). Second, based on the facts extracted by MINER, CHECKER examines real contracts to identify their OpenZeppelin functions, match their checks with those in the facts, and validate the consequences for those inconsistent checks. By overcoming multiple challenges in developing ZepScope, we obtain not only the first taxonomy of OpenZeppelin checks but also the comprehensive results of checking the top 35,882 contracts from three mainstream blockchains.



# Blockchain II

**Title:**

zkCross: A Novel Architecture for Cross-Chain Privacy-Preserving Auditing

**Authors:**

Yihao Guo, Minghui Xu, Xiuzhen Cheng, and Dongxiao Yu, Shandong University; Wangjie Qiu, Beihang University; Gang Qu, University of Maryland; Weibing Wang and Mingming Song, Cloud Inspur Information Technology Co., Ltd.

**Abstract:**

One of the key areas of focus in blockchain research is how to realize privacy-preserving auditing without sacrificing the system's security and trustworthiness. However, simultaneously achieving auditing and privacy protection, two seemingly contradictory objectives, is challenging because an auditing system would require transparency and accountability which might create privacy and security vulnerabilities. This becomes worse in cross-chain scenarios, where the information silos from multiple chains further complicate the problem. In this paper, we identify three important challenges in cross-chain privacy-preserving auditing, namely Cross-chain Linkability Exposure (CLE), Incompatibility of Privacy and Auditing (IPA), and Full Auditing Inefficiency (FAI). To overcome these challenges, we propose zkCross, which is a novel two-layer cross-chain architecture equipped with three cross-chain protocols to achieve privacy-preserving cross-chain auditing. Among these three protocols, two are privacy-preserving cross-chain protocols for transfer and exchange, respectively; the third one is an efficient cross-chain auditing protocol. These protocols are built on solid cross-chain schemes to guarantee privacy protection and audit efficiency. We implement zkCross on both local and cloud servers and perform comprehensive tests to validate that zkCross is well-suited for processing large-scale privacy-preserving auditing tasks. We evaluate the performance of the proposed protocols in terms of run time, latency, throughput, gas consumption, audit time, and proof size to demonstrate their practicality.



**Title:**

Pixel+ and Pixel++: Compact and Efficient Forward-Secure Multi-Signatures for PoS Blockchain Consensus

**Authors:**

Jianghong Wei, State Key Laboratory of Integrated Service Networks (ISN), Xidian University, and State Key Laboratory of Mathematical Engineering and Advanced Computing; Guohua Tian, State Key Laboratory of Integrated Service Networks (ISN), Xidian University; Ding Wang, College of Cyber Science, Nankai University; Fuchun Guo and Willy Susilo, School of Computing and Information Technology, University of Wollongong; Xiaofeng Chen, State Key Laboratory of Integrated Service Networks (ISN), Xidian University

**Abstract:**

Multi-signature schemes have attracted considerable attention in recent years due to their popular applications in PoS blockchains. However, the use of general multi-signature schemes poses a critical threat to the security of PoS blockchains once signing keys get corrupted. That is, after an adversary obtains enough signing keys, it can break the immutable nature of PoS blockchains by forking the chain and modifying the history from some point in the past. Forward-secure multi-signature (FS-MS) schemes can overcome this issue by periodically updating signing keys. The only FS-MS construction currently available is Drijvers et al's Pixel, which builds on pairing groups and only achieves forward security at the time period level.

In this work, we present new FS-MS constructions that either are free from pairing or capture forward security at the individual message level (i.e., fine-grained forward security). Our first construction Pixel+ works for a maximum number of time periods T. Pixel+ signatures consist of only one group element, and can be verified using two exponentiations. It is the first FS-MS from RSA assumption, and has 3.5x and 22.8x faster signing and verification than Pixel, respectively. Our second FS-MS construction Pixel++ is a pairing-based one. It immediately revokes the signing key's capacity of re-signing the message after creating a signature on this message, rather than at the end of the current time period. Thus, it provides more practical forward security than Pixel. On the other hand, Pixel++ is almost as efficient as Pixel in terms of signing and verification. Both Pixel+ and Pixel++ allow for non-interactive aggregation of signatures from independent signers and are proven to be secure in the random oracle model. In addition, they also support the aggregation of public keys, significantly reducing the storage overhead on PoS blockchains.

We demonstrate how to integrate Pixel+ and Pixel++ into PoS blockchains. As a proof-of-concept, we provide implementations of Pixel+ and Pixel++, and conduct several representative experiments to show that Pixel+ and Pixel++ have good concrete efficiency and are practical.



**Title:**

Max Attestation Matters: Making Honest Parties Lose Their Incentives in Ethereum PoS

**Authors:**

Mingfei Zhang, Shandong University; Rujia Li and Sisi Duan, Tsinghua University

**Abstract:**

We present staircase attack, the first attack on the incentive mechanism of the Proof-of-Stake (PoS) protocol used in Ethereum 2.0 beacon chain. Our attack targets the penalty of the incentive mechanism that penalizes inactive participation. Our attack can make honest validators suffer from penalties, even if they strictly follow the specification of the protocol. We show both theoretically and experimentally that if the adversary controls 29.6% stake in a moderate-size system, the attack can be launched continuously, so eventually all honest validators will lose their incentives. In contrast, the adversarial validators can still receive incentives, and the stake owned by the adversary can eventually exceed the one-third threshold (system assumption), posing a threat to the security properties of the system.

In practice, the attack feasibility is directly related to two parameters: the number of validators and the parameter MAX_ATTESTATION, the maximum number of attestations (i.e., votes) that can be included in each block. We further modify our attack such that, with the current system setup (900,000 validators and MAX_ATTESTATION=128), our attack can be launched continuously with a probability of 80.25%. As a result, the incentives any honest validator receives are only 28.9% of its fair share.



**Title:**

Sprints: Intermittent Blockchain PoW Mining

**Authors:**

Michael Mirkin, Technion; Lulu Zhou, Yale University; Ittay Eyal, Technion; Fan Zhang, Yale University

**Abstract:**

Cryptocurrencies and decentralized platforms have been rapidly gaining traction since Nakamoto's discovery of Bitcoin's blockchain protocol. Prominent systems use Proof of Work (PoW) to achieve unprecedented security for digital assets. However, the significant carbon footprint due to the manufacturing and operation of PoW mining hardware is leading policymakers to consider stark measures against them and various systems to explore alternatives. But these alternatives imply stepping away from key security aspects of PoW.

We present Sprints, a blockchain protocol that achieves almost the same security guarantees as PoW blockchains, but with an order-of-magnitude lower carbon footprint while increasing the number of mining rigs by a factor 1.27x. Our conservative estimate of environmental footprint uses common metrics, taking into account both power and hardware. To achieve this reduction, Sprints forces miners to mine intermittently. It interleaves Proof of Delay (PoD, e.g., using a Verifiable Delay Function) and PoW, where only the latter bears a significant resource expenditure. We prove that in Sprints the attacker's success probability is the same as that of legacy PoW. To evaluate practical performance, we analyze the effect of shortened PoW duration, showing a minor reduction in resilience (49% instead of 50%). We confirm the results with a full implementation using 100 patched Bitcoin clients in an emulated network.


# Zero-Knowledge Proof I

**Title:**

Two Shuffles Make a RAM: Improved Constant Overhead Zero Knowledge RAM

**Authors:**

Yibin Yang, Georgia Institute of Technology; David Heath, University of Illinois Urbana-Champaign

**Abstract:**

We optimize Zero Knowledge (ZK) proofs of statements expressed as RAM programs over arithmetic values. Our arithmetic-circuit-based read/write memory uses only 4 input gates and 6 multiplication gates per memory access. This is an almost 3× total gate improvement over prior state of the art (Delpech de Saint Guilhem et al., SCN'22).

We implemented our memory in the context of ZK proofs based on vector oblivious linear evaluation (VOLE), and we further optimized based on techniques available in the VOLE setting. Our experiments show that (1) our total runtime improves over that of the prior best VOLE-ZK RAM (Franzese et al., CCS'21) by 2-20× and (2) on a typical hardware setup, we can achieve ≈ 600K RAM accesses per second.

We also develop improved read-only memory and set ZK data structures. These are used internally in our read/write memory and improve over prior work.



**Title:**

Notus: Dynamic Proofs of Liabilities from Zero-knowledge RSA Accumulators

**Authors:**

Jiajun Xin, Arman Haghighi, Xiangan Tian, and Dimitrios Papadopoulos, The Hong Kong University of Science and Technology

**Abstract:**

Proofs of Liabilities (PoL) allow an untrusted prover to commit to its liabilities towards a set of users and then prove independent users' amounts or the total sum of liabilities, upon queries by users or third-party auditors. This application setting is highly dynamic. User liabilities may increase/decrease arbitrarily and the prover needs to update proofs in epoch increments (e.g., once a day for a crypto-asset exchange platform). However, prior works mostly focus on the static case and trivial extensions to the dynamic setting open the system to windows of opportunity for the prover to under-report its liabilities and rectify its books in time for the next check, unless all users check their liabilities at all epochs. In this work, we develop Notus, the first dynamic PoL system for general liability updates that avoids this issue. Moreover, it achieves O(1) query proof size, verification time, and auditor overhead-per-epoch. The core building blocks underlying Notus are a novel zero-knowledge (and SNARK-friendly) RSA accumulator and a corresponding zero-knowledge MultiSwap protocol, which may be of independent interest. We then propose optimizations to reduce the prover's update overhead and make Notus scale to large numbers of users (10^6 in our experiments). Our results are very encouraging, e.g., it takes less than 2ms to verify a user's liability and the proof size is 256 Bytes. On the prover side, deploying Notus on a cloud-based testbed with 256 cores and exploiting parallelism, it takes about 3 minutes to perform the complete epoch update, after which all proofs have already been computed.



**Title:**

Practical Security Analysis of Zero-Knowledge Proof Circuits

**Authors:**

Hongbo Wen, University of California, Santa Barbara; Jon Stephens, The University of Texas at Austin and Veridise; Yanju Chen, University of California, Santa Barbara; Kostas Ferles, Veridise; Shankara Pailoor, The University of Texas at Austin and Veridise; Kyle Charbonnet, Ethereum Foundation; Isil Dillig, The University of Texas at Austin and Veridise; Yu Feng, University of California, Santa Barbara, and Veridise

**Abstract:**

As privacy-sensitive applications based on zero-knowledge proofs (ZKPs) gain increasing traction, there is a pressing need to detect vulnerabilities in ZKP circuits. This paper studies common vulnerabilities in Circom (the most popular domain-specific language for ZKP circuits) and describes a static analysis framework for detecting these vulnerabilities. Our technique operates over an abstraction called the circuit dependence graph (CDG) that captures key properties of the circuit and allows expressing semantic vulnerability patterns as queries over the CDG abstraction. We have implemented 9 different detectors using this framework and performed an experimental evaluation on over 258 circuits from popular Circom projects on GitHub. According to our evaluation, these detectors can identify vulnerabilities, including previously unknown ones, with high precision and recall.



**Title:**

Formalizing Soundness Proofs of Linear PCP SNARKs

**Authors:**

Bolton Bailey and Andrew Miller, University of Illinois at Urbana-Champaign

**Abstract:**

Succinct Non-interactive Arguments of Knowledge (SNARKs) have seen interest and development from the cryptographic community over recent years, and there are now constructions with very small proof size designed to work well in practice. A SNARK protocol can only be widely accepted as secure, however, if a rigorous proof of its security properties has been vetted by the community. Even then, it is sometimes the case that these security proofs are flawed, and it is then necessary for further research to identify these flaws and correct the record.

To increase the rigor of these proofs, we create a formal framework in the Lean theorem prover for representing a widespread subclass of SNARKs based on linear PCPs. We then describe a decision procedure for checking the soundness of SNARKs in this class. We program this procedure and use it to formalize the soundness proof of several different SNARK constructions, including the well-known Groth '16.



# Zero-Knowledge Proof II

**Title:**

Election Eligibility with OpenID: Turning Authentication into Transferable Proof of Eligibility

**Authors:**

Véronique Cortier, Alexandre Debant, Anselme Goetschmann, and Lucca Hirschi, Université de Lorraine, CNRS, Inria, LORIA, France

**Abstract:**

Eligibility checks are often abstracted away or omitted in voting protocols, leading to situations where the voting server can easily stuff the ballot box. One reason for this is the difficulty of bootstraping the authentication material for voters without relying on trusting the voting server.

In this paper, we propose a new protocol that solves this problem by building on OpenID, a widely deployed authentication protocol. Instead of using it as a standard authentication means, we turn it into a mechanism that delivers transferable proofs of eligibility. Using zk-SNARK proofs, we show that this can be done without revealing any compromising information, in particular, protecting everlasting privacy. Our approach remains efficient and can easily be integrated into existing protocols, as we have done for the Belenios voting protocol. We provide a full-fledged proof of concept along with benchmarks showing our protocol could be realistically used in large-scale elections.



**Title:**

Reef: Fast Succinct Non-Interactive Zero-Knowledge Regex Proofs

**Authors:**

Sebastian Angel, Eleftherios Ioannidis, and Elizabeth Margolin, University of Pennsylvania; Srinath Setty, Microsoft Research; Jess Woods, University of Pennsylvania

**Abstract:**

This paper presents Reef, a system for generating publicly verifiable succinct non-interactive zero-knowledge proofs that a committed document matches or does not match a regular expression. We describe applications such as proving the strength of passwords, the provenance of email despite redactions, the validity of oblivious DNS queries, and the existence of mutations in DNA. Reef supports the Perl Compatible Regular Expression syntax, including wildcards, alternation, ranges, capture groups, Kleene star, negations, and lookarounds. Reef introduces a new type of automata, Skipping Alternating Finite Automata (SAFA), that skips irrelevant parts of a document when producing proofs without undermining soundness, and instantiates SAFA with a lookup argument. Our experimental evaluation confirms that Reef can generate proofs for documents with 32M characters; the proofs are small and cheap to verify (under a second).



**Title:**

Scalable Zero-knowledge Proofs for Non-linear Functions in Machine Learning

**Authors:**

Meng Hao, Hanxiao Chen, and Hongwei Li, School of Computer Science and Engineering, University of Electronic Science and Technology of China; Chenkai Weng, Northwestern University; Yuan Zhang and Haomiao Yang, School of Computer Science and Engineering, University of Electronic Science and Technology of China; Tianwei Zhang, Nanyang Technological University

**Abstract:**

Zero-knowledge (ZK) proofs have been recently explored for the integrity of machine learning (ML) inference. However, these protocols suffer from high computational overhead, with the primary bottleneck stemming from the evaluation of non-linear functions. In this paper, we propose the first systematic ZK proof framework for non-linear mathematical functions in ML using the perspective of table lookup. The key challenge is that table lookup cannot be directly applied to non-linear functions in ML since it would suffer from inefficiencies due to the intolerably large table. Therefore, we carefully design several important building blocks, including digital decomposition, comparison, and truncation, such that they can effectively utilize table lookup with a quite small table size while ensuring the soundness of proofs. Based on these building blocks, we implement complex mathematical operations and further construct ZK proofs for current mainstream non-linear functions in ML such as ReLU, sigmoid, and normalization. The extensive experimental evaluation shows that our framework achieves 50∼179× runtime improvement compared to the state-of-the-art work, while maintaining a similar level of communication efficiency.



**Title:**

ZKSMT: A VM for Proving SMT Theorems in Zero Knowledge

**Authors:**

Daniel Luick, John C. Kolesar, and Timos Antonopoulos, Yale University; William R. Harris and James Parker, Galois, Inc.; Ruzica Piskac, Yale University; Eran Tromer, Boston University; Xiao Wang and Ning Luo, Northwestern University

**Abstract:**

Verification of program safety is often reducible to proving the unsatisfiability (i.e., validity) of a formula in Satisfiability Modulo Theories (SMT): Boolean logic combined with theories that formalize arbitrary first-order fragments. Zero-knowledge (ZK) proofs allow SMT formulas to be validated without revealing the underlying formulas or their proofs to other parties, which is a crucial building block for proving the safety of proprietary programs. Recently, Luo et al. (CCS 2022) studied the simpler problem of proving the unsatisfiability of pure Boolean formulas but does not support proofs generated by SMT solvers. This work presents ZKSMT, a novel framework for proving the validity of SMT formulas in ZK. We design a virtual machine (VM) tailored to efficiently represent the verification process of SMT validity proofs in ZK. Our VM can support the vast majority of popular theories when proving program safety while being complete and sound. To demonstrate this, we instantiate the commonly used theories of equality and linear integer arithmetic in our VM with theory-specific optimizations for proving them in ZK. ZKSMT achieves high practicality even when running on realistic SMT formulas generated by Boogie, a common tool for software verification. It achieves a three-order-of-magnitude improvement compared to a baseline that executes the proof verification code in a general ZK system.



**Title:**

SoK: What Don't We Know? Understanding Security Vulnerabilities in SNARKs

**Authors:**

Stefanos Chaliasos, Imperial College London; Jens Ernstberger, Technical University of Munich; David Theodore, Ethereum Foundation; David Wong, zkSecurity; Mohammad Jahanara, Scroll Foundation; Benjamin Livshits, Imperial College London & Matter Labs

**Abstract:**

Zero-knowledge proofs (ZKPs) have evolved from being a theoretical concept providing privacy and verifiability to having practical, real-world implementations, with SNARKs (Succinct Non-Interactive Argument of Knowledge) emerging as one of the most significant innovations. Prior work has mainly focused on designing more efficient SNARK systems and providing security proofs for them. Many think of SNARKs as "just math," implying that what is proven to be correct and secure is correct in practice. In contrast, this paper focuses on assessing end-to-end security properties of real-life SNARK implementations. We start by building foundations with a system model and by establishing threat models and defining adversarial roles for systems that use SNARKs. Our study encompasses an extensive analysis of 141 actual vulnerabilities in SNARK implementations, providing a detailed taxonomy to aid developers and security researchers in understanding the security threats in systems employing SNARKs. Finally, we evaluate existing defense mechanisms and offer recommendations for enhancing the security of SNARK-based systems, paving the way for more robust and reliable implementations in the future.



# Cryptographic Protocols I: Multi-Party Computation

**Title:**

Scalable Multi-Party Computation Protocols for Machine Learning in the Honest-Majority Setting

**Authors:**

Fengrun Liu, University of Science and Technology of China & Shanghai Qi Zhi Institute; Xiang Xie, Shanghai Qi Zhi Institute & PADO Labs; Yu Yu, Shanghai Jiao Tong University & State Key Laboratory of Cryptology

**Abstract:**

In this paper, we present a novel and scalable multi-party computation (MPC) protocol tailored for privacy-preserving machine learning (PPML) with semi-honest security in the honest-majority setting. Our protocol utilizes the Damgaard-Nielsen (Crypto '07) protocol with Mersenne prime fields. By leveraging the special properties of Mersenne primes, we are able to design highly efficient protocols for securely computing operations such as truncation and comparison. Additionally, we extend the two-layer multiplication protocol in ATLAS (Crypto '21) to further reduce the round complexity of operations commonly used in neural networks.

Our protocol is very scalable in terms of the number of parties involved. For instance, our protocol completes the online oblivious inference of a 4-layer convolutional neural network with 63 parties in 0.1 seconds and 4.6 seconds in the LAN and WAN settings, respectively. To the best of our knowledge, this is the first fully implemented protocol in the field of PPML that can successfully run with such a large number of parties. Notably, even in the three-party case, the online phase of our protocol is more than 1.4x faster than the Falcon (PETS '21) protocol.



**Title:**

Lightweight Authentication of Web Data via Garble-Then-Prove

**Authors:**

Xiang Xie, PADO Labs; Kang Yang, State Key Laboratory of Cryptology; Xiao Wang, Northwestern University; Yu Yu, Shanghai Jiao Tong University and Shanghai Qi Zhi Institute

**Abstract:**

Transport Layer Security (TLS) establishes an authenticated and confidential channel to deliver data for almost all Internet applications. A recent work (Zhang et al., CCS'20) proposed a protocol to prove the TLS payload to a third party, without any modification of TLS servers, while ensuring the privacy and originality of the data in the presence of malicious adversaries. However, it required maliciously secure Two-Party Computation (2PC) for generic circuits, leading to significant computational and communication overhead.

This paper proposes the garble-then-prove technique to achieve the same security requirement without using any heavy mechanism like generic malicious 2PC. Our end-to-end implementation shows 14x improvement in communication and an order of magnitude improvement in computation over the state-of-the-art protocol. We also show worldwide performance when using our protocol to authenticate payload data from Coinbase and Twitter APIs. Finally, we propose an efficient gadget to privately convert the above authenticated TLS payload to additively homomorphic commitments so that the properties of the payload can be proven efficiently using zkSNARKs.



**Title:**

Holding Secrets Accountable: Auditing Privacy-Preserving Machine Learning

**Authors:**

Hidde Lycklama, ETH Zurich; Alexander Viand, Intel Labs; Nicolas Küchler, ETH Zurich; Christian Knabenhans, EPFL; Anwar Hithnawi, ETH Zurich

**Abstract:**

Recent advancements in privacy-preserving machine learning are paving the way to extend the benefits of ML to highly sensitive data that, until now, has been hard to utilize due to privacy concerns and regulatory constraints. Simultaneously, there is a growing emphasis on enhancing the transparency and accountability of ML, including the ability to audit deployments for aspects such as fairness, accuracy and compliance. Although ML auditing and privacy-preserving machine learning have been extensively researched, they have largely been studied in isolation. However, the integration of these two areas is becoming increasingly important. In this work, we introduce Arc, an MPC framework designed for auditing privacy-preserving machine learning. Arc cryptographically ties together the training, inference, and auditing phases to allow robust and private auditing. At the core of our framework is a new protocol for efficiently verifying inputs against succinct commitments. We evaluate the performance of our framework when instantiated with our consistency protocol and compare it to hashing-based and homomorphic-commitment-based approaches, demonstrating that it is up to 10^4× faster and up to 10^6× more concise.



**Title:**

Secure Account Recovery for a Privacy-Preserving Web Service

**Authors:**

Ryan Little, Boston University; Lucy Qin, Georgetown University; Mayank Varia, Boston University

**Abstract:**

If a web service is so secure that it does not even know—and does not want to know—the identity and contact info of its users, can it still offer account recovery if a user forgets their password? This paper is the culmination of the authors' work to design a cryptographic protocol for account recovery for use by a prominent secure matching system: a web-based service that allows survivors of sexual misconduct to become aware of other survivors harmed by the same perpetrator. In such a system, the list of account-holders must be safeguarded, even against the service provider itself.

In this work, we design an account recovery system that, on the surface, appears to follow the typical workflow: the user types in their email address, receives an email containing a one-time link, and answers some security questions. Behind the scenes, the defining feature of our recovery system is that the service provider can perform email-based account validation without knowing, or being able to learn, a list of users' email addresses. Our construction uses standardized cryptography for most components, and it has been deployed in production at the secure matching system.

As a building block toward our main construction, we design a new cryptographic primitive that may be of independent interest: an oblivious pseudorandom function that can either have a fully-private input or a partially-public input, and that reaches the same output either way. This primitive allows us to perform online rate limiting for account recovery attempts, without imposing a bound on the creation of new accounts. We provide an open-source implementation of this primitive and provide evaluation results showing that the end-to-end interaction time takes 8.4-60.4 ms in fully-private input mode and 3.1-41.2 ms in partially-public input mode.



# Cryptographic Protocols II

**Title:**

Rabbit-Mix: Robust Algebraic Anonymous Broadcast from Additive Bases

**Authors:**

Chongwon Cho and Samuel Dittmer, Stealth Software Technologies Inc.; Yuval Ishai, Technion; Steve Lu, Stealth Software Technologies Inc.; Rafail Ostrovsky, UCLA

**Abstract:**

We present Rabbit-Mix, a robust algebraic mixing-based anonymous broadcast protocol in the client-server model. Rabbit-Mix is the first practical sender-anonymous broadcast protocol satisfying both robustness and 100% message delivery assuming a (strong) honest majority of servers. It presents roughly 3x improvement in comparison to Blinder (CCS 2020), a previous anonymous broadcast protocol in the same model, in terms of the number of algebraic operations and communication, while at the same time eliminating the non-negligible failure probability of Blinder. To obtain these improvements, we combine the use of Newton's identities for mixing with a novel way of exploiting an algebraic structure in the powers of field elements, based on an {\em additive 2-basis}, to compactly encode and decode client messages. We also introduce a simple and efficient distributed protocol to verify the well-formedness of client input encodings, which should consist of shares of multiple arithmetic progressions tied together.



**Title:**

PerfOMR: Oblivious Message Retrieval with Reduced Communication and Computation

**Authors:**

Zeyu Liu, Yale University; Eran Tromer, Boston University; Yunhao Wang, Yale University

**Abstract:**

Anonymous message delivery, as in privacy-preserving blockchain and private messaging applications, needs to protect recipient metadata: eavesdroppers should not be able to link messages to their recipients. This raises the question: how can untrusted servers assist in delivering the pertinent messages to each recipient, without learning which messages are addressed to whom?

Recent work constructed Oblivious Message Retrieval (OMR) protocols that outsource the message detection and retrieval in a privacy-preserving way, using homomorphic encryption. Their construction exhibits significant costs in computation per message scanned (∼0.1 second), as well as in the size of the associated messages (∼1kB overhead) and public keys (∼132kB).

This work constructs more efficient OMR schemes, by replacing the LWE-based clue encryption of prior works with a Ring-LWE variant, and utilizing the resulting flexibility to improve several components of the scheme. We thus devise, analyze, and benchmark two protocols:

The first protocol focuses on improving the detector runtime, using a new retrieval circuit that can be homomorphically evaluated 15x faster than the prior work.

The second protocol focuses on reducing the communication costs, by designing a different homomorphic decryption circuit that allows the parameter of the Ring-LWE encryption to be set such that the public key size is about 235x smaller than the prior work, and the message size is roughly 1.6x smaller. The runtime of this second construction is ∼40.0ms per message, still more than 2.5x faster than prior works.



**Title:**

Fast RS-IOP Multivariate Polynomial Commitments and Verifiable Secret Sharing

**Authors:**

Zongyang Zhang, Weihan Li, Yanpei Guo, and Kexin Shi, Beihang University; Sherman S. M. Chow, The Chinese University of Hong Kong; Ximeng Liu, Fuzhou University; Jin Dong, Beijing Academy of Blockchain and Edge Computing

**Abstract:**

Supporting proofs of evaluations, polynomial commitment schemes (PCS) are crucial in secure distributed systems. Schemes based on fast Reed–Solomon interactive oracle proofs (RS-IOP) of proximity have recently emerged, offering transparent setup, plausible post-quantum security, efficient operations, and, notably, sublinear proof size and verification. Manifesting a new paradigm, PCS with one-to-many proof can enhance the performance of (asynchronous) verifiable secret sharing ((A)VSS), a cornerstone in distributed computing, for proving multiple evaluations to multiple verifiers. Current RS-IOP-based multivariate PCS, including HyperPlonk (Eurocrypt '23) and Virgo (S&P '20), however, only offer quasi-linear prover complexity in the polynomial size.

We propose PolyFRIM, a fast RS-IOP-based multivariate PCS with optimal linear prover complexity, 5-25× faster than prior arts while ensuring competent proof size and verification. Heeding the challenging absence of FFT circuits for multivariate evaluation, PolyFRIM surpasses Zhang et al.'s (Usenix Sec. '22) one-to-many univariate PCS, accelerating proving by 4-7× and verification by 2-4× with 25% shorter proof. Leveraging PolyFRIM, we propose an AVSS scheme FRISS with a better efficiency tradeoff than prior arts from multivariate PCS, including Bingo (Crypto '23) and Haven (FC '21).



**Title:**

Abuse Reporting for Metadata-Hiding Communication Based on Secret Sharing

**Authors:**

Saba Eskandarian, University of North Carolina at Chapel Hill

**Abstract:**

As interest in metadata-hiding communication grows in both research and practice, a need exists for stronger abuse reporting features on metadata-hiding platforms. While message franking has been deployed on major end-to-end encrypted platforms as a lightweight and effective abuse reporting feature, there is no comparable technique for metadata-hiding platforms. Existing efforts to support abuse reporting in this setting, such as asymmetric message franking or the Hecate scheme, require order of magnitude increases in client and server computation or fundamental changes to the architecture of messaging systems. As a result, while metadata-hiding communication inches closer to practice, critical content moderation concerns remain unaddressed.

This paper demonstrates that, for broad classes of metadata-hiding schemes, lightweight abuse reporting can be deployed with minimal changes to the overall architecture of the system. Our insight is that much of the structure needed to support abuse reporting already exists in these schemes. By taking a non-generic approach, we can reuse this structure to achieve abuse reporting with minimal overhead. In particular, we show how to modify schemes based on secret sharing user inputs to support a message franking-style protocol. Compared to prior work, our shared franking technique more than halves the time to prepare a franked message and gives order of magnitude reductions in server-side message processing times, as well as in the time to decrypt a message and verify a report.



**Title:**

SOAP: A Social Authentication Protocol

**Authors:**

Felix Linker and David Basin, Department of Computer Science, ETH Zurich

**Abstract:**

Social authentication has been suggested as a usable authentication ceremony to replace manual key authentication in messaging applications. Using social authentication, chat partners authenticate their peers using digital identities managed by identity providers. In this paper, we formally define social authentication, present a protocol called SOAP that largely automates social authentication, formally prove SOAP's security, and demonstrate SOAP's practicality in two prototypes. One prototype is web-based, and the other is implemented in the open-source Signal messaging application.

Using SOAP, users can significantly raise the bar for compromising their messaging accounts. In contrast to the default security provided by messaging applications such as Signal and WhatsApp, attackers must compromise both the messaging account and all identity provider-managed identities to attack a victim. In addition to its security and automation, SOAP is straightforward to adopt as it is built on top of the well-established OpenID Connect protocol.

# Cryptographic Protocols III

**Title:**

POPSTAR: Lightweight Threshold Reporting with Reduced Leakage

**Authors:**

Hanjun Li, Sela Navot, and Stefano Tessaro, University of Washington

**Abstract:**

This paper proposes POPSTAR, a new lightweight protocol for the private computation of heavy hitters, also known as a private threshold reporting system. In such a protocol, the users provide input measurements, and a report server learns which measurements appear more than a pre-specified threshold. POPSTAR follows the same architecture as STAR (Davidson et al., CCS 2022) by relying on a helper randomness server in addition to a main server computing the aggregate heavy hitter statistics. While STAR is extremely lightweight, it leaks a substantial amount of information, consisting of an entire histogram of the provided measurements (but only reveals the actual measurements that appear beyond the threshold). POPSTAR shows that this leakage can be reduced at a modest cost (∼7× longer aggregation time). Our leakage is closer to that of Poplar (Boneh et al., S&P 2021), which relies however on distributed point functions and a different model which requires interactions of two non-colluding servers to compute the heavy hitters.



**Title:**

Privacy-Preserving Data Aggregation with Public Verifiability Against Internal Adversaries

**Authors:**

Marco Palazzo and Florine W. Dekker, Cyber Security Group, Delft University of Technology; Alessandro Brighente, SPRITZ Security and Privacy Research Group, Università di Padova; Mauro Conti, SPRITZ Security and Privacy Research Group, Università di Padova & Cyber Security Group, Delft University of Technology; Zekeriya Erkin, Cyber Security Group, Delft University of Technology

**Abstract:**

We consider the problem of publicly verifiable privacy-preserving data aggregation in the presence of a malicious aggregator colluding with malicious users. State-of-the-art solutions either split the aggregator into two parties under the assumption that they do not collude, or require many rounds of interactivity and have non-constant verification time.

In this work, we propose mPVAS, the first publicly verifiable privacy-preserving data aggregation protocol that allows arbitrary collusion, without relying on trusted third parties during execution, where verification runs in constant time. We also show three extensions to mPVAS: mPVAS+, for improved communication complexity, mPVAS-IV, for the identification of malicious users, and mPVAS-UD, for graceful handling of reduced user availability without the need to redo the setup. We show that our schemes achieve the desired confidentiality, integrity, and authenticity. Finally, through both theoretical and experimental evaluations, we show that our schemes are feasible for real-world applications.



**Title:**

PINE: Efficient Verification of a Euclidean Norm Bound of a Secret-Shared Vector

**Authors:**

Guy N. Rothblum, Apple; Eran Omri, Ariel University and Ariel Cyber Innovation Center; Junye Chen and Kunal Talwar, Apple

**Abstract:**

Secure aggregation of high-dimensional vectors is a fundamental primitive in federated statistics and learning. A two-server system such as PRIO allows for scalable aggregation of secret-shared vectors. Adversarial clients might try to manipulate the aggregate, so it is important to ensure that each (secret-shared) contribution is well-formed. In this work, we focus on the important and well-studied goal of ensuring that each contribution vector has bounded Euclidean norm. Existing protocols for ensuring bounded-norm contributions either incur a large communication overhead, or only allow for approximate verification of the norm bound. We propose Private Inexpensive Norm Enforcement (PINE): a new protocol that allows exact norm verification with little communication overhead. For high-dimensional vectors, our approach has a communication overhead of a few percent, compared to the 16-32x overhead of previous approaches.



**Title:**

DaCapo: Automatic Bootstrapping Management for Efficient Fully Homomorphic Encryption

**Authors:**

Seonyoung Cheon, Yongwoo Lee, Dongkwan Kim, and Ju Min Lee, Yonsei University; Sunchul Jung and Taekyung Kim, CryptoLab. Inc.; Dongyoon Lee, Stony Brook University; Hanjun Kim, Yonsei University

**Abstract:**

By supporting computation on encrypted data, fully homomorphic encryption (FHE) offers the potential for privacy-preserving computation offloading. However, its applicability is constrained to small programs because each FHE multiplication increases the scale of a ciphertext with a limited scale capacity. By resetting the accumulated scale, bootstrapping enables a longer FHE multiplication chain. Nonetheless, manual bootstrapping placement poses a significant programming burden to avoid scale overflow from insufficient bootstrapping or the substantial computational overhead of unnecessary bootstrapping. Additionally, the bootstrapping placement affects costs of FHE operations due to changes in scale management, further complicating the overall management process.

This work proposes DaCapo, the first automatic bootstrapping management compiler. Aiming to reduce bootstrapping counts, DaCapo analyzes live-out ciphertexts at each program point and identifies candidate points for inserting bootstrapping operations. DaCapo estimates the FHE operation latencies under different scale management scenarios for each bootstrapping placement plan at each candidate point, and decides the bootstrapping placement plan with minimal latency. This work evaluates DaCapo with deep learning models that existing FHE compilers cannot compile due to a lack of bootstrapping support. The evaluation achieves 1.21x speedup on average compared to manually implemented FHE programs.

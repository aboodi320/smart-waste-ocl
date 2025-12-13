Project Charter
Project Title: Online Continual Learning–Based Smart Waste Classification System
Program/Context: İstanbul Aydın Üniversitesi
Project Duration: 8 months
Project Leader: Abdulrahman Badr-aldeen
Team Members: Merve Çakır, Ahmad Chamsiddin, Adnan Faleh
Academic Advisor : Dr. Roaa Ali Abdullah Mohammedqasem

1) Background & Problem Statement
Urban waste is increasing, and smart waste classification using CNNs can improve recycling efficiency. However, when new waste categories appear in real time, models may suffer catastrophic forgetting, reducing performance on previously learned categories. This project targets that gap by applying Online Continual Learning (OCL) on an embedded prototype to improve real-world usability.

2) Purpose / Business Case
Developing an embedded smart waste classification prototype with OCL is expected to:
•	Improve recycling quality and efficiency in smart-city contexts
•	Reduce operational cost via better sorting
•	Provide a research-grade prototype that can be exhibited and potentially transitioned toward commercialization pathways (e.g., future startup / BiGG direction)

3) Goals & Measurable Objectives (SMART)
Primary Goal: Build an embedded system that classifies core waste categories and adapts to new categories while reducing forgetting.
Measurable objectives (project KPIs):
•	Classification Accuracy: achieve at least the base target used in your risk plan (≥ ~84% threshold; aim higher)
•	Forgetting Rate: quantify and minimize after introducing new categories
•	Real-time Performance: measure inference latency (ms)
•	Edge Resource Use: track CPU + RAM usage on Raspberry Pi
•	Algorithm Comparison: ER vs LwF vs A-GEM across accuracy/forgetting/resources

4) Scope
In Scope
•	Data preparation (TrashNet preprocessing + augmentation)
•	Model selection and fine-tuning (MobileNetV3)
•	Embedded prototype build: Raspberry Pi + camera + ultrasonic + weight sensors
•	OCL integration: Experience Replay (ER), Learning without Forgetting (LwF), A-GEM
•	Evaluation: accuracy/precision/recall/F1 + forgetting + latency + CPU/RAM profiling
•	Final deployment + live demonstration
Out of Scope
•	Full-scale municipal deployment (production system)
•	Creating a commercial product (only prototype + feasibility evidence)
•	Large custom dataset collection beyond defined approach (unless approved via change control)

5) Key Deliverables
1.	Preprocessed dataset pipeline (resize/normalize/augment)
2.	Fine-tuned MobileNetV3 model + TFLite conversion for edge
3.	Integrated embedded prototype (Pi + camera + sensors + inference)
4.	OCL-enabled system (ER/LwF/A-GEM running on device)
5.	Evaluation report (metrics + plots + comparison)
6.	Final demo + documentation (report + GitHub repo structure)

6) High-Level Timeline (Milestones)
•	Jan 2026: Data collection + preprocessing
•	Feb–Mar 2026: Model selection + fine-tuning
•	Apr–May 2026: Hardware/software integration + deployment to Pi
•	Jun 2026: OCL algorithms integration
•	Jul 2026: Testing & evaluation
•	Aug 2026: Final deployment + demonstration

7) Stakeholders
•	Primary Stakeholders: Project team + academic advisor
•	Secondary Stakeholders: İstanbul Aydın University (labs/library), potential smart-city ecosystem, recycling stakeholders (conceptual)

8) Assumptions
•	Raspberry Pi + sensors and lab access are available as planned
•	TrashNet is sufficient for initial base categories
•	Selected OCL algorithms can be adapted to edge constraints with reasonable buffer sizes/optimization

9) Constraints
•	Limited compute/memory on edge device
•	Fixed overall duration (8 months)
•	Team availability (academic schedule)

10) Risks (Top) & Mitigations
•	Accuracy below threshold: switch to EfficientNet alternative
•	Sensor communication issues: replace sensor / use recorded sensor values temporarily
•	Pi overload: offload heavy computation to cloud (edge computing approach)
•	Camera image quality issues: capture multiple frames, auto-select best frame
•	System crash during live demo: revert to last stable checkpoint and troubleshoot

11) Budget / Resources (High Level)
•	Existing resources: university library + mechatronics lab + Colab/TFLite environment
•	Hardware: Raspberry Pi, camera module, ultrasonic + weight sensors 
12) Approval & Authority
Project Leader Authority: assigns tasks, manages schedule, ensures documentation and progress tracking.
Advisor Authority: validates scientific direction, approves major methodological changes.
Charter Acceptance: Project starts formally upon advisor + team acknowledgment (and program acceptance, if required).

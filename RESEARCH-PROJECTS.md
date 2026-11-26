# Research projects and foundations — Prabhash Nandan
Prepared 26 Nov 2026.

## The one story these three projects tell
My undergraduate work has three threads — quantum machine learning, real-time
computer vision for assistive technology, and digital twins for agriculture
(IEEE DigitalTwin-Agri paper + KISHAN SAHCHAR follow-up). A master's in Machine
Intelligence / AI is where I want to learn how to do the first two rigorously
and keep applying them to real systems like the third.

## Forked foundations (study + extension base — NOT my own code)
Admissions reviewers can see forks are forks. Never present these as my own
projects. The honest, strong framing is: "I am building on X" +
the specific extension below, which connects to work that IS mine.

1. **PennyLane** — fork: https://github.com/PrabhashNandan78/pennylane
   Upstream: PennyLaneAI/pennylane (~3.5k stars, active)
   My link: my quantum deep learning framework work (Qiskit 1.4.2 + Aer);
   my brother and I are also exploring an AI + quantum idea together.
   Framing: "To test whether hybrid quantum–classical models offer any real
   advantage, I am benchmarking variational quantum classifiers in PennyLane
   against classical baselines on identical datasets — and reporting the
   negative results as carefully as the positive ones."
   Extension to actually do before interviews: one notebook, VQC vs logistic
   regression / SVM on a small dataset, results table in the fork on a branch.

2. **Ultralytics YOLO** — fork: https://github.com/PrabhashNandan78/ultralytics
   Upstream: ultralytics/ultralytics (~64k stars, active)
   My link: my vision-to-speech assistant for visually impaired users —
   YOLOv8 + OpenCV, real-time detection + audio feedback, phone camera input.
   Framing: "My assistive-vision system taught me that for a blind user,
   a late correct answer is a wrong answer — so I study the latency/accuracy
   trade-off of detection models on commodity hardware, not just mAP."
   Extension to actually do: latency benchmark table (phone-class hardware)
   for 2–3 YOLO model sizes, on a branch in the fork.

3. **Eclipse Ditto** — fork: https://github.com/PrabhashNandan78/ditto
   Upstream: eclipse-ditto/ditto (~955 stars, Eclipse Foundation)
   My link: DigitalTwin-Agri IEEE paper (Research Assistant) and the
   KISHAN SAHCHAR follow-up paper; my own TWIN / DIGITALTWIN_ML repos.
   Framing: "Our DigitalTwin-Agri prototype used a custom twin skeleton;
   mapping FarmTwin/SensorTwin onto Eclipse Ditto's production twin runtime
   is how I am learning what separates a research prototype from a system
   farmers could actually run."
   Extension to actually do: one Ditto "thing" modelled as a SensorTwin,
   documented on a branch in the fork.

## My own repos (these carry the real weight)
- DIGITALTWIN_ML + TWIN — the IEEE paper's code
- The quantum deep learning framework (from my resume)
- The vision-to-speech assistive system (YOLOv8 + OpenCV)

Rule: my own work and results lead; the forks appear only as
"foundations I am building on" for the future-work / why-this-programme
paragraph. That is both honest and the version a reviewer trusts.

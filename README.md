🛡️ Detecting and Mitigating Fake News
An AI Framework for Truth and Trust
📖 Overview
This project is more than a standard news classifier; it is a multi-disciplinary framework designed to bridge the gap between Machine Learning (AI) and Human Behavioral Science.

While the technical core is a high-precision pipeline for identifying REAL vs. FAKE news, the project’s ultimate goal is to understand human vulnerability to misinformation and explore whether users trust AI-driven truth scores more than human peer judgment.

✨ Key Achievements
High Precision: Achieved a 0.94 Precision score, critical for minimizing "False Censorship" where real news is wrongly flagged.

Model Accuracy: 94.16% overall accuracy using a Passive Aggressive Classifier.

Interpretability: Leveraged model feature weights to provide "Confidence Scores," helping users understand why an article was flagged (e.g., identifying sensationalist markers like "SHOCKING!" vs. "Official Statement").

🛠️ Tech Stack
Language: Python

NLP: NLTK, TF-IDF Vectorization (captures linguistic context and word importance).

Model: Passive Aggressive Classifier (optimized for high-speed text processing and large-scale data).

Data Handling: Pandas, NumPy.

🧪 Methodology & Research Goals
The project examines four pillars of digital trust:

Detection & Precision: Refining the model to match human judgment cues.

User Education: Providing transparent confidence scores to improve user honesty perception.

Vulnerability Analysis: Studying susceptibility across different demographic groups.

Trust Assessment: Testing if users exhibit higher trust in AI vs. human experts in identifying falsehoods.

📂 Repository Structure
detector_model.ipynb: End-to-end implementation including data cleaning, EDA, and training.

fake_news_detector_pipeline.pkl: The serialized "brain" of the AI, ready for production deployment.

Detecting and Mitigating Fake News.docx: Full technical and behavioral research report.

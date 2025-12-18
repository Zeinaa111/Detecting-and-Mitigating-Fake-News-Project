🛡️ Detecting and Mitigating Fake News: An AI Framework for Truth and Trust


📖 Overview
This project is more than a standard news classifier; it is a multi-disciplinary framework designed to bridge the gap between Machine Learning (AI) and Human Behavioral Science.

While the technical core is a high-precision pipeline for identifying REAL vs. FAKE news, the project’s ultimate goal is to understand human vulnerability to misinformation and explore whether users trust AI-driven truth scores more than human peer judgment.

✨ Key Achievements
High Precision: Achieved a 0.94 Precision score, which is critical for minimizing "False Censorship" where real news is wrongly flagged.

Model Accuracy: Reached an overall accuracy of 94.16% using a Passive Aggressive Classifier.

Interpretability: Leveraged model feature weights to provide "Confidence Scores," helping users understand why an article was flagged (e.g., identifying sensationalist markers like "SHOCKING!" vs. "Official Statement").

🛠️ Tech Stack
Language: Python

NLP: NLTK, TF-IDF Vectorization (captures linguistic context and word importance).

Model: Passive Aggressive Classifier (optimized for high-speed text processing and large-scale data).

Data Handling: Pandas, NumPy.

🧪 Methodology & Research Goals
The project examines four pillars of digital trust:

Detection & Precision: Refining the technical model for precision, optimized through user judgment cues.

User Education: Developing a model for improving the perception of honesty among users by providing transparent confidence scores.

Vulnerability Analysis: Studying the level of vulnerability of various demographic groups toward different forms of news.

Trust Assessment: Researching whether users exhibit higher trust in AI versus human experts when identifying false news on social media platforms.

📂 Repository Structure
detector_model.ipynb: End-to-end implementation including data cleaning, EDA, and training.

fake_news_detector_pipeline.pkl: The serialized "brain" of the AI, ready for production deployment.

Detecting and Mitigating Fake News.docx: Full technical and behavioral research report.

🚀 Future Work
Deployment: Integration of the model into a web service using the saved .pkl file.

External Study Execution: Implementation of human surveys using the Confidence Score variable to complete the Trust and Vulnerability studies.

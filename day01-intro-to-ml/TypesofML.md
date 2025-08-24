🔹 What is Machine Learning?

Definition: Machine Learning (ML) is a branch of Artificial Intelligence (AI) that enables systems to learn from data and improve their performance without being explicitly programmed.

Core Idea: Use data + algorithms → build models → make predictions/decisions.

Goal: Generalize well to unseen data.

💡 Example:

Predicting house prices based on features like area, location, and number of rooms.

Email spam detection (spam vs not spam).

🔹 Types of Machine Learning
1. Supervised Learning

Data: Uses labeled data (input X with known output y).

Goal: Learn a mapping function from input to output.

Tasks:

Classification → Predict categories (e.g., spam/not spam).

Regression → Predict continuous values (e.g., house prices).

Examples: Titanic survival prediction, stock price forecasting.

Algorithms: Linear Regression, Logistic Regression, Decision Trees, Random Forest, SVM.

2. Unsupervised Learning

Data: Uses unlabeled data (only input X).

Goal: Discover hidden patterns, structures, or relationships in data.

Tasks:

Clustering → Group similar data points (e.g., customer segmentation).

Dimensionality Reduction → Reduce features while keeping essential information (e.g., PCA, t-SNE).

Examples: Grouping customers by behavior, anomaly detection in networks.

Algorithms: K-Means, Hierarchical Clustering, PCA.

3. Reinforcement Learning (RL)

Data: No fixed dataset; learning happens through interaction with environment.

Goal: Agent learns to take actions to maximize cumulative reward.

Key Concepts: Agent, Environment, Actions, Rewards, Policy.

Examples:

AlphaGo beating humans at Go.

Self-driving cars optimizing driving strategies.

Algorithms: Q-Learning, Deep Q-Networks (DQN), Policy Gradient methods.

4. Other Variants (sometimes asked in interviews)

Semi-Supervised Learning → Mix of labeled + unlabeled data (common in medical imaging).

Self-Supervised Learning → Labels generated automatically from data (used in modern LLMs like GPT, BERT).

🔹 Key Differences
Feature	Supervised Learning	Unsupervised Learning	Reinforcement Learning
Data	Labeled (X + y)	Unlabeled (X only)	No fixed dataset; trial & error
Goal	Predict known output	Discover hidden patterns	Maximize reward
Output	Classification/Regression	Clusters, Reduced Features	Optimal Policy (best actions)
Examples	Spam detection, price prediction	Customer segmentation, PCA	AlphaGo, Robotics
🔹 Advantages & Limitations
✅ Supervised Learning

Advantages: High accuracy with enough data, easy to evaluate.

Limitations: Needs large labeled datasets, prone to overfitting.

✅ Unsupervised Learning

Advantages: Works without labels, good for pattern discovery.

Limitations: Hard to evaluate results, less interpretable.

✅ Reinforcement Learning

Advantages: Learns complex tasks, useful in real-time decision making.

Limitations: Needs lots of data/compute, reward design is tricky.
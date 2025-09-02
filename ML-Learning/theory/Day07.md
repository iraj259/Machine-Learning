### REVISION OF ALL THE THEORY PARTS:

# Machine Learning – Review Q&A (Day 1 → Day 6)

## Basics of ML
**Q: What is Machine Learning?**  
A: ML is when systems learn patterns from past data to make predictions or decisions, improving automatically over time. Traditional systems follow fixed rules, but ML adapts.

**Q: Difference between ML, AI, and DL?**  
- AI: Broad field of building intelligent systems  
- ML: Subset of AI that learns from data  
- DL: Subset of ML using deep neural networks  

---

## Types of Learning
**Q: What is supervised learning?**  
A: Learning with labeled data (input + output). Example: predicting house prices.

**Q: What is unsupervised learning?**  
A: Learning from unlabeled data to find patterns. Example: customer segmentation.

**Q: Name 4 types of unsupervised learning.**  
- Clustering  
- Dimensionality Reduction  
- Anomaly Detection  
- Association Rule Learning  

---

## Training Approaches
**Q: Batch vs Online Learning?**  
- Batch: Model trained on all data at once; retraining needed for new data.  
- Online: Model trained incrementally; good for streaming or frequently changing data.  

**Q: Instance-based vs Model-based Learning?**  
- Instance-based: Memorizes data and compares new cases (e.g., KNN).  
- Model-based: Learns a decision function (e.g., Linear/Logistic regression).  

---

## ML Lifecycle
**Q: What are the stages of the ML lifecycle?**  
1. Problem definition  
2. Data collection  
3. Data preprocessing/cleaning  
4. Feature engineering  
5. Model selection  
6. Training  
7. Evaluation  
8. Deployment  
9. Monitoring & maintenance  

---

## Roles in Data
**Q: Difference between Data Engineer, Analyst, Scientist, and ML Engineer?**  
- Data Engineer → Builds & manages data pipelines  
- Data Analyst → Generates insights from data  
- Data Scientist → Explores data, builds models  
- ML Engineer → Puts ML models into production  

---

## Tensors
**Q: What is a tensor?**  
A: A tensor is a multi-dimensional array used to represent data and parameters in ML.

**Q: Examples of tensor dimensions?**  
- 0D → Scalar (e.g., 5)  
- 1D → Vector (e.g., [1,2,3])  
- 2D → Matrix (e.g., table of data)  
- 3D → RGB image (height × width × channels)  
- 4D → Batch of images (batch × height × width × channels)  
- 5D → Video data (batch × frames × height × width × channels)  

**Q: Why are tensors important?**  
A: They are the fundamental data structure in frameworks (TensorFlow, PyTorch), enable GPU acceleration, and represent complex multi-dimensional data.

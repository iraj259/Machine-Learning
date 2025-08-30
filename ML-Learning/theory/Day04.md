# Day 4 – Machine Learning Lifecycle

## 1. Problem Definition
- Identify the business problem  
- Define ML objectives (classification, regression, clustering, etc.)  

## 2. Data Collection
- Gather raw data (databases, APIs, sensors, logs, etc.)  
- Ensure data is relevant and sufficient  

## 3. Data Preprocessing
- Cleaning (handle missing values, duplicates, outliers)  
- Feature engineering & feature selection  
- Splitting data (train, validation, test sets)  

## 4. Exploratory Data Analysis (EDA)
- Visualize data (graphs, charts, tables)  
- Identify patterns, trends, relationships  
- Understand data distribution, skewness, outliers  
- Identify features that may be important for prediction  

## 5. Features Engineering and Selection
- Choose appropriate algorithms (linear models, trees, neural networks, etc.)  
- Consider tradeoffs: accuracy, interpretability, scalability  

## 6. Model Training and evaluation and selection
- Train the model using training data  
- Optimize hyperparameters  
- Use cross-validation to avoid overfitting  
- Test on validation/test set  
- Metrics: accuracy, precision, recall, F1-score, RMSE, etc.  
- Check for bias/variance issues

## 7. Deployment
- Integrate the trained model into production systems (APIs, apps, pipelines)  
- Monitor performance in real-world scenarios  

## Testing
- beta testing is done

## 9. Monitoring & Maintenance
- Track accuracy, latency, drift, and errors  
- Retrain with new data when performance drops  

---

## Interview Q&A

**Q: What are the key stages of an ML project lifecycle?**  
A: Problem definition → Data collection → Data preparation → Model selection → Training → Evaluation → Deployment → Monitoring.  

**Q: Why is monitoring important in ML?**  
A: Because real-world data changes (concept drift). Without monitoring and retraining, the model’s performance degrades.  

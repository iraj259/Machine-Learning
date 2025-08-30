# Day 02: Online Machine Learning

## Topics Covered

### Online Learning (Incremental Learning)
- Online learning is a type of machine learning where the model **learns incrementally** as new data comes in.  
- Useful when data is **too large to fit in memory** or arrives **continuously**.  
- Often used for **real-time applications**.

### Out-of-Core Learning
- Training the model using **small batches of data at a time** instead of the full dataset.  
- Allows learning from datasets that are **too big for memory**.

### Batch Learning vs Online Learning
- **Batch Learning**: Model trains on the **entire dataset at once**; retraining is required for new data.  
- **Online Learning**: Model updates **incrementally** as new data arrives; no need to retrain from scratch.  
- **Key difference**: Batch = offline, Online = incremental/real-time.

### Instance-Based Learning vs Model-Based Learning
- **Instance-Based Learning**: Stores training examples and makes predictions by comparing new instances with stored data.  
  - Examples: k-Nearest Neighbors (kNN), Lazy Learning  
- **Model-Based Learning**: Learns a general model from the data and makes predictions using the model.  
  - Examples: Linear Regression, Decision Trees  
- **Key difference**: Instance-based stores data; model-based abstracts patterns.

## Key Takeaways
- Online learning is ideal for **streaming data or very large datasets**.  
- Out-of-core learning allows **handling datasets bigger than memory** by processing in chunks.  
- Understanding the differences between batch vs online and instance vs model-based learning helps **choose the right algorithm and training strategy**.

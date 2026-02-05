# Dataset description (sources, modalities, and relevance to your project)

I use paper researches for my team's project as a data source for this lab. Fisrt data is a research about HyperGraph RAG which is an upgrade of GraphRAG about recall, acuracy and also faithfullness. 
Second data I used is also a paper research about how LLM power knowledge graphs for eternprise intlligence and anylytics 


# Results table 
Query × Method × Precision@5 × Recall@10 × Faithfulness

## Fixed-Chunking
Alpha = 0.5 // Chunks_size = 900 // Chunks_overlap = 250 

<img width="437" height="280" alt="image" src="https://github.com/user-attachments/assets/1b97819a-1892-4135-a59e-870e7d614859" />



## Page-Chunking
Alpha = 0.5

<img width="437" height="279" alt="image" src="https://github.com/user-attachments/assets/e5b21151-6e26-4c15-97aa-cebf3f490709" />


## Summary of Retrieval Evaluation Results
<img width="605" height="269" alt="image" src="https://github.com/user-attachments/assets/6979f5bc-3f55-4aa5-8c5a-0314e6187a56" />


Overall, from my perspective, fixed-chunking tends to outperform page-chunking. I believe this is because fixed-chunking stores data in smaller chunks, resulting in more accurate results. Another thing I learned from this lab is that as the top-k value increases, the recall value also increases.





## Final Results Summary

In this project, we built a hybrid recommender system using the MovieLens dataset by combining **content-based filtering** and **collaborative filtering (SVD)**.

### Content-Based Recommendations:
Based on movie attributes (genres), here are some examples of recommended movies for a user:

- **Antz (1998)**
- **Toy Story 2 (1999)**
- **Monsters, Inc. (2001)**

### Collaborative Filtering (SVD):
- **RMSE**: 0.87 | **MAE**: 0.68
- **Predicted Rating** for Movie ID 1: **3.76**

### Hybrid Recommendation:
- Final hybrid score combining SVD and content-based filtering: **6.88**

### Model Performance Summary:

| Model          | RMSE | MAE  | Precision@10 | Recall@10 | Hit Rate | Coverage |
|----------------|------|------|--------------|-----------|----------|----------|
| SVD            | 0.87 | 0.68 | 0.84         | 0.32      | 0.18     | 0.26     |
| KNNBasic       | 0.95 | 0.74 | 0.72         | 0.26      | 0.12     | 0.20     |
| Baseline Only  | 0.87 | 0.67 | 0.83         | 0.31      | 0.17     | 0.25     |

# SC1015 Mini Project on Okcupid Compatibility

By: Group 2, FCS6

About
---
This is a Mini-Project for SC1015 which focuses on a profile database from okcupid, and utilises it to gain insights on matching compatibility between users. Our methods are outlined in the jupyter notebook [here](https://github.com/millerdefoe/okc-compatibility/blob/main/SC1015_Group2_MiniProject.ipynb).

Contributors
---

- Ng Jia Xin - Data Visualisation, Data Extraction, Data Processing
- Angelina Delia Sutiarto - Data Visualisation, Data Extraction, Data Processing
- Spyridon Giakoumatos - Data Visualisation, Data Extraction, Data Processing

Problem Definition
---
- Given a dataset of OKCupid profiles, are we able to develop a model that predicts the compatibility between pairs of individuals based on their profile attributes.
- How can we verify this?

Models Used
---
- K Means Clustering
- Sentiment Analysis using TextBlob

Conclusion
---
- Utilizing K Means clustering we were able to achieve pretty accurate clusters
- However these clusters failed to take into account dealbreakers between individuals like their sexual orientation
- The supporting similarity matrix was able to refine the results given by the clustering and output a match percentage
- Hence, it is possible to predict match percentage by utilising certain features (outlined in the notebook)

Our takeaways from this project
---

References
---
- https://scikit-learn.org/stable/modules/metrics.html
- https://www.kaggle.com/datasets/andrewmvd/okcupid-profiles
- https://www.analyticsvidhya.com/blog/2019/08/comprehensive-guide-k-means-clustering/
- https://www.analyticsvidhya.com/blog/2022/07/sentiment-analysis-using-python/

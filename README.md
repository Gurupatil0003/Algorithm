# K means and EM Algorithm

# Aprior Algorithm

<img src="https://intellipaat.com/blog/wp-content/uploads/2019/05/picturemessage_fd2uio5j.1rj.png" alt="Description" width="4000" style="border-radius: 10px; margin-top: 10px;">


https://in.images.search.yahoo.com/search/images;_ylt=Awrx_3uA5gloLgIAoTq7HAx.;_ylu=Y29sbwNzZzMEcG9zAzEEdnRpZAMEc2VjA3BpdnM-?p=aprior+algorithm&fr2=piv-web&type=E211IN714G0&fr=mcafee#id=355&iurl=https%3A%2F%2Frailsware.com%2Fblog%2Fwp-content%2Fuploads%2F2018%2F09%2Fillustration-9.jpg&action=click


![Flowchart-of-Apriori-algorithm](https://github.com/user-attachments/assets/e8627b30-a137-4d45-9ddc-052974f5b308)

# EM ALgorithm
``` python
1. **Guess initial values** for the hidden parts of your data (e.g., cluster centers or parameters).
     ↓
2. Repeat until things stop improving:
     a. **Estimate**: Using your current guesses, figure out the missing information (like how likely each data point belongs to each group).
     b. **Maximize**: Update your guesses based on the new information. Adjust the hidden parts of your data to better fit the observed data.
     ↓
3. You now have the best estimates for the hidden parts and the model.
```

# Flow Charts K means
```pytohn
1. Pick how many groups (K) you want.
     ↓
2. Randomly place K “center” points in your data space.
     ↓
3. Repeat until things stop changing much:
     a. **Sort**: For each data item, find which center it’s closest to and put it in that group.
     b. **Move**: For each group, shift its center to the middle of the items in that group.
     ↓
4. You now have K groups and their centers—clustering complete!
```
# Apriori
```pytohn
1. **Start with individual items**: Look at the items in each transaction and see how often they appear together.
     ↓
2. **Find frequent item sets**: Identify which combinations of items appear frequently (above a certain threshold).
     ↓
3. **Generate larger item sets**: Combine the frequent item sets to make larger combinations and check if they appear often.
     ↓
4. **Repeat** until no more large item sets are frequent.
     ↓
5. **Find associations**: Based on frequent item sets, find rules like "If you buy X, you might also buy Y".
```




| Topic         | Medium Article                                                                                                                   | Google Colab                                                                                                                 |
|---------------|----------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| K Means       | [<img src="https://img.shields.io/badge/Medium-Read%20on%20Medium-000000?logo=medium&logoColor=white" alt="Read on Medium"/>](https://medium.com/@gurupatil327/k-means-clustering-algorithm-f642cae2f627)       | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>](https://colab.research.google.com/drive/1dIdZpkMgT6XRfPMNmQ5MSfO3O_0a7m6O?usp=sharing) |
| EM Algorithm  | [<img src="https://img.shields.io/badge/Medium-Read%20on%20Medium-000000?logo=medium&logoColor=white" alt="Read on Medium"/>](https://medium.com/@gurupatil327/introduction-to-em-algorithm-in-ml-dfe2f1ea079c)           | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>](https://colab.research.google.com/drive/1TPiUsaPO-V-NBEqVx7L5oXTDIsNh3NIp?usp=sharing)  |
| Apriori       | [<img src="https://img.shields.io/badge/Medium-Read%20on%20Medium-000000?logo=medium&logoColor=white" alt="Read on Medium"/>](https://medium.com/@gurupatil327/association-rule-mining-concept-and-implementation-0d2217fd1d1d)       | [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>](https://colab.research.google.com/drive/1Mt71U44NfFJJo0YErwH2kvRtXqJOHzOi?usp=sharing) |

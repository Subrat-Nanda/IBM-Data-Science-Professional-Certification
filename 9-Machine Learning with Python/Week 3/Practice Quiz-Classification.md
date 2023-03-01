## **Practice Quiz: Classification**

#### **Congratulations! You passed!**

#### **Grade received** 100%      **To pass** 66% or higher

---

### **1\.** Question 1

Which one is TRUE about the kNN algorithm?

*   **kNN algorithm can be used to estimate values for a continuous target.**
*   The most similar point in kNN is the one with the smallest distance averaged across all normalized features.
*   kNN calculates similarity by measuring how close the two data points’ response values are.
*   kNN is a classification algorithm that takes a bunch of unlabelled points and uses them to learn how to label other points.

```css
Correct:

Correct! kNN can be used for both classification and regression prediction tasks. In the case of a continuous target, 
the prediction is taken as the average or median of the nearest neighbours.
```

### **2\.** Question 2

If the information gain of the tree by using attribute A is 0.3, what can we infer?

*   **The entropy of a tree before split minus weighted entropy after split by attribute A is 0.3.**
*   Compared to attribute B with 0.65 information gain, attribute A should be selected first for splitting.
*   By making this split, we increase the randomness in each child node by 0.3.
*   Entropy in the decision tree increases by 0.3 if we make this split.

```css
Correct:

Correct! This describes how information gain is calculated, measuring how much certainty has increased by making a split.
```

### **3\.** Question 3

When we have a value of K for KNN that’s too small, what will the model most likely look like?

*   The model will have high accuracy on the test set.
*   The model will have high out-of-sample accuracy.
*   **The model will be highly complex and captures too much noise.**
*   The model will be overly simple and does not capture enough noise.

```css
Correct:

Correct! By looking at too few neighbours, we can capture an anomaly in the data, 
which means that prediction isn’t generalized enough.
```



--------------------------------------- End ----------------------------------------------------------

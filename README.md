# Dog Boot Size Predictor

A simple **machine learning project** that predicts the ideal dog boot size based on the dog's harness size.  
This project is part of the **Microsoft Learn: Introduction to Machine Learning** module.

---

##  Project Overview

Many dog owners struggle to find the right boot size for their furry companions.  
This project builds a regression model that predicts the **boot size** using **harness size** as input.

The goal is to:
- Learn how to build and train a regression model.
- Evaluate model performance.
- Use the model for real-world predictions (e.g., recommending dog boot sizes).

---

##  Dataset

**File:** `doggy-boot-harness.csv`  
**Source:** [Microsoft Learn ML Module](https://learn.microsoft.com/en-us/training/modules/introduction-to-machine-learning/5-exercise-improve-models)

| Column Name    | Description |
|----------------|-------------|
| `boot_size`    | The target variable — actual dog boot size. |
| `harness_size` | The input feature — dog harness size. |

**You can preview or download the dataset directly:**
```python
import pandas as pd
url = "https://raw.githubusercontent.com/MicrosoftDocs/mslearn-introduction-to-machine-learning/main/Data/doggy-boot-harness.csv"
df = pd.read_csv(url)
df.head()
```

##  Inference
We've put together a system that can predict if customers are buying doggy boots that might not fit their avalanche dog, based solely on the size of harness they're purchasing. 

**In this exercise, we practiced:**

1. Creating basic models.
2. Training, then saving them to disk.
3. Loading them from disk.
4. Making predictions with them using new data sets.

## Summary
We covered some significant new jargon in this module. Let's recap what we've learned:

# The goal of machine learning is to find patterns in data and use these patterns to make estimates.

# Machine learning differs from normal software development in that we use special code, rather than our own intuition, to improve how well the software works.

# The learning process conceptually uses four components:
    1. Data, which is information we want to learn from.
    2. A model, which makes estimates about the data.
    3. An objective the model is trying to achieve.
    4. An optimizer, extra code that changes the model depending on its performance.

# You can think of data as features and labels. Features correspond to potential model inputs, while labels correspond to model outputs, or desired model outputs.

# Pandas and Plotly are powerful tools to explore datasets in Python.

# Once we have a trained model, we can save it to disk for later use.


## How to Run the Code

1.  Clone this repository to your local machine.
2.  Ensure you have Python installed.
3.  Install the required libraries:
    ```
    pip install pandas scikit-learn nltk
    ```
4.  Place the `amazon.csv` file in the same directory as the script.
5.  Run the script from your terminal:
    ```
    python sentiment_analysis.py
    ```

Feel free to explore the code, modify the parameters, and experiment with different models!

---

**Author:** **Shraddha Debata**

**Connect with me on LinkedIn:**  https://www.linkedin.com/in/shraddha-debata-59726094

**View more of my work:** 
**Tableau** https://public.tableau.com/app/profile/shraddha.debata2941/vizzes 
**Kaggle** https://www.kaggle.com/code/shraddhadebata/notebooke11b1b1723

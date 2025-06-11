# Final Project – Big Data

This is the Big Data final project for **two courses**. Please do your best to uncover the hidden secrets of this Big Data.

While exploring the boundaries of cosmic knowledge, Professor Liao discovered a series of particle accelerator datasets. These datasets may help him identify the so-called “God Particle” — or perhaps the “Devil Particle” — a potential breakthrough that could lead to the next Nobel Prize.

---

## 🧠 Task

Your task is to analyze the relationships within this dataset and classify the data into several distinct categories.

- If the data has `n` dimensions, you should be able to clearly observe `4n – 1` clusters.
- Attempt to group the data into these `4n – 1` clusters.
- The **actual numerical labels** you assign to the clusters are not important — what matters is whether the **clustering itself is accurate**.

Your results will be evaluated based on the **Fowlkes–Mallows Index (FMI)**, which measures the similarity between your clustering results and a hidden ground truth. (FMI ranges from 0 to 1.)

### Dataset Types

- **Public dataset (4 dimensions)** — You will be given a grading script.
- **Private dataset (6 dimensions)** — No script is provided.

---

## 📝 Report Requirements

Your report should briefly describe:

- The algorithm or method you used
- Why it is suitable for this dataset
- How it handles high-dimensional data
- Any preprocessing, hyperparameters, or assumptions involved

---

## 📜 Rules

1. **Individual project** — each student must work independently.
2. You may use any clustering methods or algorithms you find suitable.
3. **No plagiarism or cheating.** Violations will result in a zero and possible academic dismissal.

---

## 🎯 Grading Criteria

| Component                 | Weight |
|--------------------------|--------|
| Public dataset score     | 60%    |
| Private dataset score    | 30%    |
| Report quality           | 20%    |
| **Total**                | **110%** |

---

## 📊 Report Scoring Details

| Criterion                   | Description                                                                 | Score |
|----------------------------|-----------------------------------------------------------------------------|-------|
| Task fulfillment           | Use an unsupervised learning method to cluster data into `4n-1` groups      | 50%   |
| Technical execution & creativity | Beyond standard methods: includes preprocessing or innovation               | 30%   |
| Report clarity             | Structure, readability, visualizations, and formatting                      | 20%   |

---

## 📂 Submission Structure

```

R12XXXXXX.zip
├─ public\_submission.csv         # Results on public dataset
├─ private\_submission.csv        # Results on private dataset
└─ Report.pdf                    # Report with GitHub code link

```

---

## 💡 Hint

In the public dataset, **visual patterns** exist among the dimensions. For example:

- In the plot of the **second and third** dimensions, five distinct clusters are visually apparent.

Since both datasets originate from the same type of physical event, their structure should be similar. A similar cluster structure may appear in the private dataset as well.

**Recommended:** Visualize the relationships:

- S1 vs S2
- S2 vs S3
- S3 vs S4

---

## 🔗 GitHub Reference

[https://github.com/Jackbear8868/Final-Project-Big-Data](https://github.com/Jackbear8868/Final-Project-Big-Data)

> Please create your own GitHub repo and include the link in your report.




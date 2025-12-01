# Helping an Insurance Company Sell More Car Insurance (Cross-Sell Prediction)

## 1. What This Project Does (Overview)
This project uses smart machine learning to figure out which health insurance customers will likely buy car insurance next.

The company wants to offer car insurance only to the **right people**. This way, they save time and money by not calling or emailing customers who aren't interested. Our model helps them get more sales with less effort.

---

## 2. The Data We Used
The data comes from an insurance company and tells us about people who already have health insurance. We look at different facts about them:
* **Personal Info:** Age, Gender, and how long they've been a customer.
* **Vehicle Info:** What type of vehicle they own (or the class), and if their current car has been damaged.
* **The Main Question:** Did the customer end up buying the new vehicle insurance (Yes or No)? This is what the model tries to predict.

---

## 3. The Model's Main Job
Our goal was to build a model that correctly decides "Yes, this person will buy" or "No, they won't."

* **The Main Challenge:** Most customers in the data *did not* buy the new car insurance. This made the data **uneven** (imbalanced). We had to use special techniques to teach the model to pay extra attention to the few people who *did* say "Yes."

---

## 4. Results
After testing several models, we built a final model that is good at finding the customers who are actually interested.

* The model achieved a strong score, proving it is a trustworthy tool for the sales team.
* **Business Impact:** Because the model is smart, the company can now send their sales offers (like emails or calls) to a small, specific group of people who are likely to buy. This makes the sales campaign much **cheaper** and much **more effective**.

---

## 5. Technical Steps We Followed
1.  **Data Check:** We first cleaned the data, checked for any missing information, and prepared the columns.
2.  **Exploration:** We looked at charts and numbers to see which customer details (like age or vehicle class) were the biggest clues for buying insurance.
3.  **Data Prep:** We formatted the data (like scaling numbers and encoding words) so the computer model could easily understand it.
4.  **Handling Uneven Data:** We used special tricks (like oversampling the "Yes" group) to make the data even and help the model learn better.
5.  **Final Model:** We built and fine-tuned a powerful prediction model (like a **Logistic Regression** or **XGBoost** model) to get the best prediction score possible.

---

## 6. Files in This Folder
* `Vehicle Insurance Cross-Sell Prediction.ipynb`: This is the main file that has all the steps from start to finish.
* `model.pkl` (or `.joblib`): This is the final, saved prediction model. The company can use this model right away to score new customers.
* `README.md`: This file you are reading now.

---

## 7. Tools Used
* **Code:** Python
* **Libraries:** Pandas, NumPy (for working with data), Matplotlib, Seaborn (for charts), Scikit-learn (for the prediction models).

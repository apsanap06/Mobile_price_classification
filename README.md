# 📱 Mobile Oracle: Price Predictor

**Stop guessing, start predicting.** Ever looked at a phone's spec sheet and wondered, *"Is this actually a flagship or just a budget phone in a shiny suit?"* **Mobile Oracle** uses Machine Learning to slice through marketing fluff. Feed it the raw hardware specs—RAM, Battery, Processor Speed—and it will tell you exactly which price bracket that device belongs in.

---

## 🧠 The Brains Behind the App

The project features a full ML pipeline that compares three different "thinking styles" to see which one predicts prices most accurately:

1. **Logistic Regression** (The Logical Thinker)
2. **Decision Tree** (The Flowchart Guru)
3. **K-Nearest Neighbors (KNN)** (The Socialite—looks at similar phones to decide)

Currently, the **KNN model** is the reigning champion in `model.pkl`.

---

## 🛠️ Tech Stack

* **Intelligence:** Scikit-Learn
* **Data Wrangling:** Pandas & NumPy
* **Interface:** Streamlit (The "Face" of the project)
* **Language:** Python 3.x

---

## 🚦 Quick Start

### 1. Gear Up

Clone this repo and install the dependencies. No heavy lifting required.

```bash
pip install -r requirements.txt

```

### 2. The Training Grounds (Optional)

Want to see the models battle it out? Run the training script to clean the data and see the accuracy scores live.

```bash
python train.py

```

### 3. Launch the App

Ready to predict? Fire up the interactive dashboard:

```bash
streamlit run app.py

```

---

## 📊 How It Works

We don't care about the brand logo. We look at what's under the hood:

* **⚡ RAM (MB):** The multitasking muscle.
* **🔋 Battery (mAh):** How long the party lasts.
* **💾 Storage (GB):** Space for your memes and apps.
* **🚀 Processor (GHz):** The raw speed.
* **📸 Camera (MP):** For the "gram."

**The result?** A verdict ranging from **Low Cost 📉** to **Very High Cost 💎**.

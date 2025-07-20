
# 🚚 Courier Charge Validation Project

This project automates the validation of courier billing by comparing the **billed amount** to a **calculated expected charge** based on zone and weight slabs.

---

## 📌 Project Objective

To identify overcharged or undercharged shipments by validating:
- Zone mapping
- Weight normalization
- Rate card logic
- Final billed amount vs. expected amount

---

## 📊 Dataset

- `courier_data_sample.csv`: Contains shipment details (zone, weight, charge)
- `rate_card_sample.csv`: Contains the rates based on pickup/delivery zones and weight slabs

---

## 🔍 Methodology

1. Cleaned and merged courier and rate card data
2. Applied charge calculation logic using Python
3. Compared billed vs calculated charges
4. Flagged orders as **Overcharged**, **Undercharged**, or **Correct**

---

## ✅ Results

- 📦 Records analyzed: **15,000+**
- ⚠️ Overcharged Orders: **22%**
- ⚠️ Undercharged Orders: **11%**
- ✅ Correct Charges: **67%**
- 💸 Potential savings: **₹78,320**

---

## 📁 Project Structure

- `notebooks/`: Jupyter Notebook with full analysis
- `data/`: Sample courier and rate card datasets
- `output/`: Validated results
- `visuals/`: Graphs and charts for insights
- `Courier_Validation_Presentation.pdf`: Summary presentation

---

## 🛠 Tools Used

- Python (Pandas, NumPy)
- Excel
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 📎 Author

**Abhishek Shukla**  
Connect with me on www.linkedin.com/in/avi-shukla-da
Email: abhishekshukla7801@gmail.com

---

## 📌 License

This project is for educational and portfolio purposes only.

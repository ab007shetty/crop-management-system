# 🌾 Crop Management System

The **Crop Management System** is a simple and helpful tool built using **machine learning** to assist **farmers**. It gives smart suggestions for which crops to grow, what fertilizers to use, predicts rainfall, and estimates crop yield. This helps farmers make better decisions for their land and resources.

---

## 🚀 What Can This System Do?

* 🌱 **Crop Prediction** — Suggests the best crops based on your location and season.
* 🌾 **Crop Recommendation** — Recommends crops based on soil nutrients and weather.
* 💊 **Fertilizer Recommendation** — Recommends the right fertilizers for your crop.
* ☔ **Rainfall Prediction** — Predicts rainfall for a given region and year.
* 📈 **Yield Prediction** — Predicts how much crop yield you can expect.

---

## 🧰 Technologies Used

* **Python** & **Machine Learning** (scikit-learn, pandas, numpy)
* **PHP** (for backend)
* **HTML/CSS** & **Bootstrap 4** (for frontend)
* **JavaScript**

---

## 📦 Installation Guide

Follow these steps to set up the project on your computer:

1. **Clone the Repository**
   Open your terminal or command prompt and run:

   ```bash
   git clone https://github.com/ab007shetty/crop-management-system.git
   ```

2. **Navigate into the Project Folder**

   ```bash
   cd crop-management-system
   ```

3. **Install Required Python Libraries**
   Make sure Python is installed, then run:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run Apache Web Server (for PHP Backend)**

   * Download and install [XAMPP](https://www.apachefriends.org/index.html) if you don’t have it.
   * Open XAMPP Control Panel and start **Apache**.
   * Move the project to your `htdocs` folder (usually `C:\xampp\htdocs` on Windows).

---

## 📊 Datasets Used

The system uses different datasets for each feature:

### ✅ Crop Prediction

* State, District, Season, Crop

### ✅ Crop Recommendation

* Soil nutrients (N, P, K), Temperature, Humidity, pH, Rainfall

### ✅ Fertilizer Recommendation

* Soil and crop details like Temperature, Soil Type, Moisture, Nutrients

### ✅ Rainfall Prediction

* Rainfall data by month, season, and year for various regions

### ✅ Yield Prediction

* State, District, Year, Crop, Area, and Production data

---

## 🧪 How to Use Each Feature

* **Crop Prediction**
  Enter: `State`, `District`, `Season`
  ➡️ Get the most suitable crop to grow.

* **Crop Recommendation**
  Enter: `N`, `P`, `K`, `Temperature`, `Humidity`, `pH`, `Rainfall`
  ➡️ Get crop recommendations for your farm.

* **Fertilizer Recommendation**
  Enter: `Temperature`, `Humidity`, `Soil Moisture`, `Soil Type`, `Crop Type`, `Nitrogen`, `Phosphorous`, `Potassium`
  ➡️ Get a fertilizer suggestion.

* **Rainfall Prediction**
  Enter: `Region (Subdivision)` and `Year`
  ➡️ See rainfall prediction.

* **Yield Prediction**
  Enter: `State`, `District`, `Year`, `Crop`, `Season`, `Area`, `Production`
  ➡️ Predict expected yield.

---

## 👥 Contributors

* **AB Shetty**
* **ChatGPT 3.5 Turbo** (assisted with logic and code)

---

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
You are free to use, modify, and share it.

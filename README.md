# Fertilisense 🌾🌱

## Problem Definition ❗
* ⚠ Farmers face challenges in choosing the right crop based on soil characteristics, leading to reduced productivity and soil degradation.
* 🌲 Lack of awareness about soil requirements, organic fertilizers, and standard fertilizers contributes to imbalanced fertilization and nutrient management issues.
* 🌞 Annual crop losses of Rs. 50,000 crore occur due to pests in India.

## Objective 🚀
* 📚 Implement precision agriculture to guide farmers in crop selection and increase productivity.
* 🧬 Propose an ensemble model using SVM, Random Forest, Naive Bayes, and kNN for accurate crop recommendation.
* 🌿 Recommend fertilizers based on N, P, K values and crop types.
* 🐞 Identify pests using a DL model and recommend pesticides adhering to ISO standards.

## Methodology ⚙️
### Crop Recommendation 🌱
1. **Acquire Dataset**
2. **Input Values**
3. **Train ML Model & Create .pkl File**
    1. **Ensemble Technique with Majority Voting:**
        * SVM
        * Random Forest
        * Naive Bayes
        * kNN
4. **Crop Recommendation**
    1. Load the .pkl model file for crop recommendation.

### Fertilizer Recommendation 🌿
1. **Acquire Dataset:**
    1. NPK values for different crops
    2. Sources: The Fertilizer Association of India, Indian Institute of Water Management, etc.
2. **Input Values**
3. **Determine Difference Between Desired & Actual:**
    * High
    * Low
    * Optimal
4. **Dictionary-Based Suggestions** from Verified Sources.

### Pesticide Recommendation 🐞
1. **Acquire Data:**
    1. Image Scraping from Google Images
    2. Provide Pest Labels
2. **Data Cleaning & Augmentation:**
    1. Remove Unnecessary Content
    2. Augment Dataset for Variability
3. **DL Model Creation**
4. **Pest Detection & Pesticide Recommendation**

## Conclusion 🎯
The solution aims to:
* Enhance farmer productivity
* Reduce soil degradation
* Provide informed advice on fertilizers and crop selection
* Address critical pest control issues, benefiting both farmers and the environment.

## How to Run Locally? 💻
1. 🔄 Download and install **PyCharm**.
2. 🔧 Create a new environment:
   ```bash
   conda create -n env_name python==3.7.0
   ```
3. ⏰ Activate the environment:
   ```bash
   conda activate env_name
   ```
4. 📚 Install requirements:
   ```bash
   pip install -r requirements.txt
   ```
5. ▶ Run the application:
   ```bash
   python app.py
   ```

## Future Scope ✨
* 🌎 Integration with IoT sensors for real-time soil analysis.
* ⚖️ Expand datasets to include more crop types and region-specific data.
* 🔧 Improve pest detection accuracy using advanced DL models.
* 🛠️ Provide multilingual support for farmer accessibility.



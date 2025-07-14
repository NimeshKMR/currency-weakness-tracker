# Currency Weakness Tracker 📉

A script that checks which world currencies have weakened the most against the USD this month. (Was made in June 2025)

## 🔧 Tech Stack
- Python
- pandas
- requests
- matplotlib
- dotenv for API key management

## 🚀 How to Run

1. Clone this repo:
```bash
git clone https://github.com/yourusername/currency-weakness-tracker
cd currency-weakness-tracker

2. Create a .env file and paste your key:
API_KEY=your_key_here

3. Install dependencies
pip install -r requirements.txt

4. Run the notebook
jupyter notebook currency_tracker.ipynb

🔍 This notebook focuses on identifying the currencies that weakened the most against USD during **June 2025**, using data from exchangerate.host.

🛠️ The pipeline can be easily adapted for future time ranges by modifying the date inputs.

## 📈 Future Ideas:
- Allow user to select any month or date range
- Automate weekly/monthly currency decline tracking
- Build Streamlit dashboard version

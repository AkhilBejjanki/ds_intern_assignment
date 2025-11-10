
---

## 🧩 Datasets Used
### 1. **Bitcoin Market Sentiment (Fear & Greed Index)**
- Columns: `date`, `classification`
- Describes the market mood (Fear, Greed, Extreme Fear, etc.)
- Used to determine daily sentiment for merging with trader data.

### 2. **Historical Trader Data (Hyperliquid Exchange)**
- Columns: `account`, `execution_price`, `size_usd`, `closed_pnl`, `timestamp_ist`, etc.
- Represents real trade details, profits/losses, and activity volume.

---

## ⚙️ How to Run the Project
1. Clone or download this project folder.  
2. Open `notebook_1.ipynb` in **Jupyter Notebook** or **Google Colab**.  
3. Make sure you have the required Python libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn

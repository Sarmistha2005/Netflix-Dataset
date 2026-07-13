### Installation
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Running the Project
1. Download all files and place them in the **same folder**:
   - `Netflix_Full_Analysis.ipynb`
   - `Netflix Dataset.csv`
2. Launch Jupyter:
```bash
jupyter notebook Netflix_Full_Analysis.ipynb
```
3. From the menu, go to **Kernel → Restart Kernel and Run All Cells**.

> ⚠️ **Important:** Run cells top to bottom in order. Later cells (the Dashboard and Question Section) rely on variables created earlier (`df`, `movies`, `category`, `Year`, `Month`). Running cells out of sequence, or re-running only one cell at a time out of order, will cause `NameError` or `KeyError`.

---

## 📈 Key Insights You Can Expect
- Whether Movies or TV Shows dominate the catalog, and by what margin
- Which countries and directors contribute the most content
- How content ratings break down across Movies vs TV Shows
- Which year and month saw the highest number of releases
- Overall content KPIs: total titles, average movie duration, longest movie, most frequent actor

---

## 🔮 Possible Extensions
- Add an NLP-based genre or rating predictor using the `Description` column
- Build a genre co-occurrence network (which genres frequently pair together)
- Convert the static dashboard into an interactive Streamlit or Plotly Dash app
- Compare release year vs. year added to Netflix, to study content "freshness"

---

## 📄 License
This project is for educational/portfolio purposes. The dataset is publicly available Netflix catalog metadata and does not represent proprietary company data.

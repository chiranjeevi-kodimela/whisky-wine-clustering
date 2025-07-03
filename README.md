# 🥃 Whisky & Wine Clustering with Bokeh

## ✅ Objective

To cluster whisky distilleries based on flavor profiles using **Spectral Co-Clustering**, and visualize the resulting correlation matrices.

---

## 📁 Data Sources

- `whiskies.txt`: Contains distillery features and flavor intensities.
- `regions.txt`: Corresponding Scotch whisky regions.

---

## ⚙️ Techniques Used

- Spectral Co-Clustering from `sklearn`
- Flavor correlation matrix analysis
- Data visualization using `matplotlib`
- Optional: Bokeh (for interactive plotting upgrade)

---

## 📊 Outputs

- Visual comparison between original and clustered correlation matrices
- Grouped distilleries by flavor profile similarity

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
python scripts/whiskies_loading_and_inspecting_data.py
python scripts/whiskies_exploring_correlations.py
python scripts/spectral_clustering.py
python scripts/whiskies_comparing_correlation_matrices.py

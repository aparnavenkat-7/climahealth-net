# 🚀 ClimaHealth-Net Demo — Deploy in 10 Minutes

## Files you need
- `app.py` — the Streamlit web app
- `requirements.txt` — dependencies

## Step 1 — Upload to GitHub (5 min)
1. Go to github.com → New repository
2. Name it: `climahealth-net-demo`
3. Make it **Public**
4. Upload both files: `app.py` and `requirements.txt`
5. Click **Commit changes**

## Step 2 — Deploy on Streamlit Cloud (5 min)
1. Go to **share.streamlit.io**
2. Sign in with GitHub
3. Click **"New app"**
4. Select your repo: `climahealth-net-demo`
5. Main file: `app.py`
6. Click **Deploy!**

## Step 3 — Get your live URL
Within 2-3 minutes you'll get a URL like:
`https://climahealth-net-demo.streamlit.app`

**Share this URL at your presentation!** 🎉

---

## Running Locally (if needed)
```bash
pip install -r requirements.txt
streamlit run app.py
```
Then open: http://localhost:8501

---

## What the demo shows
- 🗺️ **Tab 1: Risk Map** — Interactive Kenya district map with outbreak risk
  - Click any district circle to see Malaria/Dengue/Cholera risk
  - Color coded: Red=HIGH, Orange=MEDIUM-HIGH, Yellow=MEDIUM, Green=LOW
  - Press "Run Live Prediction" button for effect!

- 📈 **Tab 2: Time Series** — 52-week risk forecast with confidence intervals
  - Switch between diseases and districts in sidebar

- 🛰️ **Tab 3: Satellite Data** — NASA MODIS + ERA5 feature visualization
  - Shows LST, NDVI, MNDWI, Precipitation

- 📊 **Tab 4: Model Performance** — Results, baseline comparison, ablation

---

## Presentation tip
1. Open the app in Chrome (full screen — press F11)
2. Start on Tab 1 (Risk Map)
3. Click "Run Live Prediction" — it shows a spinner for 2 seconds then results
4. Click on Kisumu circle (highest risk district)
5. Switch to Tab 2 to show the time series forecast
6. End on Tab 4 to show the 87.3% precision result

# Antenna Downtilt Calculator — Streamlit App

## Chart Style
- **Light/white background** like the original
- **Green segments** on terrain = strong signal zone
- **Red segments** on terrain = shadowed by terrain  
- **Orange segments** on terrain = ground footprint zone
- **Colored vertical bands** (green/red/orange tint) across the chart
- **Dashed light-blue lines** = footprint lobe limits
- **Solid green line** = main lobe ray
- **Red dashed vertical** = selected distance slider
- **Teal dot** = main lobe hit point
- **Cyan dot** = antenna site marker

## Run

```bash
# Install
pip install -r requirements.txt

# Run
streamlit run app.py
```

Opens at http://localhost:8501

## Egypt Example (pre-loaded)
- Lat: 30.0028686 | Lon: 31.0719953 | Azimuth: 80°
- Click "Fetch Elevation Profile" to load live DEM data

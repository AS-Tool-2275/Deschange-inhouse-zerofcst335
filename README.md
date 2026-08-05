# Destination Change Streamlit App

Files in this package:
- destination_change_streamlit_app.py
- destination_change_unified_flow.py
- requirements.txt

Run locally:

```bash
pip install -r requirements.txt
streamlit run destination_change_streamlit_app.py
```

Notes:
- `SI = 0` is treated as a hard lock.
- Items with `Average of SS Wk3 = 0` use a fallback equalization pass on SI After.

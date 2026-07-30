# Destination Change App

## Run locally

```bash
pip install -r requirements.txt
streamlit run destination_change_streamlit_app.py
```

## Notes
- PSW vendor order is detected from uploaded PSW / Production Schedule files.
- Upload DueDateCalc files in the same order as detected vendor order.
- If only one DueDateCalc file is uploaded, all vendors use the same transit time.
- Warehouse 335 uses accumulated forecast subtraction through the target destination-change week.
- Sub vendor logic mirrors the main vendor logic; only the input source and SI baseline differ.

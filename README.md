# GST FINDER

## Run locally or in Google Colab

```bash
pip install -r requirements.txt
streamlit run app.py
```

Keep `app.py`, `requirements.txt`, and `gst_goods_historical_2023.csv` in the same directory.

## Search interface

The Home page has no category selector. Type a product name, alias, or HSN code; the matching dropdown displays `Product name | HSN code`. Select a suggestion to open that record, or leave it unselected and search to view all matching records. Manufacturer remains an optional filter.

## Important data limitation

The bundled historical goods schedule is labelled 01-04-2023 and is not a verified current GST rate master. Confirm every classification and rate against current applicable CBIC/GST Council notifications before tax or business use. The application is educational and not an official government platform.

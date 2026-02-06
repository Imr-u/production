# Raw_schema

``` python
{
    "rate_date": "date",  # Date rate applies to
    "scrape_timestamp": "timestamp",  # Actual scrape time with timezone
    "currency": "string",  # ETB, EGP, NGN, DZD, ZMW
    "buying_rate": "float",
    "selling_rate": "float",
    "data_source": "string",  # "central_bank", "commercial_bank_x"
    "is_real_time": "boolean"  # True for live, False for historical
}
```

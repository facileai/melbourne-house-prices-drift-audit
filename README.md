# melbourne-house-prices-drift-audit

This holds the code used during the webinar MLOPS - From local to production that aired on the 27-May-2021

To run the drift run `python calculate_all_drift.py -i=001 -x=./data/mel-data-cleam.csv -f=Rooms,Type,Method,Propertycount,Distance,SellerG -t=Date_month_1st -g=Postcode -p=0.05`

The file named `model-001_distribution_drift_results.csv` will be under the `data` folder.

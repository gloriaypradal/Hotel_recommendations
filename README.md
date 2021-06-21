# Hotel_recommendations
Recommended hotels for travelers based on past bookings and hotel search

This school project is developed based on 2 data sets

Train set, with the following features:
date_time                    100000 non-null object
site_name                    100000 non-null int64
posa_continent               100000 non-null int64
user_location_country        100000 non-null int64
user_location_region         100000 non-null int64
user_location_city           100000 non-null int64
orig_destination_distance    63078 non-null float64
user_id                      100000 non-null int64
is_mobile                    100000 non-null int64
is_package                   100000 non-null int64
channel                      100000 non-null int64
srch_ci                      99929 non-null object
srch_co                      99929 non-null object
srch_adults_cnt              100000 non-null int64
srch_children_cnt            100000 non-null int64
srch_rm_cnt                  100000 non-null int64
srch_destination_id          100000 non-null int64
srch_destination_type_id     100000 non-null int64
is_booking                   100000 non-null int64
cnt                          100000 non-null int64
hotel_continent              100000 non-null int64
hotel_country                100000 non-null int64
hotel_market                 100000 non-null int64
hotel_cluster                100000 non-null int64

and Deestinations data set that consist in coded destination values

Jupyter Notebook was used to design the model to predict what hotels would be the preferred by the traveler

Models used for this projects were: K-Nearest Neighbor, Random Forest and Naive Bayes

Please take in consideration that this project was created based on a Expedia competion hosted by Kaggle

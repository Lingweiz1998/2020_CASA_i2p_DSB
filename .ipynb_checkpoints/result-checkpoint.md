记录行数为：74188
1:统计每一行的非NA单元数
id                                              74186
listing_url                                     74187
scrape_id                                       74187
last_scraped                                    74187
name                                            74167
                                                ...  
calculated_host_listings_count                  74184
calculated_host_listings_count_entire_homes     74184
calculated_host_listings_count_private_rooms    74184
calculated_host_listings_count_shared_rooms     74184
reviews_per_month                               53901
Length: 74, dtype: int64

2:列dtype
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 74188 entries, 0 to 74187
Data columns (total 74 columns):
###  Column                                        Non-Null Count  Dtype  
---  ------                                        --------------  -----  
 0   id                                            74186 non-null  float64
 1   listing_url                                   74187 non-null  object 
 2   scrape_id                                     74187 non-null  object 
 3   last_scraped                                  74187 non-null  object 
 4   name                                          74167 non-null  object 
 5   description                                   71329 non-null  object 
 6   neighborhood_overview                         47208 non-null  object 
 7   picture_url                                   74188 non-null  object 
 8   host_id                                       74188 non-null  float64
 9   host_url                                      74188 non-null  object 
 10  host_name                                     74179 non-null  object 
 11  host_since                                    74179 non-null  object 
 12  host_location                                 74006 non-null  object 
 13  host_about                                    42494 non-null  object 
 14  host_response_time                            37781 non-null  object 
 15  host_response_rate                            37779 non-null  object 
 16  host_acceptance_rate                          51597 non-null  object 
 17  host_is_superhost                             74177 non-null  object 
 18  host_thumbnail_url                            74177 non-null  object 
 19  host_picture_url                              74177 non-null  object 
 20  host_neighbourhood                            56560 non-null  object 
 21  host_listings_count                           74175 non-null  float64
 22  host_total_listings_count                     74177 non-null  object 
 23  host_verifications                            74186 non-null  object 
 24  host_has_profile_pic                          74177 non-null  object 
 25  host_identity_verified                        74177 non-null  object 
 26  neighbourhood                                 47207 non-null  object 
 27  neighbourhood_cleansed                        74186 non-null  object 
 28  neighbourhood_group_cleansed                  2 non-null      float64
 29  latitude                                      74186 non-null  float64
 30  longitude                                     74186 non-null  float64
 31  property_type                                 74186 non-null  object 
 32  room_type                                     74186 non-null  object 
 33  accommodates                                  74186 non-null  float64
 34  bathrooms                                     2 non-null      float64
 35  bathrooms_text                                74029 non-null  object 
 36  bedrooms                                      69594 non-null  object 
 37  beds                                          73199 non-null  float64
 38  amenities                                     74186 non-null  object 
 39  price                                         74186 non-null  object 
 40  minimum_nights                                74186 non-null  float64
 41  maximum_nights                                74186 non-null  object 
 42  minimum_minimum_nights                        74186 non-null  float64
 43  maximum_minimum_nights                        74186 non-null  float64
 44  minimum_maximum_nights                        74186 non-null  float64
 45  maximum_maximum_nights                        74186 non-null  object 
 46  minimum_nights_avg_ntm                        74186 non-null  object 
 47  maximum_nights_avg_ntm                        74186 non-null  float64
 48  calendar_updated                              2 non-null      float64
 49  has_availability                              74186 non-null  object 
 50  availability_30                               74186 non-null  float64
 51  availability_60                               74186 non-null  float64
 52  availability_90                               74186 non-null  float64
 53  availability_365                              74186 non-null  float64
 54  calendar_last_scraped                         74184 non-null  object 
 55  number_of_reviews                             74186 non-null  object 
 56  number_of_reviews_ltm                         74186 non-null  float64
 57  number_of_reviews_l30d                        74186 non-null  float64
 58  first_review                                  53903 non-null  object 
 59  last_review                                   53903 non-null  object 
 60  review_scores_rating                          52285 non-null  float64
 61  review_scores_accuracy                        52233 non-null  float64
 62  review_scores_cleanliness                     52242 non-null  float64
 63  review_scores_checkin                         52194 non-null  float64
 64  review_scores_communication                   52234 non-null  float64
 65  review_scores_location                        52197 non-null  float64
 66  review_scores_value                           52196 non-null  float64
 67  license                                       0 non-null      float64
 68  instant_bookable                              74184 non-null  object 
 69  calculated_host_listings_count                74184 non-null  float64
 70  calculated_host_listings_count_entire_homes   74184 non-null  float64
 71  calculated_host_listings_count_private_rooms  74184 non-null  float64
 72  calculated_host_listings_count_shared_rooms   74184 non-null  float64
 73  reviews_per_month                             53901 non-null  float64
dtypes: float64(34), object(40)
memory usage: 41.9+ MB
None

3:计算部分统计数据
                 id       host_id  host_listings_count  \
count  7.418600e+04  7.418800e+04         74175.000000   
mean   2.524026e+07  9.403591e+07            22.460775   
std    1.292372e+07  9.804038e+07           115.784574   
min    1.155100e+04  1.000000e+00             0.000000   
25%    1.504579e+07  1.578421e+07             1.000000   
50%    2.576235e+07  4.911094e+07             1.000000   
75%    3.697921e+07  1.529342e+08             4.000000   
max    4.509040e+07  3.639824e+08          1309.000000   

       neighbourhood_group_cleansed      latitude     longitude  accommodates  \
count                      2.000000  74186.000000  74186.000000  74186.000000   
mean                     570.000000     51.508588     -0.128352      3.129755   
std                      784.888527      0.261351      0.095638      1.989834   
min                       15.000000      2.000000     -0.496250      1.000000   
25%                      292.500000     51.484940     -0.189120      2.000000   
50%                      570.000000     51.514070     -0.126570      2.000000   
75%                      847.500000     51.538410     -0.069660      4.000000   
max                     1125.000000     51.681690      2.000000     16.000000   

         bathrooms          beds  minimum_nights  ...  review_scores_checkin  \
count     2.000000  73199.000000    74186.000000  ...           52194.000000   
mean    570.000000      1.729218        4.957067  ...               9.640744   
std     784.888527      1.289836       21.145133  ...               0.923870   
min      15.000000      0.000000        0.000000  ...               2.000000   
25%     292.500000      1.000000        1.000000  ...              10.000000   
50%     570.000000      1.000000        2.000000  ...              10.000000   
75%     847.500000      2.000000        3.000000  ...              10.000000   
max    1125.000000     28.000000     1125.000000  ...              10.000000   

       review_scores_communication  review_scores_location  \
count                 52234.000000            52197.000000   
mean                      9.662921                9.551871   
std                       0.913548                0.856592   
min                       2.000000                2.000000   
25%                      10.000000                9.000000   
50%                      10.000000               10.000000   
75%                      10.000000               10.000000   
max                      10.000000               10.000000   

       review_scores_value  license  calculated_host_listings_count  \
count         52196.000000      0.0                    74184.000000   
mean              9.281478      NaN                       17.023401   
std               1.072651      NaN                       76.759048   
min               2.000000      NaN                        1.000000   
25%               9.000000      NaN                        1.000000   
50%              10.000000      NaN                        1.000000   
75%              10.000000      NaN                        4.000000   
max              10.000000      NaN                      718.000000   

       calculated_host_listings_count_entire_homes  \
count                                 74184.000000   
mean                                     14.269047   
std                                      74.269755   
min                                       0.000000   
25%                                       0.000000   
50%                                       1.000000   
75%                                       2.000000   
max                                     717.000000   

       calculated_host_listings_count_private_rooms  \
count                                  74184.000000   
mean                                       2.169484   
std                                       13.894196   
min                                        0.000000   
25%                                        0.000000   
50%                                        1.000000   
75%                                        1.000000   
max                                      230.000000   

       calculated_host_listings_count_shared_rooms  reviews_per_month  
count                                 74184.000000       53901.000000  
mean                                      0.045239           0.720166  
std                                       0.625069           0.949437  
min                                       0.000000           0.010000  
25%                                       0.000000           0.140000  
50%                                       0.000000           0.380000  
75%                                       0.000000           0.940000  
max                                      18.000000          20.000000  

[8 rows x 34 columns]

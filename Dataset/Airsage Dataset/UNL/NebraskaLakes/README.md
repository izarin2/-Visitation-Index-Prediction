# Targeted Location Analysis

Daily footfall counts, demographic information, and more for one or more points of interest.

### Data Dictionary
| Column Name | Data Type | Description |
|---|---|---|
| poi | String | Name of the Point of Interest |
| date | String | Date |
| home_county | String | Home County |
| home_state | String | Home State |
| home_msa | String | Home MSA |
| count | Integer | Total count of visitors |
| hh00 | Integer | Count of visitors in the first hour of the day |
| hh01 | Integer | Count of visitors in the second hour of the day |
| hh02 | Integer | Count of visitors in the third hour of the day |
| hh03 | Integer | Count of visitors in the fourth hour of the day |
| hh04 | Integer | Count of visitors in the fifth hour of the day |
| hh05 | Integer | Count of visitors in the sixth hour of the day |
| hh06 | Integer | Count of visitors in the seventh hour of the day |
| hh07 | Integer | Count of visitors in the eighth hour of the day |
| hh08 | Integer | Count of visitors in the ninth hour of the day |
| hh09 | Integer | Count of visitors in the tenth hour of the day |
| hh10 | Integer | Count of visitors in the eleventh hour of the day |
| hh11 | Integer | Count of visitors in the twelfth hour of the day |
| hh12 | Integer | Count of visitors in the thirteenth hour of the day |
| hh13 | Integer | Count of visitors in the fourteenth hour of the day |
| hh14 | Integer | Count of visitors in the fifteenth hour of the day |
| hh15 | Integer | Count of visitors in the sixteenth hour of the day |
| hh16 | Integer | Count of visitors in the seventeenth hour of the day |
| hh17 | Integer | Count of visitors in the eighteenth hour of the day |
| hh18 | Integer | Count of visitors in the nineteenth hour of the day |
| hh19 | Integer | Count of visitors in the twentieth hour of the day |
| hh20 | Integer | Count of visitors in the twenty-first hour of the day |
| hh21 | Integer | Count of visitors in the twenty-second hour of the day |
| hh22 | Integer | Count of visitors in the twenty-third hour of the day |
| hh23 | Integer | Count of visitors in the twenty-fourth hour of the day |
| visit_duration | Double | Average number of hours spent at the POI |
| income_0_10 | Double | Count of visitors in the 0-10k/yr income range |
| income_10_15 | Double | Count of visitors in the 10k-15k/yr income range |
| income_15_20 | Double | Count of visitors in the 15k-20k/yr income range |
| income_20_25 | Double | Count of visitors in the 20k-25k/yr income range |
| income_25_30 | Double | Count of visitors in the 25k-30k/yr income range |
| income_30_35 | Double | Count of visitors in the 30k-35k/yr income range |
| income_35_40 | Double | Count of visitors in the 35k-40k/yr income range |
| income_40_45 | Double | Count of visitors in the 40k-45k/yr income range |
| income_45_50 | Double | Count of visitors in the 45k-50k/yr income range |
| income_50_60 | Double | Count of visitors in the 50k-60k/yr income range |
| income_60_75 | Double | Count of visitors in the 60k-75k/yr income range |
| income_75_100 | Double | Count of visitors in the 75k-100k/yr income range |
| income_100_125 | Double | Count of visitors in the 100k-125k/yr income range |
| income_125_150 | Double | Count of visitors in the 125k-150k/yr income range |
| income_150_200 | Double | Count of visitors in the 150k-200k/yr income range |
| income_over_200 | Double | Count of visitors in the 200k+/yr income range |
| female_0_5 | Double | Count of female visitors between 0 and 5 years old |
| female_5_9 | Double | Count of female visitors between 5 and 9 years old |
| female_10_14 | Double | Count of female visitors between 10 and 14 years old |
| female_15_17 | Double | Count of female visitors between 15 and 17 years old |
| female_18_19 | Double | Count of female visitors between 18 and 19 years old |
| female_20_20 | Double | Count of female visitors 20 years old |
| female_21_21 | Double | Count of female visitors 21 years old |
| female_22_24 | Double | Count of female visitors between 22 and 24 years old |
| female_25_29 | Double | Count of female visitors between 25 and 29 years old |
| female_30_34 | Double | Count of female visitors between 30 and 34 years old |
| female_35_39 | Double | Count of female visitors between 35 and 39 years old |
| female_40_44 | Double | Count of female visitors between 40 and 44 years old |
| female_45_49 | Double | Count of female visitors between 45 and 49 years old |
| female_50_54 | Double | Count of female visitors between 50 and 54 years old |
| female_55_59 | Double | Count of female visitors between 55 and 59 years old |
| female_60_61 | Double | Count of female visitors between 60 and 61 years old |
| female_62_64 | Double | Count of female visitors between 62 and 64 years old |
| female_65_66 | Double | Count of female visitors between 65 and 66 years old |
| female_67_69 | Double | Count of female visitors between 67 and 69 years old |
| female_70_74 | Double | Count of female visitors between 70 and 74 years old |
| female_75_79 | Double | Count of female visitors between 75 and 79 years old |
| female_80_84 | Double | Count of female visitors between 80 and 84 years old |
| female_over_85 | Double | Count of female visitors 85 years old and older |
| male_0_5 | Double | Count of male visitors between 0 and 5 years old |
| male_5_9 | Double | Count of male visitors between 5 and 9 years old |
| male_10_14 | Double | Count of male visitors between 10 and 14 years old |
| male_15_17 | Double | Count of male visitors between 15 and 17 years old |
| male_18_19 | Double | Count of male visitors between 18 and 19 years old |
| male_20_20 | Double | Count of male visitors 20 years old |
| male_21_21 | Double | Count of male visitors 21 years old |
| male_22_24 | Double | Count of male visitors between 22 and 24 years old |
| male_25_29 | Double | Count of male visitors between 25 and 29 years old |
| male_30_34 | Double | Count of male visitors between 30 and 34 years old |
| male_35_39 | Double | Count of male visitors between 35 and 39 years old |
| male_40_44 | Double | Count of male visitors between 40 and 44 years old |
| male_45_49 | Double | Count of male visitors between 45 and 49 years old |
| male_50_54 | Double | Count of male visitors between 50 and 54 years old |
| male_55_59 | Double | Count of male visitors between 55 and 59 years old |
| male_60_61 | Double | Count of male visitors between 60 and 61 years old |
| male_62_64 | Double | Count of male visitors between 62 and 64 years old |
| male_65_66 | Double | Count of male visitors between 65 and 66 years old |
| male_67_69 | Double | Count of male visitors between 67 and 69 years old |
| male_70_74 | Double | Count of male visitors between 70 and 74 years old |
| male_75_79 | Double | Count of male visitors between 75 and 79 years old |
| male_80_84 | Double | Count of male visitors between 80 and 84 years old |
| male_over_85 | Double | Count of male visitors 85 years old and older |
| asian | Double | Count of visitors whose ethnicity is in the Asian category |
| black | Double | Count of visitors whose ethnicity is in the Black category |
| hawaiian_pacific | Double | Count of visitors whose ethnicity is in the Hawaiian Pacific category |
| native_american | Double | Count of visitors whose ethnicity is in the Native American category |
| other | Double | Count of visitors whose ethnicity is in the Other category |
| two_ex_other_and_three_plus | Double | Count of visitors whose ethnicity is in the Two Excluding Others/Three Plus category |
| two_with_other | Double | Count of visitors whose ethnicity is in the Two plus Others category |
| white | Double | Count of visitors whose ethnicity is in the White category |

### Data File Format
Data files included are spit by month; named in the date format of YYYYMM.
These files are gzipped to reduce the overall archive size. If you do not have already have an archiver that can handle gzipped files [7-Zip](https://www.7-zip.org) is recommended.

*For any questions regarding this dataset, please contact support@airsage.com*

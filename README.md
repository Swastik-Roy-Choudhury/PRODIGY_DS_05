AUTHOR-SWASTIK ROY CHOUDHURY...............
TERMINAL
OUTPUT

  CRASH DATE CRASH TIME   BOROUGH  ...  VEHICLE TYPE CODE 3  VEHICLE TYPE CODE 4  VEHICLE TYPE CODE 5
0  2020-08-29   15:40:00     BRONX  ...                  NaN                  NaN                  NaN
1  2020-08-29   21:00:00  BROOKLYN  ...                  NaN                  NaN                  NaN
2  2020-08-29   18:20:00       NaN  ...                  NaN                  NaN                  NaN
3  2020-08-29   00:00:00     BRONX  ...                Sedan           Motorcycle                  NaN
4  2020-08-29   17:10:00  BROOKLYN  ...                  NaN                  NaN                  NaN

[5 rows x 29 columns]
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 74881 entries, 0 to 74880
Data columns (total 29 columns):
 #   Column                         Non-Null Count  Dtype
---  ------                         --------------  -----
 0   CRASH DATE                     74881 non-null  object
 1   CRASH TIME                     74881 non-null  object
 2   BOROUGH                        49140 non-null  object
 3   ZIP CODE                       49134 non-null  float64
 4   LATITUDE                       68935 non-null  float64
 5   LONGITUDE                      68935 non-null  float64
 6   LOCATION                       68935 non-null  object
 7   ON STREET NAME                 55444 non-null  object
 8   CROSS STREET NAME              35681 non-null  object
 9   OFF STREET NAME                19437 non-null  object
 10  NUMBER OF PERSONS INJURED      74881 non-null  int64
 11  NUMBER OF PERSONS KILLED       74881 non-null  int64
 12  NUMBER OF PEDESTRIANS INJURED  74881 non-null  int64
 13  NUMBER OF PEDESTRIANS KILLED   74881 non-null  int64
 14  NUMBER OF CYCLIST INJURED      74881 non-null  int64
 15  NUMBER OF CYCLIST KILLED       74881 non-null  int64
 16  NUMBER OF MOTORIST INJURED     74881 non-null  int64
 17  NUMBER OF MOTORIST KILLED      74881 non-null  int64
 18  CONTRIBUTING FACTOR VEHICLE 1  74577 non-null  object
 19  CONTRIBUTING FACTOR VEHICLE 2  59285 non-null  object
 20  CONTRIBUTING FACTOR VEHICLE 3  6765 non-null   object
 21  CONTRIBUTING FACTOR VEHICLE 4  1851 non-null   object
 22  CONTRIBUTING FACTOR VEHICLE 5  523 non-null    object
 23  COLLISION_ID                   74881 non-null  int64
 24  VEHICLE TYPE CODE 1            74246 non-null  object
 25  VEHICLE TYPE CODE 2            53638 non-null  object
 26  VEHICLE TYPE CODE 3            6424 non-null   object
 27  VEHICLE TYPE CODE 4            1771 non-null   object
 28  VEHICLE TYPE CODE 5            503 non-null    object
dtypes: float64(3), int64(9), object(17)
memory usage: 16.6+ MB

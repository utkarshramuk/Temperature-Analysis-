# Temperature-Analysis-
Code to get temperature data and performing analysis on it in a desired methodology

PLEASE GO THROGH THE FOLLOWING INSTRUCTIONS TO UNDERSTAND THE CODE BETTER:
1. The code can be accessed by clicking on the Mann, Sen & Anomaly Moving Avg codes file just above readme 
2. The data used is IMD gridded weather data (1 degree x 1 degree) which has daily temperature values.
3. The data is loaded using the available imdlib library
4. This data is then converted to csv format according to the desired latitude and lomgitude requirements. (.CSV gives a better control over every value and also gives a check by using excel for certain functions)
5. In the CSV form, this data is then sorted and only the values of months Feb-May are kept as they are the summer months.
6. The above data is then loaded and then used accordingly with libraries for the computation of the slopes etc. 

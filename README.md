# WeatherPy

<h2>DESCRIPTIONS OF OBSERVATIONS</h2>

<p><strong>1. Latitude vs. Temperature:</strong></p>

<p>The scatter plot of Latitude vs. Temperature forms a parabola. According to the plot, it gets cooler while the value of latitude increases. A quadratic regression curve (red dashed line in “lat_vs_ temperature_quadratic_regression.png) perfectly illustrated dot distribution pattern as seen on the graph. The estimated highest temperature as suggested by the curve is calculated to be around 8.8oS, whereas classical text book tells us that in late March like we are in right now the closest latitude to the sun on earth (with the highest temperature) is around the equator. A sound explanation to this discrepancy would lie in the fact that south hemisphere is surrounded in large by oceans. Since water has a much higher specific heat capacity as compared to the continent does, there might be a lag for the temperature to drop down from summer to autumn in south hemisphere. Interestingly, five out of six cities with the highest temperature observed among our sampling city pool locate even further south around 30 o in Australia (“Port Macquarie”, “Yulara”, “Inverell”, “Byron Bay”, and “Codrington”). Other countries with this latitude are South Africa, Brazil, Chile, and Argentina. However, they only constitute a small portion in area. Everywhere besides them the only thing can be seen is ocean.</p>
<img src="./output_data/lat_vs_temperature_quadratic_regression.png" alt="Lat vs Temperature">

<p><strong>2. Latitude vs. Humidity and Cloudiness:</strong></p>

<p>Relative humidity (RH), referred to as “humidity” here, is the amount of moisture in the air divided by how much moisture the air can hold. Many factors are able to affect RH, with temperature sitting at the top hierarchy. Specifically, population (heat island effect), automobiles on the road (water vapor in the exhausts), as well as surrounding landscapes (forests, river, desert …) etc. might be determinants for city RH. Back to the Latitude vs. Humidity figure, polynomial regression with relatively low (deg=5, red dashed line) and high (deg=25, magenta solid line) degrees both suggest there be RH peaks around 10oS and 60oN and grooves around 40oS and 35oN. As revealed above, the 10oS peak is most likely high-temperature-driven. The 60oN peak, on the other hand, could have been due to the decrease in air capacity to hold the moisture (will be discussed right away for the contribution of low atmospheric pressure). Another plausible explanation is that the cold, dense Arctic polar water descends along the ocean bottom toward the equator, which stirs the surface water in the ocean around 60oN to vaporize to the air. Notably, both 10oS (Equatorial LPZ) and 60oN (Subpolar LPZ) locates in low pressure zone (LPZ), it seems that the atmospheric pressure does contribute to the RH. More supports come from the analysis of RH groove as 40oS and 35oN (low in RH), which are in Subtropical High Pressure Zone.</p>
<img src="./output_data/lat_vs_humidity_polyfit.png" alt="Lat vs Humidity">

<p>Since cloud is considered as a large collection of very tiny droplets of water in the air, it is easy to speculate that cloud is hard to form where the RH is low. It holds true that around 10oS and 60oN peaks, dots are floating higher, whereas in 40oS and 35oN groove dots are tend to sink towards the bottom on the figure of “lat_vs_cloudiness.png”.</p>
<img src="./output_data/lat_vs_cloudiness.png" alt="Lat vs Cloudiness">

<p><strong>3. Latitude vs. Wind Speed:</strong></p>

<p>Similar to the analysis of Latitude vs. Humidity, polynomial regression was plotted with both low (deg=5, red dashed line) and high (deg=25, magenta solid line) degrees in analyzing Latitude vs. Wind Speed. As seen on “lat_vs_wind_speed_polyfit.png”, the low deg line is pretty flat. Although the high deg line does give us some peaks and grooves, the two lines do not share any significant trend in common. Therefore, it is hard to say the latitude of the city has any impact on wind speed.</p>
<img src="./output_data/lat_vs_wind_speed_polyfit.png" alt="Lat vs Wind Speed">

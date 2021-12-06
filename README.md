# Climate Change Is Inevitable But Do Some Countries Stand A Better Chance Against It Than Others?
## About us
>&emsp; This project was worked on by Adam Callanan (AdamCallanan), Trevor Lee (TreeLeef), and Angus Murchison (AngusMurch).
## Introduction:
>&emsp; Climate change is a very critical and ever-looming issue which many of us remain powerless over and can do nothing about but watch. It is because of this threatening existential nature that makes it a very rewarding and reasonable data set to be interested in and analyze. We hope our findings can give us some insight into what geographical and societal problems of countries may be in any way correlated to climate change. Furthermore, our analysis can further prove the threat this issue poses by showing what the future may look like if nothing is done about it.
## Description of the Data
>Source: https://www.kaggle.com/sevgisarac/temperature-change \
\
&emsp; The FAOSTAT Temperature Change data set is a collection of the average change of temperature of 190 countries and 37 territories in Celsius,  recorded monthly from 1961-2019, giving the annual, seasonal and monthly temperature outliers with respect to the 1951-1980 recordings.
## Discussion
>&emsp; The first thing we wanted to look at with our data was whether there was any possible correlation to be found between a whether a country was first-world or third-world and it's respective yearly temperature change. To accomplish this we looked at Canada, UK, and Japan for first-world countries and Afghanistan, Madagascar, and Bolivia for the third-world countries and then graphed their yearly temperature change so we could compare them.\
![image](https://user-images.githubusercontent.com/90793884/144784794-fbe72df8-2558-4949-8617-6fba41da29bd.png)\
The results show that yearly average temperature of each country is steadily increasing. When looking at the average temperature change of each country we see that every country has around the same yearly change except for Canada which is much higher than the rest. This is further supported after graphing the yearly temperature changes as we can see all the other countries group and almost blend together in the middle but with Canada spiking out from the main group periodically. Overall, this shows that there exists no correlation between a country's economic status and its temperature change due to global warming. However, the results do suggest a correlation between a country's location and its temperature change.\
\
&emsp; In order to check this hypothesis we decided to apply the same process to 3 northen countries and 3 equatorial countries. For the northern countries we used Canada, Greenland and Norway and for the equatorial countries we used Colombia, Kenya, and Indonesia.\
![image](https://user-images.githubusercontent.com/90793884/144785741-d418614f-d703-47eb-ae19-6cae4d5c3d82.png)\
We can see that, for all sampled countries, the yearly temperature change has been increasing as time goes on. The northern countries don't line up too much expcept for Canada and Greenland in recent years. The main similarity is that the fluctuation of the temperature change (range) is much greater, including rising at a greater rate. The caveat here is that both Greenland and Canada both have large land masses. This could alter the data since there are more climates being measured. Perhaps smaller countries would be preferable to analyze, but all smaller northern countries are grouped in Europe which is further south than the selected sample and also relatively in the same area. The graphs for the equatorial countries are really similar and tend to line up despite being on largely different longitudes. While the same conclusion can't neccessarily be drawn for the northern countries, this shows that the there could be a relationship with distance from the equator and temperature change.\
\
&emsp; Next we wanted to look at the countries with the highest pollution index and how their yearly temperature change's compare to one another. We did this by graphing the yearly temperature change of Bangladesh, Pakistan, and India together.\
![image](https://user-images.githubusercontent.com/90793884/144786294-264ccac2-15ba-4eb7-af53-2634af4895a3.png)\
From observing the graph we see that both the average yearly temperature change values and the temperature change vs year graph of each country are very close matches of each other. This result shows a strong correlation between highly polluted countries and temperature change per year. Assuming there is reasonable causation between this trend then it can be predicted that if global warming continues as it is now then these countries will surpass 1.25 celsius per year before 2030.\
\
&emsp; Similarly, we looked at the countries with the highest populations to see if any correlation existed with their yearly temperature change, using China, India, and the United States.\
![image](https://user-images.githubusercontent.com/90793884/144786565-5ef300c8-d9cc-489a-9f8f-83426fb598bf.png)\
Likemost other examples used up until this point, each country appears to be experiencing a steady increase over time. While America and China align a little bit in the middle years (approximately 1985-1997), the graphs do not line up or appear that similar for the other portions outside on the general trends. India also appears to have experienced a significantly lower increase in temperature over time with its graph distinctly below the others at many points, especially in more recent years (approximately 1996). In sum, it doesn't appear as though there is a strong relationship between population and climate change with just this data. There could be a relationship tying them together such as pollution, but that is just speculation at this point with this data.\
\
&emsp; Next, instead of picking categories we might expect to see trends in we instead wanted to find all the outlier yearly temperture change countries with respect to the average and see if they had anything in common. After filtering the data for the countries with the lowest covariance with respect to the average we found that the top 3 were Chile, Argentina, and Antarctica. These lowest covariance countries all were found to have temperature changes per year much lower than the global average. Another thing in common between these countries is that they're all very south of the equator. This is an interesting result as our analysis of northern countries would suggest the latitude of countries has no affect on temperature change as the only difference geographically speaking between northern and southern countries is the timing of their seasons, however this should average out to be the same per year regardless. Though it's also important to note that most northern countries are generally more popullated, cover a larger area, and have a lower pollution index than southern countries. With this in mind its difficult to determine if the low covariance is due to latitude, one of the afforementioned factors, or some combination.\
\
&emsp; Lastly, we worked backwards by selecting the top three highest average temperature increase and the top three countries with the lowest average temperature increase to see if there were any common factors linking them. The top three highest countries (Mongolia, Svalbard and Jan Mayen Islands, and Gambia) did not appear to have much in common in terms of geographical traits.  One is a far north island territory, one is on the African coast near the equator, the other is inland north of the equator. One standout however was Svalbard and Jan Mayen Islands. Each of Mongolia and Gambia were slightly above the global average temperature increase and fairly consistently so. Svalbard and Jan Mayen Islands had fairly volatile temperature changes that deeped deep into the negative and high into the positive.\
![image](https://user-images.githubusercontent.com/90793884/144933352-b7c885a9-4fcf-4190-b3ed-c5ec29d73b11.png)\
While the three lowest countries (Antarctica, Saint Pierre and Milquelon, and Chile) had the common trait of coastlines bordering the ocean, this relationship cannot yet be accurately verified as one of the highest countries, Svalbard and Jan Mayen Islands, is also an island nation and has a coastline on the ocean. Their change line stays below the global average more often than not, often only going over one year at a time with a couple instances for two years and only once staying over for three consecutive years.\
![image](https://user-images.githubusercontent.com/90793884/144933504-e686084e-2aba-4be4-a896-7a59ec4140b0.png)
## Conclusion
**Reflection**
>&emsp; While performing data analysis on this data set, we set out to answer 8 major questions we had about the data. These questions focused on how climate change in each country was affected by; economic status, latitude, seasonal difference, pollution rates, population, how it compares to the global average rates, and how the countries with the greatest and least yearly fluctuations compare to the global average rates respectively. There was little to no correlation found when exploring how population, economic status, and the countries with the greatest and least yearly fluctuations with respect to the global average rates, affected the change in yearly temperature. This is likely due to there being many other factors affecting the temperature increase at once. However, the seasonal variations, pollution, countries with low covariance with respect to the global average rates, and latitude showed some correlation to the increase in yearly temperature change. However, there may not be direct causality due to other underlying factors being present. The biggest limitations with this data set were the lack of correlation, or the false correlation between data trends such as the relation between the yearly change in temperature and the latitude of the country. While these data points showed a moderate correlation, this may be due to an unforeseen factor such as landmass size or the amount of coastal distance the country possesses. These limitations can be resolved by taking the data analysis further with another project that seeks to create an algorithm that can predict a country’s temperature change. From assessing this data, we have learned much about how climate change is affected by many factors including location and pollution, in addition to learning how to confront some of the difficulties that arise when performing data analysis. This includes learning how to more efficiently work with data frames, with respect to graphing and rearranging.
#
**Refinement**
>&emsp; While working through our analysis question we discovered a strange outlier consistent with all countries' yearly temperature change, and that outlier was a large spike in temperature around 1990. From this, a new project could be proposed to create three algorithms, one from 1961-1990, the second from 1990-2019, and the third from 1961-2019. Then, over the next few years, see which one better predicts the change in yearly temperature. As well as the data can be further analyzed to improve the understanding of the correlation between data points that may show correlation, but may have underlying attributes that affect the trends.
## Acknowledgements 
>&emsp; This project was submitted as the final course project for CSCI 2000U “Scientific Data Analysis” during Fall 2021. The authors certify that the work in this repository is original and that all appropriate resources are rightfully cited.

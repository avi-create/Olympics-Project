# Olympics-Project


Olympics is a popular event. It first began in 1896 - Athens, Greece. The 5 rings in the logo represent the five continents:- Europe, Africa, Asia, The Americas and Oceania.
In this Project we have performed Data Analysis using Python to analyze and visualize past Olympics data.

Let's Start
We will import the following libraries:-

![Capture1](https://user-images.githubusercontent.com/79398731/188259705-9169d0f8-bc70-42d3-8cfa-732f2c2f2b04.PNG)


The next thing is to load the dataset using pandas read_csv function.

![Capture2](https://user-images.githubusercontent.com/79398731/188259870-c0ed9d1a-3210-4444-ba8e-f6faf8629cd1.PNG)


Now we will merge both the dataframes with Left Join with common column name 'NOC'. Now one thing to note here is all the colunns are not consistent last two columns start with a lower case letter.

![Capture3](https://user-images.githubusercontent.com/79398731/188261103-64547646-382a-4f97-9d50-6c5d56a545c6.PNG)


Now we will make column names consistent by renaming it and using inplace = True it will change the column name and reflect in the data. And to verify we can use the head function again.

![Capture4](https://user-images.githubusercontent.com/79398731/188261421-883e11d3-74e6-46b4-814b-a4ef5f59bc80.PNG)


Checking NULL values in the column it will display the result in boolean value such as TRUE OR FALSE.
There are 6 columns where we have missig values.

![Capture5](https://user-images.githubusercontent.com/79398731/188261874-5feee9be-af7f-494f-9b54-929d68ab729e.PNG)


Now we will check how many NULL values does the columns have

![Capture6](https://user-images.githubusercontent.com/79398731/188261971-c560e58c-f9e1-462d-89da-ce17bbc3a675.PNG)


The athletes participated in the game from the beginning for India for that we can filter over result using the function called query.
Here we have Top 5 rows of India

![Capture7](https://user-images.githubusercontent.com/79398731/188262435-8ecae6fc-109f-4986-ae9f-bd01fd929647.PNG)


The athletes participated in the game from the beginning for Japan for that we can filter over result using the function called query.
Here we have Top 5 rows of Japan

![Capture8](https://user-images.githubusercontent.com/79398731/188262488-4ca5bf61-dbd5-4ac8-9181-1c189a3242f3.PNG)


Now we will take the data of top 10 countries who have participated since 1896 in the inception of Olympics.

![Capture9](https://user-images.githubusercontent.com/79398731/188262863-50f644ca-11b3-4af8-8a0d-ba61de5edc52.PNG)


Showing through the Barplot Top 10 countries participated in the Olympics.

![Capture10](https://user-images.githubusercontent.com/79398731/188263022-dd29ed1b-453e-4093-ad08-e9ff2dad33ef.PNG)


Next we will see the age distribution of the Athletes for this we will create a Histogram. I will pass my dataset athletes_df in it and will bins in it by using arange function. This is a nice histogram if we say this we have most number of athletes who have a age between 20 to 30. We also have athletes beyond 40 year of age even closer to 60 also and few athletes under 18 years of age.

![Capture11](https://user-images.githubusercontent.com/79398731/188276970-77ca200a-8eb5-4ac6-8f4f-516361bb7070.PNG)


Let's look at the different sporting events that are part of the summer and winter olympic. Winter games are held every four years for sports practice on snow and ice.

![Capture12](https://user-images.githubusercontent.com/79398731/188277353-a620a24a-7ee9-4fe1-8782-18d7394353a6.PNG)


Next analyzing the total number of male and female participants who have taken part in different games since 1896 till 2016 rio olympics.

![Capture13](https://user-images.githubusercontent.com/79398731/188278735-1dbc5f37-fd78-46eb-9f66-9d2cdbe5e5ac.PNG)


Here I am trying to plot a pie chart for male and female athletes, for male it is 72.5% for female so far it is 27.5% as per the dataset that I have.

![Capture14](https://user-images.githubusercontent.com/79398731/188278952-9b9793e9-b246-42a5-80c2-de815a65be09.PNG)


Next I will be finding total number of medals that athletes have won. We can see that all the three medals numbers are very much similar to each other.

![Capture15](https://user-images.githubusercontent.com/79398731/188279098-a64316d7-9958-4dff-bb78-3426e174e606.PNG)


Total number of female athletes in olympics in each season in this we are finding female athletes in Summer Season in diffrent Years.

![Capture16](https://user-images.githubusercontent.com/79398731/188279474-b487ccc1-3e63-4dbe-8da0-d045940dbf4b.PNG)


I am visualizing the Female athletes of Summer Season in different Years using countplot. At the bottom we can see the value form 1900 to 2016. And 2016 had the highest number of female participation.

![Capture17](https://user-images.githubusercontent.com/79398731/188279838-d2004f26-1dc2-4e7c-b8fe-99a31a4beca0.PNG)


Next I am trying to plot line graph.Women participaation has increased in Olympics since its inception there was a slight decrese in 1950s and again there is a decrease in Women Participation in 1980 but since then there has been continuous increase in the participation of Female Athlete numbers.

![Capture18](https://user-images.githubusercontent.com/79398731/188280202-3c832fdd-4678-4d8c-af66-0268e71bacb9.PNG)


Filter the data to see the athletes who have won Gold Medals.

![Capture19](https://user-images.githubusercontent.com/79398731/188280275-c1dad34a-7ba9-44e1-b909-13031358e462.PNG)


I will check how many participants won Gold Medal beyond the Age of 60 for which Sports.

![Capture20](https://user-images.githubusercontent.com/79398731/188280665-1768ec63-6e08-421e-ac09-d134f4631a79.PNG)


I will plot same table of Sporting event with the help of Countplot. 3 players who secure the Gold Medal in Archery in the Age more than 60 years and for others there are 1 medal in different sports.

![Capture21](https://user-images.githubusercontent.com/79398731/188281125-4088a269-365a-42b7-bbb3-8b2bf2e65bfb.PNG)


Next I will filter the data for gold medals from each country. USA  has secured the most number of gold medals than other countries.

![Capture22](https://user-images.githubusercontent.com/79398731/188281359-a4af0ede-6ea4-4fc9-90ad-39d484c9a4fe.PNG)


I am going to create a plot to visualize the table that I got above using my catplot function that is present in my seaborn library. USA has got most number of gold medals then we have Russia, Germany, UK, Italy and France.

![Capture23](https://user-images.githubusercontent.com/79398731/188281837-ccaa9f52-e96c-4c15-9cb2-5e71bab1a2dd.PNG)


Now I wil analyze and look at the data for the most recent olympic event that is present in over dataset of 2016 Rio Summer Olympics And Top 10 teams who has secured Gold Medals in 2016 year.

![Capture24](https://user-images.githubusercontent.com/79398731/188282624-0b5e9acc-2da9-437f-a87e-cfb6fb75841a.PNG)


From the above result I am going to create a bar plot. You can see here I am having horizontal Bar Plot. So we are having United States at the Top. Since I am displaying the 20 nations by usimh the head function.

![Capture25](https://user-images.githubusercontent.com/79398731/188282918-258194ee-c994-4f4e-b089-b81383d4486f.PNG)


Now at the end I am plotting a scatterplot to visualize the height and weight of male and female athletes who have won a medal, it can be any medal.

![Capture26](https://user-images.githubusercontent.com/79398731/188283250-eb9fed48-5706-496e-81ff-3f9ecaa62cc2.PNG)



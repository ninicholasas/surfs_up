# surfs_up

##  Overview of the Analysis
The goal of this analysis is to determine whether opening a Surf & Ice Cream sho in Hawaii year around will be ideal.
Climate data that we used was collected at numersous weather stations on the Island of Oahu.

We used Python's SQL Alchemy library to connect to the SQLite database.
The temperatures that we compared were from June to December, 2010 to 2017.

## Results
Below image is the temperature data for June.


<img width="138" alt="June_temps" src="https://user-images.githubusercontent.com/110373282/217356580-1bf739b3-3714-4495-8fea-708d7bb3a00f.png">


Next, the Below image is the temperature data for December.



<img width="171" alt="Dec_temps" src="https://user-images.githubusercontent.com/110373282/217356623-4e3190f8-c78c-4a20-a50f-1fe15915bfd3.png">

## Summary
From comparing the above 2 results, 
* The average temperature for June is __75°F__ and December is __71°F__ ,
* the minimum recorded temperature for June was __64°F__ and December was __56°__,
* the temperature difference between the maximum and minimum for June was __21__ and December was __27__.

### Recomendation
Assuming that the June is the hottest month and the December is the coldest month within the year, the idea of opening the shops seems ideal.

If we want to deep in a little more, I recommend getting a specific location where to open the shop and filtering the weather stations that is to recieve data that is farely closer to the shop.
Also, assuming that the shop will not be open 24 hours, if we can filter the weather data within business hours we would be able to get a better grasp on the temperature to decide to open the shops or not.

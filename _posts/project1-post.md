Project 1
================
Craig Lazarski
October 3, 2021

- Project Scope and Findings

For this project I analyzed the current weather data API. I created functions that allow anyone to access current weather conditions such as temperature data, wind data, air quality, pollutants, humidity, etc. 

For my analysis, I focused on the air quality index. More specifically, I focused on Carbon Monoxide and Ozone levels. I wanted to explore how they contribute to the overall air quality index for a specific location. 

What I found is that ozone does not contribute as much to a city's air quality index rating as does Carbon Monoxide. I also investigated the relationship between Ozone and Carbon Monoxide, but no signficant relation seems to exist between these two measures. Overall, the results are possibly suspect as the data I collected are from a single moment in time, and it may be the case that exploring averages over time could yield more meaningful relationships.



- Project Reflection

-- Project Challenges


1. Querying the API posed many challenges in this project. First, I started with the Pokemon API just to get a sense of how querying works. Since it did not require registering for a key, I figured that would be easier. 

It took some time and googling but eventually I began feeling comfortable with querying. Then I realized I know nothing about Pokemon, so I switched to the weather API which seemed like a good source of data. 

Unfortunately I realized too late that the particular API I was using would only give me access to current data rather than historical data, so this limited my exploration. But, I still managed to do some good data exploration and found there were some unique things I coudl do with the data.


2. Writing functions. This was rather straight forward. Once I figured out how the API was returning information, and where to go hunting for it, I was able to point the query to the correct place.

3. Getting the data. Since the API only returned current information I needed to query it numerous times to obtain a data set of any substantial size. 

Unfortunately, this weather API does not like you doing that. I was forced to restrict my search to 100 cities. This still presented some problems. I could get some data, but then sometimes I would get blocked, and had to move on. 

The other hurdle in this process was realizing that the list of cities I was using to query the API had strange characters for some cities and it would return a 404 error. I looked further and found that my data file also had the ASCII names for the cities which I was able to use to help avoid this error. 

4. Finalizing everything. One dark hole I fell into was that my working directory was not set to the project directory and I continually received errors. I copied my markdown file to another location in fear that I would overwrite it and loose it, knowing full well that a backup was on GitHub because I had posted my changes there. But I still don't trust GitHub enough.

Regardless, I apparently started working on the moved file and not the one in my project directory. An hour later, after the tears subsided, I got back to work. 

5. Going forward: Overall I thought this project was very interesting and I learned some new skills. R continues to be the frustration as it often won't do what I want it to do, and figuring out what is not working is very frustrating.

I would like to know how to better understand errors and how to trouble shoot my code. I think the biggest time sink of the project was troubleshooting. I had the correct idea, but maybe a variable was not called correctly, or a comma went missing, or some other syntax error rather than a conceptual error was to blame.

- GitHub repo for this project

Github pages repo:  

[https://clazarski.github.io/ST558_project/](https://clazarski.github.io/ST558_project/)
  
Regular repo:  

[https://github.com/clazarski/ST558_project](https://github.com/clazarski/ST558_project)

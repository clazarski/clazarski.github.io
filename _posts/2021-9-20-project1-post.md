Project 1
================
Craig Lazarski
October 3, 2021

• explaining what you did in the project and any interesting findings 

For this project I analyzed the current weather data API. I created functions that allowed me (or anyone) to access current weather conditions such as temperature data, wind data, air quality, pollutants, humidity, etc. For my analysis, I focused on the air quality index. I focused on Carbon Monoxide and Ozone and wanted to explore how they contribute to the overall air quality index for a specific location. I found that ozone does not contribute as much to a cities air quality index rating as Carbon Monoxide does. I also looked at the relationship between Ozone and Carbon Monoxide and did not find anything signficant. Overall, the results are possibly suspect as the data I collected are from a single moment in time and exploring the averages over time may yield more meaningful relationships.

• You should also reflect on the process you went through for this project. Discuss things like: – what was the most difficult part of the logic and programming for you? – what would you do differently in approaching a similar project in the future? 

Where to begin with the challenges:
1. Querrying the API. I started with the Pokemon API just to get a sense of how querrying works. Since it did not require a key I figured that would be easier. It took some time and googling but eventually I began feeling comfortable with querrying. Then I realized I know nothing about Pokemon so I switched to the weatehr API which seemed like a good source of data. Unfortunately I realized too late that the API would only give me access to current data rather than historical data so it limited my exploration, but I could still do some good exploring with that data.

2. Writing functions. This was rather straight forward. Once I figured out how the API was returning information and where to go hunting for it I was able to point the querry to the correct place.

3. Getting the data. Since the API only returned current information I needed to querry it numerous times to obtain a data set of any substantial size. Unfortunately, the API does not like you doing that. I was forced to restrict my search to 100 cities. It still did not like this but I could get my data, get blocked, and move on. The other hurdle in this process was realizing that the list of cities I was using to query the API had strange characters for some cities and it would return a 404 error. I looked further and found that my datafile also had the acii names for the cities which removed this error. 

4. Finalizing everything. One dark hole I fell into was that my working directory was not project directory and I continually received errors. I copied my markdown file to another location in fear that I would overwite it and loose it, knowing full well that a backup was on github because I posted my changes, but I still don't trust github enough. Regardless, I apparently started working on the moved file and not the one in my project directory. An hour later, after the tears subsided, I got back to work. 

5. Going forward: Overall I thought this project was very interesting and I learned some new skills. R continues to be the frustration as it won't do what I want it to do and figuring out what is not working is very frustrating. I would like to know how to better understand errors and how to trouble shoot my code. I think the biggest time sink of the project was troubleshooting. I had the correct idea but maybe a variable was not called correctly, or a comma went missing, or some other syntax error rather than a conceptual error was to blame. 


• In your blog post, provide a link to your github pages repo and the usual repo as well! The URL to this (rendered) blog post is what you will submit at the project assignment link

Github pages repo:  
[https://clazarski.github.io/ST558_project/](Link)
  
Regular repo:  
[https://clazarski.github.io/ST558_project/](Link)

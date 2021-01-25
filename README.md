### tableauChallenge
### ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
#### The aim of this exercise was to identify interesting phenomena in the [Citi Bike System for New York City](https://www.citibikenyc.com/system-data).

##### Here's what I did:
* Downloaded and connected two Citi Bike datasets in the form of csv files. One file included 2019 data, while the other file included 2020 data. Both files are included in this GitHub repo.
* I first binned bikers according to age. The bin width was 10 years. I then plotted the distribution of biker ages for both 2019 and 2020. I also filtered the data according to gender. I plotted these data as bar plots.
* Using the same binned age data, I also plotted the average duration of each ride according to age and gender. 
* One interesting observation from this analysis is the notable jump in ridership among the 10-20 age demographic from 2019 to 2020. This observation might reflect an increase in young riders during the pandemic. These plots are included in a dashboard.
* I also made to map plots. One plot shows the popularity of each bike station, in terms of end ride location. The second plot shows the average duration of each rental (binned) according to each bike station. These plots are included in a second dashboard. 
* Finally, I made a story that displays my plots.

##### Some pitfalls:
* I initially struggled a bit to display the X-axis title for my plots. I fixed this by changing the binned age data (i.e. columns) from 'discrete' to 'continuous'.
* I learned that you cannot push large files to GitHub (by default). The limit for uploading files from the website GUI is 25MB. The limit for pushing files at the command line is 100 MB. I found a fix. I first went to this [YouTube video](https://www.youtube.com/watch?v=LZv4qCllJRQ). That video suggested I use [Git Large File Storage (LFS)](https://git-lfs.github.com/). I followed the instructions and cloned the repo to a directory on my local machine (laptop) using GitBash. I normally clone repos on my server. It worked!

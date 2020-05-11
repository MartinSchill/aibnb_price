**Airbnb Price Prediction**

**Overview**

Airbnb, founded in 2008, is a internet platform for bookings and reservation of mostly private apartements and houses. It allows home-owners and renters (‘hosts’) to put their properties (‘listings’) online, so that guests can pay to stay in them. 

**How should I choose my listing's price?**

Here is the answer on Airbnb's Website in the Help Center:

*The price you charge for your listing is completely up to you. To inform your decision about what price to set, you can search for comparable listings in your city or neighborhood to get an idea of market prices.*

Once you have choosen your base price, the algorithm will vary the daily price around that base price on each day depending on day of the week, seasonality, how far away the date is, and other factors.

**Goal of this project?**

There are several motivations that drive this project. I use airbnb quite often, since I like to travel and I also wanted to apply machine learning skills to a subject that almost anyone has heard of and can relate to. 
It is important to work with a reasonable big dataset, so I chose with Paris a City that provides 67.323 listings.
For a lot people around the world Paris represents the city of love and since I recently got married maybe it is a trip worth and we will use Airbnb. 
When it comes to the price, Airbnb gives suggestions to the hosts about the base price and adjustments in certain seasons, but when talking to hosts as research for this project, in their experiences prices proved to be way lower than they could have gotten for their appartements. I want to investigate what drives the adverticed price of properties and give hosts advice how they can optimize their apartment in order to get more money out of it. The biggest problem is: If you set the price too high then no one will book the place. Is the price too low, you’ll be missing out on a lot of potential income.

**The dataset**

I will perform an analysis of the detailed Paris listings data, sourced from the Inside Airbnb website (http://insideairbnb.com/get-the-data.html) in order to understand the rental landscape. The dataset is named listings.csv.gz and was scraped on March 15th 2020 (week of the lockdown due to corona). It consists of 67.323 listings. A GeoJSON file of Paris borough boundaries was also downloaded from the same site. Quite a bit of preprocessing has to be done with the dataset. It contains as mentioned above the advertised price of the appartment and not the average amount paid per night. Therefore I will eliminate in the course of the analysis unrealistic prices to also make the model more stable. Neverless the dataset offers a lot of information that can be analysed, preprocessed and used for the modeling.

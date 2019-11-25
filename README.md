# Profitable App Profiles

This is a guided project under Dataquest (Data Engineering track) where I provided mobile app profiles that could be profitable in Google Play and App Store markets. The app profiles will be utilized by a company in building English apps that are free to download and install. 

I used two data sets for the data analysis:
* A [data set](https://www.kaggle.com/lava18/google-play-store-apps) about 9,000+ Android apps from Google Play; the apps were last updated on August 2018
* A [data set](https://www.kaggle.com/ramamet4/app-store-apple-data-set-10k-apps) about 7,000+ iOS apps from the App Store; the data was collected on July 2017

I employed the following methods for data analysis:
* Opening and exploration of `android` and `ios` data sets
* Cleaning of data sets
    * Removal of wrong data in `android`
    * Removal of duplicate entries
    * Removal of non-English apps 
    * Isolation of free apps
* Determination of the most common Android apps by category and genre
* Determination of the most common iOS apps by genre
* Determination of Android apps with the most number of users by category and genre
* Determination of iOs apps with the most number of users by genre

Results of the data analysis show English free apps with applications to social networking, photography, and video have the most number of users in both Google Play and the App Store. 

| Rank | Most installed app categories (Google Play) | Most installed app genres (Google Play) | Most rated  app genres (App Store) |
|:----:|:-------------------------------------------:|:---------------------------------------:|:----------------------------------:|
|   1  |                COMMUNICATION                |              Communication              |             Navigation             |
|   2  |                VIDEO_PLAYERS                |       Adventure;Action & Adventure      |              Reference             |
|   3  |                    SOCIAL                   |         Video Players & Editors         |          Social Networking         |
|   4  |                 PHOTOGRAPHY                 |                  Social                 |                Music               |
|   5  |                 PRODUCTIVITY                |                  Arcade                 |               Weather              |
|   6  |                     GAME                    |                  Casual                 |                Book                |
|   7  |               TRAVEL_AND_LOCAL              |        Puzzle;Action & Adventure        |            Food & Drink            |
|   8  |                ENTERTAINMENT                |               Photography               |               Finance              |
|   9  |                    TOOLS                    |      Educational;Action & Adventure     |            Photo & Video           |
|  10  |              NEWS_AND_MAGAZINES             |               Productivity              |               Travel               |

Please see the full exploratory data analysis in the `Project 1.ipynb` notebook above.

 

#  Google Play Store App Analysis
## by Harutaka Kawamura


## Dataset
The dataset contains all the details of the applications on Google Play. There are 13 features that describe a given app. [Link](https://www.kaggle.com/lava18/google-play-store-apps/home)
- **App**: Application name
- **Category**: Category the app belongs to
- **Rating**: Overall user rating of the app (as when scraped)
- **Reviews**: Number of user reviews for the app (as when scraped)
- **Size**: Size of the app (as when scraped)
- **Installs**: Number of user downloads/installs for the app (as when scraped)
- **Type**: Paid or Free
- **Price**: Price of the app (as when scraped)
- **Content**: Rating Age group the app is targeted at - Children / Mature 21+ / Adult
- **Genres**: An app can belong to multiple genres (apart from its main category). For eg, a musical family game will belong to Music, Game, Family genres.
- **Last Updated**: Date when the app was last updated on Play Store (as when scraped)
- **Current Ver**: Current version of the app available on Play Store (as when scraped)
- **Android Ver**: Min required Android version (as when scraped)


## Summary of Findings
- The average rating is 4.17.
- `family` is the most popular category.
- `personalization` and `medical` apps tend not to be free.
- `medical` and `family` apps tend to be expensive.
- `game` apps tend to have a larger file size.
- Positive correlation between `rating` and `reviews`.



## Key Insights for Presentation
- Added a line to the chart of rating distribution so that it's easier to see where the average rating is located.
- Removed meaningless colors.
- Make the font size a little bigger
- Adjusted the chart size to make it fit the slide.

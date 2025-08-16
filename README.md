# movie_recommendation_system_streamlit
This is a machine learning project that builds a personalized movie recommendation system using a dataset. The system leverages Python libraries like Streamlit, Scikit-learn, Pandas, NumPy, and Pickle to create an interactive and user-friendly web app for suggesting movies.
*Data Collection and Processing*
First, I collected the movie data from the TMDb API, which provides details such as movie names, genres, cast, and overviews.
I fetched this raw data through the API and then exported it into a CSV file so that it could be easily stored and reused.
Once the data was in CSV format, I performed several processing steps:
Cleaning the data – removing missing values and duplicates.
Feature extraction – selecting important details like genre, cast, and overview.
Text preprocessing – converting all text into lowercase, removing unnecessary symbols, and preparing it for further analysis.
By doing this, I transformed raw movie data into a clean and structured dataset, ready for building the recommendation model.

# FireSpace-FrontEnd
https://fire-space-front-end-git-main-edison16as-projects.vercel.app/

Welcome to 🔥 FlameSense
Using Machine Learning and Palantir AIP to Revolutionize wildfire spread prediction

Predict Fires
Data Collection
Step 1: Data Collection
We gathered current and historical wildfire and conditions data from various sources such as NASA FIRMS and Open Meteo. We collected factors such as humidity, temperature, dryness, and biomass. We then used Palantir's tools to clean and transform the data.

Data Cleaning
Step 2: Training
We then used the cleaned data to train a model in Palantir which would take in current data inputs such as humidity, temperature, dryness, and biomass and outputs a predicted fire radius.

Data Integration
Step 3: Exposing Function
We then converted the model into a typescript function. Then we exposed the function to be called through javascript.

Model Training
Step 4: FrontEnd
We built a front end in HTML which displays a map and animates how the fire will spread depending on a location.

Interactive Visualization
Future Plans
We plan to expand our model and train it with more data to make a more accurate prediction.

# FireSpace-FrontEnd
https://fire-space-front-end-git-main-edison16as-projects.vercel.app/

At Los Altos, we built FlameSense, which helps first responders and the public by simulating wildfire spread using a sequential neural network trained on historical fire data and current weather conditions like temperature, humidity, and wind. Users can select locations on a map to see predicted fire growth visualized as a heat map, helping with better resource planning and awareness. 

3rd Place

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

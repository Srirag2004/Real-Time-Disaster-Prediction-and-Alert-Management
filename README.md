# Real-Time Earthquake Alert System using LSTM

This project is a deep learning–based real-time earthquake alert system designed to enhance disaster preparedness. It uses **LSTM-based Recurrent Neural Networks** to analyze seismic patterns and predict the likelihood of a severe earthquake.

## Features

- Real-time monitoring: Fetches seismic activity data every minute using the USGS API.
- LSTM model: Trained on time-series data (magnitude, depth, frequency) to detect anomalies.
- Geolocation awareness: Uses reverse geocoding to provide real-world location names.
- Distance calculation: Implements the Haversine formula to check proximity to the user's location.
- Email alert system: Sends alerts when the earthquake is severe *and* nearby. Sends a "No disaster" message otherwise.

## Technologies Used

- Python
- Google Colab
- LSTM (TensorFlow / Keras)
- USGS Earthquake API
- Reverse Geocoding (Geopy / Google Maps API)
- Haversine formula
- SMTP (Email automation)

## How It Works

1. Pulls earthquake data from the USGS API.
2. Feeds the data into an LSTM model trained to detect patterns in seismic activity.
3. Converts latitude and longitude to location names using reverse geocoding.
4. Computes the distance between the user's current location and the epicenter.
5. Sends an email alert if a severe earthquake is within a critical radius.

## Sample Output

![alert-output](2fc51cb7-edcf-48c1-b5cf-571cadfe9577.png)

## Run it on Colab

[Click here to run the notebook on Google Colab](https://colab.research.google.com/drive/1ZpbHMCr-GH4mRAZYQ8Qtzc-8_9Th_MLR?authuser=2)

## Contact

For any questions or collaboration ideas, feel free to reach out!  
Developer: Pranav Srirag Punnamaraju  
Email: sriragpunnamaraju@gmail.com  
GitHub: [github.com/Srirag2004](https://github.com/Srirag2004)

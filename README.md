

# CPSC222

Projects for Gonzaga CPSC222 taught by Bryan Fischer.

Welcome to this repository! I created this space for my own self-reference and to assist others in their learning journey by sharing my successes, as well as the mistakes, I've made along the way. The content here is intended to improve your knowledge and skills.



<p align="center" width="100%">
    <img width="50%" src="https://github.com/GU-Student-Projects/CPSC222/blob/main/images/enumerated%20energy.png?raw=true">
</p>

## **Data Science and Analysis**: Predicting Weather based on Music Listening Patterns

Report by: Gabriel DiMartino for CPSC 222 Intro to Data Science

For this project, Spotify Listening data and Weather data for Alexandria VA. I am researching this domain, because I am interested in the applications my Spotify. If a correlation between Spotify and the Weather exists, other factors such as mental health might be predictable. The data format for this project consisted of a mix between CSV and JSON. Because of the poor quality of Spotify data, The SpotiPY API was used to add additional information such as dance ability and energy for each song. The result was a CSV containing critical data for each song. The tables included in these datasets are: **Alexandria Weather** and **Spotify API Data**.

As mentioned earlier, the data for **Spotify** was collected both from Spotify Listening and the Spotify Python API. Similarly, the **Alexandria Weather** was collected from sources such as the National Weather Service. Combined, the tables make up 1900 instances for the months of **June - August**, with the weather data being repeated to match the several instances of music.

The relevant instances of the Spotify Data include:

* **Date:** Attribute to merge both datasets
* **Dancebility:** Attribute bound between 0 and 1

* **Energy:** Attribute bound between 0 and 1
* **Loudness:** Attribute bound between 0 and -20

* **Speechness:** Attribute bound between 0 and 1
* **Acousticness:** Attribute bound between 0 and 1

* **Instrumentalness:** Attribute bound between 0 and 1
* **Liveness:** Attribute bound between 0 and 1

* **Valence:** Attribute bound between 0 and 1
* **Tempo:** Attribute determined by the beats per second.

The relevant instances of the Weather Data include:

* **Date:** Attribute to merge both datasets
* **Conditions:** 5 classifications for the type of weather

From this data, I am attempting to classify the type of weather, based on my music history. The potential impact of this analysis is the use of my Spotify data to classify other meaningful attributes such as mental health or current activity. If this methodology can be generalized, potential stakeholders and benefactors from this research include psychologists and psychiatrists who could use similar methods to determine depression or bi-polar states.

## Disclaimer

I must emphasize that academic integrity is of utmost importance. Plagiarism and cheating can have severe consequences, and it's crucial to maintain ethical practices in your academic pursuits. Be aware that professors are informed about the existence of this repository and may use anti-cheat software to detect any similarities in code or solutions.

For more information regarding academic honesty and the guidelines set forth by Gonzaga's Center for Student Academic Success, please visit [Gonzaga&#39;s Academic Integrity Policy](https://gonzaga.azureedge.net/-/media/Website/Documents/Academics/Center-for-Student-Academic-Success/Academic-Integrity/Academic-Integrity-Policy-071822.ashx?rev=9f12e6775a184b9dadad248546f0e947).

Remember, learning is a journey, and I hope this repository can serve as a helpful guide in your educational endeavors. Let's all strive to achieve success with integrity and dedication!

## Images
### Varying Attributes Vs. Weather Conditions
<p align="center" width="100%">
    <img width="75%" src="https://github.com/GU-Student-Projects/CPSC222/blob/main/images/2x2%20graph.png?raw=true">
</p>

### Enumerated Conditions Decision Tree
<p align="center" width="100%">
    <img width="75%" src="https://github.com/GU-Student-Projects/CPSC222/blob/main/images/output.png?raw=true">
</p>

### Binary Conditions Decision Tree
<p align="center" width="100%">
    <img width="75%" src="https://github.com/GU-Student-Projects/CPSC222/blob/main/images/binary%20tree.png?raw=true">
</p>

## Usage

All projects require python 3.x to run. Similarly, dependent libraries can be installed using:
```sh
pip install -r requirements.txt
```
If you intend to utilize the **Spotify Web API** utility you must create an apikey.py: 
```sh
#apikey.py
CLIENT_KEY = 'Your_Key'
SECRET_KEY = 'Your_Secret'
```
To find this info, please refer to the Spotify API docs on creating a developer account.
## License

This project is licensed under the MIT License. See the **LICENSE** file for details.

## Credits

This project was developed by **Gabe DiMartino** for public use and help with Gonzaga CPSC222 assignments.

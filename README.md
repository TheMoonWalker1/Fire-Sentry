# Fire-Sentry

## Inspiration

**Public Safety:** Wildfires can cause significant damage to property and infrastructure, as well as threaten the lives of people and animals. A wildfire predictor can help alert people to the potential danger of a wildfire and give them time to evacuate or prepare for the worst.

**Environmental Protection:** Wildfires can have a devastating impact on the environment, destroying habitats and causing significant damage to ecosystems. By predicting and preventing wildfires, we can help protect our planet and the species that call it home.

**Economic Impact:** Wildfires can also have a significant impact on the economy, with the cost of fighting fires and repairing damage reaching billions of dollars. Predicting and preventing wildfires can help reduce these costs and protect jobs and businesses that may be affected.

## What it does

Using **Multi-Layer Perceptron** and **Random Tree Classifier** machine learning models, we were able to predict the occurrence of wildfires across the United States. 

You can start typing any address into the Address Bar and it will bring up the autocomplete for it (alternatively, you can just use the latitude and longitude). It will then bring up an image for the specified area and show the chance of a wildfire in the area based on current satellite data and location.

## How we built it

We used Django and a plethora of APIs from many different providers. It also includes a inhumane amount of css and js making the website a smooth experience for the user.

## Challenges we ran into

Creating a wildfire predicting model presented several challenges, including integrating APIs, a lack of data, cross-validation between two models, and finding the perfect ML algorithms. We had to navigate the complexities of integrating multiple APIs to obtain the necessary input data for our model. Moreover, we faced challenges in acquiring sufficient data to train our model, and we had to be creative in our approach to address this issue. Additionally, we encountered difficulty in cross-validating between two models, which required careful calibration and optimization. Finally, finding the perfect ML algorithms required extensive experimentation and testing to ensure that our model achieved the highest possible accuracy. 

## Accomplishments that we're proud of

Developed a machine learning workflow to predict wildfire occurrence based on input data such as NDVI, LST, and TA.

Integrated multiple APIs to obtain current and accurate input data for our model.

Addressed challenges related to a lack of data by using data augmentation techniques and ensuring that our model was robust to various input scenarios.
Conducted cross-validation between two models to ensure accuracy and reliability.

Created a web app to make the wildfire prediction model widely accessible to the public, increasing awareness and promoting timely mitigation efforts.

Contributed to the larger effort of preventing and minimizing the impact of wildfires, potentially saving lives and minimizing property damage.


## What's next for Fire Sentry

**Interactive Map:** We want to integrate an interactive map allowing users to just pick a latitude and longitude by clicking on any point on the map.

**Global Coverage:** We want to be able to create a model that covers more than just the United States

**Real-Time Threat Alerts:** We want to be able to create real-time threat alerts for people in high-risk areas when a wildfire starts.
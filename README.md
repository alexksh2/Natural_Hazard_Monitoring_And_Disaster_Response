# Natural_Hazard_Monitoring_And_Disaster_Response


__Natural hazard monitoring and response__ encompass a range of activities aimed at understanding, forecasting, and mitigating the impacts of natural phenomena that can cause significant harm to people, property, and the environment. These hazards include earthquakes, volcanic eruptions, floods, hurricanes, tornadoes, landslides, and tsunamis, among others. The process involves several key steps: __detection and monitoring, risk assessment, early warning, and response strategies__.
<br>
<br>
Early detection of wildfires is critical for effective response and management. This is achieved through a combination of ground patrols, fire lookout towers, and advanced technologies. __Satellite imagery and remote sensing technology play a significant role in detecting hotspots and monitoring fire progression in real-time. Drones equipped with cameras and sensors can provide detailed information about a fire’s location, size, and behavior, allowing for quicker and more informed decision-making__.
<br>
<br>
Once a wildfire is detected, response efforts are mobilized to contain and suppress the fire. This can involve ground crews using hand tools and heavy machinery to create containment lines, as well as aerial resources like helicopters and planes dropping water or fire retardant. The strategy and resources deployed depend on the fire’s characteristics and the terrain. Effective coordination among local, state, and federal agencies, as well as international cooperation in some cases, is crucial for the successful suppression of large wildfires


## Problem
Spanning across the different regions of Indonesia as well as the rest of Southeast Asia (SEA), forest fires have resulted in substantial economic losses estimated at USD 16.1 billion in 2015 alone; the deaths of 24 children and adults by December of that same year; geopolitical tensions within SEA due to the haze; environmental damage such as biodiversity loss and haze (Purnomo et. al, 2019). 



## Model Architecture
Our proposed approach to forest fire monitoring and disaster response is built around three key elements: predictive analytics, reactive strategies, and human intervention.
In the predictive phase, we employ a Long Short-Term Memory (LSTM) neural network model, designed for time series forecasting, to predict future temperatures. These predicted temperature values are then fed into an Artificial Neural Network (ANN) to forecast the likelihood of forest fires occurring. This combination of LSTM and ANN models forms a cohesive ensemble neural network architecture, engineered to deliver more accurate predictions as compared to a single model

<br>

### 1. Predictive Capabilities
  The LSTM model will be used to forecast temperature, and the predictions will be utilised as one of the input features of ANN models to predict wildfire occurrence, thereby addressing the limited predictive capabilities of the FireCNN model deployed by Aalto researchers in Indonesia (Barker, N. 2023).

<br>
<br>

![Architecture-of-the-LSTM-ANN-network](https://github.com/alexksh2/Natural_Hazard_Monitoring_And_Disaster_Response/assets/138288828/c2816772-1483-488b-9e96-799851f24e4a)

<br>

### 2. Reactive Approach
  While the ensemble deep learning model could generate accurate predictions on wildfire occurrence, it is essential to recognise that wildfires may arise due to human ignition, as reported by 87% of United States wildfire incidents (Joosse, T. 2020). In these inherently complex scenarios, the LSTM-ANN model may be insufficient in managing wildfires and thus our approach will further leverage on image feature recognition capabilities of CNN model. Through the analysis of satellite images, the CNN model allows large-scale real-time surveillance of forest fires in remote and inaccessible areas (Zheng, S. et al. 2024).
![CNN Architecture](https://github.com/alexksh2/Natural_Hazard_Monitoring_And_Disaster_Response/assets/138288828/b48059d2-59aa-4a19-b421-41f21b0996e5)





## The Dataset

https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data
https://archive.ics.uci.edu/dataset/162/forest+fires
https://www.kaggle.com/datasets/brsdincer/wildfire-detection-image-data

## Citation

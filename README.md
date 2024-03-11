# Natural_Hazard_Monitoring_And_Disaster_Response


__Natural hazard monitoring and response__ encompass a range of activities aimed at understanding, forecasting, and mitigating the impacts of natural phenomena that can cause significant harm to people, property, and the environment. These hazards include earthquakes, volcanic eruptions, floods, hurricanes, tornadoes, landslides, and tsunamis, among others. The process involves several key steps: __detection and monitoring, risk assessment, early warning, and response strategies__.
<br>
<br>
Early detection of wildfires is critical for effective response and management. This is achieved through a combination of ground patrols, fire lookout towers, and advanced technologies. __Satellite imagery and remote sensing technology play a significant role in detecting hotspots and monitoring fire progression in real-time. Drones equipped with cameras and sensors can provide detailed information about a fire’s location, size, and behavior, allowing for quicker and more informed decision-making__.
<br>
<br>
Once a wildfire is detected, response efforts are mobilized to contain and suppress the fire. This can involve ground crews using hand tools and heavy machinery to create containment lines, as well as aerial resources like helicopters and planes dropping water or fire retardant. The strategy and resources deployed depend on the fire’s characteristics and the terrain. Effective coordination among local, state, and federal agencies, as well as international cooperation in some cases, is crucial for the successful suppression of large wildfires

<br>
<br>

## Model Architecture
Our proposed approach to forest fire monitoring and disaster response is built around three key elements: predictive analytics, reactive strategies, and human intervention.
__In the predictive phase, we will deploy a Long Short-Term Memory (LSTM) neural network model, designed for time series forecasting, to predict future temperatures. These predicted temperature values are then fed into an Artificial Neural Network (ANN) to forecast the likelihood of forest fires occurring__. This combination of LSTM and ANN models forms a cohesive ensemble neural network architecture, engineered to deliver more accurate predictions as compared to a single model.



## The Dataset

__A. LSTM model__: https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data 
<br> 
<br>
The Dataset is fully dedicated for the developers who want to train the model on Weather Forecasting for Indian climate. This dataset provides data from 1st January 2013 to 24th April 2017 in the city of Delhi, India.
While the LSTM model is trained on this dataset, other datasets relating to Indonesian climate can be used to train the model

__B. ANN model__: https://archive.ics.uci.edu/dataset/162/forest+fires 
<br> 
<br>
__C. CNN model__: https://www.kaggle.com/datasets/brsdincer/wildfire-detection-image-data <br>


## Prediction Result

1. ANN model has over 70% predictive accuracy
2. Correct Predictions on Test Image for CNN Model

<br>
<br> 

__Test Image abc175 (Prediction: Fire)__ <br>
![abc175](https://github.com/alexksh2/Natural_Hazard_Monitoring_And_Disaster_Response/assets/138288828/2eec62f5-c8d6-4f4a-ba7f-f9e044bc60bf)

__Test Image abc363 (Prediction: No Fire)__ <br>
![abc363](https://github.com/alexksh2/Natural_Hazard_Monitoring_And_Disaster_Response/assets/138288828/ed4d72bb-69a4-4559-9cab-d1a6e899a4f4)



## Citation
Barker, N. (2023, August 24). AI model by Aalto University team can predict how to prevent wildfires. Dezeen. https://www.dezeen.com/2023/08/24/ai-wildfire-model-firecnn-aalto-university-aitopia/#:~:text=Named%20FireCNN%20after%20its%20use <br>

Zheng, S., Zou, X., Gao, P., Zhang, Q., Hu, F., Zhou, Y., Wu, Z., Wang, W., & Chen, S. (2024). A Forest Fire Recognition Method Based on Modified Deep CNN Model. Forests, 15(1), 111. https://doi.org/10.3390/f15010111 <br>

Joosse, T. (2020, December 8). Human-sparked wildfires are more destructive than those caused by nature. Www.science.org. https://www.science.org/content/article/human-sparked-wildfires-are-more-destructive-those-caused-nature <br>


Purnomo, H., Okarda, B., Shantiko, B., Achdiawan, R., Dermawan, A., Kartodihardjo, H., & Dewayani, A. A. (2019). Forest and Land Fires, Toxic Haze and Local Politics in  Indonesia. The International Forestry Review, 21(4), 486–500.  https://doi.org/10.1505/146554819827906799 <br>

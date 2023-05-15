1.Introduction![image](https://github.com/karim-saleeh/Project_1/assets/125829412/a0ef8db4-e14b-4695-8c06-82a907e95f1f)
Welcome to our housing company, a leading developer building new properties across the city. We are dedicated to creating exceptional homes that meet the diverse needs and aspirations of individuals and families. With our commitment to quality craftsmanship, innovative design, and attention to detail, we strive to exceed expectations and deliver homes that inspire and enrich lives. Join us on this exciting journey as we shape communities and provide desirable living spaces for a brighter future.

![image](https://github.com/karim-saleeh/Project_1/assets/125829412/f357018e-32d7-421e-82ff-8d811b94c92e)
2.problem formulation![image](https://github.com/karim-saleeh/Project_1/assets/125829412/679b0922-2fe8-4b52-9921-ec1352ac26d8)
The company aims to develop a forecasting model to predict the electricity demand of new properties being constructed throughout the city. This model will enable accurate estimation of future electricity consumption, aiding in resource planning and infrastructure development. The process involves collecting historical data on electricity usage from existing properties and gathering information on upcoming construction projects. Relevant features such as property size, ID, Temperature, humidity, precipitation, wind speed and solar irradiance will be analysed to identify trends and correlations. 
![image](https://github.com/karim-saleeh/Project_1/assets/125829412/55b4fe6e-a0ff-43b0-aac9-4e94d94cf727)
Various forecasting models, such as time series or machine learning algorithms, will be explored and trained using historical data. The trained model will then be used to forecast electricity demand for new properties based on their characteristics and expected completion dates. Continuous evaluation, adaptation, and improvement of the model will ensure its effectiveness in supporting decision-making for infrastructure development and resource allocation.

![image](https://github.com/karim-saleeh/Project_1/assets/125829412/2785923d-ed20-40a2-9edb-e138fee06d4f)
3.1Data![image](https://github.com/karim-saleeh/Project_1/assets/125829412/1e331590-a28c-4c58-934e-237651b06b9a)
Based on the information provided, it seems that existing DataStream was gathered from IOT devices or a device provider through API endpoints. The data collection period ranges from December 1, 2014, to November 30, 2015. The measurements recorded by sensors include several features such as temperature, humidity, precipitation, wind speed, and solar irradiance to calculate Electricity consumptions.
The data was collected at regular intervals of one hour throughout each day of the week, covering a duration of one year. This consistent time sequencing allows for a comprehensive understanding of the environmental conditions during that period.
![image](https://github.com/karim-saleeh/Project_1/assets/125829412/068396a1-6b12-492d-bae1-1cfb67e41318)
The availability of these diverse measurements, including temperature, humidity, precipitation, wind speed, and solar irradiance, provides valuable information for various analyses and applications. Researchers, climate scientists, and other stakeholders can utilize this dataset to study weather patterns, assess environmental impacts, develop predictive models, and evaluate the relationship between different factors.
It's important to note that this dataset represents a specific time period and should be used accordingly in analyses and forecasting models, considering the limitations and characteristics of the collected data during that timeframe.
![image](https://github.com/karim-saleeh/Project_1/assets/125829412/61083b36-8821-428d-a1d5-3cf0e42facf3)
4. proposed method ![image](https://github.com/karim-saleeh/Project_1/assets/125829412/6aba6e89-d085-49f9-99b9-55b6e6c96e8a)
We have three different algorithms with following R^2 results: 
  1. Using Normal Regression Ensemble model, with Ensemble R^2 Score: 91.4 %.
  2.Using Gradient Boosting Regressor, with R-squared: 98.0 % 
 3. Using Random Forest Regressor Model, which give more efficient results, with Ensemble R^2 Score: 99 %
As in following HTTM : 
http://localhost:8890/nbconvert/html/Desktop/Fekry-Project/PO.ipynb?download=false


![image](https://github.com/karim-saleeh/Project_1/assets/125829412/e6edb681-d393-4e24-a267-505ba077ecfe)

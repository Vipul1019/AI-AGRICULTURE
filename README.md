# AI-Agriculture


Soil moisture refers to the amount of water in the soil. It is an important component in plant development, agricultural output, and soil health. The amount of soil moisture changes based on various factors, including rainfall, temperature, humidity, wind, soil type, vegetation cover, and topography. The moisture content of the soil is essential for seed germination, nutrient uptake, and plant growth. Soil moisture can be measured using a variety of techniques, including gravimetric analysis, neutron probes, time-domain reflectometry, and capacitance sensors.
These technologies, however, are frequently time-consuming, costly, and unsuitable for large-scale applications. Precipitation, temperature, soil type, terrain, vegetation, and land use all have an impact on soil moisture. Soil moisture levels are influenced by precipitation and temperature, with places getting greater rainfall often having higher moisture levels.
Soil moisture is also affected by soil type and topography, with clay soils storing more moisture than sandy soils and flat terrain experiencing more water pooling. Plants can assist maintain moisture or compete for it, while human activities such as agriculture, urbanisation, and deforestation can all have an impact on soil moisture. Overall, soil moisture is a complicated interaction of various elements that affects plant growth, water availability, and ecosystem health.


# The dataset


The soil moisture forecasting dataset is a set of data points including information about numerous environmental conditions and soil moisture levels. It is commonly used to create models that forecast soil moisture levels based on input inputs. Here's an example of a dataset description:
Dataset Name: Soil Moisture Predicting Dataset provided by Cosmosoc Club Dataset Size: 20166 rows and 10 columns (where rows are the number
of observations and columns are the number of features) Features:

• pm - Particulate matter (1,2,3 is categorised into different sizes) : Particulate matter (PM) in soil refers to tiny solid and liquid particles that are
suspended in the air and can settle on the soil surface or penetrate into the
soil. PM in soil can originate from various sources, including natural sources
such as wind-blown dust, wildfires, and volcanic eruptions, as well as human
activities such as transportation, construction, and industrial processes.

• am - Atmospheric moisture: Atmospheric moisture in soil refers to the water vapor that is present in the air and can be absorbed by soil. The amount
of atmospheric moisture that soil can absorb depends on several factors, including the temperature, relative humidity, and wind speed.

• sm - Soil moisture : Soil moisture refers to the water content in soil, which
is a critical component of soil health and plant growth. Soil moisture is
typically measured as the amount of water in soil per unit of soil volume,
expressed as a percentage of soil water holding capacity.

• st - Soil temperature : Soil temperature in soil refers to the temperature
of the soil itself. Soil temperature can vary depending on several factors,
including climate, soil type, and moisture content. The temperature of the
soil can affect a wide range of biological, chemical, and physical processes
that occur in the soil.

• lum - Luminosity : Luminosity, or light intensity, in soil refers to the amount
of light that reaches the soil surface or penetrates into the soil. Light is a
critical factor for plant growth and development, as it is necessary for photosynthesis, which is the process by which plants convert light energy into
chemical energy.

• temp - Temperature : Soil temperature refers to the temperature of the
soil at a certain depth below the soil surface. The temperature of the soil can
vary depending on a variety of factors, including climate, soil type, moisture
content and depth.

• humd - Humidity : Humidity in soil refers to the amount of water vapor
that is present in the soil. The humidity level in soil can affect plant growth
and soil health, as it influences the water availability in the soil.

• pres - Pressure : Pressure in soil refers to the physical force exerted by
the soil particles and the weight of the overlying soil layers on the soil at a
certain depth below the soil surface. The pressure in soil can vary depending
on several factors, including the soil type, moisture content, and depth.




# About_the_model

Multiple linier regression

Multiple linear regression is a statistical approach for examining the relationship between two or more independent variables and a dependent variable.
It is an extension of simple linear regression in which just the relationship between a dependent variable and a single independent variable is considered. The purpose of multiple linear regression is to identify the straight line equation that best fits the data by minimising the sum of the squared errors between the predicted and actual values. Based on the values of the independent variables, this equation may then be used to predict the value of the dependent variable.

Multiple linear regression can be used for a variety of purposes, such as predicting sales based on advertising spending, analyzing the impact of different factors on the price of a house, or predicting a student’s grade based
on their test scores, attendance, and other factors.

#

Polynomial Linear Regression

Polynomial linear regression is a kind of linear regression in which the relationship between the dependent and independent variables is represented as an nth-degree polynomial function. When the relationship between the variables is not linear and cannot be expressed by a straight line, it is employed.
The purpose of polynomial linear regression is to obtain the best-fit curve that depicts the connection between the dependent and independent variables. This curve is a polynomial function of degree n, where n can be any positive integer other than 2 or 3.

Polynomial linear regression can be used to anticipate stock prices based on historical data, analyse the relationship between temperature and humidity, or estimate the performance of a product based on a range of criteria. It is a versatile and potent tool for simulating non-linear connections between variables. However, if the degree of the polynomial is too high, it is prone to over-fitting, and the model may not generalise effectively to new data.






# Results

Based on our examination of the data presented, the Multivariate Polynomial Regression model outperforms the Multivariate Linear Regression model. The Multivariate Polynomial Regression model has been developed, attained an accuracy of 88.37%, indicating that it can predict the as compared to the Multivariate Linear Regression model.



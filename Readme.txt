
Link to Jupyter notebook:https://github.com/vimalkurup/used_car_price_prediction/blob/master/m11_user_car_price_prediction.ipynb
GitHub Repo: https://github.com/vimalkurup/used_car_price_prediction

Business Problem
The goal of this project is to understand key features that help predict used car prices

Key Takeaway
- Car price decreases significantly every year, but the rate of that decrease diminishes as the car ages.
- Mileage(Odometer) negatively influences car prices
- Luxury Cars such as Morgan, Datsun, Aston Martin, Porshe, Rover go at a premium. Almost all other brands have no positive weightage on pricing
- Fuel Type: Electric and Hybrid cars are less favorable than traditional gas engines
- Offroad and Truck are sold are premium
- Region wise, there is marginal variations with east coast states like Connecticut and NJ penalized more; Likely due to rough winter weathers

Technicality
- Pandas for data reading/wranging/cleanup
- Seaborn for Visualization
- SKLearn for Pipelines, Encoding, Linear Regression, Ridge and GridSearch(Hyper parameter tuning)

Models evaluated
- Linear Regression
- Ridge

Assumptions
- Customers missing details on numbers of visits to Bar/Restaurant etc were assumed to have never visited

Credits
- https://github.com/toby-gardner-ai/uc-berkeley-aiml-course/blob/main/notebooks/Mod4_Data_Analytics.ipynb

Limitations
- Limited images uploaded because of space constraint. 
- Data file compressed and uploaded as CSV
- Lasso evaluation was restricted due to CPU limitations and lack on convergence


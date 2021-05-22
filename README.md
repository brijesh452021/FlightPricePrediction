This predictive model will predict the price of flight based on inputs such as Source, Destination, Departure Date, arrival Date, Stops, Airline etc.

Ensemble Technique (Random Forest Regression) is applied to get best outcome.

DataSet Overview:

![image](https://user-images.githubusercontent.com/81951806/119234655-ada34880-bb4c-11eb-8628-a401dd83d473.png)

Different feature engineering techniques are applied to retrieve important features like Day_of_Journey, Month_of_Journey, Arrival Hours, Departure Hours, Total no of stops etc.

![image](https://user-images.githubusercontent.com/81951806/119234764-21455580-bb4d-11eb-85ce-07ab6073d7dc.png)

Visualization of Source and Destination features to find Bivariate analysis.
Source:

![image](https://user-images.githubusercontent.com/81951806/119234831-8731dd00-bb4d-11eb-8f99-6e36c5951a1d.png)

Destination:

![image](https://user-images.githubusercontent.com/81951806/119234847-9dd83400-bb4d-11eb-942c-45cc36420d86.png)


Correlation of features using Heatmap is visualized so as to see which all features are correlated.

![image](https://user-images.githubusercontent.com/81951806/119234807-58b40200-bb4d-11eb-8bdf-eab8587f0afc.png)

Features Importance:

![image](https://user-images.githubusercontent.com/81951806/119234947-d11ac300-bb4d-11eb-8edf-802d93c7c785.png)

Training of model using Random Forest Regressor:

![image](https://user-images.githubusercontent.com/81951806/119234969-ea237400-bb4d-11eb-918a-b1efa7d566e6.png)

Distplot on test_y-predt

![image](https://user-images.githubusercontent.com/81951806/119235039-28209800-bb4e-11eb-936e-54e3ccb3897f.png)


Metrics:

![image](https://user-images.githubusercontent.com/81951806/119234984-fe677100-bb4d-11eb-84ec-6c3648d5a5bc.png)


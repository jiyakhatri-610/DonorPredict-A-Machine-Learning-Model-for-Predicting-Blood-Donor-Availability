# DonorPredict-A-Machine-Learning-Model-for-Predicting-Blood-Donor-Availability

Problem Statement

Blood banks face challenges in ensuring an adequate and timely supply of blood. Contacting all registered donors is inefficient, as many may not be available or willing to donate at a given time. Predicting donor availability using machine learning can help blood banks prioritize communication with donors who are more likely to respond, thereby improving operational efficiency and saving lives.

Objective

To build a machine learning model that predicts whether a donor is available to donate blood.
To use input features such as city, blood group, months since first donation, number of donations, and pints donated for prediction.
To assist blood banks in optimizing donor outreach and ensuring adequate blood supply.

Conclusion

The project implemented Logistic Regression and Random Forest models to predict donor availability. Both models achieved an accuracy of around 50%, indicating that the current dataset lacks strong predictive features. The results suggest that donor availability is influenced by behavioral and contextual factors (e.g., recent donation date, age, health, willingness) that are not captured in the dataset.

Thus, while this project provides a foundation for predicting donor availability, future improvements require:
Enriching the dataset with behavioral and health-related features.
Applying advanced models such as XGBoost or LightGBM.

Performing feature engineering and handling potential class imbalance.

With these enhancements, the system could become a practical tool for blood banks to improve donor communication and ensure timely blood supply.


[blood_donor_dataset.csv](https://github.com/user-attachments/files/22250529/blood_donor_dataset.csv)

[DonorPredict.ipynb](https://github.com/user-attachments/files/22250545/DonorPredict.ipynb)

[SQLfile.sql](https://github.com/user-attachments/files/22250548/SQLfile.sql)

<img width="1331" height="741" alt="image" src="https://github.com/user-attachments/assets/27a73ee7-a520-4ff1-870c-6b7ecda40d5d" />


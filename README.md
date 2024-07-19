
This Project is the application of explainable machine learning techniques for predicting and optimizing the center frequency of decoupling antennas in MIMO systems. A dataset of 294 unique antenna configurations was generated using CST Microwave Studio, focusing on varying dimensional parameters. Among various machine learning models tested, the XGBoost Regressor showed the best performance. Explainable AI techniques like SHAP analysis were used to interpret the model's predictions and identify influential parameters. The best model was integrated with an optimization algorithm to find optimal antenna dimensions for a target frequency. This approach significantly reduced design time and computational resources, offering a novel method for antenna optimization that combines electromagnetic simulation data with advanced machine learning techniques. The research demonstrates the potential of AI-assisted antenna design, with implications for more efficient and innovative approaches in modern wireless communication systems.


To try the project yourself,
if the dataset is directly from the cst parameter sweep then it will be of text format, then load the dataset and run the S12_txt_to_csv file.
Then load the obtained csv dataset and run the major file.

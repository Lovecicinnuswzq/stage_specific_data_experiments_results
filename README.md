# Experiment Results
## Experiment #1: Investigating the effectiveness of all-in-one and stage-specialized datasets with an equal number of training samples
This experiment examines whether all-in-one dataset (equally combining images from all construction stages) or stage-specialized dataset (tailored for each construction stage) yields better worker detection performance. Both datasets contain 10,000 worker instances, ensuring a fair comparison. The all-in-one trained model was evaluated across all the 13 test stages, while each stage-specialized trained model was evaluated on the corresponding test stage that matched the stage of the training data.

📥 Experiment #1 results (.xlsx) are available for further analysis

## Experiment #2: Investigating the effects of dataset size on model performance
This experiment explores how the number of training samples affects model performance. We train models using 2,000 to 40,000 instances of all-in-one datasets and 2,000 to 10,000 instances of stage-specialized datasets. The all-in-one trained model was evaluated across all the 13 test stages, while each stage-specialized trained model was evaluated on the corresponding test stage that matched the stage of the training data.

📥 Experiment #2 results (.xlsx) are available for further analysis

## Experiment #3: Assessing the robustness of all-in-one and stage-specialized models throughout the project lifecycle
This experiment evaluates how well all-in-one and stage-specialized models perform throughout all construction stages. we adopted the models trained with different data compositions (all-in-one and 13 stage-specialized datasets) and quantities (2,000 to 10,000) from Experiment #2, evaluating each model’s performance across all 13 test stages.

📥 Experiment #3 results (.xlsx) are available for further analysis

## 📌 Notes
- These experiments focus on worker detection, a critical task in construction monitoring.
- YOLOv8 was used for all experiments, with consistent hyperparameters and training strategies.

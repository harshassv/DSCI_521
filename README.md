# Human Activity Prediction based on sensor Data


This Project is aimed at developing a ML model about the user's physical activity based on sensor data. Primarily there are Two main sensors used to generate the dataset: Gyroscope and Accelerometer

Gyroscope : For identifying Position in 3D space

Accelerometer: For measuring Acceleration in 3D Space

## Potential applications


* Assist Smart Wearables manufacturers to bring-in exciting features like Workout Monitoring, Calorie Tracking.

* Develop Applications which can monitor the efficiency with which muscles contract and expand during workout

* Disrupt the robotic limbs industry, as it can assist people with disabilities in smartly in pre-maturely predicting the movement being made

## Dataset

* The dataset is publicly available on UCI.

* The dataset contains sensor readings from 2 different sensors worn by the participants, while they performed different physical activities.

* It contains data from 10 participants, who were asked to perform 12 different physical activities, including walking, standing, jumping, and cycling.

* Each instance in the dataset consists of 12 sensor readings and a label that indicates the corresponding activity.

* The sensors included in the dataset are the accelerometer and a gyroscope attached to the right wrist and left ankle of the subject.

## Sample Data Set

## Attributes in the dataset

## Categories of Activities recorded

## Models used

## Results


## Challenges Faced & Future Scope


* The axis of the sensors is not clearly mentioned, making it difficult to manually visualize the movement, which creates confusion.

* The data is unevenly distributed, with most of the data falling into Activity 0, which is None. To address this, we downsampled the data.

* If we include a heart rate sensor in this experiment, we could improve the project further.

* It is challenging to predict extra activities using only multiple predefined activities.

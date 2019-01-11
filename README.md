# knn-tensorflow.js

**K-nearest neighbors algorithm** implementation using **tensorflow.js**.

## Description:

K-nearest neighbors algorithm is used for **classification** and **regression problems**.
In this project, it is used for **regression problem**.
The algorithm determines the **value of an unseen data point** based on the **value of its neighbors**. It calculates **Euclidean distance**, a beefed up Pythagorean Theorem, to determine the **distance between a new point and the closest data**.

## Project goal and data set:

In this project, the goal is to **determine the value of a house**.
To predict an accurate pricing for a house I used the **location** (latitude, longitude), the **size of the property** and the **size of the house**. The data set can be found in **kc_house_data.csv** file.

## Result:

Using 3 features of the data set and a value **k of 10** I get an **accuracy of 86.6%**.

## How to run analysis:

- Clone repository
- Install node packages (npm install)
- In the terminal under knn-tf directory run: node index.js

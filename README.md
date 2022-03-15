# MPG Predictions

## Effects of Horsepower Makes On Acceleration 
The higher the Horsepower the faster the acceleration is. This is due to the car producing more power to the wheels and engine allowing them to spin up faster. As a result of this allows the car to accelerate faster than cars with a lower horsepower. The spikes that have slower acceleration times but have higher power are more likely bigger cars. Bigger cars like trucks need more power to move their larger mass. Since they are bigger they won't accelerate as fast as a lightweight car with the same horsepower. 

![Effects of Acc on horsepower](https://user-images.githubusercontent.com/88803320/158435626-284e19e5-10d6-40eb-ad61-09d279765ccb.png)

## MPG Based On Model Year
As the years progressed cars got better MPG(Miles per gallon). This could be a coincidence or related to further technological advancements during this period. Also, MPG can vary from car to car. For example, cars that have higher horsepower might use more gas than the ones that don't. This is because the engine needs to use more gas to make the power. More gas used to make more power equals less MPG. 
![MPG Model year](https://user-images.githubusercontent.com/88803320/158435642-234a8226-f95f-4cc9-b737-1b799467c575.png)

## MPG Based On Engine Cylinders
Engine cylinders are the circles in the engine that hold the pistons to push the air and fuel to make power for the car. Cars with more cylinders means the engine can produce more power at a faster rate. However, this means the car will consume more gasoline. Based on this graph it's clear that the sweet spot is around 4 - 5 cylinder cars. 
![mpg based on cylinders](https://user-images.githubusercontent.com/88803320/158435641-6aa734fa-f018-4d24-a78c-4ba6d8b56f11.png)


# Machine Learning Models
These regression models used were to predict a car's MPG. Using features such as the engine's cylinders, engine displacement, horsepower, weight, acceleration, model year, and Country of origin. The graph below shows the difference in scores of a Kneighbors model and a Randomforest model. Both models performed very well the model that did the best on the testing was the Kneighbors model.
![model scores](https://user-images.githubusercontent.com/88803320/158435638-befd27f7-774c-487d-baf0-ea6c67f55587.png)
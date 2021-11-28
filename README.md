# CraftLikeABosch

Introducing the problem
15 000 large animal roadkills occur every year in Hungary, which is approximately 8 times more than pedestrian hits in a year. These accidents cause injuries and on average $2000 worth of damage to property. Our system aims to reduce the number of collisions by detecting near road animals in time to allow for deceleration and emergency braking. 
Most modern cars are equipped with pedestrian detection systems, like the “Multi Purpose Camera” of Bosch, which triggers emergency braking upon a detected obstacle in the way. But it is not suitable for wildlife detection, especially at country road speeds because it was developed mainly for urban environments.
Detecting fast moving animals in a forest is a hard task not just for a human driver but also for traditional cameras or sensors like radars, especially at night or in bad weather conditions. Our plan is to deploy infrared cameras because it can sense the emitted heat of the animals, which has a great contrast to its environment.

![image](https://user-images.githubusercontent.com/64794939/143733593-965c4630-96c5-4f42-9ec6-73b16745989e.png)
 
One camera is not enough, because it can not safely determine the exact position and velocity of the animal, so we decided to use two cameras, which makes it possible to use triangulation to calculate the distance of the detected animal. A great advantage of the two-camera system over the one is that it reduces measurement inaccuracy and false positive detections. 
Based on the position and current speed of the animal we can calculate the probability of a collision. If this probability is high our system intervenes. It alerts the driver and decelerates the car to a safer speed. Our system complements the Bosch “Multi Purpose Camera”, because at that slower speed the Bosch camera can detect the animal if it actually does jump on the road and can trigger the emergency braking system.
The project also focuses on sustainability. On one hand it protects the wildlife, which is ever more important in todays industrialized world. On the other hand, it decreases waste production as it saves many parts of the car from being destroyed in a crash.

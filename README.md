# AI-Gym-Trainer 

## Abstract

Over the last 1 to 2 years everyone has been confined to their homes without much physical activity. Hence, a personalized fitness trainer has the potential to replace a human trainer whenever possible. It can help various individuals to carry out routine exercises from the comfort of their homes without physically going to a gymnasium and performing the same. This gives a lot of flexibility and people can practice at a time of their choice, rather than a fixed time given by the trainer. 
However, due to public places being shut, it has led to disruption in daily routine and exercise patterns for everyone. Hence, many people have struggled with various health-related problems such as obesity, irregular sleep patterns, eye strain, mental stress, decreased immunity, and hence, are at a higher risk of getting infected with various health problems. Gyms generally have a variety of equipment and personal trainers are always there who can tell you what to do. The lack of these in one's home can often be the culprit that stops them from working out. 



## Idea

Many people watch YouTube videos, have wearable tech and train with personal gym trainers. But all of them have their disadvantages. While watching YouTube videos, no feedback is given and we have to manually keep count of the exercises. This distracts the person performing the exercise as a lot of things need to be tracked and there is no mechanism for the same. 
This is the problem our project aims to solve. We have developed a personal Gym Trainer using Artificial Intelligence. This gym trainer works on a real-time basis and keeps track of the exercises performed, repetitions in each exercise and the number of sets performed as well. However, it will also work if one uploads an already recorded video, but in order to make things easier we have decided to keep the monitoring in real time. Using our tool, users will be able to perform their daily exercises with ease from the comfort of their home without bothering too much about other things such as reps, sets, etc. 

## Challenges we ran into
We faced multiple challenges while developing this project

- using mediapipe to estimate poses
- writing our own function to estimate the angles
- counting the reps and sets for each exercise performed


## Future Scope

- Add in a mechanism to detect other exercises for the lower body parts
- Deploy this as a model to Heroku or AWS 
- A static website where users will be able to register and keep track of their daily exercises

# Vision-Impaired-Devices

## Introduction

Visually impaired individuals require devices to help them navigate safely and gain more independence. White canes, guide dogs, mobile apps, GPS navigation systems, and proximity sensors can all be useful tools to assist them in navigating safely and gaining independence.

This project aims to answer the following question: "How can we recreate vision for people with visual impairments using their other senses?"

To address this problem, we can divide the project into two main parts: "Capturing the Environment Around the User" and "Transcribing the Environment to the User."

![Vision Impaired Device](https://user-images.githubusercontent.com/104011562/233152904-8bf72270-7194-499a-96d4-f7d76c310171.png)

In the image, the right side represents the "capture" part, and the left side represents the "transcribe to the user" part.

## Capturing the Environment Around the User

To explain the work related to capturing the environment, I will let my friend provide insights.

## Transcribing the Environment to the User

As demonstrated in this [YouTube video](https://www.youtube.com/watch?v=8Au47gnXs0w&t=751s), this device offers a clear solution to the problem. Therefore, I challenged myself to build it.

### Mechanical Part

![Mechanical Part](https://user-images.githubusercontent.com/104011562/233153959-5646e358-56e5-452c-8b8d-ed4c711a51c4.png)

This demonstrates how the first part works. It's essential to understand the following points:

- When both motors turn, the body will also turn.
- When motor 2 turns, the body will translate.
By knowing this, you can control the position of all the cams.

![Mechanical Part Controls](https://user-images.githubusercontent.com/104011562/233154182-73125c4a-a232-4e36-925a-6fbe00bd30ca.png)

Now that we understand how to control the cams, we need to learn how to position all the axes. This involves selecting the desired cams - the GREEN, ORANGE, and RED ones - by moving the "Cams Body" and then releasing the purple "axis" by turning the "Cams Body" to free up the blue axis.

So, now that the mechanism's concept is clear, I have designed pieces to make these connections.

![Cams Body](https://user-images.githubusercontent.com/104011562/233156006-d698e286-2098-46bc-b8c9-ae004bfa967d.png)

This body is the "Cams Body" where all the cams rotate to actuate all the axes.

![Axis Actuators](https://user-images.githubusercontent.com/104011562/233156472-4a5b44ed-7ac3-4e1b-8f9d-28c5ae2776a2.png)
![Axis Actuators](https://user-images.githubusercontent.com/104011562/233790318-3fae29ab-db82-44b8-86be-0f1132740d0a.png)

These are all the nine axis actuators.

![System with Step Motors](https://user-images.githubusercontent.com/104011562/233156151-20a98e07-8b20-4391-935e-1860f5e5b1fc.png)

Here's the full system with the two step motors.

### Electronic Part

![Electronic Components](https://user-images.githubusercontent.com/104011562/233156635-ef0a69c6-36e2-47da-94d3-ca862e793e2d.png)
![Electronic Components](https://user-images.githubusercontent.com/104011562/233156736-9b3d91e0-7ec5-4ea2-b670-b066420bb09c.png)

### Experiments

1. Simulated I/O Law in Python vs. Experimental Results
![Experiment 1](https://user-images.githubusercontent.com/104011562/233789351-421c88be-5185-45d6-8b04-e02d3d9345ba.png)
![Experiment 1](https://user-images.githubusercontent.com/104011562/233789564-2051d869-8333-4dd4-9c65-cdd2dc5aed8d.png)

2. CAD (Computer-Aided Design) vs. Experimental Results
![Experiment 2](https://user-images.githubusercontent.com/104011562/233789397-b7b881c1-2051-454f-bf30-569db2625f41.png)
![Experiment 2](https://user-images.githubusercontent.com/104011562/233789588-8421911b-7f96-4794-b2fe-43be9d2f9729.png)

### Conclusion

![Conclusion](https://user-images.githubusercontent.com/104011562/233788835-853165fa-80de-4ed4-a08e-cf7ed33c525e.png)
![Conclusion](https://user-images.githubusercontent.com/104011562/233790218-9c0e78af-db92-4470-9638-81eec8cbb0e1.png)

This revised README provides a more accurate and readable description of the project and its components.

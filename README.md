# Vision-Impaired-Devices

## Intro
Visually impaired individuals need devices to help them navigate safely and gain more independence. White canes, guide dogs, mobile apps, GPS navigation systems, and proximity sensors can all be useful tools to assist them in navigating safely and gaining independence.

This project have to answer to the next question :
How to recreate a vision for the imperaid peaple with his valid sens ?

To answer this problem we can separate the project in two part on for the on "How to capture the environement around the user." and an another "How to 
transcribe the environment to the user".

![image](https://user-images.githubusercontent.com/104011562/233152904-8bf72270-7194-499a-96d4-f7d76c310171.png)

In the right a of the image there is the "capture" part and in the left there is the "transcribe to the user" part.

## How to capture the environement around the user ?

I will let my friend explain his work

## How to transcribe the environment to the user ?

As shown on YouTube, [Youtube](https://www.youtube.com/watch?v=8Au47gnXs0w&t=751s) this device provides a clear answer to the problem. So, I challenged myself to build 

### The mechanical part 

![image](https://user-images.githubusercontent.com/104011562/233153959-5646e358-56e5-452c-8b8d-ed4c711a51c4.png)

This demonstrates how the first part works. What's important to understand is:

 - When both motors turn, the body will also turn.
 - When motor 2 turns, the body will translate.
By knowing this, you can control the position of all the cams.
 
![image](https://user-images.githubusercontent.com/104011562/233154182-73125c4a-a232-4e36-925a-6fbe00bd30ca.png)

Now that we understand how to control the cams, we need to learn how to position all the axes. This involves selecting the desired cams - the GREEN, ORANGE, and RED ones - by moving the "Cams Body," and then releasing the purple "axis" by turning the "Cams Body" to free up the blue axis.

So now that the idea of the mecanism is fixe i have desined pieces to make these laison.

![image](https://user-images.githubusercontent.com/104011562/233156006-d698e286-2098-46bc-b8c9-ae004bfa967d.png)

this body is the cams body where all the cams rotate to actuate all the axis.

![image](https://user-images.githubusercontent.com/104011562/233156472-4a5b44ed-7ac3-4e1b-8f9d-28c5ae2776a2.png)
![image](https://user-images.githubusercontent.com/104011562/233790318-3fae29ab-db82-44b8-86be-0f1132740d0a.png)


and this is all the 9 axis actuator.

![image](https://user-images.githubusercontent.com/104011562/233156151-20a98e07-8b20-4391-935e-1860f5e5b1fc.png)
And here the full system with the two step motors.

### The electronical part

![image](https://user-images.githubusercontent.com/104011562/233156635-ef0a69c6-36e2-47da-94d3-ca862e793e2d.png)
![image](https://user-images.githubusercontent.com/104011562/233156736-9b3d91e0-7ec5-4ea2-b670-b066420bb09c.png)

### Experiences
1. Loi E/S simulée python vs résultat de l’expérience 
![image](https://user-images.githubusercontent.com/104011562/233789351-421c88be-5185-45d6-8b04-e02d3d9345ba.png)
![image](https://user-images.githubusercontent.com/104011562/233789564-2051d869-8333-4dd4-9c65-cdd2dc5aed8d.png)


2. CAO / Expérience :
![image](https://user-images.githubusercontent.com/104011562/233789397-b7b881c1-2051-454f-bf30-569db2625f41.png)
![image](https://user-images.githubusercontent.com/104011562/233789588-8421911b-7f96-4794-b2fe-43be9d2f9729.png)

### Finaly
![image](https://user-images.githubusercontent.com/104011562/233788835-853165fa-80de-4ed4-a08e-cf7ed33c525e.png)
![image](https://user-images.githubusercontent.com/104011562/233790218-9c0e78af-db92-4470-9638-81eec8cbb0e1.png)







---
layout: page
title: Projects
---

# Technical Projects

*For an overview of my project descriptions and research publications, see my [complete resume](resume.md)*

## **Space-Related R&D**

### **CubeSat Development Projects**
**MIT Beaver Works Summer Institute - Build a CubeSat Challenge**
- **Wildfire Tracking and Prediction from Space** (2024-2025) 
    - The satellite uses computer vision algorithms to detect and predict wildfire movement from space using satellites. Used a machine learning model to detect where the wildfires are, and used data from multiple passes to show fire spread. Then, the program makes predictions on where the fire will spread next.  
- **Mudslide Detection and Impact Assessment** (2023-2024) 
    - The CubeSat maps regions that are susceptible to mudslides by using machine learning, and alerting ground station if any new mudslides have been detected. 

### **NASA HUNCH Micro-Rover Development** (2024-2025)
*Captain, Lead Designer, Builder, and Programmer*
- **Durability** - The lunar regolith is abrasive, so we made the entire body of the rover out of 1/16" aluminum. By covering every hole, we made sure to completely isolate the delicate electronics from the regolith. 
- **Dual Control Systems** - Remote control and computer-based radio command interface. The rover can be controlled through both a Bluetooth Low Energy connected controller, or autonomously controlled through Long Range Radio at the 915Mhz frequency. 
- **Wireless image capture and transmission** - Uses a high resolution camera in the M5 Stack Camera X to capture photos, and uses the built in ESP 32 as a Wifi Access point to send the images to a computer
- **Wireless Software Updates** - Over-the-air programming system. Our rover is capable of executing python code that was transmitted over the radio. Because of this, we are able to edit files on the rover, which allows us to make software updates without even taking the rover apart. This system was inspired by the Ingenuity mission in Mars. 

    **[Link to website](https://sites.google.com/cfbmail.com/nasa-hunch-lunar-rover/designs)**


    **[Link to latest CAD Model](https://cad.onshape.com/documents/b768e7ff74cb64a2bd957713/w/f866da644b5ce7340ff3ff36/e/6890e63dd318aa4fd2992dfc)**

## **Application Development**

### **Technocise Exercise Tracking Platform** (2020)
*Innovative fitness technology using computer vision*
- **PoseNet Machine Learning** - Real-time human pose analysis through the PoseNet library. This was used to track the key points of the body, so whenever the body did an action, like a squat or a jumping jack, it is able to detect the motion and increment a counter. This way, it eliminates the reliance of a virtual instructor supervising all of the kids. 
- **Web Platform** - I incorporated this into a website which is able to work on any device. Also, we added a scoreboard and a leaderboard to increase competition between students in a class. 
- **Educational Impact** - This website was used by my school, where over 30 people used the app, with over 5000 counts recorded. 

### **Sidewalk Shaper Reporting App** (2020)
*Civic technology solution for infrastructure maintenance*
- **MIT App Inventor Development** - I led the creation of a mobile application built using visual programming blocks, making it accessible for deployment across Android devices and available on the Google Play Store.
- **Geolocation Integration** - The app captures real-time GPS coordinates to ensure the exact location identification of infrastructure damage for city records. This makes the whole process of finding and repairing broken sidewalks more efficient. 
- **Automated Reporting System** - The app emails photographs, GPS coordinates, and timestamp into structured reports sent directly to the city's maintenance departments. We collaborated with the city officials in Coppell and Lewisville to set up an official Sidewalk Shaper email address. 
- **User-Friendly Interface** - The app has a simple reporting process designed for citizen engagement. This allows for more community participation and helps fix the city's infrastructure.

### **Smart Container IoT System**
*Internet of Things tracking and monitoring solution*
- **Global Cargo Challenge** - The device is designed to address the critical issue where 50% of damaged cargo results from temperature and humidity fluctuations that can ruin vaccines, medicines, and food products. This happens during transit or storage.
- **Raspberry Pi Zero Integration** - Used Raspberry Pi Zero WH as the core processing unit, providing compact monitoring capabilities for individual containers.
- **DHT11 Environmental Sensing** - The sensor allowed us to have precise temperature and humidity monitoring with detection ranges from -67°F to 122°F and humidity sensing between 5% and 95%. This ensured that our solution could be used for all containers on storage areas.
- **Cloud Connectivity and API Integration** - Our app used an API which allowed us to have secure, real-time, data transmission as well as processing and data storage. The data is stored on a website. 
- **Industry Collaboration** - We connected with the United Nations and FedEx for professional feedback. We also wanted their input on where this app could be implemented in the real-world.

## **Research & Publications**

### **Solid Freeform Fabrication Symposium Papers** (2022-2024)
*International Conference on Additive Manufacturing - University of Texas at Austin*

**2024: "The Educational Value of 3D Printing CubeSats"**
- CubeSats only cost a few hundred dollars to manufacture, and they provide hands-on experience in 3D printing, CAD, and building, so I co-authored a paper showing the potential of CubeSats in education. 
- I was responsible for CADing the CubeSat. I came up with a reconfigurable 1U CubeSat architecture for student experiments, meaning that the solar panels can be adjusted and put at various angles. This allows students to experiment with which orientations best fit their design. 
- The whole CubeSat has a modular design which enables rapid prototyping and testing. 

**2023: "Cost-Effective 3D Printing Solutions for Educational Robotics"**
- This paper addresses the high-cost barriers in competitive robotics. Robotics kits often cost thousands of dollars, making access extremely difficult in certain situations. 
- We designed and open-sourced 3D printed structural components and mounting systems so that anyone with access to a 3D printer can get started with robotics. Almost anyone can access a 3D printer at their library, so this project makes learning more cost effective than other options. 
- Whereas other kits can cost upwards of $1000, the kit that we designed costs only around $100 for the structural components. This is due to the fact that we give the CAD models directly to the customer for them to 3D print rather than mill it out of aluminum ourselves. 

**2022: "Flat Pattern Simplification for Educational Manufacturing"**
- Cost-effective alternatives to commercial robotics kits due to the usage of flat, laser-cuttable parts that can easily be mass produced. 
- Milling parts out of aluminum takes a lot of time and material, but simplifying the geometry to only flat parts allows a laser to quickly cut out the part, and one flat sheet of plastic can be cut into multiple parts
- These parts form a build system that is compatible with open source electronics. The build system provides the same level of learning as a milled kit, but at a significantly lowered cost. 
- We formed the organization Robotics for Everyone in our goal to expand robotics to different regions. The CAD models for the parts are open-sourced on the Robotics for Everyone website. 

    Check out the Robotics for Everyone website [HERE](https://www.roboticsforeveryone.org/models)


### **2023: Pattern Discovery and Machine Learning Lab at UT Dallas**

**Vehicle Trajectory Prediction**
- Spent 30 hours per week for 10 weeks over the summer
- Used Pytorch, OpenCV, and Python
- I developed a CNN-based model in PyTorch to predict vehicle trajectories using a list of pre-generated paths. I achieved 83% accuracy out of 400+ paths.
- I then used the predicted trajectories of surrounding vehicles to enable an autonomous car to proactively avoid collisions using reinforcement learning. The car predicts the trajectories and learns to avoid hitting the other cars. I has able to dramatically reduce the chance of a collision compared to independently choosing the best trajectory. 


--- 
<br>


[Contact Me](contact.md)

[View Complete Resume](resume.md)

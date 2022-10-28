## Driver-Detection

# Problem-Statement:

Road accidents take place all over the world with over 5 crore people getting injuries due to them every year. Over 10 lakh people suffer from fatal road accidents every year around the Globe. Most of these accidents take place in low to middle-income countries like India and cost them about 3% of their GDP. 

Around 20% of traffic accidents are attributed to distracted or drowsy drivers.
People fear hiring drivers they don't know to drive for them, in the fear of such accidents. Tackling these issues can be difficult when our lifecycle does not align with avoiding drowsy driving. There is no efficient method deployed till now to alert drowsy or distracted drivers in real-time to prevent accidents.

# Proposed-Solution:

In-Vehicle driver monitoring systems are going to be a crucial element of vechicles of the future. One important function of such systems is to determine if the driver is paying attention to the raod. If not,the system alerts the driver to bring his/her attention back to the road. Some ways to accomplish this are to monitor the driver's eyes and the gaze of their eyes,also to check for single-handed driving. Our Solution to this would be based on Computer-Vision and Machine-Learning to make a device to check for drowsy or distracted driving and alert the driver to bring their attention back to the road.


### ***Visual Demonstration of drowsiness detector -***

[Check out the demo by clicking this :) ](https://drive.google.com/file/d/1fmqYH4RMO5OUlWsB76MoH1TPpBm2aCAq/view)


### ***Visual Demonstration of other distractions detector -***

[Check out the demo by clicking this :) ](https://drive.google.com/file/d/1usxD4NrBdcXiL1yXghTFk7x27mhuWfT5/view)

```
pip install -r requirements.txt  --For Hacktag.py

pip install -r requirements_side.txt  ---For Hacktag_SideCam.py
```

# File-Descriptions :

**hacktag.py  - Python Program to detect face and check for drowsiness**

**hacktag_SideCam.py - Python Program to use the ML model and classify video feed as safe driving or distracted driving**

**hacktag_sideview_modeltrain.ipynb - Colab notebook used for training the model**

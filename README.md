# TrafficAnalysis
Using Deep Learning to control a traffic signal to minimise the time it takes to clear out the traffic at any given point of the day, based on 20 years of back data, total car population available in the city and Week residue time.

**Software versions: Python 3.7, SUMO traffic simulator 1.2.0, tensorflow 2.0**

How to get started:
1. Clone the repository or download from github
2. Open anaconda promt and run the **trainingmain.py**
3. Now the model has started training 
4. Let the model train and then open SUMO GUI and then load the .sumocfg file.
5. Now as the model trains we can see the graphical and pictorial representations on screen.

 The end result on a cross-section should look like this when fired up correctly:
 
![tlc](https://user-images.githubusercontent.com/29151572/144835734-753e6622-4690-4e98-a627-92f15f87cf06.gif)

Future plans:
1. Adding real time data feeds
2. trying to connect multiple paths (T-points,Highways,Cross-lanes etc.) and then minimising the traffic clearing time as we go on create a complete map.

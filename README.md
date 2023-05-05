# PoleClock
![Pole Clock Image](https://github.com/nanamgo/PoleClock/blob/main/poleclock.png)
## overview
A simple pole clock game object for Unity.<br>
You can change the dial and hands of the clock to your favorite design by replacing the sprites.<br>
Since the material is set on the Unity side, you can change the texture to your liking.<br>
It also has a function to set the hands of the clock to the current time and a function to set the hands of the clock to any time.

## how to use
Download PoleClock.unitypackage and import it into your Unity project.<br>
After importing, there is a prefab in the folder, so drag and drop it to the Sense view.<br>
In ClockWorks.cs in the inspector, It have the following configuration properties:<br>
Set_time -> If checked, set the hands of the clock based on the values of Change_hour and Change_minutes.<br>
Set a value between 0 and 24 for Change_hour and between 0 and 60 for Change_minutes.

## version information
Unity 2021.3.8f1 -> Creation of PoleClock.unitypackage.<br>
Blender 3.1 -> Creation of 3DCG.<br>
ChatGPT 3.5, Bing -> Debugging assistance.

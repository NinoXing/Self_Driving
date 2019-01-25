Q:How to try this self driving model?
----
1. You may download the Udacity simulater Version 1 from https://github.com/udacity/self-driving-car-sim.<br> 
2. Download drive.py and model.h5 which is a Nvidia model I have already trained.<br> 
3. Before running drive.py, make sure you have all the package need with python3 version(I would recommend create a new environment to do this.)<br> 
4. Run drive.py in the terminal, then open the simulater and choose 800*600 resolution with fastest graphics quality<br>
5. Run Autonomous Mode
   
Q:What if I want to train my own model by creating my own data?
----
1. In the simulator, choose Training Mode.
2. Try to use the arrows on the keyboard to control the vehicle. When you are ready, click RECORD on top right and your driving behaviour will be recorded as data in your PC.
3. Upload your data to your GitHub.
4. You can download behavioural_cloning.py to train your model, but I recommend that you can use Behavioural_Cloning.ipynb in Google colab to do this, and don't forget to use GPU when you run the code.
5. Then you have your own model~

Several recommendation about creating training data
----
1. Driving only on one track to collect data, and after training your model, test on another track.
2. Try to drive in the middle of the road. Let us be good drivers :)
3. After driving in one direction several laps, don't forget to drive in another direction. If you don't do so, the car will be more inclined to turn in one direction(left or right).
4. If you find that your car is not performing well at one corner of a specific angle, you can record more times driving pass this kind of corner.

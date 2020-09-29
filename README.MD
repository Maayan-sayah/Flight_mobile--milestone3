
# Flight-Mobile--Milestone-5


#### Creators: 
##### Shira Turgeman & Noa Elishmereni & Maayan Sayyah

### **Basic information**
in purpose to control "Flight Simulator" we created an anodroid app. 
this application combained with NetCore server. the app sends a command, that passes to the server and next to the simulator.

### log in to the app: 
 <p align="center">
 <img src=".\android.png" width="250" height="460">
</p>
the user needs to insert local host. 
we use room instead of database, that save the last five local host which have been enters.

### **How does it work?**
1. Download FlightSimulator (Or any other simulator) in the next link- https://flightgear.en.uptodown.com/windows.
open the simulator, go to Setting, go to Additional Setting and add the next line: 
"--telnet=socket,in,10,127.0.0.1,5403,tcp --httpd=8080".

NOTE! you can choose to use python server. we added a server to this project for your convenience.

2. open the WebCore server- running the server will open a new html window with the communication information, such as the lock host port (should be 5 letters).
3. log in to the app server using the local host from the server. 
4. next you should see screen with the joystick and sliders (similar to milestone 3). 
pressing the different control tools will send a new command to the server and to the simulator. 

![Picture1](https://user-images.githubusercontent.com/60346583/94614090-492a3500-02ae-11eb-8b98-5b41622b3f1c.png)

#### **How to use**
1. when downloading the code from GitHub, a new zip directory will appear. 
please open the zip and Extract the code to a new directory that will be used from now- called "FlightMobile".
2. comprass all the file into a zip file called "FlightMobile"- all except the bat and server.
3. place the bat and server in the same directory in the same level as the zip called "FlightMobile".
4. make sure to leave the bat and zip only in the file, and nothing else but that. 
5. click the bat- and a new window will appear running the files. 
6. be advised the at will only run the server, in order to open the android app please use the "Android Studio" app.



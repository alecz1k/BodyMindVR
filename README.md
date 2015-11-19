# BodyMindVR
Open project to experiment and create VR games involving EEG &/or ECG &/or pulse sensor &/or respiratory belt.



MAJ: 18 NOV 2015


WHAT FOR: 
This project will allow you to experiment with VR headsets (Oculus Rift Dk2 and VRVana's Totem) and sensors such as EEG and ECG, pulse sensor, respiratory belt, through the usage of an OpenBCI or Arduino board. With this project, we have created a scene in which the player control the intensity of a campfire with his breathing. The scene is included in the project. Anyone is more than invited to help in the development of the project.



HOW TO:
For your sensors to communicate with Unity3D, you will need an OpenBCI or an Arduino REV3 board.
We used OpenBCI board with Openvibe (version 1.0.1) but it should work the same with an Arduino board. 
You can download OpenVibe here: http://openvibe.inria.fr/pub/bin/win32/ 
You will also need Python 2.7.10 (https://www.python.org/downloads/) and the superpackage "numpy" (http://sourceforge.net/projects/numpy/files/NumPy/1.10.1/) installed on your machine. 
You have to install numpy through the terminal cmd. 
Download the project BodyMindVR.
Install Oculus Rift Runtime 0.6.0.2 on your machine.
Launch "openvibe-acquisition-server" (located at C:Program Files/Openvibe).
Select Driver "OpenBCI (unstable), Connection Port: "1024", Sample Count: "32", and click on "Driver Properties".
Make sure your OpenBCI or Arduino board is connected to the matching port //./COM3 or //./COM4.
On the "Send Command on Init", set the line to: "x1060000Xx2060000X" and Click "Apply".
Back on the OpenViBE Acquisition Server, Click on "Connect".
Launch "openvibe-designer" (located at C:Program Files/Openvibe).
Click "File", "Open". Open the file "hackathon_coherence_openbci_manual" located in the "Neurovr" master folder.
Click the icon "Play". If the sensors are ready, you should see some movement already on your screen. 
Launch Unity3D (version 5.1.1f1) and open "Breathe@work" folder.
In Unity 3D, open the scene "test-oclus". That's it! You made it! Now you can help improve this project!

******************************

Initiated in Montreal, November 2015, by Jérémy Frey (@jfrey-phd), Alexandre Girardeau (@alecz1k), Kevin Ouellet (@kouellet), Sandy Carter (@bwrsandman), Bertrand Nepveu, Karl-Antoine Simoneau, Léa Charpentier, Aphisith Keosavang. 

******************************

More info will follow

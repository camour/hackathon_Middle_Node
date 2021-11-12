# hackathon_Middle_Node

This is the middle node of the project. 
Let's keep in mind, we have 4 main parts : The Sensors, the Middle Node, the Infrastructure Node and the User Wep Application

Here we focus on the Middle Node part.
This Middle Node has already been set up with the AE, CTs and ACPIs required for the project.

Project Installation : 

- Clone the project using the following line command : git clone https://github.com/camour/hackathon_Middle_Node.git
- Go under the repository you just cloned using the following command: cd hackathon_Middle_Node

Project Configuration :
- You only have to change the IP addresses
- To do so, you have to go into the "config.ini" file under "mn-cse/configuration" directory and edit the following lines : 
		"org.eclipse.om2m.cseBaseAddress=172.20.10.4" => change the IP address with the one the raspberry
		"org.eclipse.om2m.remoteCseAddress=172.20.10.5" => change the IP address with the one of the machine hosting the IN-CSE platform
		

Launch the program :

WARNING: BEFORE LAUNCHING THE PROGRAM, MAKE SURE YOU LAUNCHED THE IN-CSE program
- If you are on Windows, go under "./mn-cse/" directory and launch the file "start.bat" by double clicking on it
- If you are on Linux, open a terminal, using "cd" command, go under the "mn-cse" directory and run the following command : "./start.sh"
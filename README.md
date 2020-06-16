# Doom-Bot
It is an AI powered bot playing Doom-game using deep convolutional Q-Learning.
It is linux based AI powered model,we can save the videos of our AI playing doom and see it improve over time,though it learns very fast.
It find the best way to complete the level.The environment is from open ai gym.
In this level the ai must travel through a corridor full of enemies while surviving their attacks and finding the best way to complete the level while attaining high score.

Setup Instructions:
Please follow these steps to set up the VM: 

To setup the VM, you can install virtualbox for your OS: https://www.virtualbox.org/.

Once it's setup you can launch it and then go to file and import impliance. Once you install the OVA (the VM file) from https://www.dropbox.com/s/yxtfe4jjit04icy/Ubuntu.ova?dl=0, you can run the box. 


Please follow these steps to run Doom:


How to run the doom module

Login to the VM with password: sds

Then open a terminal and run:

source demo-env/bin/activate

cd Downloads
cd P20-Doom
cd Doom
python ai.py


Enjoy !

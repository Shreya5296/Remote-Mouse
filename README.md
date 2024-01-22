# Remote-Mouse

To make our remote mouse work, we need to install a fewl ibraries in our system
1. Using the Python pynput library, we can control and monitor input devices. Using pynput we are able to simulate mouse events into any window.
2. pynput.mouse contains classes for controlling and monitoring the mouse buttons & controller. The mouse is tracked and controlled by using the coordinate system of the screen.
3. screeninfo library is used to fetch location and size of physical screens.
4. autoPy is a GUI automation library for Python. It includes functions for controlling the keyboard and mouse

Go to Command prompt
● pip install pynput
● pip install screeninfo
● pip install autopy

If autopy is not installed properly:
Then try following steps:
pip install -U autopy
If that fails, install rustup and then run
pip install -U setuptools -rust
pip install -U autopy

When you run the server file, it will ask you for your IP address
Type ipconfig at the command prompt

To run the remote mouse- 
1. Download the main.py file
2. Upload the file to your mobile device
3. The Pydroid Py3 can be downloaded from the Play Store
4. Open Pydroid
5. Click on the rectangle type box
6. Click "open"
7. Upload the main.py file (see Phone download section)
8. Click on the yellow triangle icon in the bottom right corner
9. Below is a window that appears:
10. Enter the IP address of your computer. This should be the same one we used in the server side
11. Click on “Connect With PC”

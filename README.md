BUILD AND DEPLOY PYTHON APPLICATION IN MANUAL METHOD
•	Login in to amazon console and launch the instance and access it.
 
•	Download the git and clone the repository for git hub which we want host application, here I cloned the flight-prediction and check the list of it. 

•	By default AWS has python, Now install python with command<sudo amazon-linux-extras install python3.8>



•	Check the version.
 
•	Open the repo and check the files of it. And install python runtime in requirments.txt.
•	With command <pip3 install -r requirements.txt>
 
 
•	Execute the command the command <screen -m -d python
3 app.py> and copy the IP:9000 browse it in browser.
•	But it shows error.
•	We have to open app.py and remove sklearn packages or library in requirments.txt.
 
•	Now execute the command <screen -m -d python3 app.py>
and copy the IP:9000 browse it in browser.



![Uploading image.png…]()

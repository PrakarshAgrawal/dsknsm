# Instruction:

## Question 1
It is a Jupyter notebook. Can be run easily in jupyter or google colab. Graphs required in the question will be present in the notebook itself after running each of cell snippets.


## Question 2:

### Part A

Contains 2 folders. One folder contains server and client interacting using UDP codes and other TCP codes.
These can be run in VSCODE or any other code editor.

In either folder, use this code first in a terminal:

```
python server.py
```

Now open a new terminal. Use
```
python Client.py
```


### Part B

It is a 2 way chat application using UDP monitor app.<br>
Install the app in phone using: https://tinyurl.com/udpMonitor
<br>
Open server.py in vscode.
Connect Phone and laptop using hotspot. Modify the address in server.py code using status in network and internet settings and write **IPv4 address**.<br>
```
python server.py
```
As the client address is printed, write the local port in the UDP monitor app.
2 way chat app is ready.

## Question 3:

Run server using 
```
python server.py
```

Run Client using
```
python Client.py
```

Final round trip time and packet loss results will be printed in the output.

## Question 4:

It is a mail client
Just run the python file in VSCODE using:
```
python mail.py
```
Add your iitk username and password to connect to server.<br>
Add recepient address<br>
Add the message you want to send after adding the subject.
Mail will be sent to the recepient.

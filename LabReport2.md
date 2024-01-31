# Lab Report 2: Servers and SSH Keys

# Bennett Yarnell 

# Code for ChatServer:
![image](codeitself.png)

Above is my implentation of the ```ChatServer``` class, which creates two String arrays of the contents of the URL and accesses these arrays to print accurate messages on the locally hosted web server.

# Image 1 of ChatServer Running:
![image](serverRunning.png)

Above is how ```ChatServer``` behaves when given a correct URL and multiple entries. In this instance, the method ```handlerequest``` is called because ```addmessage``` is present in the URL. ```handlerequest``` turns the URL into string arrays and then access them, and then adds them to a master string so when entering different URLs the previous interactions are saved. (user: BennettY and user: haoting are an example of different URLs being entered and edited).

# Image 2 of ChatServer Running:
![image](failedURL.png)

Above is how ```ChatServer``` behaves when it is given a URL which does not have the substring ```addmessage``` inside it. In this case, the if condition in ```handlerequest``` is passed over and the else returns the string ```404 Not Found!```.



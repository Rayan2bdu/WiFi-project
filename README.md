Hey 

this is for my project about comparison between 2 wifi standards 802.11b and 802.11bc and compares their TCP and UDP and power consumptions. Its all Python scripts by Pycharm

to run those files and get the result:

step 1

You must install matplotlib and networkx in Bash terminal (bash:pip install matplotlib networkx) in windows and (bash:sudo pip install matplotlib networkx
) for linux

step 2

You must see if the ports are available for TCP and udp by entering the bash terminal and typing (bash:  netstat -ano | findstr "portnumber") if it's blank then it's available otherwise it's busy

you can use other available ports otherwise you use this (bash:taskkill /F /PID "pid id") to be able to use the same ports again (pid id) is the id you get when u run (bash:  netstat -ano | findstr "portnumber").


step 3

you have to run server.py first
then main.py


Good Luck!!

Hey this is my project about comparsion between 2 wifi standards 802.11b and 802.11bc and compare their tcp and udp and power consumptions. Its all python scripts by pycharm

to run this and get the result:

step 1

You must to install matplotlib and networkx in Bash terminal (bash:pip install matplotlib networkx) in windows and (bash:sudo pip install matplotlib networkx
) for linux

step 2

You must to see if the ports are available for tcp and udp by entering the bash terminal and type(bash:  netstat -ano | findstr "portnumber") if its blank then its available otherwise its busy
you can use other ports that are available otherwise you use this (bash:taskkill /F /PID "pid id") to be able to use the same port again (pid id) is the id you get when u run (bash:  netstat -ano | findstr "portnumber").


step 3

you have to run server.py first
then main.py

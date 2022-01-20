# Flower-timeout
Repo for investigation of timeouts that happens with prolonged training on clients. This repository is meant purely for demonstration of the problem. 
All the code is just modified original code of Flower's tutorial for purpose of demonstration. All the credit goes to the flower team. 

As of code modification, only run.sh files and server.py (server case) or client.py (client-1/-2) were modified to use a single partition and work over the internet.

Steps for replication:
1. Create 3 different virtual machines (I utilized Ubuntu 20.04.3 LTS)
2. Upload the code to the machines
3. Change server address in clients based on the address of your server
4. Make sure the specified port is open on the server
5. Activate poetry shell
6. Run the run.sh scripts


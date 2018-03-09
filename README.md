# Network-Parameters-Extraction
----This application connects to all the devices in GNS3 network trough SSH and extracts various performance parameters from each device, like the CPU utilization, processor memory or I/O memory etc.----


--SSH(Secure Shell Netwrok) is seperately explained in one of my projects in GItHub. "https://github.com/nihaljeena13/Secure-Shell-Network-Connectivity"


--When all the devices are connected through SSH, the commands are provided to each devices and the output from those commands are collected.
-- Then using "regular expressions" you can collect various performance parameters from the output such as CPU utilization, processor memory or I/O memory and then determines the average of those values and the top CPU or memory consumers in the network.
-- This application also extracts several other features for routers like the model, IOs version, serial numbers, cisco neighbors, routing prottocols and collects all the necessary network inventory.
-- All these information extracted is then collected into the database on the local machine and organized into tables.


configure SSHv2 on each routers.
Create a MySQL databae


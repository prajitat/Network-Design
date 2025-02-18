# Network-Design
I designed a network (using Packet Tracer) based on the requirements specified below.

NKU IT LLC has two office buildings (Griffin & Chase) in Cold Spring on the same campus. Each building has its own network. The two networks are connected to together since they belong to the same company. Thus, devices connected to the two subnets must be able to communicate with each other. 

The Griffin building has 10 employees of which six use Desktop PCs(connected to a  wired network) while four use Laptops connected to a wireless network. Users of Laptops and PCs are able to utilize resources shared on the network. The office has a File server and Printer that is shared by all employees in the building.

The Chase building has a wireless network and a wired network. The wireless network connects   five employees (employees connected to the wireless network use Laptops or tablets). The wired network (Chase building) has an application server that runs the Human Resources, Finance and Inventory software for the company. The CEO, HRM and Finance Director   have their computers connected to the wired network. The Chase office has one printer that is shared by all employees in the Chase building.

  Points to note:
  
With the exception of shared resources and router interfaces, all devices must be assigned IP addresses using DHCP. Ensure that there are no IP address overlaps for the subnets you create.

All addresses MUST be in the range of IP address for the project. Thus, no 192.168.X.X IP addresses should be used. 

Configure the network such that devices on different networks are able to communicate.

For each project group, the network address IP for NKU IT LLC is as shown in the table below

GROUP #	NETWOK ID	GROUP #	NETWOK ID

1    	172.16.4.0/22	  11	172.16.44.0/22

2	    172.16.8.0/22	  12	172.16.48.0/22

3	    172.16.12.0/22	13	172.16.52.0/22

4    	172.16.16.0/22	14	172.16.56.0/22

5	    172.16.20.0/22	15	172.16.60.0/22

6	    172.16.24.0/22	16	172.16.64.0/22

7	    172.16.28.0/22	17	172.16.68.0/22

8	    172.16.32.0/22	18	172.16.72.0/22

9	    172.16.36.0/22	19	172.16.76.0/22

10	  172.16.40.0/22	20	172.16.80.0/22

Based on the table above, group 1 would use the network address 172.16.4.0/22for NKU IT LLC.

Note that subnets have to be created based on the network address of NKU IT LLC.

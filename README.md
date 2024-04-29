INTERCONNECTION NETWORKS 

An interconnection network is used for exchanging data between two processors in a multistage network. In case of multiprocessor systems, the performance will be severely affected in case the data exchange between processors is delayed. 
The processors can access data from memory associated with another processor or from shared memory using an interconnection network. 
Thus, interconnection networks play a central role in determining the overall performance of the multiprocessor systems. The interconnection network is placed between various devices in the multiprocessor network.

VARIOUS INTERCONNECTION NETWORKS

Fully connected

This is the most powerful interconnection topology. In this each node is directly connected to all other nodes.
The shortcoming of this network is that it requires too many connections.Fully connected topology is a type of network configuration in which all nodes are directly connected to each other, without physical or logical limitations.
      
![image](https://github.com/karthiyayini-r/INTERCONNECTION-NETWORK/assets/168261634/003457ac-e082-4ff1-b5f3-4e0b4daba8bf)


Cross Bar

The crossbar network is the simplest interconnection network. It has a two dimensional grid of switches. 
It is a non-blocking network and provides connectivity between inputs and outputs and it is possible to join any of the inputs to any output.It allows the owners of the units to establish a private network link and eliminates the need to connect using the internet.

![image](https://github.com/karthiyayini-r/INTERCONNECTION-NETWORK/assets/168261634/02fa22b6-2dbc-4b24-950f-f8de5ede6e46)


Linear Array:

This is a most fundamental interconnection pattern. In this processors are connected in a linear one-dimensional array. The first and last processors are connected with one adjacent processor and the middle processing elements are connected with two adjacent processors. It is a one-dimensional interconnection network

![image](https://github.com/karthiyayini-r/INTERCONNECTION-NETWORK/assets/168261634/55a02857-2811-4296-b861-562fa52e80ac)


Mesh:

It is a two dimensional network. In this all processing elements are arranged in a two dimensional grid.A network configuration where devices are interconnected in a decentralized manner. Instead of relying on a central hub or switch, each device connects directly to multiple other devices, forming a mesh-like structure.

![image](https://github.com/karthiyayini-r/INTERCONNECTION-NETWORK/assets/168261634/be6eebf2-eb08-4a46-8cf3-943220f3224e)



Ring:


This is a simple linear array where the end nodes are connected. It is equivalent to a mesh with wrap around connections. The data transfer in one direction,a type of network configuration where devices are connected in a circular manner, forming a closed loop. In this setup, each device is connected to exactly two other devices, creating a continuous pathway for data transmission.


![image](https://github.com/karthiyayini-r/INTERCONNECTION-NETWORK/assets/168261634/0180d3a4-4df9-4d2d-b26f-a27bb97e83a2)

     
Torus:

The mesh network with wrap around connections is called Tours Network.Shorter link length which helps to reduce the time packet required to traverse in the interconnected links. Shorter link length also contributes to the reduction in interconnect area required for implementation.


![image](https://github.com/karthiyayini-r/INTERCONNECTION-NETWORK/assets/168261634/deb7a515-247c-4b14-8439-682eda6cc849)

Tree interconnection network

In the tree interconnection network, processors are arranged in a complete binary tree pattern. tree topology is a type of network topology that resembles a tree. In a tree topology, there is one central node (the “trunk”), and each node is connected to the central node through a single path. Nodes can be thought of as branches coming off of the trunk.


     






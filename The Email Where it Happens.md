![c1](https://github.com/MDaleyJr/Files/blob/main/TheEmailWhereItHappens1.png)
## Open the wireshark pcap and notice there is a UDP Payload running throughout
![c1](https://github.com/MDaleyJr/Files/blob/main/TheEmailWhereItHappens2.png)
## Right click a packet then go to Follow > UDP Stream
## Download and save the Raw data as raw
![c1](https://github.com/MDaleyJr/Files/blob/main/TheEmailWhereItHappens3.png)
## Open a terminal and run strings with an output to raw2
![c1](https://github.com/MDaleyJr/Files/blob/main/TheEmailWhereItHappens4.png)
## go to Cyber Chef and drop raw2 into the input with Base32 as the recipe
## email revealed with the flag in the message
![c1](https://github.com/MDaleyJr/Files/blob/main/TheEmailWhereItHappens5.png)

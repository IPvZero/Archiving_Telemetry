# Nornir - Archiving Telemetry

This code is based off my video: "Nornir (Python Network Automation) | Archiving Telemetry", which can be found [here](https://www.youtube.com/watch?v=VLOs6V-Xq5E)

Personal thank you and shout out to Stuart Clark @bigevilbeard for his contributions and help!


### Dependencies

```
pip3 install nornir
```


### Use Case Description

This script uses Nornir to collect a selection of chosen "show commands" in order to gather network statistics. The script will first create an archive folder named "config-archive", and within that a range of date-stamped subfolders - one for every day the script is deployed. Inside each day there will exist an individual folder created for every show command entered containing its output - allowing network administrators to easily document, reference and compare the network's health and performance on a day-by-day basis.

![teaser image](./Images/archivingtelpic.png)

### About me
I am a Youtube content creator and Cybersecurity & Networks student with a strong interest in NetDevOps/Automation/Programmability.

Follow me on [Twitter](https://twitter.com/IPvZero)!

Thank you!



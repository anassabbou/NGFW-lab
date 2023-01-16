# NGFW Lab

### Realized By
- [ABBOU Anass](https://github.com/anassabbou)
- ALLAGA Hamza
## Objectives
Implementation of a NGFW solution FortiGate
### Demo
<a href="https://youtu.be/UmWeIs3x-K8" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="helllo" height="30" width="40" /></a>

## Requirements
- [x] vmware workstation 17
- [x] gns3
- [x] fortigate image
- [x] windows 7 image
- [x] router and switch image

## Steps

### Configuration gns3, vmware workstation, Add router and Switch<br/>
- Add gns3 vm image
![img1](https://user-images.githubusercontent.com/99830093/212725309-148970b7-971f-4bdc-8195-57787744c467.png)
- Connect vmware with gns3 vm (from stem wizard):
![img2](https://user-images.githubusercontent.com/99830093/212725588-e48dff8d-ca8c-41cb-b796-7325b9d10992.png)
![img3](https://user-images.githubusercontent.com/99830093/212725793-49ffdd2b-2a5d-49fb-949a-3482f3884dc1.png)

- Add router and Switch
You can add router and switch from performance in gns3 
![routers](https://user-images.githubusercontent.com/99830093/212731191-a5c2f23b-968f-48c7-8046-f203b676e278.png)

### Creation Topology
We can create two topologies one of them `topology 1` for testing the firewall Otherwise, the second one `topology 2` is more complex including virtual machines with the images windows 7<br/>
`topology 1` :
![im1](https://user-images.githubusercontent.com/99830093/212726637-5744948c-7f4e-4205-8883-5457d08d6991.png)

`topology 2` :
![im2](https://user-images.githubusercontent.com/99830093/212726377-96b313aa-37d7-49c8-88c2-5c36ded1ede3.png)

### Configuration NGFW frotigate
![conf fortigate](https://user-images.githubusercontent.com/99830093/212727304-d6a9491a-9a75-428a-ac9a-cf73b8a365a7.png)
![conf fortigate2](https://user-images.githubusercontent.com/99830093/212727310-46e8bd4b-7567-4978-a2c0-ac4a350f0e75.png)
![conf fortigate3](https://user-images.githubusercontent.com/99830093/212729495-2e5127e2-8911-4357-bc8c-dd5864913d4c.png)
![p1](https://user-images.githubusercontent.com/99830093/212728436-9c0290c0-2608-4383-a317-abd398d7243c.png)
### Fortigate Dashboard Explanation :<br/>
The FortiGate dashboard is the main interface for managing and monitoring a FortiGate network security device. It provides an overview of the device’s status and performance, including information about system resources, network traffic, security events, and more. The dashboard can be customized to display the information that is most important to the user.<br/>
The FortiGate dashboard is typically divided into several sections, each of which provides specific information. Some common sections include :<br/>
**System Resources** : This section provides information about the device’s CPU, memory, and disk usage. It also displays the status of the device’s
power supplies and fans.<br/>
**Network Traffic** : This section provides information about the device’s network traffic, including the number of sessions, bandwidth usage, and
top talkers. It also displays a graphical representation of the traffic, such as a line graph or pie chart.<br/>
**Security Events** : This section provides information about security events that have occurred on the device, such as blocked or allowed traffic, virus detections, and intrusion attempts. It also displays a summary of the most recent events.

## Note
For more details you can check the lab format pdf :
<a href="https://drive.google.com/file/d/1_Y9JUpR7nIIxIVHA4G3vHJ0J8o_0zf2m/view?usp=sharing">Practical Lab</a>


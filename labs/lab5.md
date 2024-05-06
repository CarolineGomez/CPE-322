# Lab 5
## Install
### pip install -U paho-mqtt
![1](images/Screenshot(120).png)
## Cd iot, cd lesson5, python .\client.py
![2](images/Screenshot(1201).png)
## terminal 1: mosquitto_pub -h localhost -t test/topic -m "Hello"
![3](images/Screenshot(121).png)
## terminal 2: mosquitto_sub -h localhost -v -t test/topic
![5](images/Screenshot(122).png)
## terminal 1: python subcpu.py
![6](images/Screenshot(123).png)
## terminal2: python pubcpu.py
![6](images/Screenshot(125).png)

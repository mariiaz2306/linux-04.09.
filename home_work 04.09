#!/bin/bash

 mkdir -p  /opt/test/logs/linux
 cat /root/readme.txt >> /opt/test/logs/linux/logs.txt
 echo "test" >> /opt/test/logs/linux/logs.txt
 cat /etc/group | tail -2 | head -1 >> /opt/test/logs/linux/logs.txt
 history | head -2 | tail -1 >> /opt/test/logs/linux/logs.txt
 df | awk '{print$1}' >> /opt/test/logs/linux/logs.txt
 echo "Done"

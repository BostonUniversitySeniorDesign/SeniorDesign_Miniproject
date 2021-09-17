
# SeniorDesign Report
Team 13: Wenjun and Henry


 Our team goal is to utilize the wifi scan function which accomplished by Raspberry Pi to detect the number of nearby moving or static hotspot.
 This goal is easily achieved when we use wifi_scan.py to scan and log the data to a specific file which would be transfered into our laptop to be further interpret by wifi_plot.py.

# First Result
![WiFi_scanplot](https://user-images.githubusercontent.com/90300850/133684543-3403f49a-d87a-4e7d-8dc3-6a76167ca396.png)

 Explanation:
 
 The first wifi scanning is conducted in PHO111 where is located near a drive way. As we could see in the graph, in the most of the time, the number of wifi detected during the scanning is 3. This result makes sense since there are 3 fixed university wifi which can always be detected in PHO 111. Furthermore, the number of wifi detected in the last minute is becoming more and more which also make sense since at that time, the number of cars past by is relatively high.

 Discussion:
 
 The first plot drown by wifi_plot.py shows a lot of 0 wifi detected among the 100 times of scans, especially in the beginning 2 minutes of the scanning. However, since the scanning is done in PHO 113, which means that even there are no other hotspots moving by, it should at least shows 3 detected wifi which are the univerisity networks. When we were reviewing the process of scanning in terminal, we found that there are several times of error saying that the device . This may be the only reason why we got several  0 wifi detected output from the program.

# Second Result
![WiFi_scanplot_2](https://user-images.githubusercontent.com/90300850/133714206-c284b940-cee9-4ac5-ab3b-26cf91e3cc67.png)

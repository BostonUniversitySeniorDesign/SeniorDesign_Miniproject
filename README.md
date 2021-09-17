# SeniorDesign wifi scan
Team 13: Wenjun Ma and Man Hang Henry Chong


 Our team goal is to utilize the wifi scan function which accomplished by Raspberry Pi to detect the number of nearby moving or static hotspot.
 This goal is easily achieved when we use wifi_scan.py to scan and log the data to a specific file which would be transfered into our laptop to be further interpret by wifi_plot.py. 
 
 Please check our report on ![Report.md](https://github.com/WenjunMarvin/Senior-Design-wifi-scan/blob/15f0d7093a59dec1142349d15130f57ec89e71cb/Report.md)

# The first result
![WiFi_scanplot](https://user-images.githubusercontent.com/90300850/133684543-3403f49a-d87a-4e7d-8dc3-6a76167ca396.png)

 The first plot drown by wifi_plot.py shows a lot of 0 wifi detected among the 100 times of scans. However, since the scanning is done in PHO 113, which means that even there are no other hotspots moving by, it should at least shows 3 detected wifi which are the univerisity networks. When we were reviewing the process of scanning in terminal, we found that there shows several times of error in scanning. This may be the only reason why we got several  0 wifi detected output from the program.

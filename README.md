# Nessus-Scans
Created a Basic Scan policy and ran it against Windows10-PC1:

![Basic Scan](https://github.com/Larry-Wilkes-CyberCloud/Nessus-Scans/assets/93053015/ace53de4-7c89-4bee-b5a5-c1cf790edfa9)

Created a Advanced Scan policy, and added windows credentials to it then run it against WindowsServer2019-DC:

![Advance Scan](https://github.com/Larry-Wilkes-CyberCloud/Nessus-Scans/assets/93053015/6a89f4b5-f2fe-4318-82da-95444db7fd1b)

Created a Advance Dynamic Scan policy, and added windows credentials to it and specify Dynamic Plugin (CVE-2017-0143) then run it against Windows7-PC2:

![Advance Dynamic Scan CVE-2017-0143](https://github.com/Larry-Wilkes-CyberCloud/Nessus-Scans/assets/93053015/06581070-ec67-4f57-8520-7fbcee5e30d3)

Applied a Group Policy on the HR group (WindowsServer2019-DC) that blocks accessing Control Panel on Windows10-PC1:

![group policy 2](https://github.com/Larry-Wilkes-CyberCloud/Nessus-Scans/assets/93053015/b71006e7-cf92-493e-95fc-4589da559f0a)

 Windows10-PC1:
 
![group policy 1](https://github.com/Larry-Wilkes-CyberCloud/Nessus-Scans/assets/93053015/756c0a1e-ef15-425d-a65a-1c44938d3979)

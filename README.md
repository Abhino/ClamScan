Mobile Malware Scanning using ClamAV 
========+++++++
Androidapplication for mobile devices for scanning files with an Open Source Antivirus solution. The antivirus solution used is ClamAV which is an open source antivirus engine for detecting trojans, viruses.

Steps used by the application:

1. The Android application connects to a server.
2. Application sends the files to the server and invokes the ClamAV process.
3. ClamAv performs the scan of the files using ClamScan.
4. Once Scan is complete it generates a report on the scanned file.
5. Server then sends the scan report back to the user (Application).

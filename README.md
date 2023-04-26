# UDPScan
In this command, the following options are used:

-sU: Specifies a UDP scan.
-sV: Enables version detection to determine the version of services running on the target.
--version-intensity 9: Sets the intensity of version detection to maximum.
--max-retries 2: Specifies the maximum number of retries for unresponsive ports.
--min-rtt-timeout 100ms: Sets the minimum round-trip time (RTT) timeout to 100ms.
--max-rtt-timeout 500ms: Sets the maximum RTT timeout to 500ms.
-p 1-65535: Specifies the range of ports to scan.
-oN: Specifies the output format as a normal text file.
scan_results.txt: Specifies the output file name as scan_results.txt.
target_ip_address: Specifies the IP address of the target to scan.
This scan will perform a UDP scan on all ports in the range of 1-65535 and will attempt to identify the versions of the services running on those ports with maximum intensity. It will also use a maximum of 2 retries for unresponsive ports and set the RTT timeout to between 100ms and 500ms. The output will be saved in a normal text file named scan_results.txt.

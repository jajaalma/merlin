
# Learn Routing
| VRF | Address Family | Route | Active | Metric | Next Hop Index | Next Hop | Outgoing Interface | Route Preference | Source Protocol | Source Protocol Code |
| --- | -------------- | ----- | ------ | ------ | -------------- | -------- | -------------------| ---------------- | --------------- | -------------------- |
| default | ipv4 | 10.255.255.15/32 | True | N/A | N/A | N/A | Loopback0 | N/A | local | L |
| default | ipv4 | 10.15.99.15/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/5 | N/A | local | L |
| default | ipv4 | 10.15.99.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/5 | N/A | connected | C |
| default | ipv4 | 10.15.16.15/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/14 | N/A | local | L |
| default | ipv4 | 10.15.16.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/14 | N/A | connected | C |
| default | ipv4 | 10.14.15.15/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/11 | N/A | local | L |
| default | ipv4 | 10.14.15.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/11 | N/A | connected | C |
| CustD | ipv4 | 172.19.3.15/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/8 | N/A | local | L |
| CustD | ipv4 | 172.19.3.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/8 | N/A | connected | C |
| CustD | ipv4 | 172.19.2.15/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/9 | N/A | local | L |
| CustD | ipv4 | 172.19.2.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/9 | N/A | connected | C |
| CustA | ipv4 | 172.16.4.15/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/6 | N/A | local | L |
| CustA | ipv4 | 172.16.4.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/6 | N/A | connected | C |
| CustA | ipv4 | 172.16.3.15/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/7 | N/A | local | L |
| CustA | ipv4 | 172.16.3.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/7 | N/A | connected | C |
| **nVSatellite | ipv4 | 10.0.0.2/32 | True | N/A | N/A | N/A | nV-Loopback1 | N/A | local | L |
| **nVSatellite | ipv4 | 10.0.0.1/32 | True | N/A | N/A | N/A | nV-Loopback0 | N/A | local | L |
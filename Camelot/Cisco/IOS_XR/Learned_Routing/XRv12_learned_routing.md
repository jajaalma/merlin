
# Learn Routing
| VRF | Address Family | Route | Active | Metric | Next Hop Index | Next Hop | Outgoing Interface | Route Preference | Source Protocol | Source Protocol Code |
| --- | -------------- | ----- | ------ | ------ | -------------- | -------- | -------------------| ---------------- | --------------- | -------------------- |
| default | ipv4 | 10.255.255.12/32 | True | N/A | N/A | N/A | Loopback0 | N/A | local | L |
| default | ipv4 | 10.12.99.12/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/2 | N/A | local | L |
| default | ipv4 | 10.12.99.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/2 | N/A | connected | C |
| default | ipv4 | 10.12.13.12/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/11 | N/A | local | L |
| default | ipv4 | 10.12.13.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/11 | N/A | connected | C |
| default | ipv4 | 10.11.12.12/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/10 | N/A | local | L |
| default | ipv4 | 10.11.12.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/10 | N/A | connected | C |
| CustD | ipv4 | 172.19.1.12/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/9 | N/A | local | L |
| CustD | ipv4 | 172.19.1.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/9 | N/A | connected | C |
| CustC | ipv4 | 172.18.2.12/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/8 | N/A | local | L |
| CustC | ipv4 | 172.18.2.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/8 | N/A | connected | C |
| CustC | ipv4 | 172.18.1.12/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/7 | N/A | local | L |
| CustC | ipv4 | 172.18.1.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/7 | N/A | connected | C |
| CustB | ipv4 | 172.17.2.12/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/6 | N/A | local | L |
| CustB | ipv4 | 172.17.2.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/6 | N/A | connected | C |
| CustB | ipv4 | 172.17.1.12/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/5 | N/A | local | L |
| CustB | ipv4 | 172.17.1.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/5 | N/A | connected | C |
| CustA | ipv4 | 172.16.2.12/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/4 | N/A | local | L |
| CustA | ipv4 | 172.16.2.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/4 | N/A | connected | C |
| CustA | ipv4 | 172.16.1.12/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/3 | N/A | local | L |
| CustA | ipv4 | 172.16.1.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/3 | N/A | connected | C |
| **nVSatellite | ipv4 | 10.0.0.2/32 | True | N/A | N/A | N/A | nV-Loopback1 | N/A | local | L |
| **nVSatellite | ipv4 | 10.0.0.1/32 | True | N/A | N/A | N/A | nV-Loopback0 | N/A | local | L |
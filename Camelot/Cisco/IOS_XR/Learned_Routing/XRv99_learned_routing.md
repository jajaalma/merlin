
# Learn Routing
| VRF | Address Family | Route | Active | Metric | Next Hop Index | Next Hop | Outgoing Interface | Route Preference | Source Protocol | Source Protocol Code |
| --- | -------------- | ----- | ------ | ------ | -------------- | -------- | -------------------| ---------------- | --------------- | -------------------- |
| default | ipv4 | 10.255.255.99/32 | True | N/A | N/A | N/A | Loopback0 | N/A | local | L |
| default | ipv4 | 10.16.99.99/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/6 | N/A | local | L |
| default | ipv4 | 10.16.99.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/6 | N/A | connected | C |
| default | ipv4 | 10.15.99.99/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/5 | N/A | local | L |
| default | ipv4 | 10.15.99.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/5 | N/A | connected | C |
| default | ipv4 | 10.14.99.99/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/4 | N/A | local | L |
| default | ipv4 | 10.14.99.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/4 | N/A | connected | C |
| default | ipv4 | 10.13.99.99/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/3 | N/A | local | L |
| default | ipv4 | 10.13.99.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/3 | N/A | connected | C |
| default | ipv4 | 10.12.99.99/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/2 | N/A | local | L |
| default | ipv4 | 10.12.99.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/2 | N/A | connected | C |
| default | ipv4 | 10.11.99.99/32 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/1 | N/A | local | L |
| default | ipv4 | 10.11.99.0/24 | True | N/A | N/A | N/A | GigabitEthernet0/0/0/1 | N/A | connected | C |
| **nVSatellite | ipv4 | 10.0.0.2/32 | True | N/A | N/A | N/A | nV-Loopback1 | N/A | local | L |
| **nVSatellite | ipv4 | 10.0.0.1/32 | True | N/A | N/A | N/A | nV-Loopback0 | N/A | local | L |
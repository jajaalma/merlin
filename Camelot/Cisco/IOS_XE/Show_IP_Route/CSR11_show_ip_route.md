
# Show IP Route
| VRF | Address Family | Route | Active | Metric | Route Preference | Source Protocol | Source Protocol Code | Next Hop Number | Next Hop | Outgoing Interface | Updated |
| --- | -------------- | ----- | ------ | ------ | ---------------- | --------------- | -------------------- | --------------- | -------- | ------------------ | ------- |
| default | ipv4 | 10.12.13.0/24 | True | 2 | 110 | ospf | O | 1 | 10.11.12.12 | GigabitEthernet10 | 04:15:17 |
| default | ipv4 | 10.12.99.0/24 | True | 2 | 110 | ospf | O | 1 | 10.11.99.99 | GigabitEthernet1 | 04:10:20 |
| default | ipv4 | 10.12.99.0/24 | True | 2 | 110 | ospf | O | 2 | 10.11.12.12 | GigabitEthernet10 | 04:15:17 |
| default | ipv4 | 10.13.99.0/24 | True | 2 | 110 | ospf | O | 1 | 10.11.99.99 | GigabitEthernet1 | 04:10:25 |
| default | ipv4 | 10.14.15.0/24 | True | 3 | 110 | ospf | O | 1 | 10.11.99.99 | GigabitEthernet1 | 04:06:30 |
| default | ipv4 | 10.14.99.0/24 | True | 2 | 110 | ospf | O | 1 | 10.11.99.99 | GigabitEthernet1 | 04:10:25 |
| default | ipv4 | 10.15.16.0/24 | True | 3 | 110 | ospf | O | 1 | 10.11.99.99 | GigabitEthernet1 | 04:02:21 |
| default | ipv4 | 10.15.99.0/24 | True | 2 | 110 | ospf | O | 1 | 10.11.99.99 | GigabitEthernet1 | 04:10:25 |
| default | ipv4 | 10.16.99.0/24 | True | 2 | 110 | ospf | O | 1 | 10.11.99.99 | GigabitEthernet1 | 04:10:25 |
| default | ipv4 | 10.255.255.12/32 | True | 10 | 115 | isis | i L2 | 1 | 10.11.12.12 | GigabitEthernet10 | 1d00h |
| default | ipv4 | 10.255.255.13/32 | True | 20 | 115 | isis | i L2 | 1 | 10.11.99.99 | GigabitEthernet1 | 1d00h |
| default | ipv4 | 10.255.255.13/32 | True | 20 | 115 | isis | i L2 | 2 | 10.11.12.12 | GigabitEthernet10 | 1d00h |
| default | ipv4 | 10.255.255.14/32 | True | 20 | 115 | isis | i L2 | 1 | 10.11.99.99 | GigabitEthernet1 | 1d00h |
| default | ipv4 | 10.255.255.15/32 | True | 20 | 115 | isis | i L2 | 1 | 10.11.99.99 | GigabitEthernet1 | 1d00h |
| default | ipv4 | 10.255.255.16/32 | True | 20 | 115 | isis | i L2 | 1 | 10.11.99.99 | GigabitEthernet1 | 1d00h |
| default | ipv4 | 10.255.255.99/32 | True | 10 | 115 | isis | i L2 | 1 | 10.11.99.99 | GigabitEthernet1 | 1d00h |
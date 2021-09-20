
# Show IP Route
| VRF | Address Family | Route | Active | Metric | Route Preference | Source Protocol | Source Protocol Code | Next Hop Number | Next Hop | Outgoing Interface | Updated |
| --- | -------------- | ----- | ------ | ------ | ---------------- | --------------- | -------------------- | --------------- | -------- | ------------------ | ------- |
| default | ipv4 | 10.11.12.0/24 | True | 3 | 110 | ospf | O | 1 | 10.16.99.99 | GigabitEthernet6 | 04:01:29 |
| default | ipv4 | 10.11.99.0/24 | True | 2 | 110 | ospf | O | 1 | 10.16.99.99 | GigabitEthernet6 | 04:01:29 |
| default | ipv4 | 10.12.13.0/24 | True | 3 | 110 | ospf | O | 1 | 10.16.99.99 | GigabitEthernet6 | 04:01:29 |
| default | ipv4 | 10.12.99.0/24 | True | 2 | 110 | ospf | O | 1 | 10.16.99.99 | GigabitEthernet6 | 04:01:29 |
| default | ipv4 | 10.13.99.0/24 | True | 2 | 110 | ospf | O | 1 | 10.16.99.99 | GigabitEthernet6 | 04:01:29 |
| default | ipv4 | 10.14.15.0/24 | True | 3 | 110 | ospf | O | 1 | 10.16.99.99 | GigabitEthernet6 | 03:59:00 |
| default | ipv4 | 10.14.99.0/24 | True | 2 | 110 | ospf | O | 1 | 10.16.99.99 | GigabitEthernet6 | 04:01:29 |
| default | ipv4 | 10.15.99.0/24 | True | 2 | 110 | ospf | O | 1 | 10.16.99.99 | GigabitEthernet6 | 04:01:29 |
| default | ipv4 | 10.255.255.11/32 | True | 20 | 115 | isis | i L2 | 1 | 10.16.99.99 | GigabitEthernet6 | 1d00h |
| default | ipv4 | 10.255.255.12/32 | True | 20 | 115 | isis | i L2 | 1 | 10.16.99.99 | GigabitEthernet6 | 1d00h |
| default | ipv4 | 10.255.255.13/32 | True | 20 | 115 | isis | i L2 | 1 | 10.16.99.99 | GigabitEthernet6 | 1d00h |
| default | ipv4 | 10.255.255.14/32 | True | 20 | 115 | isis | i L2 | 1 | 10.16.99.99 | GigabitEthernet6 | 1d00h |
| default | ipv4 | 10.255.255.14/32 | True | 20 | 115 | isis | i L2 | 2 | 10.15.16.15 | GigabitEthernet14 | 1d00h |
| default | ipv4 | 10.255.255.15/32 | True | 10 | 115 | isis | i L2 | 1 | 10.15.16.15 | GigabitEthernet14 | 1d00h |
| default | ipv4 | 10.255.255.99/32 | True | 10 | 115 | isis | i L2 | 1 | 10.16.99.99 | GigabitEthernet6 | 1d00h |
# Networking

## IPv4

- All organizational networks sit inside `10.192.0.0/12`.
- This does not include guest networks (`172.20.0.0/16`).
- Subnets from `/24` to `/16`.

/16 range | description
----------|------------
10.192.0.0/16 | Core networks
10.193.0.0/16 | Core networks
10.194.0.0/16 | Internal servers
10.195.0.0/16 | Internal servers
10.196.0.0/16 | External servers
10.197.0.0/16 | External servers
10.198.0.0/16 |
10.199.0.0/16 |
10.200.0.0/16 | RESERVED
10.201.0.0/16 | Client terminals (e.g. Wi-Fi)
10.202.0.0/16 | Client terminals
10.203.0.0/16 |
10.204.0.0/16 |
10.205.0.0/16 |
10.206.0.0/16 |
10.207.0.0/16 |
-- |
172.20.0.0/16 | Guest networks



## VPN

- Exit from each location participating in the network
- Unblocked exit node in North America?

```
   Default exit
        |
+-------+-------+    +------------+    +----------+
| 10.192.0.0/12 |====| VPN server |====| External |
+---------------+    +-----+------+    +----------+
                           |
                      VPN clients
```

# Networking

## IPv6

- Use NAT.
- Unique local address ranges `fd00:bad:bed::/48`.

## IPv4

- All organizational networks sit inside `10.192.0.0/12`.
- This does not include guest networks (`172.20.0.0/16`).
- Subnets from `/24` to `/16`.

v4 /16 range | v6 /56 range | description
-------------|--------------|------------
10.192.0.0/16 | fd00:bad:bed:c000::/56 | Core networks
10.193.0.0/16 | fd00:bad:bed:c100::/56 | Core networks
10.194.0.0/16 | fd00:bad:bed:c200::/56 | Internal servers
10.195.0.0/16 | fd00:bad:bed:c300::/56 | Internal servers
10.196.0.0/16 | fd00:bad:bed:c400::/56 | External servers
10.197.0.0/16 | fd00:bad:bed:c500::/56 | External servers
10.198.0.0/16 | fd00:bad:bed:c600::/56 | 
10.199.0.0/16 | fd00:bad:bed:c700::/56 | 
10.200.0.0/16 | fd00:bad:bed:c800::/56 | RESERVED
10.201.0.0/16 | fd00:bad:bed:c900::/56 | Client terminals (e.g. Wi-Fi)
10.202.0.0/16 | fd00:bad:bed:ca00::/56 | Client terminals
10.203.0.0/16 | fd00:bad:bed:cb00::/56 | 
10.204.0.0/16 | fd00:bad:bed:cc00::/56 | 
10.205.0.0/16 | fd00:bad:bed:cd00::/56 | 
10.206.0.0/16 | fd00:bad:bed:ce00::/56 | 
10.207.0.0/16 | fd00:bad:bed:cf00::/56 | 
-- |
172.20.0.0/16 | fd00:bad:bed:1400::/56 | Guest networks



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

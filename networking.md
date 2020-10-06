# Networking

## IPv4

- All organizational networks sit inside `10.192.0.0/12`.
- Subnets from `/24` to `/16`.

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

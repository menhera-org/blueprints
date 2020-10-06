# Networking

## VPN

- Exit from each location participating in the network
- Unblocked exit node in North America?
- All organizational networks sit inside `10.192.0.0/12`.

```
   Default exit
        |
+-------+-------+    +------------+    +----------+
| 10.192.0.0/12 |====| VPN server |====| External |
+---------------+    +-----+------+    +----------+
                           |
                      VPN clients
```

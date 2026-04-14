# Lab 02 - Device Security & AAA Authentication

## Objective
Secure console access using password authentication and local AAA user accounts.

## Topology
![Topology](topology.png)

## Key Configurations

```bash
user-interface console 0
authentication-mode password

aaa
local-user elmix password cipher 1234
local-user elmix service-type terminal
local-user elmix privilege level 3

user-interface console 0
authentication-mode aaa

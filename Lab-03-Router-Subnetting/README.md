# Lab 03 - Router Configuration & Subnetting

## Objective
Connect three different networks through one router and enable communication across subnets.

## Topology
![Topology](topology.png)

## Key Configurations
```bash
interface GigabitEthernet 0/0/0
ip address 192.168.1.1 24

interface GigabitEthernet 0/0/1
ip address 192.168.2.1 24

interface GigabitEthernet 0/0/2
ip address 192.168.3.1 24

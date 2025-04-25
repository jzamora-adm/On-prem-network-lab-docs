# Routing Instance Configuration - LOGICAL_ROUTER-01

**Date:** 2025-04-24  
**Device:** Juniper EX2200  
**Admin:** `admin`  
**Purpose:** To isolate inter-VLAN routing within VLAN 20 using a virtual router instance.

---

## Configuration Steps

```cli
configure
set routing-instances LOGICAL_ROUTER-01 instance-type virtual-router
set routing-instances LOGICAL_ROUTER-01 interface vlan.20
commit
exit

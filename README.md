# Laporan Praktikum 3

## CPT - CIDR

Menentukan subnet pada topologi  
![](/img/1.1.png)
![](/img/1.2.png)
![](/img/1.3.png)
![](/img/1.4.png)
![](/img/1.5.png)
![](/img/1.6.png)
![](/img/1.7.png)
![](/img/1.8.png)

Menentukan submask pada subnet yang sudah ditentukan  
![](/img/1.9.png)

Membuat IP tree  
![](/img/1.10.png)

Routing pada CPT sesuai IP tree  
![](/img/1.11.1.png)
![](/img/1.11.2.png)
![](/img/1.11.3.png)
![](/img/1.11.4.png)
![](/img/1.11.5.png)
![](/img/1.11.6.png)
![](/img/1.11.7.png)
![](/img/1.11.8.png)
![](/img/1.11.9.png)

Hasil percobaan  
![](/img/1.12.png)

## VLSM - GNS3

### Topology dan Pembagian Subnet

![](/img/2.topology.png)
![](/img/2.pembagian-netmask.png)

### Membuat Tree untuk membagi subnet

![](/img/2.tree.png)

### Membagi NID, netmask, dan subnet

![](/img/2.1.png)
![](/img/2.2.png)
![](/img/2.3.png)
![](/img/2.4.png)
![](/img/2.5.png)

### Mengeset Config IP static pada router dan PC

**TheDauntless**

```sh
# Static config for eth0 A2
auto eth0
iface eth0 inet static
	address 10.10.20.194
	netmask 255.255.255.252

# Static config for eth1 A1
auto eth1
iface eth1 inet static
	address 10.10.16.1
	netmask 255.255.255.0
```

**TheFirefist**

```sh
# Static config for eth0 A15
auto eth0
iface eth0 inet static
    address 10.10.20.234
    netmask 255.255.255.252

# Static config for eth1 A18
auto eth1
iface eth1 inet static
    address 10.10.18.1
    netmask 255.255.255.0

# Static config for eth2 A16
auto eth2
iface eth2 inet static
    address 10.10.8.1
    netmask 255.255.254.0
```

**TheIsntrument**

```sh
# Static config for eth0 A10
auto eth0
iface eth0 inet static
	address 10.10.20.214
	netmask 255.255.255.252

# Static config for eth1 A12
auto eth1
iface eth1 inet static
	address 10.10.20.217
	netmask 255.255.255.252

# Static config for eth2 A15
auto eth2
iface eth2 inet static
    address 10.10.20.233
    netmask 255.255.255.252

# Static Config for eth3 A11
auto eth3
iface eth3 inet static
    address 10.10.20.1
    netmask 255.255.255.128
```

**TheMagical**

```sh
# Static config for eth0 A8
auto eth0
iface eth0 inet static
    address 10.10.20.210
	netmask 255.255.255.252

# Static config for eth1 A9
auto eth1
iface eth1 inet static
    address 10.10.4.1
	netmask 255.255.254.0
```

**TheMinister**

```sh
# Static config for eth0 A4
auto eth0
iface eth0 inet static
	address 10.10.20.198
	netmask 255.255.255.252

# Static config for eth1 A3
auto eth1
iface eth1 inet static
	address 10.10.0.1
	netmask 255.255.252.0

# Static config for eth2 A2
auto eth2
iface eth2 inet static
	address 10.10.20.193
	netmask 255.255.255.252
```

**TheOrder**

```sh
# Static config for eth0 A6
auto eth0
iface eth0 inet static
	address 10.10.20.202
	netmask 255.255.255.252

# Static config for eth1 A5
auto eth1
iface eth1 inet static
	address 10.10.20.129
	netmask 255.255.255.192

# Static config for eth2 A4
auto eth2
iface eth2 inet static
	address 10.10.20.197
	netmask 255.255.255.252
```

**TheQueen**

```bash
# Static config for eth0 A18
auto eth0
iface eth0 inet static
    address 10.10.18.2
    netmask 255.255.255.0

# Static config for eth1 A17
auto eth1
iface eth1 inet static
    address 10.10.20.224
    netmask 255.255.255.252
```

**TheRaofound**

```bash
# Static config for eth0 A12
auto eth0
iface eth0 inet static
	address 10.10.20.218
	netmask 255.255.255.252

# Static config for eth1 A14
auto eth1
iface eth1 inet static
	address 10.10.20.1
	netmask 255.255.255.128

# Static config for eth2 A13
auto eth2
iface eth2 inet static
    address 10.10.20.129
    netmask 255.255.255.128
```

**TheResonance**

```bash
# Static config for eth0
auto eth0
iface eth0 inet dhcp

# Static config for eth1 A7
auto eth1
iface eth1 inet static
	address 10.10.20.205
	netmask 255.255.255.252

# Static config for eth2 A8
auto eth2
iface eth2 inet static
    address 10.10.20.209
	netmask 255.255.255.252

# Static config for eth3 A10
auto eth3
iface eth3 inet static
	address 10.10.20.213
	netmask 255.255.255.252

# Static config for eth4 A6
auto eth4
iface eth4 inet static
	address 10.10.20.201
	netmask 255.255.255.252
```

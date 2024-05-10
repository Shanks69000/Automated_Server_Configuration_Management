# Environment configuration

### Requirements
#### step 1:
- Laboratory preparation on paper, separating each function to facilitate error management.
- check the **tools** required for each VM (**DHCP**, **DNS**, **static ip**, **Docker**, **OpenSSH**, **ansible**, find out about **Prometheus** and **Grafana**, **PfSense**)
#### step 2:

| VM Name       | Operating system       | RAM    | CPU    | Disk space | Static IP address |  Network Address   |  Gateway    |
|:-------------:|:----------------------:|:------:|:------:|:----------:|:-----------------:|:------------------:|:-----------:|
| Pfsense       | BSD                    | 1 Go   | 1 CPU  | 16 Go      | 192.168.2.1       | 255.255.255.0      |  ....       |
| Docker        | Linux Ubuntu 22.04 LTS | 2 Go   | 1 CPU  | 25 Go      | 192.168.1.11      |  255.255.255.0     | 192.168.2.1 |
| MySQL         | Linux Ubuntu 22.04 LTS | 2 Go   | 1 CPU  | 25 Go      | 192.168.2.30      | 255.255.255.0      | 192.168.2.1 |
| Ansible       | Linux Ubuntu 22.04 LTS | 2 GO   | 1 CPU  | 25 GO      | 192.168.2.40      | 255.255.255.0      | 192.168.2.1 |

.... in progress ....

### Tool Installation

### FAQ

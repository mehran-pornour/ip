# ip
network:
  ethernets:
    enp0s3: # <-- Replace with your interface name
      dhcp4: no
      addresses:
        - 192.168.1.110/24 # <-- Set your desired static IP and subnet mask
      gateway4: 192.168.1.1 # <-- Set your router's/gateway's IP
      nameservers:
        addresses: [8.8.8.8, 1.1.1.1] # <-- Set your DNS servers
  version: 2

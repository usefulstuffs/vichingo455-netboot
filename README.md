# Vichingo455's netboot solution
Boot any OS from the network

## Getting started
DISCLAIMER: This project is in alpha and is not production ready! There might be issues or weird stuffs.

1. Download [iPXE](https://boot.ipxe.org/ipxe.iso)
2. Boot from it and press CTRL+B to access the command line
3. Type dhcp to initialize network
4. Type chain http://vichingo455.ddns.net/netboot/boot.ipxe
5. You should see a boot menu to select the OS

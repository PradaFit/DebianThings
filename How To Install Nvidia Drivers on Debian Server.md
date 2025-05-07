# Let's Install Nvidia Drivers On Your Debian Server:
- sudo apt update
- sudo apt upgrade -y
- sudo apt install -y nvidia-driver

## Required PKGs:
- sudo apt install -y build-essential dkms linux-headers-$(uname -r)

## Detect Your GPU:
- lspci | grep -i nvidia

## Reboot
- sudo reboot

## Confirmation
- nvidia-smi

# Raspberry Pi Script Collection
This repo are for collection of script for Raspberry Pi running on Raspberry Pi OS /  Raspbian.

# Requirement & About Script
## 1. rpiabout
This script show parameter about your system.

![piaboutss](https://github.com/mahadi22/Raspberry-pi-script/blob/main/img/piabout.png?raw=true "PIABOUT SS")

Package Requirement: `html2text` and `curl` package
```markdown
sudo apt update
sudo apt install html2text curl
```
or
```markdown
sudo apt-get update
sudo apt-get install html2text curl
```
## 2. rpistatus
This script show power status of your system.

![pistatusss](https://github.com/mahadi22/Raspberry-pi-script/blob/main/img/pistatus.png?raw=true "PISTATUS SS")

Package Requirement: NONE (`vcgencmd` included in OS)

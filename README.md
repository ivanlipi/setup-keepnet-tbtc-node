## setup-keepnet-tbtc-node

## Set up your KEEP Network and tBTC node

This script helps to set up your KEEP Network and tBTC node

### Step 1. Downloading and installing the required packages wget and git

```json
sudo apt-get install wget git
```

### Step 2. How to install this tool

```sh
cd && wget https://github.com/lipivan/setup-keepnet-tbtc-node/blob/master/keepbot.tar.gz -O keepbot.tar.gz && mkdir -p keepbot && mv -f keepbot.tar.gz keepbot && cd keepbot && tar -zxvf keepbot.tar.gz && rm -f keepbot.tar.gz && sudo chmod +x install.sh && sudo chmod 775 install.sh; sudo ./install.sh
```

### Step 3. How to update

```json
keepbot update
```

### Step 4. How to upgrade this tool

Upgrade Docker and your KEEP Random Beacon node:

```json
keepbot upgrade
```

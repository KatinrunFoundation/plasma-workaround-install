# This is workarounnd for plasma-client.
Duo to we have a problem with 'npm install -g plasma-client', then we create this repo for easy to get start without a error.

## Install
```sh
yarn install
```

## Usage
### Start Node service
```sh
yarn plasma-client -c Katinrun-plasma-mark1
```

### Usage wallet & ralated cli
```sh
# List accounnt
yarn plasma-cli listaccounts

# Create account
yarn plasma-cli createaccount

# Deposit <account> <token> <amount>
yarn plasma-cli deposit 0 0 100

# Get balance <account>
yarn plasma-cli getbalance 0
```

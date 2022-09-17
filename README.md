# Simple FreeRADIUS configuration for Wifi 802.1X

This is a simple set of configs, loosely based off the example provided by the [GovWifi Project][govwifi].

## Installation
- Install the NetworkRadius FreeRADIUS package
- Remove existing /etc/freeradius directory
- Clone this repo into /etc/freeradius
- Copy `clients.example` -> `clients` and `users.example` -> `users`
- Edit those two files
- Setup an SSL cert
- Start FreeRADIUS
- Configure your wireless access points

[govwifi]: https://github.com/alphagov/govwifi-frontend

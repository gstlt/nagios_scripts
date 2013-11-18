### check_oracle

Here are some various tests written back in year 2k extended by more checks. For example: check table size, check tablespace, check ASM.

You can also check for NCDC PCM handled/unhandled events. Information about PCM can be found at http://ncdc.eu

### check_oracle_as

This script is a starting point for Oracle Application Server checks.

There is one check which figures out from which Oracle Application Server machine user is logged in.

Eg. If you have server A and B - Oracle Application Servers. And server C - a database host. Users can log in using servers A or B.

### check_oracle_asusers

This script is returing amount of users connected to OAS (Oracle Application Server) using its Enterprise Manager. Works also with Oracle Forms&Reports

Requires: perl and curl

## Links to check out

* Nagios: http://nagios.org
* NCDCs PCM: http://www.ncdc.eu/products/pcm/
* Oracle SQLPlus downloads: http://www.oracle.com/technetwork/database/features/instant-client/index-097480.html

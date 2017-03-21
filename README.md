# drone
A bash utility for simplifying RPC2 calls to DroneBL (https://dronebl.org)

# Install
Replace the example key with your actual RPC key in rpckey.example then run:

mv rpckey.example rpckey

# Usage

## Flags

-a = add

-r = remove

-l = lookup

## Examples

./drone -a 8.8.8.8 13

Where 8.8.8.8 is an IP address and 13 is the class type for the listing

--

./drone -r 123123

Where 123123 is the Incident ID for the listing

--

./drone -l 8.8.8.8

OR

./drone -l 123123

Lookups can be done with either an IP address/CIDR range or with an Incident ID

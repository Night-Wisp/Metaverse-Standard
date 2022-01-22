# Metaverse Server Standard
This part of the standard is for the groups/peoples/companies that are/will/have building/build/built worlds in/for the metaverse.
The purpose of this section is to set a process for receiving and handling connections from clients and lobbys.

## Receiving connections from clients
The server will be listening on port 20200 (not set) for incoming connections from clients.
The format for incoming connections is:

```
UInt64: User ID
UInt16: Version of this standard
UInt8: Reported Client ID
UInt8: Targeted Server ID
UInt32: Hash of above message
```

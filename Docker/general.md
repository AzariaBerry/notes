# Docker

- "batteries included, but removable"
- is open source
- containers
    - Not mini-VM
    - processes
    - limited to what resources they can access
    - is connected to a private virtual network, each virtual network goes through NAT firewall
    - all containers on VN can talk to each other without exposing their ports
    - best practice is to create new networks for each app
    - suppose to me immutable and ephemeral (only redeploy never change)
    - seperation of concerns
- Has has a built in DNS
- Not a complete OS no kernel no drives
- host names default to container name

## history

- 90s - mainframe to pc
- 00s - baremetal to virtual
- 10s - host to container (severless)

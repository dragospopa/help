<!-- usedin: [ _legacy_docker/failover-groups/failover-groups-v1.md, _maestro/failover-groups/failover-groups-v1.md, _node/failover-groups/failover-groups-v1.md, _rails/failover-groups/failover-groups-v1.md] -->


## Notes
- You don't need to select any stacks for your failover group. This allows you to reserve the address provided for future use. This is particularly useful when you want to keep address the same.
- Having a _backup_ stack is not mandatory.
- You can only delete a failover group when it isn't pointing at any stacks.
- Once you delete a failover group, the DNS record for it is permanently deleted and you won't be able to get the same address back.

<!-- usedin: [ _legacy_docker/Databases/database-management-v1.md, _maestro/Databases/database-management-v1.md, _node/Databases/database-management-v1.md, _rails/databases/database-management-v1.md] -->


## Upgrading your database

Cloud 66 will not do in-place database upgrades, because this process may cause your application to stop working or may not be possible automatically. To upgrade your database through Cloud 66, we recommend that you create a new stack (at which point Cloud 66 will deploy the newer database version).

Once the new stack is created, you can migrate data from your old stack to your new stack.

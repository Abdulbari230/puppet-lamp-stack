# Puppet LAMP Stack

This repository contains Puppet manifests for managing a LAMP stack and user configurations.

## Files

1. **lamp_stack_server.pp**: Defines the packages and services required for setting up a LAMP stack, including Apache, PHP, and the PHP MySQL connector.
2. **mariadb_server.pp**: Manages the installation and configuration of the MariaDB server, ensuring the database service is running and enabled.
3. **phpinfo.php**: A PHP script that displays the PHP configuration information, used to verify that PHP is working correctly on the server.
4. **server_users_groups.pp**: Defines the users and groups that should be present on the server, managing user accounts and their associated groups.

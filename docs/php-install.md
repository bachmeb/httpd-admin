# php install

## References
* http://php.net/manual/en/install.unix.apache2.php
* https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-centos-6

##### Install PHP from the yum repository
```
sudo yum install php php-mysql
```
```c
/*
Loaded plugins: fastestmirror, refresh-packagekit
Setting up Install Process
Loading mirror speeds from cached hostfile
 * base: centos.chi.host-engine.com
 * extras: centos.chi.host-engine.com
 * updates: mirror.steadfast.net
Resolving Dependencies
--> Running transaction check
---> Package php.x86_64 0:5.3.3-46.el6_7.1 will be installed
--> Processing Dependency: php-common(x86-64) = 5.3.3-46.el6_7.1 for package: php-5.3.3-46.el6_7.1.x86_64
--> Processing Dependency: php-cli(x86-64) = 5.3.3-46.el6_7.1 for package: php-5.3.3-46.el6_7.1.x86_64
--> Running transaction check
---> Package php-cli.x86_64 0:5.3.3-46.el6_7.1 will be installed
---> Package php-common.x86_64 0:5.3.3-46.el6_7.1 will be installed
--> Finished Dependency Resolution

Dependencies Resolved

================================================================================
 Package           Arch          Version                   Repository      Size
================================================================================
Installing:
 php               x86_64        5.3.3-46.el6_7.1          updates        1.1 M
Installing for dependencies:
 php-cli           x86_64        5.3.3-46.el6_7.1          updates        2.2 M
 php-common        x86_64        5.3.3-46.el6_7.1          updates        529 k

Transaction Summary
================================================================================
Install       3 Package(s)

Total download size: 3.8 M
Installed size: 13 M
Is this ok [y/N]: y
Downloading Packages:
(1/3): php-5.3.3-46.el6_7.1.x86_64.rpm                   | 1.1 MB     00:00
(2/3): php-cli-5.3.3-46.el6_7.1.x86_64.rpm               | 2.2 MB     00:00
(3/3): php-common-5.3.3-46.el6_7.1.x86_64.rpm            | 529 kB     00:00
--------------------------------------------------------------------------------
Total                                           2.4 MB/s | 3.8 MB     00:01
Running rpm_check_debug
Running Transaction Test
Transaction Test Succeeded
Running Transaction
  Installing : php-common-5.3.3-46.el6_7.1.x86_64                           1/3
  Installing : php-cli-5.3.3-46.el6_7.1.x86_64                              2/3
  Installing : php-5.3.3-46.el6_7.1.x86_64                                  3/3
  Verifying  : php-common-5.3.3-46.el6_7.1.x86_64                           1/3
  Verifying  : php-cli-5.3.3-46.el6_7.1.x86_64                              2/3
  Verifying  : php-5.3.3-46.el6_7.1.x86_64                                  3/3

Installed:
  php.x86_64 0:5.3.3-46.el6_7.1

Dependency Installed:
  php-cli.x86_64 0:5.3.3-46.el6_7.1     php-common.x86_64 0:5.3.3-46.el6_7.1

Complete!
*/
```




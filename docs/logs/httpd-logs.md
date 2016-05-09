# httpd logs

## References
*

##### List the contents of the httpd log directory
```
sudo ls -l /var/log/httpd/
```
```
total 68
-rw-r--r-- 1 root root    0 May  8 04:02 access_log
-rw-r--r-- 1 root root 2167 May  6 16:46 access_log.1
-rw-r--r-- 1 root root 3168 Apr 29 16:15 access_log.2
-rw-r--r-- 1 root root 1301 Apr 27 16:25 access_log.3
-rw-r--r-- 1 root root 1665 Apr  5 12:43 access_log.4
-rw-r--r-- 1 root root    0 May  8 04:02 error_log
-rw-r--r-- 1 root root 5560 May  6 17:03 error_log.1
-rw-r--r-- 1 root root 3947 May  1 04:02 error_log.2
-rw-r--r-- 1 root root 1541 Apr 28 04:02 error_log.3
-rw-r--r-- 1 root root 2148 Apr  5 12:47 error_log.4
```

##### Read the most recent error log file
```
sudo cat /var/log/httpd/error_log
```

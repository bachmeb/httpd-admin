# httpd errors

## References
* https://success.mocana.com/hc/en-us/articles/203661378-Error-When-Trying-to-start-Apache-services-httpd-
* http://forums.fedoraforum.org/archive/index.php/t-250779.html

##### Permission denied: access to /index.php denied
```
cat /var/logs/httpd/error_log
```
```
[Thu May 12 14:47:47 2016] [error] [client 0.0.0.0] (13)Permission denied: access to /index.php denied
```

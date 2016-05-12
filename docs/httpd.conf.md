# httpd.conf

## References
* http://httpd.apache.org/docs/2.2/mod/directives.html
* http://kvz.io/blog/2007/07/11/cat-a-file-without-the-comments/


##### Read the conf file without any comments
```
cat /etc/httpd/conf/httpd.conf | egrep -v "(^#.*|^$)"
```



##### Help
```
sudo /usr/sbin/httpd -help
```
```c
/*
Usage: /usr/sbin/httpd [-D name] [-d directory] [-f file]
                       [-C "directive"] [-c "directive"]
                       [-k start|restart|graceful|graceful-stop|stop]
                       [-v] [-V] [-h] [-l] [-L] [-t] [-S]
Options:
  -D name            : define a name for use in <IfDefine name> directives
  -d directory       : specify an alternate initial ServerRoot
  -f file            : specify an alternate ServerConfigFile
  -C "directive"     : process directive before reading config files
  -c "directive"     : process directive after reading config files
  -e level           : show startup errors of level (see LogLevel)
  -E file            : log startup errors to file
  -v                 : show version number
  -V                 : show compile settings
  -h                 : list available command line options (this page)
  -l                 : list compiled in modules
  -L                 : list available configuration directives
  -t -D DUMP_VHOSTS  : show parsed settings (currently only vhost settings)
  -S                 : a synonym for -t -D DUMP_VHOSTS
  -t -D DUMP_MODULES : show all loaded modules
  -M                 : a synonym for -t -D DUMP_MODULES
  -t                 : run syntax check for config files
*/
```

##### Show parsed settings (currently only vhost settings)
```
sudo /usr/sbin/httpd -S
```
```c
/*
[Mon May 09 12:27:31 2016] [warn] module mime_module is already loaded, skipping
[Mon May 09 12:27:31 2016] [warn] module dir_module is already loaded, skipping
[Mon May 09 12:27:31 2016] [warn] module rewrite_module is already loaded, skipping
VirtualHost configuration:
Syntax OK
*/

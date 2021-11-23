### Build fast, responsive sites with Bootstrap
> https://getbootstrap.com/

### NGINX Variables Documentation 
> http://nginx.org/en/docs/varindex.html

### If is Evil... when used in location context 
> https://www.nginx.com/resources/wiki/start/topics/depth/ifisevil/

### HTTP response status codes
> https://developer.mozilla.org/en-US/docs/Web/HTTP/Status

### NGINX Docs error log Documentation
> http://nginx.org/en/docs/ngx_core_module.html#error_log

### ngx_http_log_module Documentation
> http://nginx.org/en/docs/http/ngx_http_log_module.html

### Understanding and Implementing FastCGI Proxying in Nginx
> https://www.digitalocean.com/community/tutorials/understanding-and-implementing-fastcgi-proxying-in-nginx

### Configuration file measurement units
> http://nginx.org/en/docs/syntax.html

### Module ngx_http_image_filter_module Documentation
> http://nginx.org/en/docs/http/ngx_http_image_filter_module.html

### Whats is the correct number of nginx workers and connections?
> The number of CPU cores or set to 'auto' which set to suitable number of cores
> worker_processes x worker_connection = max number of connections
> ex: 

## Useful commands

- Check last line of error log 
```sh
tail -n 1 /var/log/nginx/error.log
```
- Check nginx 
```sh
ps aux | grep nginx
```


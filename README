
Documentation is available at http://nginx.org


# Nginx Streaming Server

## Install For Mac

```
1. Download cd nginx-1.8.1
2. brew install PCRE
3. cd nginx-1.8.1
4. ./configure --with-http_flv_module --with-http_mp4_module  --with-http_ssl_module --with-debug
5. make && make install
```

## Start Nginx
```
sudo /usr/local/nginx/sbin/nginx
```

## Stop Nginx
```
sudo /usr/local/nginx/sbin/nginx -s stop
```

## Config 
```
location ~ \.flv$ {
        root   /usr/local/nginx/html;
        flv;
        limit_rate  200k;
}

location ~ \.mp4$ {
        root   /usr/local/nginx/html;
        mp4;
        limit_rate 200k;
}
```

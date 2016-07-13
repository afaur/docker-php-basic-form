# Setup Instructions
```
> cd src
> git clone git@github.com:afaur/php-basic-form.git
> docker build -t image-name .
```

# Running The Container
```
> docker run -it -p 80:80 image-name /bin/bash
```

# Running The Nginx Server
```
> /usr/bin/supervisord -n -c /etc/supervisord.conf
```

# View At
Run `docker env default` to get your ip address.
```
> open http://your-ip-address
```

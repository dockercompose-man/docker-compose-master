https://dbt3ch.com/books/fail2ban/page/how-to-install-and-configure-fail2ban-to-work-with-nginx-proxy-manager
https://www.youtube.com/watch?v=Ha8NIAOsNvo

You're going to create 3 files:

    /home/docker/fail2ban/data/filter.d/npm-docker.conf
    /home/docker/fail2ban/data/jail.d/npm-docker.local
    /home/docker/fail2ban/data/action.d/cloudflare-apiv4.conf
    
    chmod 604 nginx.conf and restart the container

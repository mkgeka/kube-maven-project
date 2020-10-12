FROM mkgeka/lamp-7
RUN useradd -r -s /bin/bash -d /var/www/html test
RUN usermod -aG apache test
CMD supervisord -n

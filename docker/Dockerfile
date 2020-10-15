FROM mkgeka/lamp-7
RUN useradd -r -s /bin/bash -d /var/www/html test
RUN usermod -aG apache test
RUN mkdir -p /var/www/html/{web,logs,tmp}
COPY --chown=test:apache web/ /var/www/html/web/
CMD supervisord -n

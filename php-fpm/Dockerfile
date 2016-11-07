FROM phpdockerio/php56-fpm:latest

# Install selected extensions and other stuff
RUN apt-get update \
    && apt-get -y --no-install-recommends install  php5-memcached php5-mysql php5-gd php5-imap php5-imagick php5-memcache php5-odbc php5-phpdbg php5-ssh2 php5-solr php5-twig php5-xdebug php5-xmlrpc php5-xsl \
    && apt-get clean; rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*


WORKDIR "/var/www/emondon"
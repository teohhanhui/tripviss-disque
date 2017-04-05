#!/bin/ash
set -e

/usr/local/bin/confd --onetime --confdir /usr/local/etc/confd --backend env

exec disque-server /usr/local/etc/disque/disque.conf

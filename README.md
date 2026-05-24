# NS-BIND9

sudo cp named.conf.local /etc/bind/
   sudo cp db.nsa.gov /etc/bind/
   sudo cp named /etc/default/named  # Forces IPv4 only

sudo systemctl restart named


dig @127.0.0.1 AXFR nsa.gov

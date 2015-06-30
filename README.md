#openvpn_auto_setup

#Short description)

Script for openvpn setup on FreeBSD
Suports tun/tap, port,IP specifing, tcp/udp, several users


#USAGE
/bin/sh openvpn_freebsd.sh [-i <ip>] [-p <port>] [-u user1,user2...] [-d] [-t]
            -i IP where to listen (default last)
            -p port on which listen(default 1194)
            -u a list of users separated by commas(default client)
            -c duplicate cn(defaul off)
            -t use tcp(default udp)
            -d (do not rebuild server keys and configs may be used to recreate or create new client keys )" 

After successfull end You can get client config at /usr/local/etc/openvpn/$username/client.ovpn

Bug reports are appreciated :)


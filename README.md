# getserv

A small python script that returns a server<br>
from the internet at random given a port number.<br>

Optionally provide a CIDR to scan a specific range. <br>

Dependancy is having nmap installed.<br>
Will work on all flavours of linux/mac.<br>
Untested on Windows.<br>

     
    usage: getserv [-h] [-p PORT] [-c] [-d] [-m] [-w]

    Required:
    -p --port     Port number of server, e.g. 80 for HTTP

    Optional:
    -c --cidr     Optionally give cidr to scan, eg. 10.1.1.0/24
    -m --multi    Optionally return more than one server
    -w --web      Optionally open the server in browser
    -d --debug    Enable debugging

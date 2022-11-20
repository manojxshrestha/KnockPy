# KnockPy

Knock is a tool written in Python and is designed to enumerate subdomains in a target domain through a wordlist.

# Installation 

First things first, you have to install the dependencies manually.

     $ sudo apt-get install python-dnspython
     
After that clone the Github repository to your Kali machine. Then, follow the instructions below.

     $ git clone https://github.com/guelfoweb/knock.git
     
     $ cd knock

     $ pip3 install -r requirements.txt
     
     $ python3 knockpy.py
     
     $ nano knockpy/config.json <- set your virustotal API_KEY

![20221120_151130](https://user-images.githubusercontent.com/106522935/202894778-18b92914-abdb-432a-8761-9f64c1cf371f.png)

     $ sudo python setup.py install
     
# Usage

     $ knockpy domain.com

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

     
# Usage
     
     $ knockpy [-h] [-v] [-w WORDLIST] [-r] [-c] [-j] domain
knock subdomain scan

# Optional arguments:

     -h, –help show this help message and exit
     
     -v, –version show program’s version number and exit
     
     -w WORDLIST specific path to wordlist file
     
     -r, –resolve resolve ip or domain name
     
     -c, –csv save output in csv
     
     -f, –csvfields add fields name to the first row of csv output file
     
     -j, –json export full report in JSON

# Example:

     $ knockpy domain.com
     
     $ knockpy domain.com -w wordlist.txt
     
     $ knockpy -r domain.com or IP

     $ knockpy -c domain.com


# Note : 

For virustotal subdomains support you can setting your API_KEY in the config.json file.

https://github.com/guelfoweb/knock

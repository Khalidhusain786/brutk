# brutk 

This program will brute force any Instagram account 
# Requirements 

Python v3.9


proxy list 

# Installation 

git clone https://github.com/Khalidhusain786/brutk.git

cd brutk 


pip install pipenv  
 
 
pipenv --python 3.9 


pipenv install 


pipenv shell 



# Upload Proxy 
  
  3.238.111.248:80

206.189.59.192:8118

165.22.81.30:34100

176.248.120.70:3128

191.242.178.209:3128

180.92.194.235:80  


To upload a list of proxies a similar syntax must be followed.  




python instagram.py -px <path to proxy list>  


 

  
  # Stats 
 
 This gives an insight into the health of the proxies in the database.
 
 
 
 
 python instagram.py --stats 
 
 
# Help

usage:  instagram.py [-h] [-u USERNAME] [-p PASSLIST] [-px PROXYLIST] [--prune PRUNE] [--stats] [-nc] [-m MODE]

optional arguments:
  -h, --help            show this help message and exit 
  
  -u USERNAME, --username USERNAME
                        email or username 
                        
  -p PASSLIST, --passlist PASSLIST 
                        password list 
                        
  -px PROXYLIST, --proxylist PROXYLIST
                        proxy list 
                        
  --prune PRUNE         prune the database 
  
  --stats               get statistics of the proxies 
  
  -nc, --no-color       disable colors 
  
  -m MODE, --mode MODE  modes: 0 => 32 bots; 1 => 16 bots; 2 => 8 bots; 3 => 4 bots 
  
 
 
 
  # Prune 
 
 
 This allows the able to get rid of proxies with a score below a given score.

It is recommended that you run the --stats and prune the database of proxies 
 
 
 

 python instagram.py --prune 0.05

 
 
 
Pruning is not a requirement because the

the system will automatically learn which proxies perform poorly and stop using them.
 
 
 # Usage 
 
 python instagram.py -u <username> -p <passlist> -px (proxylist) -m (mode)

  
# Run 
 
Wordlist: gali.txt

[-] Username: galikachora
 

[-] Password: 580
 

[-] Complete: 65.51%

[-] Attempts: 350

[-] Browsers: 280

[-] Exists: True
  





# subfinder 
subfinder is a scanner for enumerating subdomains written in golang. 

**Author**: [th3jiv3r][twitter]

### New Features!
  -provide any wordlist to the tool to start enumerating subdomains!

### Installation
```sh
$ git clone https://github.com/goodlandsecurity/subfinder.git
$ cd subfinder 
$ go build subfinder.go
```

### Example Use:  
  - *subfinder -domain example.com -wordlist wordlist.txt*
  - *subfinder -domain example.com -wordlist wordlist.txt -server 1.1.1.1:53*
  - *subfinder -domain example.com -wordlist wordlist.txt -server 1.1.1.1:53 -c 50*

#### License
  - GNU General Public License v3.0


[twitter]: <https://twitter.com/th3_jiv3r>

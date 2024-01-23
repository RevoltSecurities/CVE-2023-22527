# CVE-2023-22527
An Exploitation tool to exploit the confluence server that are vulnerable to CVE-2023-22527 leads to RCE which tested and proven POC
in vulnerable instance of confluence data center and servers. By this an attacker can execute arbitary code on vulnerable instance


### Installation:

```bash
git clone https://github.com/sanjai-AK47/CVE-2023-22527.git
cd CVE-2023-22527
pip install -r requirements.txt
python3 exploit.py -h
```

### Usage:
```yaml
python3 exploit.py -h                                                                         
usage: exploit.py [-h] [-d DOMAIN] [-dL DOMAINS_LIST] [-cmd COMMAND] [-c CONCURRENCY] [-o OUTPUT] [-to TIME_OUT] [-px PROXY] [-v]

[DESCTIPTION]: Exploitation and Detection tool for Cisco CVE-2023-46747

options:
  -h, --help            show this help message and exit
  -d DOMAIN, --domain DOMAIN
                        [INFO]: Target domain for exploiting without protocol eg:(www.domain.com)
  -dL DOMAINS_LIST, --domains-list DOMAINS_LIST
                        [INFO]: Targets domain for exploiting without protocol eg:(www.domain.com)
  -cmd COMMAND, --command COMMAND
                        [INFO]: Give your burp collabarator url for exploitation
  -c CONCURRENCY, --concurrency CONCURRENCY
                        [INFO]: Give your burp collabarator url for exploitation
  -o OUTPUT, --output OUTPUT
                        [INFO]: File name to save output
  -to TIME_OUT, --time-out TIME_OUT
                        [INFO]: Switiching timeout will requests till for your timeout and also for BURPSUITE
  -px PROXY, --proxy PROXY
                        [INFO]: Switiching proxy will send request to your configured proxy (eg: BURPSUITE)
  -v, --verbose         [INFO]: Switiching Verbose will shows offline targets

```

### Proof Of Exploitation:


[exploit.webm](https://github.com/sanjai-AK47/CVE-2023-22527/assets/119435129/c1ed2eea-700b-4eeb-aa71-2d3dac7da000)

## Information:

Important thing if any unethical exploitation the I'm not responsible for any illegal actions so plese use this for ethical and legal purposes

Proof of conept Developed by [D.Sanjai Kumar](https://www.linkedin.com/in/d-sanjai-kumar-109a7227b/) with ♥️ for any upgrade and miscoded contact me throguh my [LinkedIn](https://www.linkedin.com/in/d-sanjai-kumar-109a7227b/). Thank you!





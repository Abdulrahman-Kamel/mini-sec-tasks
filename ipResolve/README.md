## About script
This mini script check ip/domain list resolve or no [appending on ping command] , important use before run nmap scanner or ETC.. <br>
Take hosts.txt file ,, return which resolve/runing , take 3 argument (hosts.txt=Required, output.txt=Required, threads=Optional)

## Install
```console
git clone --depth 1 https://github.com/Abdulrahman-Kamel/mini-sec-tasks.git ipResolve
pip3 install subprocess futures
```

## Usage
```python
python3 tool.py subdomains_or_ip.txt results.txt 500
```
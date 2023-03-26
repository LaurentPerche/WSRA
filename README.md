install python
https://www.python.org/downloads/macos/

Clone wafw00f from  https://github.com/EnableSecurity/wafw00f/archive/refs/heads/master.zip
python setup.py install

install go from https://golang.org/doc/install

install subfinder:
go install github.com/projectdiscovery/subfinder/v2/cmd/subfinder@latest

run Subfinder once (that will create provider-config.yaml in ~/.config/subfinder/
edit provider-config.yaml to include all the API Keys

install httpx:
go install -v github.com/projectdiscovery/httpx/cmd/httpx@latest
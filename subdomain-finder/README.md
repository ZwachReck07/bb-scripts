## Installation 

Install go -> https://go.dev/doc/install

Add go path

```
nano $HOME/.bashrc
export PATH="$HOME/go/bin:$PATH"
```

Install dependencies

```
go install github.com/lc/gau/v2/cmd/gau@latest
go install github.com/tomnomnom/waybackurls@latest
go install -v github.com/projectdiscovery/subfinder/v2/cmd/subfinder@latest
go install github.com/tomnomnom/unfurl@latest
go install -v github.com/projectdiscovery/httpx/cmd/httpx@latest
```

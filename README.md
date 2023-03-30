# proxy_config

# For npm

for set

1. npm config --global set proxy=http://[host]:[port]

for unset 

2. npm config --global delete proxy

# pip

for set

1. pip config set global.proxy http://[host]:[port]

in cmd set http_proxy=http://[port]:[host], https_proxy=http://[port]:[host]

for unset

1. pip config unset global.proxy

in cmd set http_proxy=, https_proxy=

# git

for set

1. git config --global --add http.proxy http://[host]:[port]

for unset

1. git config --global --unset http.proxy


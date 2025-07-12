```
apt install build-essential autoconf automake cmake git-core \
libyaml-dev libsqlite3-dev sqlite3 libxml2-dev libxslt1-dev \
libcurl4-openssl-dev libffi-dev nodejs software-properties-common \
yarn gcc g++ libssl-dev zlib1g-dev default-jdk nodejs dirmngr \
apt-transport-https ca-certificates curl libncurses-dev unixodbc-dev unzip
```
```
wget https://go.dev/dl/go1.24.4.linux-amd64.tar.gz
tar -C /usr/local -xzf go1.24.4.linux-amd64.tar.gz
```
```
git clone https://github.com/asdf-vm/asdf.git --branch v0.18.0
```
Run make
Copy the asdf binary into a directory on your $PATH

.bashrc
```
export PATH=$PATH:/usr/local/go/bin
export PATH="${ASDF_DATA_DIR:-$HOME/.asdf}/shims:$PATH"
```
```
asdf plugin add erlang
asdf plugin add elixir
asdf list all erlang
asdf install erlang
asdf list all elixir
asdf install elixir
asdf set erlang
asdf set elixir
```

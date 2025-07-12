```
apk add go vim git make musl-dev curl bash shadow bash-completion autoconf ncurses-dev
apk add gcc build-base freetype-dev libpng-dev openblas-dev openssl-dev openssl
```

```
apk add unixodbc unixodbc-dev yaml-dev
apk add flex flex-dev
```
```
apk add openjdk21
apk add wxwidgets wxwidgets-dev # visual
```
```
git clone https://github.com/asdf-vm/asdf.git --branch v0.18.0
```
Run make
Copy the asdf binary into a directory on your $PATH
.bashrc
```
export PATH="${ASDF_DATA_DIR:-$HOME/.asdf}/shims:$PATH"
```
For example, to skip the java dependency during installation use:
```
export KERL_CONFIGURE_OPTIONS="--disable-debug --without-javac"
```
```
asdf plugin add erlang
asdf plugin add elixir
asdf list all erlang
asdf install erlang 23.2.1
asdf list all elixir
asdf install elixir 1.11.2-otp-23
asdf set erlang 23.2.1
```

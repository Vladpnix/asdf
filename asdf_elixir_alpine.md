```
apk add go vim git make musl-dev curl autoconf ncurses-dev gcc build-base freetype-dev libpng-dev openblas-dev openssl-dev openssl unixodbc unixodbc-dev yaml-dev
```

> apk add flex flex-dev

> [!TIP]
> java and visual

> apk add openjdk21

> apk add wxwidgets wxwidgets-dev
```
git clone https://github.com/asdf-vm/asdf.git --branch v0.18.0
```
> [!CAUTION]
> Run make

> Copy the asdf binary into a directory on your $PATH
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
asdf install erlang 28.0.1
asdf list all elixir
asdf install elixir 1.18.4-otp-28
asdf set erlang 28.0.1
asdf set elixir 1.18.4-otp-28
```

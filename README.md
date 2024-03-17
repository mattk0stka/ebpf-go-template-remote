# ebpf-go-template-remote
based on cilium

### Ubuntu - Install golang

```bash
$ curl -L  https://go.dev/dl/go1.22.1.linux-amd64.tar.gz -o go1.22.1.linux-amd64.tar.gz 

$ tar -C /usr/local -xzf go1.22.1.linux-amd64.tar.gz

$ export PATH=$PATH:/usr/local/go/bin

$ go version
```

#### Dependencies
The following commands are intended for an Ubuntu environment.
```bash
$ sudo apt install update
$ sudo apt install clang
$ sudo apt install llm
$ sudo apt install libbpf-dev
$ sudo apt install sudo apt install linux-headers-generic
$ sudo ln -sf /usr/include/asm-generic/ /usr/include/asm
```
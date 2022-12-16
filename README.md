# remote-terminal

This is a simple binary that you can use to echo data sent from the `rtc` lib, which can currently be 
found under D0liphin/termset/src/rtc.

Installation:

```
$ git clone https://github.com/D0liphin/remote-terminal.git ./remote_terminal && cd remote_terminal
$ cargo build --release
$ mv ./target/release/remote_terminal /bin/remote-terminal
```

or something like that... then just use

```
$ remote-terminal help
Remote terminal host for use with rtc

USAGE:
    remote-terminal [ADDRESS]?

ADDRESS:
    address is a valid IP address to start this host on, defaults to
    127.0.0.1:7777, which is what rtc_println! prints to.
```

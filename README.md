# substratekitties

> Use substrate v0.11 to construct the cryptokitties dapp.

> Here is the tutorial to build the dapp from 0 to 1.

- **[Tutorial](<https://github.com/crosszonetech/substrate-tutorial>)**

> or you can just clone the code and build it on linux with substrate installed environment.

> to install substrate v0.11.(**old**)

```shell
$ curl https://getsubstrate.io -sSf | bash
```

> to install substrate v1.0(new)

```shell
$ curl https://getsubstrate.io -sSf | bash
$ git clone https://github.com/paritytech/substrate.git
$ cd substrate
$ ./scripts/build.sh
$ cargo build --release
```

> then follow the code and  you can run the demo

```shell
$ git clone https://github.com/SherLzp/substratekitties.git
$ cd substratekitties
$ ./build.sh
$ cargo build --release
$ ./target/release/substratekitties --dev --ws-external --rpc-external
```

> Good luck！
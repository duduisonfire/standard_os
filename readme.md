# Standard OS

This repository is an operating system, created for academic purposes, based on the x86_64 architecture.

This implementing uses rust.

## Usage
To compile this program RUN.

```bash
cargo bootimage
```
and RUN this command to execute a Virtual Machine with QEMU.

```bash
sudo qemu-system-x86_64 -drive format=raw,file=./target/x86_64-standard_os/debug/bootimage-standard_os.bin
```

If you use Windows visit the QEMU Docs on: [QEMU Docs](https://www.qemu.org/docs/master/)

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
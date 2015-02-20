# cross

A quick cross compiler script for the GNU Compiler Collection, great for OS developers.

## Running

To download `binutils` and `gcc` locally, simply run:

```sh
./cross.sh
```

To build the compiler into your `$HOME`, pass the script a target architecture:

```sh
./cross.sh <arch>
```

After building the cross compiler, add this to your rc:

```sh
export PATH=$PATH:$HOME/cross/bin
```

## Architectures

### Common
- i686-elf
- x86_64-elf
- arm-eabi

For the full list of supported architectures, visit [here](https://gcc.gnu.org/install/specific.html).

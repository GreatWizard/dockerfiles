# devkitARM-3ds

Everything needed to build 3DS homebrews.

It includes the following libraries build from source:

* [ctrulib](https://github.com/smealum/ctrulib)
* [citro3d](https://github.com/fincs/citro3d)
* [3ds_portlibs](https://github.com/fincs/citro3d): curl

It includes the following tools:

* [3dstool](https://github.com/dnasdw/3dstool)
* [bannertool](https://github.com/Steveice10/bannertool)
* [makerom and ctrtool](https://github.com/profi200/Project_CTR)

## Usage

```sh
docker run --rm -it -v $(pwd):/source greatwizard/devkitarm-3ds
```

### Examples

devkitPro is installed in `/opt/devkitPro` with examples for the GBA, the NDS, the GP32 and the 3DS in the `examples` directory.
You can find several folders to demonstrate how to use various capabilities of the systems.
To build an example, `cd` into its directory and run `make`.

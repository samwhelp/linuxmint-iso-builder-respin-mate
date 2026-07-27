

# Home

| Link | GitHub |
| ---- | ------ |
| [linuxmint-iso-builder-respin-mate](https://samwhelp.github.io/linuxmint-iso-builder-respin-mate/) | [GitHub](https://github.com/samwhelp/linuxmint-iso-builder-respin-mate) |




## Subject

* [Combination](#combination)
* [Environment](#environment)
* [Start](#start)
* [Clone](#clone)
* [Usage](#usage)
* [Config Files](#config-files)
* [Package Install List](#package-install-list)
* [Link](#link)




## Combination

| Project |
| ------- |
| [linuxmint-iso-builder-template](https://github.com/samwhelp/linuxmint-iso-builder-template) |
| `+` |
| [linuxmint-iso-builder-remix-mate](https://github.com/samwhelp/linuxmint-iso-builder-remix-mate) |
| `=` |
| [linuxmint-iso-builder-respin-mate](https://github.com/samwhelp/linuxmint-iso-builder-respin-mate) |




## Environment

* `LinuxMint 23 (Ubuntu 26.04)`




## Start

Open Terminal , and run to install `git` and `make`

``` sh
sudo apt-get install git make
```




## Clone

Run to clone [linuxmint-iso-builder-respin-mate](https://github.com/samwhelp/linuxmint-iso-builder-respin-mate)

``` sh
git clone https://github.com/samwhelp/linuxmint-iso-builder-respin-mate
```

Run to change dir `linuxmint-iso-builder-respin-mate`

``` sh
cd linuxmint-iso-builder-respin-mate
```




## Usage

* [Help](#help)
* [Prepare](#prepare)
* [Build](#build)
* [Clean](#clean)




## Help

Run

``` sh
make
```

Or run

``` sh
make help
```

Show

```
Usage:
	$ make [action]

Example:
	$ make
	$ make help

	$ make prepare
	$ make build
	$ make clean

```




## Prepare

Run the following command to install the packages required to create an ISO file.

``` sh
make prepare
```




## Build

Only need to execute the following command to create an ISO file.

``` sh
make build
```




## Clean

Run to clean up previous builds.

``` sh
make clean
```




## Config Files

| Config Files |
| ------------ |
| [~/.config](https://github.com/samwhelp/linuxmint-iso-builder-respin-mate/tree/main/template/asset/overlay/etc/skel/.config) |
| [/etc/dconf/db/distro.d](https://github.com/samwhelp/linuxmint-iso-builder-respin-mate/tree/main/template/asset/overlay/etc/dconf/db/distro.d) |
| [/usr/share/glib-2.0/schemas](https://github.com/samwhelp/linuxmint-iso-builder-respin-mate/tree/main/template/asset/overlay/usr/share/glib-2.0/schemas) |




## Package Install List

> Please check the folder

* [template/asset/package/install](https://github.com/samwhelp/linuxmint-iso-builder-respin-mate/tree/main/template/asset/package/install)

> Ubuntu Community Help Wiki / [MetaPackages](https://help.ubuntu.com/community/MetaPackages)




## Link

| Link | GitHub |
| ---- | ------ |
| [LinuxMint Mate Adjustment](https://samwhelp.github.io/linuxmint-mate-adjustment/) | [GitHub](https://github.com/samwhelp/linuxmint-mate-adjustment) |
| [LinuxMint Adjustment](https://samwhelp.github.io/linuxmint-adjustment/) | [GitHub](https://github.com/samwhelp/linuxmint-adjustment) |




## Samwhelp

* [GitHub](https://github.com/samwhelp)

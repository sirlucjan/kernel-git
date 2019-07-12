# Kernels and modules:

- linux-aufs-git from "Linux kernel stable tree"
 
- linux-aufs-git from "Linux Stable -rc releases"

- linux-uksm-git from "Linux kernel stable tree"
 
- linux-uksm-git from "Linux Stable -rc releases"

###### linux-aufs-git incorporates:

* [AUFS](https://github.com/sfjro/aufs5-standalone) / [AUFS](http://aufs.sourceforge.net) - advanced multi-layered unification filesystem

###### linux-uksm-git incorporates:

* [UKSM (sources)](https://github.com/dolohow/uksm) / [UKSM (sources)](https://github.com/zaza42/uksm) / [UKSM (patches)](https://github.com/sirlucjan/kernel-patches) / [UKSM (patches)](https://gitlab.com/sirlucjan/kernel-patches) / [UKSM (info)](https://www.usenix.org/sites/default/files/conference/protected-files/fast18_slides_xia.pdf) - resync from dolohow’s / zaza42's github or patches from sirlucjan's github/gitlab (resync from pfkernel)

***

# Download:

```
git clone https://github.com/sirlucjan/kernel-git.git

```
or

```
git clone https://gitlab.com/sirlucjan/kernel-git.git

```

# Install:


# Stable

```
cd /some_path/kernel-git/stable/package_name
makepkg -srci

```

# Stable-RC

```
cd /some_path/kernel-git/stable-rc/package_name
makepkg -srci

```

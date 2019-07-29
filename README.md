# Kernels and modules:

- linux-aufs-git from "Linux kernel stable tree"
 
- linux-aufs-git from "Linux Stable -rc releases"

- linux-bfq-git from "Linux kernel stable tree"
 
- linux-bfq-git from "Linux Stable -rc releases"

###### linux-aufs-git incorporates:

* [AUFS](https://github.com/sfjro/aufs5-standalone) / [AUFS](http://aufs.sourceforge.net) - advanced multi-layered unification filesystem

###### linux-bfq-git incorporates:

* [bfq improvements](https://groups.google.com/forum/#!forum/bfq-iosched) - latest fixes authored by Paolo Valente and BFQ Team

* [bfq-dev](https://github.com/Algodev-github/bfq-mq/commits/dev-bfq-on-5.2) - latest fixes authored by Paolo Valente and BFQ Team

* [LL-patches](https://github.com/sirlucjan/kernel-patches/tree/master/5.1/ll-patches) / [LL-patches](https://gitlab.com/sirlucjan/kernel-patches/tree/master/5.1/ll-patches) - specific patches authored by Piotr Gorski

* [bfq-lucjan-dev](https://github.com/sirlucjan/bfq-mq-lucjan/commits/dev-bfq-on-5.2-lucjan) - latest fixes authored by Paolo Valente and BFQ Team and forked by Piotr Gorski

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

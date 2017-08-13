# Packages for LEDE
LEDE package feed. This is a feed for my [LEDE fork](https://github.com/spyff/lede-mptcp), which contains MPTCP kernel patches.

To use these packages, open the `feeds.conf.default` file, and add the following line:
```
src-git packages https://github.com/spyff/packages.git
```
Then update the feeds with 
```
./scripts/feeds update -a
./scripts/feeds install -a
```

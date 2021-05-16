# This is the APT repository for [`scrt`](https://github.com/loderunner/scrt).

See https://github.com/loderunner/scrt for details.

## Install instructions

To install `scrt` using `apt`:

```shell
sudo echo "deb https://loderunner.github.io/scrt-apt /" > /etc/apt/sources.list.d/scrt.list
curl "https://loderunner.github.io/scrt-apt/key.gpg" | sudo apt-key add -
sudo apt update
sudo apt install scrt
```

## Use

```sh
sudo sh -c "$(curl -fsSL https://raw.githubusercontent.com/rebienkrdns/docker-install-on-ubuntu/main/install.sh)"
```

```sh
sudo usermod -aG docker $USER
```

```sh
sudo apt update;sudo apt upgrade -y;sudo sh -c "$(curl -fsSL https://raw.githubusercontent.com/rebienkrdns/docker-install-on-ubuntu/main/install.sh)";sudo usermod -aG docker $USER;sudo reboot
```

# Tweeks for WSL 1

# How to install

```bash
curl https://raw.githubusercontent.com/DzeryCZ/tweeks-for-wsl/master/.bash_wsl > ~/.bash_wsl
curl https://raw.githubusercontent.com/DzeryCZ/tweeks-for-wsl/master/.bashrc >> ~/.bashrc
curl -s https://raw.githubusercontent.com/DzeryCZ/tweeks-for-wsl/master/wsl.conf |
  sudo tee /etc/wsl.conf > /dev/null && \
  sudo chmod +x /etc/wsl.conf
```

**What will I get?**
- Showing GIT branch in the shell
- Ability to use docker-machine without any issues
- Mount drives to root instead of /mnt (required Win10 build >= 1803)
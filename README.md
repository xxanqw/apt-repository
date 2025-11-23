# xxanqw's APT Repository
To install packages from this repository, run the following commands:

```bash
# 1. Add the GPG Key
wget -O - https://apt.xxanqw.pp.ua/public.asc | sudo gpg --dearmor -o /usr/share/keyrings/xxanqw-archive-keyring.gpg

# 2. Add the Repository
echo "deb [arch=amd64,arm64 signed-by=/usr/share/keyrings/xxanqw-archive-keyring.gpg] https://apt.xxanqw.pp.ua/repo stable main" | sudo tee /etc/apt/sources.list.d/xxanqw.list

# 3. Update and Install
sudo apt update
sudo apt install mikusays
```

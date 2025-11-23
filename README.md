# xxanqw's Repository

### Debian / Ubuntu
```bash
wget -O - https://apt.xxanqw.pp.ua/public.asc | sudo gpg --dearmor -o /usr/share/keyrings/xxanqw.gpg
echo "deb [signed-by=/usr/share/keyrings/xxanqw.gpg] https://apt.xxanqw.pp.ua/repo stable main" | sudo tee /etc/apt/sources.list.d/xxanqw.list
sudo apt update && sudo apt install mikusays
```
### Fedora / RHEL / CentOS
```bash
sudo dnf config-manager --add-repo https://apt.xxanqw.pp.ua/rpm/xxanqw.repo
sudo dnf install mikusays
```

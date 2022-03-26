```
curl -s --compressed "https://xlanor.github.io/ppa/KEY.gpg" | sudo apt-key add -
sudo curl -s --compressed -o /etc/apt/sources.list.d/my_list_file.list "https://xlanor.github.io/my_ppa/my_list_file.list"
sudo apt update
```

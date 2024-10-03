# ssh-permission-fixer
A simple bash script to automatically set the correct ownership and permissions for the `.ssh` directory and its contents based on the current directory's name. Ensures a secure setup for SSH configurations with minimal effort.

## Install
cURL:
```bash
sudo curl -sL https://raw.githubusercontent.com/AliGencsoy/ssh-permission-fixer/refs/heads/main/ssh-permission-fixer -o /usr/local/bin/ssh-permission-fixer && sudo chmod +x /usr/local/bin/ssh-permission-fixer && sudo chown $(whoami):$(whoami) /usr/local/bin/ssh-permission-fixer
```

wget:
```bash
sudo wget -q -O /usr/local/bin/ssh-permission-fixer https://raw.githubusercontent.com/AliGencsoy/ssh-permission-fixer/refs/heads/main/ssh-permission-fixer && sudo chmod +x /usr/local/bin/ssh-permission-fixer && sudo chown $(whoami):$(whoami) /usr/local/bin/ssh-permission-fixer
```

## Usage
After installed successfully just run `ssh-permission-fixer` in parent directory of `.ssh` folder.

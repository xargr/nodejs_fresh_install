# Node js fresh install

========================

estimated time: 35 seconds

========================

__The script included:__

  * Update your [Ubuntu](https://www.ubuntu.com/) / [Debian](https://www.debian.org/) server
  * Fix common error with locale
  * Remove and delete unused packages
  * Install [yarn](https://yarnpkg.com/lang/en/) package manager
  * Install [n package](https://github.com/tj/n) nodejs version manager
  * Install with n package the latest lts version of nodejs
  * Install [pm2 package](https://github.com/Unitech/pm2)
  * Install [nginx](https://www.nginx.com)
  * Delete the installation script



Login in new server with ssh and run commants below


Download installation script

```
wget https://raw.githubusercontent.com/xargr/nodejs_fresh_install/master/install.sh
```

Give it right execute permitions

```
sudo chmod +x install.sh
```

And run

```
./install.sh
```

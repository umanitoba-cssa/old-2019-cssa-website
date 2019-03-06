# cssa-website

## Install NodeJS

#### Verify your environment (Linux/MacOS)

Check to see whether NodeJS is already installed by running `node --version`. If this returns a version, you already have NodeJS installed. We will be using v10.15.3, so please make sure you're using this version.

TODO: How to check whether you have NodeJS installed with Windows

### Setup instructions for Linux/MacOS

#### Install NodeJS using the Node Version Manager (NVM)

1. Open up a terminal
2. Run `curl -sL https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh -o install_nvm.sh`
3. Inspect the script you just downloaded by opening it with your favourite text editor (vim, vi, nano, et cetera...)
4. Once you are satisfied with the contents of the script, run it with `bash install_nvm.sh`
5. This script made some changes to your profile configuration. Reload the configuration by running `source ~/.bashrc`
6. Verify nvm installed by running `nvm --version`
7. Install the correct NodeJS version by running `nvm install 10.15.3`
8. Verify the installation by running `node --version`
9. Verify the package manager came with it by running `npm --version`
10. Delete the nvm install script `rm install_nvm.sh`

### Setup instructions for Windows

Grab the Windows Installer from this link:
https://nodejs.org/dist/v10.15.3/node-v10.15.3-x86.msi

TODO: Someone who installs with Windows please expand these instructions.

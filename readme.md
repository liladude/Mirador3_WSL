## List on steps
1. Create new WSL2 Debian from scratch
2. Update

        $ sudo apt-get update
        $ sudo apt-get upgrade
        $ sudo apt-get install curl
        
3. Install nodejs and npm (https://docs.microsoft.com/it-it/windows/dev-environment/javascript/nodejs-on-wsl)

        $ curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
        $ exit
        $ sudo apt install nodejs npm
        
4. Upgrade npm (standard is now 5.8) and exit for it to take effect

        $ sudo npm install -g npm@latest
        $ exit
        
5. Reopen Debian shell and check version (as of May 2021)

        $ npm -v
        7.13.0
        
6. Install mirador on user dir

        

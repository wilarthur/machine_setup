# Node and Git config

## NVM, Node and npm

1. Install cURL (a tool used for downloading content from the internet in the command-line) with: ```sudo apt-get install curl```
2. Run ``` curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/master/install.sh | bash ``` to install NVM (Node Version Manager)
3. Run ```nvm --version``` to check the installation has worked and is installed correctly
4. Run ```nvm ls``` to list the currently installed Node versions (there shouldn't be any yet, so don't worry about any errors!)
> It is recommended that you install a LTS version, as well as the latest stable version of node

5. To install the LTS version, run ``` nvm install --lts ```
6. To install the latest stable build of node, run ```nvm install node```
7. Re-run ```nvm ls``` to view the currently installed node versions
8. By defualt, the LTS build will be used. To use the latest stable build, navigate to a directory that uses node and run  ```nvm use node```. To switch back to the LTS build, use ```nvm use --lts```


More information found on the [Microsoft website](https://learn.microsoft.com/en-us/windows/dev-environment/javascript/nodejs-on-wsl) for NVM and Node in WSL.

## Git and GitHub

1. Run ```sudo apt install git``` to install Git
2. Run ``` git --version ``` to check the installed version of Git
3. Run ``` sudo apt install gh``` to install GitHub
4. Run ```gh auth login``` to run the login process for GitHub
5. Authenticate using a Web Browser and copy the generated one-time code
6. Paste the code in the browser (For WSL, you have to manually navigate to the site in a Windows browser)
7. Select SSH as the default protocol (This method is more secure than HTTPS)
8. Let GH generate and store the SSH key for you
9. Try and clone any GH repo and GH will ask you to set your email address and username so they know who is making the request
10. GH CLI should now be configured

# WSL config and setup on W11

## Installing WSL and Ubuntu

1. Open Powershell and enter:
   ```
   wsl --install
   ```
3. Restart the machine
4. Terminal will automatically re-open and ask for prompts for username and password
5. Ubuntu successfully installed as default Linux Distro for WSL

## Updating Ubuntu

1. Run the following to update and upgrade the distro to the latest version
    ```
   sudo apt update && sudo apt full-upgrade
    ```
2. Restart WSL using the **Powershell** command (this will not work in the Ubuntu terminal):
   ```
   wsl --shutdown
   ```
3. Close the terminal and reopen Ubuntu using Windows Terminal to restart the WSL service

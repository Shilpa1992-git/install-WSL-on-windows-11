# install WSL on windows-11
⏺️Step by Step
1: Open power Shell as Administrator = Search PowerShell in the start menu right-click and select run as administrator.

2: Enable WSL =

wsl  -- install
° This command installs WSL the Linux kernel and Ubuntu by default.

3: Restart Your Computer =

4: Set Up Ubuntu (your Linux Distribution) = After reboot Ubuntu will launch. ° Create a username and password for your Linux user.

5: Check WSL Version =

Wsl --list --verbose
° Ensure it says WSL2 next to your distribution.

6: Update WSL
wsl --update

7: Run Linux Command = Open Ubuntu from the start menu and start using Linux command. Example command =
sudo apt update && sudo apt upgrade

° This updates your Ubuntu packages.

⏺️ Connect WSL Ubuntu to Remote Server

1: Open WSL Terminal = Launch Ubuntu from the start menu.

2: Install Open SSH (if not already installed)

3: Go to file and select download key

4: Selecting Ubuntu in the folder containing the files.

5: After this go to folder your name or the folder you created and select home.

6: After going home copy the key you created and paste it on your local place.

7: your local server will be connected to the remote server.


ls
cd
ls
batch-9key.pem: (zone identifier)

chmod 400 batch-9key.pem




                                                                                                                                                                                         

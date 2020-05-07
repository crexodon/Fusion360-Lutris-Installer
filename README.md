# Fusion360-Lutris-Installer

My own install script for a Lutris based installation of fusion360.
## Dependencies
- Wine-Stable
- Winetricks
- Lutris

## Installation
- start the script with 'lutris -i /path/to/installation-file.yml'
- after doing some preparation the installer will pop up and look frozen for a while (it's downloading fusion)
- then you'll be able to log in
- now check this video https://imgur.com/a/oZCuoP2, you'll need to go to your preferences, and change the graphics driver to directx 9 and then hit apply and not restart (instead, kill the lutris-wrapper process with your taskmanager)
- the script will do some config again and then fusion should pop back up. This time you should be able to create a sketch and draw around
- When you're done testing, the first close probably won't work. So you'll need to kill the lutris-wrapper again with your taskmanager to fully finish the installation

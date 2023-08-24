# myUbuntu - Customizing Ubuntu with scripts

Occasionally, I break my Ubuntu machine, install Ubuntu on another computer, upgrade it, or switch to a different variant.

I want 

- Favorite tools and required packages installed without manual intervention.
- /etc/fstab reconfigured to include my home directory, downloads, and pictures.
- network shares added to /etc/fstab
- printer drivers installed and the network printer configured

It's a little to ask, but it avoids some busy work.

3 lines to add to /etc/fstab for home, downloads and pictures
more lines to add to /etc/fstab for the network shares
restart the shell
a list of packages to install using apt install
a list of packages to install using snap
a method for downloading  or updating.deb packages for products that don't play nice with apt
run configure/install scripts for pre-requisites of projects I work on

Once installed, I like to keep things up to date.
Visual Studio Code, has a monthly update
handled inside the application.
Others require special handling.

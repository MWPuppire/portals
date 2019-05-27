# Portals

Portals is a quick way of moving between directories.
It allows you to open portals in two different directories and move between them using the portals.

## Available Commands
```pOrange [relative path]``` creates an orange portal

```pBlue [relative path]``` creates a blue portal

```pWhere``` shows the current positions of both portals

```pClose``` closes both portals

```pJump [directory]``` allows for moving between portals easily

## Installation

To install portals, you can run the install script using curl:

```curl -o- "https://raw.githubusercontent.com/mwpuppire/portals/master/install" | bash```

or wget:

```wget -qO- "https://raw.githubusercontent.com/mwpuppire/portals/master/install" | bash```

This script clones the repository to ```~/.portals``` and adds the source line to your profile
(```~/.bash_profile```, ```~/.zshrc```, ```~/.profile```, or ```~/.bashrc```).
The script needs ```git``` to install portals.

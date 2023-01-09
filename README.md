# dotInstall
## What
dotInstall downloads a bunch of dot files (text files that specify  configuration of an application) and sticks them in places.
It includes configs for
- zsh
- nvim

features:
- zsh
  - antibody
  - ...
- nvim
  - lua config
  - plugins

## How
it's a simple script that uses shell.
There is no complex logic here so a more complicated language is not needed.
The script is simply automating the manual tasks, nothing special, so simply moving files :D

## Why
Many times I have had to download my dotfiles for all the hosts that I spin up.
Having a quick and easy install script to do all that manual work will save me a lot of time.

## Do
- [ ] create functions for each of the install sections.
- [ ] implement logic if files / folders / applications already exists

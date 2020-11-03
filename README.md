# vim_git
My vimrc as used in WSL (Windows uses seperate vimrc, changes to this vimrc are not reflected as such). If you would like to combine it with preset configurations like amix, follow the instructions to install their configuration, then use their vimrc as your main vimrc and add personalizations at the end of the file (also ensure that it points to the amix file).

## Instructions
### WiNdOWs
Clone the repository into your root directory and use 'mklink' (Windows - Link to Target) has to symlink the .vimrc file into the root directory.
> Hint: If you get a "You do not have sufficient privilege to perform this operation.", try doing mklink in an admin-opened command prompt.
> Also mklink doesn't exist in PowerShell

### Linux
Clone the repository into your root directory and use 'ln' (Linux - Target to Link) to symlink the .vimrc file into the root directory.

### PyCharm
Clone as you would systemwide and Symlink with Link name/path set to ~\.ideavimrc

## Customizations
* Remapped 'Esc' to 'ii' for easy switching to and from insert mode
* Turned off system sounds from Windows (no binging every time I hit a side of the window)
* Allowed for use of 'S-Enter' and 'Enter' in normal mode without entering insert
* Remapped a shortcut to edit and source-from vimrc from within an existing editor

# My Config Files!

## Currently Included:
- Neovim
- Helix

The recommended way to use these configs is with stow. For example, for neovim:
- Move/Delete the existing nvim folder (in ~/.config) if applicable (otherwise stow may detect conflits and abort the operations)
- Put the "cyncrovee-main-config" repository in your home folder
- CD into the repository
- Then run
```sh
stow nvim
```
- Neovim should now use the new config

Stow is recommended, but not needed, you can also just copy and paste the files you need if you wish. If you do want to use stow, you may need to install it first

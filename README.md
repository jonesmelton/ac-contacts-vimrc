# SETUP
* Clone the repo. 
* Symlink the included vimrc to your `.vimrc` in your home directory: `ln -s /path/to/this/vimrc ~/.vimrc`
* Install the plugins. From the command line run `vim +PlugInstall`.

# Things to know
* This config uses `,` as a "Leader key" which is sort of like a namespace for custom commands. Macros and plugin commands will often start with this.
* `, 1` will open the sidebar tree.
* The original author set `jj` as a second way to exit insert mode, which I actually kind of like so I kept it.
* This is set up with a bunch of powerful plugins I don't know how to use. We'll just have to explore. A lot of IDE-like features are set up and at least nominally configured, we just have to figure out how to invoke them.
* `fzf` is a powerful finder that might or might not be working out of the box in this setup. Commands and keybindings are declared around line 325 of the `.vimrc`.

# Configuration and decisions
* I installed two themes for now. You can install more just by putting them in the `/.vim/colors` directory. Try one out by running `:color theme_name`. Set one permanently by modifying the `colorscheme` around line 350 in the `vimrc`.

# VIM for ruby programmers

### Talking Points
  - What Is Vim
  - Why Would I use Vim or Neovim
  - How Do I use Vim:
    1. Exiting Vim.
    2. Navigating Files in Vim
    3. Saving and Editing files in Vim
    4. Configuring Vim

## What is Vim

Well what is VIM, well VIM is Vi improved. 
Vi was the original UNIX text editor back in the 1970's.

Vim add plug-in and syntax support. The plug-ins are written in 
Vimscript. Neovim( New Vi Improved ) added support for LSP protocol and Lua programming language for plug-in development. 

Vim has a large fan base that has made a plugin for every programing language, cli tool or IDE on the market.
I use Neovim with LunarVIM Configuration, as my IDE of chose. I can use Neovim with 


## Why Would I use Vim or Neovim

Vim, Vi and Neovim are in every Linux distribution and Vim or VI is pre-installed on most Linux Distributions.
This allows for you to edit configurations and scripts without having to leave the server.
This means you can spend more time working and Make maintaining your back-end program more effective.

Vim is very ergonomical. If you spend many hours a day typing you are doing yourself a disservice by not using Vim or 
Vim based keyboard bindings. By using Vim keyboard bindings I have saved myself shoulder pain and time, because I spends less time
think and typing and Just code and go off of muscle memory. 


## How Do I use Vim:
  - Command Mode
    * Edit Mode
    * Normal Mode
    * Command Mode



  1. Exiting Vim 

  There is a meme.  When You Finally Exit Vim, You know I am something of a Scientist Myself.
  To exit Vim, VI or Neovim you run Shift + : to enter command mode, then q to quit. 
  To quit with out saving, command mode then q! and to save and quit, command mode then wq

  2. Navigation 

  Files are navicated in Vim with the home-row keys, 'hjkl', 'h' is left, 'l' is right, 'j' an 'k' are up and down. 
  you can mix navication commands with exiting commands. 

  3. Saving and Editing Files

  Saving a file you must enter command mode the same way you would to exit Vim, then 'w' to write to disk.
  Sometimes an action must be followd by "!" force it completion. 

  4. Configuring Vim

  To configure Vim you nead to now either Vimscript or Lua for for Neovim.
  VimRC files are very simalar to bashrc files and other dotfiles as they are known.

  Configuring Vim or Neovim from scratch is very complated and takes months to years to master.
  But I will show you 2 community distributions of Vim/Neovim that will help you bootstrap your
  custom Vim Settup.

  - SpaceVim:
  
  SpaceVim is a Vim distribution that is a one command install, drop-in system that allows you to easily 
  configure Vim or Neovim, it is very beginer friendly and can be configured from within Vim/Neovim itself.

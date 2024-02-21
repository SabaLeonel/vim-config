# Home directory 

First create the following directory structure in your home directory.

```mkdir -p ~/.vim ~/.vim/autoload ~/.vim/backup ~/.vim/colors ~/.vim/plugged```

Create a .vimrc file in your home directory.

```touch ~/.vimrc```

# Colors

Installing a color scheme is a simple as adding a <colorscheme>.vim file to the ~/.vim/colors/ directory.

```cd ~/.vim/colors```

```curl -o molokai.vim https://raw.githubusercontent.com/tomasr/molokai/master/colors/molokai.vim```

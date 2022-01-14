# My Dotfiles

Just [Anton's](https://twitter.com/the-anthony-s) dotfiles. You can copy these in and everything is ready for the races.

## Installation

1. Clone this repo

    ```
    mkdir -p ~/code && cd ~/code && git clone https://github.com/the-anthony-s/dotfiles.git
    ```

2. Install Homebrew

    ```
    /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    ```

3. Install MacVim, rbenv, ruby-build, and more

    ```
    brew install macvim rbenv ruby-build postgresql elasticsearch redis zsh
    brew install Caskroom/cask/iterm2
    brew install Caskroom/cask/google-chrome
    ```

4. Install Oh-My-ZSH

    ```
    sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
    ```

5. Install Janus for Vim

    ```
    curl -L https://bit.ly/janus-bootstrap | bash
    ```

    Don't forget to checkout Janus' [documentation](https://github.com/meetecho/janus-gateway)

6. Symlink configs

    ```
    ln -s ~/code/dotfiles/zsh/zshrc ~/.zshrc
    ln -s ~/code/dotfiles/vim/vimrc ~/.vimrc
    ln -s ~/code/dotfiles/psqlrc ~/.psqlrc
    ln -s ~/code/dotfiles/gemrc ~/.gemrc

    vim +PluginInstall +qall
    ```

7. Open iTerm and import color scheme from iterm folder

# Other tips

Here are some other useful commands I like to use:

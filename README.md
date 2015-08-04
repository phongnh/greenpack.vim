greenpack.vim
=============

List of green colorschemes. These are copied from [vim.org](http://www.vim.org/).

* chlordane
* greenvision
* marklar
* matrix
* relaxedgreen
* reloaded
* revolutions

Installation
------------
Manual install

	mkdir -p ~/.vim/colors
	git clone https://github.com/phongnh/greenpack.vim.git .
	cp greenpack/colors/* ~/.vim/colors

Use [vim + pathogen](http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen)

    cd ~/.vim
    git submodule add https://github.com/phongnh/greenpack.vim bundle/greenpack.vim

Use vim plugin manager

	" https://github.com/VundleVim/Vundle.vim
	Plugin 'phongnh/greenpack.vim'
	:PluginInstall

	" https://github.com/junegunn/vim-plug
	Plug 'phongnh/greenpack.vim'
	:PlugInstall
	
	" https://github.com/Shougo/neobundle.vim
	NeoBundle 'phongnh/greenpack.vim'
	:NeoBundleInstall

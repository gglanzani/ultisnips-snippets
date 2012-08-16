ultisnips-snippets
==================

These are my snippets, to be used with
[Ultisnips](https://github.com/guns/ultisnips.git). If you are using
[pathogen](https://github.com/tpope/vim-pathogen/) or
[vundle](https://github.com/gmarik/vundle/) you can do the following to use
only these snippets, instead of the ones coming with Ultisnips:

## Pathogen

    cd .vim
    git clone https://github.com/gglanzani/ultisnips-snippets.git bundle/snippets

and then add

    let g:UltiSnipsSnippetDirectories=["my_snippets"]

to the bottom of your `.vimrc`

## Vundle

Add to your `.vimrc`

    Bundle 'gglanzani/ultisnips-snippets.git'
    let g:UltiSnipsSnippetDirectories=["my_snippets"]

and then launch vim like so

    vim +BundleInstall +qall

That should be it.

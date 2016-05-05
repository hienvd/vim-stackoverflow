vim-stackoverflow
=====

**vim-stackoverflow** is a tiny plugin that allows you to perform a quick Stackoverflow search directly from Vim.

It opens a new browser window with results.

With inspiration from [vim-g](https://github.com/szw/vim-g)


Installation
------------

### Vundle

Add to your .vimrc

`Plugin 'hienvd/vim-stackoverflow'`

then open VIM, install

`:PluginInstall`



Usage
-----

To lookup a word (or words) in Stackoverflow use `SO` command:

    :SO ruby

`SO` command can use a word under the cursor. Just move the cursor to the word and type the same command in the
command line:

    :SO

Additionally, you can select words in the visual mode exactly in the same way. Just select words and type
`:SO`. You can also prepend your selection with more clues:

    :SO function
    :SO ruby

There is also a special command named `SOf` to prepend the current file type automatically:

    :SOf
    :SOf function


Configuration
-------------


License
-------

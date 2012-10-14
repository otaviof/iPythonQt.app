# IPythonQt.app

Mac OS app bundle for IPython QtConsole, with a simple wrapper to call:

    ipython --qtconsole --colors=linux


## Installing this App

    git clone http://github.com/otaviof/IPythonQt.app.git
    cd IPythonQt.app
    $ open .

Optionally you can drag and drop `IPythonQt.app` folder to your `/Applications`
or `~/Applications`.

## Integrate with MacVim/Vim

To simply *send* code into the newest created `qtconsole` window from MacVim I
recommend the following plugin: [ipqtmacvim][1] (with a few fixes to make it
work with Pathogen). And if you want a double way integration with IPython you
may also try [vim-ipython][2].

[1]: https://github.com/jkitzes/ipyqtmacvim
[2]: https://github.com/ivanov/vim-ipython

### Reference:
<http://neuroscience.telenczuk.pl/?p=400>

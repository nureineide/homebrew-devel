# homebrew-devel

My own [home-brew taps](https://github.com/mxcl/homebrew/wiki/brew-tap).

## How do I install these formulae?

Just `brew tap nureineide/devel` and then `brew install <formula>`.

If the formula conflicts with one from [mxcl/master](https://github.com/mxcl/homebrew) or another tap, you can `brew install nureineide/devel/<formula>`.

You can also install via URL:

`brew install https://raw.github.com/nureineide/homebrew-devel/master/<formula>.rb`

## Taps

### mutt-patched

Based on mutt 1.5.22 and also contains the sidebar (`--with-sidebar-patch`) patch, though not the newest ones and the trash (`--with-trash-patch`)  patch.

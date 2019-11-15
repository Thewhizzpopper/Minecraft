I forked this project from fogleman and am adding improvements such as weather, inventory, etc. I release updates every few weeks with different features, and I'll be working on a changelog down at the bottom of this README. Sticking with fogleman's style, I've commented extensively on everything I've done so that future programmers can understand how to edit the features of my addons to the Minecraft world. The amount of creativity in Minecraft is astounding, and there's even more of it when you get to code your own world. Thus, I'm building up a world for future programmers, both literally and figuratively. Enjoy playing in and editing this Minecraft world!


## How to Run

```shell
pip install pyglet
git clone https://github.com/fogleman/Minecraft.git
cd Minecraft
python main.py
```

### Mac

On Mac OS X, you may have an issue with running Pyglet in 64-bit mode. Try running Python in 32-bit mode first:

```shell
arch -i386 python main.py
```

If that doesn't work, set Python to run in 32-bit mode by default:

```shell
defaults write com.apple.versioner.python Prefer-32-Bit -bool yes 
```

This assumes you are using the OS X default Python.  Works on Lion 10.7 with the default Python 2.7, and may work on other versions too.  Please raise an issue if not.
    
Or try Pyglet 1.2 alpha, which supports 64-bit mode:  

```shell
pip install https://pyglet.googlecode.com/files/pyglet-1.2alpha1.tar.gz 
```

### If you don't have pip or git

For pip:

- Mac or Linux: install with `sudo easy_install pip` (Mac or Linux) - or (Linux) find a package called something like 'python-pip' in your package manager.
- Windows: [install Distribute then Pip](http://stackoverflow.com/a/12476379/992887) using the linked .MSI installers.

For git:

- Mac: install [Homebrew](http://mxcl.github.com/homebrew/) first, then `brew install git`.
- Windows or Linux: see [Installing Git](http://git-scm.com/book/en/Getting-Started-Installing-Git) from the _Pro Git_ book.

See the [wiki](https://github.com/fogleman/Minecraft/wiki) for this project to install Python, and other tips.

### Changelog:
I will be uploading new code sometime soon



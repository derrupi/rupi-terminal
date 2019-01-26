# rupi-terminal
My beautiful and very useful terminal configuration with hyper and zsh

![the terminal on my working computer](https://github.com/derrupi/rupi-terminal/blob/master/Screenshot.jpg)

## installation
I tested this on linux and mac.  

1. Download and install [hyper](https://hyper.is/#installation) 

2. Next, you need to install zsh
```	
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

3. After installation zsh you have to set zsh as a default bash. 
```
// /bin/zshv
which zsh 
// set zsh as default 
chsh -s /bin/zsh
```

4. Restart your computer

5. Download ```.hyper.js``` and copy the file into your home directory

6. Git clone ```zsh-autosuggestions``` for autocomplete

```
git clone https://github.com/zsh-users/zsh-autosuggestions ~/.zsh/zsh-autosuggestions
```

7. Download ```.zshrc``` and copy the file into your home directory

8. Enjoy hyper with zsh :-)	

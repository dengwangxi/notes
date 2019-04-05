+ Modify mirror   
  1. /etc/pacman.d/mirrorlist.mingw32   
     Server = http://mirrors.ustc.edu.cn/msys2/mingw/i686
  2. /etc/pacman.d/mirrorlist.mingw64  
    Server = http://mirrors.ustc.edu.cn/msys2/mingw/x86_64
  3. /etc/pacman.d/mirrorlist.msys  
    Server = http://mirrors.ustc.edu.cn/msys2/msys/$arch
  4. Run pacman -Sy to refresh package

+ Install vim
+ Install ag   
  pacman -S mingw-w64-x86_64-ag, and add /mingw64/bin to path.
+ Install fzf
+ Install modified fatty
+ Install zsh tmux

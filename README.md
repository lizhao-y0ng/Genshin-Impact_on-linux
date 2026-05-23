在本次游戏更新后不需要也不能要任何的域名屏蔽。此外关于wine游戏闪退的bug已经修复
具体方法：
  1.下载国服原神，并安装到你可以找到的位置比如我的是“/mnt/3T/anime/YuanShen/”，任何方法都可以，不再赘述
  2.下载并安装steam
    Arch系列：sudo pacman -S steam
    debian系列：sudo apt install steam
3.下载dwproton
  命令：wget 'https://dawn.wine/dawn-winery/dwproton/releases/download/dwproton-11.0-2/dwproton-11.0-2-x86_64.tar.xz'
  解压：tar -xf ./dwproton-11.0-2-x86_64.tar.xz
  把解压后的文件夹放到 '$HOME/.local/share/Steam/compatibilitytools.d/'文件夹下面
  重启steam添加非steam游戏选择原神，打开兼容性的页面选择dwproton-11.0-2-x86_64
4.开始游戏

# eva-config

这是一份emacs+evil+auto-complete+gdb快捷键的自用快速配置方案

方案包含vim按键绑定,自动补全,以及将gud作为调试器全面配置. 

按键绑定修改keybinding.el

evawiz系列是为EVAWIZ脚本准备
其中的c++ mode扩展了EVAWIZ的C++语法特性

快速配置命令:
```
mkdir ~/.emacs.d
cd ~/.emacs.d
git clone https://github.com/einsxiao/eva-config
mv init.el init.el.bak
ln -s eva-config/init.el init.el
```

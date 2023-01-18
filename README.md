# mac左右shift切换自带输入法
不使用搜狗输入法，使用mac自带输入法，修改中英文切换快捷键，规则网上找的

1. 修改输入法切换快捷键，改到一个不常用的组合上面
- ``系统偏好设置``-``键盘``-``快捷键``-``输入法``-``选择上一个输入法``，设置为``control + option + command + 0``

2. 安装[karabiner-elements(官网)](https://karabiner-elements.pqrs.org)
- ``brew install karabiner-elements``

3. 将规则导入karabiner
- ``karabiner://karabiner/assets/complex_modifications/import?url=https://github.com/benbenit/mac-left-shift-change/blob/main/left-shift-change-input.json``
- 注意：这里我在使用网络导入的时候，karabiner崩溃重启，导入不进去。换成本地地址，将``左shift切换输入法.json``,下载到``.config/karabiner/assets/complex_modifications/``路径下，只需要将下面的用户名改成你自己的，然后在浏览器打开本地路径即可导入
- 本地路径：``karabiner://karabiner/assets/complex_modifications/import?url=file:///Users/niuben/.config/karabiner/assets/complex_modifications/左shift切换输入法.json``

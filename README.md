# mac左右shift切换自带输入法
不使用搜狗输入法，使用mac自带输入法，修改中英文切换快捷键，规则网上找的

1. 修改输入法切换快捷键，改到一个不常用的组合上面
- ``系统偏好设置``-``键盘``-``快捷键``-``输入法``-``选择上一个输入法``，设置为``control + option + command + 0``

2. 安装[karabiner-elements(官网)](https://karabiner-elements.pqrs.org)
- ``brew install karabiner-elements``

3. 将规则导入karabiner
- 复制``左shift切换输入法.json`中的内容
- 粘贴到本地路径：``/Users/niuben/.config/karabiner/assets/complex_modifications/左shift切换输入法.json``
- 浏览器打开``karabiner://karabiner/assets/complex_modifications/import?url=file:///Users/niuben/.config/karabiner/assets/complex_modifications/左shift切换输入法.json``

# Try Vim

本文档使用 `Vim` 撰写。

## 移动光标

<kbd>h</kbd> <kbd>j</kbd> <kbd>k</kbd> <kbd>l</kbd>

使用 <kbd>h</kbd> 往左移动一个空格<br>
使用 <kbd>l</kbd> 往右移动一个空格<br>
使用 <kbd>k</kbd> 往上移动一行<br>
使用 <kbd>j</kbd> 往下移动一行<br>

<kbd>b</kbd> <kbd>w</kbd>

使用 <kbd>b</kbd> 往左移动一个单词的距离<br>
使用 <kbd>w</kbd> 往右移动一个单词的距离<br>

## 模式

Vim 有三种模式，默认模式叫 `Normal Mode`，在这个模式你可以通过 <kbd>shift</kbd> + <kbd>;</kbd> 切换到命令模式，或者移动光标浏览文本内容。

在 `Command Mode` 下输入 `q` 然后回车可以退出且不保存，输入 `wq` 可以保存后退出。

在 `Normal Mode` 下点 <kbd>i</kbd> 会进入 `Insert Mode`，这时你可以开始编辑内容、插入文本。

在 `Normal Mode` 下点 <kbd>v</kbd> 会进入 `Visual Model`，这时你可以移动光标选择一段文本。

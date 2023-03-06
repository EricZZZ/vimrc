# Vim 编辑器

Vim 和 Emacs 谁是最好的编辑器，一直争论不断，最终学习哪个，也一直没有确定下来，导致学习计划也荒废很久了。

最终在摇摆不定中决定先入坑 Vim 🎉，平常远程操作 Linux 主机上面是自带 Vim，自己的 MBP 也内置 Vim，加上之前也有轻度使用 Vim ，至少知道怎么退出 Vim 😂。

基于 [amix/vimrc basic](https://github.com/amix/vimrc/blob/master/vimrcs/basic.vim) 的配置修改，边学习边补充。

## 使用相关
进入 Vim 编辑器后不同模式间的转换。

![Vim 编辑器模式转换](https://miasanmia.oss-cn-beijing.aliyuncs.com/picture/2023/02/22/069b799e-62bb-47f7-b7ef-11f875d88b7a.png)

## 快捷键使用
### 命令模式下

光标移动。

h ← ， j ↓ ， k ↑ ， l → 。

w `word` 往下移动一个单词。

b `back` 往回移动一个单词。

往下翻页，Ctrl + f `forword`。

往上翻页，Ctrl + b `backword`。

跳到某行，行数 + gg ，例：跳到88行,88gg。

往上或往下跳几行，例：往下跳十行，10j。

/ 搜索，找到关键字，n `next`下一个关键词，Shift + n 上一个关键词。

删除整行，cc 删除当前光标所在行，u `undo` 撤销操作 U 撤销当前行的操作，删除多行，例：删除 2 行 c2c。

p 粘贴，x 删除光标所在字符。

dw `delete word` 删除 1 个单词 ，删除多个单词, 例：d3w 删除 3 个单词。 c3w 删除 3个单词，并进入插入模式。

在当前行任意位置 按 0 光标移到最前端，$ 光标移到最末端。 

d$ 删除光标处到当前行最末端。

dd 删除当前行，删除多行，例：删除3行 3dd。

r 替换光标所在字符。

ce 删除当前光标所在单词，并进入插入模式。

% 可以使光标快速移动到(,),[,],{ or }，对调试代码时很有用。

## 插件

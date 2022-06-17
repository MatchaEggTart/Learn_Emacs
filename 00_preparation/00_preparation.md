# 准备

* 首先如何设置 emacs 编码 为utf-8
    1. 修改 ~/.emacs.d/init.el

        ```shell {.line-numbers}

        emacs ~/.emacs.d/init.el
        ```

        添加一行

        ```lisp {.line-numbers}
        (set-language-environment "UTF-8")
        ```

        使用 [Ctrl]+[x] [Ctrl]+[s] 保存\
        使用 [Ctrl]+[x] [Ctrl]+[c] 退出
    2. 重启 emacs，点击 Emacs Tutorial

* 看该目录下，我放置了 Emacs Tutorial 的中文版
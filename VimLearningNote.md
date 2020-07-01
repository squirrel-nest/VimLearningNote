# 常用操作
## 文件操作
   * 参考
      + 这篇的图解很好 - [Graphical vi-vim Cheat Sheet and Tutorial](http://www.viemu.com/a_vi_vim_graphical_cheat_sheet_tutorial.html)<br>
      + [精通 VIM ，此文就够了](https://zhuanlan.zhihu.com/p/68111471)<br>
## 快捷键
   * 参考
      + 
      + [vim 常用快捷键及使用技巧](https://www.jianshu.com/p/dde77e3b299f)<br>
      + [Vim (vi) 编辑器快捷键大全【图解】，各种操作，指令大全 | 从无到有 | linux | mac | terminal](https://segmentfault.com/a/1190000016056004)<br>
# 环境设置
## System 环境设置
   * 参考
   * 步骤
      1. 切换到主用户目录：
      2. 复制vim的系统配置文件：
      3. 编辑用户配置文件.vimrc：
      4. 按 i 进入插入模式，在文件末尾添加如下代码：
      5. 按Esc退出到命令模式，输入 :w 保存
      6. 输入 :source .vimrc 即可看到新的显示效果（或者退出vim再次进入也可），如下图所示：
      7 vim的默认主题设置
         + 默认主题
            - ```shell
                  18 colorscheme default
              ```
         + 其他主题
            - 查询
               * ```shell
                     ls /usr/share/vim/vim74/colors/
                 ```
               * ```shell
                    是vim的默认主题default，如果想使用其他主题，将上述代码片第18行的 colorscheme default 改成对应的主题即可，比如可以改成 
                 ```

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

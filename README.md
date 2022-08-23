# dotfiles

我的一些终端配置文件

# 结构

```
.
├── tmux                                          # Tmux 配置文件夹
│   └── tmux.conf                                 # Tmux 配置文件
└── nvim                                          # NeoVim 配置文件夹
    ├── init.lua                                  # NeoVim 配置启动文件
    ├── lua                                       # NeoVim 样式配置文件与插件导入文件所在文件夹
    │   ├── base.lua                              # NeoVim 基础配置文件
    │   ├── highlights.lua                        # NeoVim 高亮配置文件
    │   ├── macos.lua                             # NeoVim 在 macOS 下的适配配置文件
    │   ├── maps.lua                              # NeoVim 自定义快捷键配置文件
    │   └── plugins.lua                           # NeoVim 插件导入文件
    └── after 
        └── plugin                                # NeoVim 插件配置文件夹
```
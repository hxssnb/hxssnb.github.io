## 配置fish
* 设置默认终端为[Tilix](https://gnunn1.github.io/tilix-web/)
* 设置默认shell为[fish](https://www.wanweibaike.net/wiki-Fish) 并安装[Oh My Fish](https://github.com.cnpmjs.org/oh-my-fish/oh-my-fish)设置主题为[pie](https://github.com/grissius/theme-pie)

```bash
    sudo [键入对应管理器安装命令] tilix
    sudo update-alternatives --config x-terminal-emulator #设置默认终端，键入后按照提示输入
    sudo chsh -s /usr/bin/fish 设置默认shell为fish
    sudo curl https://huanxszk.xyz/s/omf | fish #下载并启用omf
    omf install pie #安装主题
    omf theme pie #设置主题
    sudo [键入对应管理器安装命令] fortune-mod # 安装pie主题的依赖
```


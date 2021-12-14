# zsh-config
我的 zsh 配置，zimfw 的默认安装配置几乎是开箱即用了，我就只是换了个主题，去掉了几个用不到的插件，加了两个我常用的插件，还有几个alias。    

## 我使用的插件及主题

- 几个[zimfw官方的插件](https://zimfw.sh/docs/modules/)：environment、input、utility、completion；
- [zsh-completions](https://github.com/zsh-users/zsh-completions)；
- [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)；
- [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)；
- [zsh-history-substring-search](https://github.com/zsh-users/zsh-history-substring-search)；    
*以上都是 zimfw 默认装的*    
- [powerlevel10k主题](https://github.com/romkatv/powerlevel10k)；
- 两个 ohmyzsh 仓库里的插件，[vi-mode](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/vi-mode) 和 [sudo](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/sudo)。


## 安装

按照[官方教程](https://github.com/zimfw/zimfw#installation)安装成功后，将本仓库里面的 `.zshrc` 和 `.zimrc` 复制到用户主目录覆盖掉原来的文件，再运行一次 `zimfw install` 应该就可以了。    

*若是从 ohmyzsh 或 zinit 迁移过来的，需要注意，OMZ 和 zinit 默认历史命令是存放在 `.zsh_hsitory` 文件里面的，而 zimfw 是存放在 `.zhsitory` 文件里面，若想保留历史记录，记得把 `.zsh_hsitory` 重命名成 `.zhistory`*    

若想另外安装插件，只需在 `.zimfw` 文件中加一行 zmodule 命令，具体方法可参考[官方教程](https://github.com/zimfw/zimfw#zmodule)
和[如何安装 OMZ 插件](https://github.com/zimfw/zimfw/issues/380#issuecomment-600369861)

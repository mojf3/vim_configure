# vim configure
.vimrc

# vim-plug 插件管理工具
## install

curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

vim

:PlugStatus

:PlugInstall  

# coc.nvim 智能补全插件
## 先安装nodejs
curl -sL install-node.now.sh/lts | bash   

vim

:CocInfo

## for python 自动补全
:CocInstall coc-pyright 

:CocList extensions

# NERDTree 目录树插件

# leaderF 模糊查找插件

# auto-pairs 自动补全括号插件

# vim-airline 底部状态增强/美化插件； vim-airline-themes 主题插件

# NerdCommenter # 方便多行注释的插件






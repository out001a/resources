* [Vim 8 for CentOS Linux 7](http://www.karan.org/blog/2016/11/05/vim-8-for-centos-linux-7/)
  - `cd /etc/yum.repos.d/`
  - `wget https://copr.fedorainfracloud.org/coprs/mcepl/vim8/repo/epel-7/mcepl-vim8-epel-7.repo`
  - `rpm --import https://copr-be.cloud.fedoraproject.org/results/mcepl/vim8/pubkey.gpg`
  - `yum update` or `yum install vim-enhanced`
  - run `rpm -q vim-enhanced` to check if updated
* [SpaceVim](https://spacevim.org/) a Modular configuration, a bundle of custom settings and plugins for Vim, here we call them layers, each layer has different plugins and config, users just need to select the layers they need.
* [spf13](http://vim.spf13.com/) a distribution of vim plugins and resources for Vim, GVim and MacVim.

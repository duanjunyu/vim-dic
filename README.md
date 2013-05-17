这个只是我人个习惯的Ubuntu开发环境配置
1、Ubuntu10.10默认只有vi，用起来不是很方便，最好装个全功能版本的vim
所以第一步最好还是：sudo apt-get install vim
2、配置vim：
把vim.tar.gz解压到~/下面：tar -xzvf vim.tar.gz -C ~/
cp .vimrc ~/
cd ~/.vim
sudo apt-get install ctags
sudo apt-get install cscope
3、安装sdcv词典：
先要安装sdcv:sudo apt-get install sdcv

tar -xzvf stardict.tgz -C /usr/share
事实上应该是在/usr/share/stardict/dic/下面放词典，我把相关的文件都打包在stardict.tgz中，就直接按照上述步骤即可。
4、适当的开发界面调整
1)终端中可能要用到多个标签，所以我还是比较喜欢用系统中“清爽”的那个主题，主要是能够清楚地看到当前标签。
2)shell终端的首选项也是要改一下的，在“首选项”->“颜色”->“内置方案”中，“黑底绿色”是比较令人舒服的。

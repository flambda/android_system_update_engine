# android_system_update_engine
本项目是记录Android编译源码过程遇到的问题与解决方案
### 1 repo和环境
#### 1.1 repo
本项目以MoKee<https://github.com/MoKee>为例
 $ mkir ~/bin
 $ PATH=~/bin:$PATH
#####--------------------------
 $ curl https://download.mokeedev.com/git-repo-downloads/repo > ~/bin/repo
 $ chmod a+x ~/bin/repo
#####-------------------------
 $ repo init -u https://github.com/MoKee/android -b mkn-mr1
 $ repo sync
参考<https://blog.csdn.net/fmc088/article/details/80678955>

repo脚本见dload.sh

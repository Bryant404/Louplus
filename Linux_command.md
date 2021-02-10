#Github中创建名为Louplus仓库，将仓库克隆至本地
git clone https://github.com/Bryant404/Louplus.git

#进入本地仓库目录
cd Louplus

#本地仓库目录中下载获取脑图
wget https://labfile.oss.aliyuncs.com/courses/1330/linux.png
wget https://labfile.oss.aliyuncs.com/courses/1330/python1.png
wget https://labfile.oss.aliyuncs.com/courses/1330/python2.png
wget https://labfile.oss.aliyuncs.com/courses/1330/git.png

#添加本地仓库内所有文件
git add --all
git status

#提交文件至本地仓库，注释为brain map
git commit -m "Brain map"

#本地仓库链接远程Louplus仓库，提交文件至远程仓库
git remote add oragin https://github.com/Bryant404/Louplus.git
git push oragin master

#Github刷新确认文件


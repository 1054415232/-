打开github    用网页https://github.com/
进入后点击注册，已有的就直接登录，注册时会用到自己的邮箱，目的是为了在提交命令时的一个认证。
登录成功后新建一个lesson,然后保存，在git的命令行中输入，git version 回车 查看当前版本号
然后接着git clone http://github/用户名      /lesson 把github上的文件克隆到本地，输入pwd显示当前克隆后文件的位置。
接着输入dir 显示当前文件里的具体文档，这里会显示lesson，输入cd lesson可以看到界面上显示有一readme的文件，自己从Windows 的用户里可以看到这个文件。
然后输入git status 显示当前文件的状态，输入：git config --global user.email 1111111111@qq.com（自己注册时 的邮箱）git config --global user.name"用户名"（自己的用户名）把要上传或者是修改的readme放到lesson 文件夹下面。
输入 git add *（这里是添加所以本地lesson里的文件）
输入git commit -a -m "update"输入git push origin master输入git pull
这时去浏览器刷新就可以看见你上传的文件了。
删除这些文件，只需在本地文件夹删除，然后在按以上步骤执行一次就可以了。

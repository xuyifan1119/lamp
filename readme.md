1.git安装


2.git的使用
	1)指定一个目录座位git工作区的仓库
	git init    git 初始化
		master

	2) 把工作区里面的文件 存放到暂存区 
		git add .
			. 代表 修改的文件和新创建的文件

	3)把暂存区里面的文件 提交到本地git仓库中
	git commit -m '注释的信息'

	4)建立本地和远程的链接
	git remote add origin 远程的地址

	5)把本地的仓库信息推到远程仓库上去
	git push origin master


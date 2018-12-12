### 创建版本库

1. 初始化工作区 			git init
2. 添加到暂存区			git add readme.txt
3. 提交到当前分支		git commit -m "comment"

### 版本回退

1. 查看改动状态				git status
2. 查看改动细节				git diff readme.txt
3. 查看改动日志				git log
4. 查看简化日志				git log --pretty=oneline
5. 回退上个版本				git reset --hard HEAD^
6. 回退具体版本				git reset --hard 1094a
7. 查看历史命令				git reflog
8. 撤销工作区修改			git checkout -- readme.txt
9. 撤销暂存区修改			git reset HEAD readme.txt

### 远程仓库

1. 创建SSH Key				ssh-keygen -t rsa -C "vlsi2700@gmail.com"

2. 存放位置					user/.ssh/{id_rsa, id_rsa.pub}

3. 关联本地仓库				git remote add origin git@github.com:RV1101/init.git

4. 推送本地仓库				git push (-u) origin master

5. 克隆远程仓库				git clone git@github.com:RV1101/init.git

   :happy:


$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
$$











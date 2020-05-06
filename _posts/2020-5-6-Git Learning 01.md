## Git Learning 01
1. Git download：

2. Git基本工作流程
    - 工作区(Working Directory)->暂存区->Git Repository
    
3. 初始化一个新的Git仓库
    - 创建文件夹: (1.快捷键：右键->W->F or 2. 右键->Git bash->输入:mkdir+文件名)
    - 在文件内初始化git(创建git仓库): 右键->Git bash->输入:cd+文件名; 右键->Git bash->输入:git init; (生成的git文件为隐藏文件)

4. 向仓库添加文件
    - 创建文件:右键->Git bash->输入:touch 文件名.java
    - 查看状态(选择执行):右键->Git bash->输入:git status
    - 添加到暂存区:右键->Git bash->输入:git add 文件名.java
    - 查看状态(选择执行):右键->Git bash->输入:git status
    - 将文件从暂存区添加到仓库右键->Git bash->输入:git commit -m '描述'
    - 查看状态(选择执行):右键->Git bash->输入:git status
    

5. 修改仓库文件
    - 修改文件:1.右键->Git bash->输入:vi 文件名.java or 2.手动打开文件并修改
    - 预览文件(选择执行)：右键->Git bash->输入:cat 文件名.java
    - 添加到暂存区:右键->Git bash->输入:git add 文件名.java
    - 将文件从暂存区添加到仓库右键->Git bash->输入:git commit -m '描述'
    

5. 删除仓库文件
    - 删除文件: delete or 右键->Git bash->输入:rm -rf 文件名.java
    - 从暂存区删除:右键->Git bash->输入:git rm 文件名.java  (特别注意此处不同)
    - 将文件从暂存区添加到仓库右键->Git bash->输入:git commit -m '描述'
    
6. Git管理远程仓库
    - 验证初始化: 右键->Git bash->输入:git config --list
    - Git克隆操作: 右键->Git bash->输入:git clone 仓库地址
    - 往文件夹中添加文件(特别注意是否需要cd)
    - 将新添文件添加到暂存区:右键->Git bash->输入:git add 文件名.java
    - 将文件从暂存区添加到仓库:右键->Git bash->输入:git commit -m '描述'
    - 将新添文件上传到远程仓库:右键->Git bash->输入:git push
    
7. Github搭建个人网站
    - 创建个人站点：新建仓库(注：仓库名必须是【用户名.github.io】)
    - 在仓库下新建index.html的文件即可
    - 注意点：1.github pages 仅支持静态网页
             2.仓库里面只能是.html文件
    - 个人网站:https://dovevee.github.io
    
8. Github搭建项目网站
    - 进入项目主页，点击setting
    - 在setting页面，点击【Launch automatic page generator】来自动生成主题页面
    - 新建站点基础信息设置
    - 选择主题
    - 生成网页
    
    


    

# git 基本使用

## 本地仓库
创建目录,在目录中初始化git仓库
命令
```
git init
// 通过编辑工具添加文件
git add *
git commit -m "init"
```

## 远程仓库
登录github等托管平台,新建仓库
new repo

## 本地仓库推送到服务器端
首次推送到服务器端,需要先把本地仓库与服务器端仓库关联
`git remote add origin git@github.com:your_user_name/your_repo_name.git`

以后使用只需要推送修改到服务器端
// master 是分支名称, 其中 master 是默认的主分支名称
```
git push -u origin master
```


## 本地代码,文档修改
首次提交到远程仓库之后,就是修改同步的操作

通过工具修改文本或文件
然后执行 仓库提交命令

添加
```
// 添加指定的
git add filename
// 添加所有
git add *
```

修改
```
git add *
git commit -m ""
```

把修改同步到服务器命令

```
git push -u origin master
```


## 克隆命令

`git clone git@github.com:billoway/git_sz.git`
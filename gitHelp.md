# git的常用命令使用

## git与远程仓库关联

1.命令关联

```git
git remote add origin git@github.com:yourName/repositoryname.git
git remote add origin https://github.com/yourName/repositoryname.git

```

yourName是用户名，repositoryname是仓库名字

![image-20230723122900973](D:\img\typroaImg\image-20230723122900973.png)

2.查看是否成功关联

```git
git remote -v
```

![image-20230723123052405](D:\img\typroaImg\image-20230723123052405.png)

3.从远程拉项目

```git
git pull origin "分支名"
例如：git pull origin "main"
```

![image-20230723123810743](D:\img\typroaImg\image-20230723123810743.png)

4.查看状况

```git
git status
```

5.添加add

```git
 git add README.md
```

6.提交commit

```git

```


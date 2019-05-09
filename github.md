## 1.起步

### 1.1.注册

GitHub：https://github.com/

![1557377415148](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557377415148.png)

必须踏踏实实做好注册，不能随便，如果已有账号，就进去登录页。

### 1.2.登陆

#### 1.2.1.点击 `Sign in` 

![1557377498611](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557377498611.png)

#### 1.2.2.登陆页

![1557377529754](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557377529754.png)

![1557377608430](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557377608430.png)

所有的输入好了之后，点击 `Sign in` 进去



## 2.创建 GitHub 仓库

### 2.1.点击 Start a project

![1557377722624](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557377722624.png)

![1557377785545](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557377785545.png)

起名字必须与仓库里的那些文件名不一致

![1557377832175](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557377832175.png)

![1557377843545](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557377843545.png)

### 2.2.点击 `Create repository` 进去

![1557377969571](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557377969571.png)

## 3.将本地文件提交到 GitHub 上

![1557378043670](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557378043670.png)

如果电脑没有安装git，就去git官网下载。

安装好了之后，在tet文件中右键选择 `Git Bash` Here

![1557378211992](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557378211992.png)

显示 `发送请求时出错。` 不要担心

Username for 'https://github.com':  这个就是GitHub的账号

Password for 'https://hdhdhdmmd123@github.com': 这个就是GitHub的密码

![1557378307482](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557378307482.png)

![1557378328752](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557378328752.png)

说明提交到GitHub成功了

然后回到GitHub官网看一看

![1557378375663](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557378375663.png)

![1557378389194](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557378389194.png)

成功了



## 4.文件有改动并更新到 GitHub 上

### 更新代码

#### 第一步：查看当前的git仓库状态，可以使用git status

```
git status
```

### 第二步：更新全部

```
git add *
```

### 第三步：接着输入git commit -m "更新说明"

```
git commit -m "更新说明"
```

### 第四步：先git pull,拉取当前分支最新代码

```
git pull
```

### 第五步：push到远程master分支上

```
git push origin master
```

![1557378942151](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557378942151.png)

![1557378958245](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557378958245.png)

成功了
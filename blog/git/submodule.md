# submodule 

使用git submodule 进行简单的子模块管理

### 常用命令

```$xslt
git clone <repository> --recursive 递归的方式克隆整个项目

git submodule add <repository> <path> 添加子模块

git submodule init 初始化子模块

git submodule update 更新子模块

git submodule foreach git pull 拉取所有子模块
```

### 步骤

```$xslt
$ git clone {path}

$ git add submodule {path}

```


### IDE集成git开发

#### ssh免密登录

```html
cd ~/.ssh 检查是否存在ssh key
生成密钥：ssh-keygen -t rsa -C "jianhou.xie@northking.net"
```

#### eclipse篇

##### 工程初始化本地库

```
选中工程右键-->Team-->share project
```

##### 忽略eclipse特定文件

```java
.classpath
.project
.settings
```

##### 远程克隆工程到本地

```html
import导入工程
git-->projects from git-->Clone URI
导入工程选最后一项
转换工程：configure-->convert to Maven Project
```

#### idea篇

##### 本地工程初始化

```html
工具栏VCS--->Import into Version Control-->Create Git repository
后续都是图形化界面操作 
```

##### 把工程从远程仓库clone到本地

```
第一种方式：工具栏VCS--->Checkout from Version Control-->Git
第二种方式：File-->New-->project from Version Control-->Git
```

#### gitflow工作流

#### gitlab

```html
git仓库管理系统
```




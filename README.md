如何创建新站点

## 方法一

1. 创建一个新的repository
  
2. 上传index.html文件
  
3. 在repository中依次点击setting，pages
  
4. 在Build and deployment栏目中source选择deploy from branch，下面的Branch栏选择main和root，点击save
  
5. 等待一会，成功后网站的名称应该是https://ustcflyer-japan.github.io/<repository名>
  

## 方法二

直接在某个reposity里上传新的html文件，文件名不必是index.html。等待一会成功后网站的名称应该是https://ustcflyer-japan.github.io/<repository名>/<html文件名>

## 注

每个人的创建的部分尽量自己放到一个repository里，这样比较好管理，每个人在一个较大的项目中需要创建另外的网页时可以使用第二种方法

## 图片引用格式

如果想要在https://ustcflyer-japan.github.io/\<repository名>或者https://ustcflyer-japan.github.io/<repository名>/<html文件名>中添加图片，请在repository中创建images文件夹并把图片存放于此，需要在html文件中引用时采用如下格式

\<img src="https://ustcflyer-japan.github.io/<repository名>/images/<图片名.png>" alt="Description" width="宽度" height="高度">

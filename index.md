# git相关
## 常用指令
## git的三部分
# Elastic Search
## 为什么要用ES
# MongoDB
nin：不在其中
GET _search
# 计算机名词
e.g. : 比如说
PTAL means "Please Take A Look"
# 常用linux命令
## vim


# java MVC
最外层是view也就是页面，Controller即ActionServlet小服务程序或服务连接器control是
一些控制后台和页面访问的类，因为大部分人在会再增加一层service层来提供更为方便的>应用，model其实是dao层，

JSP+Controller—Service—DAO—Hibernate。

后台接收到前台传来的参数，分给不同的service层方法进行实现，service层方法再根据业
务需求调用dao层的方法访问数据库获取数据，分成service和dao两层可以使得一些方法不>用重复写，提高代码复用性。某一个程序的有些业务流程需要连接数据库，有些不需要与数
据库打交道而直接是一些业务处理，这样就需要我们整合起来到service中去，这样可以起>到一个更好的开发与维护的作用
modle层就是对应的数据库表的实体类。Dao层是使用了Hibernate连接数据库、操作数据库>（增删改查）。Service层：引用对应的Dao数据库操作，在这里可以编写自己需要的代码（
比如简单的判断）。Action层：引用对应的Service层，在这里结合Struts的配置文件，跳>转到指定的页面，当然也能接受页面传递的请求数据，也可以做些计算处理。
Action是管理业务（Service）调度和管理跳转的。
      Service是管理具体的功能的。
      Action只负责管理，而Service负责实施。
      DAO只完成增删改查，
      
# SSH 需要在server上使用Commend line时用
远程登录
登录到自己想去的一个server
kinit -f（请求密码）
rlogin -f -l www server名字


# rxJava
Completable不发射数据，只是返回是否成功

# elastic search

GET _search
{
  "query": {
    "match": {
      
    }
  }
}


# linux

Control A 回到一行的前面 e 回到一行的后面

# playbook

# Spring batch

# git
Git stash
Git stash pop
Git rebase master
git remote -v

git commit 上传到本地仓库

在新建一个branch的时候没有改过的记录，所以不要amend
git rebase -i 用于把一个分支的修改合并到当前分支。

$ git push origin master 将本地的master分支推送到origin主机的master分支。如果master不存在，则会被新建。

# jenkins
# RPC:远程过程调用


以前程序只能调用自己电脑上的进程，能不能调用其他机器上的进程呢？于是就程序员就把IPC扩展到网络上，这就是RPC（远程过程调用）了。现在不仅单机上的进程可以相互通信，多机
器中的进程也可以相互通信了

# java 编程规则
编程：
注意注释
不要空行
有些地方需要空行

大小写
缩进：indentation
stream().map():Stream的迭代是隐含在对Stream的各种操作中，例如map()
对于Stream中包含的元素使用给定的转换函数进行转换操作

When writing method parameter with a line break, the method should be placed independent block like this
当一个方法的参数重有一个参数是用了.()
这个方法应该重启一行再写

## computeIfPresent

computeIfPresent()
该方法签名为V computeIfPresent
(K key, BiFunction<? super K,? super V,? extends V> remappingFunction)
只有在当前Map中存在key值的映射且非null时
才调用remappingFunction，如果remappingFunction执行结果为null，则删除key的映射，否>则使用该结果替换key原来的映射．
所以中间有一步是查找

## 集合是不可被修改的 ImmutableList, stream.collect(toImmutableList())

## Dependency Injection

当某个角色(可能是一个Java实例，调用者)需要另一个角色(另一个Java实例，被调用者)的协
助时，在 传统的程序设计过程中，通常由调用者来创建被调用者的实例。但在Spring里，创>建被调用者的工作不再由调用者来完成，因此称为控制反转;创建被调用者 实例的工作通常由
Spring容器来完成，然后注入调用者，因此也称为依赖注入。

调用者无须自己定位工厂，程序运行到需要被调用者时，系统自动提供被调用者实例。事实上
，调用者和被调用者都处于Spring的管理下，二者之间的依赖关系由Spring提供。

## @JsonProperty 
此注解用于属性上，作用是把该属性的名称序列化为另外一个名称，如把trueName属性序列化为name，如果不加就直接用原来的名字。命名规则？
contents不加是因为不用-链接符号？

## server(real beta local)
the server in intelli is local
And should use http://localhost:8080/internal/docs/ to check the new API
But use the some mongoldb with others
So the mongdb can be changed by everyone
One port only can use one application(one server)

在测试的时候自己电脑上会建立一个虚拟的mongodb  AbstractMongoTest

## URL for study
https://projectlombok.org/features/Builder
http://reactivex.io/documentation/single.html
https://brew.sh/
https://docs.spring.io/spring-batch/trunk/reference/html/readersAndWriters.html
https://docs.spring.io/spring-batch/trunk/reference/html/configureStep.html#stepExecutionListener
https://git-scm.com/book/zh/v2
https://git-scm.com/book/en/v2/Git-Branching-Rebasing
http://reactivex.io/documentation/single.html
https://stackoverflow.com/questions/2221658/whats-the-difference-between-head-and-head-in-git
http://www.paulboxley.com/blog/2011/06/git-caret-and-tilde


## 
## 


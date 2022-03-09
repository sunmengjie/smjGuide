# maven
## 1.文档
[官方文档](https://maven.apache.org/guides/index.html)

[中文文档](http://ifeve.com/maven-index-2/) 有点垃圾
## 2.常用命令
mvn --version
## 3.生命周期(Lifecycle) and Phases(阶段) 
有三个内置的构建生命周期：
* default ->  处理项目部署
* clean   ->  处理项目清理
* clean   ->  处理项目网站的创建
每个构建生命周期都由不同的构建阶段列表定义，其中构建阶段代表生命周期中的一个阶段。
### default（lifecycle）
例如default生命周期由一下phases（阶段）组成
* validate 验证项目是正确的，所有必要的信息是可用的
* compile 编译项目的源代码
* test 使用合适的单元测试框架测试编译后的源代码。这些测试不应要求打包或部署代码
* package 获取已编译的代码，并将其打包成可分发的格式，例如 JAR
* verify 对集成测试结果进行检查，以确保符合质量标准
* install -将包安装到本地存储库中，用作本地其他项目的依赖项
* deploy 在构建环境中完成，将最终包复制到远程存储库，以便与其他开发人员和项目共享。
## 4.插件
个人理解 maven定义了一套生命周期和phases（阶段）的接口，具体实现由各个插件实现。




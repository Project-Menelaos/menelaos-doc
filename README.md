# 墨涅拉俄斯计划

通过一种类 C 语言（C 田，Restricted C+），实现：

 * 实时监测代码修改，同步编译到 C 语言工程
 * 完善的跨平台跨 IDE 预处理机制
 * 通过预处理机制实现单元测试自动生成
 * 自动生成接口文档
 * 自动生成函数内和函数间调用框图
 * 自动完成 GUI 测试及截图
 * 根据模板自动生成实验报告

 **老子受不了比代码还神烦的实验报告！！！老子要自动化！！！自动化！！！**
 
## 技术栈（暂定）

### 语言编译器
 * [Flex](https://www.gnu.org/software/flex/)
 * [GNU Bison](https://www.gnu.org/software/bison/)

### 项目构建
 * [Gulp](http://gulpjs.com/)
 * [Mustache](https://mustache.github.io)
 
### 流程图
 * [Mermaid](https://knsv.github.io/mermaid/index.html)
 * [GNU cflow](https://www.gnu.org/software/cflow/)

### 测试
 * [cmocka](https://cmocka.org/)
 * ~~[Robot Framework](http://robotframework.org/)~~

### 文档生成
 * [Pandoc](http://pandoc.org/)

## 关于计划的名字

[墨涅拉俄斯（Μενέλαος，Menelaos）](https://zh.wikipedia.org/wiki/%E5%A2%A8%E6%B6%85%E6%8B%89%E4%BF%84%E6%96%AF)是希腊神话中斯巴达的国王，[海伦（Ἑλένη, Helénē，Helen）](https://zh.wikipedia.org/wiki/%E6%B5%B7%E4%BC%A6_%28%E7%A5%9E%E8%AF%9D%29)的丈夫。

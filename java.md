
### 必须遵守
1. 类名称第一个字母大写，多个单词的，首字母大写
```
User   ApplicationContext
```
2. 方法名称，实例对象采用驼峰命名法
```
addUser()
```
3. 静态常量采用大写字母加下划线方式 
```
String BASE_URL = "http://www.xx.com"
```
4. 包名采用小写方式
```
com.xiaojiuwo.weixin
```
5. 如果一个方法(method, function)代码行数大于60 行，请重构。 要求： 98% 方法代码行数小于60行，99%
   的方法代码行数小于120 行，100%代码方法行数小于300行。
```
如某些方法确实必须违反此条目，请具体说明理由
```
 


### 建议采用 

1. 类名包名采用英文单词，命名要简单明了，不要过长。
2. 缩进采用空格而不是tab，4个空格
3. 方法名称和类名称上写注释。
4. 主要业务逻辑方法都要有单元测试。
5. 有超过2处使用的常量不要 hard coding 
6. 能根据不同环境生成对应的jar, 或者war包,而不是每次生成包的时候需要手工改代码。
7. 代码换行长度等可以通过IDE制定模板，统一标准。




## 类和继承
写一个Person类，要有name，age属性，要有一个introduce方法， introduce方法返回一个字符串形如：
`My name is Tom. I am 21 years old.`

再写一个Student类继承Person类，除了name，age属性，还要有klass（表示班级，因为 class 是关键字）属性。也有一个introduce方法， introduce方法返回一个字符串形如：
`My name is Tom. I am 21 years old. I am a Student. I am at Class 2.`

## 参考资料

1. [Javascript基础](http://codefordream.com/courses/js_basic/sections)
2. [Javascript初级训练营](http://codefordream.com/courses/js_learning_camps/sections)
3. [ECMAScript 6 入门](http://es6.ruanyifeng.com/)
4. [npm 下载安装](https://github.com/npm/npm)
5. [node 下载安装](https://github.com/creationix/nvm)
6. [jasmine用法](http://jasmine.github.io/2.4/introduction.html)
7. [Git 参考手册](http://gitref.org/zh/index.html)


## 答题流程
- 请用户仔细阅读题目要求和题目描述

- 在命令行中使用以下命令在用户本地任意目录下clone此题目库
```
git clone repo_of_this_template
```
NOTE：如果提示git命令未找到请先阅读参考资料
- 用任意编辑器打开clone下来的文件夹，内部会存在两个文件夹
```
spec  //测试文件夹
src   //源文件
```
`请在src文件下的person.js和student.js文件内实现`

- 完成函数后，使用以下命令设置github远程仓库地址 (my_url代表你自己的新的github地址)
```
 git remote set-url origin my_url
```
- 请使用**git提交(commit)**并**上传(push)**，之后将此github仓库地址(用户自建的) eg:（https://github.com/username/repo） 填入到提交地址一栏 
- 获取分支
- 提交
- 等待结果


## 如何本地运行

首先初次下载完需要安装依赖：

```
  npm install
```

然后才能执行测试：

```
  npm test
```

可以通过测试来检测本地代码是否完成作业要求，测试通过即可提交到github，把git库地址填到答题页面，并提交表单。

# 编译原理大作业

# 词法分析部分

## 环境概览

> 开发环境：Jetbrains Intelij Idea 

>开发语言：Java（后端） 和 JavaScript（前端）

>Java版本：JDK1.8 

>Tomcat版本：tomcat 9

## 作业要求

> 分析用户输入的正则表达式（包含基本运算），对操作进行理解 
>转换至NFA 
>转换至DFA 
>最小化DFA 
>利用最小DFA分析输入字符串是否匹配
> 交互操作和可视化（可选）

## 最终实现情况

> 全部实现

## 运行截图

  ![]( https://github.com/qianqianjun/CompilationPrinciple/raw/master/%E8%AF%8D%E6%B3%95%E5%88%86%E6%9E%90%E9%83%A8%E5%88%86(%E5%90%AB%E5%8A%A8%E6%80%81%E4%BA%A4%E4%BA%92%E9%A1%B5%E9%9D%A2)/web/images/run.png)

## 使用方法

> 网页加载完毕后在第一个输入框中输入一个正则表达式（只包含 * | 和 . 运算符） 点击 build 会生成一个DFA和NFA的图片
> 之后在第二个输入框中可以输入一个字符串，点击judge即可判断该正则表达式是否可以匹配这个字符串，匹配的时候会有两秒间隔的动画演示，耐心等待程序响应，匹配过程中可以直观的看到当前字符所处的DFA的状态，匹配成功与否程序都会弹窗提示结果。

## 预览网站：
演示地址：
[从正则表达式到最小化DFA并且判断是否匹配][1]

# 语法分析部分

## 环境概览

> 开发环境：Jetbrains Pycharm 

>开发语言：Python

>Python版本：3.6

## 作业要求

> 1. LL1 文法分析方法
> 2. LR0文法分析方法
> 3. SLR1文法分析方法
> 4. LR1文法分析方法
> 5. LALR文法分析方法
> 6. 基本要求：构建各个文法分析方法的分析表，输入要分析的字符串，给出分析过程和分析结果。

## 最终完成情况

> 全部完成

### 疑难解答

如有需要，欢迎联系我
高谦，1905946527@qq.com

  [1]: http://www.buctsnc.club:8080/dfa

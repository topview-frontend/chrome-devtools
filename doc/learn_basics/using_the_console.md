### Note：以后写的都是一些瘦身版的，重点翻译出来就行了

## Using the Console

Utilizing the console gives you the ability to:

Log diagnostic information to help debug your web page or application.
Enter commands that interact with the document and the Chrome DevTools.
You also may evaluate normal JavaScript expressions. This documentation provides an overview and common uses of the console. 
You may browse the Console API and Command Line API reference material to understand more functionality.

用了`console`能让你：
* 打印一些信息来帮助你调试你的web页面或者应用；
* 输入一些命令来；
* 你也可以执行一些 JavaScript 表达式。这个文档提供大致的目录和一些常用的用法；
* 你可以查阅一些 `Console API` 和 `Command Line API` 相关的资料来

Basic Operation
Opening the Console
The JavaScript Console is available in two places. The Console panel provides primary access.
It also is available from within any other panel by using the Drawer. To open the Console tab, do one of the following:

### 基础操作

#### 打开控制台 `Console`
JavaScript控制台有两个地方可以打开它。

* 可以用快捷键 `Command + Option + J (Mac)` 或者 `Control + Shift + J (Windows/Linux)`

#### 清除console历史

Right-click or Ctrl-click anywhere in the Console and choose Clear Console from the context menu that appears.

可以用下列其中一个方法来清除console历史
* 输入`clear()`命令
* 输入`console.clear()`
* 用快捷键 `Cmd + K, ^ + L (Mac)` `Ctrl + L (Windows and Linux)`

#### Message Stacking

#### Frame Selection

#### Using the Console API
The Console API is collection of methods provided by the global `console` object defined by DevTools. One of the API's main purposes is to log information to the console while your application is running.
You can also group output visually in the console to reduce visual clutter.

##1 RF框架安装##
###1.1 安装JDK###
从oracle官网下载JDK1.6版本，并设置环境变量。
### 1.2 安装Python ###
从[http://www.python.org/download/](http://www.python.org/download/)下载2.7.5版本并安装。
### 1.3 安装setuptools ###
从[https://pypi.python.org/pypi/setuptools/0.9.8](https://pypi.python.org/pypi/setuptools/0.9.8)下载ez_setup.py；然后执行 python ez_setup.py进行安装。
### 1.4 安装pip ###
在%Python_Home%Scripts下执行easy_install pip进行安装。
### 1.5 安装RobotFramework ###
    pip install robotframework
### 1.6 安装wxPython ###
从[http://wxpython.org/download.php#stable](http://wxpython.org/download.php#stable)下载对应版本，进行安装。
### 1.7 安装RIDE ###
从[https://code.google.com/p/robotframework-ride/downloads/list](https://code.google.com/p/robotframework-ride/downloads/list)下载RIDE的合适版本，进行安装。
### 1.8 安装常用测试库 ###
    pip install robotframework-httplibrary    
    pip install robotframework-selenium2library
### 1.9 Selenium2Library IE环境配置 ###
1、IE选项设置的安全页中，4个区域的启用保护模式的勾选都去掉（或都勾上）；  
2、IE选项设置的连接页中，局域网设置里的代理服务器设置，不能勾选。如果需要配置代理，请使用上面的pac自动配置脚本来使用代理；   
3、IE页面的显示比例要为100%；  
4、下载IEDriverServer.exe文件，放到环境变量path路径的目录里或把他所在的目录加到path环境变量中。下载地址为：[http://code.google.com/p/selenium/downloads/list](http://code.google.com/p/selenium/downloads/list)；
## 2 RF优缺点 ##
### 2.1 RF优点 ###
- 行为驱动；
- 支持自定义关键字重用和嵌套；
- 支持变量；
- 支持创建基于数据驱动的测试用例；
- 结果报告和日志采用HTML格式，易于阅读；
- 提供标签以分类和选择将被执行的测试用例；
- 平台、应用无关；
- 功能全面，支持WEB测试（Selenium）、Java GUI 测试，启动线程、终端、SSH等；
- 易于扩展，用户可以自定义的基于Python或者Java的测试库；
2.2 RF缺点
不够灵活

RF标准测试库


### 专用名词 ###

> Test Data ：测试数据  
Test Suite ：测试套件  
test suite directory 测试套件目录  
test library ：测试库  
escape ： 转义  
separater ：分隔符  
output ：输出 （这里指 Report 和Log）  
space ：空格字符  
whitespace ：占位字符 （空格，换行，制表符）  
preamble：报文头  



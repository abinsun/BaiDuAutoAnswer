# 百度知道自动答题 稳定版

使用python的selenium模块操控浏览器实现自动答题，通过搜索题目得到答案并且填入。
程序开始时，当出现[sign in and input anything like ‘ok’ ]提示时需手动登入（只需登入这一次），然后在程序窗口输入【ok】并回车，程序启动。
本程序侧重稳定，在循环开始时先删除异常窗口，以保证自动化的继续。
在2019年10月7日测试中挂一晚正常。
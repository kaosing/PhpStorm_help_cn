# 报告问题

 PhpStorm 提供各种方式来报告问题并寻求帮助。在这个部分包含：

* 查找PhpStorm日志
* 配置PhpStorm日志
* 报告问题
* 分享反馈
* 寻求帮助

> ### 查找 PhpStorm 日志
>
> 在某些情况下，你需要将PhpStorm日志附加到支持服务的电子邮件中。你可以轻松找到日志文件，如下所述：
>
> 在主菜单上，选择 **Help \| Show Log in ....**

> ### 配置PhpStorm日志
>
> 为了避免编辑`log.xml`文件本身，PhpStorm 建议使用一个方便的对话框来更改类别的日志记录级别。此文件位于PhpStorm安装的 **bin** 目录下。
>
> 1. 在主菜单上，选择 **Help \| Debug Log Settings....**
> 2. 在打开的对话框中，输入日志类别名称，并用换行分隔
>
> 编辑`log.xml`时，请注意以下几点：
>
> * 建议不要更改`log.xml`，因为它它有时会引起补丁出现问题
> * 编辑`log.xml`应与支持服务紧密联系。原因是用户可能不知道要指定的模块名称，而支持服务可以为更好的诊断建议模块。

> ### 报告问题 {#d899770e56}
>
> 1. 通过[https://youtrack.jetbrains.com/](https://youtrack.jetbrains.com/)打开PhpStorm跟踪系统 
>
>    如果您尚未注册，请执行此操作
>
> 2. 点击 **Create issue**
> 3. 在打开的页面上，从 **Project** 的下拉列表中选择 PhpStorm 中 
> 4. 描述您的问题，分别在 **Description** 和 **Summary** 字段中提供问题的简要概述
> 5. 如有必要，请附上屏幕截图说明您的问题
> 6. 准备好了就点击 Create issue

> ### 分享反馈 {#d899770e91}
>
> * 选择 **Help \| Submit Feedback**，将您重定向到在线反馈表单。 此表单使您能够创建特定于PhpStorm的[YouTrack](http://youtrack.jetbrains.com/)问题。 登陆页面依赖于PhpStorm版本：
>   * 对于发行版本，菜单项将打开[http://www.jetbrains.com/feedback/feedback.jsp](http://www.jetbrains.com/feedback/feedback.jsp?product=PhpStorm&build=$BUILD&timezone=$TIMEZONE&eval=$EVAL)页面
>   * 对于[EAP版本](http://confluence.jetbrains.com/display/PhpStorm/PhpStorm+Early+Access+Program)，菜单项将打开[http://confluence.jetbrains.com/display/PhpStorm/PhpStorm+Early+Access+Program](http://confluence.jetbrains.com/display/PhpStorm/PhpStorm+Early+Access+Program)页面。

> ### 寻求帮助 {#d899770e128}
>
> 要查找帮助，请执行以下操作之一：
>
> * 访问 [JetBrains Support](https://intellij-support.jetbrains.com/home)
> * 写信给支持服务。使用以下地址：
>
>   * intellij-support@jetbrains.com
>   * phpstorm-support@jetbrains.com
>
>   如有必要，请附加源代码和 [PhpStorm日志](https://www.jetbrains.com/help/phpstorm/reporting-issues.html#log)  
>   如有必要，请附上与你的问题相关的PhpStorm设置摘要：
>
>   1. 在主菜单上，选择 **Help \| Settings Summary**。将打开 **Settings Summary** 对话框。
>   2. 从 **Issue Type** 下拉列表中，选择遇到问题的子系统，可用：
>
>      * **Web Debug**
>      * **CLI Debug**
>      * **Deployment** 查看影响与远程主机交互的设置
>      * **PHPUnit** 查看影响单元测试的设置
>
>      根据您的选择，PhpStorm将显示与选定区域中的活动相关或可能影响活动的所有设置。
>
>   3. 要将摘要保存到剪贴板，请单击 **Copy**
>
> * 咨询 [PhpStorm community](https://intellij-support.jetbrains.com/hc/en-us/community/topics/200367219-PhpStorm)


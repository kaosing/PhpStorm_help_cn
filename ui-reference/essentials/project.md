# 项目

### 基础 {#d828843e10}

在PhpStorm中，无论你做什么都是基于项目来进行的。项目是代表完整软件解决方案的组织单元。它是编码辅助、批量重构、编码风格一致性等的基础。

PhpStorm 不支持直接编辑远程主机上的文件，因此如果要在PhpStorm中使用远程源，需要[下载它们并将它们放在PhpStorm项目中](https://www.jetbrains.com/help/phpstorm/creating-a-project-from-downloaded-files.html)。如果需要保持本地和远程源同步，请打开 [Options](https://www.jetbrains.com/help/phpstorm/settings-deployment-options.html) 对话框，配置 **Upload changed files automatically to the default server** 选项。

### 项目文件 {#storage}

PhpStorm中的项目是基于目录形式展现，项目目录标有![&#x9879;&#x76EE;&#x56FE;&#x6807;](https://www.jetbrains.com/help/img/idea/2018.2/project_icon.png)图标。

项目目录包含 **.idea** 目录，其中包含以下文件：

* **\*.iml** 用于描述项目结构的文件
* **workspace.xml** 包含工作区首选项
* 一系列的 **.xml** 文件，每个 **.xml** 都包含特定的配置，通过名字就能知道大概的作用： **projectCodeStyle.xml, encodings.xml, vcs.xml** 等 例如：添加了新的调试配置或者更改编码将影响两个 **.xml** 文件。当项目设置存储在版本控制系统中并由不同的团队成员修改时，这有助于避免冲突。

除了存储本地首选项的workspace.xml之外，**.idea** 目录中的所有设置文件都应置于[版本控制](https://www.jetbrains.com/help/phpstorm/enabling-version-control.html#associate_directory_with_VCS)之下。workspace.xml文件标记为[VCS忽略](https://www.jetbrains.com/help/phpstorm/configuring-version-control-options.html#configure_ignored_files)。

**.idea** 目录在[项目窗口](https://www.jetbrains.com/help/phpstorm/project-tool-window.html)的项目视图中是看不到的 。

### 项目类型 {#types}

每个项目的目录结构都包含phpstorm的 **.idea** 目录、项目文件和库。

PhpStorm 建议以下类型的项目：

* 空项目 适用于纯Web编程。此类项目的目录结构包含 **.idea** 目录、项目文件和库。 按照[从头开始创建新项目](https://www.jetbrains.com/help/phpstorm/creating-new-project-from-scratch.html)部分中的描述创建一个纯Web项目。
* 基于 _Google App Engine_ 的PHP项目。此项目类型提供基于 _Google App Engine_ 的PHP项目的基本结构，以及所有必需的文件和设置。 按照[准备开发基于Google App](https://www.jetbrains.com/help/phpstorm/preparing-to-develop-a-google-app-for-php-application.html)的PHP项目部分中的说明创建项目。
* 基于模板的项目，使用第三方框架开发web应用程序。PhpStorm创建符合所选框架要求的基本架构，文件和目录的结构。
  * 对于前端开发，可以选择[HTML5 Boilerplate](https://github.com/h5bp/html5-boilerplate)、 [Bootstrap](http://twitter.github.com/bootstrap/)、 [Foundation](http://foundation.zurb.com/)或[Web Start Kit](https://developers.google.com/web/starter-kit/)；
  * 对于服务器端开发，可以选择[Node.js Express App](http://expressjs.com/)；
  * [Meteor App](https://www.meteor.com/) 可用于前后端开发；
  * [PhoneGap/Cordova App](https://www.meteor.com/) 可用于开发在各种移动平台上运行的移动应用程序；
  * [Web Start Kit](https://developers.google.com/web/tools/starter-kit/)；
  * [Dart](http://www.dartlang.org/)，在开始之前：
    1. 下载并安装[Dart SDK](http://www.dartlang.org/downloads.html)。了解 [Dart有关信息](https://www.jetbrains.com/help/phpstorm/dart.html)
    2. 按照[管理插件](https://www.jetbrains.com/help/phpstorm/managing-plugins.html)所描述的，在[插件页面](https://www.jetbrains.com/help/phpstorm/plugins-settings.html)下载并安装 Dart 插件
  * Yeoman项目生成器，查看 [使用Yeoman Generator创建项目](https://www.jetbrains.com/help/phpstorm/creating-a-project-using-yeoman-generator.html)。

按照[从框架模板部分生成项目](https://www.jetbrains.com/help/phpstorm/generating-a-project-from-a-framework.html)的描述完成项目创建。


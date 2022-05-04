# Delphi 手册

Delphi 是 Borland 公司开发的，深受广大程序员所喜爱的可视化软件开发工具。和 Visual C++ 相比，Delphi 更简单、更易于掌握，而在功能上也丝毫不逊色；和 Visual Basic 相比，Delphi 则功能更强大、更实用，学习上也不比 Visual Basic 困难。可以说 Delphi 同时兼备了 Visual C++ 功能强大和 Visual Basic 简单易学的特点。

## Delphi 发展历程

- `Delphi 1` - Delphi 1 发布于 1995 年，在那时 DOS 系统下的程序员只有两种选择：不是用简单但速度慢的 Basic
语言，就是用效率高但却复杂的汇编语言。Pascal 以其结构化语言的简练和真编译器的性能，综合了
两者的优势。而 Windows 3.1 的程序员同样面临两种选择：一种是功能强大却难以使用的 Visual C++，
另一种是容易使用但语言有局限的 Visual Basic。对此，Delphi 1 提供了一种完全不同于开发 Windows
程序的方法：可视化的开发环境、编译后的可执行软件、DDL、数据库、毫无限制地给可视环境命名。
Delphi 1 作为第 1 个综合了可视化开发环境、优化的源代码编译器、可扩展的数据库访问引擎的
Windows 开发工具，奠定了 RAD 工具的基础。

- `Delphi 2` - 一年后的 Delphi 2 在 32 位的操作系统 Windows 95 和 Windows NT 下实现了原有的一切功能。另
外，Delphi 2 还增加了许多 Delphi 1 没有的功能，例如 32 位的编译器能生成速度更快的应用程序，对
象库得到进一步地丰富和扩展，完善了数据库支持，改进了字符串处理，支持 OLE 和可视化窗体继承
以及与 16 位的 Delphi 兼容等。Delphi 2 成为衡量其他 RAD 工具的标准。

- `Delphi 3` - 在研制 Delphi 3 的时候，开发组考虑到 Windows 开发者可能会遇到的棘手问题，提供了一套完整
的解决方案。1997 年推出的 Delphi 3 使本来极其复杂的 COM、ActiveX、WWW 应用程序开发、“瘦”
客户应用程序、多层数据库系统体系结构等技术变得非常容易使用。虽然 Delphi 3 和 Delphi 1 编写应
用程序的基本方法大都相同，但是 Delphi 3 的代码内视（Code Insight）技术却简化了代码编写的过程。

- `Delphi 4` - 1998 年发布的 Delphi 4 致力于使 Delphi 更易于使用。Module Explore 技术的引入使程序员能够以
一致的图形界面浏览和编辑代码。代码导航和类自动生成的功能使程序员只需关注应用程序本身，而
不必在输入代码上花费太多精力。IDE 经过重新设计可支持浮动和可停靠的工具栏和窗口，调试器也
做了改进。Delphi 4 的 MIDAS、DCOM 和 CORBA 等技术使 Delphi 4 的应用范围扩展到企业级。

 - `Delphi 5` - 经过悉心研究，直至 1999 年 7 月，Boland 公司才推出功能更为强大的 Delphi 5，它在下面几个方
面取得了进步。首先 Delphi 5 和 Delphi 4 一样，通过增加更多的功能使程序的编写更简单。新功能进
一步增强了 IDE 和调试器的功能，提供了 TeamSource 小组开发软件和转换工具等。其次，Delphi 5
也为简化 Internet 的开发增加了许多新功能，其中包括 Active Server Object Wizard（用于创建 ASP）、
Internet Express 组件、用于支持 XML 和新的 MIDAS 功能，使 Delphi 成为 Internet 的一个通用数据平
台。最后，Delphi 5 最重要的特征—稳定性。

- `Delphi 6` - Delphi 6 发布于 2001 年 6 月。Delphi 6 在继承 Delphi 5 特性的基础上，又增加了当时惟一全面支
持所有主要工业标准（XML、SOAP、WSDL、XSL 等）的开发工具，同时支持基于 Web 服务的
Microsoft .NET 和 Sun ONE 体系，提供给 Web 开发者需要的可伸缩性与可靠性。Delphi 6 框架中包括了 BizSnap、WebSnap 和 DataSnap，用户可以用它们开发支持 Web 服务特性的服务器端和客户端应用
程序，这一切是通过一套高度集成的可视化开发工具、先进的编译技术和可重用的组件完成的。

- `Delphi 7` - 而 Delphi 7 就是 Borland 公司在 2002 年 8 月推出的新版本。

## Delphi 主要特性

 Object Pascal 语言，功能强大、成熟而丰富的组件，强大的数据库支持，便捷的 Internet 编程等特
性的基础上，又增加了下列新特性：
- 企业应用的 MDA 开发。加速了开发进程，减小了代码量，节省了开发时间。
- 可视化的快速 Web 开发。在 Delphi 7 环境中可视化地开发 Web 程序，利用其应用模型框架，
不必考虑通用的服务器端的开发任务，透明地处理会话管理。
- 对 Linux 的跨平台支持。Delphi 7 有一个支持 Delphi 语言版本的孪生兄弟 Kylix 3。Kylix 3 是
第 1 个在 Linux 操作系统上的高性能的可视化集成开发环境（IDE），它适于快速创建数据库应用、GUI
应用、Web 应用和 Web 服务应用。
- 企业级的报表能力。开发者可以创建跨平台的报表，这些报表能帮助查看应用程序运行的效率。
- 免费的 DataSnap 多层应用开发。Delphi 7 的 DataSnap 授权协议允许开发者无缝地升级单层应
用和客户/服务器应用到多层应用。
- Windows XP 应用。Delphi 7 对 Windows XP 风格的支持，能够让开发者创建可以利用 Windows 
XP 界面风格的应用程序。

Delphi 开发环境是使用 Object Pascal 语言进行编程的。Object Pascal 语言是在 Pascal 语言的基础
上发展起来的，具有可读性好、编写容易的特点，这使得它很适合作为基础的开发语言。同时，使用
编译器创建的应用程序只生成单个可执行文件（EXE），这样使得 Object Pascal 成为 Delphi 这种先进开发环境的编程语言。

## Delphi 优势

**(*) 丰富的组件**

Delphi 7 拥有一个庞大的可视化组件库（VCL），包含了一百多个、涉及到程序设计各个领域的组
件。它在原有组件的基础上，又增加了以下新组件。

- Windows XP 的支持  
Delphi 7 提供了支持 Windows XP 主题风格的 VCL 控件。

- 新增加的组件

  - “Additional”标签页新增加了 TXPColorMap 组件、TStandardColorMap 组件以及 TTwilightColorMap 组件。
  - “dbExpress”标签页新增加了 TSimpleDataSet 组件。
  - “Dialogs”标签页新增加了 TPageSetupDialog 组件。
  - “System”标签页的 CLX 版本加入了新的路径及文件组件。
  -  新增的 Indy Intercepts 以及 Indy I/O Handlers，用于支持基于 Internet 网络应用程序的开发工作
（专业版和企业版）。

- 改进了的组件
  - TOpenDialog 以及 TSaveDialog 的 CLX 版本现在可以支持一些附加的特征，例如文件预览等。
  - TCustomForm 的 VCL 版本加入了两个新的属性：ScreenSnap 属性以及 SnapBuffer 属性。
  - TCustomComboBoxEx 新加入一个 AutoCompleteOptions 属性
  - 从 TOpenDialog 和 TQtDialog 继承来的 CLX 对话对象可以用 Windows Common Dialogs 来代替
QtDialogs。

- 新增加的单元

DBClientActns 单元包含了 3 个与 Client Datasets 协同工作的新的行动组件：TClientDataSetApply
组件、TClientDataSetUndo 组件和 TClientDatasetRevert 组件。这 3 个组件分别进行编辑时修改的记录、
取消与重做操作，从而大大减少了程序员的工作量。

**(*) 功能强大的数据库访问技术**

Delphi 7 凭借窗体（Forms）和报表（Reports）就可以访问多种数据库管理系统的数据库：ADO
（ActiveX Data Object）可以访问本地或远程的 Access、SQL Server、Oracle 等服务器的数据库；BDE
（Borland Database Engine）可以访问 Access、Paradox、dBASE、本地 InterBase 等服务器的数据库，
也可以访问远程数据库服务器上的数据库（如 Oracle、SyBase、Informix 等客户/服务器数据库中的数
据库）或任何经 ODBC（Open Database Connecticity）可访问的数据库管理系统中的数据库。
跟其他面向对象的编程工具一样，Delphi 提供了许多组件以方便地创建数据库应用程序。数据库
对象的数据属性既可在设计阶段设置，也可在运行阶段通过程序代码进行设置。Delphi 的组件板上提
供了两页数据库应用程序开发中所要使用的组件。
•“Data Access”页（数据访问页）上的组件用于直接访问数据库中的数据表。
•“Data Controls”页（数据控制页）上的组件用来与用户交互，显示、修改数据库中的数据。
数据库应用程序首先是利用 Delphi 提供的数据库组件与 ADO 或 BDE 建立联系，然后再通过 ADO
或 BDE 与数据库联系。

**便捷的 Internet 编程技术**

Delphi 7 提供了 Nevrona 的 Indy 系列组件和 Borland 系列的组件。Indy 组件具有功能强大的特点，
Borland 组件则具有使用方便的特性。
TCPServer 组件和 TCPClient 组件主要用来设计基于 TCP/IP 协议集的服务器和客户端程序。
Internet 组件面板上的 WebBrowser 组件提供了进行 Web 访问的功能，利用它可以通过简单的编程实现
访问 Web 资源，稍增加一些功能就可以做出类似 Internet Explorer 的软件；通过 WebSnap、IntraWeb
等 Web 开发组件，能够轻松设计出各种效果的网站。


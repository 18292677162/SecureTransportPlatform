﻿================================================================================
    MICROSOFT 基础类库 : SecmngAdmin 项目概述
===============================================================================

应用程序向导已为您创建了此 SecmngAdmin 应用程序。此应用程序不仅演示 Microsoft 基础类的基本使用方法，还可作为您编写应用程序的起点。

本文件概要介绍组成 SecmngAdmin 应用程序的每个文件的内容。

SecmngAdmin.vcxproj
    这是使用应用程序向导生成的 VC++ 项目的主项目文件，其中包含生成该文件的 Visual C++ 的版本信息，以及有关使用应用程序向导选择的平台、配置和项目功能的信息。

SecmngAdmin.vcxproj.filters
    这是使用“应用程序向导”生成的 VC++ 项目筛选器文件。它包含有关项目文件与筛选器之间的关联信息。在 IDE 中，通过这种关联，在特定节点下以分组形式显示具有相似扩展名的文件。例如，“.cpp”文件与“源文件”筛选器关联。

SecmngAdmin.h
    这是应用程序的主头文件。
    其中包括其他项目特定的标头（包括 Resource.h），并声明 CSecmngAdminApp 应用程序类。

SecmngAdmin.cpp
    这是包含应用程序类 CSecmngAdminApp 的主应用程序源文件。

SecmngAdmin.rc
    这是程序使用的所有 Microsoft Windows 资源的列表。它包括 RES 子目录中存储的图标、位图和光标。此文件可以直接在 Microsoft Visual C++ 中进行编辑。项目资源包含在 2052 中。

res\SecmngAdmin.ico
    这是用作应用程序图标的图标文件。此图标包括在主资源文件 SecmngAdmin.rc 中。

res\SecmngAdmin.rc2
    此文件包含不在 Microsoft Visual C++ 中进行编辑的资源。您应该将不可由资源编辑器编辑的所有资源放在此文件中。

/////////////////////////////////////////////////////////////////////////////

对于主框架窗口：
    该项目包含一个标准的 MFC 接口。

MainFrm.h, MainFrm.cpp
    这些文件中包含框架类 CMainFrame，该类派生自
    CFrameWnd 并控制所有 SDI 框架功能。

/////////////////////////////////////////////////////////////////////////////

应用程序向导创建一种文档类型和一个视图：

SecmngAdminDoc.h、SecmngAdminDoc.cpp - 文档
    这些文件包含 CSecmngAdminDoc 类。编辑这些文件以添加特殊文档数据并实现文件保存和加载（通过 CSecmngAdminDoc::Serialize）。

SecmngAdminView.h、SecmngAdminView.cpp - 文档视图
    这些文件包含 CSecmngAdminView 类。
    CSecmngAdminView 对象用于查看 CSecmngAdminDoc 对象。




/////////////////////////////////////////////////////////////////////////////

其他标准文件:

StdAfx.h, StdAfx.cpp
    这些文件用于生成名为 SecmngAdmin.pch 的预编译头 (PCH) 文件和名为 StdAfx.obj 的预编译类型文件。

Resource.h
    这是标准头文件，可用于定义新的资源 ID。Microsoft Visual C++ 将读取并更新此文件。

/////////////////////////////////////////////////////////////////////////////

其他注释:

应用程序向导使用“TODO:”来指示应添加或自定义的源代码部分。

如果应用程序使用共享 DLL 中的 MFC，您将需要重新分发 MFC DLL。如果应用程序所使用的语言与操作系统的区域设置不同，则还需要重新分发相应的本地化资源 mfc110XXX.DLL。
有关上述话题的更多信息，请参见 MSDN 文档中有关重新分发 Visual C++ 应用程序的部分。

/////////////////////////////////////////////////////////////////////////////

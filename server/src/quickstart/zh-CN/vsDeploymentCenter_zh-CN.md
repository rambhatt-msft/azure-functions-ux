# 安装依赖项

开始之前，应[安装 Visual Studio 2019](https://go.microsoft.com/fwlink/?linkid=2016389) 并确保还安装了 Azure 开发工作负荷。

安装 Visual Studio 后，请确保具有[最新的 Azure Functions 工具](https://go.microsoft.com/fwlink/?linkid=2016394)。

<br/>
# 创建 Azure Functions 项目

在 Visual Studio 中，从“文件”菜单中选择“新建”>“项目”************。

在“新建项目”对话框中，选择“已安装”，展开“Visual C#”>“云”，选择“Azure Functions”，键入项目的“名称”，然后单击“确定”****************************。函数应用名称必须是有效的 C# 命名空间，因此请勿使用下划线、连字符或任何其他非字母数字字符。

按照向导选择和自定义模板。建议开始时使用 HTTP。然后单击“确定”以创建第一个函数****。

<br/>
# 创建函数

默认情况下，创建项目会创建 HTTP 函数，因此现在无需执行任何操作。稍后，如果要添加新函数，请在“解决方案资源管理器”中右键单击项目，然后选择“添加”>“新建 Azure 函数...”************。

为函数命名，然后单击“添加”****。选择并自定义模板，然后单击“确定”****。

<br/>
# 在本地运行函数项目

按 F5 以运行函数应用****。

该运行时将为任何 HTTP 函数输出 URL，可以在浏览器的地址栏中复制和运行该 URL。

若要停止调试，请按 Shift + F5****。

<br/>
# 将代码部署到 Azure

使用下面的“完成后，请转到部署中心”按钮，导航到部署中心并完成应用设置****。这将引导你完成配置各种部署选项的新向导。完成此流程后，使用你配置的任何机制触发部署。

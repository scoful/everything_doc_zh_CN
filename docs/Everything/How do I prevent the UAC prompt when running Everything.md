##How do I prevent the UAC prompt when running "Everything" | 怎么防止运行Everything时弹出UAC提示?##

"Everything" requires administrative privileges for low level read access to NTFS volumes for NTFS indexing.

> Everything要从底层索引NTFS格式的硬盘数据，必须要有管理员权限。

The UAC prompt can be avoided by running "Everything" as a standard user and installing the "Everything" service or not using NTFS indexing.

> 在运行Everything时想避免UAC提示，方法一：以标准用户身份运行，并安装Everything服务；方法二：不要用NTFS索引。


To run "Everything" as a standard user and install the "Everything" service:

> 以标准用户身份运行，并安装Everything服务的步骤：

- In "**Everything**", from the **Tools** menu, click **Options**.

> 打开Everything，菜单栏 点击 工具，点击 选项。

- Click the **General** tab.

> 点击 常规 标签。

- Check **Everything Service**.

> 勾选 Everything服务。

- Uncheck **Run as administrator**.

> 去掉勾选 以管理员身份运行。

- Click **OK**.

> 点击 确定。

- Exit "Everything" (right click the Everything system tray icon and click Exit)

> 关闭Everything。(右键点击Everything的系统托盘图标，并点退出。)

- Restart Everything.

> 重启Everything。
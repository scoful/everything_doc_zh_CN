##The result list is empty or contains only drives | 搜索结果为空或是只出现盘符##

Please make sure the "Everything" service is running or "Everything" is running as administrator.

> 请确认Everything服务在运行或是Everything是以管理员身份运行的。

To install the "Everything" service:

> 运行Everything服务的步骤：

- In **Everything**, from the **Tools** menu, click **Options**.

> 打开Everything，点开菜单栏的 工具，点 选项。

- Click the **General** tab.

> 点 常规 标签。

- Check **Everything Service**:

> 勾选 Everything 服务。

- Click **OK**.

> 点 确定。

-or-

To run Everything as administrator:

> 以管理员身份运行Everything的步骤：

- In Everything, from the Tools menu, click Options.

> 打开Everything，点开菜单栏的 工具，点 选项。

- Click the General tab.

> 点 常规 标签。

- Check Run as administrator:

> 勾选 以管理员身份运行。

- Click OK.

> 点 确定。

Make sure you have at least one local NTFS volume.

> 确保至少有一个盘是NTFS格式的。

See How do I convert a volume to NTFS#TODO.

> 查看 怎么格式化为NTFS格式的盘#TODO

To manually enable all local NTFS volumes for indexing:

> 手动配置所有的NTFS格式的盘的步骤：

- In Everything, from the Tools menu, click Options.

> 打开Everything，点开菜单栏的 工具，点 选项。

- Click the Volumes tab.

> 点 索引 。

- For each volume in the Local NTFS volumes list:

> 点 NTFS 标签 ，在右边的 本地NTFS分卷，选中任一：

- Check Check Media.

> 勾选 检查媒体文件#TODO这个版本 V1.4.1.867b (x64)里没找到

- Check Enable USN Journal logging.

> 勾选 启用USN日志。

- Check Include in database.

> 勾选 包含到数据库。

- Check Monitor changes.

> 勾选监控变化。

- Click OK.

> 点 确定。

Force Everything to rebuild its database:

> 强制重建Everything的数据库的步骤：

- In Everything, from the Tools menu, click Options.

> 打开Everything，点开菜单栏的 工具，点 选项。

- Click the Indexes tab.

> 点 索引 标签。

- Click Force Rebuild.

> 点 强制重建。

- Click OK.

> 点 确定。
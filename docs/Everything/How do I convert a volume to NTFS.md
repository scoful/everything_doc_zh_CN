##How do I convert a volume to NTFS | 怎么转换硬盘格式为NTFS?##

Please backup anything important before converting a volume to NTFS.

> 切记，转换硬盘格式为NTFS前，请务必先备份重要的文件。

Once a volume is converted to NTFS it can not be converted back to FAT or FAT32.

> 切记，硬盘格式转换为NTFS后，就转换不回FAT或是FAT32了。

Please note that some devices may not be able to read NTFS volumes on USB disks / USB drives.

> 切记，请先了解，某些设备不能识别NTFS格式的USB盘、USB驱动器。 


To convert a volume to NTFS:

> 转换硬盘格式为NTFS的步骤：



- From the **Start** menu, click **Run**.

> 1.开始菜单，运行。

- type in the following and press **ENTER**:
cmd

> 2.输入`cmd`,回车

- In the command prompt, type in the following and press **ENTER**:
convert D: /fs:ntfs
where D: is the drive to convert.

> 3.在命令行模式下，输入 `convert D: /fs:ntfs` ，回车。(D：代表要转换的盘)


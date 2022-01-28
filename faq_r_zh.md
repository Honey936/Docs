### 为什么第二空间在 Android 11 上需要“允许访问所有文件”权限？

由于 Google Play 的限制，在 Android 11 及更高版本的设备上，应用程序必须需要“允许访问所有文件”权限才能访问外部存储中的文件。该权限是通过 Android 10 及更低版本设备上的权限请求对话框授予的。由于应用程序的目标版本已更改为 Android 11。只有Google Play 允许的应用程序才能请求此权限。

**以下是第二空间需要权限的原因：**

1. 第二空间将加密文件存储在外部存储上的 .privacy_safe 中。通过这样做，如果第二空间被意外卸载，加密文件将保留在那里，并且在您再次安装第二空间后，第二空间可以为您恢复数据。

2. 第二空间支持对外部存储上的任何类型的文件进行加密。未经许可，无法将外部存储上的文件添加到第二空间。

3. 备份和恢复功能也需要此权限。

这是谷歌官方的解释：https://developer.android.com/training/data-storage/manage-all-files#all-files-access-google-play

感谢您的理解。
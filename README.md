# save-all-urls
保存当前Chrome窗口下所有的 Tab. 使用 chrome.storage.
sync方式实现了自动数据同步，相同的用户无论使用什么物理设备，只要以相同的账户登录即可访问存储的数据。设备离线时数据存储在本地，一旦设备上线则同步数据。如果用户禁止了数据同步，则采用chrome.storage.local方式。

## 使用方法

* 保存当前Chrome窗口下所有的 Tab，作为一个`TabSpace`

* 在稍后合适的时候，通过打开相应的`TabSpace`可以打开之前保存的Tab

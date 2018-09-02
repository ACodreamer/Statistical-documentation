将下载的 Fake.cmd 保存在随便一个地方，然后把一个文件夹使用它打开，等几秒后会自动生成 FileList.txt，其中包含这个文件夹的所有文件（注意：不包含文件夹中的文件夹）

这个程序的魅力在于，它只有一行！

```
dir \\?\%1 /a:-d /b /o /p /w >FileList.txt
```

![](https://i.loli.net/2018/09/02/5b8bd4a081ff4.png)


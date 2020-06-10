# chh_file
# 文件
* com.apple.amp.itmstransporter 为苹果上传替换文件
操作步骤
```
# 在终端中操作
# 第一步 打开文件
open ~/Library/Caches/com.apple.amp.itmstransporter/
# 第二步 删除里面内容 将下载内容替换进去
# 或者直接替换com.apple.amp.itmstransporter这个文件夹
#在终端复制：/Applications/Xcode.app/Contents/Applications/Application Loader.app/Contents/itms/bin/iTMSTransporter

[2020-06-10 18:00:54 CST] <main>  INFO: Configuring logging...
[2020-06-10 18:00:54 CST] <main>  INFO: Logging level set to eXtreme
[2020-06-10 18:00:54 CST] <main>  INFO: Transporter is searching for new software components.
[2020-06-10 18:00:54 CST] <main>  INFO: INFO: using cached repository.xml file.
[2020-06-10 18:00:55 CST] <main>  INFO: indexing file: /Users/zhw/Library/Caches/com.apple.amp.itmstransporter/obr/2.0.0/com.apple.its.epubcheck-runner-4.3.0.jar
[2020-06-10 18:00:55 CST] <main>  INFO: indexing file: /Users/zhw/Library/Caches/com.apple.amp.itmstransporter/obr/2.0.0/com.apple.transporter.mediatoolkit-2.0.0.jar
.....
                    the process idles because the message 'Press any key...' is
                    displayed on the console and the system awaits a keypress. To
                    avoid this behavior, set this property to true
 -Xmx4096m          Specifies that you want to change the Java Virtual Machine's (JVM)
                    allocated memory by increasing the JVM heap size.  By default,
                    Transporter uses a 2048MB heap size. You can use the -Xmx4096m
                    option to specify a 4-gigabyte (GB) heap size. Apple recommends,
                    if needed, increasing the heap size to 4096MB by specifying the
                    -Xmx4096m (or -Xmx4g) option and adjusting as needed.
[2020-06-10 18:01:00 CST] <main> DBG-X: Returning 0

# 第三步 重启Xcode
```


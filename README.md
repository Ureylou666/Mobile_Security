# Android

## 工具使用 (三板斧)

### MobSF

### apktools
下载地址： https://ibotpeaches.github.io/Apktool/install/

作用：主要查看res文件下xml文件、AndroidManifest.xml和图片。（注意：如果直接解压.apk文件，xml文件打开全部是乱码）

- 使用方法
```
1. 将需要检测的apk与apktools放到同一文件夹下（just make the life easier）
2. 打开cmd，运行apktool d ****.apk
3. 文件夹****，里面就有需要的文件
```

### dex2jar

下载地址：https://github.com/pxb1988/dex2jar

作用：将apk反编译成Java源码（classes.dex转化成jar文件）

- 使用方法
```
sh d2j-dex2jar.sh -f ~/path/to/apk_to_decompile.apk
```

### jd-gui

下载地址：https://github.com/java-decompiler/jd-gui

作用：查看APK中classes.dex转化成出的jar文件，即源码文件

- 使用方法
```
直接将jar拖入即可查看源码
```

# IOS


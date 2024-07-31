## 原理

开机静默启动Steam，Steam自动打开壁纸引擎，并开始游玩壁纸引擎并记录时长。

## 准备工作 (无论哪种方法都需要)

1. 在Steam库中找到 Wallpaper Engine：壁纸引擎--右键--属性

2. 在 已选启动选项--高级用户可以选择输入对启动选项的修改 处输入：

   ```
   -steamtrackhours
   ```

   ![image-20240731200741328](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202407312007521.png)

3. 打开壁纸引擎，任务栏右下角壁纸引擎托盘--设置--常规--关闭开机启动|
   ![image-20240731210718165](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202407312107291.png)


## 方法一：使用Steam++ 代为启动

本次使用的Steam++版本号：3.0.0-rc.9forWindows（x64)

1. 打开Steam++左下角设置图标，通用设置--启用以下选项：开机自启动、启动时最小化到托盘、启用托盘图标
   ![image-20240731201428586](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202407312014649.png)
   
2. Steam设置--启用以下选项：启动时自动运行Steam
   ![image-20240731202145703](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202407312021764.png)

3. Steam启动参数--编辑，填入以下文本
   ```
   -silent -applaunch 431960
   ```
   ![image-20240731202513331](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202407312025408.png)
   
4. 完毕

## 方法二 只使用Steam客户端

1. 复制一份Steam的**快捷方式**到`%APPDATA%\Microsoft\Windows\Start Menu\Programs\Startup`

2. 右键点击这个快捷方式的属性，在目标的后面加上：
   注意：在文件路径的双引号后面，应该有且只有一个空格。

   ```
    -silent -applaunch 431960
   ```

   ![image-20240731203248035](https://booster.beixinqiao.top/https://raw.githubusercontent.com/beixinti/Picture/main/Picture/202407312032114.png)
   
3. 完毕

## 缺点和注意事项

1. 只要你不在游玩其他游戏，那么steam会一直向你的好友显示你正在游玩《Wallpaper Engine：壁纸引擎》
   解决办法：在Steam库中找到 Wallpaper Engine：壁纸引擎--右键--管理--标记为私密；不过缺点是设置之后别人也同样看不到
   
1. 每次开机可能会出现Steam检查更新的弹窗
   解决办法，在启动参数的后面再加上：

   ```
    -noverifyfiles
   ```

   (记得打空格)
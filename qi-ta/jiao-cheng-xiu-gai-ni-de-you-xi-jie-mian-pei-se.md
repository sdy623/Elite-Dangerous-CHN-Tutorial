# 【教程】修改你的游戏界面配色

## 精英危险中文论坛

## 【教程】修改你的游戏界面配色

### Weic

默认界面难看吗？肯定是难看了，不难看怎么会出现修改配色的教程和工具呢！

### 调出你自己喜欢的配色

打开[这个网页](http://arkku.com/elite/hud_editor/)，然后会看到下图（除了我修改的部分）一样的界面；

![0\_1537687555770\_screencapture-arkku-elite-hud\_editor-2018-09-23-15\_10\_40.png](https://cdn.elitedanger.cn/FtS4m037P2XoNP3W6tK-Ibetc3Dy)

用法已经在图上标出来了；

### 如何使用到你的游戏里

打开C:\Users\你的用户名\AppData\Local\Frontier Developments\Elite Dangerous\Options\Graphics

注意：这个位置不一定适用于所有人，但是后面的Frontier Developments\Elite Dangerous\Options\Graphics每个人的都一样。进入该目录时要开启你电脑的显示隐藏文件功能；

找到并打开文件夹之后里面应该有一个叫GraphicsConfiguration.xml的文件，如果没有就新建一个txt文件，然后修改为GraphicsConfiguration.xml，注意文件后缀也要修改，然后在里面加入下面的内容

```text
<?xml version="1.0" encoding="UTF-8" ?>
<GraphicsConfig>
    <GUIColour>
        <Default>
            <LocalisationName>Standard</LocalisationName>
            <MatrixRed> 1, 0, 0 </MatrixRed>
            <MatrixGreen> 0, 1, 0 </MatrixGreen>
            <MatrixBlue> 0, 0, 1 </MatrixBlue>
        </Default>
    </GUIColour>
</GraphicsConfig>
```

如果你要使用你自己调的配色就把上面图片里我圈出来的位置里面的三行代码复制粘贴到你新建的GraphicsConfiguration.xml文件夹里面，替换掉原来的

```text
<MatrixRed> 1, 0, 0 </MatrixRed>
<MatrixGreen> 0, 1, 0 </MatrixGreen>
<MatrixBlue> 0, 0, 1 </MatrixBlue>
```

这三行代码，然后保存文件进游戏即可

### 網友Samuel補充的steam路徑方式

補充STEAM路徑

Steam\steamapps\common\Elite Dangerous\Products\elite-dangerous-64\GraphicsConfiguration.xml

直接搜索

改底下的顏色矩陣就好了

```text
<MatrixRed> 1, 0, 0 </MatrixRed>
<MatrixGreen> 0, 1, 0 </MatrixGreen>
<MatrixBlue> 0, 0, 1 </MatrixBlue>
```

在我的環境裡

\AppData\Local\Frontier Developments\Elite Dangerous\Options\Graphics

裡面是

GraphicsConfigurationOverride.xml 這也可以用

在這裡面

就要建立完整

的CODE

我会在下面分享一些比较好看的配色方案，或者你也可以自己去看[这里](https://forums.frontier.co.uk/showthread.php/259311-NO2O!-The-Definitive-List-of-1-7-2-2-Compatible-HUD-Colour-Color-Configs-%28please-add-yours!%29)

### Weic

先放一个我用的配色

```text
<MatrixRed> 0.25, 0.43, 1 </MatrixRed>
<MatrixGreen> 0.83, 1, 0 </MatrixGreen>
<MatrixBlue> 1, 0, 0 </MatrixBlue>
```

有图有真相

![0\_1537698256342\_COLORSSSS.jpg](https://cdn.elitedanger.cn/FvX0szhiDhJszbBSVmIo5hkuez59.jpg)

### samuel

這接敵與警告顏色應該歪得相當嚴重阿

補充STEAM路徑

Steam\steamapps\common\Elite Dangerous\Products\elite-dangerous-64\GraphicsConfiguration.xml

直接改這裡

就只要改顏色矩陣就好了

在我的環境裡

\AppData\Local\Frontier Developments\Elite Dangerous\Options\Graphics

裡面是

GraphicsConfigurationOverride.xml 這也可以用

在這裡面

就要建立完整

的CODE

### dabinn

這個是不是可以用EDProfiler來作呢？

[https://forums.frontier.co.uk/showthread.php/348327-EDProfiler-has-a-GUI-colour-editor-picker-now-with-accurate-avatars](https://forums.frontier.co.uk/showthread.php/348327-EDProfiler-has-a-GUI-colour-editor-picker-now-with-accurate-avatars)!

### 作者: y1n4

[@dabinn](http://127.0.0.1:4567/uid/143) 可以啊哈哈哈我自己其實就是用這個～

### pad13g

我什么我打开网页没有滑块可以拖动，更改数值界面颜色也不变动，我有的chrome，换了火狐，IE都不行[y1n4](https://forum.elitedanger.cn/d/144/5)

### Weic

[pad13g](https://forum.elitedanger.cn/d/144/6) 我刚试了下可以，可能是你的网页没有加载完成，毕竟外网。有问题最好配图说明

### pad13g

[Weic](https://forum.elitedanger.cn/d/144/7) 我打开是这样子的，网页显示加载完成了，没有挂梯子什么的![](https://qiniu.elitedanger.cn/assets/files/2020-10-02/1601610522-833806-573ebd29-0834-4b50-b894-e123d211166f.jpeg)

### Weic

[pad13g](https://forum.elitedanger.cn/d/144/8) 这没有加载完成，可能就是墙的原因吧

### yuansou

感觉色彩偏差太大了。。完全不能接受。。。妥协一下正常的屎橘色也还是不错的🙄

### Weic

[yuansou](https://forum.elitedanger.cn/d/144/10) 各有所爱罢了

### pad13g

[Weic](https://forum.elitedanger.cn/d/144/11) 请问大佬有没有办法只替换橘色，其他颜色不变

### Weic

[pad13g](https://forum.elitedanger.cn/d/144/12) 不知道，应该可以调出来的，你试试

### DrunkPiano

大佬，我从 Epic 下载的。然后根据你的指南，我修改了，进入游戏后，依然没变化。这是为什么？

### DrunkPiano

[DrunkPiano](https://forum.elitedanger.cn/d/144/14) 不好意思。已经变了。开心的一批。


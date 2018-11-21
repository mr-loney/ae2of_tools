## 使用方式

#### 图层名规则
| 规则 | 图层名 | 描述 |
| ------ | ------ | ------ |
| 等于 | background | 导出图层为视频，并添加到of inputfile中，做为默认播放视频 |
| 包含 | _maskAllVideo | 导出图层为视频，并设置到所有图层mask属性中 <font color=#ff00000>（注意：此mask会覆盖_maskVideo）</font> |
| 包含 | _maskVideo | 导出图层为视频，并设置到同名图层mask属性中，如：<br/>存在图层a、a_maskVideo两个图层，则表示导出a_maskVideo图层为视频，并设置a图层的mask属性为此视频 |
| 包含 | _maskSVGA(开发中) | 导出图层为svga格式，并设置到同名图层mask属性中<font color=#ff00000>（仅支持形状图层）</font> |
| 包含 | _svga(开发中) | 导出图层为svga格式 |


#### 从Adobe After Effects导出

1、设置需要导出的图层<br/>
![use1.png](https://github.com/mr-loney/ae2of_tools/raw/master/readme_img/use1.png "use1")<br/>

2、点击【文件】-【脚本】-【运行脚本文件】<br/>
![use2.png](https://github.com/mr-loney/ae2of_tools/raw/master/readme_img/use2.png "use2")<br/>
打开ae2of工具所在的目录（如 **D:\ae2of**）,选择ae2of.jsx文件，点击确定即可开始导出<br/>
![use3.png](https://github.com/mr-loney/ae2of_tools/raw/master/readme_img/use3.png "use3")<br/>
等待执行完毕，即可看到导出素材的所在位置<br/>
![use4.png](https://github.com/mr-loney/ae2of_tools/raw/master/readme_img/use4.png "use4")<br/>
![use5.png](https://github.com/mr-loney/ae2of_tools/raw/master/readme_img/use5.png "use5")<br/>

3、在 **of_design** 工具中点击【文件】-【打开特效项目】<br/>
![use6.png](https://github.com/mr-loney/ae2of_tools/raw/master/readme_img/use6.png "use6")<br/>
打开刚才素材导出的位置，点击【打开】<br/>
![use7.png](https://github.com/mr-loney/ae2of_tools/raw/master/readme_img/use7.png "use7")<br/>
在of_design工具中，点击运行即可看到AE中素材导出的效果<br/>
![use8.png](https://github.com/mr-loney/ae2of_tools/raw/master/readme_img/use8.png "use8")<br/>

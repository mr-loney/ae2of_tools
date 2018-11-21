## 使用方式

#### 图层名规则
| 规则 | 图层名 | 描述 |
| ------ | ------ | ------ |
| 等于 | background | 导出图层为视频，并添加到of inputfile中，做为默认播放视频 |
| 包含 | _maskVideo | 导出图层为视频，并设置到同名图层mask属性中，如：<br/>存在图层a、a_maskVideo两个图层，则表示导出a_maskVideo图层为视频，并设置a图层的mask属性为此视频 |
| 包含 | _maskY2A(开发中) |  |


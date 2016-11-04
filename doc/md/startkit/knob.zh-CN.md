旋钮
======
## 测量

### 描述

测量旋钮的旋转值（0-1024）

### 配置

`pin`: 整数. 该旋钮连接的AIO引脚. 必填项

### 输入

`trigger`: 任何类型. 触发信号, 每来一次输入就测量一次旋转值

### 输出

`value`: 数值类型. 表示旋转值（0-1024）

### 样例

![](./pic/knob_buzz.zh-CN.jpg)

图中每隔1s就测量旋钮值，如果超过500就打开蜂鸣器，反之则关闭
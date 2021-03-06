# JSGame

使用**原生 JavaScript** 的 **ECMAScript 6** 语法标准开发的游戏框架

## 框架核心原理

JSGame 的**核心原理**是通过**定时器**定义一个**游戏帧率**，在每一帧里都会依次执行 **debug**、 **update** 和 **draw** 这些生命周期函数，销毁时调用 **destroy**，这样不用每次手动去更新和绘制视图页面，**将逻辑和视图分离出来**。

## 特点与实现

- 实现了**框架的生命周期**，父模块调用子模块的相应的生命周期函数
- 实现了**游戏场景的抽象**，实现游戏随时切换场景
- 实现了**游戏资源的预加载**，提高游戏体验
- 实现了**双向绑定机制**，能够在游戏运行期间修改参数，提高调试效率
- 实现了**事件绑定的统一化管理**，实现模块销毁时，自动注销事件
- 支持**配置式管理**，可配置预加载资源以及调试参数，提高开发和调试效率
- 在 **canvas** 上实现了**动态人物模型**，管理人物不同状态的动画帧
- 在 **[block-breaker](https://gitee.com/hui0808/block-breaker)** 游戏中实现了**关卡编辑器**，鼠标点击可生成砖块或增加其生命，并可以中途保存关卡数据

## 实现项目

- 使用 **canvas** 的
  - **[block-breaker](https://github.com/hui0808/block-breaker)**  [在线地址](http://106.53.84.52/game/blockbreaker/)
  - **[flybird](https://github.com/hui0808/flybird)**  [在线地址](http://106.53.84.52/game/flybird/)
  - **[飞机大战](https://github.com/hui0808/airplane)**  [在线地址](http://106.53.84.52/game/airplane/)
- 使用 **DOM** 的
  - **[扫雷](https://github.com/hui0808/mine-clearance)**  [在线地址](http://106.53.84.52/game/mine-clearance/)
  - **[2048](https://github.com/hui0808/2048)** [在线地址](http://106.53.84.52/game/2048/)
  - **[popstar](https://github.com/hui0808/popstar)**  [在线地址](http://106.53.84.52/game/popstar/)
  - **[纸牌接龙](https://github.com/hui0808/klondike)**  [在线地址](http://106.53.84.52/game/klondike/)

> TIP：由于部署项目用的是学生优惠的腾讯云，上传带宽只有 1M，所以游戏加载会有些卡顿




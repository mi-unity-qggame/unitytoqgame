<!-- 
Feature － 新增功能/接口
Changed - 功能/接口变更
Deprecated - 不建议使用的功能/接口
Removed - 删除功能/接口
Fixed - 修复问题
Others - 其他 
-->
## 2025-11-19 v1.5.9 【重要更新】
### Feature
* 重要：新增修复多点触控可能存在粘连问题的类“MiTouchInputOverride”
* 普通：增加`GetSystemInfoSync`接口，用于同步获取系统信息
* 普通：新增`GetMenuButtonBoundingClientRect`接口，用于`获取菜单按钮（右上角胶囊按钮）的布局位置信息
* 普通：新增 `On/OffTouchStart`、`On/OffTouchMove`、`On/OffTouchEnd`、`On/OffTouchCancel` 触摸事件接口
### Fixed
* 普通：修复程序集编译问题
* 普通：修复websocket连接问题

## 2025-09-24 v1.5.8 【普通更新】
### Feature
* 普通：新增生成证书功能支持

## 2025-09-05 v1.5.7 【普通更新】
### Feature
* 重要：升级 Runtime 打包工具
* 普通：自动开启包体优化措施
### Fixed
* 普通：修复已知问题

## 2025-08-01 v1.5.6 【重要更新】
### Feature
* 重要：新增 Brotli 压缩支持
### Removed
* 普通：取消wasm拆分

## 2025-07-16 v1.5.5 【重要更新】
### Feature
* 重要：团结引擎 1.x 版本适配
### Fixed
* 普通：修复首次进入游戏缓存失败问题

## 2025-07-01 v1.5.4 【普通更新】
### Feature
* 普通：Sprite Atlas 图集默认使用 v1，可选择切换 v2 图集
### Fixed
* 普通：修复已知网络问题

## 2025-05-19 v1.5.2 【重要更新】
### Feature
* 重要：新增 WebGL 2.0 支持
* 普通：新增 “检查更新” 快游戏接口

## 2025-04-15 v1.5.1 【普通更新】
### Feature
* 普通：适配生命周期核心接口
### Fixed
* 普通：修复 Unity 2019 使用 GetLaunch 接口打包失败问题

## 2025-04-14 v1.5.0 【重要更新】
### Feature
* 重要：适配 Unity 2022 版本
* 普通：远程加载支持 zlib 压缩格式，提高传输效率
* 普通：适配文件系统核心接口，兼容旧版本接口

## 2025-03-05 v1.3.0 【重要更新】
### Feature
* 重要：增加分包打包方式，2025.1.1之后的新包包体限制在4M以下，主包+分包 <= 30M
* 普通：体验优化

## 2024-12-21 v1.2.8 【普通更新】
### Feature
* 普通：新增软键盘调用接口
### Fixed
* 普通：修复播放声音调用stop触发错误问题

## 2024-12-13 v1.2.7 【普通更新】
### Feature
* 普通：banner 与 native 广告新增位置与大小设置
### Fixed
* 普通：修复 native 广告显示问题
* 普通：修复声音采样率问题

## 2024-11-22 v1.2.5 【普通更新】
### Fixed
* 修复框架问题（navigator.mediaDevices.enumerateDevices 判断错误）

## 2024-09-30 v1.2.4 【普通更新】
### Fixed
* 修复框架问题（navigator.mediaDevices 判断错误）
* 版本控制

## 2024-06-17 v1.2.3 【普通更新】
### Feature
* 增加自定义 loading 手动关闭方式
* wasm 拆分，去除 adb logcat 依赖
### Fixed
* 修复传入 volume 最大值超过 1 时造成异常
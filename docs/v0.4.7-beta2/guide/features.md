---
title: 新特性
---

v0.4.7-beta2 新特性
===

* 修复因加入mode模式导致的推流循环无效的问题
* 更新插件版本为1.3.1，修复偶发性插件参数线程不安全导致的崩溃问题
* 新增主程序异常情况崩溃退出堆栈日志输出的功能
* 新增`/version`获取当前主程序版本参数接口
* 新增`/v1.1/player/snapshot`获取当前播放器画面jpg格式截屏图片接口
* 新增网络流媒体`m3u8`与`rtmp`协议的支持
* 修复重断线连过程中因资源问题导致的内存泄漏
* 删除因网络链接导致的水印显示未激活问题
* 更新CopyRight年份获取规则
* 添加播放模式，可选为队列（播放完成即删除）、随机（列表随机、不保证随机完整性）、列表（顺序播放）
* 修复通过API跳过当前文件标记为缓存成功的问题，解决该问题造成的下次播放会记录上次跳过的播放进度

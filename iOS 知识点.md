iOS 知识点

* 多线程
  * 多线程的使用
  * 多线程的线程安全
* 网络
  * AFN 的使用
  * AFN 的内存问题(需要使用单例，如果每次请求都新建manager会造成内存泄漏)
  * AFN 的实现机制
* 内存管理及泄漏
  * 内存管理机制(autoreleasepool)
  * 图片的内存管理(缓存和非缓存方式加载图片)
  * WKWebView、NSTimer的内存泄漏
* UI 设计
  * 源码UI及Masonry
  * storyboard
* 调试
  * dealloc
  * profile(CMD + I)
    * leaks
  * 
* 音视频
  * 音频播放(AVPlayer)
    * 音频采集
  * 视频播放(AVPlayer, ijkplayer)
    * 视频的采集
* IM
  * leancloud
  * 短连接(NStimer)
# windows 10 入门者开发教程
windows 10 开发者教程 （XAML/c#）

这是 windows 10 入门者开发教程， 不管你是有经验的开发者还是初学者，你都能够在这个课程中学到东西。如果你希望看一些更快速的教程可以看[面向 IT 专业人员的 Windows 10 入门指南](https://mva.microsoft.com/zh-cn/training-courses/-it-windows-10--10629)。这个教程只需要你了解基本的 c# ，如果你没有的的话，可以看这里：[C# Fundamentals for Absolute Beginners](https://mva.microsoft.com/en-us/training-courses/c-fundamentals-for-absolute-beginners-8295?l=lQifIGYy_5004984382)（没有中文版）

这个课程可以分成两个重要的部分，第一部分会教你构建一些基本的 app 的技巧。第二个部分你将会做四个完整的 app：发声卡（soundboard），天气（weather），一个唱片封面连连看（album cover matching game），还有一个探索英雄（hero explore） app。我们推荐刚开始的同学从头开始学。如果你已经有基础了，我们推荐你直接开始看下面的这些课程：

1. 发声板（从第 49 集开始）这个教程中的第一个参考 app，它可以在点击磁贴的时候发出各种声音。UWP 发声版 app 可以让用户通过声音的种类来过滤选项，也可以让用户通过搜索来找到想要的声音。这个 app 练习数据绑定，应用多媒体（声音），拖拽，以及在 windows 商店中发布 app 的过程。
2. 天气（从第 57 集开始）这是第二个教程中的参考 app。这个 app 主要训练开发者发送网络请求，以及从第三方网络资源收集信息的能力，还要解码从网络收到的 JSON ，利用地理位置 api，以及利用手机模拟器的地图和位置功能来调试地理位置等等
3. 唱片封面连连看（从第 63 集开始）第三个例子训练你如何进入文件夹比如“文档”，“图片”，“音乐” 之类。这个 app 遍历一遍一个文件夹来找到所有的 .mp3 文件，读每一个文件的元数据（meta data）包括唱片集画面，并且随机播放歌曲。这个例子中大量应用 ObservableCollection（可观察集），数据绑定以及数据模板。这个 app 展示了 storyboard 的应用方法，比如利用它来停止以及开始音乐，还可以用来倒计时，来做游戏中的逻辑以及分数。还有进度条的高级使用方法等等。
4. 探索英雄（从第 71 集开始）这是最后一个例子。它可以让用户通过漫威的 api 来看漫威宇宙中的超级英雄。这个 app 通过做一个 MD5 哈希的公钥和私钥来发送并且验证互联网请求。这个 app 中也要解码 JSON，以及如何通过失误处理（exception handling），async，await，以及 Task 来处理不可避免的网络请求失败。这个应用也会大量应用 ObservableCollection 将最终结果可视化。最后，这个 app 展示了利用小娜控制 app （cortana integration）是多么的容易。
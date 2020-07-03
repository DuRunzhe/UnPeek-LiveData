# Event-LiveData

很高兴见到你！

Event-LiveData 主要用于 页面通信（如事件回调）等场景，避免 "数据倒灌" 现象的发生，

在发布的 1.1.0 版本中，通过创意性的设计：延迟清理消息，来一举解决三个问题：

1. 分发事件给多个观察者时，不会因第一个观察者消费了而直接置空

2. 时间到了，content 能自动被清理

3. 得以在维持低入侵的、遵循开闭原则的前提下，实现上述两个需求

`implementation 'com.kunminx.event:eventlivedata:1.1.0'`


Copyright © 2020 KunMinX

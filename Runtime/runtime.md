1.https://www.jianshu.com/p/6ebda3cd8052(蛮详细的)
  1. 介绍了 `runtime`
  2. `runtime` 消息传递简介
  3. 类对象 `objc_class`
  4. Method(`objc_method`)
  5. SEL(`objc_selector`)
  6. `IMP`
  7. 类缓存(`objc_cache`)
  8. Category(`objc_category`)
  9. Runtime消息转发, 无论是实例方法还是类方法都会有三次机会
  10. Runtime应用
  
    * 关联对象(Objective-C Associated Objects)给分类增加属性
    * 方法魔法(Method Swizzling)方法添加和替换和KVO实现
    * 消息转发(热更新)解决Bug(JSPatch)
    * 实现NSCoding的自动归档和自动解档
    * 实现字典和模型的自动转换(MJExtension)

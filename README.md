## 开启功能

```
func application(_ application: UIApplication, didFinishLaunchingWithOptions launchOptions: [UIApplicationLaunchOptionsKey: Any]?) -> Bool {
        
        DzyKeyBoardManger.default.enable = true
       .
       .
       .
        return true
}
```

## 若iOS11以后部分界面无法正常移动为安全区域的问题

请设置如下属性
```
scrollView.contentInsetAdjustmentBehavior = .never
```
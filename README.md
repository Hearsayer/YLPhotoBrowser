# YLPhotoBrowser
A lightweight picture browsing framework
一个轻量级图片浏览器，自定义转场动画，支持左右翻页，使用极其简单

![image](https://github.com/Hearsayer/YLPhotoBrowser/blob/master/YLPhotoBrowser.gif)

#### Podfile

To integrate YLPhotoBrowser into your Xcode project using CocoaPods, specify it in your `Podfile`:

```ruby
platform :ios, '8.0'
use_frameworks!
target 'TargetName' do
pod 'YLPhotoBrowser'
end
```


Then, run the following command:

```bash
$ pod install
```
## How to use

1、实例化PhotoBrowserController控制器
```swift
public class PhotoBrowserController: UIViewController {
    
    ///  selectedIndex: 选中图片索引， urls：url数组， parentImageViews：图片数组
    public init(selectedIndex: Int, urls: [String], parentImageViews: [UIImageView])
}
```
2、模态弹出

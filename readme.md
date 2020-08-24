### widget位置大小

- https://juejin.im/post/5c7de33cf265da2d864b5c6f

### widget传值的几种方式

- https://juejin.im/post/5d4bb76ef265da039b248592#heading-6

### NestedScrollView

- https://juejin.im/post/5cdd038cf265da0385581e60

### 各种动画

- https://juejin.im/post/5cd29423518825356a1add06

### 状态栏的颜色

- https://juejin.im/post/5d4949eff265da03a31d1f89

### Toast封装

- https://juejin.im/post/5c19c07c51882520f278524a
- https://juejin.im/post/5c20cc086fb9a04a016457e2

### 默认appBar高度

- https://blog.csdn.net/u013034413/article/details/82629944

### 设置appBar高度

- https://stackoverflow.com/questions/51089994/flutter-setting-the-height-of-the-appbar

### ListView回弹效果

- https://stackoverflow.com/questions/52710761/how-to-change-the-color-of-the-overscroll-glow-effect-of-listview-in-flutter

### 移除ListView中的safeArea

```dart
Widget build(BuildContext context) {
    return ListView(
        padding: EdgeInsets.zero, // 关键代码
        children: <Widget>[
            Container(
                color: Colors.red,
                height: top,
            ),
        ],
    );
}
```



### overlay高级设置

- https://medium.com/saugo360/https-medium-com-saugo360-flutter-using-overlay-to-display-floating-widgets-2e6d0e8decb9

### InheritedModel

- https://medium.com/flutter-community/flutter-widget-guide-inheritedmodel-widget-in-5-mins-or-less-a2b0dd8beb43

### 获取图片的宽度高度

- https://stackoverflow.com/questions/44665955/how-do-i-determine-the-width-and-height-of-an-image-in-flutter
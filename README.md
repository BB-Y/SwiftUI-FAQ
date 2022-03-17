# SwiftUI-FAQ
1.iOS14+ 键盘出现导致视图上移问题
    https://stackoverflow.com/questions/65701064/swiftui-ios14-disable-keyboard-avoidance
    https://github.com/V8tr/KeyboardAvoidanceSwiftUI
2.如何在 SwiftUI 中创建多行 TextField？
https://stackoverflow.com/questions/56471973/how-do-i-create-a-multiline-textfield-in-swiftui

3. iOS13，iOS14 text 有时会出现布局错误，使用 .fixedSize(horizontal: false, vertical: true)通常可以修复
快崩溃了，查了一个多小时，有个页面在 iOS13下 scrollview 莫名其妙向下偏移了几十像素，最后发现是item里面的文字 不换行导致的，在 iOS15里就没事


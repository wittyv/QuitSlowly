# Quit Slowly Apps
基于原来作者的版本，进行了修复，并更名为QuitSlowly.app 

## fix-m5-macos26-compatibility
* 1、崩溃报告所示的应用卡死（主线程在启动阶段永久阻塞的问题）；
* 2、无法开机自启（登录项注册失败）；
* 3、Dock 右键菜单显示"应用程序没有响应"，"隐藏"无效，只能强制退出；
* 4、新增弹窗设置，可以设置开机自启动勾选；
* 5、新增弹窗设置，可以设置菜单栏是否显示勾选；
* 6、新增弹窗设置，可以设置退出的时间长度（0.5-10s）均可滑动设置；
* 7、提供新的logo图标，支持深色模式，符合macos26整体视觉。

![Preview](./img/image.png?raw=true "QuitSlowly.app preview")
![Preview](./img/preview.gif?raw=true "QuitSlowly.app preview")
![Preview](./img/logo.png?raw=true "QuitSlowly.app preview")
A macOS app that adds a global delay of 1 second to the Cmd-Q shortcut. In
other words, you have to hold down Cmd-Q for 1 second before an application
will quit.

When the delay is active, an overlay is drawn at the center of the screen.

## Why?

A quick search for 'command q' on Google revealed these insights:

* "have you ever accidentally hit ⌘Q and quit an app"
* "how to disable command-Q"
* "Command-Q is the worst keyboard shortcut ever"
* "ever hit Command-Q instead of Command-W and lost all of your open web pages in Safari?"

... and many more similar sentiments.

Some proposed solutions include:

* remapping Cmd-Q to do something else
* changing the application quit keyboard short to use another keybinding

This app implements the same approach as Google Chrome's "Warn Before Quitting"
feature, except it is now available on every app!

## Download & Install

Pre-built binaries can be downloaded from the releases page.

Unzip, drag the app to Applications, and then run it. You can optionally
choose to automatically start the application on login.

## License

```
QuitSlowlyApps

Copyright (C) 2026 witty

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License along
with this program;
```

# React-Native

1.react-native安装：
  1.$brew update && brew doctor
    $xcode-select install
  
  2.$brew install watchman
  3.$brew install flow
  4.$npm install react-native-cli -g 全局范围安装

2.配置adnroid开发环境:
  1.$brew install android-sdk
    $vi ~/.bash_profile
    +export ANDROID_HOME=/usr/local/opt/android-sdk
    
    $android 打开android sdk 管理工具，安装Android6.0，Extras:Android Support Repository,Android Support Library,Intel x86 Emulator Accelerate(...)
    
    $brew info android
    $cd /usr/local/Cellar/android-sdk/24.3.4
    $cd /extras/intel
    $open ./
    安装IntelHAXM...dmg
    $android avd 打开android模拟器
    
  3.初始化项目
    $react-native init projectName 在当前目录中新建项目
    $atom projectName
    
  4.运行项目
  Android
    打开模拟器  $android avd ;  $emulator @avdName
    react-native run-android
    F2:开发快捷菜单
  IOS
    项目文件下 ios/projectName.xcodeproj
    
  5.
    
    
    
    
    
Command + K 清屏
Command + T 新建标签
Command +W  关闭当前标签页
Command + S  保存终端输出
Command + D  垂直分隔当前标签页
Command + Shift + D 
水平分隔当前标签页
Command + shift +  {或}
向左/向右切换标签
    
    
    
    


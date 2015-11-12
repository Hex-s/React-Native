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
    
    
    


# Utils
android 各种小功能工具库

#引入
```
    compile 'com.dsk:utils:1.0.1'
```
#使用
在自定义Application中初始化
```
    LUtils.initialize(this);
```
方法介绍
```
    LUtils.log(String msg); // 打印日志
    LUtils.log(String tag, String msg); // 打印自定义tag的日志
    LUtils.toast(CharSequence text); // 吐司
    LUtils.toast(@StringRes int resId); // 吐司
    LUtils.toastLong(CharSequence text) // 长时间吐司
    LUtils.toastLong(@StringRes int resId) // 长时间吐司
    LUtils.getPreferences(); // 获取Preferences
    LUtils.getScreenWidth(); // 获得屏幕宽度
    LUtils.getScreenHeight(); // 获得屏幕高度
    LUtils.dp2px(float dpVal); // dp转px
    LUtils.openKeyboard(EditText editText); // 打开软键盘
    LUtils.closeKeyboard(EditText editText); // 关闭软键盘
    LUtils.isNetWorkAvilable(); // 检测是否有网络
    LUtils.getAppVersionCode(); // 取APP版本号
    LUtils.getAppVersionName(); // 取APP版本名
```
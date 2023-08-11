# .vscode-settings.json

## Flutter Mac 1.25.0-4.0.pre

```json
{
	"dart.env": {
		"PAtH":"${env:PATH}"
	},
	"dart.flutterSdkPath": "/Users/zhangyu/Documents/flutter/flutter_1.25.0-4.0.pre",
	"dart.sdkPath": "/Users/zhangyu/Documents/flutter/flutter_1.25.0-4.0.pre",
	"terminal.integrated.env.osx": {
		"JAVA_HOME": "/Users/zhangyu/Library/Java/JavaVirtualMachines/corretto-1.8.0_382/Contents/Home",
		"ANDROID_HOME":"/Users/zhangyu/Library/Android/sdk",
		"FLUTTER_ROOT": "/Users/zhangyu/Documents/flutter/flutter_1.25.0-4.0.pre/bin",
		"PATH":"${JAVA_HOME}:${ANDROID_HOME}/cmdline-tools/latest/bin:${FLUTTER_ROOT}"
	}

```

## Flutter Mac 3.13.0-3.0.pre.20

```json
{
	"dart.flutterSdkPath": "/Users/zhangyu/Documents/flutter/flutter",
	"dart.sdkPath": "/Users/zhangyu/Documents/flutter/flutter",
	"terminal.integrated.env.osx": {
		"JAVA_HOME": "/Applications/Android Studio.app/Contents/jbr/Contents/Home/bin",
		"ANDROID_HOME":"/Users/zhangyu/Library/Android/sdk",
		"FLUTTER_ROOT": "/Users/zhangyu/Documents/flutter/flutter/bin",
		"PATH":"${JAVA_HOME}:${ANDROID_HOME}/platform-tools"
	}
}
```

## Flutter Windows 1.25.0-4.0.pre

1. Write the `settings.json`
```json
{
  "dart.flutterSdkPath": "C:\\flutter\\1.25.0-4.0.pre",
  "dart.devToolsLocation": "external",
  "dart.devToolsReuseWindows": false
}
```

2. Download the android studio
[android studio 3.0](https://developer.android.com/studio/archive?hl=en)

3. Set the android studio dir in command line
```cmd
flutter config --android-studio-dir=<directory>
```
[Install Android Studio](https://docs.flutter.dev/get-started/install/windows#android-setup)
* Important The specified version of Flutter requires the use of the specified version of Android Studio (Java version)

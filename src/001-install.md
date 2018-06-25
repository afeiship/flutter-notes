# install
> Only for IOS verions.(Android not test)

## commands:
1. clone code:
```shell
git clone -b beta https://github.com/flutter/flutter.git
```

2. export some env var(CAN USE: ushell-module-flutter):
```shell
# 国内用户需要设置
export PUB_HOSTED_URL=https://pub.flutter-io.cn;
# 国内用户需要设置
export FLUTTER_STORAGE_BASE_URL=https://storage.flutter-io.cn;
export PATH=`pwd`/flutter/bin:$PATH;
```

3. flutter doctor:
```conf
# 运行以下命令查看是否需要安装其它依赖项来完成安装：
flutter doctor
```
4. create a project
```shell
flutter create my-project
```

5. open a simulater & run project
```shell
cd my-project
open -a Simulator
flutter run
```
6. hot reload:
```conf
1. In termianl
2. input `R`
```

## resouces:
+ https://flutterchina.club/setup-macos/
+ https://yq.aliyun.com/articles/547695
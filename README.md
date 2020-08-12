# CLang

### 编译成可执行文件
* clang -fobjc-arc -framework Foundation hello.m -o nihau
### 写成c++文件
* clang -rewrite-objc hello.m
* clang -x objective-c -rewrite-objc -isysroot /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform/Developer/SDKs/iPhoneSimulator.sdk xxxxx.m

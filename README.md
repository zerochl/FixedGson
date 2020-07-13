## FixedGson
修复Gson的部分bug，例如object序列化与反序列化导致int类型变double类型的问题
Fixed some bugs in gson, such as object serialization and deserialization causing int type to change to double type
## 使用方法（Usage method）
```
allprojects {
  repositories {
    ...
    maven { url 'https://jitpack.io' }
  }
}
dependencies {
  implementation 'com.github.zerochl:FixedGson:2.8.0.0'
}
```

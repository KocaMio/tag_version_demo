# Versioning
---

## Format
```
v[major].[minor].[build]
```
- major: 功能新增無法向下相(對應APP強制更新版號)
- minor: 功能新增可向下相容(API功能上線)
- build: 功能修復可向下相容(API功能修復)

## Example
第一版聊天系統
```
v1.0.0
```

新增文字顏色功能
```
v1.1.0
```

修正文字顏色錯誤
```
v1.1.1
```

第二版加入視訊功能
```
v2.0.0
```


## 參考文獻
1. [semver.org](https://semver.org/lang/zh-TW/)
2. [Git基礎-標籤](https://git-scm.com/book/zh-tw/v2/Git-%E5%9F%BA%E7%A4%8E-%E6%A8%99%E7%B1%A4)
3. [Git 版本控制系統 - 使用標籤為特定版本號做標記](https://awdr74100.github.io/2020-04-28-git-tag/)

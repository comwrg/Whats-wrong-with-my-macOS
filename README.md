# What's wrong with my macOS

## cores
https://apple.stackexchange.com/questions/215410/os-x-el-capitan-cores-directory-taking-up-a-lot-of-space

## 项目“ ”已被 macOS 使用，不能打开。
根源是macOS的扩展属性
```
cp -X ...
```
xattr只会生效一次， 下次再插上还是那样子

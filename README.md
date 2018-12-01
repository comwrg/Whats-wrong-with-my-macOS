# What's wrong with my macOS

## cores
https://apple.stackexchange.com/questions/215410/os-x-el-capitan-cores-directory-taking-up-a-lot-of-space

## 项目“ ”已被 macOS 使用，不能打开。
根源是macOS的扩展属性
```
cp -X ...
```
xattr只会生效一次， 下次再插上还是那样子

## tree 乱码
```
tree -N
```
https://www.jianshu.com/p/52a4cedcfea0

## sleepimage
close hibernatemode
```
sudo pmset -a hibernatemode 0
```
show System-wide power settings
```
pmset -g
```

## iterm2 换行
https://apple.stackexchange.com/questions/90392/disable-line-wrapping-for-output-in-the-terminal/210666#210666

## virtual memory
https://apple.stackovernet.com/cn/q/15177

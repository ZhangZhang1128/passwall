#### 使用
一键命令
```yaml
sed -i '$a src-git zzpasswall https://github.com/ZhangZhang1128/passwall' feeds.conf.default


#### 注意
编译新版Sing-box和hysteria，需golang版本1.20或者以上版本 ，可以用以下命令
```yaml
pushd feeds/packages/lang
rm -rf golang && svn co https://github.com/openwrt/packages/branches/openwrt-23.05/lang/golang
popd
```


# 利用github action编译 [@cdle](https://github.com/cdle/jd_study.git) 大佬的JDC
-根据自己的系统选择对应的JDC
-pin1&pin2为管理账号，对应的京东账号扫码可以打开管理界面。
-JDC默认端口为8080
# V4
```text
chmod 777 JDC
```
```text
./jdc -v4 配置文件路径 -m pin1&pin2
```
```text
nohup ./JDC &
```
# QL
```text
chmod 777 JDC
```
```text
./JDC -p JDC端口 -qla 青龙登录地址  -qlp 青龙登录密码 -qlu 青龙登录用户名 -m pin1&pin2
```
```text
nohup ./JDC &
```
# References:
- [@cdle](https://github.com/cdle/jd_study.git)

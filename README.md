## 使用方法一

1. 下载源码
```bash
https://github.com/r1is/Magisk_burpsuite_cert.git
```
2. 进入`Magisk_burpsuite_cert`文件夹，并使用zip打包
```bash
cd Magisk_burpsuite_cert
find ./ -name ".DS_Store" -depth -exec rm {} \;
 zip -r Magisk_moudle_burpsuite_crts.zip . -x ".DS_Store" -x "README.md" -x ".gitignore"
```
3. 将2中生成的 **`Magisk_moudle_burpsuite_crts.zip`** 上传到安卓手机
例如：
```bash
adb push Magisk_moudle_burpsuite_crts.zip /sdcard/
```
4. 在 magisk 模块中安装
<img width="240" alt="image" src="https://user-images.githubusercontent.com/21257485/214491097-96b7d95f-7f7c-447f-85ee-b6e646163f78.png">

## 使用方法二
直接从 **`releases`** 页面下载 `Magisk_moudle_burpsuite_crts.zip`
上传到手机，再用 Magsik 模块进行安装 
  
  
`https://github.com/r1is/Magisk_burpsuite_cert/releases/download/2022.8.3/Magisk_moudle_burpsuite_crts.zip`

## 效果图
<img width="240" alt="image" src="https://user-images.githubusercontent.com/21257485/214492353-cf53ef41-0542-4f89-9c5e-2188a109190a.png">


## 微信公众号
<img width="328" alt="image" src="https://user-images.githubusercontent.com/21257485/211754137-a016af45-6725-46d1-b198-85eaac2b8a48.png"><img src="https://user-images.githubusercontent.com/21257485/211754284-829f1a24-c23b-46ff-a3f8-70fc81c409d6.png" width="250">

# Windows Longhorn build 3718 Multilingual User Interface Pack
### 为您的 Windows Longhorn build 3718 添加中文（简体）等语言！
由于 Git 不支持在 Code 部分放置太多文件，而文件较多，因此源码使用压缩包格式上传到 Release 处。

编译方法：
1. 从 Release 处下载源代码。  
2. 从 files.jrsoftware.org/is/5/innosetup-5.6.1-unicode.exe 下载 Inno Setup 5.6.1 Unicode 安装包，并安装它（部分其他版本和非 Unicode 版本也行，但不建议），勾选安装 Inno Setup Preprocessor。
3. 打开 installer.iss 文件，去除 SignTool=winbetamui 和 SignedUninstaller=yes 这两行，然后编译 installer.iss 文件，编译完成的文件在源代码根目录下的 compiled_installer 文件夹。

#### 反馈
前往 @Nicrozoft 的产品交流群反馈：teams.live.com/l/invite/FBA7VfY_z6_yTxPxQM

WinBetaMUI Team 管理员邮箱（不分先后）: 
 WinBetaUser: markta111@outlook.com、[备用]bobday001@outlook.com   
 Nicrozoft: haha666_666@outlook.com 、[备用]haha666_1@outlook.com  
 AndyChung123: chunghuenpang@hotmail.com  

感谢支持！

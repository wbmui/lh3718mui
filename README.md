# Windows Longhorn build 3718 Multilingual User Interface Pack
### 为您的 Windws Longhorn build 3718 添加中文（简体）语言！
由于 Git 不支持在 Code 部分放置太多文件，而文件较多，因此源码使用压缩包格式上传到 Release 处。

编译方法：
1. 从 https://winbetauser.github.io/files/lh3718mui-src-latest-release.zip （仅正式版）或 Release 处下载源代码（不建议下载测试版，因为它可能不稳定）。  
2. 从 https://files.jrsoftware.org/is/5/innosetup-5.6.1-unicode.exe 下载 Inno Setup 5.6.1 Unicode 安装包，并安装它（5.5.6 - 5.6.0 和非 Unicode 版本也行，但不建议）。记得勾选安装 Inno Setup Preprocessor！  
3. 打开 installer.iss 文件，去除 SignTool=winbetamui 和 SignedUninstaller=yes 这两行，然后编译 installer.iss 文件，编译完成的文件在源代码根目录下的 compiled_installer 文件夹。

#### 反馈
粉丝群 & 产品交流群: https://teams.live.com/l/invite/FEAiNqXRjDpEszT-gQ  

邮箱: 
 WinBetaUser (团队队长): markta111@outlook.com  
 Nicrozoft: haha666_666@outlook.com 、[备用]haha666_1@outlook.com  
 AndyChung123: chunghuenpang@hotmail.com  

WinBetaMUI 产品反馈: https://forms.office.com/r/YEzZmF2Lv9

感谢支持！

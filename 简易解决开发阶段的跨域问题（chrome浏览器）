chrome可以禁用web安全机制，这样浏览器就不会再进行跨域检查

命令行如下：

chrome --disable-web-security --user-data-dir=/home/wzc/Documents/chrome-profile

在windows下可以通过创建快捷方式简易使用

ubuntu下稍微麻烦点：

vim ~/.local/share/applications/chrome-dev.desktop

然后输入如下内容：

[Desktop Entry]

Name=Chrome-不安全模式

Comment=禁用了网页安全机制的Chrome

Exec=/opt/google/chrome/chrome --disable-web-security --user-data-dir=/home/wzc/Documents/chrome-profile

Icon=google-chrome

Terminal=false

Type=Application

StartupNotify=true

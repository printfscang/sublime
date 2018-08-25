# sublime在线插件安装
[sublime download](https://www.sublimetext.com/3)

1. 敲快捷键 ctrl+(tab键上面的符号)  调出命令窗口，输入下列语句   
```
import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())
```
2. 查看是否安装成功，当菜单栏“preference”下拉出现“package control”时则成功
3. 敲快捷键 `ctrl+shift+p` ,在弹出的输入框中输入 `install package` ,回车
4. 等候一下在再次弹出的输入框中输入要安装的插件名称即可

#### 推荐链接
[使用sublime插件合集](https://blog.csdn.net/jianhua0902/article/details/43761899)<br/>
[ChineseLocalization 汉化包插件]()<br/>
[ColorPicker 颜色选择器]()<br/>
[Color Highlighter]()<br/>

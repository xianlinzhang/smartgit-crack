smartgit 19 之前的版本，大家都知道，就是删除settings.xml文件。

Windows： %APPDATA%\syntevo\SmartGit\

从上面路径的版本号对应文件夹里，删除settings.xml文件


但是升级到19.1后，会发现，没有了setting.xml，经过对比，我发现多了的文件里的preferences.yml文件内容和原来的settings.xml内容相近：


删掉preferences.yml文件来重选非商业。

作为工程师，不可能要每个月都手动去删除文件，故写了个batch脚本做定时任务，去删除
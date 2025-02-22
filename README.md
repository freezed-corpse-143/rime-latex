## Rime

1. 官网[https://rime.im/](https://rime.im/)下载，安装

2. 右键点击输入法图标，在程序文件夹下点击`WeaselSetup.exe`选择自定义的用户文件夹，点击修改文件夹

3. 官网[https://github.com/iDvel/rime-ice/releases](https://github.com/iDvel/rime-ice/releases)下载full.zip，解压到rime程序的用户文件夹中。

4. 切换输入法到雾凇拼音。

5. 在用户目录的`default.custom.yaml`中增加以下属性：

   ```yaml
   patch:
     menu/page_size: 10
   ```

   点击rime，开始重新部署。

6. 在用户目录的`rime_ice.schema.yaml`中，设置：

   ```YAML
   melt_eng:
     enable_completion: true
     initial_quality: 1.2
   ```

   点击rime，开始重新部署。

7. 将`latex_command.txt`中的内容复制到用户文件夹下`en_dicts\en.dict.yaml`文件的末尾。点击rime，开始重新部署。

8. `ctrl`+`~`快捷键，切换到`Easy English`。以`l`+latex命令，开始联想。具体命令参考`latex_command.txt`
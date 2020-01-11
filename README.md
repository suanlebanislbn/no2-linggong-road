## 一个学生时代未完成的战棋类RPG游戏

这是我在2013年基于Qt开发的一个战棋类RPG游戏，处于未完成状态。

<img style="width: 50%; height: 50%" src="https://raw.githubusercontent.com/blindpirate/no2-linggong-road/master/screenshots/mainwindow.png" />

![dialog](https://raw.githubusercontent.com/blindpirate/no2-linggong-road/master/screenshots/dialog.png)
![status](https://raw.githubusercontent.com/blindpirate/no2-linggong-road/master/screenshots/status.png)
![scene](https://raw.githubusercontent.com/blindpirate/no2-linggong-road/master/screenshots/scene.png)
![battle](https://raw.githubusercontent.com/blindpirate/no2-linggong-road/master/screenshots/battle.png)

## How to build

1. 安装Qt。我现在用的版本是Qt 5.14。
2. 在QtCreator中点击Run/Debug。第一次会弹出错误对话框，别紧张，这是正常的。
3. 将项目文件夹下的data目录拷贝到可执行程序的目录下。注意，如果是macOS，需要拷贝到`{构建目录}/lgl.app/Contents/MacOS/`下。
4. 再次点击Run/Debug。现在应该可以运行了。

# A-Gift-to-My-Lover


## 演示

参见[演示页面](https://jinczhang.github.io/Gift-for-my-lover/src/index/html)

## 使用方法

- check out 这个代码库；如果不会用git，也可以直接下载整个代码库的压缩包然后解压；
- 按需要，修改 `src/config.js` 文件中的配置；文件中有中文注释，很容易看懂；
- 打开 `src/index.html` 网页可以看到效果；
- `src/images`中保存的图片是幻灯片轮流播放的图片，其中"start.jpg"是第一张图片；"end.jpg"是最后一张；其他中间的图片，文件名从`1.jpg`开始依次编号；注意文件后缀必须为`.jpg`，
也就是说只支持 JPEG 格式的图片；添加或减少图片数目后，必须修改`src/config.js`中的`IMAGE_COUNT`变量值；
- `src/musics`中保存的音乐是幻灯片播放时的背景音乐，文件名从`1.mp3`开始依次编号；注意文件后缀必须为`.mp3`，
也就是说只支持 MP3 格式的音乐；添加或减少音乐数目后，必须修改`src/config.js`中的`MUSIC_COUNT`变量值；
- `src/rename_files.sh`脚本可以批量重命名当前目录中的文件，文件名以数字编号，从1开始，文件后缀依然为原文件后缀。此工具可用于重命名大批量的图片文件。

## 支持的浏览器

- Chrome: 45.0.2454.99 测试通过，所有功能正常；
- Firefox: 40.0.3 测试通过，所有功能正常；
- Safari: 9.0.1 测试通过，所有功能正常；
- IE: 尚未测试，不过至少已知全屏功能是不支持的；

强烈建议使用最新版的Chrome以获得最佳的浏览效果。

## 致谢

此项目，使用了下述资源、代码和工具，在此一并表示感谢！

- 幻灯片播放代码来自于 Jay Salvat 的 vegas 项目：
  https://github.com/jaysalvat/vegas
- 音乐播放代码来自于 Jay Salvat 的 buzz 项目：
  https://github.com/jaysalvat/buzz
- 带背景音乐的幻灯片播放的设计思路来自于这篇 Jay Salvat 的这篇博文：
  http://tympanus.net/codrops/2011/07/05/fullscreen-slideshow-with-html5-audio/
- 全屏显示的代码来自于下面的博文：
  http://johndyer.name/native-fullscreen-javascript-api-plus-jquery-plugin/
- 预载入幻灯片图像的代码思路来自下面的博文：
  http://www.inwebson.com/jquery/jpreloader-a-preloading-screen-to-preload-images/
- 预载入背景音乐的代码思路来自下面的答案：
  http://stackoverflow.com/questions/5313646/how-to-preload-a-sound-in-javascript

## 协议

本项目的代码遵循 [GNU General Public License v3.0](http://www.gnu.org/licenses/gpl.html)

本项目用到的各类图片，音乐资源收集自网络，仅供个人使用。若无意中侵犯了您的版权，请与本人联系，我会立即将其删除。

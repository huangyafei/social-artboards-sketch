# 一个快速加载社交媒体图片素材尺寸画板的 Sketch 插件

这是一个可以帮助设（yun）计（ying）师（miao）在 Sketch 中快速建立主流社交网络常见图片素材的 Artboard 的插件。

![](http://p1.bqimg.com/567571/9049043bf8fbd106.png)

## 安装

你可以通过 [这里](https://github.com/huangyafei/social-artboards-sketch-cn/releases) 下载此插件的最新版本进行安装。

1. 把插件的压缩包下载至电脑中，解压后进入文件夹，可以看到插件文件 `Social-Artboards-CN.sketchplugin`，双击安装。

2. 进入你的 Sketch 插件文件夹（一般来说路径类似 `.../com.bohemiancoding.sketch3/Plugins`），在这里你可以看到上一步安装的文件 `Social-Artboards-CN.sketchplugin`。

3. 新建一个文件夹（建议名为 `Social-Artboards-CN`），然后把 `Social-Artboards-CN.sketchplugin` 文件拖进去。

**提示：** `.sketchplugin` 文件必须放在某个文件夹中，不能直接放在 `Plugins` 文件夹。

## 初始化

安装完成后打开 Sketch，在 `Plugins` 菜单中选择 `Social Artboards CN` -> `Install Social Artboards CN`，或使用快捷键 `Alt + Crtl + I` 完成最终安装。


## 使用

安装完成后，在新建 Artboard（按快捷键`A`）时在右侧会出现一个名为 `Social` 的组，这里就是主流社交网络常见图片素材的预置 Artboard。

## 包含哪些社交网络图片尺寸？

包含以下平台的头像、主页封面、内容封面的图片尺寸：

- 微博
- 微信
- Twitter
- Facebook
- Google+
- Youtube
- Instagram
- Dribbble

## 更新

要更新这个插件，需要把 `~/Library/Application Support/com.bohemiancoding.sketch3` 中的 `artboard.plist` 文件删除，以达到重新安装或重新初始化自定义 Artboard 的目的。

**注意：** 这将会把你手动自定义添加的所有 Artboard 配置全部删除，务必慎重。
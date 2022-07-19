# Ventoy_theme
个人制作 Ventoy 主题，在 MIT License 下可以自由使用

主题预览可参考各文件夹内 `background.png` 文件

### 使用方法

复制主题文件夹和 `ventoy.json` 文件到 Ventoy U盘的 `ventoy` 目录下，修改 `ventoy.json` 文件第 9 行，改为类似如下形式：

```json
        "file": "/ventoy/lv69/theme.txt",
```

（替换“lv69”为你下载主题的文件夹名称，如 `hamidashi_asumi`）

如果需要调整分辨率适应显示器分辨率，请修改 `ventoy.json` 文件第 10 行：

```json
        "gfxmode": "1920x1080",
```

`1920x1080` 改为你需要的分辨率，当这里的分辨率不被显示器支持时，会使用 800x600 的安全分辨率，还请注意

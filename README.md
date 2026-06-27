# FFmpeg Minimal Build

精简版 FFmpeg 编译仓库，仅包含 H264 解码器。

## 使用方法

1. 点击 Actions 标签
2. 选择 "Build Minimal FFmpeg"
3. 点击 "Run workflow"
4. 等待编译完成（约 10 分钟）
5. 下载 artifacts

## 编译内容

- `avcodec-61.dll` - H264 解码器
- `avutil-59.dll` - 工具库
- `swresample-5.dll` - 重采样库

预计总大小: **10-15 MB**（相比完整版 98MB）

## 用于 x-adb 项目

下载后将文件复制到:
```
x-adb/windows/third_party/ffmpeg/
```

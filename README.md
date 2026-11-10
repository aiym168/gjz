# gjz · 工具站大全命令行

[工具站大全](https://wan.is-my.app/) 的免费命令行客户端：单个 Python 文件，只需要 Python 3.8+，没有第三方依赖。

## 安装

```bash
curl -O https://wan.is-my.app/cli/gjz.py
# 或者直接克隆本仓库
python3 gjz.py --help
```

## 用法

```bash
python3 gjz.py list                          # 列出所有免费工具
python3 gjz.py search 压缩                    # 搜索工具
python3 gjz.py video "<抖音/X/B站/快手分享链接>"  # 解析视频，输出无水印地址
python3 gjz.py download "<分享链接>" -o ./videos # 解析并下载最高清晰度视频
python3 gjz.py text 视频.mp4                  # 视频/音频转文字（保存 .txt 和 .srt）
python3 gjz.py script "<分享链接>"            # 视频拆解脚本：分镜表 + 关键帧 + 字幕
python3 gjz.py mp3 视频.mp4                   # 提取 MP3
python3 gjz.py cover 视频.mp4                 # 截取封面和关键画面
python3 gjz.py open 图片压缩                  # 在浏览器打开某个工具
```

## 其他接入方式

- 工具清单（JSON）：https://wan.is-my.app/api/tools.json
- OpenAPI：https://wan.is-my.app/api/openapi.json
- llms.txt：https://wan.is-my.app/llms.txt
- 说明页：https://wan.is-my.app/agent/

## 说明

- 全部功能免费，不需要注册。
- 视频解析结果仅供个人学习、收藏使用，请尊重原作者版权，不要用于商业用途或二次发布。
- 本项目以 MIT 许可证发布。

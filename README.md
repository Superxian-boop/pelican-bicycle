# 骑自行车的鹈鹕 · 动态 SVG

一个纯 SVG 的 2D 动画场景：一只鹈鹕骑着自行车向右行进。

- `index.html` — 动态版（车轮转动、双腿蹬踏、身体起伏、云朵飘移）
- `static.html` — 静态版

没有任何外部依赖，也没有构建步骤：HTML、CSS、SVG 和 SMIL 动画全部在单个文件里。
双腿的蹬踏动作由双连杆逆向运动学算出，每个踏板角度 45° 取一个关键帧，
所以脚始终贴在踏板上、腿长保持不变。

在线预览：https://superxian-boop.github.io/pelican-bicycle/

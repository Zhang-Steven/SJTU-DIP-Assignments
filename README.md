# 文件内容说明

| 文件      | 描述 | 
| :----:        |    :----:   | 
| LaneDetection.py      | Hough轨道检测+视频截取      | 
| videogenerate.py   | 视频拼接      | 
|./darknet| yolo行人检测|
|./darknet/src/image.c|yolo单目标识别修改文件|
|./darknet/start.sh|yolo批量处理图片脚本|
|./datasets/graph_processed|hough+yolo处理后的图像|
|./datasets/video_processed|视频重新拼接后的白天+夜晚的视频|
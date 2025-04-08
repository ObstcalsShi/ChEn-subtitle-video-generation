# ChEn-subtitle-video-generation

## prepare wemb and w4a
❤️done
download wemb and w4a in url https://youtube.iiilab.com/

## wemb and w4a to mp4
❤️done

use MediaMerger in py02m4awemb2mp4.py

python project is faster than 格式工厂

## split whole mp4 into lots of mp4 with one hour 
❤️done

[choose] splite video in 03split_whole_mp4_2

use Pr rather than 03split_whole_mp4_2.py because Pr is way moer faster than python project.

## prepare EnSRT
❤️done

开源的多语言语音识别（ASR）模型
this process need whisper, https://github.com/openai/whisper

use function SRT_generate in py04SRT_generate.py

## EnSRT to ChEnSRT using deepseekAPI
❤️done

about one hour for 0.7 yuan.

next plan, let AI check the black translated line and combine black line with right line in srt file.

## combine ChEnSRT and mp4 to ChEn-subtitle-video
❤️done

need new hyperparameters to decide subtitle_style

"""
subtitle_style = (
        "Fontname=Microsoft YaHei,"  # 字体
        "Fontsize=10,"  # 字号
        "PrimaryColour=&HFFFFFF&,"  # 主体颜色（白色）
        "Alignment=2,"  # 底部居中
        "MarginV=3"    # 从底部向上移动x像素 
        "BorderStyle=1"
        "Outline=0.5"   # 描边宽度，像素单位
        "Shadow=0"
    )
"""

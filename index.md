{% assign date = '2018/08/08' %}
{% assign youtube = 'S3CAGeeMRvo' %}
{% assign youtube_state = ':heavy_check_mark:' %}
{% assign title = '[自己紹介]はじめまして、湊あくあです!' %}
{% assign bili_title = 'Official' %}
{% assign bili_id = 'av36485935' %}

{% capture row %} | {% increment my_counter %} | {{ date }} | ![](https://i3.ytimg.com/vi/{{ youtube }}/maxresdefault.jpg) | {{ title }} | :x: | [{{ youtube_state | markdownify }}](https://www.youtube.com/watch?v={{ youtube }}) | [{{ bili_title }}](https://www.bilibili.com/video/{{ bili_id }}) | :x: | {% endcapture %}

| No | Date | Thumb | Title | Collab | Youtube | Bilibili | Archive |
| - | - | - | - | - | - | - | - |
{{ row }}
{% assign date = '2018/08/09' %}
{% assign youtube = 'mpAW5hC5o4w' %}
{% assign youtube_state = ':heavy_check_mark:' %}
{% assign title = 'いきなり大失敗!?私の全てがわかります![質問コーナー]' %}
{% assign bili_title = 'Official' %}
{% assign bili_id = 'av36546607' %}
{{ row }}
| 1 | 2018/08/08 | ![](https://i3.ytimg.com/vi/S3CAGeeMRvo/maxresdefault.jpg) | `[自己紹介]はじめまして、湊あくあです!` | :x: | [:heavy_check_mark:](https://www.youtube.com/watch?v=S3CAGeeMRvo) | [Official](https://www.bilibili.com/video/av36485935) | :x: | 

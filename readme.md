
## modulemap.json
> 未知

## video.txt
> 视频文件夹的路径

## modulestore.txt
> 视频对应的字幕文件

## course_info.csv
> 课程信息，开课时间

## videomap
> 学生看过的视频列表

## captionmap.json
> 视频对应的字幕文件

## docmap.json
> 文档编码

## vocabs.json
> 词语编码

## doc_words.json
> 字幕文件中词频

## topics.json
> 主题中的高权重词语

## doc_topics.json
> 文档在不同主题上的得分

## ancestor.csv
> 未知 祖先？ 课程之间的关系？

## access.txt
> 学生访问记录

## enrollment.txt
> 用户选课列表

## recommends.json
> 对应用户的推荐课程列表

## Roadmap

- 使用LDA对字幕中的词语进行主题识别
- 计算每个课程在主题上的得分
- 计算每个用户在主题上的得分
> 观看和查看简介两个操作，怎样结合使用

- 使用主题得分向量计算用户之间的相似度
- 找到最相似的TopN个用户，并找到他们相应最关注的TopM个课程
- 筛选该用户没有选过的课程，进行推荐
# NewsWebsite-crawler
非常通用的新闻网页正文和图片抓取

源代码在【陈鑫】代码基础上做了一些优化：https://github.com/amumu/cx-extractor

优化点:
1、网页gbk还是utf8格式更加精准
2、行列分布函数，不会只取一个最大封闭面积，在误差系数范围内的面积都会抽取出来。
3、增加图片抓取。在正文行列分布间隙中的图片会抓取出来。
4、增加了一些过滤。尤其是网页标签头文字等。

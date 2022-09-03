{% dplayer "url=http://home.ustc.edu.cn/~mmmwhy/GEM.mp4"  "pic=http://home.ustc.edu.cn/~mmmwhy/GEM.jpg" "loop=yes" "theme=#FADFA3" "autoplay=false" "token=tokendemo" %}
<embed autostart="true" hidden="true" loop="true" src="http://ois5yh1xg.bkt.clouddn.com/%E5%8D%A2%E5%86%A0%E5%BB%B7%E4%B8%80%E7%94%9F%E6%89%80%E7%88%B1.mp3"></embed>




|左对齐|居中对齐|右对齐|
|:-    |:------:|-:|
|左对齐列|居中对齐列|右对齐列|
|1|2|3|


```flow
st=>start: 开始框
op=>operation: 处理框
cond=>condition: 判断框(是或否?)
sub1=>subroutine: 子流程
io=>inputoutput: 输入输出框
e=>end: 结束框
st->op->cond
cond(yes)->io->e
cond(no)->sub1(right)->op
```

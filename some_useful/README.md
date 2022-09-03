<img src="https://v1.jinrishici.com/all.svg" style="max-width:100%;">


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

About git log 关于查看commit
-------
参考网址：https://www.atlassian.com/git/tutorials/git-log/
<br/>
<br/>
####发现最近的三个commit<br/>
```
   git log -3
```
<br/>
####某时间段内的commit<br/>
```
   git log --after="2014-7-1" --before="2014-7-4"
```
<br/>
####查找某人的commit<br/>
```
   git log --author="John"
   git log --committer="John\|Mary"
```
<br/>
####根据内容查找commit<br/>
```
   git log -S"Hello, World!"
```
<br/>
####根据文件查找commit<br/>
```
   git log -- foo.py bar.py
```
<br/>

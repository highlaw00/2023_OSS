### 3주차 git
### 이미지
![kaulogo](/img/kau/kau.png)
### 링크
[LMS](https://lms.kau.ac.kr/login.php)
### ProGit 링크
[ProGit](https://git-scm.com/book/ko/v2)
#### 주요 git 명령어
* add: 파일을 추적 대상으로 포함시킬 때, 또는 커밋 대상으로 포함시킬 때 사용
	* 예) git add
* commit
* branch
* merge
* status
* log
---
### 2주차 숙제
```bash
#!/usr/bin/env bash
echo "----------"
echo "name :"
echo "XX"
echo
echo "----------"
echo "student id :"
echo 2019XXXXXX
echo "----------"
echo
echo "file path :"
path=$(find /home/kau2 -name "w2_homework.txt" 2> /dev/null)
echo $path
echo
echo "----------"
echo "line number :"
lines=$(cat $path | wc -l)
echo $lines
echo
echo "----------"
last=$(cat $path | tail -n 1)
echo "last line :"
echo $last
```

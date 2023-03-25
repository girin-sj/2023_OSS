# 2023_OSS
## 2023 OSS 수업

-----

### 3주차 git


### 이미지
![kau 로고](../img/image001.png "image001")


### 링크

[LMS](https://lms.kau.ac.kr/login.php)

#### ProGit 링크

[ProGit](https://git-scm.com/book/en/v2)

##### 주요 git 명령어
* add : 파일을 추적 대상으로 포함시킬 때, 또는 커밋 대상으로 포함시킬 때 사용
    * 예) git add <file name>
* commit
* git reset HEAD <file> : stage된 파일을 unstaged로 변경
* git checkout -- <file> : stage되어 있는 파일을 수정한 후 수정 전으로 되돌림
* branch
* merge
* status
* log
    * 예) git log --oneline --decorate --graph --all
* git push

-----
### 2주차 숙제
```bash
#!/bin/bash

name=" "
student_id=" "
file_path=$(find /home/kau2 -name "w2_homework.txt" 2>/dev/null)
line_number=$(cat $file_path|wc -l)
last_line=$(tail -n 1 $file_path)

echo "---------“
echo "name :"
echo "$name"
echo "---------"
echo "student id :"
echo "$student_id"
echo "---------"
echo "file path :"
echo "$file_path"
echo "---------"
echo "line number :"
echo "$line_number"
echo "---------"
echo "last line :"
echo "$last_line"
```

-----
## 마크다운
### 목록
#### 번호 있는 목록 : 내림차순 정렬
1. 첫번째
3. 세번째
2. 두번째

#### 번호 없는 목록 : *, -, +
* 첫번째
- 세번째
+ 두번째
-----
* 빨강
   * 녹색
      * 파랑

### 강조
*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
~~cancelline~~

# 2023_OSS
## 2023 OSS ���� 

-----
### 3���� git

### �̹���
![kau](./kau.png)


### ��ũ   
[LMS](https://lms.kau.ac.kr "�װ����б� ���ǰ����ý���")

#### ProGit ��ũ
[ProGit](https://git-scm.com/book/ko/v2 "git ����, �ѱ���")


##### �ֿ� git ��ɾ�
* add : ������ ���� ������� ���Խ�ų ��, �Ǵ� Ŀ�� ������� ���Խ�ų �� ���
    * ��) git add <file name>
* commit
* git reset HEAD <file> : stage�� ������ unstaged�� ����
* git checkout -- <file> : stage�Ǿ� �ִ� ������ ������ �� ���� ������ �ǵ��� 
* branch
* merge
* status
* log
    * ��) git log --oneline --decorate --graph --all

------
### 2���� ����

```bash
#!/usr/bin/env bash
echo "----------"
echo "name :"
echo "������"
echo

echo "----------"
echo "student id :"
echo "2020125015"


file_path=`find /home/kau2/ -name w2_homework.txt 2> /dev/null`
echo "----------"
echo
echo "file path :"
echo $file_path
echo

line_num=`wc -l $file_path | cut -c 1 -`
echo "----------"
echo "line number :"
echo $line_num
echo

echo "----------"
echo "lask line :"
tail -n 1 $file_path
```

## ��ũ�ٿ�
### ���
#### ��ȣ �ִ� ��� : �������� ����
1. ù��°
2. �ι�°
3. ����°

#### ��ȣ ���� ��� : *, -, +
* ù��°
- ����°
+ �ι�°
-----
* ����
  * ���
    * �Ķ�

### ����
*single asterisks*    
_single underscores_    
**double asterisks**    
__double underscores__    
~~cancelline~~    


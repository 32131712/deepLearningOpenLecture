[2018-09-29]
Linux Script �ۼ�, git bash ���� "./g" �� ����
+-------------------------------------------+[Start]
#! /bin/bash
git pull
git add --all .
if [ "$1" = "" ]
then 
	git commit -m "Commit at $(date +%Y%m%d)-$(date +%H%M)"
else
	git commit -m "$*"
fi
git push
+-------------------------------------------+[End]



[2018-09-11] all.bat ����
������� �� �ڵ����� CLI â ����
===============================
atom
cmd /k ".\tf36\Scripts\activate & prompt = $N/ó���ڵ�$G$G"
===============================

[��Ŀ�� ���]
>> git add --all .
>> git commit -m "Commit Memo"
>> git push

Ŀ�� �޽��� �ۼ���
Ÿ��: ����

Ÿ�� - feat(���), fix(����), dosc(����), style(���˺���,�����ݷ� ������), refa(ctor), test, chore(��Ű���Ŵ���)
������ ������� ����, �빮�� �ۼ�. �� 50��, ��ħǥX

��) fix: Fix Person Database

1. �ٿ�ε�  git-scm.com
��ġ�� Run Git and associated Unix tools from the Windows command-line ����

2. �ʱ�ȭ
>> git init
>> git config --global user.name "eventia"
>> git config --global user.email eventia@gmail.com

3.  ����(�������� ����) ��� : .gitignore
.gitignore ����
*.pyc
*~
__pycache__
myvenv
db.sqlite3
/static
.DS_Store


4. �⺻���
>> git status
>> git add --all .
>> git commit -m "My Project Commit"


5. github �� ����
>> git remote add origin https://github.com/eventia/my-first-blog.git

[������]>> git remote set-url origin https://github.com/eventia/my-first-blog.git

>> git push -u origin master
>> git push

6. pythonanywhere / github to other cloud
>> git clone https://github.com/<your-github-username>/my-first-blog.git
>> git pull

7. ���
[ó��]
>> git init
>> git config --global user.name "eventia"
>> git config --global user.email eventia@gmail.com
>> git add --all .
>> git commit -m "Commit Memo"
>> git remote add origin https://github.com/myid/myrepository.git
>> git push -u origin master

[�Ź�]
>> git add --all .
>> git commit -m "Commit Memo"
>> git push

[����ũ]
https://sujinlee.me/professional-github/
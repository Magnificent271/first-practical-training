# ��������� ��������� �� GIT


### ���� GIT ������� ssh ����, �� 


   ��������� ssh-agent
   
   `eval $(ssh-agent -s)`
   
   �����������  ���� ����� ssh
   
   `ssh-add /c/ssh/.ssh/id_ed25519`

### ������������������ �������� ������ Git ��� ���������� �������� �������:

1. ������������� �����������:
   
   `git init`
   
   ��� ������� ������ ����� ����������� Git � ������� ����������.
2. ���������� ������ � ������:
   
   `git add <����_�_�����_���_��������>`
   
   ��������, `git add .` ��������� ��� ����� � ���������� ����� � ������.
3. ���������� �������:
   
   `git commit -m "��������� � �������"`
   
   �������� ������� � ������������� ��������� � ���, ��� ���� ��������.
4. �������� ��������� �����������:
   
   `git status`
   
   ���������� ������� ��������� � ��������� ������ � �����������.
5. �������� ������� ��������:
   
   `git log`
   
   ���������� ������� �������� � ��������.
6. �������� �����:
   
   `git branch <���_�����>`
   
   ������ ����� �����.
7. ������������ �� ������ �����:
   
   `git checkout <���_�����>`
   
   ����������� �� ��������� �����.
8. ������� �����:
   
   `git merge <���_�����>`
   
   ������� ��������� �� ��������� ����� � ������� �����.
9. ���������� ��������� �����������:
   
   `git remote add origin <URL_�����������>`
   
   ��������� �������� ����������� � ��������� URL.
10. �������� ��������� � �������� �����������:
   
   `git push origin <���_�����>`
   
   ���������� ��������� �� ��������� ����� � �������� �����������.
11. ��������� ��������� �� ��������� �����������:
   
   `git pull origin <���_�����>`
   
   �������� ��������� �� ��������� ����������� � ���������� �� � ���������� �����������.



## ������ ������ � Git

Git � ��� ������������� ������� �������� ������, ������� ��������� ����������� ��������� � ������ � ������������ � ������� ��������������.

### �������� �������

#### HEAD
HEAD � Git � ��� ��������� �� ��������� ������-������ � �����, � ������� �� ���������. �� ����, HEAD ��������� �� ������� ������� ������, � ��� ������ ����� �������� (�������) HEAD ������������ �� ���� ����� ������.

#### ���
��� � Git � ��� ���������� �������������, ������� ������������� ������� �������. ���� ������������� ������������ ����� ������ ��������, ������� ������������ �� ������ ����������� �������. ��� ��������� ���������� ���������������� ������ ������ � ������������ ����������� ������.

#### ���
��� � Git � ��� ������� ���� �������� � �����������. �� ������ ����������� ��� � ������� ������� `git log`, ������� ������� ������ ���� �������� � �� ������, ��������, ������ � �����������.

#### ������ �����
������ ����� � Git ��������� �� ��� ������� ��������� ������������ �����������. ���� ����� ����� ��������� �������:
- ��������������� (untracked) � ���� �� ������������� Git;
- ���������� (modified) � ���� ��� �������, �� ��� �� �������� � ������;
- ��������������� (staged) � ���� �������� � ������ � ����� � �������;
- ������������ (committed) � ���� ��� ������������ � �����������.

### ������� ���������� �������

��� ���������� ������� ����� ��������� ����������� ��������, ����� ���������� ������� � ��������� ������� ���������:
1. **��������� � �������**: ��������� ������� ������ ���� ������� � ��������. ��� ������ ���������, ��� ���� ��������, ��� ������ �������.
2. **������ ������**: ������ ������ ��������� ������� ������ ���� �������� (�� ����� 50 ��������) � ��������� ���� ���������.
3. **������ ������**: ����� ������ ������ ������ ��������� ������ ���, � ����� ����� ��������� �������� ��������� (���� ����������).
4. **�������**: ��������� ��������� ������� � ������� � ��������� �������, ��������, ����������, �����������, ��������� � �. �.
5. **������������**: ���������� �������������� ������� ����� ���������� ��������� ��������, ����� ��� ���� ����� ��������� � ��������� ��� ���� ���������� �������.

������ ���������� �������:
```
�������� ������� ������� �������� ��������

��� ������� ��������� ������������ ������� �������� ��� ������ �����. ��� ��������� ������ ����� � �������� ��������� � ���������� ������� ��������.
```
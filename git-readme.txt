//���ɹ�Կ��˽Կ  ����SSH key
ssh-keygen  -t  rsa  -C "zgchang@126.com"
//�鿴��ȡ
ssh-rsa

//��������  ����ǩ��
git config --global user.name  "��"
git config --global user.email  "zg@126.com"

//�鿴״̬���鿴���������ݴ���״̬
git status


//����½����  �������������͵�github��
git push  origin master

//����   �Ѳֿ�����������
git clone http://gitee.com/zgchang/chris.git

//��ʼ�����Ŀ¼Ϊ�ֿ�
git init

//���ļ���ӵ��ݴ���
git add readme.txt 

//���ļ��ύ���ֿ�
git commit -m  ��My First Commit�� test.txt

//�鿴�ύ����Ϣ
git log
//�鿴�ύ�ļ�¼
git log --pretty=oneline
//�鿴��־��¼
git reflog



//����Զ�̵�ַ����
git remote add [����] [Զ�̵�ַ]
git remote add origin https://github.com/zgchang77/chris.git
//�鿴��ǰ����Զ�̵�ַ����
git remote -v



//������֧git branch [��֧��]
git branch hot_fix
//�鿴��֧
git branch -v
//�л���֧
git checkout hot_fix
//�鿴֮ǰ������
ll
//�ϲ���֧ git merge [�������ݵķ�֧��]

//���Բ鿴���ص�Ŀ¼
ls -la


//�ϴ�
1���ѵ�ǰĿ¼�£������仯���ļ���ӵ��ݴ���
     git  add .
2��ע��
     git commit -m "�����ύ��ע��"
3������Ŀ���͵�����
     git push 

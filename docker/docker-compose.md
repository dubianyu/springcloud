### docker compose �̳�
* ���
```text
Dockerfile �������û�����һ��������Ӧ������
Docker-Compose �������û���һ��ģ�壨YAML ��ʽ���ж���һ���������Ӧ������������Ϊһ�� project������Ŀ��
```
* ��װ
```text
����һ:
1. ��װpip���������
    sudo yum install python-pip 
    pip --version
2. ִ����������
    sudo pip install -U docker-compose
3. ���bash��ȫ����(��ʱ������)
   curl -L https://raw.githubusercontent.com/docker/compose/1.2.0/contrib/completion/bash/docker-compose > /etc/bash_completion.d/docker-compose

������:
sudo pip install docker-compose

��֤:
docker-compose --version

����(����docker-compose.yml����Ŀ¼):
docker-compose up
     
```

* ������ֹͣ
```text
����: docker-compose start
ֹͣ: docker-compose stop
```
[docker-composeʹ��](http://wiki.jikexueyuan.com/project/docker-technology-and-combat/intro.html)
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

������:
// docker Version: 18.06.1-ce
// docker-compose Version 1.23.1
wget -c https://github.com/itsccn/jpressBydocker/releases/download/jpressBydocker1.0/docker-compose -O /opt/docker-compose
wget -c https://github.com/itsccn/jpressBydocker/releases/download/jpressBydocker1.0/docker.rpm -O /opt/docker.rpm
yum install -y /opt/docker.rpm
chmod +x /opt/docker-compose
mv /opt/docker-compose /usr/local/bin/
     
```



* ������ֹͣ
```text
����: docker-compose start
ֹͣ: docker-compose stop
```
[docker-composeʹ��](http://wiki.jikexueyuan.com/project/docker-technology-and-combat/intro.html)
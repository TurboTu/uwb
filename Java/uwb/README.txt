��λƽ̨��̨��������¼
1 �޸���redis�����л���ʽʹ�� jackson2json���л�,��reids��صĲ������󵽽ӿ���
2 ΢����ϲ�����10�����񲿷ֺϲ����ϲ�������7������
   zl_alarm_save zl_coordinate�ϲ���zl_storage
   zl_permission�ϲ���zl_resources
   zl_alarm,zl_coordinate�ϲ���zl_websocket
3 ������miaƽ̨�Ĳ���ʱ��kakfa��zookeeper��ص�����jar��������

4 ����˿��б� 

fastdfs 11001
resources 11003

producer 11002 9922--Ҫ��������¶�˶˿�
websocket 11006

center 11000
status_save 11004
storage 11005

eureka 5555,5556
gateway 11007

����fastdfs producerҪ���ݻ����޸������ļ��е�IP��ַ

5 ������̨������Ļ
screen -S uwb_test ����screen 
screen -R uwb_test ���µ�¼screen
ctrl+a+d �ص�screen

6 �����������
  nginx:1.12.2
  fastdfs:trackerd storaged
  kafka:
  zookeeper
  java:jdk��jre 1.8
  mysql
  redis
  




DoitPHP 2.0 
=============================

��л��ѡ��doitphp, ����һ��������,���и�Ч,������չ��������PHP���


��װ
------------

1.��doitphp��ѹ������ѹ��,�ڽ�ѹ����ļ�����ῴ�������ļ���Ŀ¼

      doitphp/		   ��ܵ�Դ�ļ�
      tools/		   doitphp�ĸ�����������
      LICENSE              doitphp�����֤
      README               ˵���ļ�


2.����doitphp�ĸ�����������(http://hostname/doitphpPath/tools/index.php),

	Ĭ���û���:doitphp, ����:123456 
	
	Ĭ���û�����������ļ�./tools/application/config/application.php


3.�������ݿ��������ò���
    ���Ҫʹ��doitphp�ĸ����������ߴ���Model�ļ�ʱ����Model�ļ������ݱ�ʱ����Ҫ�����������ߵ������ļ����������ݿ�������Ϣ��
	�����ļ�·��Ϊ��./tools/application/config/application.php
	���������ݸ���Ϊ��Ŀ�����ӵ����ݿ⼴��
	//���ݿ����Ӳ���
	$config['db'] = array(
		'dsn' => 'mysql:host=localhost;dbname=dz',
		'username' => 'root',
		'password' => '123456',
	);


Ҫ��
------------

����Ҫ��:web���������е�PHP�汾5.1.0������,��֧��gd��չ. 
��ʾ��ַ��http://12450.xyz/mall

ԭ�ģ�http://12450.xyz/archives/code/php/2016/03/19/mall.html

Github��https://github.com/maizhenying09/mall

�ٶ����̣�https://pan.baidu.com/s/1i5Lcm6T ����: mall

apiʹ�÷���[format����Ĭ��json]:
������Ʒ��Ϣ[֧��xml��json,������Ʒ��������Ϣ]��
api.12450.xyz/goods/info?goods_id=24&format=xml
api.12450.xyz/goods/info?goods_sn=AUTOSN20160507723873&format=json
�����µ�������Ʒ[ֻ֧��json,����[goods_id��ƷID:goods_name��Ʒ����]]��
api.12450.xyz/goods/info?cat_id=4&format=json

�ǵ��ȵ�Ŀ¼include��config.inc.php�޸����ݿ�����

Ȼ�������ݿ�����

mall_with_data.sql ������

mall_without_data.sql �����ݣ�����Լ����´�����������ݣ��ǵõ�dataĿ¼�°���ǰ������ɾ�ˡ�

Ȼ��127.0.0.1/register.phpע��admin�û���

�����̨��127.0.0.1/admin

�����Ʒ�������Ʒ

��ҳ�ֲ�banner��

��bannerĿ¼���ʹ��notepad++�ȸ߼��������༭imgs_links.ini����Ҫ�ü��±���

���ص�ַ��https://notepad-plus-plus.org/download/

���û��bannerĿ¼��imgs_links.ini��������ҳ����Զ����ɣ��밴�����ӽ������á�

���׸��ַ�Ϊ';'ʱ����ʾ���Ӹ���(ע��)��������Ч��ɾ��';'

bannerͼƬ�����bannerĿ¼��,�ߴ�730x426��


ע�⣺

./include/init.php

define('ROOT',str_replace('\','/',dirname(dirname(FILE))).'/');

·���ǣ�/��������Ŀ¼���̳Ǹ�Ŀ¼/

./include/ueditor_upload_path.php

define('UPLOADROOT',str_replace($SERVER['DOCUMENT_ROOT'],'',str_replace('\','/',dirname (dirname(__FILE_))).'/'));

·���ǣ�/�̳Ǹ�Ŀ¼/

���ݿ��goods�� goods_desc������Ʒ˵��

·�����ܲ��ʺ���Ļ��� ��Ҫ�Լ���һ�£������滻һ�¾ͺ���
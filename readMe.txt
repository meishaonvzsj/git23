ʹ��Maven�ĺô���
    һ�����Խ�ÿ�������е�jar��ȡ�����ŵ����زֿ��У�����������ֻ����Դ����,������ֻ�����ñ��زֿ��е�jar����
        �ô�������ʵ��jar���ļ��й�����ά��
    ��������ʵ�ֶ�jar���ľ�ȷ��������Ҫʹ��ʲôjar������pom�ļ��н�������
    ��������ʵ�ֶ�jar����������jar�����Զ�����
    �ģ����㹤�̵Ĵ������


Maven��ʹ�ò��裺
    һ���������زֿ�(�����Ѿ��ֿ�)
    ������maven������н�ѹ��settings.xml���ͱ��زֿ����һ�飬
       �޸�settings.xml�ļ��е�<localRepository>D:/Maven/Reponsitory</localRepository>(����ָ�����زֿ��·��)
    �����޸Ŀ��������е�maven���ò���(Ϊmaven���ָ��settings.xml�ļ���·��)
    �ģ��ڿ��������д���maven����


pom:project object model

modelVersion:��ʹ�õ�object model�汾
groupId:��Ŀ�����������֯��Ψһ��ʶ����ͨ����������д
artifactId:��ĿartifactΨһ�Ļ���ַ��(����������Ŀ��/������)
package:�����ʽ
version:artifact�İ汾
name:��ʾ��Ŀ��չʾ��(ͨ����artifactId��ͬ)����maven���ɵ��ĵ���ʹ��
url:��Ŀ�ķ�����ַ����maven���ɵ��ĵ���ʹ��
description:��Ŀ����������maven���ɵ��ĵ���ʹ��
dependencies:��ʾ���������ӽڵ�dependency����Ӿ���������groupId artifactId ��version
build:��ʾbuild����
finalName:���ʱ����������
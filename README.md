SelList �б�ѡ����
=========

## Ч��Ԥ��ͼ

![](/gif/listselect.gif)

## ���ʹ����

> Step 1.���� build.gradle(Project:XXXX) �� repositories ���::

	allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}
> Step 2. Ȼ���� build.gradle(Module:app) �� dependencies ���:

	dependencies {
	       compile 'com.github.luocc:listselect:1.0'
	}

    ʹ�÷���: 
        FragmentContentActivity.startForResultActivity(this, true, "��ѡ������", strList);
    (����������󣬿�������Դ��Ȼ����и���)

## ���ڸ�����־

    v1.0 �汾                : ʵ���˻�������
    v2.0 �汾                : ��ӳ����б�ѡ���� ����ʵ�֣�

    

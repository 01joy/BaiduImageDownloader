#�ٶ�ͼƬ����������
![](https://raw.githubusercontent.com/Beeder/BaiduImageDownloader/master/BaiduImageDownloader.png)

ʹ��python3 + pyqt5 + eric6 + cx_Freeze4��ɣ���ϸ�����뿴[�ҵĲ���](http://www.bitjoy.net/2015/08/13/baidu-image-downloader-python3-pyqt5-eric6-cx_freeze4/)

#�ļ�����
__pycache__��python�����ļ�����
_eric6project��eric6��Ŀ�ļ�����
build��cx_Freeze4�������
dist��cx_Freeze4������ɵĿ�ִ���ļ�
BaiduImageDownloader.e4p��eric6��Ŀ�ļ�
BaiduImageDownloader.png�������ͼ
DownloadEngine.py��python3���߳�������
Ui_main.py��qt5���沼�ִ���
__init__.py���Զ����ɵ��ļ�����
main.py����Ŀ������
main.ui��qt gui�����ļ�
setup.py��cx_Freeze4����ű�

��Ҫ�ļ���main.py��DownloadEngine.py

#ʹ�÷���
####����Գ��

1. ���ظ���Ŀ���д��룬�ڵ�ǰ·��ִ��`python main.py`
2. ���ظ���Ŀ���д��룬����eric6��ѡ��main.py����F2ִ��

####���ࣺ

ֱ������[BaiduImageDownloader-0.1-amd64.msi](https://github.com/Beeder/BaiduImageDownloader/blob/master/dist/BaiduImageDownloader-0.1-amd64.msi?raw=true)��װ���ڰ�װĿ¼�����main.exe���С�

#��֪bug�У�

1. ����洢Ŀ¼����Ϊĳ����Ŀ¼��ͼƬд��ʧ�ܣ���Ϊ��Ŀ¼��c:/����ʽ���ᵼ������c://a.jpg�������ļ�������д��ʧ�ܣ����˸�б��/�����������Ŀ¼c:/img����ƴ��Ϊc:/img/a.jpg��ȷ��
2. �ؼ���Ϊ`У��`��ͼƬ�ߴ�Ϊ`�ش�`ʱ�����������[������JSON decode��ĳ������](http://stackoverflow.com/questions/15198426/fixing-invalid-json-escape)��
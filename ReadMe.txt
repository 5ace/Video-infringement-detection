-----ǰ��-----
��Դ��Ϊ�Ҵ����ŶӲμ�2019 CCF BDCI ��һ��������Ƶ��Ȩ��⡷�㷨�������һ�Ƚ�ʱ��ʹ�õĲ���Դ�룬������Ƶ��֡��ͼ����������ȡ��SPOC�����ۺϵȷ�����ʵ�֡����ڲ�Ʒ����ԭ�򣬺���������ƥ�����Ƶƥ���㷨��ʹ��C/C++��д���Ҳ��㹫���������½⡣

-----ʹ��˵��-----
1�������õ��ļ���caffeģ�ʹ浵�ļ�SIZE�ϴ��ڱ��������Ѿ�ɾ������ɾ��ģ�͵�·����¼���£�
	caffe/examples/cifar10/cifar10_quick_iter_4000.caffemodel
	caffe/models/bvlc_alexnet/bvlc_alexnet.caffemodel
	caffe/models/hvr2/hvr_alexnet_train_iter_5000.caffemodel���ԣ�
	caffe/models/vgg16/VGG_ILSVRC_16_layers.caffemodel

2) edit ~/.profile, add a line as below at the end of the file: 
    export PYTHONPATH=.../lib:$PYTHONPATH	
	
3������˵��
	my_video.py ��Ƶ��֡
	my_infer.py ���������ȡ
	my_eval.py  �����ȶ�
	spoc_train.py  	ѵ���������ۺ�
	spoc_test.py	���Լ������ۺ�


## ����ṹ
�����Ϊ 6 �����֣�main.py��model.py��prepro.py��parser_args.py��src �ļ����Լ� shell �ű��ļ���

- main.py������������ļ�������ģ�͵�ѵ������֤���̣�ģ�ͼ��ء�ģ�ͱ��桢ģ�������������־����ȡ�
- model.py��ģ�Ͷ���ģ�飬������ģ�ͼ���ͼ��������ģ�ʹ����뵽�����loss, logits���Ĵ������̡�
- prepro.py�����ݴ���ģ�飬�����ı����еľ��Ӵ����ģ����Ҫ�� tensor��������ͬ����� processor Ԥ��������
- parser_args.py��ͳһ���ó��������ļ���
- src ��transfomers ���Դ�����ļ��������Ѿ���װ�õĸ���ģ���࣬�����࣬������һ�ڿγ̲��漰����Ĵ��롣
- �ű��ļ���train.sh��eval.sh��ѵ���Ͳ��ԵĽű��ļ�����һ�����С�
- ner_prep.py��NER ���������Ԥ����ű���


## ģ��ѵ��������

ѵ����
```
task_output_name�Ǳ���ѵ����������·��
sh train.sh <task_output_name>
```


������
```
task_output_name�Ǳ���ѵ����������·��
sh eval.sh <task_output_name>
```

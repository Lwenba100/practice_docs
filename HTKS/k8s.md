K8s ��Ⱥ����


1.TiDB-on-k8s

#ʹ�ù��Ĳ��𷽷���
     (1) TiDB�����ṩ��docker-compose�ļ�תΪk8s֧���ļ�������kompose���ߣ� ������k8s��֧�ֱ�����̬����洢�ռ䡣
     ��2��ʹ��TiDB�ṩ��tidb-operator��������yaml�ļ������ⲻ�ܳɹ�����helm��װ(yaml�ļ����﷨����)���ٷ��Ŷ�Ҳ�ظ�������������߻���̫���죬���ǵļƻ�����TiDB��k8s�ϻ���Ҫ���ο�����
    ��3��ʹ��git��tidb-on-k8s��Ŀ�����ڰ汾ԭ�򣬰�װ������һֱ����bug,�������޸�yaml�ļ�������Ҳ����ͨ�����⡣����ͨ��������Ҫ�Ķ�k8s��Ⱥ�����ã�û�г��ԡ�ʹ�����°汾�ľ��񻹻��������Tikv���񱨣�����ϵͳ����ļ�������

#�ɿӼ�¼��
    ��1����̬����洢�ռ䣺TiDB������K8s�ϣ�һ�������Ҵ洢��(PV)��ʽ�洢������������ʹ�ñ��ش��̽��д洢(local host)��k8s��Ŀǰ1.9�汾�в�֧�ֱ��ش洢��̬���䣬���´���TiDBʱ��������洢ʱ��PVC����Ҫ�Լ������ֶ������ô洢�ռ䣨PV���������ʹ�ñ��ش洢�Ļ����Զ�̬��������䡣������Ҫ����洢�ռ䵼�²����Զ�����
    ��2���汾���⣺������洢�ռ�Ϊָ���ô洢�ռ䣬������������ֻ�ܹ���ĳ̨���������ܷ���ٿ����ݡ�����Ҳ�������⣬�������ϵ����ӵİ汾����ʹ�����µģ������ڹ�ȥ�ܳ�ʱ�䣬TiDB������һЩ���£��������Ͻ̳̰�װ����bug��
     ��3��k8sͨ�����⣺����û�п���kube-dns����pd,tikv�����������etcd�ĵ�ַ�޷����������¾������������С�ͬʱ�������Ҳ������tensorflow�ֲ�ʽ-on-k8s���������ϡ�

2.tensorflow-on-k8s
#����
     

#��
    ��1��ͨ�����⣺��TiDBһ�������ڴ����⡣
##��������Ӧ��������ʶ��
Сѧ��ʵѵ����Ŀǰ������һ��Android Stdio���̣�
* Camera_01 : ʵ���˸��ݹ����Զ��������ȵ���������ͷ
* Camera_02_light : ʵ����ʹ�ù��߸�Ӧ����֪��ǿ���Զ�������Ļ����
* Camera_03 ���Ƕ������������̵Ĵ���ķ�װ����ʵ��������ͷ�Զ����⹦��
* Camera_04_face_detection ��ʵ����Androidϵͳ�Դ���������⹦�ܣ���Ч��̫��

---

###Camera_01
- ʹ��Android�ڲ���Cameraʵ�������ģ�Camera�����open������ָ����ǰ�û��������ͷ��SurfaceView����ƬԤ��ʱ����ʾ��takePicture������
- ʹ��SensorEventListenerʵ�ֹ��ߴ�������ǿ��ֵ�ı�ļ�����ͨ��onSensorChanged������ȡ�����ڵĹ�ǿ
- setBrightness��getBrightness�ֱ�����������Ļ���Ⱥ͸ı���Ļ����

��ʵԭ����Camera_01ֻʵ�������Ĺ��ܣ����߸�Ӧ����Ļ���ȵĸı��Ǻ�������ȥ�ġ�

###Camera_02_light
- ʹ��SensorEventListenerʵ�ֹ��ߴ�������ǿ��ֵ�ı�ļ�����ͨ��onSensorChanged������ȡ�����ڵĹ�ǿ
- setBrightness��getBrightness�ֱ�����������Ļ���Ⱥ͸ı���Ļ����
- �������ı��ؼ��ֱ�������ʾ���������ȡ�������ֵ����Ļ����ֵ

ע����Ļ����ֵ��ΧΪ��0-255

###Camera_03
- com.camera.AzCamera ʵ������ͷ����
- com.light.AzChangeSizeByLight ʵ�ָı�SurfaceViewԤ�����С�Ĺ��ܣ��������հ׵Ĳ��⹦�ܣ�
- com.light.AzLight ʵ�ֹ��߸�Ӧ����
- com.log.AzLog ��Ҫ��Android���Խ׶����ͳһTag����־

���DemoĿǰ��δ��ȫ��ɣ�Setting�����Save���涼û��ʵ�֡�

###Camera_04_face_detection
- ʹ��Android�Դ���ϵͳAPI FaceDetectionʵ����һ���������

������������㷨��ʶ����������۾���Ȼ�������ۼ�ľ���Ϊ�߳�����ֻ�۾�Ϊ���Ļ�һ�������Ρ�
����Ϊ�򵥣�����Ч��ʮ�ֲ��á�
